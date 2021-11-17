# BugBounty-Oneliners
Just a compilation of bash scripts I made that I use to make life easier while Bug Bounty Hunting

# Enum 
Script made to do all of the initaial subdomain enumeration, host pinging and port scanning. It outputs all of the information it scrapes in the current directory.
It requiers Assetfinder, Subfinder, Naabu, Amass, Httpx, and Aquatone to run. It is used by running the script with the root domain as an arguement.


# Filefuzz 
Script that fuzzes the directories of a list of URLs. It is used by running the script with the URL list as the first arguement, and the wordlist as the second arguement.
