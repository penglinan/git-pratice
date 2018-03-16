
# Git 学习资料整理笔记
## 1 课程介绍
## 2 Git基础命令
- touch 文件名字 新建文件
- mkdir 文件夹名字 新建文件夹
- ‘git init’初始化目录
工作区-> 暂存区
- git add <文件名或目录名> 提交工作区文件到暂存区
工作区->暂存区->本地版本库
-‘git commit -m’ "为什么要提交的注释" 提交到本地版本库
-‘git status’查看工作区状态
- 'git diff' <文件名/目录名称> [--cached] 版本内容对比
## git log

- git log 
- git log <-number>
- git log -p <-number> 最近两次之间的差异
- git log --stat  缩略行的形式显示
- git log --oneline  以一行的形式显示版本
--gitk    gui界面的形式显示
## git reset 
- git reset  --hard <版本号>
- git reset <版本号>
- git reset --soft <版本号>
- git reset --hard HEAD^
## git rm/mv
- git rm <file/menu>
- git rm --cached <file/menu>
- git mv <文件原来位置><文件或目录的新位置>
- git mv <文件的旧名字>
## git config
- git config --global user.name "penglinan"
- git config --global user.email "774032263@qq.com"
- git remote add 名字 地址
- git push -u 名字 分支 
## git remote 
- git remote add <别名> <https:...>  给地址取名字
- git remote remove <别名>   删除他
- git remote show  显示所有别名
- git remote rename <原名> <新名>
- git remote -v
## git push
- git push <remote name> <版本分支>
- git push -u <remote name> <版本分支>
- git push --all 推送所有分支到服务器
- git push --force <remote name> 强制上传，不管与其他开发者的冲突
## git branch 
- git branch <new name> 创建新分支
- git checkout <branch name> 切换到xx分支
- git checkout -b <branch name> 创建新分支，并切换到新分支
- git merge <branch name> 合并分支
- git rebase <branch name> 合并分支
- git push origin [name]  创建远程分支(本地分支push到远程)
- git push origin :heads/[name] 删除远程分支
- git branch
- git branch -D <branch name>
## git tags
- git tag
- git tag -a <new tag name> -m <tag name describe>
- git show <tag name>
- git push <remote name> <tag name>
- git push <tagname> --tages
