---
title: "黄土高原上的绿飘带"
author: 'samli'

date: '2023-12-12'

draft: false

description: "没想好组名组"

theme_version: '2.8.2'

cascade:
  featured_image: '/images/mountain-547363.jpg'
---  

## 向兰州市生态建设者致敬！

<!DOCTYPE html>
<html>
<head>
	<title>无缝滚动</title>
</head>
<style type="text/css">
	
*{margin: 0;padding: 0;}
	#div1{position: relative;border:1px solid #0ff;width:1510px; height: 380px;margin:80px auto 0;overflow: hidden;margin-left: -500px;}
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
		<li><img src="/images/sign.jpg"></li>
		<li><img src="/images/leaf.jpg"></li>
		<li><img src="/images/temple.jpg"></li>
		<li><img src="/images/m1.jpg"></li>
		<li><img src="/images/m2.jpg"></li>
		<div style="clear: none;"></div>
	</ul>
</div>
</body>
</html>



## [榆中县贡井林场](https://www.lzyuzhong.gov.cn/art/2021/8/31/art_1736_1043670.html#:~:text=%E5%A7%8B%E5%BB%BA%E4%BA%8E1959%E5%B9%B4%E7%9A%84%E8%B4%A1%E4%BA%95%E6%9E%97%E5%9C%BA%EF%BC%8C%E6%98%AF%E6%A6%86%E4%B8%AD%E5%8E%BF%E5%9F%9F%E5%86%85%E5%94%AF%E4%B8%80%E4%BB%A5%E9%80%A0%E6%9E%97%E7%BB%BF%E5%8C%96%E4%B8%BA%E5%AE%97%E6%97%A8%E7%9A%84%E5%9B%BD%E8%90%A5%E6%9E%97%E5%9C%BA%EF%BC%8C%E4%B9%9F%E6%98%AF%E9%BB%84%E6%B2%B3%E6%B0%B4%E5%88%A9%E5%A7%94%E5%91%98%E4%BC%9A%E7%94%98%E8%82%83%E4%B8%AD%E9%83%A8%E9%BB%84%E5%9C%9F%E9%AB%98%E5%8E%9F%E4%B8%98%E9%99%B5%E6%B2%9F%E5%A3%91%E5%8C%BA%E4%BB%A5%E6%B0%B4%E5%9C%9F%E4%BF%9D%E6%8C%81%E4%B8%BA%E4%B8%BB%E7%9A%84%E9%87%8D%E7%82%B9%E6%9E%97%E5%9C%BA%E3%80%82,%E7%9B%AE%E5%89%8D%E6%9E%97%E5%9C%BA%E7%AE%A1%E8%BE%96%E8%8C%83%E5%9B%B4%E3%80%81%E9%80%A0%E6%9E%97%E5%8C%BA%E5%9F%9F%E5%B7%B2%E6%8B%93%E5%B1%95%E5%88%B0309%E5%9B%BD%E9%81%93%E6%B2%BF%E7%BA%BF%E4%B9%A1%E6%9D%91%EF%BC%8C%E7%AE%A1%E6%8A%A4%E9%9D%A2%E7%A7%AF13.16%E4%B8%87%E4%BA%A9%EF%BC%8C%E6%9E%97%E6%9C%A8%E8%A6%86%E7%9B%96%E7%8E%8726.93%25%E3%80%82)
<body>
<p style="width: 950px;margin-left: -200px;">始建于1959年的贡井林场，是榆中县域内唯一以造林绿化为宗旨的国营林场，也是黄河水利委员会甘肃中部黄土高原丘陵沟壑区以水土保持为主的重点林场。目前林场管辖范围、造林区域已拓展到309国道沿线乡村，管护面积13.16万亩，林木覆盖率26.93%。</p>

<img src="/images/forest.jpg" style="width: 6000px;">

<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">近年来，榆中县采取春、雨、秋“三季”抢墒造林方式，相继实施了“三北”防护林(含黄土高原综合治理)、天然林资源保护、新一轮退耕还林、面山绿化等重点林业生态建设工程，不断推进大规模国土绿化，生态建设各项工作成效显著。
<br><br></p>


## 黄土高原上的“绿色奇迹”<br><br>——走近兴隆山保护区和贡井林场


<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">当人们来到兰州市榆中县的贡井林场以及兴隆山国家级自然保护区，都不由得为之惊讶，很难想象在如此贫瘠干旱的西北地区，能有这般壮观的绿色，它们不似南方的绿那样连绵不绝，它们更像是沙漠里的绿洲，沧海里的明珠，在西北地区发出璀璨的光芒，在这一片土地上创造了绿色奇迹。<br><br>
习近平总书记在党的二十大报告中指出，推动绿色发展，促进人与自然和谐共生。尊重自然、顺应自然、保护自然，是全面建设社会主义现代化国家的内在要求。必须牢固树立和践行绿水青山就是金山银山的理念，站在人与自然和谐共生的高度谋划发展。<br><br>
绿色发展，建设美丽中国已经成为五位一体发展理念的重要方面和目的，两大林场依托这一理念，不断建设和发展，住在榆中县的居民最能感受到，榆中的天更蓝了，榆中的山更绿了，榆中的环境更好了，榆中的人更美了。<br><br> 

**黄土高原的绿色明珠——兴隆山自然保护区** 
</p>
<img src="/images/xls.jpg" style="width: 6000px;">
<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">
当游客登临风景如画的榆中县兴隆山国家级自然保护区时，穿过美丽的云龙桥，拾级而上，眼前便是一座雄伟壮观的牌厦门，人们都要在此驻足观赏镶嵌在门额上方由当时所任中共中央总书记胡耀邦所题的“陇右名山”这四个苍劲有力的大字。<br><br>
兴隆山保护区位于甘肃省榆中县西南隅，西起兰州市七里河区阿干林场，东至榆中县新营镇，南接临洮县，北连榆中平原，东西长约 37 km，南北宽约17km。总面积29583.60 hm2。1986 年甘肃省人民政府批准成立甘肃兴隆山省级自然保护区，1988年5月经国务院批准晋升为国家级自然保护区，属于森林生态系统类型自然保护区。<br><br>
现如今，兴隆山的绿色仍在不断扩大，“二十年以来，兴隆山的森林覆盖率从原来的72%到如今的78.9%。”兴隆山国家级自然保护区纪委书记裴书记说，他曾经也是兴隆山的一位护林员，亲眼见证了兴隆山变得越来越绿，环境也在不断地改善“也因为兴隆山生态建设的持续发展，兴隆山的一些森林也变成了湿地。”他说的时候语气里带着自豪。<br><br>
十年前来到兴隆山保护区进行生态环境监测的沈研究员说到：“兴隆山资源保护已经取得了实效，通过有效保护和开展植被恢复造林，使森林总量不断增加，主要保护对象呈现恢复性增长的良好态势。生态效益显著增强。近年来生态定位观测数据表明，森林总量持续增加，生态状况明显好转，生态系统平衡稳定，水土流失不断减少，荒漠化威胁逐年降低，生态环境明显改善。”<br><br>
一个当地居民背着小包，慢慢悠悠的从山路走下来。“我很喜欢来这里爬山，早晨的时候这里的空气很清爽，”<br><br>
“现在上山随处都可以看到小动物，动物越来越多，这里也变得越来越热闹。“已经退休的护林员安师傅就住在兴隆山附近的榆中县里，他时不时的来到兴隆山里散步，坐在亭子里怀念着过去的日子。<br><br>


</p>

**林场工人的一代代建设，只为把贡井林场变成另一个兴隆山**
<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">当人们来到兰州市榆中县的贡井林场以及兴隆山国家级自然保护区，都不由得为之惊讶，很难想象在如此贫瘠干旱的西北地区，能有这般壮观的绿色，它们不似南方的绿那样连绵不绝，它们更像是沙漠里的绿洲，沧海里的明珠，在西北地区发出璀璨的光芒，在这一片土地上创造了绿色奇迹。<br><br>
习近平总书记在党的二十大报告中指出，推动绿色发展，促进人与自然和谐共生。尊重自然、顺应自然、保护自然，是全面建设社会主义现代化国家的内在要求。必须牢固树立和践行绿水青山就是金山银山的理念，站在人与自然和谐共生的高度谋划发展。<br><br>
绿色发展，建设美丽中国已经成为五位一体发展理念的重要方面和目的，两大林场依托这一理念，不断建设和发展，住在榆中县的居民最能感受到，榆中的天更蓝了，榆中的山更绿了，榆中的环境更好了，榆中的人更美了。<br><br> 

**黄土高原的绿色明珠——兴隆山自然保护区** 
</p>
<img src="/images/gjlc.jpg" style="margin-left:px;">
<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">不同于兴隆山国家级自然保护区，贡井林场的绿色并没有这么丰富，历史上，榆中北山一带与兴隆山一样美丽，草木葳蕤，鸟兽繁多。在明代，榆中北山一代还多为森林和草地，在经历战争劫乱、自然灾害和人为破坏，至清初，现在到处都是荒山秃岭、惨不忍睹，游牧民族被迫迁移他处，方圆十公里没有人烟，也没有一棵树，仅有一些稀疏的蒿草。<br><br> 
新中国成立后，党和国家十分重视国土绿化。1959年，正值国民经济困难时期，国家仍咬紧牙关，在榆中县贡井镇、夏官营镇、清水驿乡、韦营乡的四乡镇交界处，建起了国有贡井林场，恢复北山植被。<br><br> 
为了生计，经常会在贡井林场进行浇水工作的梁村民回忆道： “小时候经常刮沙尘暴啥的，生态环境很不好。”他把水管放到鱼鳞坑后，来自注水车的水慢慢灌满进坑，“林场搞起来后生态就慢慢变好起来了。”
“现在村民们看到一出门就有树，心情也变好了，也就不会去破坏他们了”作为第三代贡井林场护林员，同时现在也是贡井林场的场长火场长也是很高兴的说到。<br><br> 
“有一次榆中县不下雨，但贡井林场下雨了，一般来说只有榆中县下雨，贡井林场才会下雨。”榆中县森林公安局的邸警官说到，“我相信在贡井林场护林员的努力下，贡井林场会变成下一个兴隆山保护区。”
在新中国成立时，榆中北部山区年降水量仅为280毫米，到现在，这里的降水量最高可达556毫米，蒸发量也由最高的2000毫米变为现在的927毫米，相对湿度也在不断上升。<br><br> 
第一代老护林员的儿子金师傅，是顶替父亲到贡井林场上班的。在贡井林场一干就是37年，2018年退休在家。“在贡井林场上班，不仅仅是一个工作，而是对树的一种依恋和情感，同时也是一种责任。我爱一棵树甚于爱一个人。”
<br><br> 

**携手保护，你我同行**
</p>
<p style="display: flex; justify-content: center;width: 999px;margin-left: -200px;">“陇中苦瘠甲天下。”100多年前，清朝陕甘总督左宗棠的那声叹息，回荡在历史的长空到先如今，山青了，水绿了，野生动物多了，砍伐树木、猎杀动物、烧毁森林少了，“这个过程中，我们森林派出所服从和服务于榆中县生态建设的大局，按照县委县政府和县公安局的安排部署，立足岗位，认真履行保护林地林木和野生动物资源，打击破坏林地林木和野生动物资源的违法犯罪行为，” 榆中县森林公安局的邸警官说道，“困难和问题无处不在，随时都有，特别是防火方面，一不注意就有可能发生重大险情。<br><br> 
“兴隆山国家级自然保护区纪委书记裴书记说：“未来榆中县将对林场进行及时更新和维修各项基础设施设备建设，如界碑、界桩、围栏、巡护道路、防火道路、管护用房、瞭望塔、视频监控点及其相关的通讯、扑救火、防疫、科研、监测、宣教等设施设备，为两地林场保护管理提供基础保障。”<br><br> 
 
</p>
