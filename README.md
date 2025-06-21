This is a test file written in README.md which is a markdown file

Listed below is how Github and Git work:

Step 1: Initialise your repository using ```git init``` (initialises a git repository, code can be pushed to github)
Step 2: Create relevant files and add code (Eg: We have added README.md)
Step 3: Use the command ```git status``` for checking the status of your files.
    - If files are untracked, you need to add and commit them before pushing
    - If files are in staging area, you need to commit them and then push
    - If files are committed, you need to push
Step 4: Adding untracked files using ```git add [filename]``` to add a specific file or ```git add .``` to add all files
Step 5: Commit files in staging area using ```git commit -m "[commit-message]```
Step 6: Add remote origin using ```git remote add origin git@github.com:[username]/[repository-name].git```
Step 7: Push the changes using ```git push -u origin main```
