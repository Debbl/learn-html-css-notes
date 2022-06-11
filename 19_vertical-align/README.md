# vertical-align

- 结论：line-boxes一定会想办法包裹住当前行中所有的内容。 
- 但是，但是为什么对齐方式千奇百怪呢？ 
  - 你认为的千奇百怪，其实有它的内在规律 
  - 答案就是baseline对齐
- 我们来看官方vertical-align的默认值：没错，就是baseline
- 但是baseline都是谁呢？ 
  - 文本的baseline是字母x的下方 
  - inline-block默认的baseline是margin-bottom的底部（没有，就是盒子的底部） 
  - inline-block有文本时，baseline是最后一行文本的x的下方

# vertical-align的其他值

- 现在，对于不同的取值就非常容易理解了 
  - baseline(默认值)：基线对齐（你得先明白什么是基线） 
  - top：把行内级盒子的顶部跟line boxes顶部对齐 
  - middle：行内级盒子的中心点与父盒基线加上x-height一半的线对齐  bottom：把行内级盒子的底部跟line box底部对齐 
  - \<percentage>：把行内级盒子提升或者下降一段距离（距离相对于line-height计算\元素高度）， 0%意味着同baseline一 样
  - \<length>：把行内级盒子提升或者下降一段距离，0cm意味着同baseline一样
- 解决图片下边缘的间隙方法:
  - 方法一: 设置成top/middle/bottom 
  - 方法二: 将图片设置为block元素

# line-height 的继承问题