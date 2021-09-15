<!DOCTYPE html >
< html  dir =" ltr " lang =" zh-CN " id =" bgimg " >
<头>
<元 字符集=" UTF-8 " />
<元 名称="视口"内容="宽度=设备宽度" />
<元 名称=" baidu_union_verify "内容=" 84a16d6239c2064e1bbeb4808518e86b " >
< title > block鱼社区-https://discord.gg/2zbHGq9j2a </ title >
<元 名称="描述"内容="块鱼社区-https://discord.gg/2zbHGq9j2a " >
< meta  name =" keywords " content =" block鱼社区-https://discord.gg/2zbHGq9j2a " >
< link  rel =" icon " href ="" mce_href ="/ dir / favicon.ico " type =" image/x-icon " >
< link  rel ="样式表" type =" text/css " href =" https://www.bootcss.com/p/buttons/css/buttons.css " >
< link  rel ="样式表" type =" text/css " href =" https://www.bootcss.com/p/buttons/css/showcase.css " >

<元 名称=" referrer " content =" no-referrer " />
<脚本 类型="文本/javascript " >

var  omitformtags = [ "input" ,  "textarea" ,  "select" ]

omitformtags = omitformtags 。加入（“|” ）

功能 禁用选择（e ）{ 
如果 （omitformtags 。的indexOf （Ë 。目标。的tagName 。toLowerCase （））== - 1 ） 
返回 假 
}

功能 重新启用( ) { 
返回 真 
}

if  ( typeof  document . onselectstart != "undefined" ) 
文件。onselectstart = new 函数 （“返回假” ） 
其他{ 
文件。onmousedown =禁用选择 
文件。onmouseup =重新启用 
} 
</脚本>

<脚本> 
功能 停止( ) { 
返回 假； 
} 
文件。oncontextmenu =停止; 

	功能 点击( e )  {
		如果 （文档。层） {
			if  ( e . which  ==  3 )  {
				oncontextmenu = '返回假' ;
			}
		}
	}
	如果 （文档。层） {
		文件。captureEvents （事件。MOUSEDOWN ）;
	}
	文件。onmousedown =点击;
	文件。oncontextmenu  =  new 函数（“返回假；” ）
	文件。onkeydown  =文档。onkeyup  = 文档。onkeypress =函数( ) { 
		如果（窗口。事件。键代码 ==  123 ） { 
			窗口。事件。返回值=假；
			返回（假）； 
		} 
	}
</脚本>

<脚本 类型="文本/javascript " >
	功能 变化( ) {
		var  bodyBgs  =  [ ] ;
		bodyBgs [ 0 ]  =  "http://img.netbian.com/file/2019/0808/ea41cb48c796ffd3020514994fc3e839.jpg" ;
		bodyBgs [ 1 ]  =  "http://img.netbian.com/file/2019/0808/ea41cb48c796ffd3020514994fc3e839.jpg" ;
		bodyBgs [ 2 ]  =  "http://img.netbian.com/file/2019/0808/ea41cb48c796ffd3020514994fc3e839.jpg" ;
		bodyBgs [ 3 ]  =  "http://img.netbian.com/file/2019/0808/2bedaa2e638faded4fbec176aea8c223.jpg" ;
		bodyBgs [ 4 ]  =  "http://img.netbian.com/file/2019/0808/2bedaa2e638faded4fbec176aea8c223.jpg" ;
		bodyBgs [ 5 ]  =  "http://img.netbian.com/file/2019/0808/2bedaa2e638faded4fbec176aea8c223.jpg" ;
		bodyBgs [ 6 ]  =  "http://img.netbian.com/file/2019/0125/01a2990f9e6125fa93b01441aab2cc2e.jpg" ;
		bodyBgs [ 7 ]  =  "http://img.netbian.com/file/2019/0125/01a2990f9e6125fa93b01441aab2cc2e.jpg" ;
		bodyBgs [ 8 ]  =  "http://img.netbian.com/file/2018/1214/3fd293c8825cab753516ae3f8b6b6660.jpg" ;
		bodyBgs [ 9 ]  =  "http://img.netbian.com/file/2018/1214/3fd293c8825cab753516ae3f8b6b6660.jpg" ;
		bodyBgs [ 10 ]  =  "http://img.netbian.com/file/2018/1214/3fd293c8825cab753516ae3f8b6b6660.jpg" ;
//注意bodyBgs[50] 50是当前顺序，按顺序添加或删除，但是顺序必须是连续的

		//bodyBgs[] = "";

		var  randomBgIndex  =  Math 。轮（ 数学。随机（） *  10  ）；//这里的10是随机取值范围，取最后一个bodyBgs[*]的值
		//document.write('<style>html{background-image:url(' + bodyBgs[randomBgIndex] + ')}</style>');
		var  img1 = 文档。getElementById ( 'bgimg' ) ;
		图像1 。风格。backgroundImage = 'url('  +  bodyBgs [ randomBgIndex ]  +  ')' ;
	        窗口。setTimeout ( function ( ) { change ( ) } , 10000 ) ; //图片切换时间 1000=1s
	}
	改变( ) ;
</脚本>
<风格>
/* 黑色背景和十字光标的基本样式 */
* {
	-webkit-box-sizing :边框框；
	-moz-box-sizing ：边框框；
	-o-box-sizing :边框框；
	-ms-box-sizing ：边框框；
	box-sizing :边框框
}

html , body , div , span , applet , object , iframe , h1 , h2 , h3 , h4 , h5 , h6 , p , blockquote , pre , a , abbr , acronym , address , big , cite , code , del , dfn , em , img , ins ,kbd 、q 、s 、samp 、small 、strike 、strong 、sub 、sup 、tt 、var 、b 、u 、i 、center 、dl 、dt 、dd 、ol 、ul 、li 、fieldset 、form 、label 、legend 、表格，标题，tbody ，tfoot 、thead 、tr 、th 、td 、文章、旁白、画布、细节、嵌入、图、figcaption 、页脚、页眉、hgroup 、菜单、导航、输出、ruby 、节、摘要、时间、标记、音频、视频{
	边距： 0；
	填充： 0；
	边界： 0；
	字体样式：正常；
	字体粗细：正常；
	字体大小： 100 %；
	垂直对齐：基线；
}

文章，旁白，细节，figcaption ，图，页脚，页眉，hgroup ，菜单，导航，部分{
	显示：块
}

块引用, q {
	报价：无
}

blockquote : before , blockquote : after , q : before , q : after {
	内容： '' ;
	内容：无
}

输入，文本区域{
	边距： 0；
	填充： 0
}

ol , ul {
	列表样式：无
}

表{
	边框折叠：折叠；
	边框间距： 0
}

标题，第{
	文本对齐：左
}

一个：焦点{
	大纲： 0
}

html {
	位置：相对；
	宽度： 100 %；
	高度： 100 %；
	font-family :微软雅黑, sans-serif;
	z-索引： 1；
	行高： 1.5；
	背景颜色： # 121925；
	字体粗细： 300；
	背景大小：封面；
	背景位置： 50 %  50 %；
	背景附件：固定；
	-webkit-transition ： 0.5秒线性；
	-moz-transition ： 0.5秒线性；
	-o-transition ： 0.5秒线性；
	过渡： 0.5秒线性；
	/*溢出：隐藏*/
}

身体{
	位置：相对；
	宽度： 100 %；
	高度： 100 %；
	最小宽度： 300像素；
	z-索引： 2；
	光标：URL（'./style/default.cur' ），网址（/风格/ default.cur） ，汽车;
}
体：前{
  内容： '' ;
  位置：固定；
  顶部： 0；
  右： 0；
  底部： 0；
  左： 0；
  背景： URL（/风格/ mask.png）中心0重复;
}
一个{
	颜色： # 858585；
	文字装饰：无；
	光标： URL（'./style/hand.cur' ），网址（/风格/ hand.cur） ，汽车;
}

一个：悬停{
	颜色： # 00b3ba
}

乙{
	背景颜色： rgba ( 0 , 179 , 186 , 0.4 )
}

::选择{
	背景： # 00b3ba
}

:: -moz-选择{
	背景： # 00b3ba
}

. top_hr_style01 {
	宽度： 70 %；
	边距： 5 px自动；
	边界： 0；
	边框底部： 1 px实心# fff
}

. top_hr_style02 {
	边界： 0；
	边框底部： 1像素虚线# 858585
}

. 滑块{
	宽度： 100 %；
	高度： 150像素；
	-webkit-transition :  .2秒轻松；
	-moz-transition :  .2秒轻松；
	-o-transition :  .2秒轻松；
	过渡： .2秒轻松；
	背景图像： URL（。/ ; IMG / topBG.jpg）
	背景颜色： # 121925；
	背景大小：封面；
	背景位置： 50 %  50 %；
	背景附件：固定
}

#顶部{
	宽度： 100 %；
	高度： 100 %；
	位置：相对；
	保证金：自动；
	z-索引： 11
}

# top_img {
	宽度： 100 %；
	高度： 100 %；
	位置：相对；
	背景图像： URL（。/ ; IMG / topBG.jpg）
	背景颜色： # 121925；
	背景大小：封面；
	背景位置： 50 %  50 %；
	背景附件：固定；
	z-索引： 11
}

# top_main {
	宽度： 100 %；
	高度： 100 %；
	位置：相对；
	边距： 0自动；
	填充： 40像素 0  10像素 0
}

# top_logo {
	高度： 30 %；
	最小高度： 50像素；
	最大高度： 244像素；
	显示：块
}

# top_logo  img {
	-webkit动画：甲15个小号线性0小号无限;
	动画：甲15个小号线性0小号无限;
	右边距：自动；
	左边距：自动；
	显示：块；
	高度： 100 %
}

@-webkit-keyframes A {
	0 % {
		-webkit-transform ： 旋转（0度）
	}

	100 % {
		-webkit-transform ： 旋转（360度）
	}
}

@keyframes A {
	0 % {
		变换： 旋转（0度）
	}

	100 % {
		变换： 旋转（360度）
	}
}

# top_title {
	文本对齐：居中；
	填充顶部： 15像素；
	显示：块；
	高度： 10 %
}

# top_title  img {
	右边距：自动；
	左边距：自动；
	显示：块
}

# top_title  # top_title01 {
	高度： 83 %；
	最大高度： 59像素；
	最小高度： 30像素
}

# top_title  # top_title02 {
	高度： 9像素
}
# top_title  # top_title02 ：悬停{
	背景：rgba ( 0 , 0 , 0 , 0.8 );
}
# top_navlist {
	显示：块；
	宽度： 30 %；
	高度： 220像素；
	最大宽度： 220像素；
	左边距：自动；
	右边距：自动；
	边距顶部： 50像素
}

＃top_navlist ::后{
	内容： “”；
	显示：块；
	宽度： 20 %；
	高度： 150像素
}

. 顶部导航{
	背景图像： URL（/风格/ nav_bg.png）;
	边框半径： 5像素；
	显示：块；
	宽度： 100 %；
	最大高度： 40像素；
	最小高度： 10像素；
	边距顶部： 15像素；
	文字装饰：无；
	字体大小： 90 %；
	垂直对齐：中间居中；
	颜色： ＃ FFF ;
	字母间距： .5像素；
	文本对齐：居中；
	-webkit-transition :  .2 s线性；
	-moz-transition :  .2 s线性；
	-o-transition :  .2 s线性；
	过渡： .2 s线性；
	行高： 180 %
}

. 顶部导航：悬停{
	边框半径： 5像素；
	背景： ＃ FFF
}

# top_footer {
	填充： 4像素 10像素 4像素 10像素；
	背景色： # 000；
	背景颜色:  rgba ( 0 , 0 , 0 , 0.9 );
	颜色： # 858585；
	位置：固定；
	底部： 0；
	左： 0；
	右： 0；
	z-索引： 12；
	-webkit-transition :  .2 s线性；
	-moz-transition :  .2 s线性；
	-o-transition :  .2 s线性；
	过渡： 0.2 s线性
}
# top_footer ：悬停{
	背景色： ＃ FFF ;
	背景颜色： rgba ( 255 , 255 , 255 , 0.8 );
	颜色： # 000；
}
# top_copyright {
	显示：块；
	-webkit-transition :  .2 s线性；
	-moz-transition :  .2 s线性；
	-o-transition :  .2 s线性；
	过渡： .2 s线性；
	字体大小： 10像素；
	字母间距： 1.5像素；
	文本对齐：居中
}

@media屏幕和（最大宽度：500像素）{
	# top_footer {
		填充： 1像素
	}

	# top_copyright {
		字体大小： 8像素；
		字母间距： 0；
		文本对齐：居中
	}
}
. 工具提示{
-webkit动画：阿3个小号线性0小号无限;
动画：阿3个小号线性0小号无限;
宽度：12像素；
高度：12像素；
顶部：10像素；
左：10像素；
背景：网址（/风格/ snow0.gif）;
字体大小： 10像素；
位置：绝对；/*这是关键*/
z-索引：102；
}
. 工具提示：悬停{
-webkit-animation ：无；
动画：无；
z-索引：103；
背景：无；/*没有这个在IE中不可用*/
}
. 工具提示 跨度{
显示：无；
}
. tooltips : hover  span { /*span 标签仅在 :hover 状态时显示*/
显示：块；
位置：相对；
}
</风格>
< div  style =" text-align:center;clear:both " >
</ div >
< div  class ="工具提示" >
<跨度>


< IFRAME  SRC = “ http://music.163.com/outchain/player?type=2&id=1391638771&auto=1&height=280 ”宽度= 330 高度=“ 300 ” FRAMEBORDER =“无” MARGINWIDTH = " 0 " marginheight =" 0 " > </ iframe >
</ span >
</ div >
<脚本>
var  _hmt  =  _hmt  ||  [ ] ;
(函数( )  {
  var  hm  = 文档。createElement ( "脚本" ) ;
  嗯。src  =  "https://hm.baidu.com/hm.js?fdf2184efaf851b3205918e981935a44" ;
  var  s  = 文档。getElementsByTagName ( "script" ) [ 0 ] ; 
  小号。父节点。插入前（嗯， s ）；
} ) ( ) ;
</脚本>
</头>
<身体>
< div  id ="顶部" >
<主 ID =“ top_main ” >
< div  id =" top_logo " > < img  src =" ./htmlimg/tx.png " onmouseover =" mouseOver() " onmouseout =" mouseOut() " id =" mainimg " > </ div >
< div  id =" top_title " > < img  id =" top_title01 " alt ="""src="./htmlimg/toptitle01.png" >
< BR 类= “ top_hr_style01 ” >
< img  id =" top_title02 " alt =""" src="./htmlimg/toptitle02.png" >
</ DIV > < BR > < BR >小号
< div  class =" showcase-examples l-over l-center " >
  < a  href =" https://discord.gg/4NN8cByf7e " class =" button button-rounded button-plain button-small-caps button-border " > block社区鱼dis </ a >
  <一个 HREF =“ https://t.me/blockyu ‘类=’按钮按钮圆形按钮滑动按钮小瓶盖按钮边界” >电报</一>
  < a  href =" https://t.me/loveblockyu00 " class =" button button-rounded button-plain button-small-caps button-border " >电报频道</ a >
  <一个 HREF =“ https://weibo.com/u/5434070316 ‘类=’按钮按钮圆形按钮滑动按钮小瓶盖按钮边界” >微博</一>
  <一个 HREF =“ https://bihu.com/people/1505682262 ‘类=’按钮按钮圆形按钮滑动按钮小瓶盖按钮边界” >币乎</一>
  <一个 HREF =“ 869230603 ‘类=’按钮按钮圆形按钮滑动按钮小瓶盖按钮边界” > QQ </一>
  <一个 HREF =“ https://twitter.com/blockyushequ ‘类=’按钮按钮圆形按钮滑动按钮小瓶盖按钮边界” >推特</一>
  </ div >

</主要>
<脚本>
	函数 鼠标悬停( ) {
		文件。getElementById ( "mainimg" ) 。src = "./htmlimg/tx2.png" ; //悬浮时的旋转图标
	}
	函数 mouseOut ( )
	{
		文件。getElementById ( 'mainimg' ) 。src  = "./htmlimg/tx.png" //默认的旋转图标
	}
</脚本>
</ div >
<页脚 ID =“ top_footer ” >
< span  id =" top_copyright " >
< hr  class =" top_hr_style02 " >
　　　　　　 　　（°'Д'°）つ友情链接：<一个 HREF = “ https://discord.gg/2zbHGq9j2a ” >块鱼社区
<一个 HREF = “” >块鱼社区</一>版权©二零一一年至2019年版权所有。<一个 HREF = “ https://discord.gg/2zbHGq9j2a ” >素素</一>
</ span >
</页脚>
</正文>

< script  src =" ./javascript / snow.js " > </ script >
<脚本>
createSnow ( '' ,  60 ) ;
</脚本>
</ html >
