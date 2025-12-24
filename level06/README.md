## Level 6 → Level 7

### Goal
Find a file owned by bandit7, grouped by bandit6, and exactly 33 bytes in size.

### Steps
1. Login to Bandit Level 6:
   ssh bandit6@bandit.labs.overthewire.org -p 2220

Search across the filesystem:
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null

Read the discovered file:
cat /path/to/file

Result
The password for Level 7 was obtained successfully.
