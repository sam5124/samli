---
title: "The Simpsons"
author: 'samli'

date: '2023-12-12'

draft: false

description: "没想好组名组"

theme_version: '2.8.2'

cascade:
  featured_image: '/images/cover.jpeg'
---  

## Welcome to The Simpsons！
## 您好，辛普森一家了解一下！

<!DOCTYPE html>
<html>
<head>
	<title>无缝滚动</title>
</head>
<style type="text/css">
	
*{margin: 0;padding: 0;}
	#div1{position: relative;border:1px solid #0ff;width:1510px; height: 350px;margin:50px auto 0;overflow: hidden;margin-left: -500px;}
	#div1 ul{position: absolute;left: 0;}
	#div1 ul li{list-style: none;width:600px;float: left;padding: 10px;height: 1800px;}
	#div1 ul li img{width:100%;}
</style>
<script type="text/javascript">
	window.onload=function(){
		var oDiv=document.getElementById('div1');
		var oUl=oDiv.getElementsByTagName('ul')[0];
		var aLi=oUl.getElementsByTagName('li');
		var aA=document.getElementsByTagName('a');//获取向右向左的箭头
		var timer=null;
		var iSpeed=10;
		oUl.innerHTML+=oUl.innerHTML;//定义图片可以循环播放
		oUl.style.width=aLi.length*aLi[0].offsetWidth+'px';//定义外层ul的宽度，根据图片的个数和每个图片的宽度计算，保证总宽度是可调整的
		function fnMove(){
			if(oUl.offsetLeft<-oUl.offsetWidth/2){
				oUl.style.left=0;
			}else if(oUl.offsetLeft>0){
				oUl.style.left=-oUl.offsetWidth/2+'px';
			}//定义到边界的时候，实现无缝衔接
			oUl.style.left=oUl.offsetLeft+iSpeed+'px';
//定义图片的右边距随着速度不断不断增加，或减小，实现运动的效果
		}
		timer=setInterval(fnMove,200);
		aA[0].onclick=function(){
			iSpeed=-10;
//按下左箭头，定义向左运动
		}
		aA[1].onclick=function(){
			iSpeed=10;
//按下右箭头，定义向右运动
		}
		oDiv.onmouseover=function(){
			clearInterval(timer);
//鼠标移动到图片上，清除定时器，停止运动
		}
		oDiv.onmouseout=function(){
			timer=setInterval(fnMove,175);
//鼠标移出，重新开启定时器，重新运动
		}
	};
</script>
<body>
	<a href="javascript:;">←</a>
	<a href="javascript:;">→</a>
<div id="div1">
	<ul>
	<div class="carousel">
		<li><img src="/images/P183872_b_h8_co.webp"></li>
		<li><img src="/images/Cue_Detective_69.JPG.webp"></li>
		<li><img src="/images/Simpsons_on_Disney_Plus (1).webp"></li>
		<li><img src="/images/SeriesList_s35-1.webp"></li>
		<li><img src="/images/1024px-murder_she_boat_promo_3-min.webp"></li>
		<div style="clear: none;"></div>
	</ul>
</div>
</body>
</html>



## [辛普森一家](https://baike.baidu.com/item/%E8%BE%9B%E6%99%AE%E6%A3%AE%E4%B8%80%E5%AE%B6/35758)
<body>
<p style="width: 950px;margin-left: -200px;">《辛普森一家》(The Simpsons)是由美国福克斯广播公司出品，马特·格勒宁创作的一部动画情景喜剧。该剧通过展现霍默、玛姬、巴特、丽莎和麦琪一家五口的生活，讽刺性地勾勒出了居住在美国心脏地带人们的生活方式。
该片从许多角度对美国的文化与社会、人的条件和电视本身进行了幽默的嘲讽，是一部家庭喜剧幽默片。</p>

<img src="/images/first.jpg" style="width: 6000px;">

<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">辛普森一家以虚拟的美国小镇斯普林菲尔德（Springfield)为背景。在播出期间影迷们试图通过Springfield小镇的特点，周围的地理情况作为线索来寻找其确切的地点。（像在"这都怪丽莎"一集中，丽莎的巴西孤儿笔友写道“我试着给你写信，但我不知你住在哪一州”，对此，丽莎回答说：“这虽然有些神秘，但只要你关注一些线索，你会找到的。”）几乎美国的每一个州和地区都被猜测过是Springfield的所在地，但都因矛盾的证据而被推翻。因此理论上说，Springfield无处不在。例如，在“笑声背后”一集中，辛普森一家被描绘成一个北肯塔基家庭，但肯塔基的Springfield却不在州的北部。后来，地点转移到南密苏里州（密苏里州的Springfield在密苏里的西南部）。作者马特高宁（Matt Groening）声明Springfield与他成长的城市波特兰（位于俄勒冈州）有更多共同点。他之所以用Springfield这个名字是因为美国几乎每个州都有一个小镇或城市叫这个名字。
<br><br></p>


## 角色介绍
![](http://5b0988e595225.cdn.sohucs.com/images/20180810/aa5a15849cb3471d820a42e9e5b5983b.gif)

## Homer
<img src="/images/homer.jpg" style="margin-left: -650px;"><p style="margin-top: -480px;margin-left: 200px;width: 670px;">**辛普森一家中的父亲，一人养着全家**<br><br>
春田镇核电厂里7-G部门的安全检查员，他是通过政府经济改革下进入核电厂工作的。
他是个体重230多磅（104多千克），头脑简单，脾气暴躁的典型人物。
食量大，特爱吃甜甜圈，以及一切高热量食物，生活中离不开DUFF啤酒和电视。而他的工作时间就是在睡觉和吃甜甜圈。
生气时喜欢掐儿子Bart脖子。
口头禅D'oh!和WooHoo！
儿时由于将一支蜡笔插入大脑而导致智力低下，被取走后智商提高了许多，但却和朋友们疏远了，生活变得不快乐，最后在Moe的帮助下又插了回去，智商恢复从前。
尽管Homer是一个深爱家庭的丈夫，但妻子Marge经常抱怨Homer的酗酒和懒惰。
当压力过大时，妻子Marge会向婚姻顾问和牧师抱怨Homer忘记生日；忘记结婚纪念日；忘记节日（无论是宗教节日还是传统节日）；张着嘴巴嚼东西；在低级酒吧里和流浪汉，醉汉鬼混；用毛巾擤鼻涕；而且擤完之后还把毛巾挂回去；用钥匙挠痒痒。不管怎样，Homer还是深爱着他的家庭，而且他一直努力证明这点，尽管这行为总让他变得很可笑。
很爱自己的女儿，曾经为了给Lisa买匹小马而没日没夜工作，第四季中，别人说Lisa丑时，他说lisa很美丽，Marge说那是因为你是她的爸爸（that's because of father's eyes），Homer说要是可以的话，我把我的眼睛挖出来安到别人眼里（那样别人也会像他那样看待Lisa）。
总之，Homer很少有聪明的时候，但他很有爱。</p>

<br><br>

## Marge
<img src="/images/marge.jpg" style="margin-left:px;"><p style="width: 950px;margin-left: -200px;" >**一个充满包容的母亲和妻子，家庭主妇**<br><br>
喜欢把头发染蓝色，固定成竖立发型，喜欢将钱藏在头发里，生气或者烦恼时会发出类似小狗的腔音，深爱丈夫Homer和家庭，尤其能够容忍丈夫的一切缺点。也能够同情原谅周围的人。
Marge是粘合剂，是她的辛勤努力，让辛普森一家日复一日的呆在一起。通过对各项琐碎生活费用（如一个电动门，孩子们的服装费等）制定计划，Marge小心翼翼的规划Homer的微薄薪水，然而千禧年的各项巨大费用让Marge目不暇接：Homer的啤酒，炸面包圈，还要准备印度一日游——Kwik-E超市购物。
Marge可不是只会做饭的家庭妇女，她也是丈夫强有力的支撑。</p>

<br><br>

## Bart

<img src="/images/bart.gif" style="margin-left: 360px;"><p style="width: 550px;margin-top: -480px;margin-left:-240px;width=500px" >**一个淘气可爱的男孩子，10岁**<br><br>
擅长滑板，喷漆涂鸦，常常打骚扰电话用文字游戏捉弄酒吧的Moe。
喜欢小丑Krusty的表演，以及动画片《Itchy和Scratchy》（傻猫与坏鼠）（恶搞《猫和老鼠》）。
在第一季中因被学校派送至法国交换生而学会了法语，那集他受了不少的苦。Bart每周都会被留堂，被罚在黑板上写字（之前几乎每集的开头都有一句）。Bart不爱学习，但是关键时刻却很少掉链子。
Bart喜欢在人面前装成小丑，并以此为乐，喜欢恶搞一切事物，但是其却不缺乏同情心和关键时刻的道德观，Bart最爱恶搞的人是他的爸爸，所以总被他爸爸掐脖子。Bart最好的朋友是Milhouse。
Bart喜欢成为人们的焦点，喜欢欺负Lisa，但是却常被Nelson等人揍，为此Bart十分想成为像Nelson一样的学校霸王。
Bart没有太大的追求，更没有远大的抱负，他的生活态度就是快快乐乐的过每一天，烦恼对于他来说总是转瞬即逝，不过Bart的生活总是多姿多彩，曾经救过自己的偶像小丑Krusty，多次破坏杂耍Bob的阴谋，在剧场版里还和爸爸拯救过春田镇。</p>
<br><br>
## Lisa
<img src="/images/lisa.png" style="margin-left: -650px;"><p style="width: 750px;margin-top: -480px;margin-left:140px;">**博学多才的女孩子，8岁**<br><br>信仰佛教，素食主义者，环保主义者，女权主义者，喜欢吹萨克斯，喜欢小丑Krusty的表演，以及动画片《Itchy和Scratchy》（恶搞《猫和老鼠》），多次幻想自己成为美国总统，门萨Mensa俱乐部的会员，学习成绩特好。
由于她的理智公正并具有真正的道德感常常能够帮助周围的人解决矛盾，并使她发现一些谎言和阴谋，但一般没有人相信她。同样，虽然她很理智，但当有人超越她时，她会明显的表现出嫉妒和恐惧的心里。（有一集Maggie表现出超越她的天赋时Lisa故意教她错误的词意来误导她，虽然之后又被自己吓到了为了避免伤害Maggie而主动离家出走。）
天生丽质，在第四季第4集中披荆斩棘荣获儿童选美冠军。比较有趣的是，这和前面Homer词条中有人说Lisa丑的事情发生在同一集，其实只是别人为了打击她的自信，最后荣获冠军后对容貌的自信也回归了。
也在第二十四季第15集中因为美貌和甜美可爱的娃娃音，被新来的代课老师误认为是交际花而被老师欺负。
她同情动物，为此素食终生（尝试过昆虫和虾后又放弃）。曾出于同情和Milhouse，Ralph等人约会，但最终都不欢而散。Lisa的道德标准有些超标，往往她会强迫其他人服从自己的意志，但实际上常常是自己单纯相信某些道理而反衬出大人的双标，不过对于同龄人而言很多时候也不合时宜，由于这点Lisa缺少朋友，并且她的观点经常遭到同镇人的鄙视，她对爱人的要求标准也很高，但又特别容易被渣男蒙骗利用。</p>


<br><br>

## 播出信息
[《辛普森一家》](https://baike.baidu.com/reference/35758/533aYdO6cr3_z3kATPyIzvz1N37MNIipu-KGUeZzzqIP0XOpX5nyFI49-Jk88fooAAPO_YtrbcYGmea5FR0AsqsNJK1sAep2yDU)是美国电视史上[讽刺喜剧](https://baike.baidu.com/item/%E8%AE%BD%E5%88%BA%E5%96%9C%E5%89%A7/479620?fromModule=lemma_inlink)及动画节目的常青树，
于1989年12月17日首播。<br><br>
《辛普森一家》现已播出至第32季（更新中）。<br><br>2012年2月19日，《辛普森一家》迎来了历史性的第500集（第23季第14集）。<br><br>《辛普森一家》电影版（别名辛普森大电影/阿森一族大电影）于2007年上映。

![film](/images/film.jpg)
<p style="margin-left: -170px;width: 970px;">在2019年9月30日《辛普森一家》宣布续订至32季，届时集数将达到713集。不过，
 《辛普森一家》的版权年限到2086年才会到期，所以在本世纪应该不会完结.
</p>  
<br>

## 视频介绍  

<head>
<style>
  .video-container {
    border: 3px solid #000;
    border-radius: 10px;
    padding: 5px;
  }
</style>
<div class="video-container">
<iframe src="//player.bilibili.com/player.html?aid=942010036&bvid=BV17W4y1h73V&cid=804436734&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="100%"  height="400px" left="500px"</iframe>
  }
</div>
</head>




