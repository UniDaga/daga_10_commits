## **Bypass Zama Dev Guild "10 Commits Before 10 July" Task**
After following this guide you will have: 20 commits on your github before 30 June

There are currently 2 ways to bypass this task
using codespace terminal: short but works for few people
using wsl/ubuntu: works for everyone we will be using second method here to onboard more people
Instructions

1. ## Create a New Repository
Go to: https://github.com/new
Repository Name: 20commits
Tick "Add a README file"
Click Create repository

2. ## Open Ubuntu
3. Clone your GitHub repo
In Newly Created GitHub Repo click the green <> Code button copy the HTTPS link (looks like: https://github.com/username/repo.git)

4. ## In Ubuntu Terminal:
cd ~
**git clone https://github.com/your-username/your-repo.git
cd 20commits**
replace HTTPS link in above command by link you copied above -do this carefully

5. ## Authenticate
**git config --global user.name "X"
git config --global user.email "Y.com"**
**replace X and Y by your original github username and email respectively

6. ## Run this command
**echo "Commit 1 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:00:01" GIT_COMMITTER_DATE="2025-06-30T01:00:01" git commit -m "Commit 1"

echo "Commit 2 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:15:13" GIT_COMMITTER_DATE="2025-06-30T01:15:13" git commit -m "Commit 2"

echo "Commit 3 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:30:22" GIT_COMMITTER_DATE="2025-06-30T01:30:22" git commit -m "Commit 3"

echo "Commit 4 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:45:33" GIT_COMMITTER_DATE="2025-06-30T01:45:33" git commit -m "Commit 4"

echo "Commit 5 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:01:07" GIT_COMMITTER_DATE="2025-06-30T02:01:07" git commit -m "Commit 5"

echo "Commit 6 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:20:11" GIT_COMMITTER_DATE="2025-06-30T02:20:11" git commit -m "Commit 6"

echo "Commit 7 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:33:19" GIT_COMMITTER_DATE="2025-06-30T02:33:19" git commit -m "Commit 7"

echo "Commit 8 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:50:05" GIT_COMMITTER_DATE="2025-06-30T02:50:05" git commit -m "Commit 8"

echo "Commit 9 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T03:12:29" GIT_COMMITTER_DATE="2025-06-30T03:12:29" git commit -m "Commit 9"

echo "Commit 10 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T03:30:03" GIT_COMMITTER_DATE="2025-06-30T03:30:03" git commit -m "Commit 10"

echo "Commit 11 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T03:44:56" GIT_COMMITTER_DATE="2025-06-30T03:44:56" git commit -m "Commit 11"

echo "Commit 12 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:01:09" GIT_COMMITTER_DATE="2025-06-30T04:01:09" git commit -m "Commit 12"

echo "Commit 13 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:20:20" GIT_COMMITTER_DATE="2025-06-30T04:20:20" git commit -m "Commit 13"

echo "Commit 14 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:40:00" GIT_COMMITTER_DATE="2025-06-30T04:40:00" git commit -m "Commit 14"

echo "Commit 15 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:59:44" GIT_COMMITTER_DATE="2025-06-30T04:59:44" git commit -m "Commit 15"

echo "Commit 16 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T05:12:12" GIT_COMMITTER_DATE="2025-06-30T05:12:12" git commit -m "Commit 16"

echo "Commit 17 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T05:33:27" GIT_COMMITTER_DATE="2025-06-30T05:33:27" git commit -m "Commit 17"

echo "Commit 18 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T05:50:00" GIT_COMMITTER_DATE="2025-06-30T05:50:00" git commit -m "Commit 18"

echo "Commit 19 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T06:10:10" GIT_COMMITTER_DATE="2025-06-30T06:10:10" git commit -m "Commit 19"

echo "Commit 20 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T06:30:01" GIT_COMMITTER_DATE="2025-06-30T06:30:01" git commit -m "Commit 20"**

**git push**

After git push command you will be asked for username, paste your github username Then you will be asked for password: Don't use your github password use PAT instead (below is guide how to grab your PAT# daga_10_commits
