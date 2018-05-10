# Library
A library management system written using Django.


### 如何使用

# 可以先安装pyenv管理python版本的
可以百度如何安装pyenv

之后就可以在电脑上安装多个python版本,随意切换

切换python版本到3.4.2
切换python版本到3.5.2

```
pyenv local 3.4.2
或者
pyenv local 3.5.2
```
确保对应的python版本是安装过pip包管理器的

确保安装依赖(python3)
用pip安装本项目的依赖
```
pip install -r requirements.txt
```

然后执行即可,服务就可以跑起来
```
python manage.py runserver 8000
```


主页：
http://localhost:8000/

后台页面:
http://localhost:8000/admin/

初始化用户名密码:

```shell
python manage.py create_admin_account --username admin --password admin
```

![][6]

主页：
![index][0]

书目检索页面：可以根据ISBN/书名/作者检索
![][1]


书籍信息爬取自豆瓣读书Top250，读者信息用Faker生成
登陆方式为电话号码，密码为*password*

![][3]


管理界面

![][4]

用户界面

![][5]

关于数据库
![][7]

[0]:http://upload-images.jianshu.io/upload_images/3645027-807d0c6c55b0e878.png
[1]:http://opsfsk07z.bkt.clouddn.com/search_page.png
[3]:http://opsfsk07z.bkt.clouddn.com/reader_info.png
[4]:http://opsfsk07z.bkt.clouddn.com/admin.png
[5]:http://opsfsk07z.bkt.clouddn.com/profile_1.png
[6]:images/admin.png
[7]:images/db.jpeg
