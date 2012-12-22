---
layout: post
title: "在Chrome下指定域名加上https"
date: 2012-10-29 01:26
comments: true
categories: ['Chrome']
---

众所周知的原因,国内用Google搜索出来的结果,点击后经常无法跳转.有一个办法便是把所有的google地址默认全加上https.设定的办法是在Chrome地址输入chrome://net-internals/#hsts,然后在Add Domain中依次添加www.google.com,www.google.com.hk,并在Include subdomains打勾.大功告成!

