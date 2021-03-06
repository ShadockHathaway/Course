# 爱影网影评系统 需求规格说明

## 补充需求

### 1、功能性

#### 1）日志和错误处理：在持久性存储中记录所有错误
#### 2）舆论管理：对于发表不良言论的用户，管理员可以将其拉黑
#### 3）同步性：用户和管理员对影评系统进行的操作实时同步
#### 4）安全性：所有用户都需要经过认证

### 2、可靠性

#### 1）可恢复性：管理员可以随时对影片获影讯信息进行修改，以防信息有误的情况出现
#### 2）效率：当用户向服务器发出请求时，JSP就会转换被请求的文件为Servlet代码，由于用户提出请求后代码才会执行，所以在第一次调用代码时加载时间会比较长，而经过第一次的编译和执行后，代码就可以在后台独立运行，让程序的运行始终保持高效率
#### 3）可适应：“爱影网”影评系统采用了Browser/Server模式进行开发，在B/S体系架构下，用户只需要通过客户端的浏览器向服务器发出请求而不需要另外安装专门的客户端软件，这大大简化了客户端的工作

### 3、可用性

#### 1）可视化：在展示页面使用电影海报加文字的形式进行展示，让网站色调统一。响应式布局，根据窗口大小调整布局，避免出现某些信息被隐藏的情况
#### 2）用户体验：避免各项功能接口过深，提供个人中心一站式管理功能

### 4、法律问题

#### 1）信息真实：爱影网影评系统会保证所有影片、影讯信息的真实可靠，避免诋毁影片或捏造影讯的情况出现
#### 2）文明评论：实时监控用户发布影评，对于发布不文明内容影评者一律拉黑

对于网络言论的相干法律有：

1、《刑法》第二百二十一条规定，捏造并散布虚伪事实，损害他人的商业信誉、商品声誉，给他人造成重大损失或者有其他严重情节的，处二年以下有期徒刑或者拘役，并处或者单处罚金。

2、《中华人民共和国刑法》第二百四十六条规定：“以暴力或者其他方法公然侮辱他人或者捏造事实诽谤他人，情节严重的，处三年以下有期徒刑、拘役、管制或者剥夺政治权利。
具有下列情形之一的，应当认定为刑法第二百四十六条第一款规定的“情节严重”：

（一）同一诽谤信息实际被点击、浏览次数达到5000次以上，或者被转发次数达到500次以上的；

（二）造成被害人或者其近亲属精神失常、自残、自杀等严重后果的；

（三）二年内曾因诽谤受过行政处罚，又诽谤他人的；（四）其他情节严重的情形；

此外，一年内多次实施利用信息网络诽谤他人行为未经处理，诽谤信息实际被点击、浏览、转发次数累计计算构成犯罪的，应当依法定罪处罚。
