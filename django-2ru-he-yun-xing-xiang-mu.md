\# Django学习

\#\# 项目的运行：

python manage.py runserver

\#\# 结构分析：

1.\`manange.py\`：  

以后和项目交互基本上都是基于这个文件。一般都是在终端输入python manage.py \[子命令\]。可以输入python manage.py  

2.\`setting.py\`:保存项目的所有基本配置信息.  

3.\`urls.py\`:用来做url与视图函数映射的。以后来了请求，就会从这个文件中找到匹配的视图函数。  

4.\`wsig.py\`:专门用来做部署的。不需要修改



\# 视图函数

1.视图函数的第一个参数必须是request。这个参数绝对不能少    

2.视图函数函数的返回值必须是\`django.http.response.HttpResponseBase\`的子类对象。

广告

