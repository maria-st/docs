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

