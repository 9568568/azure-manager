## Azure 管理

原版：https://github.com/1injex/azure-manager

在原版的基础上 去广告、汉化。

安装教程：https://www.ydyno.com/archives/1404.html

'1、创建应用

使用下面的脚本创建应用

docker run -itd --name az \
--restart always \
-p 8888:8888 \
dqjdda/azure-manager

'2、初始化管理员账号与密码

docker exec -it az flask admin 用户名 密码
访问 http://IP:8888 进入管理页面

登陆后添加需要管理的账号
