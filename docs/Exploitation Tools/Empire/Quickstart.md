## Initial Setup

Run the **./setup/install.sh** script. This will install the few dependencies and run the **./setup/setup_database.py** script. The setup_database.py file contains various setting that you can manually modify, and then initializes the ./data/empire.db backend database. No additional configuration should be needed- hopefully everything works out of the box.

Running `./empire` will start Empire, and `./empire --debug` will generate a verbose debug log at .**/empire.debug**. Running `./empire --debug 2` will provide verbose output to empire console. The included **./setup/reset.sh** will reset/reinitialize the database and launch Empire in debug mode. There's also a detailed "Empire Tips and Tricks" [post up here](http://enigma0x3.net/2015/08/26/empire-tips-and-tricks/).


## Main Menu
Once you hit the main menu, you'll see the number of active agents, listeners, and loaded modules.

[[/Images/empire_main_menu.png|align=center]]

The **help** command should work for all menus, and almost everything that can be tab-completable is (menu commands, agent names, local file paths where relevant, etc.).

You can ctrl+C to rage quit at any point. Starting Empire back up should preserve existing communicating agents, and any existing listeners will be restarted (as their config is stored in the sqlite backend database).

## Listeners 101
The first thing you need to do it set up a local listener. The **listeners** command will jump you to the listener management menu. Any active listeners will be displayed, and this information can be redisplayed at any time with the **list** command. The `uselistener` command will allow you to select the type of listener. Hitting TAB after this command will show all available listener types. The info command will display the currently set listener options.

[[/Images/empire_listeners_menu.png|align=center]]

The info command will display the currently configured listener options. Set your host/port by doing something like set Host http://192.168.52.142:8081. This is tab-completable, and you can also use domain names here). The port will automatically be pulled out, and the backend will detect if you're doing a HTTP or HTTPS listener. For HTTPS listeners, you must first set the CertPath to be a local .pem file. The provided **./setup/cert.sh** script will generate a self-signed cert and place it in **./data/empire.pem**.

Set optional and WorkingHours, KillDate, DefaultDelay, and DefaultJitter for the listener, as well as whatever name you want it to be referred to as. You can then type **execute** to start the listener. If the name is already taken, a nameX variant will be used, and Empire will alert you if the port is already in use.

## Stagers 101
The staging process is described [[here|Staging]].

Empire implements various stagers in a modular format in **./lib/stagers/* **. These include dlls, macros, one-liners, and more. To use a stager, from the main, listeners, or agents menu, use usestager [tab] to tab-complete the set of available stagers, and you'll be taken to the individual stager's menu. The UI here functions similarly to the post module menu, i.e set/unset/info and generate to generate the particular output code.

For UserAgent and proxy options, default uses the system defaults, none clears that option from being used in the stager, and anything else is assumed to be a custom setting (note, this last bit isn't properly implemented for proxy settings yet). From the Listeners menu, you can run the **launcher [listener ID/name]** alias to generate the stage0 launcher for a particular listener (this is the stagers/launcher module in the background). This command can be run from a command prompt on any machine to kick off the staging process.

## Agents 101
You should see a status message when an agent checks in (i.e. [+] Initial agent CGUBKC1R3YLHZM4V from 192.168.52.168 now active). Jump to the Agents menu with **agents**. Basic information on active agents should be displayed. Various commands can be executed on specific agent IDs or **all** from the agent menu, i.e. **kill all**. To interact with an agent, use **interact AGENT_NAME**. Agent names should be tab-completable for all commands.

[[/Images/empire_agent_checkin.png|align=center]]

In an Agent menu, **info** will display more detailed agent information, and help will display all agent commands. If a typed command isn't resolved, Empire will try to interpret it as a shell command (like ps). You can **cd** directories, **upload/download** files, and **rename NEW_NAME**.

For each registered agent, a **./downloads/AGENT_NAME/** folder is created (this folder is renamed with an agent rename). An ./agent.log is created here with timestamped commands/results for agent communication. Downloads/module outputs are broken out into relevant folders here as well.

When you're finished with an agent, use **exit** from the Agent menu or **kill NAME/all** from the Agents menu. You'll get a red notification when the agent exits, and the agent will be removed from the interactive list after.

## Modules 101
To see available modules, type **usemodule [tab]**. To search module names/descriptions, use **searchmodule privesc** and matching module names/descriptions will be output.

To use a module, for example share finder from PowerView, type **usemodule situational_awareness/network/sharefinder** and press enter. info will display all current module options.

[[/Images/empire_module_menu.png|align=center]]

To set an option, like the domain for sharefinder, use **set Domain testlab.local**. The Agent argument is always required, and should be auto-filled from jumping to a module from an agent menu. You can also **set Agent [tab]** to tab-complete an agent name. **execute** will task the agent to execute the module, and **back** will return you to the agent's main menu. Results will be displayed as they come back.

## Scripts
In addition to formalized modules, you are able to simply import and use a .ps1 script in your remote empire agent. Use the **scriptimport ./path/** command to import the script. The script will be imported and any functions accessible to the script will now be tab completable using the "scriptcmd" command in the agent. This works well for very large scripts with lots of functions that you do not want to break into a module.