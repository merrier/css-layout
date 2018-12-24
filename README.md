# css-layout

总结了常用的布局，也经常会在面试的时候遇到

### 圣杯（双飞翼）布局

> 三列等高、中间宽度自适应，两边宽度固定

#### 利用margin负值

[圣杯布局-利用margin负值](https://merrier.github.io/css-layout/grail/method1.html)

#### 利用margin负值和float

> 可以实现高度随内容自适应，但是left和right的背景颜色需要保持相同

[圣杯布局-利用margin负值和float](https://merrier.github.io/css-layout/grail/method2.html)

#### 利用中间盒子

> 中间的子盒子里再加一个子盒子，然后对这个子盒子设置`margin-left`和`margin-right`来为左右盒子留位置

[圣杯布局-利用中间盒子](https://merrier.github.io/css-layout/grail/method3.html)

### 两列等高布局

> 两列等高、高度随文章内容自适应布局。

#### 利用伪元素和清除浮动

[两列等高布局-利用伪元素和清除浮动](https://merrier.github.io/css-layout/two-columns/method1.html)

#### 利用margin负值

> 给每个框设置大的底部内边距，然后用数值相似的负外边距消除这个高度。这会导致每一列溢出容器元素，如果把外包容器的overflow属性设为hidden，列就在最高点被裁切

[两列等高布局-利用margin负值](https://merrier.github.io/css-layout/two-columns/method2.html)

#### 利用border

[两列等高布局-利用border](https://merrier.github.io/css-layout/two-columns/method3.html)

#### 利用背景图片

> 主要依靠一张图片，然后将其平铺，使页面在视觉上产生等高效果；这个方法需要根据你的实际项目需求，值得注意的是背景图片切图时必须以两列的形式，否则达不到等高效果

[方案来源](http://www.cnblogs.com/JoannaQ/p/3424594.html)

### 仿微信布局

> 实现微信聊天页面布局

[仿微信布局demo](https://merrier.github.io/css-layout/weixin/method1.html)


## 待整理

* https://github.com/merrier/css-layout-1

* https://juejin.im/post/5c171f0ef265da61553abade