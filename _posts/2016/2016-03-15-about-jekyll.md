---
layout: post
title: 关于Jekyll的一些事情
categories: Program
tags: Jekyll
---

## 说一说为什么会用Jekyll

这个博客的技术是用[Jekyll](https://github.com/mojombo/jekyll)以及[Github Page](http://pages.github.com)。各种技术名词层出不穷，对于新手来说真是晕菜，本以为自己也号称是前端工程师，做过了一些网站了。没想到搭起来这个Jekyll的架构也是颇费了一番功夫。说起来还是资料不够多，就像我以前看了一周的新版Magento资料，头都大了，却发现框架改动太大，新旧资料前后矛盾。新技术的时效性太强了，可一定要注意找最新的来看啊。

下面说一下我看过的几篇文章和它们的问题：

#### 1. [零基础从wordpress到jekyll](http://www.daijiang.name/cn/2013/12/27/wordpress-to-jekyll/)
从这篇文章我被引到了[这里](http://jekyllbootstrap.com/lessons/jekyll-introduction.html)，JekyllBoostrap是Jekyll的一个主题，就是用了Bootstrap的前端UI框架。但是我用教程里面说的方法好多遍，总是有各种稀奇古怪的问题。而且看github代码库这个项目已经有多半年没有更新过了，可能比起Github Page推荐使用的配置太老了，我没有去验证这一点，但是一次次看不到自己想要的结果，真的是很沮丧，我只想要一个简简单单写字的地方，实在承受不起这一次次的重装。

#### 2.[【建站】Wordpress 与 Jekyll 优劣比较](http://cn.derekyang.us/wordpress-jekyll/)
这篇文章下面居然出现了很多吐槽，技术问题都能掐起来真是服了。大致比较了WP和Jekyll的优劣。就我个人经验而言，Jekyll还是交给程序员去用吧，github我至今还有好多问题没搞明白，更何谈用它搭静态博客。在我工作的媒体网站里，editor们有时候连Wordpress的后台都要教教才会用，就甭提用这种高度自动化的新方法了。并不是小看editor哦，只是术业有专攻，他们花在写稿的时间我们用来写码了，那些高质量的稿件也是我所难以企及的。

#### 3.[阮一峰 的 搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
网上流传最广的文章了，可真是基础教程，按这个做出来的网站是最简版的，没有样式，虽说是挺简单的，但是基本没法用啊。
最后有个[网址](https://github.com/mojombo/jekyll/wiki/Sites)很有用，有许多别人搭好的博客。因为Jekyll博客都是host在github上的开源的，所以可以clone别人的改一改就好啦。

#### 4.[写作环境搭建(git+github+markdown+jekyll)](https://site.douban.com/196781/widget/notes/12161495/note/264946576/)
里面也提供了一些不错的关于markdown的教程链接，我在折腾都是泪了以后就按这里面的方法做了一个，先安心写一些字再说吧，不折腾了，写博客顺手的工具和坚持的恒心缺一不可，更要的是敢写的勇气。

还有两个很有用的网址[GitHub Pages](https://pages.github.com/)&[Jekyllrb](https://jekyllrb.com/)。

好了，就先写这么多的吧，这两天折腾这个Jekyll真是弄得我心力憔悴，还有好多东西要学要写，以后再把这个教程给补齐吧。


PS：每个post最上面的定义部分，居然连一个空格缺了都会导致失败。

像这里：

> layout: post
> 
> title: 关于Jekyll的一些事情
> 
> categories: Program
> 
> tags: Jekyll