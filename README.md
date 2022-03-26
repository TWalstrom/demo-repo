# Demo

Some Description!

## Starting a repo locally

mkdir new-folder-for-repo-name
cd  new-folder-for-repo-name
sudo nano new-filename.txt
  - add in stuff
git init
git status (should show new-filename.txt as untracked)
git add new-filename.txt
git commit -m "put some comment/description here"
create empty repo in github to link to
git remote add origin put-empty-repo-link-here
get remote -v
get push -u origin master (-u so dont have to type origin master anymore)

## branching/forking

- show available branches
git branch

- create new branch and switch to it
git checkout -b new-branch-name-here

- switch back to main branch
git checkout main

- switch back to new-branch-name-here
git checkout new-branch-name-here

- do a git status to see your changes in that branch

- do a git add to save changes
git add name-of-file-you-added-or-changed

- do a git commit to stage changes
git commit -m "updated readme in test-branch"

- shows the code changes
git diff

- merge the branches together locally
git merge test-branch

- more likely will do a git push
git push
- most likely your new branch wont exist will do
git push -u origin test-branch
- -u is quicker to set upstream




