### 移动端常见布局

#### 1.流式布局

或者叫**百分比布局**,在布局的时候宽度常常被设置为百分比值 其他值依然用像素表示 布局依然用浮动 定位 流式布局相对于其他布局还是比较简单的

**案例**:京东移动端的首页 分类页

#### 2.flex布局

全新的布局 用一种全新的方式控制元素横向显示或者竖向显示 flex布局相对来说比较复杂

**案例:**携程

#### 3.rem布局

简单粗暴 rem相对于html字体大小的单位 当我们拿到设计稿的时候 先看设计稿的宽度是多少 再设置根元素的字体大小 写布局的时候 所有的元素在做计算的时候 都是相对于根元素的 那么只要根元素的字体大小发生变化 整体网页就会发生变化, **目标像素值** / **根元素的字体大小**.

**案例:**石榴

#### 4.响应式布局

兼容pc端与移动端,检测屏幕宽度，针对不同的屏幕宽度为相同的HTML结构设置不同的样式，以呈现出符合当前屏幕宽度网站样式。

使用原理

- css3媒体查询(Media Query)
- 检测屏幕宽度，为不同的屏幕尺寸设置不同的样式

**案例:**微金所

