 MyIFE2018 Experience:
 ## 第二天：HTML
    1. html：超文本标记语言，用标签来描述网页；
      html5：最新的html标准，增加了很多新的API，将标签细分且语义化；
    2. 属性：提供了关于元素的更多信息，【属性名：属性值】；
    3. 文档类型：规定文档类型使得浏览器能正确显示文档；
    4. <meta> 元素可提供有关页面的元信息，比如针对搜索引擎和更新频度的描述和关键词；
    5. web语义化，将标签名称细分为各个部分，使得爬虫之类的可以更容易的读懂html文档；
    6. 链接<a href="">：①url实现网页跳转，②在网页内设置name，通过#name实现位置跳转；
    7. ul无序，ol有序；
      <dl>自定义列表
       <dt>项目</dt>
       <dd>对项目的描述</dd>
      </dl>
    
## 第三天：CSS 
   1. CSS（Cascading Style Sheets）：层叠样式表，对网页进行样式渲染；
   2. 选择器{属性名：属性值}；
   3. 选择器是用来定位想要样式化元素的位置；
   4. 文本的常用样式：
       文本缩进：text-indent
       文本对齐：text-align
       字间隔：word-spacing
       字母间隔：letter-spacing
       字母转换：text-transform
       文本装饰：text-decoration
       处理空白符：white-space
       文本方向：decoration
       文本颜色：color
       背景颜色：background-color
       文本阴影：text-shadow
       
- &#12288 一个中文间隔
- flex布局会使得div变成类似inline-block的形式，能够水平放置
- 可以通过flex实现导航栏的自适应（grow，shrink都设为1）
- 设置flex不会影响到孙子元素，孙子元素要使用的话要重新设置为flex
- div里文字不能换行，可以设置**word-wrap：break-word；**来实现换行
