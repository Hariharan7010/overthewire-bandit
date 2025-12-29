## Level 14 → Level 15

### Goal
Retrieve the password for the next level from the system.


### Steps

1. Login to Bandit Level 14:
   ssh bandit14@bandit.labs.overthewire.org -p 2220

Read the password file:
cat /etc/bandit_pass/bandit14

Result
Successfully obtained the password for Bandit Level 15.

Concepts Learned:
Understanding system-protected password files
Using correct permissions to access restricted files
