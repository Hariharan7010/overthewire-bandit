## Level 11 → Level 12

### Goal
Decode a file that uses ROT13 encryption.

### Steps
1. Login to Bandit Level 11:
   ssh bandit11@bandit.labs.overthewire.org -p 2220

List files:
ls

Decode ROT13:
tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt

Result
The password for Level 12 was obtained successfully.
