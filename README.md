# ITS - 互助教学社区系统

> 该系统实现相对较简单，是本人毕业设计作品，仅供初学者学习参考。


### 环境搭建 

- Apache
  - Tomcat
  - Maven
- MySql
- JDK 1.8 

### 数据库导入

导入 `its/sql` 下的sql文件

### 功能简述

#### 前台
  - 本站概述：网站简介
  - 新闻热点：可外链也可自行编写
    - 教育新闻
    - 时事热点
  - 「微」论坛：话题发布，回复
    - 恶意灌水检测
    - 刷帖检测
  - 不耻下问：可查找本站认证教师
  - 教学资源：上传、查看及下载资源
    - PDF：在线PDF预览及下载
    - RAR ZIP：仅提供下载
    - MP4：在线观看及下载
  - 本站活动：本站相关活动查看
  - 名师认证：通过实名及上传相关资料审核成功后即可成为本站认证教师，显示专属认证标识
    - 认证申请、通过、驳回邮箱通知
  - 举报系统：对用户或者相关页面进行举报
  - 消息系统：站内相关操作都会由消息通知用户（发帖回复，处罚等）
  - 积分制度：
    - 完善个人信息，上传资源，发布话题，评论等操作均匀有相应的积分奖励
    - 灌水、恶意刷帖、下载资源会扣除相应的积分
    - 积分下限0

#### 后台
  - 活动管理：本站活动增删改
  - 新闻管理：新闻编辑增删改
  - 公告管理：主页公告增删改
  - 举报处理：根据用户反馈信息进行相应操作
  - 认证审核：前台提交名师认证审核
  
> 后台参考  

`git@github.com:DepressionCoder/its-admin.git`

`https://github.com/DepressionCoder/its-admin.git`
  
  
----
## 写在最后
> - 1.本站为作者2018毕业设计,考虑并不是很全面
> - 2.系统相对设计简单，仅供学习参考使用
> - 3.设计使用框架相对较老，不做更新
