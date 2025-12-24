## Level 9 → Level 10

### Goal
Extract a human-readable password from a binary file.

### Steps
1. Login to Bandit Level 9:
   ssh bandit9@bandit.labs.overthewire.org -p 2220

List files:
ls

Extract readable strings and filter:
strings data.txt | grep "="

Result
The password for Level 10 was found successfully.
