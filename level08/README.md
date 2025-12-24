## Level 8 → Level 9

### Goal
Find the only line that occurs once in a file.

### Steps
1. Login to Bandit Level 8:
   ssh bandit8@bandit.labs.overthewire.org -p 2220
List files:
ls

Sort the file and extract the unique line:
sort data.txt | uniq -u

Result
The password for Level 9 was obtained successfully.
