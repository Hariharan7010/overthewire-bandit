Level 19 → Level 20

Level Overview
Username: bandit19
Objective: Use a setuid binary to access the password

Tools Used
ssh

Step-by-Step Solution
Step 1: Login
ssh bandit19@bandit.labs.overthewire.org -p 2220

Step 2: Execute the setuid binary
./bandit20-do cat /etc/bandit_pass/bandit20

Result
Successfully obtained the password for Bandit Level 20.
