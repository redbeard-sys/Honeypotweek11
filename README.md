# Honeypotweek11

<h3>Setup</h3>

- Setting up the google cloud account was actually one of the most time consuming parts of the assingment. Google would not accept my edu account, so I had to use my personal email. After familiarizing myself with the google cloud interface. I was able to setup Ubuntu 18.04 Minimal. From there I followed the dirctions of the assingment closely to make the necesary google commands to make the honeypot vm and the MHN-admin with appropriate firewall and network settings.

 ![Image](https://github.com/redbeard-sys/Honeypotweek11/blob/main/Google%20Cloud.png)

 # Image of Honeypot Sensors
  - Creation of Dionaea Honeypot
  - A honeypot is an intentionally exposed and compromised server to trap hackers.
  - A honeypot can be used to observe what kind of payloads hackers are using.
 ![Image](https://github.com/redbeard-sys/Honeypotweek11/blob/main/MHN%20Server.png)

 # Nmap Attack
  - I opted to use Nmap form my host operating system to scan the honeypot. The right corner of the Nmap gif shows the ammount of attacks launched on the honeypot.
  - You can see below the attacks report which shows attacks from various IPs and countries.
  - The session.json file can be viewed in this repository.
  - MHN admin uses mongodb to store files
 ![Image](https://github.com/redbeard-sys/Honeypotweek11/blob/main/honeyAttack.gif)


 ![Image](https://github.com/redbeard-sys/Honeypotweek11/blob/main/Attack%20Report.png)
 
 ![Attack Report 2](https://github.com/redbeard-sys/Honeypotweek11/blob/main/Attack%20report%202.png)
 
 
 # Malware Analysis 
 
  - I looked at the payloads captured by the honeypot.
  - I copied the hashes and searched the virus total for a report on the malware.
  - The report gave a cve and showed that many antiviruses flag the malware as a trojan.
  - I beleive that one of the payloads is the wannacry trojan.
 
 ![image](https://github.com/redbeard-sys/Honeypotweek11/blob/main/Malware%20Analysis.png)
 
 ![image](https://github.com/redbeard-sys/Honeypotweek11/blob/main/Malware%202.png)

 # Requirements
 - [x] MHN Admin 
 - [x] Dionaea Honeypot
 - [x] Session.json
 - [x] Malware Capture and Identification (Stretch)
