# 1. border 图形

- https://css-tricks.com/the-shapes-of-css/#top-of-site、

# 2. 网络字体

- 字体格式转换 https://font.qqe2.com/

- 字体的兼容性写法  https://www.paulirish.com/2009/bulletproof-font-face-implementation-syntax/

```css
@font-face {
    font-family: "why";
    src: url("./fonts02/AaQingHuanYuanTi.eot");
    /* IE9 */
    src: url("./fonts02/AaQingHuanYuanTi.eot?#iefix") format("embedded-opentype"),
        /* IE6-IE8 */
        url("./fonts02/AaQingHuanYuanTi.woff") format("woff"),
        /* chrome、firefox */
        url("./fonts02/AaQingHuanYuanTi.ttf") format("truetype"),
        /* chrome、firefox、opera、Safari, Android, iOS 4.2+ */
        url("./fonts02/AaQingHuanYuanTi.svg#uxfonteditor") format("svg");
    /* iOS 4.1- */

    font-style: normal;
    font-weight: 400;
}
```

# 3. cursor

- cursor常见的设值有 
  - auto：浏览器根据上下文决定指针的显示样式，比如根据文本和非文本切换指针样式 
  - default：由操作系统决定，一般就是一个小箭头 
  - pointer：一只小手，鼠标指针挪动到链接上面默认就是这个样式 
  - text：一条竖线，鼠标指针挪动到文本输入框上面默认就是这个样式  none：没有任何指针显示在元素上面