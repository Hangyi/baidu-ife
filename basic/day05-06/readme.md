## 学习时间

- 8hours

## 学习内容

- 百度前端编码规范


- 盒模型的概念

  - Margin(外边距) - 清除边框外的区域，外边距是透明的
  - Border(边框) - 围绕在内边距和内容外的边框
  - Padding(内边距) - 清除内容周围的区域，内边距是透明的
  - Content(内容) - 盒子的内容，显示文本和图像

- inline、block和inline-block的概念

  - block：将元素转为块元素，块元素占一行，可以设置宽和高。

  - inline：将元素转为行内元素，占一行，不可以设置宽和高。

  - inline-block：将元素设置为行内块元素，这时元素既可以设置宽和高，又占一行。但这时的元素之间会出现缝隙，解决办法：1）设置浮动 2)将父元素的font-size设置为0，子元素设置为实际大小

- 常见的几种元素：

    - 块级元素：div、h1~h6、li、dt、dd、p

    - 行内元素：span、u、a、em、b、i、u、em

    - 行内块元素：input、img、button、textarea、label。

  - p标签不能包含div标签，块级元素和行内元素之间的嵌套，是块级可以嵌套行内元素和某些块级元素，而行内元素不能嵌套块级元素，可以嵌套文本和其他行内元素。

    但有几个特殊的块级元素只能包含行内元素，h1~h6、p、dt，因此p标签不能包含div元素，因为浏览器渲染的缘故，p包含div元素时会被渲染成：`<p>xxx<p> <div>xxx<div> <p>xxx<p>`

    li 内可包含 div 标签：`<li><div><div><li>`

    块级元素与块级元素并列、行内元素与行内元素并列，如下：

    - `<div><h1><h1><p><p><div>`---正确
    - `<div><a><a><span><span><div>`---正确
    - `<div><h2><h2><span><span><div>`---错误，行内元素与块级元素并列了

- 内外边距，宽度，高度，box-sizing等属性

  - 内边距：padding---定义元素边框与元素内容之间的空白区域。
  - 外边距：margin---围绕在元素边框的空白区域是外边距。
  - 宽度：width---元素宽度
  - 高度：height---元素高度
  - `box-sizing: content-box|border-box|inherit`---指定宽度和高度

- 浮动，清除浮动

  - 浮动：

    浮动的元素脱离标准流、互相贴靠、有文字环绕效果

  - 清除浮动：

    1）清除浮动：清除对应的单词是 clear，对应CSS中的属性是 clear：left | right | both | none； 

    2）闭合浮动：更确切的含义是使浮动元素闭合，从而减少浮动带来的影响。

- 如何使用浮动进行布局

  - float

## 总结

拖了好久才完成，感觉好难，到最后还是参考别人的解决方案
https://github.com/DukeLuo/IFE2018-Base/blob/master/day05-06

## 待解决的疑问