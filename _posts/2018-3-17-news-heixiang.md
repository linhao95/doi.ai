---
layout:     post
title:      一个优雅的开源学术论文书写工具
subtitle:   ""
date:       2018-03-17
author:     " "
header-img: "img/home-bg-o.jpg"
tags:
    - 新闻
---

本文主要内容：近日，Substance 在 GitHub 上开源了一个用于结构文本的文字处理工具 Texture，他们表示该工具像 LaTeX 一样可以开放使用，且如经典的文字处理工具那样简单。机器之心使用后发现，该工具可以非常流畅与简单地编写学术论文，我们可以添加作者、正文或参考文献等结构化的模块而快速完成文章。





<!-- more -->

## 主要内容

项目地址：https://github.com/substance/texture

用于处理结构化文本的文字处理工具 Texture：

![images](/images\news\2018-3-16-Texture.jpg)

Texture 是一个用于生产科学论文或内容的工具，它使用 Dar 格式，因此也严格定义了 JATS Archiving 和 Interchange Tag Set（「green」v.1.1）XML 格式。读者可以查看以下在线演示或直接下载桌面版 APP。

[在线演示](http://cdn.substance.io/texture-preview-1/)

[桌面版 APP](https://github.com/substance/texture/releases/tag/v1.0.0-preview.1)

Texture 的开发项目早在 2015 年就已经启动，2016 年发布了两个预览版，并在 2017 年持续完善。今年三月，Substance 发布了 Texture 的最终测试版 Texture 1.0.0 Preview 1。该项目首先会满足研究社区的论文书写需求，因此也会有明确的讨论和补充渠道。

其实 Texture 就是为了解决撰写学术论文成本过高的问题。因为不论我们选择 Word 那样的传统文字处理工具还是使用 LaTeX 那样的标记语言，完成学术论文都有很大的局限性。Word 非常容易使用，但只提供非结构化的内容，而 LaTeX 能提供很多结构，却需要我们学习一门新的标记语言。这两种方式最后都需要转化为结构化的 JATS-XML 格式，才能继续提交到出版物。因此 Texture 希望结合 Word 易于使用的特点和 LaTeX 结构化内容的属性，而大大减少完成学术论文所需要的成本。

在机器之心的试用中，论文的不同结构模块可以使用对应的对话框添加，如下是添加预印本论文参考文献的界面：

![images](/images\news\2018-3-16-Texture-1.jpg)

因此，Texture 允许将原始内容以交互的方式转化为结构化内容，并添加语义信息以满足出版物的要求。最后，Texture 目前还有一些功能模块没有完成，我们也没有找到 Mathjax 等数学模块。在 GitHub 中，Substance 展示了 Texture 所有的特征与功能，我们也非常期望该工具完成后能给学术写作带来真正意义上的飞跃。

![images](/images\news\2018-3-16-Texture-1.jpg)

[文章未完，点击这里查看全文（来自机器之心）](http://mp.weixin.qq.com/s/6S2HCDSx9ePwycHcve1Hlw)