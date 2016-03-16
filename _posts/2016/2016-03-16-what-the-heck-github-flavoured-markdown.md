---
layout: post
title: 到底什么是Github Flavored Markdown？
categories: Trivia
tags: github markdown
---

> 神马？连一个Markdown都要分出来平台标准吗?

真是让人绝望，刚开始写Jekyll+Github的博客，就有一大堆问题，先是费了番功夫找windows下堪用的Markdown（以下简称md）编辑器，现在在用的这个MarkdownPad 2 Pro还算不错，你若问这个Pro版是怎么搞的，嘿嘿自己google去。md的格式看来Github还有自己的特殊偏好，比如说##然后一定要空格一下才会被当作是标题；回车一次当空格，两次才是分段。

**然后就是我维护的媒体网站一连崩溃两次啊！！！**

我就得忙不迭地去重启系统，唉，以后还得好好查查到底是哪造成的崩溃。

回来主题，到底什么是Github Flavored Markdown，原来Github里经常会用到md，于是就做了一些语法修改，会更方便吧，熟悉一下就不会出现本地和远程的文件显示不一致啦。

## 一

[文章链接](http://www.jianshu.com/p/cfPxyr)  写的比较乱七八糟，有几点写到的：

#### 自动URL链接

如果直接写URL link，那么会自动生成URL，文字即链接本身： https://github.com

#### 代码高亮
- 首尾都用```（三个键盘左上角的符号）

```
//this is code
console.log("Hello World");		
```

- 首用```JavaScript，可以指定语言高亮

```JavaScript
//this is code
console.log("Hello World");		
```

- 内嵌代码段用\<code>\</code>或者\`\`\`封住，会变成这样<code>console.log("HelloWorld");</code> ```code```

比起那些用四个空格来表示代码段的蛋疼方式，这些确实好多了

#### 任务列表

用<code>- [ ]</code> 表示，注意中间都是空格，空格不对的话是显示不出来的哦，效果如下：
- [ ] Task1
- [ ] Task2


## 二

[好书推荐](http://xianbai.me/learn-md/index.html)，介绍的详细而具体，可以好好读读



居然和本地效果又不一样！！！