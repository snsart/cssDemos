﻿1.模式名称
2.模式描述
3.模式示意图
4.解决方案
5.demo
6.知名网站示例

一、并列布局



二、嵌套布局


一、CSS
css模式1：左右并排——把左边的块设置为绝对定位，右边的块设置margin-left为左边块的宽度。
css模式2：上下结构——两个块上下排列，解决办法：直接使用普通流进行布局，前提是两个块必须设置为块级元素；
css模式3：横向列表——解决办法:使用li标签，关键需要设置两点：1.li标签使用浮动 2.其包围快必须是有宽度的；
css模式4：横向列表充满包围块——解决办法：按百分比设置li元素的宽度，即宽度为：1/numLi*100+"%";
css模式5：包围块恰好包围横向列表——模式5为包围块宽度已知，内部列表通过拉伸充满包围块，本模式为内部列表的宽度已知，调整外部包围块使其恰好包围列表；
解决办法有两种：1.设定包围块为绝对定位或浮动定位；
				2.设定包围块显示属性为行内块元素inline-block;
css模式6：纵向列表——解决办法：给定包围块宽度，li标签设置宽度100%，使用普通流布局即可；
css模式7：块中文字垂直居中——使块的height和line-height数据相同，这里单位不能用百分比，因为height的百分比是相对于父元素高度，而line-height是相对于字体的font-size；
css模式8：在包围块中水平居中——包围块必须有宽度，块的margin-left和margin-right设置为auto

知识点：

一、浮动定位与绝对定位的区别：
浮动定位和绝对定位都会脱离普通文档流，区别有两点：
1.绝对定位会忽略当前层级下的所有其他元素，无论这些元素是什么定位；而浮动元素不会忽略其他的浮动元素；
2.绝对定位可以通过left、top等属性设置元素的位置，浮动元素没有这些属性；

二、static定位与relative定位的区别：
static和relative都会占用普通文档流中的空间，区别如下：
1.relative定位可通过left、top等属性设置元素的偏移位置，static元素位置不可调整；
2.当为内部定位为absolute的元素设置left、top的属性时，它们会参考relative定位的元素而忽略static定位的元素；