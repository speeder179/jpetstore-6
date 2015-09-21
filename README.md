MyBatis JPetStore
=================

[![Build Status](https://travis-ci.org/mybatis/jpetstore-6.svg?branch=master)](https://travis-ci.org/mybatis/jpetstore-6)

![mybatis-jpetstore](http://mybatis.github.io/images/mybatis-logo.png)

JPetStore 6 is a full web application built on top of MyBatis 3, Spring 3 and Stripes. It is available for downloading in the downloads section of MyBatis project site. In this section we will walk through this sample to understand how is it built and learn how to run it.

See: http://www.mybatis.org/spring/sample.html

## Tomcat7 JNDI配置
例子用JNDI配置Mysql5数据源实现读写分离
- server.xml配置参考tomcat7_server.xml
- context.xml配置参考tomcat7_context.xml

## Running with Tomcat 7
Running JPetStore sample under Tomcat 7 (using maven).
- Clone this repository
- Open command prompt/shell and change to cloned directory
- Issue following command to run project using Tomcat 7

mvn clean tomcat7:run

- Run application in browser http://localhost:8080/jpetstore/ 
- Press Ctrl-C to stop the server.
