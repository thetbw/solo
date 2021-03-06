# <img src="https://cloud.githubusercontent.com/assets/873584/26024695/4defcb5e-3809-11e7-9755-fa4d22c45718.png"> [Solo](https://github.com/b3log/solo) [![Build Status](https://img.shields.io/travis/b3log/solo.svg?style=flat)](https://travis-ci.org/b3log/solo) [![Coverage Status](https://img.shields.io/coveralls/b3log/solo.svg?style=flat)](https://coveralls.io/github/b3log/solo?branch=master)  [![AGPLv3](http://img.shields.io/badge/license-AGPLv3-orange.svg?style=flat)](https://www.gnu.org/licenses/agpl-3.0.txt)

## 简介

[Solo](https://github.com/b3log/solo) 是**一个命令**就能搭建好的 Java 开源博客系统，并内置了 18+ 套精心制作的皮肤。除此之外，Solo 还有着非常活跃的[社区](https://hacpai.com)，文章分享到社区后可以让很多人看到，产生丰富的交流互动。

## 案例

* [D 的个人博客](https://88250.b3log.org)
* [Jiahao.Zhang's Blog](https://blog.hduzplus.xyz)
* [子兮子兮](https://zixizixi.cn)
* [铅笔的个人博客](https://pencilso.cn)
* [洗澡狂魔的技术阵地](https://blog.washmoretech.com)
* [liumapp 的个人博客](http://www.liumapp.com)
* [水星的随笔](https://note.abeffect.com)
* [1992 社区](https://1992.cool)
* [何遇](http://littleq.cn)
* [Relyn](http://relyn.cn)
* [思干豆](http://sigandou.com)
* [DevHyxo](https://blog.devhyxo.top)

## 功能 

* Markdown / Emoji
* [聚合分类](https://github.com/b3log/solo/issues/12256) / 标签
* 自定义导航（页面、链接）
* 草稿夹
* 评论 / 回复邮件提醒
* 随机文章 / 相关文章 / 置顶 / 更新提醒
* 自定义文章永久链接
* 自定义站点 SEO 参数
* 自定义公告 / 页脚
* 多个签名档
* 代码高亮 / 数学公式 / 流程图
* [多皮肤，多端适配](https://github.com/b3log/solo-skins/tree/master/skin-preview) / [社区皮肤](https://github.com/b3log/solo-third-skins/tree/master/skin-preview)
* 多语言 / 国际化
* 上传本地 / 七牛云 / 阿里云 OSS
* 友情链接管理
* 多用户写作，团队博客
* [Hexo/Jekyll 导入](https://hacpai.com/article/1498490209748)
* SQL / JSON / Markdown 导出
* 插件系统
* Atom / RSS / Sitemap
* MetaWeblog API
* CDN 静态资源分离
* [GitHub 集成](https://github.com/b3log/solo/issues/12514)

## 界面

### 初始化

![init](https://user-images.githubusercontent.com/873584/52255268-d5a31980-294c-11e9-9d16-708b9748ebe7.png)

### 后台首页

![console-index](https://user-images.githubusercontent.com/873584/52255442-85788700-294d-11e9-8c8e-38bdcba6736c.png)

### 编辑文章

![article](https://user-images.githubusercontent.com/873584/52255441-85788700-294d-11e9-8fb4-f72e353a76de.png)

### 选择皮肤

![skin](https://user-images.githubusercontent.com/873584/52255444-85788700-294d-11e9-9c21-8758bad2c3b4.png)

### 前台界面

![index](https://user-images.githubusercontent.com/873584/52255333-19961e80-294d-11e9-85c4-92bc508864a4.png)

## 安装

[下载](https://github.com/b3log/solo/releases)最新的 Solo 包解压，进入解压目录执行：

* Windows: `java -cp "WEB-INF/lib/*;WEB-INF/classes" org.b3log.solo.Starter`
* Unix-like: `java -cp "WEB-INF/lib/*:WEB-INF/classes" org.b3log.solo.Starter`

用 `Docker` 运行？

`docker volume create solo_datas && docker run --privileged --name solo --restart=unless-stopped -p 8080:8080 -v solo_datas:/opt/b3log/backup/ -d 88250/solo`

**如果你不想自己维护服务器，可以购买我们运维的 Solo 直接使用，细节请联系 QQ845765。**

## 文档

* [《提问的智慧》精读注解版](https://hacpai.com/article/1536377163156)
* [用户指南](https://hacpai.com/article/1492881378588)
* [Solo 从设计到实现](https://hacpai.com/article/1537690756242)
* [贡献指南](https://github.com/b3log/solo/blob/master/CONTRIBUTING.md)
* [皮肤开发](https://hacpai.com/article/1493814851007)
* [插件开发](https://docs.google.com/document/pub?id=15H7Q3EBo-44v61Xp_epiYY7vK_gPJLkQaT7T1gkE64w&pli=1)

## 社区

* [讨论区](https://hacpai.com/tag/solo)
* [报告问题](https://github.com/b3log/solo/issues/new/choose)

## 授权

Solo 使用 [GNU Affero General Public License, Version 3](https://www.gnu.org/licenses/agpl-3.0.txt) 开源协议。

## 鸣谢

* [jQuery](https://github.com/jquery/jquery)：前端 JavaScript 工具库
* [Highlight.js](https://github.com/isagalaev/highlight.js)：前端代码高亮库
* [pjax](https://github.com/defunkt/jquery-pjax)：pushState + ajax = pjax
* [jsoup](https://github.com/jhy/jsoup)：Java HTML 解析器
* [flexmark](https://github.com/vsch/flexmark-java)：Java Markdown 处理库
* [Apache Commons](http://commons.apache.org)：Java 工具库集
* [Latke](https://github.com/b3log/latke)：一款以 JSON 为主的 Java Web 框架
* [Vditor](https://github.com/b3log/vditor)： 一款浏览器端的 Markdown 编辑器，使用 TypeScript 实现

----

<p align = "center">
<strong>小而美博客系统</strong>
<br><br>
<img src="https://cloud.githubusercontent.com/assets/873584/26024667/c031e40a-3808-11e7-9176-f2c9af01bd64.png">
</p>

