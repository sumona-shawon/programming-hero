- Command line
    - `cd..`
    - `cd folder-name`
- Git author setup
    - `git config --global user.email "name@mail.com"`
    - `git config --global user.name "User's Name"`
- Create GitHub account, create public repository
- For the first time
    - `echo "# github-practice" >> README.md`
    - `git init`
    - `git add .`
    - `git commit -m "commit message"`
    - `git branch -M main`
    - `git remote add origin url`
    - `git push -u origin main`
- After setting the remote origin
    - `git add .`
    - `git commit -m "commit message"`
    - `git push`
- Create pages from repository's setting
- Common GitHub issues
    - `git --version` doesn't work → change powershell to git bash
    - error on pushing → don't forget to add & commit
    - pages don't work → missing index.html file
    - remote origin already exists → set remote origin
        - `git remote set-url`
- Working with Git (feature) branches
    - `git branch`
    - `git branch new-branch`
    - `git checkout branch-name`
    - `git push --set-upstream origin branch-name`
    - `git merge branch-name`
    - Merge Conflict → Current Change / Incoming Change
- [Common Git Commands](https://github.com/joshnh/Git-Commands)