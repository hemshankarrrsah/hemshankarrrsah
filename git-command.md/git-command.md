# Git commands
## After creating new projects
1. Git initialization
```
   git init
   ```
2. Adding files and folders to git for tracking notes for specific files
   ```
   git add [file_name]
   

   eg:git and index.html
   ```
   To add all *files* and folders (follow this)
   ```
   git add .
   ```
3. Git version save or `commit`
   ```
   git commit -m"[your_commit_message]"

   eg:git commit -m"auth feature done"
   ```
4. change main branch[optional step]
   ```
   git branch -M[your_new_branch_name]
   ```
5. Add remote url [link the remote repository url]
   ```

6. push the commited code to remote repo
   At initial (-u: upstream)
   ```
   git push -u origin [your_branch_name]
   ```
   After firsh push
   ```
   git push
7. To check the status of git(vcs)
   ```
   git status
   ```
8. To update the remote repo url
   ```
   ```markdown
   
   git remote set-url origin [your_repo_url]

   To Verify/Display added remote url:
   git remote -v
   ```
9. To config the user.name and user.email:
   ```


   Global Config:
   git config --global user.name [hemshankarrrsah]
   git config --global user.email [hemshankarrr@icloud.com]

   To Verify/Display Config (Note: enter to view more config and q to exit the opened editor):
   git config --list
   ```
   