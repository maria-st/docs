# docs
Notes for myself
## How to push first project to github
1. Make sure you have a git installed or install it here https://desktop.github.com
2. Create a folder that you want to commit
3. Go to command line and `cd <your folder>` 
4. Initialize the local directory as a git repository `git init`
5. Stage the files that you want to commit `git add <filename>`. Or commit all the files `git add .`
6. Commit the files to your local repository `git commit -m "Your message about the commit"`
7. At the top right of any Github page, you should see a '+' icon. Click that, then select 'New Repository'
8. Now at the top of your GitHub repository's Quick Setup page, copy the link in the input right beneath the title. 
It will look something like https://github.com/yourgithub/test-repo.git
9. in a command line add your local repository to remote repository `git remote add origin https://github.com/yourgithub/test-repo.git`
10. Push your changes `git push origin master`

## How to commit to an open source project
1. Find the repository and Fork it
2. In a command line navigate to folder where the local repository will be stored `cd <your folder>`
3. In a command line type: `git clone [HTTPS ADDRESS]`, you can get http address from your github forked repository webpage. 
4. Make the changes in your local repository files.
5. Check the status `git status`
6. Stage the files that you want to commit `git add <filename>`. Or commit all the files `git add .` seems like nothing will happen in command line. It's OK. Files are staged (addded and ready for commit).
7. Commit the files to your local repository `git commit -m "Your message about the commit"`
8. In order to push the changes to the remote project find how branch is called `git remote`
9. Push your changes to the branch `git push origin <branch name>`. If it is the master branch `git push origin`. Enter your username and password if it is required.
10. Go to your Github repository (webpage: <code>) and create a 'New pull request'
11. Master of the repository that you commited to will make pull requests merge and changes will appear in the original master branch
12. Others will get the changes to local repositories by `git pull origin master`
13. I'm very hungry, please give me food!!! NOW!!
