# CoderGroup


#### 预览地址
[http://codergroup.cn/](http://codergroup.cn/)
效果图见下面


#### 项目介绍
CoderGroup 是博主2017年准备做的一个开发者社区，至少实现用户发布文章笔记，技术问答，话题讨论等功能。开始是服务于身边的同学朋友，毕竟程序人生，你我陪伴，真好。但是，一拖再拖，竟然拖到了2018年，寒假和弟弟打了一个月的王者荣耀，开学后又准备春招，就浅尝辄止了。到了4月份放弃春招，专心做好这个项目。但是，很不幸，博主因为沉迷于爱情的海洋，进度非常缓慢，也暂时放弃了一些功能(比如话题讨论)。一边上课，一边恋爱，终于在6月份完成了，当初说好的20天完成呢，竟然用了几倍的时间。


#### 技术要点
本项目使用的是 SpringBoot1.5.9 版本，起初用的是 SpringBoot 2.0,但是觉得还是会遇到很多问题，而且新版本也缺少资料，于是中途修改了版本。
ORM框架用的 Spring Data JPA，权限管理用的是 Spring Security。
以 MySQL 作为数据库，同时用 Redis 数据库缓存几个排行榜。
图片上传使用第三方上传——七牛云，最终项目部署在腾讯云服务器(花了不少钱，痛)，使用 jar 部署方式稳定运行中。
前端采用的是 Bootstrap 模板，支持响应式，方便移动端，电脑端不同用户。

#### 未来期望
因为时间有限，博主还要准备面试，复习基础，刷算法题，本项目还可能存在很多设计不足和实现不当，当然也有很多做得不完备。等找到实习后，稳定下来，博主再努力完善。到时候肯定还要将该项目构建成微服务，无论使用 Spring Cloud 还是 Dubbo。
总之，这个项目将永远不会停止，并且本站(codergroup.cn)将永久运行，并保证每个用户的数据安全。欢迎大家入驻 CoderGroup.

#### 注意
本项目源码只给了 java 类，没有给静态资源代码。
女朋友建议我不要开源，可能到时候我再完善一下开源给她做毕业设计了。
于是，我便先半开源，所以本项目无法部署，只能通过预览地址来查看。
这是一个遗憾，不过我相信在不久后，该项目将完全开源。


#### 补充
有什么问题，可以加QQ群：590480292(开发者技术交流群)
或者加我QQ/微信 847064370



#### 效果图
1、首页(高清图片无法完整显示，缩小模糊了下)
![](https://liuyanzhao.com/wp-content/uploads/2018/06/WX20180622-010202@2x-2-1024x629.png)
<br/>
2、用户个人中心(普通用户权限可用)
![](http://cdn.codergroup.cn/uploads/2018/6/22/saysky/1529601279202)
<br/>
3、管理员后台(管理员权限可用)
![](http://cdn.codergroup.cn/uploads/2018/6/22/saysky/1529601307309)




上次更新时间 -- 2018-06-22 01:01:09
