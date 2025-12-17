## Level 1 → Level 2

### Goal
Read a file named `-`, which is a special filename in Linux.

### Steps
1. Logged in using SSH:
   ```bash
   ssh bandit1@bandit.labs.overthewire.org -p 2220
Listed files:
            ls
Read the file safely using relative path:
                                        cat ./-

Result:
The password for Level 2 was obtained successfully.
