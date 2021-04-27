# community
<font face="黑体" >（价值1699元）Java高级工程师 - 高薪求职项目课</font>

牛客网高级后端项目，可用于本科毕业设计，校招或实习面试项目

涉及到Spring、SpringMVC、Mybatis的整合，以及SpringBoot去简化Spring的配置开发

主要的技术点：

登录注册功能：使用kaptcha去生成验证码，使用邮件完成注册，Redis优化验证码的保存，解决分布式session问题

使用拦截器拦截用户请求，将用户信息绑定在ThreadLocal上

构建Trie数据结构，实现对发表帖子评论的敏感词过滤

支持对帖子评论，也支持对评论进行回复

利用AOP对service的业务代码实现日志记录

利用Redis的zset并结合Redis实现点赞关注的功能

点赞关注后的系统通知，实时性不需要特别高，使用kafka实现异步的发送系统通知

使用ElasticSearch实现对帖子的搜索功能，以及结果的高亮显示

SpringQuartz实现定时任务，完成热门帖子的分数计算模块

使用本地缓存Quartz缓存热门帖子优化热门帖子页面，提高了QPS（10 - 200）
![image](https://user-images.githubusercontent.com/39627757/115350664-f7181500-a1e7-11eb-90df-d3b38eea2991.png)
![image](https://user-images.githubusercontent.com/39627757/115350723-06975e00-a1e8-11eb-821f-1352b36bef15.png)
![image](https://user-images.githubusercontent.com/39627757/115350746-0eef9900-a1e8-11eb-90d8-7e37992131fb.png)
![image](https://user-images.githubusercontent.com/39627757/115350771-19aa2e00-a1e8-11eb-99df-68c08d23ae56.png)
![image](https://user-images.githubusercontent.com/39627757/115350801-2169d280-a1e8-11eb-8dfc-7b1431c8953a.png)
