# mall整合SpringBoot+MyBatis搭建基本骨架
> 本文主要讲解mall整合SpringBoot+MyBatis搭建基本骨架，以商品品牌为例实现基本的CRUD操作及通过PageHelper实现分页查询

## mysql数据库环境搭建
* 下载并安装mysql5.7版本，下载地址：https://dev.mysql.com/downloads/installer/
* 设置数据库帐号密码：root root
* 下载并安装客户端连接工具Navicat,下载地址：http://www.formysql.com/xiazai.html
* 创建数据库mall
* 导入mall的数据库脚本，脚本地址：https://github.com/macrozheng/mall-learning/blob/master/document/sql/mall.sql

## 项目搭建

### 使用IDEA初始化一个SpringBoot项目
![img.png](img.png)