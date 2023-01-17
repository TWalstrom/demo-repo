# instructions for me because I always forget

## Starting a repo locally

- mkdir new-folder-for-repo-name
- cd  new-folder-for-repo-name
- sudo nano new-filename.txt
  - add in stuff
- git init
- git status (should show new-filename.txt as untracked)
- git add new-filename.txt
- git commit -m "put some comment/description here"

## Create empty repo in github to link to
- git remote add origin put-empty-repo-link-here
- get remote -v
- get push -u origin master (-u so dont have to type origin master anymore)

## Push changes to github
- git add -A
- git commit -m "put some comment/description here"
- git push
