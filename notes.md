## Exercise 1: Git command line basics

- mkdir git-exercise
- cd git-exercise
- git clone https://github.com/mattpe/git-intro.git
- git remote -v
- git remote remove origin
- git remote add origin https://github.com/ainaral/git-exercise.git
- git remote -v
- git push -u origin main
- history
- git status
- git add .
- git commit -m "made notes"
- git status
- git push

## Exercise 2: Collaboration & conflicts

- git checkout -b notes
- git add .
- git commit -m "added new notes"
- git push origin notes
- git checkout main
- git merge notes
- git status
- git add .
- git commit -m "added new notes"
- git push
