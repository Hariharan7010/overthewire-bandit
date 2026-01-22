Level 29 → Level 30
Level Overview
Username: bandit29
Objective: Find password hidden in Git branches

Tools Used
ssh
git

Step-by-Step Solution
Step 1: Login
ssh bandit29@bandit.labs.overthewire.org -p 2220

Step 2: Clone repository
git clone ssh://bandit29@bandit.labs.overthewire.org/home/bandit29-git/repo

Step 3: List branches
git branch -a

Step 4: Switch to correct branch
git checkout <branch_name>
cat README

Result
Successfully obtained the password for Bandit Level 30.
Next password: qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL
