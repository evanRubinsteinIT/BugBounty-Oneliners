# BugBounty-Oneliners
Just a compilation of bash scripts I made that I use to make life easier while Bug Bounty Hunting

## enum 
Script made to do all of the initaial subdomain enumeration, host pinging and port scanning. It outputs all of the information it scrapes in the current directory.
It requiers Assetfinder, Subfinder, Naabu, and Httpx to run


## filefuzz
Script made to fuzz the directories of several hosts in a file. For each host, it appends "/FUZZ" to the end, and sends it to FFUF to be fuzzed with a wordlist that you input.
First arguement after the script is the file containing hosts, and the second is the path to the wordlist file. 
