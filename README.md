# muke
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>测试</title>
	<link rel="stylesheet" href="css/mian.css"> <!-- 引入主CSS样式文件 -->
	<script src="js/SetHome.js"></script>
	<script type="text/javascript" src="js/myfocus-2.0.1.min.js"></script><!--引入myFocus库-->
	<script type="text/javascript">
	myFocus.set({
    id:'boxID',//焦点图盒子ID
    pattern:'mF_liuzg',//风格应用的名称
    time:3,//切换时间间隔(秒)
    trigger:'click',//触发切换模式:'click'(点击)/'mouseover'(悬停)
    width:1000,//设置图片区域宽度(像素)
    height:310,//设置图片区域高度(像素)
    txtHeight:'default'//文字层高度设置(像素),'default'为默认高度，0为隐藏
	});
</script>
</head>
<body>
	<div class="top">
		<div class="top-content">
			<ul>
				<li><a href="#">联系我们</a></li>
				<li><a href="#" onclick="AddFavorite(window.location,document.title)">加入收藏</a></li>
				<li><a href="#" onclick="SetHome(window.location)">设为首页</a></li>
			</ul>
		</div>		
	</div>
	<!-- top部分结束 -->
	<div class="logo">
		<div class="logo-left">
			<img src="images/logo.jpg" alt="慕课网">
		</div>
		<div class="logo-right">
			<img src="images/tel.jpg" alt="咨询热线">24小时服务热线:<span class="fon">123-456-7890</span>
		</div>
		<div class="clear-float"></div>
	</div>
	<!-- logo结束 -->

	<!-- 导航 -->
	<div class="nav">
		<div class="nav-left"></div>
		<div class="nav-mid">
			<ul class="nav-mid-left">
				<li><a href="">首页</a></li>
				<li><a href="index.html">关于慕课</a></li>
				<li><a href="">新闻动态</a></li>
				<li><a href="">课程中心</a></li>
				<li><a href="">在线课程</a></li>
				<li><a href="">人才招聘</a></li>
			</ul>
			<div class="nav-mid-right">
				<form action="" method="post">
					<input type="text" class="search">
				</form>		
			</div>
		</div>
		<div class="nav-right"></div>
	</div>
	<!-- myfocus制作焦点轮播图 -->
	<div class="wrap">
		<div id="boxID"><!--焦点图盒子-->
		  	<div class="loading"><img src="images/loading.gif" alt="请稍候..." /></div><!--载入画面(可删除)-->
		  	<div class="pic"><!--内容列表(li数目可随意增减)-->
			  	<ul>
			        <li><a href="#"><img src="images/ad2.jpg" thumb="" alt="1" text="详细描述1" /></a></li>
			        <li><a href="#"><img src="images/ad3.jpg" thumb="" alt="2" text="详细描述2" /></a></li>
			        <li><a href="#"><img src="images/ad4.jpg" thumb="" alt="3" text="详细描述3" /></a></li>
			  	</ul>
		  	</div>
		</div>
	</div>
	<!-- myfocus制作焦点轮播图 -->
	
	<!-- 主要内容 -->
	<div class="main">
		<div class="news-center">
			<div class="head">
				<div class="head-left">
					新闻中心
				</div>
				<div class="head-right">
					<img src="images/more.jpg" alt="更多">
				</div>
			</div>
			<!-- 新闻中心头部结束 -->
			<div class="main-content">
				<img src="images/news.jpg" alt="慕课女神">
				<div class="content-right">
					<h4>520!慕课女神喊你来表白</h4>
					<p>活动时间：5月20日—5月25日</p>
					<p>获奖公布时间：5月26日</p>
					<p style="color:red">learn More>></p>
				</div>
				<ul class="list">
				<li><a href="">【慕客访谈 用户篇】“有为屌丝”在路上</a><p>2014-06-06</p></li>
				<li><a href="">【有奖活动】给父亲的三行书信</a><p>2014-06-04</p></li>
				<li><a href="">《程序猿，请晒出你的童年》活动获奖公告</a><p>2014-06-04</p></li>
				<li><a href="">【慕课访谈】破茧成蝶——美女程序员的蜕变史</a><p>2014-06-01</p></li>
				</ul>
			</div>
		</div>
		<!-- 新闻中心结束 -->
		<div class="classes">
			<div class="news-center">
			<div class="head">
				<div class="head-left">
					课程中心
				</div>
				<div class="head-right">
					<img src="images/more.jpg" alt="更多">
				</div>
			</div>
			<!-- 新闻中心头部结束 -->
			<div class="main-content">
				<img src="images/css.jpg" alt="CSS圆角进化论">
				<div class="content-right">
					<h4>CSS圆角进化论</h4>
					<p>CSS圆角的实现，经历了三大发展阶段：背景图片方式、CSS2.0+HTML标签模拟、CSS3.0圆角属性）。本案例详细讲解每一种的实现方式，并对实现的优缺点进行对比分析。</p>	
				</div>
				<ul class="list">
				<li><a href="">PHP开发</a></li>
				<li><a href="">前端开发</a></li>
				<li><a href="">JAVA开发</a></li>
				<li><a href="">Android开发</a></li>
				</ul>
			</div>
			</div>
		</div>
		<!-- 课程中心结束 -->
		<div class="media-center">
			<div class="news-center">
			<div class="head">
				<div class="head-left">
					媒体聚焦
				</div>
				<div class="head-right">
					<img src="images/more.jpg" alt="更多">
				</div>
			</div>
			<!-- 媒体聚焦头部结束 -->
			<div class="main-content">
				<p class="video_content">
	          	<embed src="http://player.youku.com/player.php/sid/XNjkzMDE5MTUy/v.swf" allowFullScreen="true" quality="high" width="220" height="140" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>
	       		</p>
				<img src="images/app.jpg" alt="精品推荐">
			</div>
			</div>
		</div>
		<!-- 媒体聚焦结束 -->
	</div>
<!-- 主体内容结束	 -->

<!-- 底部版权区 -->
	<div class="footer">
		<ul class="footer-box">
			<li class="foot-list">
				<ul>
					<li><p>关于</p></li>
					<li>品牌故事</li>
					<li>联系我们</li>
					<li>加入我们</li>
					<li>版权声明</li>
				</ul>
			</li>
			<li class="foot-list">
				<ul>
					<li><p>课程</p></li>
					<li>PHP开发</li>
					<li>前端开发</li>
					<li>JAVA开发</li>
					<li>Android开发</li>
				</ul>
			</li>
			<li class="foot-list">
				<ul>
					<li><p>关注</p></li>
					<li>新浪微博</li>
					<li>腾讯微博</li>
					<li>企业微信</li>
					<li>QQ空间</li>
				</ul>
			</li>
			<li class="foot-list">
				<ul>
					<li><p>留言</p></li>
					<li>意见反馈</li>
					<li>问题留言</li>
					<li>媒体联络</li>
					<li>在线客服</li>
				</ul>
			</li>
			<li class="foot-list">
				<ul>
					<li>
						<img src="images/weixin.png" alt="微信"><span>微信关注</span>
					</li>
					<li>
						<img src="images/qrcode.jpg" height="102" width="102" alt="二维码">
					</li>
				</ul>
				
			</li>
		</ul>
	</div>
<!-- 底部版权区结束 -->
</body>
</html>
