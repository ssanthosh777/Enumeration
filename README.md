# Enumeration
Enumeration Techniques
```
NAME: SANTHOSH S
REG.NO: 212224100052
```

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/cfa0246a-0629-437d-8983-ed878a6b311d" />


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/aec084b0-f512-450b-a636-acdce3bcf0c8" />



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/e44c0206-4ec7-48ae-9cf4-d0aa5c838000" />


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/33cc4ff3-70f2-49ce-bc75-dccfe4d7a586" />

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/be5218d9-6ec9-4f6f-bc3e-9f80991a8df7" />

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/2c29a65e-8451-48e5-acc3-15d3147b67c0" />

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## OUTPUT
<img width="1920" height="1200" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/9bdc2e5e-4950-448e-9ac1-7d9f64ac5c6a" />

 
## DNS Enumeration

## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
<img width="1920" height="1102" alt="Screenshot From 2026-01-31 08-51-54" src="https://github.com/user-attachments/assets/e35ffd83-bb7a-4aa2-be29-927bbd8d06b1" />






## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
## OUTPUT
<img width="1920" height="1102" alt="Screenshot From 2026-01-31 08-54-08" src="https://github.com/user-attachments/assets/97ad7584-54fc-4c96-9073-1c737d8a615f" />



## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
## OUTPUT
<img width="1920" height="1102" alt="Screenshot From 2026-01-31 09-44-09" src="https://github.com/user-attachments/assets/1dda63b8-9acd-44f3-b966-9a6b5c2e3b9b" />



## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output
 <img width="1920" height="1102" alt="Screenshot From 2026-01-31 09-44-50" src="https://github.com/user-attachments/assets/a075b160-6ed7-4f7b-ac63-d8598e92c4cd" />

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
<img width="1920" height="1102" alt="Screenshot From 2026-01-31 09-48-07" src="https://github.com/user-attachments/assets/645c10f2-43bb-43ae-a7ed-b3582562fa44" />



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

