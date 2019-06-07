# 爱影网影评系统 设计说明书

## 数据库设计

### 1、数据库ER图

### 2、数据库详细设计

    在应用程序的开发与设计中，最基础且最重要的环节就是数据库设计工作环节，由于应用程序的功能都是基于对各种数据的存储与修改而展开的，所以数据库的设计是一切程序操作的基础。高质量的数据库设计能够降低开发者的工作难度、合理存储用户数据、发挥自身安全性和稳定性。
    “爱影网”影评系统所包括的信息有电影信息、用户信息、管理员信息、影讯信息、影评信息。这些信息可以被抽象为下列系统所需要的数据项和数据结构：
    （1）电影信息（电影编号，电影名称，电影导演，电影演员，电影制片地区，电影封面，电影摘要）；
    （2）用户信息（用户名，密码，手机号，电子邮件，个性签名，用户昵称）；
    （3）管理员信息（用户名，密码）；
    （4）用户管理影评信息（影评发布时间，影评内容，影片编号）；
    （5）管理员管理影评信息（影评发布时间，影评内容，影评发布人）；
    （6）影讯信息（影讯编号，影讯标题，影讯作者，影讯摘要，影讯封面）；
    （7）黑名单信息（用户名）；
    （8）用户收藏片单信息（电影编号）；
    （9）隐藏片单信息表（电影编号）；
    （10）隐藏影讯信息表（影讯编号）。
    注：带下划线的表示主键。