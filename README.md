# 015springboot物流管理系统
015springboot物流管理系统


# Express-System
使用 spring boot，基于 ssm 框架和 shiro 安全框架，开发的一个物流管理系统。前端使用的是 H-ui 开源框架，运用了 Bootstrap table、zTree、PageHelper、jQuery validate 等插件。

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=164)

## 特点
1. 基于 spring boot、maven 构建；
2. 运用了 spring、spring mvc、mybatis 和 shiro 框架；
3. 采用了 RBAC 的思路设计系统，采用了 Mysql 作为数据库支持；
4. 不同的角色登录系统会有不同的菜单列表，且会根据角色返回特定的数据；
5. 拥有基础数据管理模块，管理员管理模块，角色管理模块，权限管理模块，客户管理模块，订单管理模块和业务处理模块；
6. 能够实现完整的业务流程：添加客户、添加订单、订单处理、财务报表。

## 细节介绍
1. 业务员访问时，只能访问客户管理、订单管理、业务处理菜单，且只有添加的权力，没有修改和删除的权力；
2. 业务员添加订单时，只能基于自己拥有的客户添加；
3. 业务经理拥有客户管理、订单管理、业务处理的所有功能，可以查看所有业务员的客户和订单；
4. 总经理角色可以查看所有数据，但是没有修改的权力；
5. 仓管员只有业务处理中，测量物品信息和入库的功能，其他数据不可修改；
6. 财务可以查看审核订单价格详情并导出为 excel 表格。

## 使用
需要的运行环境：
1. JDK 1.8；
2. Maven；
3. Tomcat 8；
4. mysql 8.0。

使用前修改 application.properties 里的数据库的连接信息即可。可以通过 dataBase 目录下的 sql 文件创建所需要的表，数据库名字为 logistic_system。

## 登录
> username:admin
> password:123456

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/124106_092f525e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/124114_0556d0fd_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/124122_a9e7241c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/124130_0d567a48_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/124138_d04b330e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/124145_e5a8d076_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/001259_b75db453_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/001316_a996efcf_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/001328_a5aa6414_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/001337_c83f3684_863230.png "屏幕截图.png")
