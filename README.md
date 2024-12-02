

<p align="center" id="top"><a href="https://github.com/neptoo/awesome-css"><img src="https://s2.loli.net/2024/12/02/JQD2TaxRN7BFIzv.png" /></a></p>
<p align="center"><i>A playground for css tricks</i> 🤖</p>

## Demos

### 使用线性渐变和动画 实现波浪形旗帜

![flag](https://s2.loli.net/2024/12/02/l6PFBxhYoX5ZRpb.gif)

[在线预览](https://codepen.io/neptoo/pen/emONeZe)

- 使用 `linear-gradient` 的 **color stop** 属性，构造界限分明的色彩分区
- 将旗帜分为等宽的几列，依次设置不同的**动画延迟**时间，结合`transform: translate` 构造波浪效果

优化：

部分设备上的小数列存在显示bug；

正延时导致的前几帧的显示不流畅；

使用CSS伪类（.column:first-child / .column:last-child）设置列表的部分圆角