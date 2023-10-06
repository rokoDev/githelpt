# Git help:

- list all branches(remote and local): `$ git branch -a`
- switch to remote branch: `$ git switch -c test origin/test`
- create new branch from remote branch: `$ git branch --track <new-branch> origin/<base-branch>`
- create new branch from remote branch: `$ git checkout --track <new-branch> origin/<base-branch>`
- create new branch from remote branch with same name: `$ git checkout --track origin/<base-branch>`
- add remote: `$ git remote add origin https://github.com/rokoDev/githelpt.git`
- push branch `master` and set up branch it to track remote branch `master` from `origin`: `$ git push -u origin master`
- create new branch: `$ git branch <new-branch>`
- create new branch based on commit, tag or another branch: `$ git branch <new-branch> <base-branch>`