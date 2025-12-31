Level 16 → Level 17
Level Overview

Username: bandit16

Objective: Obtain the credentials for Bandit Level 17

Service Type: SSL/TLS encrypted service

Port Range: 31000–32000

Tools Used
ssh – remote login
nmap – port scanning
openssl – SSL service interaction

Step-by-Step Solution
Step 1: Login to the server
ssh bandit16@bandit.labs.overthewire.org -p 2220

Step 2: Scan for open ports
nmap -p 31000-32000 localhost

Step 3: Identify SSL-enabled service

Connect to each open port using:
openssl s_client -connect localhost:<port>

Step 4: Retrieve SSH private key
One port returns an SSH private key instead of a password.

Step 5: Save key and set permissions
chmod 600 private.key

Step 6: Login to Bandit17 using the key
ssh -i private.key bandit17@localhost -p 2220

Result
Successfully logged in to Bandit Level 17 using SSH key authentication.
