---
layout: post
title: 使用Zotero管理文献
date: 2023-09-18 10:14:00-0400
description: 介绍Zotero
tags: 工具 分享
categories: 知识分享
giscus_comments: true
related_posts: false
toc:
  sidebar: left
---

# 什么是Zotero？

Zotero 是一款免费的、开源的研究工具，帮助你收集、整理和分析你的研究。它是由 Corporation for Digital Scholarship 开发的，这是一个专门从事软件和服务开发的非盈利性组织，旨在为研究人员和文化遗产机构提供服务。

由于完全免费且支持许多插件，Zotero能够支持许多功能，提供从下载、阅读到笔记的一站式文献管理体验。例如，Zotero可以结合浏览器插件抓取文献并保存到相应的资料库里；你可以对文献按标签或文件夹分类以方便管理，并在阅读文献时使用便捷的翻译服务。此外，你还可以使用WebDav功能，把所有文献都储存到云空间中，方便在多个设备上阅读和管理文献。

这篇文章将帮助你从0开始上手Zotero，并安装几个常用的插件。

# 一、下载Zotero

Zotero提供Windows、MacOS、Linux以及iOS系统的软件，下载地址如下：

[[Zotero | Your personal research assistant](https://www.zotero.org/)](https://www.zotero.org/)

除了Zotero本体外，还需要下载一个浏览器插件Zotero Connector。以微软Edge浏览器为例，可以在官方插件商城搜索下载。
<img width="329" alt="image" src="https://github.com/socrateslab/KnowledgeSpace/assets/62193117/07074a79-1824-4fb2-8506-4f23fe66d69b">

# 二、注册账号并与浏览器插件链接
下载完Zotero本体与浏览器插件后，需要注册一个账号。首次点击Zotero Connector插件会自动导向注册页面，完成注册后，在Zotero本体“首选项”中登入账号。
<img width="689" alt="image" src="https://github.com/socrateslab/KnowledgeSpace/assets/62193117/c51093ac-21b7-461e-9110-d9ec6231917d">
你可以尝试随便打开一个网页并单击Zotero Connector插件按钮，如果能够在Zotero本体中看到相应的网页快照，则完成了二者的绑定。需要注意的是，使用浏览器插件保存文献时，Zotero本体需要处于开启状态。

# 三、配置WebDev云存储
由于Zotero自带的云存储空间只有300MB容量，后续可能会超容，因此推荐使用坚果云等第三方云存储服务。坚果云为免费用户提供 20GB 的存储空间，以及每月 1GB 的上传流量和 3GB 的下载流量，对于文献阅读而言完全足够。
首先，注册并登入坚果云：https://www.jianguoyun.com/
其次，进入个人设置中的安全选项，添加应用（可以命名为zotero）并生成密码。
<img width="1278" alt="image" src="https://github.com/socrateslab/KnowledgeSpace/assets/62193117/c01d4270-874d-45d2-a26c-88cc0948cfce">
最后，打开Zotero客户端的“首选项”，将文件同步选项更改为WebDav，并将你的坚果云账号和刚才生成的密码填写完整。
<img width="642" alt="image" src="https://github.com/socrateslab/KnowledgeSpace/assets/62193117/2bb320b1-add9-410d-b8a0-cb912e45dd85">

# 四、安装一些非常好用的插件
你可以在Zotero中文小组下载喜欢的插件：https://zotero-chinese.github.io/zotero-plugins/#/
下载相应版本的插件后，在Zotero的Add-on选项中导入插件即可安装。
## 文献翻译
https://github.com/windingwind/zotero-pdf-translate
该插件可以实现划词翻译并一键生成翻译笔记。
<img width="814" alt="image" src="https://github.com/socrateslab/KnowledgeSpace/assets/62193117/e62238a3-3f4a-49f7-8065-e03612996c34">
## 文献下载
https://github.com/ethanwillis/zotero-scihub
该插件可以自动根据文献的doi在Scihub中下载，方便在没有校园IP的情况下抓取部分文献

https://github.com/l0o0/jasminum
该插件可以实现知网元数据识别，对于中文文献比较必要

https://github.com/MuiseDestiny/zotero-file
该插件能够将下载的文献自动根据元数据重命名，方便管理本地pdf文件

## 文献阅读
https://github.com/windingwind/zotero-better-notes
该插件能够在Zotero中更加方便管理笔记，比如将多个文献的笔记生成双链笔记，方便文献综述的整理

https://github.com/MuiseDestiny/zotero-figure
该插件能够自动提取pdf中的图表并放在左侧的目录中，方便在阅读文献的过程中打开小窗（该功能需要下载上面的better notes插件）查阅图表。
<img width="1512" alt="image" src="https://github.com/socrateslab/KnowledgeSpace/assets/62193117/9c334c54-5ad1-45d6-9670-29995767983d">

还有一些其他的插件，例如Zotero-GPT（在文献阅读时调用ChatGPT）等等，可以自行探索。
