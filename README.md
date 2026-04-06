# **Learning the Git Basic's**
---

1. **Setup and Configuration**  
For setting up the Username : `git config --global user.name "Your Name"`  
For setting up the Email : `git config --global user.email "username@mail.com"`  
For checking the Git Settings/Config : `git config --list`  
For changing default Branch Name : `git config --global init.defaultBranch main`  
2. **Starting a Directory**  
You can either create a new local repository or copy an existing one.  
Initialize New Repo: `git init` (Run this inside your project folder)  
Clone Existing Repo: `git clone <url>` (Downloads a copy from a remote server like GitHub)  
3. **Core Workflow(Stage & Commit)**  
Git workflow involves moving code between four local and remote states: Working Directory, Staging Area, Local Repository, and Remote Repository.  
Update: Sync your local environment with the latest changes from the server (`git pull` - Read Later).  
Edit: Make changes to files in your working directory.  
Stage: Select specific changes to include in your next snapshot (`git add`).  
Commit: Save the staged changes to your local history with a descriptive message (`git commit`).  
Push: Upload your local commits to the remote server (`git push` - Read Later).  
4. **Branching & Merging**  
Branches allow you to work on new features without affecting the main code.  
List Branches: git branch  
Create New Branch: `git branch <branch-name>`  
Switch Branch: `git switch <branch-name>` or `git checkout <branch-name>`  
Create & Switch: `git checkout -b <branch-name>`  
Merge Branch: `git merge <branch-name>` (Combines changes into your current branch)  
5. **Remote Syncing**  
To share your code or get updates from a team, you must sync with a remote server.  
Add Remote: `git remote add origin <url>` (Connects local repo to a remote one)
Push Changes: `git push origin <branch-name>` (Uploads local commits)
Pull Changes: `git pull` (Downloads and merges changes from the remote)
Fetch Changes: `git fetch` (Downloads remote changes without merging them)
6. **Inspecting & Undoing**  
View History: `git log` (See past commits)  
Condensed History: `git log --oneline`  
Discard Local Changes: `git restore <file>`  
Hard Reset: `git reset --hard` (Deletes all uncommitted changes)  


## **Good To Know Information**
1. A hotfix commit refers to a code change made to immediately resolve a critical bug, security vulnerability, or functional failure in a "live" production system.  



