## Level 5 → Level 6

### Goal
Find a human-readable file of size 1033 bytes that is not executable.

### Steps
1. Login to Bandit Level 5:
   ssh bandit5@bandit.labs.overthewire.org -p 2220

Search for the file using find:
find . -type f -size 1033c ! -executable

Read the discovered file:
cat ./maybehereXX/.fileX

Result:
The password for Level 6 was obtained successfully.
