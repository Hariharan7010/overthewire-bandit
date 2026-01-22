Level 31 → Level 32
Level Overview
Username: bandit31
Objective: Push correct content to a Git repository

Tools Used
ssh
git

Step-by-Step Solution
Step 1: Login
ssh bandit31@bandit.labs.overthewire.org -p 2220

Step 2: Clone repository
git clone ssh://bandit31@bandit.labs.overthewire.org/home/bandit31-git/repo

Step 3: Create required file
echo "May I come in?" > key.txt

Step 4: Commit and push
git add key.txt
git commit -m "add key"
git push

Result
Successfully obtained the password for Bandit Level 32.
Next password: 3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K
