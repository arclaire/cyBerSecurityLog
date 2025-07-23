# cyBerSecurityLog
Introduction and general cyberSecurity task from TryHackMe

Cryptographic method or product considered to be bogus or fraudulent: 
- Snake Oil (derived from patent medicine from US)

netstat command in LINUX depracated changed to: 
- ss (socket statistics)

Search Engine format:
- " exact phrase " :double quotes for exact phrase
- site: : specify
- pyramids -tourism or -tourism pyramids:  "minus sign" omit search (beside sample to find about pyramids but not include about tourism
- filetype: : finding files instead web pages

Search engine for devices connected to the Internet:
- Shodan (servers, routers, webcams, and IoT devices)
- Censys (Internet-connected hosts, websites, certificates, and other Internet assets)
- VirusTotal (a virus-scanning service for files using multiple antivirus engines)
- Have I Been Pwned: show if one email is appeared in leaked data breach

CVE > Common Vulnerabilities and Exposures

LINUX COMMAND
Search Files
echo > print 
echo > tryhackme 
(one word no need inside quote)
echo > "tryhackme success"

ls > listing

cat > content of file 

cd > change directory 

pwd > print working directory 

grep > find specific string in file content  
ex: grep "THM" access.log

SHELL OPERATORS 
& > will do process in background (copying big filesize)
&& > combine list of commands
">" redirector overwrite content
">>" redirector append content

Task
To run a command in the background, what operator would we want to use = &

Command to replace the contents of a file named "passwords" with the word "password123"
echo password123 > passwords

Command to add "tryhackme" to this file named "passwords" but also keep "passwords123"
echo tryhackme >> passwords



