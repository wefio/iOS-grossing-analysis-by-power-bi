# iOS-grossing-analysis-by-power-bi
用powerbi进行的IOS畅销榜流水分析

## 以下是一个简单教程，主要是自学资源指路，因为教程不是很好找

# 相关教程：
`公众号：PowerBI星球、wujunmin
`bilibili：孙兴华zz、wujunmin

# 找数据
说实话，这个我帮不了你,但是某些方面我可以给你指条路
[国家统计局](https://www.stats.gov.cn/)
[国家数据（和上面应该是一家）](https://data.stats.gov.cn/)
[CnOpenData（不知道是啥，瞎找的）](https://www.cnopendata.com/all-data)
[七麦数据（软件排行榜相关，我用的那个）](https://www.qimai.cn/)
[世界黄金协会（来自up主小Lin说）](https://china.gold.org/)
[关键词 常用数据公开网站 搜出来的](https://www.zhihu.com/tardis/bd/art/128508857?source_id=1001)
<p>不想找就自己编（但是假数据这玩意真比真的容易吗？）</p>

# 文件归类
## 为什么归类
这可能是一个容易忽略的点，数据不多可能体现不出优势，但是如果你的数据不止一张表后面会很方便。因为pbi支持文件夹导入，可以一键刷新增加的表。比如我的表其中一组数据有30张，一个一个导入要累死了
# Power Query(一)
这不仅是pbi的工具，excel也有，推荐从excel开始练手。值得注意的一点，PQ是数据处理工具，不能像excel一样修改某一格，所以想要填数据、改某一个数据，拿excel去改你的原始表

七天入门PowerBI.PDF
余下的部分看文档自己学吧
文档也可以 公众号“PowerBI星球”回复“PowerBI”
练习数据自己去公众号找，公众号“PowerBI星球”，回复“PQ体验”
这里只提供一点使用经验
如果你的数据大部分都相似，且只有文件名不同，导入pq之后数据行数不对。手动加上一列文件名。
附带一点点excel使用方法
框的右下角，变成黑色十字“+”，下拉可以自动填充
如果这一列都一样，就填两行一样然后下拉
也可以双击黑色小十字

# 数据建模
学会了简单pq之后可以试着把自己的数据导入pbi了。
左侧第三个是建模，第二个是pq，第一个是可视化报表。
如果你学过大学计算机A，那么你应该已经对数据库有一点初步认识，好处就是，你会学的更快。
[相关学习资源]（https://www.bilibili.com/video/BV1tf4y117Sh/)
你所需要的知识只有：
`1. 什么是数据类型
`2. 数据表之间有什么关系
`3. 数据表应该什么样
注：名词可能不准确，意会一下
视频差不多看几节课就够了
当你导入了几张表之后，就可以看看数据建模了，建模可能会跟着pq部分一起改

# Power Query(二)
[相关学习资源](https://www.bilibili.com/video/BV1oa4y1j75e/)
同样看几集应该就差不多了
# PBI部分
[相关学习资源](https://www.bilibili.com/video/BV1W54y1i7dE/)
[相关学习资源](https://www.bilibili.com/video/BV1r54y1i75n/)
重点在于多看看能用什么图表

# PowerPivot
（度量值/DAX函数/PP/超级透视）
[相关学习资源](https://www.bilibili.com/video/BV1YE411E7p3/)
看着很难，但是主要是多抄。
想要华丽的图表可以关注公众号“wujunmin”
