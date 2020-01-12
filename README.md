<details>
<summary>R作业补交</summary>
<mark><font color=darkred> 

![软件作图](https://github.com/Amiya-95/homework/blob/master/%E4%BA%BA%E5%9D%87%E8%83%BD%E6%BA%90%E6%B6%88%E8%80%97%EF%BC%88%E6%B2%B9%E5%BD%93%E9%87%8F%EF%BC%89.png)

![R作图](https://github.com/Amiya-95/homework/blob/master/%E4%BA%BA%E5%9D%87%E7%9F%B3%E6%B2%B9%E5%BD%93%E9%87%8F.pdf)

代码：getwd()
setwd("D:/可视化课/数据")
data<-read.csv("shiyou.csv")
data
library(ggplot2)
ggplot(data,aes(年份,人均石油当量))+geom_line()
                
![软件作图](https://github.com/Amiya-95/homework/blob/master/%E6%8A%95%E8%B5%84.jpg)

![R作图](https://github.com/Amiya-95/homework/blob/master/%E6%8A%80%E6%9C%AF%E6%8A%95%E8%B5%84%E5%8D%A0%E6%AF%94.pdf)

代码：getwd()
setwd("D:/可视化课/数据")
data<-read.csv("清洁能源.csv")
data
library(ggplot2)
ggplot(data,aes(x = 技术,y = 投资占比,fill = 国家))+
  geom_col()
 
</font></mark></summary>
</details>












<details>
<summary>期末作业想法</summary>
<mark><font color=darkred> 
   
&emsp;&emsp;我现阶段的打算时做环境卫生相关的主题，具体未定。因为一方面是对这类话题比较感兴趣；二是相关数据集较多，可供参考选取的资料广泛；三是个人感觉可以展开讨论的点比较多，能更好地完成数据报道和分析，做到内容充分且有质量保证，也有找到的新意报道点的可能与灵活性。具体的选题、报道和呈现方式还要看具体的数据和内容而定。

</font></mark></summary>
</details>








<details>
<summary>第5次作业</summary>
<mark><font color=darkred> 

![数据呈现](https://github.com/Amiya-95/homework/blob/master/%E6%9C%AA%E6%88%90%E5%B9%B4%E4%BA%BA%E7%8A%AF%E7%BD%AA%E8%A2%AB%E5%91%8A%E4%BA%BA%E5%AE%B6%E5%BA%AD%E7%BB%93%E6%9E%84%E6%9F%B1%E7%8A%B6%E5%9B%BE.jpg)
![数据呈现](https://github.com/Amiya-95/homework/blob/master/%E5%9F%8E%E4%B9%A1%E6%9C%AA%E6%88%90%E5%B9%B4%E4%BA%BA%E7%8A%AF%E7%BD%AA%E4%BA%BA%E6%95%B0%E5%8D%A0%E6%AF%94.jpg)
 
&emsp;&emsp;近年来，未成年人犯罪的话题越发受到社会的关注。尽管在案件数量上呈现逐年递减的趋势，但案件整体表现出低龄化、团伙化、成人化等特点，成为影响社会稳定的因素之一。同时，部分恶性案件中嫌疑人的作案动机、手段及其反应与其未成年人的身份形成巨大反差，在另社会震惊之余，更能引起人们的思考。许多人开始反思《未成年人保护法》对未成年人的减刑是否一定程素上纵容了未成年犯罪；同时，关于未成年人教育的反思也受到了更多人的重视。本文将从家庭、学校和社会三个角度分别展开分析，以期能为未成年人教育事业提供参考。

&emsp;&emsp;未成年人犯罪多发生在初中，正是青少年世界观、人生观、价值观处在塑造阶段的时期，易受外来因素的影响，辨别是非的能力和自控能力较差，理性思考能力欠缺，往往不能冷静面对压力和诱惑，同时受可能存在的不良社会关系影响，容易放纵自我，寻求刺激，以身试法。从相关数据中，我们不难发现，未成年人犯罪现象与教育的缺失有关，家庭、学校以及社会教育的缺失是很多未成年人误入歧途最终走上犯罪道路的重要原因。数据显示，未成年人犯罪案件中，大量未成年人来自流动家庭、离异家庭、留守家庭、单亲家庭和再婚家庭。这些家庭的共同特征是对未成年人疏于管教；同时，来自农村地区的涉案未成年人比例远高于城市地区，也反映了农村地区对青少年教育的不重视。因为忙于生计，外出务工以及父母离异、无心管教等原因，家庭教育常存在失职现象；同时，也存在父母管教方式不正确，教养方式或是简单粗暴等问题，同样未能起到良好的管教作用。家庭作为未成年人成长的第一个课堂，对未成年人的教育方面有重大的影响。许多未成年人犯罪案件背后的家庭因素，暴露出我国未成年人教育在家庭教育方面的缺失问题。

&emsp;&emsp;另一方面，学校教育缺失也是影响未成年人犯罪的重要因素。部分初、高中学生因学业不佳、家境困难等原因导致辍学，而学校、家庭及社区对待业或辍学在家的未成年人缺乏管理教育，这些未成年人闲荡于社会，无所事事，容易与不良朋辈交往，沾染不良习气，妄想不劳而获，成为潜在的危险因素。同时，对于不少在校学生的不良行为，学校教育也常显得无能为力，所能做的只有批评处分，教育管理却未能跟上。这是未成年人步入歧途的重要原因,也是学校教育在今后的建设中要着重关注的一点。

&emsp;&emsp;其三，就是社会教育的种种问题。社会未能对一些出现问题的青少年几时起到规劝、警戒的作用；而社会上存在的一些现象、风气或个人群体，反而可能成为引导未成年人树立不正确的社会观念，最终走上犯罪道路的重要助力。建立完备的社会教育体系，以及解决社会自身存在的一些问题对未成年人的不良示范、引导问题，是我们加强社会教育的关键。



数据来源：人民法院大数据管理和服务平台

数据收集过程：从老师给出的新闻由头出发，由于新闻由头是纯粹国内未成年人犯罪的报道，我将数据定在了与中国未成年人犯罪和保护相关的数据。但我国的相关数据较少，我搜集数据能力可能也不太高，尝试之后也只找到了人民法院的相关数据，相对粗浅但也只能拿来使用了。

数据分析和呈现步骤：为了直观表现出家庭教育的缺失对未成年人犯罪的影响，我选取了涉案未成年人家庭结构的数据以及城乡分布的数据，借以表现出其家庭教育可能存在的问题，并展开分析家庭教育失范对未成年人犯罪的影响。

选择报道角度和思考过程：基于有限的粗浅的数据，我权衡之下还是把报道角度放在了简单的“教育缺失对未成年人影响”上。从家庭、学校和社会三个角度分别展开，对未成年人身心成长、家庭学校疏于管教、社会管理效果不佳等诸多方面进行了分析。由于数据简单，本次报道只能是不求标新立异，但求把事情讲清。

</font></mark></summary>
</details>









<details>
<summary>第4次作业</summary>
<mark><font color=darkred> 

![数据呈现](https://github.com/Amiya-95/homework/blob/master/%E9%83%A8%E5%88%86%E5%9B%BD%E5%AE%B6%E5%9B%BA%E6%80%81%E5%BA%9F%E7%89%A9%E7%BB%84%E6%88%90%E5%8F%8A%E6%AF%94%E4%BE%8B.png)
 
&emsp;&emsp;据世界银行发布的调查数据《what a waste》显示，中国的各种垃圾成分中餐饮垃圾占比高达61.2%，远高于世界平均水平。笔者统计整理了中国、日本、韩国三个东亚国家以及美国、俄罗斯、德国三个国家作为比对参考，以呈现中国的垃圾成分比例与其他国家的区别，并试图从中分析中国的产业结构及垃圾管理机制的一些问题。

&emsp;&emsp;我国餐饮垃圾比重大的一个重要原因是人口基数大、密度大。同时，随着我国经济的快速增长、城市化进程的加快和人民生活水平的普遍提高，人们对于食品的质量需求也在提升，俗话说“民以食为天”，人们对食品的要求已经由以前的“吃饱”转变为“吃好”。这也使得我国的餐厨垃圾产生量不断增加。在世界银行提供的原始数据中，人口密度大的国家往往都有餐饮垃圾比重较大的特点。

&emsp;&emsp;但是，人口不是造成此现象的唯一原因。同为人口稠密的东亚近邻日本、韩国，其餐饮垃圾的比重明显低于中国。这与我国食品产业和垃圾监管机制的不完善不无关系。国外发达国家除了在餐厨垃圾的处理上有着先进的技术和管理经验，也十分注重在源头上减少餐厨垃圾的产生，如实行净菜入世政策，以及对各种餐厨垃圾进行有效的分类等。

&emsp;&emsp;此外，餐饮垃圾比重一定程度上还能反映出我国产业结构的问题。对比美国，其餐饮垃圾只占到14.9%的比重，这与美国高度发达的工业体系和消费水平相关，餐饮在其中仅占据小部分比重。而我国的工业化水平和居民消费能力与美国相比还有一定差距，从本数据中可窥一斑。
我国最为餐饮行业大国，餐饮垃圾数量巨大。如何妥善处理之一问题，是我国社会治理和环境治理的重要课题。



参考资料：世界银行公开数据（http://datatopics.worldbank.org/what-a-waste/）

数据收集过程：原计划继续在Kaggle上查找相关数据，但由于很多没有可访问的数据来源，数据权威性不够。在各官方数据开放平台搜索数据时偶然找到世界银行《what a waste》的相关报道，浏览之后决定选取本数据集的相关数据。

数据分析和呈现步骤：为了直观表现出我国餐饮垃圾比重大的特点，使用了日本、韩国两个东亚人口稠密、经济发达的国家作为对比，并选取了美国、俄罗斯、德国三个有代表性的其他地区国家作为参考，以便展现出我国垃圾管理和产业结构的一些问题。

选择报道角度和思考过程：在看到各国垃圾比重的异同时感觉有分析呈现的兴趣，感觉可以从中展示出不只是垃圾比重，还包括人口影响、管理制度、工业体系和消费能力等多方面的信息，便决定以此为切入点，在展示出我国与世界其他国家垃圾比重上的区别的都是，展开对我国垃圾管理和工业化水平进行一定的剖析，最终形成了本篇报道。由于篇幅限制未能继续展开，但不可否认从垃圾比重分析人口、经济等影响因素会是一个有趣的角度。

</font></mark></summary>
</details>








<details>
<summary>第3次作业</summary>
<mark><font color=darkred>
  数据集网址:https://www.kaggle.com/eliasdabbas/gold-reserves-by-country-quarterly
  
  使用工具：图表秀、文图、百度图说
  
  呈现：
  ![图表秀](https://github.com/Amiya-95/homework/blob/master/%EF%BC%88%E5%9B%BE%E8%A1%A8%E7%A7%80%EF%BC%89%E9%83%A8%E5%88%86%E6%AC%A7%E6%B4%B2%E5%9B%BD%E5%AE%B61961-2018%E9%BB%84%E9%87%91%E5%82%A8%E5%A4%87.png)
  ![文图](https://github.com/Amiya-95/homework/blob/master/%EF%BC%88%E6%96%87%E5%9B%BE%EF%BC%89%E9%83%A8%E5%88%86%E6%AC%A7%E6%B4%B2%E5%9B%BD%E5%AE%B62001-2018%E9%BB%84%E9%87%91%E5%82%A8%E5%A4%87.jpg)
  ![百度图说](https://github.com/Amiya-95/homework/blob/master/%EF%BC%88%E7%99%BE%E5%BA%A6%E5%9B%BE%E8%AF%B4%EF%BC%89%E9%83%A8%E5%88%86%E6%AC%A7%E6%B4%B2%E5%9B%BD%E5%AE%B61961-2018%E9%BB%84%E9%87%91%E5%82%A8%E9%87%8F.png)
  
&emsp;&emsp;通过此次作业，我了解到了很多诸如数可视、图表秀、百度图说、镝数以及RAWGraphs、ChartBlocks、Tableau等可视化工具，对这些可视化工具的一些简单运用有了一定熟悉。同时，也学会了在Kaggle等数据公开网站上获取数据，以及对数据的一些筛选处理。本次我在尝试了几个数据集后，最终选择了各国黄金储备作为选取数据，并在一百多个国家、近两百年的数据统计中摘选了部分欧洲国家1961-2018年黄金储备变化情况进行可视化。由于是初次尝试，选取的数据和可视化工具都不是很有难度，只是能直观看出变化走势的折线图而已，但也同样让我学到了很多，也发现了自己在应用这些数据和工具时的一些问题。同时我也对我选取的其他数据集和工具进行了尝试，但由于不太能直观明显地表达出有价值的内容，故此作为了费案，但在此过程中也还是有所收获。

&emsp;&emsp;对于一些我还没能理解的问题，我也会继续努力学习。举例来说，我之前尝试做星巴克甜点营养成分的数据可视化，但数据中一种甜点含有的各营养成分之间单位不同、也不是简单的包含或并列关系，饼状图等都无法适用；即使用分组柱状图呈现，由于单位不同也无法看出各成分的多少有什么意义。这种数据应如何呈现才能让观众有直观的感受？这也许需要我今后继续摸索得出答案了。

&emsp;&emsp;另外，本周我重新学习了一些markdown语法，不过仍需要多加练习。有时照搬标准格式也会出现问题，还要继续努力。
</font></mark></summary>
</details>

<details>
<summary>第2次作业</summary>
<mark><font color=darkred>
1.《上海市公共数据和一网通办管理办法》《福建省政务数据管理办法》《成都市公共数据管理应用规定》《政府信息公开条例》等。
  
  参考链接：http://www.pkulaw.cn/fulltext_form.aspx?Gid=1510206959
  
  北京市政务数据资源网，上海市政府数据服务网，开放广东，广州市政府数据统一开放平台，苏州市政府数据开放平台，浙江政务服务网“数据开放”专题网站等。
  
  参考链接：http://www.tanmer.com/blog/451
  
2.2012：8.1%，7.6%，7.4%，7.9%

  2013：7.7%，7.6%，7.7%，7.7%
  
  2014：7.4%，7.5%，7.3%，7.4%
  
  2015：7.0%，7.0%，6.9%，6.8%
  
  2016：6.7%，6.7%，6.7%，6.8%
  
  2017：6.8%，6.8%，6.7%，6.7%
  
  2018：6.8%，6.7%，6.5%，6.4%
  
  统计指标：国内生产总值当季值
  
  数据页面：http://data.stats.gov.cn/easyquery.htm?cn=B01
  
  计算步骤：用当季度GDP减去上季度GDP，再除以上季度GDP即可
</font></mark></summary>
</details>




<details>
<summary>第1次作业</summary>
<mark><font color=darkred> 
  
 ![个人数据](https://github.com/Amiya-95/homework/blob/master/%E7%8E%8B%E8%A8%80%20%E6%95%B0%E6%8D%AE%E8%AE%B0%E5%BD%95.jpg) 
  
&emsp;&emsp;在本次数据的记录和与其他同学的交流中，我更明显地意识到生活中所有事情都是可以以数据的形式进行收集的，而不仅仅是一些类似数据新闻、市场分析的大事才有必要进行数据统计，这也加深了我对数据的敏感，希望今后能在这一方面学到更多。

&emsp;&emsp;在今天这个网络、信息高度发达的时代，公民的很多个人信息都会被收集。诸如网络上喜欢浏览哪类消息、视频；最近是否买了车、车险；网购时的消费倾向和消费习惯等。同时我们的很多社会行为都会被网络记录下来。收集这些信息的人不尽相同，总的来说主要是服务于我们的媒体、应用；有利益关系的商家；政府出于国家利益和社会利益方面的考虑下也会进行记录收集，等等。
</font></mark></summary>
</details>
