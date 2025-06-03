# Shodan-WHOIS-Lab

## Objective
To gain hands-on familarity with Shodan and WHOIS. This lab will be carried out in a controlled environment, using a cloud server with Apache2 installed.

### Skills Learned
- Using Shodan and applying the various search filters
- Using WHOIS, through web browser and CLI

### Tools Used
- Shodan
- WHOIS

## Steps
Set up a cloud server, install Apache2. The IP address assigned to this server is 64.227.149.43
![Screenshot 2025-06-03 141941](https://github.com/user-attachments/assets/51d42712-1195-48a0-b3ee-6298e5a2e48e)

Using search filter "ip:64.227.149.43", we see stuff like general info, open ports. Seeing Port 80 is expected as there's Apache2 running, on HTTP.
![image](https://github.com/user-attachments/assets/f094767a-2d0a-4967-a12f-dc5ae337ccf5)

Using WHOIS (whois.domaintools.com) to retrieve additional details, like registration, technical and abuse contacts.
![image](https://github.com/user-attachments/assets/a6da86ad-29ab-4bac-80d7-612cd3440231)

Personally I prefer using <whois> in the CLI, since it pulls similar information with less navigation on the web UI.
![image](https://github.com/user-attachments/assets/52a138b4-bbaa-484c-8a84-921b87fcb6ab)
