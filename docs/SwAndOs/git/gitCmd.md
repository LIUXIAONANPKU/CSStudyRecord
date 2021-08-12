# Git 命令与技巧


## 新建

* git init



## 提交

* git commit
* git add

## 查看

* git diff 
* git status
* git log
* git log --graph --pretty=oneline --abbrev-commit
* git reflog
* git stash list


## 撤销与恢复

* git checkout -- file-name
* git reset HEAD file-name
* git stash 
* git stash apply
* git stash pop


## 删除

* git rm file-name



## 版本跳转

* git reset --hard commit_id


## 分支管理

* 创建分支
    + git checkout -b branch-name
    + git branch branch-name
    + git switch -c branch-name

* 查看分支
    + git branch

* 切换分支
    + git checkout branch-name
    + git switch branch-name

* 合并分支
    + git merge branch-name
    + git merge --no-ff -m  merge_message  branch-name


* 删除分支
    + git branch -d branch-name
    + git branch -D branch-name


* 合并单次提交
    + git cherry-pick commit_id

* 整理历史线
    + git rebase

* 远程仓库
    + git remote
    + git remote -v
    + git push origin branch-name
    + git pull
    + git checkout -b branch-name origin/branch-name
    + git branch --set-upstream branch-name origin/branch-name


