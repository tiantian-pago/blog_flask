# blog_flask
使用python3.5+flask1.0开发的简单博客
其中包括登录、登出、编写博客等基础功能，使用最轻量的 SQLite3 数据库存储数据。

首先
在python解释器中运行以下语句，初始化创建数据库表
from flaskr import init_db
init_db()
[admin@localhost blog_flask]$ python3
Python 3.6.8 (default, Nov 21 2019, 19:31:34) 
[GCC 8.3.1 20190507 (Red Hat 8.3.1-4)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> from flaskr import init_db
>>> init_db()
>>> 

运行服务
flask run -h [ip] -p [port]
