## 框属性
### 基本属性： width 和 height  
width 和 height 设置内容框（content box）的宽度和高度，内容框是框内容显示的区域——包括框内的文本内容，以及表示嵌套子元素的其它框。
### padding
padding 表示一个 CSS 框的内边距 ——这一层位于内容框的外边缘与边界的内边缘之间。该层的大小可以通过简写属性padding 一次设置所有四个边，或用 padding-top、padding-right、padding-bottom 和 padding-left 属性一次设置一个边。
### border：
CSS框的边界（border）是一个分割层，位于内边距的外边缘 和 外边距的内边缘 之间。一般默认为0---从而让不可见. border 简写属性可以让我们一次设置所有四个边，例如  border: 1px solid black; 但这个简写可以被各种普通书写的更详细的属性所覆盖：
- border-top, border-right, border-bottom, border-left: 分别设置某一边的边界厚度／风格／颜色。
- border-top, border-right, border-bottom,border-left:分别设置某一边的边界厚度/风格/颜色，并应用到全部的四边边界。

### margin
外边界（margin）代表css框周围的外部区域，称为外边距，它在


#盒子显示（display）类型  
迄今为止我们所说的都是针对块级元素的盒子。不过，CSS 还有元素行为不同的其它类型的盒子。元素的盒子类型是由 display 属性指定的。

常见的 display 的类型：
常见的值有三种：block， inline， inline-block
- 块盒（block） 是被定义为堆放在其它盒子之上的盒子（即盒子之前以及之后的内容出现在不同的行上），并且可以给它设置高度和宽度。上面所述的整个盒模型都适用于块盒。 
- 行内盒（inline box）与块盒相反：它跟随文档的文本流堆放（即，它会与周围的文本和其它行内元素出现在同一行，并且其内容会像段落中的文本行一样，随着文本流换行）。宽度和高度设置对行内盒无效；在行内盒上的所有内边距、外边距和边界设置会改变周围文本的位置，但是不会影响周围块盒的位置。  
- 行内块盒（inline-block） 它介于两者之间：它会 随着文本流堆放，不会在其创建前后换行；不过同时，他可以像块盒一样，使用宽度和高度设置大小；  
