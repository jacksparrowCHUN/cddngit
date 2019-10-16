git checkout -b feature_x   # 创建一个叫做"feature_x"的分支并切换过去
git checkout master  # 切换回主分支
git branch -d feature_x # 删除新建的分支"feature_x"
如果不推送到远程仓库,新建的仓库是不会再远程大仓库显示的

git push origin <branch> # 推送到远程仓库 
