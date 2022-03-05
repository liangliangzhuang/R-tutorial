---
title: "庄闪闪的可视化手册"
author: "庄亮亮"
date: "2022年2月5日"
description: "这是用R的bookdown功能制作中文图书的模板，输出格式为bookdown::gitbook和bookdown::pdf_book."
documentclass: book
biblio-style: apa
bibliography: [mybib.bib]
link-citations: yes
---



# 简介 {-}


R软件的bookdown扩展包是R Markdown的增强版，
支持自动目录、文献索引、公式编号与引用、定理编号与引用、图表自动编号与引用等功能，
可以作为LaTeX的一种替代解决方案，
在制作用R进行数据分析建模的技术报告时，
可以将报告文字、R程序、文字性结果、表格、图形都自动地融合在最后形成的网页或者PDF文件中。

Bookdown使用的设置比较复杂，
对初学者不够友好。
这里制作了一些模板，
用户只要解压缩打包的文件，
对某个模板进行修改填充就可以变成自己的中文图书或者论文。
Bookdown的详细用法参见<https://bookdown.org/yihui/bookdown/>，
在李东风的[《统计软件教程》](http://www.math.pku.edu.cn/teachers/lidf/docs/Rbook/html/_Rbook/index.html)也有部分介绍。

一些常用功能的示例在`0101-usage.Rmd`文件中，
用户可以在编辑器中打开此文件参考其中的做法。

Bookdown如果输出为网页，
其中的数学公式需要MathJax程序库的支持，
用如下数学公式测试浏览器中数学公式显示是否正常：

$$
\text{定积分} = \int_a^b f(x) \,dx
$$

如果显示不正常，
可以在公式上右键单击，
选择“Math Settings--Math Renderer”，
依次使用改成“Common HTML”，“SVG”等是否可以变成正常显示。
PDF版本不存在这样的问题。





