# 氩洛谷 - 夜间模式

**最新版本 Beta 0.1.1**

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

> [Stylus插件下载链接](https://www.crxsoso.com/webstore/detail/clngdbkpkpeebahjckkjfobafhncgmne)

### userstyles.world (推荐)

1. 先按照[此文章](https://www.luogu.com.cn/blog/fsy2017/material-luogu-material)的方式安装`Stylus`插件。
2. 打开[userstyles.world](https://userstyles.world/style/3238/default-slug)，点击蓝色的`Install`按钮。
3. 在新页面中勾选"检查更新"，点击"安装样式"。

**发布更新后会自动更新，无需手动安装**

### 手动安装

1. 先按照[此文章](https://www.luogu.com.cn/blog/fsy2017/material-luogu-material)的方式安装`Stylus`插件。
2. 打开洛谷主页，点击右上角`Stylus`图标，为`www.luogu.com.cn`添加一个样式。
3. 点击`导入`，将存储库中`main.css`的全部内容复制进文本框内。
4. 依次点击`覆盖替换导入`，`保存`。

**每当发布更新后需要重新执行3-4步**

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

## 更新日志

Beta 0.1.1:

修复行间代码块样式

Beta 0.1.0:

**中等版本更新**

增添代码框夜间模式(`Github Dark`主题)

Beta 0.0.7:

修复问题:
- （主页打卡日历）建议改一下颜色

Beta 0.0.6:

增添`Extend-Luogu`支持

Beta 0.0.5:

修复问题:
- 图床 看的不太清晰

Beta 0.0.4:

修复问题:
- 「我的」 是白色的
- 题解工具栏是白的
- 私信是白的
- 通知中心是白的

Beta 0.0.3:

修复问题:
- 题解和云剪贴板的渐变是白的
- 头像的悬浮框是白的

Beta 0.0.2:

修复问题:
- 发表言论时，我竟看不见光标了
- 左边「应用」 点开全是白的，输入验证码是黑的（
- 以及主页几个讨论的分界线比较不明确

Beta 0.0.1:

初始版本
