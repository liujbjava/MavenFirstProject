web.xml是一个项目的核心，看看它的一些配置：
配置 ContextLoaderListener 监听器
配置Spring字符编码过滤器
配置shiro 安全过滤器
配置Spring MVC 核心控制器 DispatcherServlet
配置一些页面
spring 和 apache shiro 是由一个 ContextLoaderListener 监听器 加载的配置文件，并初始化