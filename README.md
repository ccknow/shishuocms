# shishuocms
师说CMS

介绍一款国内java免费开源CMS系统框架--师说CMS
转载他人的开源代码，个人也研究过一段时间，并在其基础上二次开发过，很不错。

一款使用Java语言开发的CMS，提供文章发布，图片展示，文件下载和商城等功能。可免费用于商业用途。

欢迎使用 “师说CMS”

使用Java语言开发的CMS（使用Apache2协议，可免费用于商业用途）
Spring MVC为表现层，Spring为业务层，MyBatis为数据层。项目大量使用注解，代码注释清晰，文档齐全，是学习和二次开发的首选。

QQ群：7343505

release 0.1

优化了表设计，更能够修理解系统设计
对于目录和文章，都可以有附件和评论
支持4级目录，以目录的英文名为URL
简化了代码，删除了不需要的方法
初始化后台登录用户
PS：明年（过年以后）才会对系统统进行开源友好支持，敬请期待。

捐赠

如果您喜欢“师说CMS”，认为“师说CMS”确实给您带来方便和帮助，那么欢迎您捐赠。这笔钱会用在“师说CMS”的服务器费用上。非常感谢，您的捐赠，是我们前进的动力。我们将定期公开捐赠和支出。
介绍一款国内java免费开源CMS系统框架--师说CMS

演示地址

前台演示： http://42.121.56.21:7070/index.htm

后台演示： http://42.121.56.21:7070/auth/admin/login.htm

邮 箱： cmstest@shishuo.com

密 码： cmstest

技术关键词

jQuery
Bootstrap
Java
Maven
Spring
Spring MVC
MyBatis
MySQL
FreeMarker
Lucene
前言

师说CMS是由长沙师说网络科技有限公司开源的一款CMS产品，其公司推出的“师说" http://www.shishuo.com ，是一个专业人才交流平台，致力于解决人才与企业和人才与人才之间交流的平台。

安装

# 下载代码
git clone http://git.oschina.net/shishuo/CMS.git
# 进入CMS目录
cd CMS
# 清理
mvn clean
# 编译
mvn compile
# 修改数据库配置文件
    1、 把 src/main/resources/shishuocms.properties 拷贝到 CMS目录下
    2、 修改shishuocms.properties里的超级管理员的email，和数据库连接的相关信息
# 安装
mvn exec:java -Dexec.mainClass="com.shishuo.cms.Install"
# 运行
mvn jetty:run
# 后台地址
http://127.0.0.1:8080/auth/admin/login.htm
登录邮箱：cmstest@shishuo.com
登录密码：cmstest
目标

为致力于学习Java语言的初学者提供学习和参考的Demo
帮助企业以更低的成本打造自己的网站
让广大Web前端开发者和设计者，专注前台页面设计和制作
填补各种优秀的开源CMS系统中，使用Java语言开发的空白
需求

文章列表模块
图片展示模块
文件下载模块
电子商务模块
用户注册登录模块
后台管理模块
