# Pentest Tools

![](logo.png)

The tools listed below are commonly used in penetration testing, and the tool catalog is referenced from Kali Tools, most of which are open source software. The project long-term supplementary update QAQ


## TODO

*   [x]  Directory 
*   [ ]  Browser bookmarks
*   [ ]  Tools Usage
*   [x]  Virtual machine - [Windows11 Penetration Suite Toolkit](https://github.com/arch3rPro/Pentest-Windows)

## List
* [Information Gathering](#information-gathering)
* [Vulnerability Analysis](#vulnerability-analysis)
* [Web Applications](#web-applications)       
* [Database Assessment](#database-assessment)
* [Password Attacks](#password-attacks)
* [Wireless Attacks](#Wireless-Attacks)
* [Reverse Engineering](#Reverse-Engineering)
* [Exploitation Tools](#exploitation-tools)
* [Sniffing & Spoofng](#Sniffing-&-Spoofng)
* [Maintaining Access](#maintaining-access)
* [Golang Sec Tools](#Golang-Sec-Tools)
* [Reporting Tools](#reporting-tools)
* [Social Engineering](#Social-Engineering)
* [Code Audit](#code-audit) 
* [Port Forwarding & Proxies](#port-forwarding--proxies)
* [DevSecOps](#DevSecOps)
* [RootKit](#RootKit)
* [Pentesting Distribution](#Pentesting-Distribution)
* [Cyber Range](#Cyber-Range)
   
### Information Gathering

#### Domain Name

* [whois](https://docs.microsoft.com/en-us/sysinternals/downloads/whois) - Windows Whois performs the registration record for the domain name or IP address that you specify. ![](svg/Windows.svg)

#### Subdomain

* [subDomainsBrute](https://github.com/lijiejie/subDomainsBrute) - A fast sub domain brute tool for pentesters ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [ksubdomain](https://github.com/boy-hack/ksubdomain) - Subdomain enumeration tool, asynchronous dns packets, use pcap to scan 1600,000 subdomains in 1 second ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [OneForAll](https://github.com/shmilylty/OneForAll) - 👊 OneForAll is a powerful subdomain integration tool ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [LayerDomainFinder](https://github.com/euphrat1ca/LayerDomainFinder) - a subdomains enumeration tool by Layer ![](svg/Windows.svg)
* [ct](https://github.com/knownsec/ct) - Collect information tools about the target domain.

#### Google Hacking

* [GHDB](https://www.exploit-db.com/google-hacking-database/) - Google Hack Database  ![](svg/chrome.svg)
* [SearchDiggity](http://www.bishopfox.com/resources/tools/google-hacking-diggity/attack-tools/) - SearchDiggity 3.1 is the primary attack tool of the Google Hacking Diggity Project ![](svg/Windows.svg)
* [Katana](https://github.com/adnane-X-tebbaa/Katana) - A Python Tool For google Hacking ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [uDork](https://github.com/m3n0sd0n4ld/uDork) - uDork is a script written in Bash Scripting that uses advanced Google search techniques to obtain sensitive information in files or directories, find IoT devices, detect versions of web applications, and so on. ![](svg/linux.svg)![](svg/mac.svg)
* [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) - GooFuzz is a tool to perform fuzzing with an OSINT approach, managing to enumerate directories, files, subdomains or parameters without leaving evidence on the target's server and by means of advanced Google searches (Google Dorking). ![](svg/linux.svg)![](svg/mac.svg)
* [Pagodo](https://github.com/opsdisk/pagodo) - pagodo (Passive Google Dork) - Automate Google Hacking Database scraping and searching . ![](svg/linux.svg)![](svg/mac.svg)
* [Google-Dorks](https://github.com/Proviesec/google-dorks) - Useful Google Dorks for WebSecurity and Bug Bounty

#### Github 

* [GitHacker](https://github.com/WangYihang/GitHacker) - 🕷️ A Git source leak exploit tool that restores the entire Git repository, including data from stash, for white-box auditing and analysis of developers' mind. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [GitGraber](https://github.com/hisxo/gitGraber) - gitGraber is a tool developed in Python3 to monitor GitHub to search and find sensitive data in real time for different online services. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [GitMiner](https://github.com/UnkL4b/GitMiner) - Tool for advanced mining for content on Github. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Gitrob](https://github.com/michenriksen/gitrob) - Reconnaissance tool for GitHub organizations. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [GitGot](https://github.com/BishopFox/GitGot) Semi-automated, feedback-driven tool to rapidly search through troves of public data on GitHub for sensitive secrets.
* [GitDump](https://github.com/Ebryx/GitDump) - A pentesting tool that dumps the source code from .git even when the directory traversal is disabled

#### SVN

* [svnExploit](https://github.com/admintony/svnExploit) - Support for SVN source code disclosure of full version and Dump it. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [SvnHack](https://github.com/callmefeifei/SvnHack) - SvnHack is a SVN folder disclosure exploit. :lock:
 
#### Port Scan

* [Nmap | Zenmap](https://nmap.org/) - Free and open source utility for network discovery and security auditing
* [Masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously
* [Ports](https://github.com/nixawk/pentest-wiki/blob/master/3.Exploitation-Tools/Network-Exploitation/ports_number.md) - Common service ports and exploitations
* [Goby](https://gobies.org/) - Attack surface mapping
* [Goscan](https://github.com/marco-lancini/goscan) - Interactive Network Scanner
* [NimScan](https://github.com/elddy/NimScan) - 🚀 Fast Port Scanner 🚀
* [RustScan](https://github.com/RustScan/RustScan) - 🤖 The Modern Port Scanner 🤖
* [TXPortMap](https://github.com/4dogs-cn/TXPortMap) - Port Scanner & Banner Identify From TianXiang
* [Scaninfo](https://github.com/redtoolskobe/scaninfo) - fast scan for redtools
* [SX](https://github.com/v-byte-cpu/sx) - 🖖 Fast, modern, easy-to-use network scanner ![](svg/linux.svg)

#### OSINT

* [theHarvester](https://github.com/laramies/theHarvester)- E-mails, subdomains and names Harvester - OSINT
* [SpiderFoot](https://github.com/smicallef/spiderfoot) - SpiderFoot automates OSINT for threat intelligence and mapping your attack surface.
* [Recon-ng](https://github.com/lanmaster53/recon-ng) - Open Source Intelligence gathering tool aimed at reducing the time spent harvesting information from open sources. ![](svg/linux.svg)
* [FOCA](https://github.com/ElevenPaths/FOCA) - Tool to find metadata and hidden information in the documents. 
* [Amass](https://github.com/OWASP/Amass) - In-depth Attack Surface Mapping and Asset Discovery
* [Censys-subdomain-finder](https://github.com/christophetd/censys-subdomain-finder) - Perform subdomain enumeration using the certificate transparency logs from Censys.
* [EmailHarvester](https://github.com/maldevel/EmailHarvester) - Email addresses harvester
* [Finalrecon](https://github.com/thewhiteh4t/FinalRecon) - The Last Web Recon Tool You'll Need.
* [LittleBrother](https://github.com/lulz3xploit/LittleBrother) - Information gathering (OSINT) on a person (EU)
* [Octosuite](https://github.com/rly0nheart/octosuite) - Advanced Github OSINT Framework
* [Kunyu](https://github.com/knownsec/Kunyu) - Kunyu, more efficient corporate asset collection
* [Glass](https://github.com/s7ckTeam/Glass) - OSINT Framework with Fofa/ZoomEye/Shodan/360 API
* [BBOT](https://github.com/blacklanternsecurity/bbot) - OSINT automation for hackers.
* [octosuite](https://github.com/bellingcat/octosuite) - Advanced Github OSINT Framework


### Phishing
* [gophish](https://github.com/gophish/gophish) - Open-Source Phishing Toolkit
* [AdvPhishing](https://github.com/Ignitetch/AdvPhishing) - This is Advance Phishing Tool ! OTP PHISHING
* [SocialFish](https://github.com/UndeadSec/SocialFish) - Educational Phishing Tool & Information Collector
* [Zphisher](https://github.com/htr-tech/zphisher) - An automated phishing tool with 30+ templates. This Tool is made for educational purpose only ! Author will not be responsible for any misuse of this toolkit !
* [Nexphisher](https://github.com/htr-tech/nexphisher) - Advanced Phishing tool for Linux & Termux
 
### Vulnerability Analysis

#### Fuzzing

#### Vulnerability Scanner
* [Struts-Scan](https://github.com/Lucifer1993/struts-scan) - Struts2 vulnerability detection and utilization tools
* [Nikto](https://github.com/sullo/nikto) - Nikto is an Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items
* [W3af](https://github.com/andresriancho/w3af/) - Web application attack and audit framework, the open source web vulnerability scanner
* [Openvas](http://www.openvas.org/) - The world's most advanced Open Source vulnerability scanner and manager
   * [Openvas Docker](https://github.com/mikesplain/openvas-docker)
* [Archery](https://github.com/archerysec/archerysec) - Open Source Vulnerability Assessment and Management helps developers and pentesters to perform scans and manage vulnerabilities
* [Taipan](https://github.com/enkomio/Taipan) - Web application vulnerability scanner 
* [Arachni](https://github.com/Arachni/arachni) - Web Application Security Scanner Framework
* [Nuclei](https://github.com/projectdiscovery/nuclei) - Fast and customizable vulnerability scanner based on simple YAML based DSL.
* [Xray](https://github.com/chaitin/xray) - A passive-vulnerability-scanner Tool.  ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Super-Xray](https://github.com/4ra1n/super-xray) - Web Vulnerability Scanner XRAY GUI Starter ![](svg/Windows.svg)
* [SiteScan](https://github.com/kracer127/SiteScan) - AllinOne Website Information Gathering Tools for pentest.
* [Banli](Github.com/Goqi/Banli) - High-risk asset identification and high-risk vulnerability scanner. ![](svg/Windows.svg)
* [vscan](https://github.com/veo/vscan) -  Open Source Vulnerability Scanner.  ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Wapiti](https://github.com/wapiti-scanner/wapiti) - Web vulnerability scanner written in Python3.
* [Scaninfo](https://github.com/redtoolskobe/scaninfo) - fast scan for redtools
* [osv-scanner](https://github.com/google/osv-scanner) - Vulnerability scanner written in Go which uses the data provided by https://osv.dev

### Web Applications

####  CMS & Framwork Identification

* [AngelSword](https://github.com/Lucifer1993/AngelSword) - CMS vulnerability detection framework :lock:
* [WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Next generation web scanner ![](svg/linux.svg)
* [Wappalyzer](https://github.com/AliasIO/Wappalyzer) - Cross-platform utility that uncovers the technologies used on websites ![](svg/chrome.svg)
* [Whatruns](https://www.whatruns.com/) - A free browser extension that helps you identify technologies used on any website at the click of a button (Just for chrome)![](svg/chrome.svg)
* [WhatCMS](https://github.com/HA71/WhatCMS) - CMS Detection and Exploit Kit based on Whatcms.org API
* [CMSeeK](https://github.com/Tuhinshubhra/CMSeeK) - CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and over 180 other CMSs
* [EHole](https://github.com/EdgeSecurityTeam/EHole) - CMS Detection for RedTeam ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)

> Online Tools

* [Yunsee](http://www.yunsee.cn/finger.html) - Online website for to find the CMS footprint
* [Bugscaner](http://whatweb.bugscaner.com/look/) - A simple online fingerprint identification system that supports hundreds of cms source code recognition
* [WhatCMS online](https://whatcms.org/) - CMS Detection and Exploit Kit website Whatcms.org 
* [TideFinger](http://finger.tidesec.com/) -  Fingerprinter Tool from TideSec Team
* [360finger-p](https://fp.shuziguanxing.com/) - Fingerprinter Tool from 360 Team

#### Web Applications Proxies
* [Burpsuite](https://portswigger.net/) - Burpsuite is a graphical tool for testing Web application security ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [ZAP](https://github.com/zaproxy/zaproxy) One of the world’s most popular free security tools ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Mitmproxy](https://github.com/mitmproxy/mitmproxy) - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Broxy](https://github.com/rhaidiz/broxy) - An HTTP/HTTPS intercept proxy written in Go. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Hetty](https://github.com/dstotijn/hetty) - An HTTP toolkit for security research. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)

#### web browser extension

* [Hack-Tools](https://github.com/LasCC/Hack-Tools) - The all-in-one Red Team extension for Web Pentester 🛠

#### Web Crawlers & Directory Brute Force
* [Dirbrute](https://github.com/Xyntax/DirBrute) - Multi-thread WEB directory blasting tool (with dics inside) :lock:
* [ffuf](https://github.com/ffuf/ffuf) - Fast web fuzzer written in Go. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Dirbuster](https://sourceforge.net/projects/dirbuster/) - DirBuster is a multi threaded java application designed to brute force directories and files names on web/application servers. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Dirsearch](https://github.com/maurosoria/dirsearch) - Web path scanner. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [Gobuster](https://github.com/OJ/gobuster) Directory/File, DNS and VHost busting tool written in Go. ![](svg/Windows.svg)![](svg/linux.svg)![](svg/mac.svg)
* [WebPathBrute](https://github.com/7kbstorm/7kbscan-WebPathBrute) - Web path Bruter. ![](svg/Windows.svg)
* [wfuzz](https://github.com/xmendez/wfuzz) - Web application fuzzer ![](svg/Windows.svg)![](svg/linux.svg)
* [Dirmap](https://github.com/H4ckForJob/dirmap) - An advanced web directory & file scanning tool that will be more powerful than DirBuster, Dirsearch, cansina, and Yu Jian.


#### Docker Scanners

* [Fuxi-Scanner](https://github.com/jeffzh3ng/Fuxi-Scanner) - open source network security vulnerability scanner, it comes with multiple functions. ![](svg/Docker.svg)
* [Xunfeng](https://github.com/ysrc/xunfeng) - The patrol is a rapid emergency response and cruise scanning system for enterprise intranets. ![](svg/Docker.svg)
* [WebMap](https://github.com/SabyasachiRana/WebMap) - Nmap Web Dashboard and Reporting. ![](svg/Docker.svg)
* [Pentest-Collaboration-Framework](https://gitlab.com/invuls/pentest-projects/pcf) - Opensource, cross-platform and portable toolkit for automating routine processes when carrying out various works for testing!

 
### Database Assessment

* [Enumdb](https://github.com/m8sec/enumdb) - Relational database brute force and post exploitation tool for MySQL and MSSQL
* [MDUT](https://github.com/SafeGroceryStore/MDUT) - Multiple Database Utilization Tools
* [Sylas](https://github.com/Ryze-T/Sylas) - Multiple Database Exploitation Tools
* [ODAT](https://github.com/quentinhardy/odat) - Oracle Database Attacking Tool
* [MSDAT](https://github.com/quentinhardy/msdat) - Microsoft SQL Database Attacking Tool

### Password Attacks

* [Hydra](https://github.com/vanhauser-thc/thc-hydra) - Hydra is a parallelized login cracker which supports numerous protocols to attack
* [Medusa](http://foofus.net/goons/jmk/medusa/medusa.html) - Medusa is intended to be a speedy, massively parallel, modular, login brute-forcer
* [Sparta](https://github.com/SECFORCE/sparta) - Network Infrastructure Penetration Testing Tool. ![](svg/linux.svg)
* [Hashcat](https://github.com/hashcat/hashcat) - World's fastest and most advanced password recovery utility
* [Patator](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer, with a modular design and a flexible usage.
* [HackBrowserDat](https://github.com/moonD4rk/HackBrowserData) - Decrypt passwords/cookies/history/bookmarks from the browser
* [John](https://github.com/openwall/john) - John the Ripper jumbo - advanced offline password cracker, which supports hundreds of hash and cipher types, and runs on many operating systems, CPUs, GPUs, and even some FPGAs.

#### Wordlists

* [wordlists](https://github.com/trickest/wordlists/) - Real-world infosec wordlists, updated regularly
* [psudohash](https://github.com/t3l3machus/psudohash) - Password list generator that focuses on keywords mutated by commonly used password creation patterns
* [wister](https://github.com/cycurity/wister) - A wordlist generator tool, that allows you to supply a set of words, giving you the possibility to craft multiple variations from the given words, creating a unique and ideal wordlist to use regarding a specific target.

### Wireless Attacks

#### Wireless Tools

* [Fern Wifi cracker](https://github.com/savio-code/fern-wifi-cracker) - Fern-Wifi-Cracker is designed to be used in testing and discovering flaws in ones own network with the aim of fixing the flaws detected
    
### Reverse Engineering

* [Ollydbg](http://www.ollydbg.de/) - OllyDbg is a 32-bit assembler level analysing debugger for Microsoft Windows

### Exploitation Tools

#### Vulnerability Search

* [SPLOITUS](https://sploitus.com) - Sploitus is а convenient central place for identifying the newest exploits and finding attacks that exploit known vulnerabilities
* [SearchSploit](https://github.com/offensive-security/exploitdb) - The official Exploit Database repository
* [Getsploit](https://github.com/vulnersCom/getsploit) - Command line utility for searching and downloading exploits
* [Houndsploit](https://github.com/nicolas-carolo/houndsploit) - An advanced graphical search engine for Exploit-DB
* [OSV](https://osv.dev/) - Open source vulnerability DB and triage service.

#### Cross-site Scripting（XSS）

* [BeeF](https://github.com/beefproject/beef) - The Browser Exploitation Framework Project
* [BlueLotus_XSSReceiver](https://github.com/firesunCN/BlueLotus_XSSReceiver) - XSS Receiver platform without SQL
* [XSStrike](https://github.com/s0md3v/XSStrike) - Most advanced XSS scanner.
* [xssor2](https://github.com/evilcos/xssor2) - XSS'OR - Hack with JavaScript.
* [Xsser-Varbaek](https://github.com/Varbaek/xsser) - From XSS to RCE 2.75 - Black Hat Europe Arsenal 2017 + Extras
* [Xsser-Epsylon](https://github.com/epsylon/xsser) - Cross Site "Scripter" (aka XSSer) is an automatic framework  to detect, exploit and report XSS vulnerabilities in web-based applications.
* [Xenotix](https://github.com/ajinabraham/OWASP-Xenotix-XSS-Exploit-Framework) - An advanced Cross Site Scripting (XSS) vulnerability detection and exploitation framework
* [PwnXSS](https://github.com/pwn0sec/PwnXSS) - PwnXSS: Vulnerability (XSS) scanner exploit
* [dalfox](https://github.com/hahwul/dalfox) - 🌙🦊 DalFox is an powerful open source XSS scanning tool and parameter analyzer, utility
* [ezXSS](https://github.com/ssl/ezXSS) - ezXSS is an easy way for penetration testers and bug bounty hunters to test (blind) Cross Site Scripting.

####  Sql Injection

* [Sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool 
* [SSQLInjection](https://github.com/shack2/SuperSQLInjectionV1) - SSQLInjection is a SQL injection tool , support Access/MySQL/SQLServer/Oracle/PostgreSQL/DB2/SQLite/Informix Database. 
* [Jsql-injection](https://github.com/ron190/jsql-injection) jSQL Injection is a Java application for automatic SQL database injection.
* [NoSQLMap](https://github.com/codingo/NoSQLMap) - Automated NoSQL database enumeration and web application exploitation tool.
* [Sqlmate](https://github.com/s0md3v/sqlmate) - A friend of SQLmap which will do what you always expected from SQLmap
* [SQLiScanner](https://github.com/0xbug/SQLiScanner) - Automatic SQL injection with Charles and sqlmap api
* [sql-injection-payload-list](https://github.com/payloadbox/sql-injection-payload-list) - 🎯 SQL Injection Payload List
* [Advanced-SQL-Injection-Cheatsheet](https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet) - A cheat sheet that contains advanced queries for SQL Injection of all types.

#### Command Injection

* [Commix](https://github.com/commixproject/commix) - Automated All-in-One OS command injection and exploitation tool

#### File Include

* [LFIsuite](https://github.com/D35m0nd142/LFISuite) - Totally Automatic LFI Exploiter (+ Reverse Shell) and Scanner
* [Kadimus](https://github.com/P0cL4bs/Kadimus) - Kadimus is a tool to check sites to lfi vulnerability , and also exploit it
* [Shellfire](https://github.com/unix-ninja/shellfire) - Exploitation shell for exploiting LFI, RFI, and command injection vulnerabilities
* [LFIter2](https://github.com/3mrgnc3/LFIter2) - LFIter2 Local File Include (LFI) Tool - Auto File Extractor & Username Bruteforcer
* [FDsploit](https://github.com/chrispetrou/FDsploit) - File Inclusion & Directory Traversal fuzzing, enumeration & exploitation tool.

#### File Upload vulnerability

* [Fuxploider](https://github.com/almandin/fuxploider) - File upload vulnerability scanner and exploitation tool

#### XML External Entity Attack（XXE）

* [XXEinjector](https://github.com/enjoiz/XXEinjector) - Tool for automatic exploitation of XXE vulnerability using direct and different out of band methods
* [Oxml_xxe](https://github.com/BuffaloWill/oxml_xxe) - A tool for embedding XXE/XML exploits into different filetypes

#### Cross-site request forgery （CSRF）

* [Deemon](https://github.com/tgianko/deemon/) - Deemon is a tool to detect CSRF in web application

#### Deserialization exploit framework

* [Ysomap](https://github.com/wh1t3p1g/ysomap) - A helpful Java Deserialization exploit framework.

#### Exploit Framework

* [POC-T](https://github.com/Xyntax/POC-T) - Pentest Over Concurrent Toolkit
* [Pocsuite3](https://github.com/knownsec/pocsuite3) - pocsuite3 is an open-sourced remote vulnerability testing framework developed by the Knownsec 404 Team.
* [Metasploit](https://github.com/rapid7/metasploit-framework) - The world’s most used penetration testing framework
* [Venom](https://github.com/r00t-3xp10it/venom) - Shellcode generator/compiler/handler (metasploit)
* [Empire](https://github.com/BC-SECURITY/Empire) - Empire is a PowerShell and Python post-exploitation agent
* [Starkiller](https://github.com/BC-SECURITY/Starkiller) - Starkiller is a Frontend for PowerShell Empire.
* [Koadic](https://github.com/zerosum0x0/koadic) - Koadic C3 COM Command & Control - JScript RAT
* [Viper](https://github.com/FunnyWolf/Viper) - metasploit-framework UI manager Tools
* [MSFvenom-gui](https://github.com/ssooking/msfvenom-gui) - gui tool to create normal payload by msfvenom
* [Afrog](https://github.com/zan8in/afrog) -  A tool for finding vulnerabilities

#### Machine Learning

* [DeepExploit](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/DeepExploit) - Fully automatic penetration test tool using Machine Learning
* [GyoiThon](https://github.com/gyoisamurai/GyoiThon) - GyoiThon is a growing penetration test tool using Machine Learning
* [Generator](https://github.com/13o-bbr-bbq/machine_learning_security/tree/master/Generator) - Fully automatically generate numerous injection codes for web application assessment

#### Automate
* [AutoSploit](https://github.com/NullArray/AutoSploit) - Automated Mass Exploiter
* [WinPwn](https://github.com/SecureThisShit/WinPwn) - Automation for internal Windows Penetrationtest / AD-Security

### Sniffing & Spoofng

* [WireShark](https://github.com/wireshark/wireshark) - Wireshark is a network traffic analyzer, or "sniffer", for Unix and Unix-like operating systems.
* [Cain & able](http://www.oxid.it/cain.html) - Cain & Abel is a password recovery tool for Microsoft Operating Systems. 

### Maintaining Access

#### Shell

* [Goshell](https://github.com/eze-kiel/goshell) - Generate reverse shells in command line with Go !
* [Print-My-Shell](https://github.com/sameera-madushan/Print-My-Shell) - Python script wrote to automate the process of generating various reverse shells.
* [Reverse-shell-generator](https://github.com/0dayCTF/reverse-shell-generator) - Hosted Reverse Shell generator with a ton of functionality. -- (Great for CTFs)
* [Girsh](https://github.com/nodauf/Girsh) - Automatically spawn a reverse shell fully interactive for Linux or Windows victim
* [Blueshell](https://github.com/whitehatnote/BlueShell) -  Generate a reverse shells for RedTeam 
* [Clink](http://mridgers.github.io/clink/) - Powerful Bash-style command line editing for cmd.exe
* [Natpass](https://github.com/jkstack/natpass) - A new RAT Tools, Support Web VNC and Webshell
* [Platypus](https://github.com/WangYihang/Platypus) 🔨 A modern multiple reverse shell sessions manager written in go
* [shells](https://github.com/4ndr34z/shells/) - Script for generating revshells
* [Reverse_ssh](https://github.com/NHAS/reverse_ssh) - SSH based reverse shell


#### Web Shell

* Chopper
> Tips: The tool comes from the network, no backdoor verification, please choose it on yourself......

> Link: https://pan.baidu.com/s/1VnXkoQU-srSllG6JaY0nTA  Password: v71d

* [AntSword](https://github.com/AntSwordProject/antSword) : [Document](https://doc.u0u.us/zh-hans/index.html) - AntSword is a cross-platform website management toolkit

* [CKnife](https://github.com/Chora10/Cknife) - The cross platform webshell tool in java
> Tips: The tool comes from the network, no backdoor verification, please choose it on yourself...... 

> Link: https://pan.baidu.com/s/1QZrnWU7DUuJhiXl7u1kELw  Password: hjrh   

* [Behinder](https://github.com/rebeyond/Behinder) - dynamic binary encryption webshell management client 
* [Godzilla](https://github.com/BeichenDream/Godzilla) - a Java tool to encrypt network traffic
* [Skyscorpion](https://github.com/shack2/skyscorpion) - Modified version of Behinder.
* [PyShell](https://github.com/JoelGMSec/PyShell) - Multiplatform Python WebShell.
* [Weevely3](https://github.com/epinna/weevely3) - Weaponized web shell.
* [Bantam](https://github.com/gellin/bantam) - A PHP backdoor management and generation tool/C2 featuring end to end encrypted payload streaming designed to bypass WAF, IDS, SIEM systems.
* [Awsome-Webshells](https://github.com/abhinavprasad47/Awsome-Webshells) - Collection of reverse shells.

#### Privilege Escalation Auxiliary

* [windows-exploit-suggester](https://github.com/GDSSecurity/Windows-Exploit-Suggester) - This tool compares a targets patch levels against the Microsoft vulnerability database in order to detect potential missing patches on the target
* [Windows-kernel-exploits](https://github.com/SecWiki/windows-kernel-exploits) - windows-kernel-exploits
* [linux-exploit-suggester-2](https://github.com/jondonas/linux-exploit-suggester-2) - Next-Generation Linux Kernel Exploit Suggester
* [Linux-kernel-exploits](https://github.com/SecWiki/linux-kernel-exploits) - linux-kernel-exploits Linux
* [BeRoot](https://github.com/AlessandroZ/BeRoot) - Privilege Escalation Project - Windows / Linux / Mac
* [PE-Linux](https://github.com/WazeHell/PE-Linux) - Linux Privilege Escalation Tool By WazeHell
* [Portia](https://github.com/SpiderLabs/portia) - Portia aims to automate a number of techniques commonly performed on internal network penetration tests after a low privileged account has been compromised.
* [PEASS-ng](https://github.com/carlospolop/PEASS-ng) - PEASS - Privilege Escalation Awesome Scripts SUITE (with colors)
* [GTFOBins](https://gtfobins.github.io/) - GTFOBins is a curated list of Unix binaries that can be used to bypass local security restrictions in misconfigured systems.
* [LOLBAS](https://lolbas-project.github.io/) - Living Off The Land Binaries, Scripts and Libraries.
* [GTFOBLookup](https://github.com/nccgroup/GTFOBLookup) - Offline command line lookup utility for GTFOBins、LOLBAS and WADComs.
* [PrintNotifyPotato](https://github.com/BeichenDream/PrintNotifyPotato) - PrintNotifyPotato

#### C2

* [DeimosC2](https://github.com/DeimosC2/DeimosC2) - DeimosC2 is a Golang command and control framework for post-exploitation.
* [Sliver](https://github.com/BishopFox/sliver) - Implant framework
* [PHPSploit](https://github.com/nil0x42/phpsploit) - Full-featured C2 framework which silently persists on webserver via evil PHP oneliner 😈
* [Shad0w](https://github.com/bats3c/shad0w) - A post exploitation framework designed to operate covertly on heavily monitored environments (Win8、Win10)
* [Covenant](https://github.com/cobbr/Covenant) - Covenant is a collaborative .NET C2 framework for red teamers.
* [Emp3r0r](https://github.com/jm33-m0/emp3r0r) - linux post-exploitation framework made by linux user
* [C3](https://github.com/FSecureLABS/C3) - Custom Command and Control (C3). A framework for rapid prototyping of custom C2 channels, while still providing integration with existing offensive toolkits. 
* [byob](https://github.com/malwaredllc/byob) - An open-source post-exploitation framework for students, researchers and developers.
* [Havoc](https://github.com/HavocFramework/Havoc) - Havoc is a modern and malleable post-exploitation command and control framework.
* [Villain](https://github.com/t3l3machus/Villain) - Villain is a Windows & Linux backdoor generator and multi-session handler that allows users to connect with sibling servers (other machines running Villain) and share their backdoor sessions, handy for working as a team.

#### Bypass AV

* [Shellcodeloader](https://github.com/knownsec/shellcodeloader) - ShellcodeLoader of windows can bypass AV.
* [AV_Evasion_Tool](https://github.com/1y0n/AV_Evasion_Tool) - AntiVirus Shellcode generation tool.

### Golang Sec Tools
> Tips: Golang is a excellent cross platform language for security.

* [Naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in go with focus on reliability and simplicity.
* [ServerScan](https://github.com/Adminisme/ServerScan) - A high concurrency network scanning and service detection tool developed by golang.

### Reporting & Collaboration

* [Vulnreport](https://github.com/salesforce/vulnreport) - Open-source pentesting management and automation platform by Salesforce Product Security 
* [Pentest-Collaboration-Framework](https://gitlab.com/invuls/pentest-projects/pcf) - Opensource, cross-platform and portable toolkit for automating routine processes when carrying out various works for testing!
* [CervantesSec](https://github.com/CervantesSec/cervantes) - Cervantes is an opensource collaborative platform for pentesters or red teams who want to save time to manage their projects, clients, vulnerabilities and reports in one place.

### Social Engineering Tools


### Code Audit

* [Cloc](https://github.com/AlDanial/cloc) - cloc counts blank lines, comment lines, and physical lines of source code in many programming languages
* [Cobra](https://github.com/WhaleShark-Team/cobra) - Source Code Security Audit
* [Cobra-W](https://github.com/LoRexxar/Cobra-W) - Cobra for white hat
* [Graudit](https://github.com/wireghoul/graudit) - Grep rough audit - source code auditing tool 
* [Rips](https://github.com/ripsscanner/rips) - A static source code analyser for vulnerabilities in PHP scripts
* [Kunlun-M](https://github.com/LoRexxar/Kunlun-M) - KunLun-M is a static code analysis system that automates the detecting vulnerabilities and security issue.

### Port Forwarding & Proxies

* [EarthWorm](https://github.com/rootkiter/EarthWorm) - Tool for tunnel 
* [Termite](https://github.com/rootkiter/Termite/) - Tool for tunnel (Version 2) 
* [Frp](https://github.com/fatedier/frp) - A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet 
* [Nps](https://github.com/ehang-io/nps/) - A lightweight, high-performance, powerful intranet penetration proxy server, with a powerful web management terminal. 
* [Goproxy](https://github.com/snail007/goproxy) -  A high-performance, full-featured, cross platform proxy server
* [ReGeorg](https://github.com/sensepost/reGeorg) - The successor to reDuh, pwn a bastion webserver and create SOCKS proxies through the DMZ. Pivot and pwn
* [Venom](https://github.com/Dliv3/Venom) - A Multi-hop Proxy for Penetration Testers
* [Stowaway](https://github.com/ph4ntonn/Stowaway) - 👻 Stowaway -- Multi-hop Proxy Tool for pentesters
* [rport](https://github.com/cloudradar-monitoring/rport) - Manage remote systems with ease.
* [PortForward](https://github.com/knownsec/PortForward) - The port forwarding tool developed by Golang solves the problem that the internal and external networks cannot communicate in certain scenarios.


### DevSecOps

### RootKit

* [Beurk](https://github.com/unix-thrust/beurk) - BEURK Experimental Unix RootKit
* [Bedevil](https://github.com/naworkcaj/bdvl) - LD_PRELOAD Linux rootkit (x86 & ARM)

### Audit Tools

* [DevAudit](https://github.com/OSSIndex/DevAudit) - Open-source, cross-platform, multi-purpose security auditing tool

### Pentesting Distribution

* [Backbox Linux](https://linux.backbox.org) - penetration testing and security assessment oriented Linux distribution
* [Kali Linux](https://www.kali.org) - Debian-based pentesting distribution
* [BlackArch Linux](https://blackarch.org) - Arch Linux-based penetration testing distribution
* [Parrot Security](https://parrotlinux.org) - The ultimate framework for your Cyber Security operations
* [ArchStrike](https://archstrike.org) - Arch Linux respository for security professionals

### Cyber Range

#### Vulnerability application

* [DVWA](https://github.com/ethicalhack3r/DVWA) - Damn Vulnerable Web Application (DVWA)
* [WebGoat](https://github.com/WebGoat/WebGoat) - WebGoat is a deliberately insecure web application maintained by OWASP designed to teach web application security lessons
* [DSVW](https://github.com/stamparm/DSVW) - DSVW is a deliberately vulnerable web application written in under 100 lines of code, created for educational purposes
* [DVWS](https://github.com/snoopysecurity/dvws) - Damn Vulnerable Web Services is an insecure web application with multiple vulnerable web service components that can be used to learn real world web service vulnerabilities
* [XVWA](https://github.com/s4n7h0/xvwa) - XVWA is a badly coded web application written in PHP/MySQL that helps security enthusiasts to learn application security
* [BWAPP](http://www.mmebvba.com/sites/bwapp/index.htm) - A buggy web application whit more than 100 vulnerabilities
* [Sqli-lab](https://github.com/Audi-1/sqli-labs) - SQLI labs to test error based, Blind boolean based, Time based
* [HackMe-SQL-Injection-Challenges](https://github.com/breakthenet/HackMe-SQL-Injection-Challenges) - Hack your friend's online MMORPG game - specific focus, sql injection opportunities
* [XSS-labs](https://github.com/paralax/xss-labs) - Small set of scripts to practice exploit XSS and CSRF vulnerabilities
* [SSRF-lab](https://github.com/m6a-UdS/ssrf-lab) - Lab for exploring SSRF vulnerabilities
* [SSRF_Vulnerable_Lab](https://github.com/incredibleindishell/SSRF_Vulnerable_Lab) - This Lab contain the sample codes which are vulnerable to Server-Side Request Forgery attack
* [LFI-labs](https://github.com/paralax/lfi-labs) - Small set of PHP scripts to practice exploiting LFI, RFI and CMD injection vulns
* [Commix-testbed](https://github.com/commixproject/commix-testbed) - A collection of web pages, vulnerable to command injection flaws
* [File-Upload-Lab](https://github.com/LunaM00n/File-Upload-Lab) - Damn Vulnerable File Upload V 1.1
* [Upload-labs](https://github.com/c0ny1/upload-labs) - A summary of all types of uploading vulnerabilities for you
* [XXE-Lab](https://github.com/c0ny1/xxe-lab) - A XXE vulnerability Demo containing language versions such as PHP, Java, python, C#, etc
* [Vulnerable-Flask-App](https://github.com/anil-yelken/Vulnerable-Flask-App) - Erlik2 Vulnerable-Flask-App provided by [anil-yelken](https://github.com/anil-yelken).

#### Simulation Range

* [Fopnp](https://github.com/brandon-rhodes/fopnp/tree/m/playground) - A Network Playground for 
《Foundations of Python Network Programming》

* [CyberRange](https://github.com/secdevops-cuse/CyberRange) - The Open-Source AWS Cyber Range

#### Honeyhots

* [DecoyMini](https://github.com/decoymini/DecoyMini/) - A highly scalable, safe, free enterprise honeypots

#### CTF challenges
* [Vulnhub](https://www.vulnhub.com/) - VulnHub provides materials allowing anyone to gain practical hands-on experience with digital security, computer applications and network administration
* [TryHackMe](https://tryhackme.com/) - TryHackMe is a free online platform for learning cyber security, using hands-on exercises and labs, all through your browser!
* [Hackthebox](https://www.hackthebox.com/) - Hack The Box is a massive, online cybersecurity training platform, allowing individuals, companies, universities and all kinds of organizations around the world to level up their hacking skills.
* [Root Me](https://www.root-me.org/) - Root Me allows everyone to test and improve their knowledge in computer security and hacking.
* [Pentestit](https://lab.pentestit.ru/) - Penetration testing laboratories "Test lab" emulate an IT infrastructure of real companies and are created for a legal pen testing and improving penetration testing skills
* [Pentesterlab](https://pentesterlab.com/) - Learn Web Penetration Testing: The Right Way
* [Cyberseclabs](https://www.cyberseclabs.co.uk/) - At CyberSecLabs, we aim to provide secure, high-quality training services that allow information security students the opportunity to safely learn and practice penetration testing skills.
* [Web Security Academy](https://portswigger.net/web-security) - Free, online web security training from the creators of Burp Suite
* [Vulnmachines](https://www.vulnmachines.com/) - A place to learn and improve penetration testing/ethical hacking skills for FREE
### Excellent project
* [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/tools.html#title-tools-osint-and-reconnaissance) - An inventory of tools and resources about CyberSecurity.
