## Level 10 → Level 11

### Goal
Decode a Base64-encoded file to retrieve the password.

### Steps
1. Login to Bandit Level 10:
   ssh bandit10@bandit.labs.overthewire.org -p 2220

List files:
ls

Decode the file:
base64 -d data.txt

Result
The password for Level 11 was obtained successfully.
