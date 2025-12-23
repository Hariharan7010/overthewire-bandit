## Level 3 → Level 4

### Goal
Find a hidden file inside a directory.

### Steps
1. Login to Bandit Level 3:
   ssh bandit3@bandit.labs.overthewire.org -p 2220

List files:
ls
Enter directory:
cd inhere

Show hidden files:
ls -a

Read hidden file:
cat .hidden

Result
The password for Level 4 was found successfully.
