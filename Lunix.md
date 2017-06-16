# MySQL-doc
## Day1 
### Linux虚拟机的创建
##### 使用软件：VMwareWorkstation 以及 Linux镜像文件
### vim基本命令
##### i：在当前字符的左边插入，I：在当前行首插入
##### a：在当前字符的右边插入，A：在当前行尾插入
##### o：在当前行下面插入一个新行 ，O：在当前行上面插入一个新
##### h: 向前移动一个字符，j: 向上移动一行，k: 向下移动一行，l: 向后移动一个字符
##### yy: 复制当前一行，dd:剪切当前一行
##### p: 粘贴内容到游标之后，P: 粘贴内容到游标之前
#
### Linux文件操作命令
##### touch  file 创建一个新的文件 
##### cp file file1 复制文件
##### cp file  /home/linux/file1 复制文件到目录
##### ls -al 显示该目录下文件，包括隐藏文件
##### cat  file 以源码形式打开文件
##### tar xvf  file.tar.gz 打开压缩文件
#
### 虚拟机操作
#### 安装git,vim,更新源
#### 语句：sudo apt-get install git
####       sudo apt-get install vim
####       sudo arp-get install
#
### 练习vim打出下面程序
```c
#include <stdio.h>
int main(void){
printf(“hello world!”);
return 0;
}
```
#### gcc编译该程序，输出a.out文件
## 相关图片
