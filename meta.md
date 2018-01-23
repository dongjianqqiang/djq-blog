Meta 适用 
==

		<!--================  声明文档的兼容模式  ================-->
		<!-- 优先使用 IE 最新版本和 Chrome -->
		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
		<!-- 避免IE使用兼容模式 -->
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<!-- 针对手持设备优化，主要是针对一些老的不识别viewport的浏览器，比如黑莓 -->
		<meta name="HandheldFriendly" content="true" />

		<!--======  SEO 优化   ========================================================-->
		<!-- 页面描述 -->
		<meta name="description" content="不超过150个字符" />
		<!-- 页面关键词 -->
		<meta name="keywords" content="" />
		<!-- 网页作者 -->
		<meta name="author" content="name, email@gmail.com" />
		<!-- 网页创建时间 -->
		<meta name="date" content="2016-5-20" />
		<!-- 定义网页搜索引擎索引方式 -->
		<meta name="robots" content="index,follow" />
		<!-- 公司  -->
		<meta name="Copyright" content="" />
		<!-- 不让百度转码  -->
		<meta http-equiv="Cache-Control" content="no-siteapp" />

		<!-- 为移动设备添加 viewport, width=device-width 会导致 iPhone 5 添加到主屏后以 WebApp 全屏模式打开页面时出现黑边 -->
		<meta name="viewport" content="initial-scale=1, maximum-scale=2, minimum-scale=1, user-scalable=no">
		<!--
			content 参数解释：  
    		width  　　　　viewport 宽度(数值/device-width)  
    		height         viewport 高度(数值/device-height)  
    		initial-scale  初始缩放比例  
    		maximum-scale  最大缩放比例  
    		minimum-scale  最小缩放比例  
    		user-scalable  是否允许用户缩放(yes/no)  
    	-->

		<!--======  网站缓存 cookie   ========================================================-->
		<!-- 清除缓存（再访问这个网站要重新下载！）  -->
		<meta http-equiv="cache-control" content="no-cache" />
		<!-- 设定网页的到期时间  -->
		<meta http-equiv="expires" content="0" />
		<!-- 如果网页过期，那么存盘的cookie将被删除。-->
		<meta http-equiv="Set-Cookie" content="cookievalue=xxx;expires=Wednesday, 20-Jun-2007 22:33:00 GMT； path=/" />
		<!-- 如果网页过期，必须到服务器上重新传输。-->
		<meta http-equiv="expires" content="Wed, 20 Jun 2007 22:33:00 GMT" />
		<!-- 设定禁止浏览器从本地机的缓存中调阅页面内容，设定后一旦离开网页就无法从Cache中再调出-->
		<meta http-equiv="Pragma" content="no-cache" />

		<!--======  页面刷新和访问动画      ========================================================-->
		<!--  自动刷新并指向新页   -->
		<meta http-equiv="Refresh" content="2；URL=http://www.net.cn/" />
		<!-- 设定进入页面时的特殊效果 -->
		<meta http-equiv="Page-Enter" contect="revealTrans(duration=1.0,transtion = 12)" />
		<!-- 设定离开页面时的特殊效果 -->
		<meta http-equiv="Page-Exit" contect="revealTrans(duration=1.0,transtion = 12)" />

		<!--======  苹果浏览器设置   ========================================================-->
		<!-- 添加到主屏后的标题（iOS 6 新增） -->
		<meta name="apple-mobile-web-app-title" content="标题" />
		<!-- 是否启用 WebApp 全屏模式，删除苹果默认的工具栏和菜单栏 -->
		<meta name="apple-mobile-web-app-capable" content="yes" />
		<!-- 添加智能 App 广告条 Smart App Banner（iOS 6+ Safari） -->
		<meta name="apple-itunes-app" content="app-id=myAppStoreID, affiliate-data=myAffiliateData, app-argument=myURL">
		<!-- 设置苹果工具栏颜色 -->
		<meta name="apple-mobile-web-app-status-bar-style" content="black" />
		<!-- 忽略页面中的数字识别为电话，忽略email识别 -->
		<meta name="format-detection" content="telphone=no, email=no" />
		<!-- windows phone 点击无高光 -->
		<meta name="msapplication-tap-highlight" content="no" />

		<!--======  其他浏览器设置   ========================================================-->
		<!-- 启用360浏览器的极速模式(webkit) -->
		<meta name="renderer" content="webkit" />
		<!-- 微软的老式浏览器 -->
		<meta name="MobileOptimized" content="320" />
		<!-- uc强制竖屏 -->
		<meta name="screen-orientation" content="portrait" />
		<!-- QQ强制竖屏 -->
		<meta name="x5-orientation" content="portrait" />
		<!-- UC强制全屏 -->
		<meta name="full-screen" content="yes" />
		<!-- QQ强制全屏 -->
		<meta name="x5-fullscreen" content="true" />
		<!-- UC应用模式 -->
		<meta name="browsermode" content="application" />
		<!-- QQ应用模式 -->
		<meta name="x5-page-mode" content="app" />
		<!-- Windows 8 磁贴颜色 -->
		<meta name="msapplication-TileColor" content="#000" />
		<!-- Windows 8 磁贴图标 -->
		<meta name="msapplication-TileImage" content="icon.png" />

		<!--======  网页图标与订阅   ========================================================-->
		<!-- 添加 RSS 订阅 -->
		<link rel="alternate" type="application/rss+xml" title="RSS" href="/rss.xml" />
		<!-- 添加 favicon icon -->
		<link rel="shortcut icon" type="image/ico" href="favicon.ico" />
