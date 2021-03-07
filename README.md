# Git笔记给
>1. Git config(肯 费 克)  --global(哥 咯 波) 全局变量 
>2. user.name 提交人名字
>3. user.email  提交人邮件
>4. git config –global user.name 
>5. git config –list 查看配置信息
* 提交步骤
>1.	git init 初始化git仓库
>2.	git status 查看文件状态
>3.	git add 文件列表 追踪文件 存入暂存区
>4.	git commit –m 提交信息  像仓库提交代码
>5.	git log 查看提交记录
* 撤销
>1. 用暂存区中的文件覆盖工作目录中的文件：git checkout 文件
>2. 将文件从暂存区中删除：git rm  --cached(抗 去 的) 文件
>3. 将git仓库中指定的更新记录恢复出来，并且覆盖暂存区和工作目录：git rest --hard commitID 
# 分支
* 分支命令
>1.	git branch 查看分支
>2.	git branch 分支名称 创建分支
>3.	git checkout 分支名称 切换分支
>4.	git merge 来源分支 合并分支
>5.	git branch –d 分支名称  删除分支（分支被合并后才允许删除）-D强制删除
# 暂时保存
>1.	储存零时改动：git stash
>2.	恢复改动：git stash pop
# Github
>1.	本地推送远程仓库
>2.	Git push 远程仓库地址（别名） 分支名称
>3.	Git remote add  远程仓库地址别名 远程仓库地址
>4.	Git push  -u 下次可以直接写成 git push
# 克隆仓库
>1.	Git  clone 远程库地址
# 拉取操作
>1. git pull 远程仓库地址 分支名
