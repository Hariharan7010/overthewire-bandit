## Level 4 → Level 5

### Goal
Find the password inside one human-readable file among many.

### Steps
1. Login to Bandit Level 4:
   ssh bandit4@bandit.labs.overthewire.org -p 2220

Enter the directory:
cd inhere

Check file types:
file ./*

Identify the ASCII text file and read it:
cat ./-fileXX

Result
The password for Level 5 was found successfully.
