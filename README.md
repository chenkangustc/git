# git
## 版本控制
|命令|功能
|---|---
|git log|查看commit id
|git log --graph|可进一步看到分支图
|git log --pretty=oneline --abbrev-commit|显式结果漂亮
|git reflog|查看id简称
|git reset --hard [commit id]|回到历史版本
|git add [file]|添加到暂存区
|git commit -m ''|commit
|git tag [name]|给当前commit打标签
|git show [tagname]|显式tag对应commit的信息
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
|git merge --no-ff -m ''|合并后的历史有分支
|git branch -d [branch]|删除指定分支
