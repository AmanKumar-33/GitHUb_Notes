# GitHUb_Notes
This repository is basically for making a notes on github cmd.
**git init<directory>**
Create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository
**git clone <repo>** 
Clone repo located at <repo> onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH
**git config user.name <name>**
Define author name to be used for all commits in current repo. Devs commonly use --global flag to set config options for current user
**Git add <Directory**
Stage all changes in <directory> for the next commit. Replace <directory> with a <file> to change a specific file
**git commit -m “message”**
Commit the staged snapshot, but instead of launching a text editor, use <message> as the commit message.
**git status**
List which files are staged, unstaged and untracked.
**git log**
Display the entire commit history using the default format. For customization see additional options.
**git diff** 
Show unstaged changes between your index and working directory


**GIT Push**
The git push command is used to upload local repository content to a remote repository.
**git push <remote> <branch>**
Push the specified branch to , along with all of the necessary commits and internal objects. 
**git push <remote> --tags**
The --tags flag sends all of your local tags to the remote repository

**GIT PULL**
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository.




**git branch**
List all of the branches in your repository.
**git branch -d <branch>**
Create a new branch called ＜branch＞
**git branch -D <branch>**
Delete the specified branch. This is a “safe” operation in that Git prevents you from deleting the branch if it has unmerged changes.
**git branch -a**
Rename the current branch to ＜branch＞


**GIT CheckOUT**
you can switch between these branches using git checkout.
**git checkout -b ＜new-branch＞**
command accepts  -b argument that acts as a convenience method which will create the new branch and immediately switch to it.
**Switching branches is a straightforward operation** **git checkout ＜branchname＞**


**GIT Merge**
![image](https://github.com/AmanKumar-33/GitHUb_Notes/assets/89511864/bbf118b2-59e1-4ae7-8c83-461337d17f48)
it merge will combine multiple sequences of commits into one unified history.
**git checkout main
git merge new-feature
git branch -d new-feature**




