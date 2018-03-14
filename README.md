# Git 学习资料整理笔记
## 1 课程介绍
## 2 Git基础命令
- ‘git init’初始化目录
工作区-> 暂存区
- git add <文件名或目录名> 提交工作区文件到暂存区
工作区->暂存区->本地版本库
-‘git commit -m’ "为什么要提交的注释" 提交到本地版本库
-‘git status’查看工作区状态
- 'git diff' <文件名/目录名称> [--cached] 版本内容对比
## 3 git log
- git log 
- git log <-number>
- git log -p <-number> 最近两次之间的差异
- git log --stat  缩略行的形式显示
- git log --oneline  以一行的形式显示版本
--gitk    gui界面的形式显示
## 4 git reset 
- git reset  --hard <版本号>
- git reset <版本号>
- git reset --soft <版本号>
- git reset --hard HEAD^
## 5 git rm/mv
- git rm <file/menu>
- git rm --cached <file/menu>
- git mv <文件原来位置><文件或目录的新位置>
- git mv <文件的旧名字>
## 6 git config
- git config --global user.name "penglinan"
- git config --global user.email "774032263@qq.com"
- git remote add 名字 地址
- git push -u 名字 分支
