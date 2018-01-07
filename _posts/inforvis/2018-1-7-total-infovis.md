---
layout: post
title:  "信息可视化笔记-框架"
categories: posts infovis  
tags: [学习笔记]
date:   2017-12-26 11:44:41 +0800
comments: true
---
### 《哪一个图表或图形适合您？》 13种图形告诉你更好的使用

###### 条形图 Bar Chart* 
* 条形图位居最常见数据可视化方式之列。(用于跨类别比较数据)
###### 折线图 Line chart
* 最常用的一种图表类型之一。
* 可连接各个单独的数值数据点。
*主要用途就是显示一段时间内的趋势。
(用于查看数据中随时间推移的趋势。)
###### 饼图 
* 饼图应该用来显示信息的相对比率（或百分率
* 饼图是误用最多的图表类型。(用于显示比率)
* 注意： 把扇形边限制到六个！！
###### 地图 Map
* 用于显示地理编码数据。
###### 散布图 Scatter Plot
* 散布图是大概了解趋势、集中度、极端数值的有效方式
(用于考察不同变量之间的关系。)
###### 甘特图 Gantt chart
* 对于说明项目各元素的起始与终止日期效果非常好。
* 可以考虑添加色彩。便于看图人快速了解变量的关键方面。
(用于显示项目进度。显示随时间推移的其他事物使用事项。)
###### 气泡图  Bubble chart
* 气泡图不是自成一类的可视化，而应视为强调散布图或地图上数据的手段。
* 使用气泡的原因是圆圈的不同大小揭示数据的意义。
(用于显示数据沿两个轴的集中度。)
###### 直方图 Histogram chart
* 查看数据的跨组分布情况
###### 靶心图 Bullet chart
* 设定了目标并希望参照目标跟踪进展时，靶心图就是理想之选
(用于参照目标评估指标表现。)
*  向仪表板添加靶心图，便于概括。 
###### 热点图 Heat map
* 使用色彩跨两个类别比较数据的理想方式。作用是快速看清两个类别的交集哪里最强，哪里最弱。
###### 突出显示表 Highlight table
* 突出显示表让热点图更进一步。除了用色彩显示数据的交叉情况外，突出显示表还在上方添加数字，提供更多详细信息。
###### 树形图 Treemap
* 图表使用一系列的矩形，嵌套在其他矩形内，以相对于整体的比例显示分层数据。
*树形图能有效利用空间，便于一目了然地看到整个数据集。
###### 箱形图 Box-and-whisker plot
* 箱形图又称盒须图，是显示数据分布情况的重要方式。

### 《最简单的图形与最复杂的信息》
#### 图形感知及图形方法
> 使用规范
* 有效地绘图CHARTING（遵守四个基本步骤：调查研究、编辑、规划和检查。）
* 运用精准的数字NUMBERS（确凿的证据）
* 恰如其分地整合数据DATA INTEGRITY（讲述全部事实）
* 极大地丰富数据DATA RICHNESS
* 善用但不乱用字体FONTS（易读性、图表的字体编排）
* 数据连续统一，加强视觉冲击THE VISUAL—DATA CONTINUUM
* 巧妙运用颜色COLOR
<br/>
> 制作必备常识
* 数值计算DO THE MATH
* 拷贝图表风格COPY STYLE IN CHARTS
* 金钱MONEY
<br/>
> 应对图表制作中的常见问题
* 缺失数据MISSING DATA(是否还值得为其绘制图表？)
* 大数字，小变化BIG NUMBERS, SMALL CHANGE(不能夸张强调)
* 类比刻度COMPARABLE SCALES
* 用黑墨着色COLORING WITH BLACK LNK(形成对比和强调要点)
<br/>
[具体的内容笔记](http://note.youdao.com/noteshare?id=ea6b05d28cf6b33b1d8e788731019ea5&sub=DD942031D94A4DD895742CF4CF993581)

> 图表类型
[关系图](http://note.youdao.com/noteshare?id=8868eabf7e87eabd43d6cc48f09334c1)
##### 对于在运用中，图形的使用[哪个图表或图形适合您？](http://note.youdao.com/noteshare?id=0e1ee6bce9fc47e27707b0e2d3c45dde&sub=B152E99FA7B64BFD968F5AE3F8AA060A)

> 图表的规范运用：用图表讲述令人信服的故事

#### 数据连接及准备
* 数据准备：使用Python交互可视化库Bokeh进行交互式可视化。数据来源：可以是国家数据网
* tableau可以连接多种数据源，连接文件的文本格式包括excel，文本文件，access，json文件以及其它类型文件。数据处理可以用到pandas，运用之前学习过的python抓取数据。
* tableau数据连接：创建一个join-->编辑加入类型-->编辑加入字段（tableau支持数据混合/多个数据连接）

#### 数据仪表板和故事
* 通过仪表板将数据所要表达的故事展现出来，对数据进行分析，摸索更具有表达性故事性的图表
* 实操性比较强

#### [tableau的学习心得](https://sunsipan.github.io/2018/01/share-tebleau/)
> 相关阅读文本
* [tableau 哪一个图表或图形适合您？]({{ site.url }}/assets/pdf/Which_chart_or_figure_is_suitable_for_you.pdf )
* [最简单的图形与最复杂的信息]({{ site.url }}/assets/pdf/最简单的图形与最复杂的信息_nodrm.pdf )
<div markdown="0"><a href="https://pan.baidu.com/s/1dFq8UNB" class="btn btn-info">下载链接BOOK1</a></div>
<div markdown="0"><a href="https://pan.baidu.com/s/1eSET1SY" class="btn btn-info">下载链接BOOK2</a></div>
