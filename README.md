# 微信小程序 - 超级课程表
### 说明：
该项目为本人的毕业设计，主体功能参考一款校园app-[超级课程表](https://baike.baidu.com/item/%E8%B6%85%E7%BA%A7%E8%AF%BE%E7%A8%8B%E8%A1%A8/1167485?fr=aladdin)。项目包括了四个模块，分别是个人主页、课程查询、成绩查询和树洞，其中，在个人主页输入账号（即学号）密码进行登录的时候，后台会模拟登录教务系统，以校验正确性，并返回登录结果；
在已登录的状态下可以进入课程查询和成绩查询模块，课程和成绩信息都是使用该账号模拟登录教务系统抓取的；树洞模块是调用api访问数据库进行树洞和评论的发表、删除操作。
### 服务接口：[查看代码](https://github.com/fupengfei058/super_course_schedule_api)
后端基于PHP的CodeIgniter框架提供API，以实现以下功能：
* 模拟登陆教务系统验证学号密码正确性
* 从教务系统抓取个人课表
* 从教务系统抓取个人成绩
* 操作本地数据库发表、删除树洞及评论
### 系统用例图：
![github](https://github.com/fupengfei058/super_course_schedule/blob/master/png/use_case.png)
### 登录时序图：
![github](https://github.com/fupengfei058/super_course_schedule/blob/master/png/login.png)
### 课程查询时序图：
![github](https://github.com/fupengfei058/super_course_schedule/blob/master/png/course_query.png)
### 成绩查询时序图：
![github](https://github.com/fupengfei058/super_course_schedule/blob/master/png/score_query.png)
### 浏览树洞时序图：
![github](https://github.com/fupengfei058/super_course_schedule/blob/master/png/browse_tree_holes.png)
### 发表评论时序图：
![github](https://github.com/fupengfei058/super_course_schedule/blob/master/png/publish_comments.png)
<h3>个人主页界面：</h3>
<img src="https://github.com/fupengfei058/super_course_schedule/blob/master/png/personal_homepage.png" width="350px" border="2px">
<br>
<h3>课程查询界面：</h3>
<img src="https://github.com/fupengfei058/super_course_schedule/blob/master/png/curriculum_schedule.png" width="350px" border="2px">
<br>
<h3>成绩查询界面：</h3>
<img src="https://github.com/fupengfei058/super_course_schedule/blob/master/png/score_query_interface.png" width="350px" border="2px">
<br>
<h3>树洞界面：</h3>
<img src="https://github.com/fupengfei058/super_course_schedule/blob/master/png/tree_hole_interface.png" width="350px" border="2px">
<br>
<h3>发表树洞界面：</h3>
<img src="https://github.com/fupengfei058/super_course_schedule/blob/master/png/publish_tree_hole_interface.png" width="350px" border="2px">
<br>
<h3>评论界面：</h3>
<img src="https://github.com/fupengfei058/super_course_schedule/blob/master/png/comment_interface.png" width="350px" border="2px">
