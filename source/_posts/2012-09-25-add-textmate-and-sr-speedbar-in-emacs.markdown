---
layout: post
title: "在Emacs中增加sr-speedbar.el与textmate.el"
date: 2012-09-25 14:51
comments: true
categories: [emacs,rails]
---

博主最近在学习Rails,所以想把Emacs下的开发环境整合一下,感觉Rails下的开发与平时在Emacs下的开发习惯还是有些区别的,因为Rails大部分时间是在配置文件,然后生成代码,故需要在多个文件间经常来回切换.这次先加了sr-speedbar与textmate.

首先就是左侧加上文件目录:
以前用的speedbar没有固定位置的功能,因此google一下,得到宝物sr-speedbar:
[sr-speedbar]
然后在.emacs作如下配置:
{% gist 3780388 %}

其中的(kbd "s-s"),在Mac下就是Command + s的意思,博主在mac下的emacs是把左侧的command与option键互换了,command变成了option(也就是meta):
{% gist 3780429 %}

textmate.el就是引用了textmate的一些方法,具体可以参考这里[textmate.el],这里就不再赘述了.

[sr-speedbar]: https://github.com/emacsmirror/sr-speedbar/blob/master/sr-speedbar.el
[textmate.el]: https://github.com/defunkt/textmate.el
