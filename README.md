# 个人简历

- 手机：17762569163
- Email：yanhaod96@gmail.com
- QQ：17762569163
# 个人信息

 - 闫孟浩/男/1998.0528 
 - 专科/湖北职业技术学院
 - 技术博客：[http://blog.tongsong.top/](http://blog.tongsong.top/) 
 - Github：[https://github.com/yanhaod ](https://github.com/yanhaod)
 - Github Resume: [https://github.com/yanhaod/resume](https://github.com/yanhaod/resume)
 - 期望职位：Java 开发程序员
 - 期望城市：武汉

# 技术文章


## 技术文章推荐

- [可能是把Java内存区域讲的最清楚的一篇文章](https://juejin.im/post/5b7d69e4e51d4538ca5730cb)

- [搞定JVM垃圾回收就是这么简单](https://juejin.im/post/5b85ea54e51d4538dd08f601)

- [前端&后端程序员必备的Linux基础知识](https://juejin.im/post/5b3b19856fb9a04fa42f8c71)

- [可能是把Docker的概念讲的最清楚的一篇文章](https://juejin.im/post/5b260ec26fb9a00e8e4b031a)

# 项目经历

## 项目一

### 紫金网 项目

项目描述

紫金网是一个在线商城系统，主要进行医疗产品的销售。整个项目采用微服务架构使，用SSM框架作为基础，利用Maven搭建Pom做依赖管理，包括单点登录、后台产品管理、前台产品检索、购物车管理、订单管理、消息推送等子系统。整个系统使用Eureka作为服务的注册中心和服务发现功能，在用户访问我们的接口必须先注册；使用Confie作为配置文件中心，可以简化我们很多的文件配置从而花更多的时间在业务代码上；使用Feign进行远程服务的调用，在高并发的情况下简单的调用已经不能满足我们的要求，使用Feign可以在高并发的系统依然保持正常；使用Hystrix断路器防止雪崩现象，在服务链之间一个程序出现问题不至于发生雪崩现象；使用Zuul作为网关实现负载均衡；使用Bus作为消息总线实现配置文件的的扩散过程；使用LCN作为分布式事务管理系统；使用Redis作为缓存将主要的菜单以及读写频繁数据存入Redis,便于更加高效的开发；使用FastDFS作为文件管理系统实现图片的上传。后台管理系统利用EasyUI直接操作数据库，进行产品的读取与CRUD操作。前台检索系统操作Solr索引库，提高检索效率，同时使用ZooKeeper + Solr搭建SolrCloud集群。保证检索系统的高可靠性，并将产品图片保存到Nginx静态资源服务器，提高系统性能。每个子系统都采用Nginx反向代理，采用特定算法实现访问的负载均衡，以处理高并发情况；用户提交订单后，将订单信息保存到数据库；其中后台产品管理、购物车管理、订单管理需要用户登录才能访问操作，结合Redis + Cookie实现用户的单点登录。整个系统实现了服务的高并发和高可用。

负责模块:

参与项目的需求分析与项目功能模块的制定；

主要负责后台系统商品的添加和检索功能、以及树节点的CRUD操作。其次还负责单点登录系统模块为整个系统提供授权和认证的功能以及当用户下单时用微信进行消息推送。

负责项目集群环境的搭建，主要是Redis集群的搭建。

## 项目二

### 易租商城 项目

项目描述

易租商城采用SSM框架，包括车辆管理、客户管理、汽车出租管理、出租单位管理、检查单管理、统计分析管理等子系统。客户表一对一关联车辆表，车辆表完成RBAC的权限控制；根据登陆用户的权限，选择性显示zTree权限树；使用Shiro进行细粒度的权限控制，判断用户的每个请求是否拥有操作权限；使用Zzxing.生成客户信息二维码，并利用POI生成订单Excel表格；使用FastDFS方式上传汽车图片时；使用Redis缓存思想存储读写频繁的数据。

负责模块:

参与项目的需求分析与项目功能模块的确定；

负责客户管理、检查单管理、统计分析模块的代码编写、测试与优化。


# 技能清单

以下均为我熟练使用的技能

1. 掌握JavaSE,JavaEE知识

2. 掌握OOP与AOP编程思想。

3. 掌握Eclipse、IDEA、Navicat、Tomcat、SVN、Git、Maven,的使用。

4.   掌握Spring、SpringMVC、Springboot、SpringCloud、MyBatis、MyBatis Plus框架技术。

5. 掌握MySQL、Oracle数据库操作，熟悉数据库的优化。

6. 掌握 Linux操作部署，及开发环境的搭建。

7.   掌握Nginx静态资源服务器的搭建及Nginx反向代理和集群搭建。

8.   掌握RBAC权限控制，熟悉Shiro安全框架、 Activiti工作流的使用。

9.   掌握Solr检索服务，熟悉Solr + ZooKeeper搭建SolrCloud分布式搜索服务。

10.  掌握Redis非关系型数据库的操作及Redis集群的搭建。

11.  掌握 ZooKeeper、Dubbo分布式协调服务的使用。

12. 掌握Mycat数据库中间件服务及Mycat集群的搭建。

13.  掌握Dubbo、Feign远程服务的发布与调用。

14.  掌握 Docker容器的使用。

15.  熟悉HTML、JS、CSS、jQuery技术，掌握AJAX异步交互技术。

16.  熟悉 AcitveMQ消息中间件的使用。

# 自我评价

性格踏实稳重，积极乐观，有强烈的集体荣誉感与责任意识，有较强的学习能力，乐于接受新事物与新技术，爱好爬山，敢于挑战。


### 感谢您花时间阅读我的简历，期待能有机会和您共事。

 
