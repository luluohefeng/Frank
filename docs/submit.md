# 提交代码

打开 powershell，进入项目目录

> cd D:\luluohefeng\Frank

## 1. 查看当前状态

git status : 查看哪些文件被修改、未加入暂存
> 红色=未暂存  绿色=已暂存

git add . : 加入当前目录所有改动到暂存区
> git add 后加具体文件名，加入该文件到暂存区

git commit -m "提交信息备注" : 把暂存内容固化成本地提交记录， -m 后写清修改内容方便追溯

> git pull : 从远程仓库拉取最新代码(多人协作时，推送前必执行，同步远程他人更新，防止代码冲突)

git push : 推送本地提交记录到远程仓库(Gitee/Github等)