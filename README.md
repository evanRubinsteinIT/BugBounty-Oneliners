# BugBounty-Oneliners
Just a compilation of bash scripts I made to make information gathering for Bug Bounties easier

## Enum 
Handles all of the initaial subdomain enumeration, host pinging and port scanning. It outputs all of the information it scrapes in the current directory.
It requiers Assetfinder, Subfinder, Naabu, Amass, Httpx, and Aquatone to run. It is used by running the script with the root domain as an arguement.


## Filefuzz 
Fuzzes the directories of a list of URLs. It is used by running the script with the URL list as the first arguement, and the wordlist as the second arguement.


## Grabheaders 
Grabs the http/https headers from a list of URLs. It is used by running the script with the URL list as the arguement
