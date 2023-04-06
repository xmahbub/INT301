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

```sh
nmap -p 3389 -sV -sC <RDP-service-IP>
```

# b) FTP

## To gather information about an FTP service, we can use a tool called "Nmap" which we used earlier. Nmap can help us to identify open ports, service versions, and OS details. To use Nmap, we can run the following command:

`nmap -p 21 -sV -sC <FTP-service-IP>`

# c) SMTP

## To gather information about an SMTP service, we can use a tool called "Netcat" which is a simple and powerful network tool. Netcat can help us to identify the banner information of the service. To use Netcat, we can run the following command:

`nc -nv <SMTP-service-IP> 25`

# d) NetBIOS

## To gather information about a NetBIOS service, we can use a tool called "Nbtscan" which is a free and open-source NetBIOS scanner. Nbtscan can help us to identify IP addresses and NetBIOS names on a local area network. To use Nbtscan, we can run the following command:

`nbtscan <NetBIOS-service-IP-range>`

# e) SQL

## To gather information about a SQL service, we can use a tool called "Sqlmap" which is a free and open-source SQL injection tool. Sqlmap can help us to identify the database management system, tables, columns, and data. To use Sqlmap, we can run the following command:

`sqlmap -u <SQL-service-URL> --banner --dbs`

