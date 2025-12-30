## Level 14 → Level 15

### Goal
Send the current level password to a local service and retrieve the password for the next level.

---

### Steps

1. Logged in as bandit14.

2. Read the current level password:
   cat /etc/bandit_pass/bandit14
   
Connected to the local service using netcat:
nc localhost 30000
Sent the bandit14 password to the service and received the password for bandit15.

Result
Successfully obtained the password for Bandit Level 15.
