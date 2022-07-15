# 在github上新建项目后通过命令行把本地仓库与远程仓库关联起来
1、git remote add origin github项目地址
2、git branch -M master 本地分支重命名为master
3、git push -u origin master 把本地分支推送到远程仓库 远程仓库是空仓库时 需要使用 -u