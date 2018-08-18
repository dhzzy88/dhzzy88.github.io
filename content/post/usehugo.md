---
title: "Usehugo"
date: 2018-08-18T20:14:50+08:00
draft: true
---

## 关于使用hugo搭建本博客的相关步骤和所使用的工具

1. 使用了Github Pages作为博客的托管平台，在github上使用仓库可以很方便地更新博客，通过更新仓库就可以了，其实找资源也挺费劲的，文章的末尾有我使用的博客的地址，和相关的技术网站。你需要会使用git并且拥有自己的github账号，如果没有可以现在就去注册一个。[link to github](https://github.com/).


2. 其实除了使用hugo生成静态网页以外，你还可以使用github官方推荐的网页部署工具进行网站部署，给出链接[link to Github Pages](https://help.github.com/articles/what-is-github-pages/)这个链接是github官方帮助引擎里给出的使用文档，当然ｃｈｒｏｍｅ可以帮你翻译，点击右键。


3. <p>hugo是使用golang编程语言实现的一个静态网页生成工具，是github上的一个开源项目，最近很流行，除了在生成展示用的静态网页以及个人博客以外，你还可以使用hugo制作十分漂亮的各种低io的网站，上面有很多开源的主题，你可以选择自己喜欢的，frok或者git clone到你生成的ｈｕｇｏ网站项目的　"themes" 目录下。相关的配置和生成方法[在这里](http://www.gohugo.org/doc/) 这是hugo中文中文网站，上面大部分制作的过程都有中文版。</p>

4.  <pre><code>
      hugo new site website
      就创建了一个自己的网站，是不是超简单
      hugo new post/firstpage.md
      就可以在firstpage.md中写博客了，使用markdown语法，又快速，又方便，而且不用再次排版。
      </code></pre>


5. 你如果觉得这太博客仍然太丑了，你可以去上方的中文网站了解怎么制作自己的主题，更炫酷的东西也可以制作出来。有点费劲，一天做不出来。一个礼拜也不行，怎么也得个把月吧

6. 坑，坑，坑
>1. 关于部署过程的一些坑，一定要把config.toml中的相关文件目录指定相对路径。不然部署以后很干，ｃｓｓ全都不见了.
>2. 生成写完博客务必要使用hugo -D或者把博文文件开头的drag:true删除
>3. hugo server  -w或者--watch 可以本机查看网站预览
>4. hugo new \*\*\*.md  生成的文件在ｃｏｎｔｅｎｔ目录下面

7. 下面是对构建博客中使用的相关资源整理，十分感谢这些分享的博主。

>1  [来自简书的：FrankWang0909](https://www.jianshu.com/p/7426c16880f6)

>2  [hugo网站中文](http://www.gohugo.org/doc/)

>3  [Markdown语法中文文档](https://www.appinn.com/markdown/)

>3  [传送门直达hugo快速开始](https://gohugo.io/getting-started/quick-start/)

>4 [hugo的github主页，也是下载链接处](https://github.com/gohugoio/hugo/releases)

>5 [本博客的源码地址](https://github.com/dhzzy88/dhzzy88.github.io)
