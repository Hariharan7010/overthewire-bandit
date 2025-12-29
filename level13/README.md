## Level 13 → Level 14

### Goal
Use an SSH private key to log in to the next level instead of using a password.

---

### Key Information
- Bandit Level 13 does **not** provide a password.
- Instead, a private SSH key is given.
- This key must be used to authenticate as `bandit14`.

---

### Steps

1. Login to Bandit Level 13:
   ssh bandit13@bandit.labs.overthewire.org -p 2220

List files to locate the SSH private key:
ls

Output:
sshkey.private

Copy the key to a writable location and fix permissions:
cp sshkey.private /tmp/bandit14.key
chmod 600 /tmp/bandit14.key

Login to Bandit Level 14 using the private key:
ssh -i /tmp/bandit14.key bandit14@localhost -p 2220

Result
Successfully logged in to Bandit Level 14 using SSH key authentication.
