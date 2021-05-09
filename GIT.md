# Git Lifesavers
1. [Cheat Sheet](https://dzone.com/articles/useful-git-commands)
2. Keeping a fork up to date. Original [article](https://medium.com/@topspinj/how-to-git-rebase-into-a-forked-repo-c9f05e821c8a).
```
git remote add upstream https://github.com/original-repo/goes-here.git

git fetch upstream

git rebase upstream/master

git push origin master --force

```
3. Getting new changes from master into another branch. Original [article](https://stackoverflow.com/questions/5340724/get-changes-from-master-into-branch-in-git).
```
git checkout other_branch

git rebase master

```

4. [Video](https://www.youtube.com/watch?v=viY1BbKZhSI) for squashing commits.