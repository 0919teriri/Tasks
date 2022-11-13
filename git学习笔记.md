# git学习笔记  
## 初始化  
`git config --global user.name "名字"`  
`git config --global user.email "邮箱"`
## 创建本地仓库  
创建一个文件夹  
`git init`得到一个含有隐藏文件.git 的文件夹  
* 暂存区到本地仓库  
`git add 文件名`  
`git commit 写日志`  
`git log`修改后可以重复以上的操作  
回退`git reset --hard文件ID`  
## 推送到远程仓库  
github，gitee 两种方法SSH 和HTTP  
