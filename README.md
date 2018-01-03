# jsets-jdbc-spring-boot-starter

在开发实践中，经常会遇到一些数据库表不多的项目，比如一些非业务性的功能系统、一些职责单一的微服务系统。

如果集成像MyBatis、Hibernate这样框架，相对整个系统架构而言有些偏重，采用jdbctemplate实现则更为轻量。

针对一些需要大量批处理操作、LOB字段操作、存储过程操作、复杂SQL操作的情况，使用jdbctemplate则更为直接便捷。

jsets-jdbc-spring-boot-starter在spring jdbctemplate之上进行了一些包装，支持部分常用的JPA注解，使得经过注解的实体可以像Hibernate一样进行增、删、改和获取。SQL构造工具、链式API等让查询操作更为灵活。动态实体映射使得各种查询不再需要写大量的RowMapper。



**功能简介：**

1：常用的JPA注解支持。

2：简化的批处理操作。

4：简化的分页操作。

5：灵活的链式查询API和SQL构造器。

6：实体属性动态映射。


