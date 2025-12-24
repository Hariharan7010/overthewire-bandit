## Level 12 → Level 13

### Goal
Extract a password hidden inside multiple layers of compression.

### Steps
1. Login to Bandit Level 12:
   ssh bandit12@bandit.labs.overthewire.org -p 2220

Create a temporary directory:
mkdir /tmp/bandit12_work
cd /tmp/bandit12_work

Convert hex dump to binary:
cp ~/data.txt .
xxd -r data.txt > data
Repeatedly identify and extract compression layers using file, gunzip, bunzip2, and tar.
Read the final ASCII file.

Result
The password for Level 13 was obtained successfully.
