**需要完整代码可以加qq  931708230 或者加微信 ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**

#超市账单管理系统 #java web #java #毕业设计 #springboot #课程设计 #编程 #vue #mybatis #源代码 

## 基于Vue和SpringBoot的超市账单管理系统

## 一、系统介绍

管理员：
- 系统基础管理：对登入用户、部门、角色、权限进行维护。       
- 商品管理：对超市所出售的商品档案进行维护。      
- 供应商管理：对超市所合作的供应商档案进行维护。      
- 账单管理：对超市所管理的账单档案进行维护。  

职员：商品管理、账单管理

经理：商品管理、账单管理、供应商管理

## 二、所用技术

前端采用View UI组件库，后端集成MyBatisPlus连接MySQL数据库，采用Spring Security做权限控制。    


## 三、环境介绍

基础环境 :IDEA/eclipse, maven3.x, JDK 1.8 , Mysql, node.js

源码+数据库脚本 

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)

![contents](./picture/picture9.png)

![contents](./picture/picture10.png)


## 五、浏览地址

http://localhost:8081/

管理员账号：admin  密码： 123456

职员账号：staff1 密码： 123456

经理账号：header1 密码： 123456
	
**需要完整代码可以加qq  931708230 或者加微信 ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**

## 安装教程

1.本机安装GIT，输入命令

```java
git clone https://gitee.com/ynwynw/bill-system.git
```

2.前端使用VsCode打开front文件夹，控制台输入npm i 安装依赖

3.前端控制台输入npm run dev 运行（默认8080端口）

4.控制台cd到redis目录，运行以下命令

```java
redis-server.exe redis.windows.conf
```

5.导入数据库（bill.sql）

6.使用idea导入back后端项目，maven方式导入，运行(默认1314端口)！