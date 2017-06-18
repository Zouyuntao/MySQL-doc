
# Day2
### 注册github网站,outlook邮箱，
#### 用户名：Zouyuntao 邮箱名：zouyuntaodevil@outlook.com
#
### github的简介
#### GIT 是一个分布式版本控制软件，最初由林纳斯·托瓦兹（Linus Torvalds）创作，于2005年以GPL发布。最初目的是为更好地管理Linux内核开发而设计。是目前世界上最先进的分布式版本控制系统.
###### 相关链接 [github](http://baike.baidu.com/link?url=Mv1FTvCTYN2gqCX3MEHcrYnPWmqB3szTAn-S0sYK94Xp_nlHEqdJFaY4y_3s2wtZb8wLYsB4OW8XPBiIlw_x1q)
#
### github基本命令
#### 安装：sudo apt-get install git
#### 将当前目录创建成git仓库：git init
#### 创建成功了, 并提示这是一个空仓库：ls -al .git
#### 查看当前状态：git status
#### 文件加到仓库:git add README
#### 提交:git commit
#
### github的远程连接
#### 连接到网络github服务器 git remote add origin https://github.com/
#### 将远程的仓库的信息更步到本地：git fetch origin
#### 同步master分支：git push origin master
#### 同步其它分支：git push origin branch-name
#### 从远程仓库同步：git clone https://github.com/Zouyuntao/MySQL-doc.git   git pull
#
### 本地git仓库的恢复
#### 每次提交本地仓库都会有一个gitID，用来存储当时的状态和信息，使用该命令：git reset --hard(gitID),能恢复到该版本的所有文件
#### 从本地git库将文件移除：git rm --cached hello.c(注意：该操作不会删除文件，只是将文件从库中移除)
#### 每一次修改文件，都要重新添加关注，并重新提价，git add .
#
#### 通过这一天的学习，我们在本地使用命令行建立了一个git仓库，并添加文件，修改文件，提交本地仓库，提交到远程仓库
#
### 相关图片

