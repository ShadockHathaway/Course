# 爱影网影评系统 产品特性库

编写产品Backlog需要关注的几个点：
- ID：统一标识符，只是用来区分故事的递增数字
- Name：简短的、描述性的故事名
- Importance：产品负责人评估的一个数字，数字越大代表这个故事越重要
- Initial estimate：初步评估，完成该故事所需的工作量，单位是story point，相当于一个理想的人天(man-day)
- How to demo：描述这个故事应该怎么进行
- Notes：解释

## 产品Backlog

| ID | Name | Imp | Est(man-day) | How to demo | Notes
| :--: | :--: | :--: | :--: | ----------- | ------------ |
| 1 | 注册登陆 | 10 | 5 | 默认直接登陆，需要用户名和密码进行登陆，登陆成功后显示用户的头像和用户名；如果没有账号，则进入注册页面，需要提供用户名，密码，手机号，验证码来进行注册，注册成功后自动跳转回登陆页面。| 注册信息的合法性及重复性检测 |
| 2 | 影片中心 | 40 | 20 | 影片中心模块是“爱影网”影评系统的核心模块，在此模块下用户可以浏览、检索影片信息、“打卡”已看电影、发布个人影评。该模块下的电影和影评将采取分页显示的方式，以方便用户来回切换浏览。 | 用户收藏后的电影要显示“已收藏” |
| 3 | 影讯中心 | 20 | 15 | 作为“爱影网”影评系统的辅助功能，影讯中心模块满足用户浏览、查询、查看详情页的需求，并且影讯以分页的方式进行排列展示以便用户来回切换浏览。 | 影讯按时间优先级排序展示 |
| 4 | 个人中心 | 30 | 20 | 个人中心模块功能的设置是为了满足用户一站式管理个人信息的需求，在此模块下用户可以查看并修改个人资料、查看个人累积发布的影评并删除已发布影评、查看个人累积“打卡”的影片并将影片从收藏片单移除。 | 用户对影评进行删除后要在电影信息页同步 |
