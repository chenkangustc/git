# git
## 版本控制
|命令|功能
|---|---
|git log|查看commit id
|git reflog|查看id简称
|git reset --hard [commit id]|回到历史版本
|git add [file]|添加到暂存区
|git commit -m ''|commit
## 分布式
|命令|功能
|---|---
|git remote origin [website]|关联远程仓库
|git push -u origin master|推送（首次推送加-u,关联分支）
|git clone [website]|clone远程分支
## branch
|命令|功能
|---|---
|git branch [branch]|创建分支
|git checkout [branch]|切换分支
|git branch|查看所有分支
|git merge [branch]|合并指定分支到当前分支
|git branch -d [branch]|删除指定分支
