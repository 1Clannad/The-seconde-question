# The-seconde-question
polished code
# 背景介绍
&emsp;&emsp;B站的使用频率与交际影响力逐渐提升，大家为了找到共同话题，不可避免地要比较关注列表中共同的up主。作者从这个角度出发，编写了爬取两个用户共同关注列表的程序，由共同关注的列表再得到共同关注的用户的相关信息。<br>
# 使用说明
&emsp;&emsp;先输入两个用户的uid,之后在mysql中创建两个表，存储用户关注列表中的相关要求数据，如：uid、用户昵称、B站等级、粉丝数。之后将表格自然连接，使用SQL语句对于符合条件的元组的属性进行选取，结果存储在表中。
