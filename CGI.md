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
#
## Atom editor 开环境使用的插件


    activate-power-mode：动感插件 atl + ctrl + o :打开插件
    vim-mode：vim模式
    ex-mode：实现:w功能
    monokai：高亮显示
    atom-ternjs：JavaScript 自动补全
    autoprefixer：给 CSS 添加适当的前缀
    color-picker：选颜色
    emmet：写 HTML 的神器
    atom-beautify：美化代码，空格啊什么什么的
    autoclose-html：HTML自动补全闭标签
    file-icons: 增加许多图标,在侧边蓝文件名前面的icon,,很赞
    autocomplete-modules: 自动补全插件, 有HTML, CSS, python 等
    highlight-selected: 高亮当前所选的文字, 双击后全文这个词或变量都会变高亮.
    Open In Browser: 右键打开浏览器.
    atom-clock: 在bar显示 时间
    autocomplete-js-import: 模块导入智能提示
    autocomplete-modules: 模块智能提示【node_modules】
