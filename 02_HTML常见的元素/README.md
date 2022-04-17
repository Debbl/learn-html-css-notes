# 文档申明
- HTML5 的文档申明
```html
<!DOCTYPE>
```
# html 元素
- lang
    - `en`
    - `zh-CN`
# meta
- charset
# 常见的元素
> 不同的标签，浏览器会自动加上不同的 CSS 样式 （user agent stylesheet）
## h 元素 （Heading）
> 可以做 SEO 优化
- h1-h6
## p 元素 （paragraph）
## img 元素 （image）
> 可替换元素 （replaced element）
- src (source)
    - 网络路径
    - 本地路径
        - 相对路径
        - 绝对路径
- alt
    - 加载不成功显示对应文字
    - 屏幕阅读

## a 元素 （anchor）

- 属性
  - href (Hypertext Reference)
    - 指定要打开的 URL 地址
    - 也可以是一个本地地址
  - target 在何处显示链接的资源
    - _self 默认值，当前窗口
    - _blank 在新的一个标签页打开
    - _parent 在父窗口打开， 与 `iframe` 结合使用
    - _top 在顶层窗口打开， 与 `iframe` 结合使用
- 锚点链接
  - 在跳到的元素定义一个 `id` 属性
  - 在 `a` 元素的 `href` 指定对应的 `id`
- 图片链接
- 其他 URL 地址
  - 文件地址，压缩包
  - `mailto:`

## iframe 元素

> 在一个文档中，嵌入其他的文档

- 属性
  - frameborder 是否显示边框
    - 1 显示
    - 0 不显示
- 响应头 `X-Frame-Options: sameorigin` 禁止 `iframe`

## div 元素 （division / 分开，分配）

- 不同行，占一行

## span 元素 （跨越、涵盖）

- 包裹内容，行内

# 不常用的元素

- strong
- i
- code
- br
- https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element

# HTML 的全局属性

- id
- class
- style
- title
- https://developer.mozilla.org/zh-CN/docs/Web/HTML/Global_attributes

