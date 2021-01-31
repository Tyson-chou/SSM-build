# SSM-build
这是第一个ssm整合项目

## 可能会出现的问题
1.出现 NotClassFound ，tomcat启动失败，这是因为在WEB-INF下没有导入依赖，新建lib包，并把依赖导入可解决

2.tomcat运行成功，但是点击跳转页面出现404，这是在web.xml 没有配置springmvc文件启动

如果使用三句import在总文件里，那么web.xml的DispatcherServlet的param-value写的是总文件

如果仅仅只有三个分类的配置文件，没有给他集合起来的那种，那么web.xml的DispatcherServlet的param-value写的是spring-mvc.xml
