![gh_17810254f3db_258](https://github.com/user-attachments/assets/59d4e45d-0a64-428f-a5ec-12a6b519cf7e)

 **郑重声明：项目经过本地测试，确保可以运行。项目仅供学习和毕业设计参考~** 


1.项目介绍

技术栈+环境：SSM + MySQL5.7及以上 + Maven + Tomcat8

门户网站：注册、登录、商品查询、商品发布、商品购买、购买记录、发表评论、收藏、订单中心等。

系统功能：用户管理、分类管理、物品管理、订单管理等

2.项目部署

创建数据库，导入项目中的sql文件

打开IDEA，open——>双击项目里的pom.xml导入项目

进入 src/main/resources/spring/mybatis.xml 12-14行，更具本地数据库的环境修改数据库连接

通过IDEA创建 Tomcat Local server启动项目 http://localhost:8090/secondshop/

管理员账号密码： 111111@qq.com/admin

用户账号密码：133333333@qq.com/123456 或者自行注册
