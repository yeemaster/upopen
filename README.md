===========================================================================
**描述**

站点地址：
http://www.upopen.cn

本博客旨在从一个系统的角度，系统的学习、使用js、nodejs、sql等周边知识
学习某技术点时单独做一个demo，难以深度理解应用，将其应用到项目中才是真正的掌握。
公开这些知识，以便和大家共同进步

本系统会尽量多且合理的使用各新知识点

=============================================================================

**系统功能介绍**

web:
	站点前台服务，属前后端分离中的前台，免责页面渲染、与客户端数据交互及server端的数据交互
	页面端使用 require.js
	服务端使用 express
	数据以http协议向server端传输
	
server:
	站点后台服务，属前后端分离中的后台，与web端的数据交互及数据库的数据交互
	服务端采用 express
	服务端使用 mysql

check:
	用于记录、验证接口功能，在前后端分离过程中，为方便并行开发
	页面端使用 react.js / webpack
	服务端使用 koa.js，涉及到相关功能也采用koa-**框架，以求同步规则
	数据库使用 mongodb，接口验证数据以http协议向server端传输
	

=============================================================================

**系统架构介绍**

docs:系统文档

log: 系统日志

	web/
	
	check/

	server/

check: 接口记录、验证系统，整体采用MVSC结构，server、web系统也采用相同结构

	app.js

	package.json

	webpack.config.js

	assets/		静态资源包

	build/		react打包后文件

	model/		数据层

	views/		展示层

	controls/	路由控制层

	server/		业务层

	lib/		工具包

	config/		配置

server: 同check

web: 同check

static: 静态资源文件

upload: 上传资源文件

=============================================================================

	

	
