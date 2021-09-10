This folder contains my research into the Forti SLL VPN data leak which was published by the threat actor known as Orange.
At this stage my research does not contain the full dataset of leaked records from the dark web, as focus was more so directed at identifying which South African companies
have been affected.

From my research I believe it is in goodwill to contact some of these companies and check to see if they are aware of their systems being compromised.

For navigation purposes please see the below explaination of the contents within.

|_[Directory]-FortiSLLVPN_SOUTH_AFRICA
	|_[Directory]Companies Data (Main Folder for all the return data from OSINT searches)
		|_[File]-Company names - September 09 2021... (Excel sheet listing all affected companies)
		|_[File]-FortiVPN_southAfrica.json (IP range,netname,descr,person,phone and address from whois lookups in json format suitable for database insertion.)
		|__[File]-FortiVPN_southAfrica_LIST.json (data from whois lookups in json format suitable for viewing)
		|_[File]-IPs.txt (list of all the IP addresses from south africa - source Cognyte)
		|_[File]-netnames.txt (list of all the netnames returned from whois queries on all IP addresses)
		|_[File]-whois-all.txt (text file containing all of the whois query results from whois.afrinic.net)
	|_MaltegoScans (Folder with maltego scans, to download maltego visit: https://www.maltego.com/downloads/)
		|_[Directory]-MaltegoIPV4List (Folder which holds excel&csv lists of IP addresses)
			|	|_[File]-one.xlsx (List of 49 IPV4 addresses)
			|	|_[File]-two.xlsx (List of 49 IPV4 addresses)
			|	|_[File]-three.xlsx (List of 49 IPV4 addresses)
			|	|_[File]-four.xlsx (List of 49 IPV4 addresses)
			|	|_[File]-five.xlsx (List of 49 IPV4 addresses)
			|	|_[File]-six.csv (List of 1 IPV4 addresses)
		|_[File]-one.mtgl (Maletgo graph mapping 49 IPv4 NOTE:scans mostly tie IP addresses to AFRINIC)
		|_[File]-two.mtgl (Maletgo graph mapping 49 IPv4 NOTE:scans mostly tie IP addresses to AFRINIC)
		|_[File]-three.mtgl (Maletgo graph mapping 49 IPv4 NOTE:scans mostly tie IP addresses to AFRINIC)
		|_[File]-four.mtgl (Maletgo graph mapping 49 IPv4 NOTE:scans mostly tie IP addresses to AFRINIC)
		|_[File]-five.mtgl (Maletgo graph mapping 49 IPv4 NOTE:scans mostly tie IP addresses to AFRINIC)
		|_[File]-six.mtgl (Maletgo graph mapping 49 IPv4 NOTE:scans mostly tie IP addresses to AFRINIC)
	|_[File]-README.txt (Explaination file)
		
