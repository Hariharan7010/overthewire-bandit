## Level 15 → Level 16

## Level Overview
- **Username:** bandit15  
- **Objective:** Obtain the password for Bandit Level 16  
- **Service Type:** SSL/TLS encrypted service  
- **Port:** 30001

## Tools Used
- ssh – for remote login  
- openssl – to establish an SSL/TLS connection

## Step-by-Step Solution

### Step 1: Login to the server
ssh bandit15@bandit.labs.overthewire.org -p 2220

Step 2: Connect to the SSL-enabled service
openssl s_client -connect localhost:30001

Step 3: Submit the password

Once the connection is established:
Paste the current level’s password
Press Enter
If the password is correct, the service responds with:
Correct!
<password for bandit16>

Result
Successfully retrieved the password for Bandit Level 16
