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

# a) RDP

## To gather information about an RDP service, we can use a tool called "Nmap" which is a free and open-source network scanner. Nmap can help us to identify open ports, service versions, and OS details. To use Nmap, we can run the following command:

`nmap -p 3389 -sV -sC <RDP-service-IP>`

# b) FTP

## To gather information about an FTP service, we can use a tool called "Nmap" which we used earlier. Nmap can help us to identify open ports, service versions, and OS details. To use Nmap, we can run the following command:

`nmap -p 21 -sV -sC <FTP-service-IP>`
