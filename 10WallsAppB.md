# 附录B Spring Boot起步依赖

Spring Boot起步依赖大大简化了项目构建说明中的依赖配置，因为常用的依赖聚合于更粗粒度的依赖。你的构建项目会传递解析到起步依赖中声明的其他依赖。

起步依赖不仅能让构建说明中的依赖配置更简单，还根据提供给应用程序的功能将它们组织到一起。例如，与其指定用于验证的特定库（比如Hibernate Validator和Tomcat的内嵌表达式语言），还不如简单地添加`spring-boot-starter-validation`起步依赖。

表B-1列出了Spring Boot的所有起步依赖，还有它们传递声明的依赖。

__表B-1 Spring Boot起步依赖__

> P188~194表格，表头翻译如下：

| 起步依赖（Group ID：`org.springframework.boot`）| 传递依赖 |
|---------------------------------------------|--------|

| [PREV](https://github.com/5202m/spring-boot-in-action-zh-cn/blob/master/09WallsAppA.md) | [NEXT](https://github.com/5202m/spring-boot-in-action-zh-cn/blob/master/11WallsAppC.md) |
