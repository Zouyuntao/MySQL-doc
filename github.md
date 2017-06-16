# MySQL-doc
## Day2
### 注册github网站,outlook邮箱，
#### 用户名：Zouyuntao 邮箱名：zouyuntaodevil@outlook.com
### github的简介
#### GIT 是一个分布式版本控制软件，最初由林纳斯·托瓦兹（Linus Torvalds）创作，于2005年以GPL发布。最初目的是为更好地管理Linux内核开发而设计。是目前世界上最先进的分布式版本控制系统.
###### 相关链接 [github](http://github.com)
#
### github基本命令
#### 安装：sudo apt-get install git
#### 将当前目录创建成git仓库：git init
#### 创建成功了, 并提示这是一个空仓库：ls -al .git
#### 查看当前状态：git status
#### 文件加到仓库:git add README
#### 提交:git commit
### github的远程连接
连接到网络github服务器 git remote add origin https://github.com/
将远程的仓库的信息更步到本地：git fetch origin
同步master分支：git push origin master
同步其它分支：git push origin branch-name
从远程仓库同步：git clone 
git pull
