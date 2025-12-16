# overthewire-bandit
## Level 0 → Level 1

### Goal
Login using SSH and read the password from a file.

### Steps
1. Connected to the server using SSH:
   ```bash
   ssh bandit0@bandit.labs.overthewire.org -p 2220
Listed files:
ls
Read the file:
cat readme
Result
The password for Level 1 was found inside the readme file.
