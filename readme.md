微信支付/开放平台/公众号/企业微信/小程序的Java开发工具包（SDK）
---------------------------------
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.binarywang/weixin-java-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.binarywang/weixin-java-parent)
[![Build Status](https://travis-ci.org/Wechat-Group/weixin-java-tools.svg?branch=develop)](https://travis-ci.org/Wechat-Group/weixin-java-tools)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![GitHub stars](https://img.shields.io/github/stars/badges/shields.svg?style=social&label=Stars)](https://github.com/Wechat-Group/weixin-java-tools)
[![使用IntelliJ IDEA开发维护](https://img.shields.io/badge/IntelliJ%20IDEA-提供支持-blue.svg)](https://www.jetbrains.com/idea/)


#### 声明： ***本项目Fork自chanjarster/weixin-java-tools，但由于原项目已停止维护，故单独维护和发布，且发布到maven上的groupId也会不同，详细信息见下文。***

#### [出现`Illegal key size`问题的解决办法](https://github.com/Wechat-Group/weixin-java-tools/wiki/%E5%8A%A0%E8%A7%A3%E5%AF%86%E7%9A%84%E5%BC%82%E5%B8%B8%E5%A4%84%E7%90%86%E5%8A%9E%E6%B3%95) （太多人遇到此问题而不知所措，因此特意置顶，希望能引起新手的注意）

***新人提示：本项目仅是一个开发工具包（即SDK），未提供Web实现，建议使用maven或gradle引用本项目即可使用本SDK提供的各种功能，详情可参考下文中提到的Demo项目或本项目中的部分单元测试代码；另外微信开发新手请务必阅读[Wiki首页](https://github.com/Wechat-Group/weixin-java-tools/wiki)的常见问题部分，可以少走很多弯路，节省不少时间。***

## Demo项目列表
1. [微信支付Demo](http://gitee.com/binary/weixin-java-pay-demo)
1. [企业号/企业微信Demo](http://gitee.com/binary/weixin-java-cp-demo)
1. [微信小程序Demo](http://gitee.com/binary/weixin-java-miniapp-demo)
1. [开放平台Demo](http://gitee.com/binary/weixin-java-open-demo)
1. 公众号Demo：
	- [使用Spring MVC实现的公众号Demo](http://gitee.com/binary/weixin-java-mp-demo)
	- [使用Spring Boot实现的公众号Demo](http://gitee.com/binary/weixin-java-mp-demo-springboot)
	- [含公众号和部分微信支付代码的Demo](http://gitee.com/binary/weixin-java-tools-springmvc)

---------------------------------
### 重要提示信息（部分为新手必读）：
1. 最新更新：**2017-12-01 发布[【2.9.0正式版】](https://github.com/Wechat-Group/weixin-java-tools/releases)**！
1. [开源中国本项目的首页地址](https://www.oschina.net/p/weixin-java-tools-new)，欢迎大家积极留言评分 🙂
1. 阅读源码的同学请注意，本SDK为简化代码编译时加入了lombok支持，如果不了解lombok的话，请先学习下相关知识；
1. SDK详细开发文档请查阅 [【Wiki】](https://github.com/wechat-group/weixin-java-tools/wiki)，部分文档可能未能及时更新，如有发现，可以及时上报或者自行修改。
1. 各个模块的Javadoc可以在线查看：[weixin-java-miniapp](https://binarywang.github.io/weixin-java-miniapp-javadoc/)、[weixin-java-pay](https://binarywang.github.io/weixin-java-pay-javadoc/)、[weixin-java-mp](https://binarywang.github.io/weixin-java-mp-javadoc/)、[weixin-java-common](https://binarywang.github.io/weixin-java-common-javadoc/)、[weixin-java-cp](https://binarywang.github.io/weixin-java-cp-javadoc/)、[weixin-java-open](https://binarywang.github.io/weixin-java-open-javadoc/)
1. 本SDK要求的最低JDK版本是1.7，还在使用JDK6的用户请参考[【此项目】]( https://github.com/binarywang/weixin-java-tools-for-jdk6) ，而其他更早的JDK版本则需要自己改造实现。
1. 如有新功能需求，发现BUG，或者由于微信官方接口调整导致的代码问题，可以直接在[【Issues】](https://github.com/Wechat-Group/weixin-java-tools/issues)页提出issue，便于讨论追踪问题；
1. 如果想贡献代码，请阅读[【代码贡献指南】](contribution.md)；
1. **捐助渠道已开通，如有意向请点击[【支付宝二维码】](alipay_qrcode.jpg)捐赠，或者直接前往[【托管于码云的项目首页】](http://gitee.com/binary/weixin-java-tools)，在评论区上方可以找到“捐助”按钮。非常感谢各位捐助的同学！**

---------------------------------
## 使用交流方式说明：
1. QQ群： [![加入QQ群](https://img.shields.io/badge/QQ群-343954419-blue.svg)](http://shang.qq.com/wpa/qunwpa?idkey=731dc3e7ea31ebe25376cc1a791445468612c63fd0e9e05399b088ec81fd9e15) 或 [![加入QQ群](https://img.shields.io/badge/QQ群-343954419-blue.svg)](http://jq.qq.com/?_wv=1027&k=40lRskK)，推荐点击按钮入群，当然如果无法成功操作，请自行搜索群号343954419进行添加 ）
1. 由于群容量有限，即将爆满，故开启付费入群模式以保证只有真实交流需求的人进入，如果确实因为各种原因无法付费入群的，请联系群主说明原因即可入群；并为保证群的活跃度，本群将不定期清理长时间不活跃的同学；
1. 微信群： 因微信群已达到100人限制，故如有想加入微信群的，请入QQ群后联系管理员，提供微信号以便邀请加入；
1. 新手提问前，请先阅读此[【文章】](http://www.dianbo.org/9238/stone/tiwendezhihui.htm)；
1. 寻求帮助时需贴代码或大长串异常信息的，请利用http://paste.ubuntu.com

---------------------------------
## 版本说明
1. 本项目定为大约每两个月发布一次正式版，版本号格式为X.X.0（如2.1.0，2.2.0等），遇到重大问题需修复会及时提交新版本，欢迎大家随时提交Pull Request；
1. BUG修复和新特性一般会先发布成小版本作为临时测试版本（如2.4.5.BETA，2.4.6.BETA等，即尾号不为0，并添加BETA字样，以区别于正式版）；
1. 目前最新版本号为 [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.binarywang/weixin-java-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.binarywang/weixin-java-parent) ，也可以通过访问链接 [【微信支付】](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.github.binarywang%22%20AND%20a%3A%22weixin-java-pay%22) 、[【微信小程序】](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.github.binarywang%22%20AND%20a%3A%22weixin-java-miniapp%22) 、[【公众号】](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.github.binarywang%22%20AND%20a%3A%22weixin-java-mp%22) 、[【企业微信】](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.github.binarywang%22%20AND%20a%3A%22weixin-java-cp%22)、[【开放平台】](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.github.binarywang%22%20AND%20a%3A%22weixin-java-open%22)
分别查看所有最新的版本。 

---------------------------------
#### 本项目在以下代码托管网站同步更新:
* 码云：https://gitee.com/binary/weixin-java-tools
* GitHub：https://github.com/wechat-group/weixin-java-tools

---------------------------------
## Maven 引用
```xml
<dependency>
  <groupId>com.github.binarywang</groupId>
  <artifactId>（不同模块参考下文）</artifactId>
  <version>2.9.0</version>
</dependency>
```
* 各模块的`artifactId`：
  - 微信小程序：`weixin-java-miniapp`   
  - 微信支付：`weixin-java-pay`
  - 微信开放平台：`weixin-java-open`   
  - 公众号：`weixin-java-mp`    
  - 企业号/企业微信：`weixin-java-cp`
