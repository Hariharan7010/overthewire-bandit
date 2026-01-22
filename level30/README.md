Level 30 → Level 31
Level Overview
Username: bandit30
Objective: Retrieve password from Git tag

Tools Used
ssh
git

Step-by-Step Solution
Step 1: Login
ssh bandit30@bandit.labs.overthewire.org -p 2220

Step 2: Clone repository
git clone ssh://bandit30@bandit.labs.overthewire.org/home/bandit30-git/repo

Step 3: List tags
git tag

Step 4: View tag content
git show <tag_name>

Result
Successfully retrieved the password for Bandit Level 31.
Next password: fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy
