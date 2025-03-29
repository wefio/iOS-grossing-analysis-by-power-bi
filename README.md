# iOS-grossing-analysis-by-power-bi
用powerbi进行的IOS畅销榜流水分析
![pbi](https://github.com/user-attachments/assets/a8d47391-2f94-44e6-b940-9037d7bff74e)


## 以下是一个简单教程，主要是自学资源指路，因为教程不是很好找

# 相关教程：
公众号：PowerBI星球、wujunmin<br>
bilibili：孙兴华zz、wujunmin

# 找数据
说实话，这个我帮不了你,但是某些方面我可以给你指条路<br>
[国家统计局](https://www.stats.gov.cn/)<br>
[国家数据（和上面应该是一家）](https://data.stats.gov.cn/)<br>
[CnOpenData（不知道是啥，瞎找的）](https://www.cnopendata.com/all-data)<br>
[七麦数据（软件排行榜相关，我用的那个）](https://www.qimai.cn/)<br>
[世界黄金协会（来自up主小Lin说）](https://china.gold.org/)<br>
[关键词 常用数据公开网站 搜出来的](https://www.zhihu.com/tardis/bd/art/128508857?source_id=1001)<br>
<p>不想找就自己编（但是假数据这玩意真比真的容易吗？）</p>

# 文件归类
## 为什么归类
这可能是一个容易忽略的点，数据不多可能体现不出优势，但是如果你的数据不止一张表后面会很方便。因为pbi支持文件夹导入，可以一键刷新增加的表。比如我的表其中一组数据有30张，一个一个导入要累死了
# Power Query(一)
这不仅是pbi的工具，excel也有，推荐从excel开始练手。值得注意的一点，PQ是数据处理工具，不能像excel一样修改某一格，所以想要填数据、改某一个数据，拿excel去改你的原始表

七天入门PowerBI.PDF<br>
余下的部分看文档自己学吧<br>
文档也可以 公众号“PowerBI星球”回复“PowerBI”<br>
练习数据自己去公众号找，公众号“PowerBI星球”，回复“PQ体验”<br>
这里只提供一点使用经验<br>
如果你的数据大部分都相似，且只有文件名不同，导入pq之后数据行数不对。手动加上一列文件名。

# 数据建模
学会了简单pq之后可以试着把自己的数据导入pbi了。<br>
![image](https://github.com/user-attachments/assets/3ab1f909-3321-44bf-9252-7e560eecf11a)
左侧第三个是建模，第二个是pq，第一个是可视化报表。<br>
如果你学过大学计算机A，那么你应该已经对数据库有一点初步认识，好处就是，你会学的更快。<br>
[Access教程 零基础入门教程 Access数据库 Access2016 office365 Access VBA AccessVBA](https://www.bilibili.com/video/BV1tf4y117Sh/)
你所需要的知识只有：<br>
1. 什么是数据类型<br>
2. 数据表之间有什么关系<br>
3. 数据表应该什么样<br>
注：名词可能不准确，意会一下<br>
视频差不多看几节课就够了<br>
当你导入了几张表之后，就可以看看数据建模了，建模可能会跟着pq部分一起改<br>

# Power Query(二)
[【2020年9月合集 全107集】Excel Power Query 零基础入门到M函数 Excel PowerQuery教程](https://www.bilibili.com/video/BV1oa4y1j75e/)<br>
同样看几集应该就差不多了
# PBI部分
[跟着孙兴华学习数据分析 第四季 可视化图表 PowerBI进阶篇 Power BI 【本季完】](https://www.bilibili.com/video/BV1W54y1i7dE/)<br>
[跟着孙兴华学习数据分析 第五季 自定义图表篇 PowerBI进阶篇 Power BI教程 【全季终】](https://www.bilibili.com/video/BV1r54y1i75n/)<br>
重点在于多看看能用什么图表

# PowerPivot
（度量值/DAX函数/PP/超级透视）<br>
[孙兴华讲Power BI之DAX神功【DAX原理】 PowerBI教程 PowerPivot通用 DAX函数](https://www.bilibili.com/video/BV1YE411E7p3/)<br>
看着很难，但是主要是多抄。<br>
想要华丽的图表可以关注公众号“wujunmin”
