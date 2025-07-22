**Git Commands Reference**
**1. Basic Configuration**
Set your Git username:
git config --global user.name "Your Name"

**Set your Git email:**
git config --global user.email "your.email@example.com"

**2. Initialize Repository**
**Start a new Git repository:**
git init

**3. File Management (Non-Git)
Create a file:**
touch filename.txt

**Delete a file:**
rm filename.txt

**Edit a file:**
vi filename.txt

**List files:**
ls, ls -a, ls -l

**Clear terminal:**
clear

**Print current directory:**
pwd

**Change directory:**
cd directory_name

**4. Staging Files
Add a specific file to staging:**
git add filename.txt

**Add all changes:**
git add .

**Remove a file from staging:**
git rm --cached filename.txt

**5. Committing Changes**
Commit staged changes with a message:
git commit -m "Commit message"

**6. Checking Status**
View current changes and status:
git status

**7. Commit History**
**Show commit log:**
git log

**Show one-line commit history:**
git log --oneline

****8. Branching**
View all branches:**
git branch

**Create a new branch:**
git branch branch-name

**Switch to a branch:**
git checkout branch-name

**Create and switch to a new branch:**
git checkout -b branch-name

**9. Restoring Files**
**Discard local changes in a file:**
git restore filename.txt

**10. Helpful Utilities**
Show terminal command history:
history
