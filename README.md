使用说明
=========

TableGroup专为分组式表格而生，适用于把一个二维数据按照一定规则进行分组合并生成html table，通过简单的分组规则生成一个高度自定义的table组件。

##特点优势

- 这是非常高效的java实现，比使用大规模的统计报表引擎要易用和轻量的多
- 比使用各类页面模版化手段更要简单、易用、通用
- 在不手动操作html的情况下完成同等的高度灵活自定义的需求

##适合的场景

- 二维数据在多个列上进行分组合并
- 二维数据多个列的分组要约束在前一列(某一列)的分组中
- 对分组后的数据进行简单统计计算
- 对分组后的html对象在渲染输出时基于css选择器的拦截和修改

##主要的内部实现

- HtmlElement的树型构建
- 节点的渲染器、拦截点、修改器和对应规则
- 分组规则的构建和定义
- css选择器的语法分析和构建
- css选择器的倒序匹配器
- 简易的统计计算

## 效果简介

![image](https://github.com/spance/tableGroup/raw/master/screenshot/tableGroup-demo.png)


License
----

MIT

**Free Software, Hell Yeah!**