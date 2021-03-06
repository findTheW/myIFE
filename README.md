 MyIFE2018 Experience:
 ## 第二天：HTML
   1. html：超文本标记语言，用标签来描述网页；
     html5：最新的html标准，增加了很多新的API，将标签细分且语义化；
   2. 属性：提供了关于元素的更多信息，【属性名：属性值】；
   3. 文档类型：规定文档类型使得浏览器能正确显示文档；
   4. <meta> 元素可提供有关页面的元信息，比如针对搜索引擎和更新频度的描述和关键词；
   5. web语义化，将标签名称细分为各个部分，使得爬虫之类的可以更容易的读懂html文档；
   6. 链接<a href=""></a>：①url实现网页跳转，②在网页内设置name，通过#name实现位置跳转；
   7. ul无序，ol有序；
      <dl>自定义列表
       <dt>项目</dt>
       <dd>对项目的描述</dd>
      </dl>
    
## 第三天：CSS 
   1. CSS（Cascading Style Sheets）：层叠样式表，对网页进行样式渲染；
   2. 选择器{属性名：属性值}；
   3. 选择器是用来定位想要样式化元素的位置；
   4. 图片自适应img{
 width:auto;
 height:auto;
 max-width:100%;
 max-height:100%;
}
   5. ul > li 大于号表示只有儿子辈的会被影响，li里面的li就不受影响
       
- **&#12288 一个中文间隔**
- flex布局会使得div变成类似inline-block的形式，能够水平放置
- 可以通过flex实现导航栏的自适应（grow，shrink都设为1），将flex设置为1时，不管里面多少内容，他都会进行分配空间
- 设置flex不会影响到孙子元素，孙子元素要使用的话要重新设置为flex
- div里文字不能**换行**，可以设置word-wrap：break-word来实现换行
- 通过给**超链接a**设置宽度，从而使得超链接可以点击的范围扩大
- ul列表会自带margin，所以得将margin置为0
- 当使用position：fixed时，会使其脱离文档流，所以要重新设置宽度什么的
- 可以通过**z-index**进行掩盖

## 小技巧
> 1. **分割线**：可以创建一个div，设置其border，然后在需要的地方加上div当做分割线用
> 2. 子div可能没有继承flex，
>>       display：flex；（弹性布局）
>>       justify-content：center；（水平居中）
>>       align-items：center；（垂直居中）
>>       word-wrap：break-all;（超过div就换行）
>>  这样就能实现div里内容**完全居中**
> 3. 文字**在宽度内左右分布** ：文字 （间隔） 图标 → 可以设置display：flex，justify-content：space-between。
> 4. 将body设置display：flex，然后在一个div设置height：100**vh**（vh表示浏览器可视高度），就可以实现多个div**高度自适应浏览器**[可能会出现其他问题]
> 5. vw可以解决横向自适应
> 6. **calc()** 可以来用计算宽度：【符号两边要有空格】比如（100vh - 100px），（100vh - 10%） 
> 7.placeholder : 设置占位符文字  

> hbuilder 展开/折叠代码快捷键 ctrl + alt + +/-   
> ctrl + shift + X :可以使选中文字变大写  
> ctrl + D : 删除当前行  
> alt + shift + A : 使得选择变成范围的形式  
