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
<img width="845" height="445" alt="Screenshot 2026-08-08 134912" src="https://github.com/user-attachments/assets/3203e0da-5f41-4d02-a912-018328703078" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

##output
<img width="540" height="442" alt="Screenshot 2026-08-08 141535" src="https://github.com/user-attachments/assets/430185d4-1550-498a-b03f-3296aead3b75" />



## Finding Hosting Company
get further detail by using ip2location.com website.

##Output

<img width="1350" height="715" alt="Screenshot 2026-08-08 141924" src="https://github.com/user-attachments/assets/8ab96b5c-ea15-43f0-a2f3-d94c6e6eeb67" />

<img width="1377" height="557" alt="Screenshot 2026-08-08 141939" src="https://github.com/user-attachments/assets/d6fb4187-09ee-4f76-846a-ec32705aae07" />


## History of the website:
## output
https://web.archive.org/
<img width="1307" height="687" alt="Screenshot 2026-08-08 142721" src="https://github.com/user-attachments/assets/09d93fc4-6c21-41cf-ace8-c2f4f1ca1194" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

##output




## nmap:
###output
<img width="532" height="176" alt="Screenshot 2026-08-08 145537" src="https://github.com/user-attachments/assets/555f93d5-06db-4286-9725-a1366ba64e4f" />



## Whatweb
### output
<img width="516" height="362" alt="Screenshot 2026-08-08 145551" src="https://github.com/user-attachments/assets/f402b5c8-149c-4bd9-865d-aa33d567bc89" />


## httprint
### output
<img width="657" height="573" alt="Screenshot 2026-08-08 152252" src="https://github.com/user-attachments/assets/1d830ed2-d0d3-4b42-9503-ca607530747a" />




# Tracing the Location
TCP Traceroute:
3sudo traceroute wikipedia.org
## output
<img width="787" height="435" alt="Screenshot 2026-08-08 145511" src="https://github.com/user-attachments/assets/bf812870-b7ad-4972-aac8-2e39d2ed7465" />


## UDP Traceroute:
sudo traceroute -T www.microsoft.com
## output

<img width="652" height="202" alt="Screenshot 2026-08-08 204434" src="https://github.com/user-attachments/assets/877f4124-28aa-4f47-aa18-91114b878286" />


## ICMP Traceroute:
sudo traceroute -U www.twitter.com
## output

<img width="541" height="485" alt="Screenshot 2026-08-08 204600" src="https://github.com/user-attachments/assets/00df984e-1e72-4898-8f4e-34ba0a77ecb9" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully

The information gathering techniques tools/procedure were  identified successfully
