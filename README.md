# food_check_v4
【美食管理与推荐系统】Vue3+协同过滤推荐+Deepseek大模型+2026原创+Web管理系统

## 一、介绍
美食管理与个性化推荐系统，将美食分类与条目维护、用户注册登录与偏好设置、浏览与互动行为采集以及智能推荐整合在同一平台。管理员可对分类与菜品执行增删改查并上传封面；普通用户检索与浏览详情，借助点赞、收藏、评论等行为形成可用于推荐的隐式反馈。后端采用 Flask 提供 RESTful JSON 服务，配合 JWT 实现鉴权与用户、管理员角色区分；前端采用 Vue 3 与 Element Plus 搭建交互界面，组件化与统一规范便于迭代。推荐模块基于行为日志运用协同过滤，从群体相似性出发生成「猜你喜欢」列表，在信息规模上升时仍有助于缩小候选范围，形成「内容管理—行为沉淀—个性推荐」的业务闭环。

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/78b259b45fc14fd2bb53b58df73a3f2d.png)

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/2c400a4916134e2ba3823a3932fb9e0a.png)

## 二、演示视频 and 完整代码 and 安装
地址：https://www.yuque.com/ziwu/qkqzd2/dbch9rkvqwy4q99z
