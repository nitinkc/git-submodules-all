# Git Submodules

Detached Head Problem

```sh
git log --graph --decorate --pretty=oneline --abbrev-commit master origin/master
git log -n 2
git checkout 957833d728b3249d22a3b3160f3a48b72c576d91
git checkout -b temp
git checkout master
git merge temp
// delete branch locally
git branch -d temp
```
