# :hearts: Jike Extension

帮你在「网页版即刻」获得更好体验的插件。

**[在 Chrome Store 下载](https://chrome.google.com/webstore/detail/love-jike-extension/pnglcgpgmedjmknpknjedmkggedgdlpk)**

![example](https://github.com/Unknow-Y/tojike-chrome-extension/blob/master/dist/example-v2.0.9.gif)

## 功能简介

[即刻App](https://okjike.com/)是一个很棒的资讯+社交平台，在这里可以追踪你想知道的信息，也能遇到有趣的即友。

现在即刻有了网页版，本插件解决的是网页版目前还没有官方支持的需求，期待即刻越来越好。

**功能列表**
- ~「即刻分享页」到「网页版即刻」的传送门（已官方支持）[v1.0文档](https://github.com/Unknow-Y/tojike-chrome-extension/blob/master/his/README-v1.0.md)~
- 在网页版查看通知详情，支持的通知类型如下：
  - [x] 评论和回复
  - [x] 关注
  - [x] 点赞
  - [x] 回答

## 下载地址

版本 | 更新进度 | 下载
----|----|----
Chrome Extension 版本 | 2.1.2 | [到 Chrome Store 下载](https://chrome.google.com/webstore/detail/love-jike-extension/pnglcgpgmedjmknpknjedmkggedgdlpk)
UserScript 版本 | 2.0.1 | [在 OpenUserJS 下载](https://openuserjs.org/scripts/soyaine/Love_Jike)
crx 版本 | 2.1.2 | 可以在[ crx 文件夹](https://github.com/Unknow-Y/tojike-chrome-extension/tree/master/crx) 找到

### Chrome Extension 版本
[到 Chrome Store 下载](https://chrome.google.com/webstore/detail/love-jike-extension/pnglcgpgmedjmknpknjedmkggedgdlpk)

### UserScript 版本
如果你使用的是其它浏览器，可以下载使用[ Love Jike 的 UserScript 版本](https://openuserjs.org/scripts/soyaine/Love_Jike)。

以 Firefox 为例：
1. 安装 [Greasemonkey](https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/)
2. 在 [Love Jike Userscript](https://openuserjs.org/scripts/soyaine/Love_Jike/) 页面点击 Install 安装脚本

### CRX 版本
如果你不能访问 Chrome Web Store，可以下载最新版的 .crx 文件进行安装：
1. 在[ crx 文件夹](https://github.com/Unknow-Y/tojike-chrome-extension/tree/master/crx)下载版本号最大的文件
2. 打开 Chrome 后在地址栏输入 `chrome://extensions`
3. 把 .crx 文件拖入

## 更新日志
#### v2.1.2
2019-05-27
- 当没有新通知时，保持通知栏关闭
- 修复因为 Chrome 安全限制导致的跨域请求问题

#### v2.1.1
2018-10-11
- 支持关闭通知区域

#### v2.0.13
2018-08-20
- 修复官方接口字段变动引起的 bug

#### v2.0.12
2018.08.11
- 修复某些类型通知的原消息链接拼接问题

#### v2.0.11
2018.08.10
- 增加支持对在官方消息下评论的点赞通知

#### v2.0.10
2018.08.07
- 新增对于问答类动态的回答和点赞通知
- 清理了之前的坏代码

#### v2.0.9
2018.07.20
- 新增了点赞类型的通知
- 优化了不同类型通知的处理逻辑和原动态链接的生成逻辑
- 修复了点击通知按钮无法获取新通知的 bug
- 修复非中文系统下的通知日期显示问题

#### v2.0.8
2018.07.06
- 修复了获取不到通知的问题（因为 header 版本号过低）
- 根据 API 结构更新了一些内容，包括转发、评论消息的链接修复
- 这次即刻好像统一了很多 ID，很棒

#### v2.0.7
2018.07.04
- 修复 ruguoapp.com 域名的匹配问题

#### v2.0.6
2018.06.13
- 增加转发动态的通知详情
- 修改了一些文案细节
- 修复有时因顶部状态栏未加载出来而导致的通知无法显示问题
- 修复个人动态下评论的跳转链接

#### v2.0.4
2018.06.04
- 增加对两个 http 即刻域名的支持
- fix 跳转链接至 https

#### v2.0.3
2018.06.03
- 支持点击插件图标打开网页版即刻
- 新增被关注的通知显示

#### v2.0.1
2018.03.30
- 在网页版可以看到通知，包括三种评论类型
- 由于官方支持了分享页的直接跳转，所以去掉了此功能

#### v1.2
2018.03.13
- 修复了 Firefox 中无法识别按钮的问题
- 在个别页面不显示 To Web 按钮，包括即刻小报和热门
- 发布了 Userscript 版本

#### v1.1
2018.03.09
- 首版发布到 Chrome Web Store 了！实现了核心功能啦！

## 关于作者
本插件的开发者是朵爷，常说的一句话是“朵爷又日常爱即刻了”，即刻ID是[未枝丫](http://web.okjike.com/user/soyaine)，如果有问题欢迎反馈交流。  

如果你想赞赏支持一下用于支付 Chrome Web Store 开发者账号的费用，请用微信扫这里并留言附上你的名字：
<img src="https://github.com/Unknow-Y/tojike-chrome-extension/blob/master/dist/donate.jpeg" width="480">

## Contributors
制作这个插件的过程中，即友们提供了很多帮助。
- 插件 icon by Ⓙ花鸟酱
- 使用示意动图 by Ⓙ段子宇
- 可爱的全图AI们提供了「微即分」这个名字，并且很有耐心地帮忙测试以及提需求❤️
