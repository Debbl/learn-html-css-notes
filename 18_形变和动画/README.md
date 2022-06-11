# transform

- translate
- scale
- rotate
- skew

# transform-origin

>  原点的位置

# transform 设置多个值

​    \*<transform-function>+*

​     *+: 一个或者多个, 并且多个之间以空格分隔*

​     *transform: scale() translate();*



​    \*<box-shadow>#*

​     *#: 一个或者多个, 多个之间以 `,` 分隔*

​     *box-shadow: 1px 1px 1px 1px #f00,* 

# 动画 transition

- transition-property
- transition-duration
- transition-timing-function
- transition-delay

# 关键帧动画 Animation

- animation-name：指定执行哪一个关键帧动画 
- animation-duration：指定动画的持续时间
- animation-timing-function：指定动画的变化曲线
- animation-delay：指定延迟执行的时间
- animation-iteration-count：指定动画执行的次数，执行infinite表示无限动画 
- animation-direction：指定方向，常用值normal和reverse
- animation-fill-mode：执行动画最后保留哪一个值 
  - none：回到没有执行动画的位置 
  - forwards：动画最后一帧的位置 
  - backwards：动画第一帧的位置
- animation-play-state：指定动画运行或者暂停（在JavaScript中使用，用于暂停动画）

# 水平居中方案

- 行内级元素
  - 设置父元素的 `text-align: center;`
- 块级元素
  - 当前块级元素固定宽度，并 `margin: 0 auto;`
- 绝对定位
  - 元素有宽度的情况下 `left: 0; right: 0; maring: 0 auto;`
- flex
  - `justisy-content: center;`

# 垂直居中方案

- 绝对定位
  - 元素有宽度， `top: 0; bottom: 0; margin: auto 0`;
- flex
  - `align-items: center;`
- `top: 50%; transform: translate(0, -50%);`