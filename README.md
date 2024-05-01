# IPWA02-01_E
PROGRAMMING INFORMATION SYSTEMS WITH JAVA EE

# Main commit command
this will contain all git command 

## Git command 
****Git command :***
* `git commit -m "message" -m "discrption this optional"`

***if commit did not work you can use below config command:***
* `git config --global user.email "izz_sheran@hotmail.com"`
* `git config --global user.name "BAWER"`
* `git push origin master`  -> *this to push change to github*

* `git pull`  -> *this to get update one files from github*

* repo -> repository
* `clone` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `add` -> track your files and changes with Git
* `commit` -> save your changes into Git
* `push` -> push your changes to your remote repo on Github (or another website)
* `pull` -> pull changes down from the remote repo to your local machine
* `git branch` -> show branch
* `git checkout -b f-readme-1-izzuddin`  -> diclear a new feature branch
* `git checkout nameOfBranch`  -> Switch betwheen branches for 
* `git diff`  -> show diffrenace betwheen 2 branchs
* `git push -u origin f-readme-1-izzuddin` -> push from new branch 
* *you can push your changes from new branch in order to compear from github*
* *from gitHub you can compear and add more comment about chnages*
* `git branch -d f-readme-1-izzuddin` -> Delete created branch 

* `status` -> check to see which files are being tracked or need to be commited
* `init` -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase

* `git reset --soft HEAD~1` -> This command will move the HEAD pointer to the previous commit, keeping your changes staged.

* `git reset --hard HEAD~1` -> Please be cautious when using git reset --hard as it will remove all changes in the last commit permanently
* `git log` -> this will shows all commit history so we can undo spesfic one 
* `git reset commit id` -> id will be get it for git log 47dc221b25b5de57e28d90f2f1a1a92ece29a67e

* ***Please note after push this will not work we can use flowing to undo change after push command ***
* `git revert <commit_id>` -> by using this we can revert spesfic commit and we can do commit again in order to chnage it in github 
* **Adding new file** -> use git add filename -> commit ->push

## Generating a new SSH key and adding it to the ssh-agent
* `ssh-keygen -t ed25519 -C "izz_sheran@hotmail.com"`
* *Note: If you are using a legacy system that doesn't support the Ed25519 algorithm, use:*
* ` ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
* `Generating public/private ALGORITHM key pair.` -> *This creates a new SSH key, using the provided email as a label.*

* *When you're prompted to "Enter a file in which to save the key", you can press Enter to accept the default file location. Please note that if you created SSH keys previously, ssh-keygen may ask you to rewrite another key, in which case we recommend creating a custom-named SSH key. To do so, type the default file location and replace id_ALGORITHM with your custom key name.*

* `Enter file in which to save the key (/c/Users/YOU/.ssh/id_ALGORITHM):[Press enter]`
* *for more info please visit this link:* https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent


