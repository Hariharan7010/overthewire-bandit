Level 26 → Level 27

Level Overview
Username: bandit26
Objective: Escape restricted shell and read password
Shell Type: Restricted (rbash)

Tools Used
ssh
vi

Step-by-Step Solution
Step 1: Login to the server
ssh bandit26@bandit.labs.overthewire.org -p 2220

Step 2: Escape restricted shell
Inside vi, run:
:set shell=/bin/bash
:shell

Step 3: Read password
cat /etc/bandit_pass/bandit27

Result
Successfully retrieved the password for Bandit Level 27.
