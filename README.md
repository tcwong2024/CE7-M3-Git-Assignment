<!-- ![git_banner-1024x265](https://github.com/user-attachments/assets/2da10d72-48d6-4bd2-a26a-e25307b4d491) -->
<img src="https://github.com/user-attachments/assets/2da10d72-48d6-4bd2-a26a-e25307b4d491" alt="git_banner" width="500" height="160">

# Git Assignment - Test and run the commands 

## Basic Git Commands :
| Commands | Description |
| ------ | ------ |
| ```git version``` | Displays the installed Git version. |
| ```git init``` | Initializes a Git repository in the current folder. |
| ```git clone <github repository>``` | Clones a repository from GitHub. |
| ```git status``` | Checks the local folder for any new or modified files. |
| ```git add .``` | Stages all new and modified files for the next commit. |
| ```git commit -m "<Message>"``` | Commits the staged changes with a descriptive message (replace <message> with your specific change description). |
| ```git log``` | View all the commits history of your repository. |
| ```git stash``` | Temporarily saves your changes without committing, allowing you to work on something else.  |
| ```git remote -v```| Displays the remote URLs that your Git repository is pointing to. |
| ```git remote set-url origin <NEW_URL>``` | Updates the local Git repository's remote URL if the GitHub repository's name changes. |

## Git Commands - Working on branch 
| Commands | Description |
| ------ | ------ |
| ```git checkout```| Switches between branches or restores files. |
| ```git branch```| Creates, lists, or deletes local branches. |
| ```git branch``` | Lists local branches. |
| ```git branch -r``` | Lists remote branches. |
| ```git branch -a``` | Lists local and remote branches. |
| ```git pull``` |  Fetches changes from the remote repository and merges them into your current branch. |
| ```git checkout -b <NEW_BRANCH>``` | Creates and switches to a new branch (e.g., FeatureUpdate-DevOps-0930-UpdateReadMe). |
| ```git push --set-upstream origin <NEW_BRANCH>``` | Pushes the new branch to the remote repository and sets the upstream tracking. |
| ```git checkout main``` | Switches to the main branch. |
| ```git pull``` | Downloads and merges changes from the remote repository into your current branch. |
| ```git fetch``` | Retrieves changes (commits, branches, tags, etc.) from the remote repository without merging them into your local branch. | 

## Assignment Hands-On Activity
| Steps | Description |
| ------ | ------ |
| Create github repository. | Repository Name: ```M3-Git-Assignment``` <br> Repository URL : ```https://github.com/tcwong2024/M3-Git-Assignment.git``` |
| Git clone the github repository | ```git clone https://github.com/tcwong2024/M3-Git-Assignment.git``` |
| Do files modification | - Add input.txt and update ReadMe, then push to GitHub: <br> ```git status``` <br> ```git add .``` <br> ```git commit -m "<Message>"``` <br> ```git push origin main``` |
| Crete new branch| ```git checkout -b <NEW_BRANCH>``` <br> ```git branch``` |
| Use new branch for modification | ```git checkout <NEW_BRANCH>``` <br>- Add or update file <br> ```git add .``` <br> ```git commit -m "<Message>"``` <br> ```git push --set-upstream origin <NEW_BRANCH>``` |
| Compare and Merge at GitHub| - GitHub repository will auto detect change, click "Compare & pull request" <br>- Add description and click "Create pull request" <br>- Owner review the changes, add comment and click "Merge pull request" if review ok <br>- Click the "Confirm merge" <br>- Delete the branch click "Delete branch" or keep it then done. |
|Update the main branch| - On your local terminal <br> ```git branch``` <br> ```git checkout main``` <br> ```git pull```|
