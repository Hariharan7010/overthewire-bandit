Level 20 → Level 21

Level Overview
Username: bandit20
Objective: Obtain the password for Bandit Level 21
Concept: Network service + setuid binary

Tools Used
ssh
nc (netcat)

Step-by-Step Solution
Step 1: Login to the server
ssh bandit20@bandit.labs.overthewire.org -p 2220

Step 2: Start a listening service
nc -l 1234

Step 3: Run the setuid binary in another session
./suconnect 1234

Step 4: Receive the password
The password is sent through the listening port.

Result
Successfully retrieved the password for Bandit Level 21.
