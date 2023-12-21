```shell
tree /f
```

```
│  manage.py 项目管理，启动项目，创建App，数据管理，不用修改
│
└─mysite
        asgi.py 异步接受网络请求，不用修改
        settings.py 配置文件，连接数据库，注册App
        urls.py URL和函数的对应关系，经常操作
        wsgi.py 同步接受网络请求，不用修改
        __init__.py
```

```
│  admin.py django默认提供的admin后台管理
│  apps.py app启动类
│  models.py 操作数据库
│  tests.py 单元测试
│  views.py 函数
│  __init__.py
│
└─migrations 数据库变更记录
        __init__.py
```

python manage.py runserver
