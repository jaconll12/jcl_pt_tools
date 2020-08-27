# PT Tool Kit
playground of creating a docker image for some Pen testing tools I may need anywhere.  

This is my first docker container that has some simple pen testing tools loaded as a toolkit to take anywhere I need.

Tools are:
- netcat
- Nmap
- nano
- wfuzz
- dirt
- nikto
- curl
- git
- sqlmap
- wget
- whois
- vim
- searchsploit
- gobuster
- Wordlists for dns and directory (located at /usr/share/wordlists/) - dns.txt and dir.txt

To run the docker image run the command:
docker run -it jacoll/jcl_pt_tools


## TO DO 
- Make Bash script interactive
