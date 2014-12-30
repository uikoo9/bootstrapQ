[bootstrapQ](http://uikoo9.com/bootstrapQ)
==========================================
1. [Bootstrap](https://github.com/twbs/bootstrap)常用插件封装
2. [Bootstro](https://github.com/clu3/bootstro.js)网站引导插件封装
3. 压缩后仅5.5k

开始
====

依赖
---
BootstrapQ是对Bootstrap3.0的封装，所以依赖以下js：

	<!-- jquery-1.11.1 -->
	<script type="text/javascript" src="http://cdn.staticfile.org/jquery/1.11.1/jquery.min.js"></script>
 	
	<!-- bootstrap3.0 js and css -->
	<link rel="stylesheet" href="http://cdn.staticfile.org/twitter-bootstrap/3.2.0/css/bootstrap.min.css">
	<script type="text/javascript" src="http://cdn.staticfile.org/twitter-bootstrap/3.2.0/js/bootstrap.min.js"></script>

引入
---
可以下载到本地然后引入，或者直接引入七牛云上的版本，推荐后者：

	<script type="text/javascript" src="http://uikoo9.qiniudn.com/@/js/bootstrapQ/bootstrapQ.min.js"></script>

使用
---
现在就可以开始使用了，例如：

	// 消息提示
	BootstrapQ.msg({msg:'请填写评论昵称！',type:'danger'});

自定义
---
可以自己将BootstrapQ.js中的“BootstrapQ”批量替换为自己想使用的变量，例如替换为“qiao”，
然后这样使用：

	// 消息提示
	qiao.msg({msg:'请填写评论昵称！',type:'danger'});


