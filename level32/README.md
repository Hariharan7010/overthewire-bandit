Level 32 → Level 33
Level Overview
Username: bandit32
Objective: Escape uppercase-only shell

Tools Used
ssh

Step-by-Step Solution
Step 1: Login
ssh bandit32@bandit.labs.overthewire.org -p 2220

Step 2: Bypass shell restriction
Execute:
$0

Step 3: Read password
cat /etc/bandit_pass/bandit33

Result
Successfully retrieved the password for Bandit Level 33.
Next password: tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ0
