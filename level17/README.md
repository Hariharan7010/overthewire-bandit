Level 17 → Level 18

Level Overview
Username: bandit17
Objective: Find the password for Bandit Level 18
File Type: Text comparison

Tools Used
ssh
diff

Step-by-Step Solution

Step 1: Login to the server
ssh bandit17@bandit.labs.overthewire.org -p 2220

Step 2: List available files
ls

Step 3: Compare files
diff passwords.old passwords.new

Step 4: Identify the password
The line starting with > contains the password.

Result
Successfully obtained the password for Bandit Level 18.
