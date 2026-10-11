Git: DVCS, copy available locally and stored on server through GitHub

git: --version --help
git config: --global user.name "Name" / --global user.email "email.com" (--local per project)

git status
git checkout <br_name> OR <commit_id>
git branch --list (--delete <br_name>)

clone repo -> create branch -> push changes to remote -> others pull changes (PR)

create branch -> add/commit files -> open/merge PR

_**Creating A Repo**_

Working Directory: Project files to make changes
Staging Area (Index): prep area for grouping changes to save to history
Repo: permanent record of project development history

git init -> git add folder/* (.) -> git commit --message "msg"


Created files show up in Source Control Tab ... stage changes to files & commit

_**Exploring Git History**_

HEAD: current position in project history

git log --all --oneline --graph

_**Comparing Changes**_

git diff: diff between working directory & staging area
git diff --staged: diff between staging area and previous commit
git diff HEAD~1: diff between current and previous commit

make changes to file, add to staging area, commit to repo

_**Working with Branches**_

Fast Forward Merge (DEFAULT): move new commits from child onto parent

git branch <br_name> -> git checkout <br_name> -> git merge










