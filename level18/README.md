Level 18 → Level 19

Level Overview
Username: bandit18
Objective: Bypass automatic logout and read the password
Restriction: Shell exits immediately after login

Tools Used
ssh

Step-by-Step Solution
Step 1: Execute command during login
ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme

Step 2: Read the password
The password is displayed directly in the output.

Result
Successfully retrieved the password for Bandit Level 19.
