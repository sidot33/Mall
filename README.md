# Mall
springboot商城微服务

目前实现了产品展示，手机验证码登录，认证授权，产品查询，订单记录，订单退订等功能。
支持使用swagger浏览。



使用项目需要安装Redis, ElasticSearch 7.x,Mongodb, RabbitMq.
导入项目到java编辑器（Eclipse，或者IDEA）
修改\mall3\mall\src\main\resource下的property配置文件的用户名及密码
点击\mall3\mall\src\mainjava\com\example\demo DemoApplication运行。
如出现连接错误，检查Redis, ElasticSearch 7.x,Mongodb, RabbitMq是否开启。
运行后：在浏览器输入：http://localhost:8080/swagger-ui.html即可访问全部功能。
