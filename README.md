# study
今天是JavaEE的第一课

1.springMVC框架应用：

springMVC框架是Javaweb进阶高级课程，是目前中国大陆Javaweb项目的主流框架，大多数Javaweb项目都是由该框架或该框架改进版开发的。

2.在springMVC框架中需要学习和掌握的：

(a)HTTP协议的运行机制

(b)springMVC框架环境的搭建

(c)MVC框架结构及其运行机制

(d)pojo

(e)数据库实体映射

(f)用hibernate中间件操作数据库

(g)JSTL标签的使用

(h)AOP（面向切面编程）

未补充完

3.输入网址之后，HTTP的运行机制

浏览器向服务器（Tomcat）发送网址请求(URL)--->服务器解析求（解析链接地址--->寻找程序（在servlet中)---> 执行程序---> 返回请求

注意：HTTP是一种无连接的协议，一次请求响应后会断开  （引入session  让服务器记住曾经请求过，session是有时效性的，默认为20 min）

4.请求转发和重定向的区别：

(a)转发：向服务器发送一次URL

（b）重定向：向服务器发送两次URL（在同一台服务器上）

5.springMVC的环境配置

a.在WebRoot的WEB-INF中的lib 换成SpringMVC框架所用Jar包中的lib

b.配置web.xml中的servlet
