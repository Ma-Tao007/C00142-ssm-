
(C00142基于SSM的小型仓库库存管理系统)
# 项目简介
该系统有三类用户分别是管理员、员工、客户。
管理员（登陆后台）：可以对以上6个模块进行相应操作，还可以修改自己的密码。
员工（登陆后台）：可以对货物进行出入库，有货物库存模块和预定货物的客户信息模块（两个模块都是只可以进行查询和修改），可以对自己的个人信息进行修改和查看，还可以修改密码。
客户（前台）：在前台预定想要的货物，注册自己的相关信息和想要的货物。

仓库库存管理系统（即对一个大型仓库中的库存货物进行管理）

该系统有货物类型、货物库存、入库、出库、员工、预定货物的客户6个模块。
货物类型模块：货物类型编号、货物类型名称；
货物库存模块：货物编号、货物名称、货物类型、价格、库存量；
货物入库模块：货物名称、货物类型、入库时间、入库量、负责员工；
货物出库模块：货物名称、货物类型、出库时间、出库量、负责员工；
员工信息模块：员工编号、员工名称、性别、年龄、电话、登陆密码。
预定货物的客户信息模块：客户编号、客户名称、负责人、性别、电话、邮箱、预定的货物名称。

 # 项目获取
> [源码获取地址](http://www.manoncode.cn/details?id=142)

 
# 开发环境

运行环境：推荐jdk1.8；
开发工具：eclipse以及idea（推荐）；
操作系统：windows 10 8G内存以上（其他windows以及macOS支持，但不推荐）；
浏览器：Firefox(推荐)、Google Chrome(推荐)、Edge;
数据库：MySQL8.0(推荐)及其他版本（支持，但容易异常尤其MySQL5.7（不含）以下版本）；
数据库可视化工具：Navicat Premium 15（推荐）以及其他Navicat版本
是否maven项目：是


 # 项目技术
 
后端：Spring、SpringMVC、Mybatis、mysql
前端：jsp、bootstrap、jquery、ajax

 # 运行截图
 
![在这里插入图片描述](https://img-blog.csdnimg.cn/9b3f446e7e03467bab7730eef1b0475c.png#pic_center)

  -1.下载所得 

![-1.下载所得](https://img-blog.csdnimg.cn/img_convert/af29c8d1fb7be10a368d57be07cb6e04.png)

  1.项目结构 

![1.项目结构](https://img-blog.csdnimg.cn/img_convert/37519bab3bebd28a91bad289738d74e5.png)

  2.数据库表 

![2.数据库表](https://img-blog.csdnimg.cn/img_convert/938767b5403f846d2f7a5405fda02fe6.png)

  3.数据库模型 

![3.数据库模型](https://img-blog.csdnimg.cn/img_convert/9869190ee5bfd6b95672f4aca5a3bc63.png)

  4.首页1 

![4.首页1](https://img-blog.csdnimg.cn/img_convert/6bf5f6a2e25734311926c774c5261acb.png)

  5.首页下方 

![5.首页下方](https://img-blog.csdnimg.cn/img_convert/398b86f5111c18b30de49c6843a18f04.png)

  6.客户预定货物 

![6.客户预定货物](https://img-blog.csdnimg.cn/img_convert/47ed40e93120bc7ea7ab519c3eaf614b.png)

  7.登录页面 

![7.登录页面](https://img-blog.csdnimg.cn/img_convert/3a85f82f8c5448ab1ccda2dfdc3c5dcc.png)

  8.管理员登录首页 

![8.管理员登录首页](https://img-blog.csdnimg.cn/img_convert/6c0b67de4fb0c91536a59e16f5fdcdc3.png)

  9.入库信息管理-新增 

![9.入库信息管理-新增](https://img-blog.csdnimg.cn/img_convert/b7b895b87fe40945c1c7033c4f784ef1.png)

  10.出库信息管理-新增出库单 

![10.出库信息管理-新增出库单](https://img-blog.csdnimg.cn/img_convert/b9df609a611b16cc8bbf6eebd13b832a.png)

  11.类别管理 

![11.类别管理](https://img-blog.csdnimg.cn/img_convert/e92513ff177f5daaffabdd30e7be4958.png)

  12.货物管理 

![12.货物管理](https://img-blog.csdnimg.cn/img_convert/8bcf7dfc1cbd24bba3c7c37e9a51b725.png)

  13.员工管理 

![13.员工管理](https://img-blog.csdnimg.cn/img_convert/5629c9c285e956a46f4ea808a4910328.png)

  14.入库信息管理列表 

![14.入库信息管理列表](https://img-blog.csdnimg.cn/img_convert/f0111d1c82ebfc54ea9926f0f929f555.png)

  15.出库信息管理列表 

![15.出库信息管理列表](https://img-blog.csdnimg.cn/img_convert/2403f1ef468e49098413999bddb62cdf.png)

  16.客户预约信息 

![16.客户预约信息](https://img-blog.csdnimg.cn/img_convert/3c689b67f92076659dcdec058f0b93f6.png)

  17.修改密码 

![17.修改密码](https://img-blog.csdnimg.cn/img_convert/09575cd1f6aea24bc93bce5d29c34684.png)

  18.员工页面 

![18.员工页面](https://img-blog.csdnimg.cn/img_convert/cfbc3a5f1a40a097b4ee6cfe52862c19.png)
