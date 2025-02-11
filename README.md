# XianYu-Store
## 基于Django的二手咸鱼系统
# 一、前言论
目前移动互联网大行其道，人人都手中拿着智能手机，如果开发一个用在手机上的程序软件，那是多么的符合潮流，符合管理者和客户的理想。本课题就是开发一个基于微信小程序的校园二手物品交易平台，有管理员和学生两个角色。管理员可以在后台管理个人中心，学生管理，商品分类管理，商品信息管理，购买信息管理，出售信息管理，交流论坛，系统管理。学生可以注册登录，发布和购买商品，还可以收藏商品和在交流论坛发帖。
本基于微信小程序的校园二手物品交易平台服务端用Java开发的网站后台，接收并且处理微信小程序端传入的json数据，数据库用到了MySQL数据库作为数据的存储。这样就让用户用着方便快捷，都通过同一个后台进行业务处理，而后台又可以根据并发量做好部署，用硬件和软件进行协作，满足于数据的交互式处理，让用户的数据存储更安全，得到数据更方便。

# 二.技术环境
jdk版本：1.8 及以上<br>
ide工具：Eclipse或者 IDEA，微信小程序开发工具<br>
数据库: mysql5.7 （必须5.7）<br>
编程语言: Java<br>
java框架：SSM<br>
maven: 3.6.1<br>
详细技术：HTML+CSS+JAVA+Django+SSM+MYSQL+VUE+MAVEN+微信开发工具

# 三.功能设计
本次开发的微信小程序的校园咸鱼版二手物品交易平台，有管理员和学生两个角色。管理员可以在后台管理个人中心，学生管理，商品分类管理，商品信息管理，购买信息管理，出售信息管理，交流论坛管理，系统管理。学生可以注册登录，发布和购买商品，还可以收藏商品和在交流论坛发帖。
系统功能结构图如下所示：<br>
![image](image002.gif)

# 四.数据设计
概念模型的设计是为了抽象真实世界的信息，并对信息世界进行建模。它是数据库设计的强大工具。数据库概念模型设计可以通过E-R图描述现实世界的概念模型。系统的E-R图显示了系统中实体之间的链接。而且Mysql数据库是自我保护能力比较强的数据库，下图主要是对数据库实体的E-R图。



