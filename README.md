# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![239421664-a2b13e20-b504-4901-a35d-1d53247726af](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/19103694-3ff1-4deb-a046-9b03ceaefb66)
## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![239421780-0f9a3d5c-ae8c-4d1b-a4f5-2a025ed498a5](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/96c85699-9af6-45af-a003-6cad4d3107e5)
## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![239421870-bbf4095f-00d4-49b8-a950-ddd504d0d81e](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/ab62ca61-9ed9-48a4-897d-12945b360c23)
## History of the wbsite:
## Output:
https://web.archive.org/        

![239421942-f5166239-895a-4e51-924a-1771ccea3ec8](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/8164062d-1bca-4bad-a92a-f02adc282179)
## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![239422058-2f794aca-900f-4e44-b5e4-9eff031425ab](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/299bb65c-1c83-4c15-bab5-fb08d8499fd6)
## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![239422130-f8eebdf9-67ff-42c0-ae3b-b126d20576bb](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/4bb36ba7-34f4-4eea-bc87-dd922fdf1429)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![239422365-13003241-f18f-4e84-b15d-86a327e9c68c](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/c2f54de4-7829-472e-8674-4254ba7afa0f)
## httprint:InformationGathering
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![239422518-e1275ae0-7aef-43d9-a8bf-99be791d0070](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/ce09856f-cabd-4203-960d-644003b46ec1)
## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![239422644-67469d67-bba1-4fa1-925d-1bc35c4146ca](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/a7bbc981-822e-4883-809e-a3a557a7066b)
## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![239422752-6f980827-c16f-4865-afff-1de0714937fd](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/9eb6d02f-0c6c-4edc-a95d-6cec7652814b)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![239423060-5b0e049e-98ee-4849-ad1c-de8d8189927e](https://github.com/Yogeshvar005/InformationGathering/assets/113497367/434e560e-1564-4222-9ee8-c5e1e1b81e11)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
