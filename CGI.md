# Day6
## Apache安装
* sudo apt-get update
* sudo apt-get install tasksel
* sudo tasksel
#
## CGI
#### CGI(Common Gateway Interface) 是WWW技术中最重要的技术之一，有着不可替代的重要地位。CGI是外部应用程序（CGI程序）与WEB服务器之间的接口标准，是在CGI程序和Web服务器之间传递信息的过程。CGI规范允许Web服务器执行外部程序，并将它们的输出发送给Web浏览器，CGI将Web的一组简单的静态超媒体文档变成一个完整的新的交互式媒体。
## Apache开启CGI
* sudo ln -s /etc/apache2/mods-available/cgi.load /etc/apache2/mods-enabled/cgi.load
* service apache2 restart
* sudo mkdir /usr/lib/cgi-bin/sx
* sudo chmod 777 /usr/lib/cgi-bin/sx
# 
## 安装mysql的C语言库
* sudo apt-get update
* sudo apt-get install libmysqlclient-dev
###### 相关链接[CGI](https://boutell.com/cgic/)
#
## 补充函数fprintf
```C
int fprintf(FILE *stream, const char *format, ...);
功能： 将格式化的语句输出到指定的流
fprintf(stdin, "helloworld\n")  等价于 printf("helloworld\n);
```
## 补充函数atoi
```C
int atoi(const char *nptr);
功能：将一个字符串转换成对应的数字，比如：“1234” ==》 1234
```
#
## Atom安装
#### [下载链接](https://atom.io/)
#### 命令
* wget -c https://github.com/atom/atom/releases/download/v1.18.0/atom-amd64.deb
* sduo dpkg -i atom-amd64.deb
