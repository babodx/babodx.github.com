--- 
categories: ['Linux','Windows']
comments: true
layout: post
title: 批量部署系统方案
---
最近单位一直弄刀片服务器，7个笼子，112片。安装系统是个麻烦的事情，如果单机安装，太痛苦了。
所以就尝试了批量部署系统。
 
主要是分Linux和Windows两种方案

我这里Linux是CentOS。 采用了cobbler来做批量部署。

Windows采用的是win 2008的部署服务，就是WDS来做批量部署。

这样Linux做一台分发服务器，Windows做一台WDS服务器，需要部署那种系统就开那台服务器就可以了。

所有刀片全部采用pxe来引导就可以了。
 
具体方法就先不写了，以后再补上吧
 