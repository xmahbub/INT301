## Use any open source software to generate a report on information gathering, Identify and enumerate information like IP address, MAC address, ports details, encryption details, banner information, etc. about services listed below:-
           
## 1. RDP
## 2. FTP
## 3. SMTP
## 4. Netbios
## 5. SQL               
----

<p align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExNDAyZjUxMTY3Y2IyNTJjYzAxMDA2YjBmODM5ODJhNWFmMDUwYjA3NSZjdD1z/XSmHWLpvdycR6xukzC/giphy.gif" width=100>
  <br>

</p>

# RDP

To generate a report on information gathering, we need to use some open-source software tools that can help us to identify and enumerate information such as IP address, MAC address, port details, encryption details, banner information, etc. about the services listed below. Here are the tools we will use for each service:

Web Service (HTTP/HTTPS)
To gather information about a web service, we can use a tool called "Nmap" which is a free and open-source network scanner. Nmap can help us to identify open ports, service versions, and OS details. To use Nmap, we can run the following command:


nmap -p 80,443 -sV -sC <web-service-IP>
This command will scan the web service on ports 80 and 443, and perform version detection (-sV) and default script scanning (-sC) to gather more information about the service.

Mail Service (SMTP/POP/IMAP)
To gather information about a mail service, we can use a tool called "Netcat" which is a simple and powerful network tool. Netcat can help us to identify the banner information of the service. To use Netcat, we can run the following command:


nc -nv <mail-service-IP> 25
This command will connect to the SMTP service on port 25, and display the banner information.

File Transfer Service (FTP/SFTP)
To gather information about a file transfer service, we can use a tool called "Nmap" which we used earlier. Nmap can help us to identify open ports, service versions, and OS details. To use Nmap, we can run the following command:

arduino
Copy code
nmap -p 21,22 -sV -sC <file-transfer-service-IP>
This command will scan the file transfer service on ports 21 and 22, and perform version detection (-sV) and default script scanning (-sC) to gather more information about the service.

Database Service (MySQL/PostgreSQL)
To gather information about a database service, we can use a tool called "SQLMap" which is an open-source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws. SQLMap can help us to identify the banner information, database version, and tables. To use SQLMap, we can run the following command:



sqlmap -u "http://<database-service-IP>" --banner --current-db --tables
This command will scan the database service and display the banner information, current database name, and table names.

DNS Service
To gather information about a DNS service, we can use a tool called "Dig" which is a command-line tool for querying DNS name servers. Dig can help us to identify the IP address of the DNS server, and the DNS record information. To use Dig, we can run the following command:


dig <domain-name>
This command will query the DNS service for the domain name and display the IP address and DNS record information.

VoIP Service (SIP)
To gather information about a VoIP service, we can use a tool called "SIPVicious" which is an open-source security testing tool for the SIP protocol. SIPVicious can help us to identify the banner information, extension information, and password information. To use SIPVicious, we can run the following command:


svmap <voip-service-IP>
This command will scan the VoIP service and display the banner information, extension information, and password information.

