# 认识与入门 Markdown

> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 https://sspai.com/post/25137

> [Markdown](http://zh.wikipedia.org/wiki/Markdown) 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的 HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。

## 认识 Markdown

在刚才的导语里提到，Markdown 是一种用来写作的轻量级「标记语言」，它用简洁的语法代替排版，而不像一般我们用的字处理软件 Word 或 Pages 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。

目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如 [简书](http://jianshu.io)）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式，这种格式写出的简历更能得到 HR 的好感，甚至可以利用 [CloudApp](http://www.getcloudapp.com) 这种云服务工具直接上传至网页用来分享你的文章，全球最大的轻博客平台 Tumblr，也支持使用 Mou 这类 Markdown 工具进行编辑并直接上传。

### Markdown 官方文档

这里可以看到官方的 Markdown 语法规则文档，当然，后文我也会用自己的方式，阐述这些语法在实际使用中的用法。

*   [创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)
*   [Markdown 中文版语法说明](http://wowubuntu.com/markdown/#list)

### 使用 Markdown 的优点

*   专注你的文字内容而不是排版样式，安心写作。  
*   轻松的导出 HTML、PDF 和本身的 .md 文件。
*   纯文本内容，兼容所有的文本编辑器与字处理软件。
*   随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。
*   可读、直观、学习成本低。

### 使用 Markdown 的误区

> We believe that writing is about content, about what you want to say – not about fancy formatting.
> 
> 我们坚信写作写的是内容，所思所想，而不是花样格式。  
> — _Ulysses for Mac_

Markdown 旨在简洁、高效，也由于 Markdown 的易读易写，人们用不同的编程语言实现了多个版本的解析器和生成器。这就导致了目前不同的 Markdown 工具集成了不同的功能（基础功能大致相同），例如流程图与时序图，复杂表格与复杂公式的呈现。

虽然功能的丰富并没有什么本质的缺点，但终归有些背离初衷，何况在编写的过程中很费神，不如使用专业的工具撰写来的更有效率，所以如果你需实现复杂功能，专业的图形界面工具会更加方便。

当然，如果你对折腾这些不同客户端对 Markdown 的定制所带来高阶功能感到愉悦的话，那也是无可厚非的。

## 我该用什么工具？

### macOS 平台

在 macOS 上可以使用 [Mou](http://mouapp.com)，它支持实时预览，既左边是你编辑 Markdown 语言，右边会实时的生成预览效果，笔者文章就是 Mou 这款应用写出来的。

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69489.jpg)

其次还有很多同类选择。如果你是个编辑作者，我强烈建议你购买 [Ulysses](http://www.ulyssesapp.com)，这款应用入围了 Mac App Store 的 The Best of 2013，相比 Mou 它支持更多的写作格式、多文档的支持。Mou、iA Writer 这些应用都是基于单文档的管理方式，而 Ulysses 支持 Folder、Filter 的管理，一个 Folder 里面可以创建多个 Sheet，Sheet 之间还可以进行 Combine 处理。

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69490.jpg)

### Windows、iOS、Web 平台

*   笔者并未使用过 Windows 下的 Markdown 工具，但经朋友介绍，有两款还算不错，一款叫 [MarkdownPad](http://www.markdownpad.com) ，另一款叫 [MarkPad](http://code52.org/DownmarkerWPF/)。
*   iOS 端已有相当多的 app 支持 Markdown 语法编辑，例如 Drafts、Day One、iA Writer 等。
*   Web 端上，我强烈推荐 [简书](http://jianshu.io) 这款产品，上面有无数热爱文字的人在不停的创造、分享。在 Web 端使用 Markdown 没有比简书更舒服的地方了，它同样支持左右两栏的实时预览，字体优雅、简洁。

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69491.jpg)

*   同样是 Web 端，[Draftin](https://draftin.com) 这款在线 MD 编辑器也近乎完美。

## Markdown 语法的简要规则

### 标题

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69492.jpg)

标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 `#` 号即可。

`# 一级标题`

`## 二级标题`

`### 三级标题`

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

### 列表

熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 `-` 或 `*` 即可变为无序列表，有序列表则直接在文字前加 `1.``2.``3.` 符号要和文字之间加上一个字符的空格。

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69493.jpg)

### 引用

如果你需要引用一小段别处的句子，那么就要用引用的格式。

`> 例如这样`

只需要在文本前加入 `>` 这种尖括号（大于号）即可

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69494.jpg)

### 图片与链接

插入链接与插入图片的语法很像，区别在一个 `!`号

插入图片的地址需要图床，这里推荐 [CloudApp](http://www.getcloudapp.com) 的服务，生成 URL 地址即可。

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69495.jpg)

### 粗体与斜体

Markdown 的粗体和斜体也非常简单，用两个 `*` 包含一段文本就是粗体的语法，用一个 `*` 包含一段文本就是斜体的语法。

例如：**这里是粗体**_这里是斜体_

### 表格

表格是我觉得 Markdown 比较累人的地方，例子如下：

```
	| Tables        | Are           | Cool  |
	| ------------- |:-------------:| -----:|
	| col 3 is      | right-aligned | $1600 |
	| col 2 is      | centered      |   $12 |
	| zebra stripes | are neat      |    $1 |
```

这种语法生成的表格如下：

| Tables | Are | Cool |
| --- | :-: | --: |
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

### 代码框

如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown 下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来，如 `` `code` ``。图例：

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69496.jpg)

使用 `tab` 键即可缩进。

### 分割线

分割线的语法只需要另起一行，连续输入三个星号 `***` 即可。

### 小结

到这里，Markdown 的基本语法在日常的使用中基本就没什么大问题了，只要多加练习，配合好用的工具，写起东西来肯定会行云流水。更多的语法规则，其实 Mou 的 Help 文档例子很好，当你第一次使用 Mou 时，就会显示该文档，其次，你也可在撰写过程中，使用 `CMD+R` 快捷键来快速打开文档，以随时查阅和学习语法。

![](https://cdn.sspai.com/attachment/origin/2014/04/15/69497.jpg)

## 与 Markdown 相关的一些推荐

### 可配套使用的工具

*   [Droplr](http://droplr.com)
*   [Cloudapp](http://www.getcloudapp.com)
*   [ezShare for Mac](https://itunes.apple.com/cn/app/yi-xiang/id672522335?mt=12&uo=4)
*   [围脖图床修复计划](http://weibotuchuang.sinaapp.com)
*   [马克飞象，专为印象笔记打造的 Markdown 编辑器，非常推荐](http://maxiang.info)

### 相关文章阅读

*   [为什么作家应该用 Markdown 保存自己的文稿](http://apple4us.com/2012/02/why-writers-should-use-markdown.html)
*   [Markdown 写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)
*   [Markdown 工具补完](http://www.appinn.com/markdown-tools/)
*   [Drafts + Scriptogr.am + Dropbox 打造移动端 Markdown 风格博客](http://jianshu.io/p/63HYZ6)
*   [图灵社区 - 怎样使用 Markdown](http://www.ituring.com.cn/article/23)
*   [为什么我们要学习 Markdown 的三个理由](http://news.cnblogs.com/n/139649/)
*   [Markdown 语法写作入门指南 by ibuick](http://ibuick.me/?p=4093)
