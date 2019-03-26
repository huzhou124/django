# django的学习

## 1.安装virtualenv：

virtualenv是用来创建虚拟环境的软件工具，我们可以通过\`pip\`或者\`pip3\`来安装：

\`\`\`

pip install virtualenv

pip3 install virtualenv

\`\`\`

---

## 2.创建虚拟环境：

创建虚拟环境非常简单，通过一下命令就可以创建了：

\`\`\`

virtualenv \[虚拟环境的名字\]

\`\`\`

如果你当前的\`Python3/Scripts\`的查找路径再\`Python2/Scripts\`的面前，那么将会使用\`Python3\`作为这个虚拟环境。如果你当前的\`Python2/Scripts\`的查找路径再\`Python3/Scripts\`的面前，那么将会使用\`Python2\`作为这个虚拟环境。

---

## 3.进入虚拟环境：

虚拟环境创建好了以后，

\`\`\`

1.windows: 进入创建的虚拟环境文件夹的scripts中输入activate

2.\*inux类：进入虚拟环境：source /path/to/virtualnev/bin/activate一旦你inrush到了这个虚拟环境中，你安装包，卸载包都是在这个虚拟环境中，不会影响到外面的环境。

\`\`\`

---

## 4.退出虚拟环境：

推出虚拟环境很简单，通过一个命令就可以完成：\`deactivate\`

---

## 5.virtualenvwarpper的安装和基本使用

#### 安装：

\`\`\`

1.\*inux:pip install virtualenvwrapper

2.windows:pip install virtualenvwrapper-win

\`\`\`

#### 使用：

\`\`\`

1.mkvirtual \[name\]    创建一个虚拟环境

2.cdvirtual           去虚拟环境所在的目录

3.lsvirtual           列出虚拟环境

4.workon my\_env       切换到某个虚拟环境

5.deactivate          推出虚拟环境

6.rmvirtualenv        删除某个虚拟环境

\`\`\`

#### 修改virtualenvwrapper默认安装位置

在系统的环境变量中添加一个WORKON\_HOME

#### 创建虚拟环境的时候指定\`python\`版本

在使用\`mkvirtualenv\`的时候，可以指定\`--python\`的参数来指定具体的\`python\`路径：

\`\`\`

mkvirtualenv --python==C:\Python36\python.exe hz\_nev

\`\`\`

出现问题\(报编码问题时\)时：

\`mkvirtualenv django\_env --no-setuptools\`

### python-django版本：

django版本\|python

--\|--\|--

1.8\|2.7,3.2,3.3,3.4,3.5

1.9,1.10\|2.7,3.4,3.5

1.11\|2.7,3.4,3.5,3.6

2.0\|3.4,3.5,3.6

2.1\|3.5,3.6,3.7

|  |  |
| :--- | :--- |
|  |  |

## mysql下载地址：

windos版本：

```
https://dev.mysql.com/downloads/windows/installer/5.7.html
http://ftp.ntu.edu.tw/MySQL/Downloads/MySQLInstaller/
```

### web服务器和应用服务器以及web应用框架：

**web服务器**：负责处理http请求，响应静态文件，常见的有Apace，Nginx以及微软的ISS

**应用服务器**：负责处理逻辑的服务器。比如有php、python的代码，是不能直接通过nginx这种web服务器来处理的，只能通过应用服务器来处理，常见的应用服务器有uwsgi、tomcat等

**web应用框架**：一般使用某种语言，封装了常用的web功能的框架就是web应用框架，flask、django以及java中的ssh（Structs2+Spring3+Hibernate3）框架都是web应用框架。

### Django和mvc

Django是一个遵循mvc设计的框架，mvc是model、view、controller的三个单词的简写。分别代表模型、视图、控制器。一下图片说明这三者之间的关系：

!\[image\]\(FB586B2F3EBF4570AE4347E8B2B6C221\)

### Django的学习网址：

```
官网: https://www.djangoproject.com
Django book版本中文文档 http://djangobook.py3k.cn/2.0/chapter01/
Django 2.0版本的中文文档：http://python.usyiyi.cn/translate/django2/index.html
https://code.ziqiangxuetang.com/django/django-intro.html
```



