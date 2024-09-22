# datafun-04-jupyter

## How to Install and Run the Project


# Create a virutal Environment named .venv
python3 -m venv .venv 
# Activate Virtual Environment
source .venv/bin/activate

# Install Dependencies

python3 -m pip install -r requirements.txt

# Git Add

git add . 

# Git Commit
git commit -m "initial commit"

#       Subsequent Commits
        Just input your message on command
        git commit -m "Your commit message"

# Git Push
git push -u origin main

#       Subsequent Pushes
        git push
==============================================
# Additional Commands
Python3 Commands
-----------------

1. Check Python Version:
   python3 --version

2. Install a Package:
   python3 -m pip install <package_name>

3. Install from `requirements.txt`:
   python3 -m pip install -r requirements.txt

4. Run a Python Script:
   python3 script_name.py

5. Create a Virtual Environment:
   python3 -m venv env

6. Activate Virtual Environment:
   source env/bin/activate

7. Deactivate Virtual Environment:
   deactivate

8. Upgrade `pip`:
   python3 -m pip install --upgrade pip

9. List Installed Packages:
   python3 -m pip list

10. Uninstall a Package:
   python3 -m pip uninstall <package_name>


Git Commands
------------

1. Initialize a Git Repository:
   git init

2. Clone a Repository:
   git clone https://github.com/yourusername/your-repository.git

3. Check Repository Status:
   git status

4. Stage Changes (a specific file):
   git add <file_name>

   OR stage all changes:
   git add .

5. Commit Changes:
   git commit -m "Your commit message"

6. View Commit History:
   git log

7. Push Changes to Remote Repository:
   git push origin main

8. Pull Changes from Remote Repository:
   git pull origin main

9. Create a New Branch:
   git checkout -b new-branch-name

10. Switch to an Existing Branch:
    git checkout branch-name

11. Merge a Branch:
    git merge branch-name

12. Remove a Remote Branch:
    git push origin --delete branch-name

13. Remove a Local Branch:
    git branch -d branch-name

14. Configure Git User Info:
    git config --global user.name "Your Name"
    git config --global user.email "you@example.com"

15. Set Remote Repository URL:
    git remote set-url origin https://github.com/yourusername/new-repository.git