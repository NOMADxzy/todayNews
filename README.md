# 迷你版今日头条开发说明
[代码](https://github.com/Peter-Hai-0/todaynews)

## 项目前端页面确定
通过字节跳动的寒假训练营，我们初步了解了前端知识，尤其是react知识。基于我们学习的知识，我们觉得仿照今日头条，于是用react app建立前端的框架。考虑到美观问题，页面的部分功能并未实现只是充当装饰，当然如果时间来的及的话，还是可以实现一下的。

## 项目阶段目标确定
首先我们分析了需求，并且前后端通过商讨确定了需要实现的API。

随后我们先分工实现文档上的基础功能，例如文章编辑上传和用户登录。

然后根据项目进度，决定继续实现评论、PVUV以及点赞功能。

## 项目团队分工确定
团队的分工很明确，队员李金海负责前端页面框架，同时还有一些前端数据渲染，样式等，徐祖云和张笑天负责后端的云函数上线和数据库的建立，其中徐祖云还负责了一些前端的交互问题。

## 项目团队分工
李金海负责前端页面框架，同时还有一些前端数据渲染，样式等 徐祖云负责后端的云函数上线和数据库的建立以及一些前端的交互问题 张笑天负责后端的云函数上线和数据库的建立

## 项目功能
文章列表获取并跳转到详情页面。
进入首页即可获取文章列表，默认加载了15条文章标题，每条标题下方有来源、日期等信息，可点击底部的加载更多获取更多文章，点击文章标题即可进入详情页面
注册和登录个人账号。
页面左上角时账号区域，初始时为未登录状态，可输入账号：环球时报，密码：123进行登录，也可点击注册账号注册后直接进入登录状态。
文章评论的显示和发表。
在文章详情页面下方显示了当前评论（包含时间等信息），输入框中输入评论内容，点击评论即可发送并显示在下方评论列表第一项。
对文章的点赞和点踩。
文章内容的末尾显示了当前文章的赞（踩）数，点击赞（踩）或相应的表情可以实现对文字的点赞（踩）
个人账号的文字编辑和录入。
点击右上角账号区域的发布文章按钮可进入发布文章页面，依次输入标题，来源和具体内容最后点击提交即可。可以在文章内容中嵌入https开头from=pc结尾的图片链接，（图片链接末尾需要换行）。点击右上角账号区域的文章列表按钮可进入文章列表界面，可点击所需编辑的文章标题进入编辑界面，和录入相似，最后点击提交完成编辑。
文章的上线下线及访问统计。
进入文章列表界面显示了当前账号的所有文章标题即其赞、踩、评论、状态，访问量(pv)、访问数(uv)信息，右上角显示总的pv、uv。点击文章状态右边的交换箭头可对文章状态进行反转。
