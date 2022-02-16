# 氩洛谷 - 夜间模式

**Beta 0.0.1**

**仍处在测试状态**

若有问题可在`Issues`中提出或直接使用洛谷私信。

## 简介

[氩洛谷](https://www.luogu.com.cn/blog/fsy2017/material-luogu-material)是一个美化[洛谷](https://www.luogu.com.cn)的`CSS`样式，深受用户（比如我）喜爱。

但氩洛谷有一个很大的缺点：没有夜间模式（自带的夜间模式无法使用）。因此我对氩洛谷的样式做了亿点点修改，做出了夜间模式的氩洛谷。

> 本人甚菜，`CSS`杂乱无章，若有不规范之处请多多关照。

## 效果图

![主页](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-1.webp)

![题目列表](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-2.webp)

![题面](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-3.webp)

![题单](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-4.webp)

![比赛](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-5.webp)

![讨论](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-6.webp)

![回帖](https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/argon-luogu-7.webp)

## 安装教程

1. 先按照[此文章](https://www.luogu.com.cn/blog/fsy2017/material-luogu-material)的方式安装`Stylus`插件。
2. 打开洛谷主页，点击右上角`Stylus`图标，为`www.luogu.com.cn`添加一个样式。
3. 点击`导入`，将存储库中`main.css`的全部内容复制进文本框内。
4. 依次点击`覆盖替换导入`，`保存`。

## 背景图片修改

找到第二部分中的这些代码：

```css
/*此区域用来应用一些自定义设置*/
/*--------------------背景图片，默认是颜色编码*/
html > body{
    background-image: url(https://cdn.jsdelivr.net/gh/dajia-1701/image-host@master/3.2ig0usnlvqe0.webp);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
```
将`background-image: url(...);`中`url()`里的内容改为你的图片链接。

## 已知问题

- 代码框仍是正常样式（不敢乱改高亮）
