# cssDemos

#### demo1——margin折叠问题
#### demo2——相对定位与绝对定
#### demo3——浮动
#### demo4——absolute默认位置，即left、top的相对位置
#### demo5——默认垂直对齐方式，元素的默认margin、padding值
#### demo6——行内元素的宽高
#### demo7——方块菜单自适应界面
#### demo8——缩放页面时，保持元素宽高比（1）
#### demo9——缩放页面时，保持元素宽高比（2）
#### demo10——使浮动元素撑开其所在容器
#### demo11——行内元素垂直居中（单行、多行）
#### demo12——选项卡的实现

### 知识点记录
1.min-height:要使min-heigh生效，其父元素必须有明确的高度，特别是当父元素设置了min-height,而没有设置height时,子元素的min-height不会起作用；

***

### css编写思考流程

1. 考虑元素是块级元素还是行内元素
2. 考虑元素的定位：相对定位还是绝对定位
3. 考虑元素left top margin padding等属性
4. 考虑元素大小颜色等属性

若元素是行内元素，考虑line-height vertical-align text-align 以及继承等属性

### CSS命名规范（规则）
常用的CSS命名规则

头：header <br/>
内容：content/container  <br/>
尾：footer  <br/>
导航：nav  <br/>
侧栏：sidebar  <br/>
栏目：column  <br/>
页面外围控制整体佈局宽度：wrapper <br/> 
左右中：left right center  <br/>
登录条：loginbar  <br/>
标志：logo  <br/>
广告：banner  <br/>
页面主体：main  <br/>
热点：hot  <br/>
新闻：news  <br/>
下载：download  <br/>
子导航：subnav  <br/>
菜单：menu  <br/>
子菜单：submenu  <br/>
搜索：search  <br/>
友情链接：friendlink <br/> 
页脚：footer  <br/>
版权：copyright  <br/>
滚动：scroll  <br/>
内容：content  <br/>
标签：tags  <br/>
文章列表：list  <br/>
提示信息：msg  <br/>
小技巧：tips  <br/>
栏目标题：title  <br/>
加入：joinus  <br/>
指南：guide  <br/>
服务：service  <br/>
注册：regsiter  <br/>
状态：status  <br/>
投票：vote  <br/>
合作伙伴：partner <br/>

### id的命名:

* 1)页面结构

容器: container <br/>
页头：header <br/>
内容：content/container <br/> 
页面主体：main <br/>
页尾：footer <br/>
导航：nav <br/>
侧栏：sidebar <br/>
栏目：column <br/>
页面外围控制整体布局宽度：wrapper <br/> 
左右中：left right center<br/>

* (2)导航

导航：nav <br/>
主导航：mainnav <br/>
子导航：subnav <br/>
顶导航：topnav <br/>
边导航：sidebar <br/>
左导航：leftsidebar <br/>
右导航：rightsidebar <br/>
菜单：menu <br/>
子菜单：submenu <br/>
标题: title <br/>
摘要: summary<br/>

* (3)功能

标志：logo <br/>
广告：banner <br/>
登陆：login <br/>
登录条：loginbar <br/>
注册：register <br/>
搜索：search <br/>
功能区：shop <br/>
标题：title <br/>
加入：joinus <br/>
状态：status <br/>
按钮：btn <br/>
滚动：scroll <br/>
标籤页：tab <br/>
文章列表：list <br/>
提示信息：msg <br/>
当前的: current <br/>
小技巧：tips <br/>
图标: icon <br/>
注释：note <br/>
指南：guild <br/>
服务：service <br/>
热点：hot <br/>
新闻：news <br/>
下载：download <br/>
投票：vote <br/>
合作伙伴：partner<br/> 
友情链接：link <br/>
版权：copyright<br/>

### 注意事项::

1. 一律小写; 
2. 尽量用英文; 
3. 不加下划线; 
4. 尽量不缩写，除非一看就明白的单词。

### CSS样式表文件命名

主要的 master.css <br/>
模块 module.css <br/>
基本共用 base.css <br/>
布局、版面 layout.css <br/>
主题 themes.css <br/>
专栏 columns.css <br/>
文字 font.css <br/>
表单 forms.css <br/>
补丁 mend.css <br/>
打印 print.css <br/>
