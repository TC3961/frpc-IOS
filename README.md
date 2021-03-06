# 项目介绍

frp 源项目 [https://github.com/fatedier/frp](https://github.com/fatedier/frp)

frp 帮助网站 [https://www.frp.fun/](https://www.frp.fun/)

QQ交流群 [222670265](https://jq.qq.com/?_wv=1027&k=5kkmkwa)

## 开发说明

* xcode ≥ 9.x
* go ≥ 1.10.x
* [编译动态库](https://github.com/FrpcCluster/frpc-IOS/blob/master/Compile_zh.md)

## 项目 demo 大概简要图

<img src="https://github.com/TelDragon/Dragon/blob/master/image/frp-Android-02.png" width="266" alt="frp-Android-02.png">   <img src="https://github.com/TelDragon/Dragon/blob/master/image/frp-Android-03.png" width="266" alt="frp-Android-03.png">   <img src="https://github.com/TelDragon/Dragon/blob/master/image/frp-Android-04.png" width="266" alt="frp-Android-04.png">

## 项目逻辑

* 启动初始化，写入预连接的服务器地址，服务器端口号，服务器toke
* 添加隧道
  * tcp协议，加密/压缩为非必选项，其他必填项
  * udp协议，加密/压缩为非必选项，其他必填项
  * http协议，加密/压缩为非必选项，自定义域名/泛域名二选一必填项
  * https协议，加密/压缩为非必选项，自定义域名/泛域名二选一必填项
* 隧道列表，可以复制分享列表内容

## 支持情况

* 支持
  * 手机免越狱
  * 自定义添加服务器
  * 协议tcp、udp、http、https
  * 加密、压缩
  * 动态添加隧道、删除隧道 (热加载)
  * 自定义域名、泛域名
  * 分享隧道信息
  * 后台运行
  * 支持frps 0.13.0/0.15.0/0.16.0/0.17.0/0.18.0/0.21.0
* 不支持
  * 保存配置文件(退出软件app后重新进入需再次填写信息)

  
 ## 开发计划
 
* 支持多frps服务器版本 0.13.0/0.15.0/0.16.0/0.17.0/0.18.0/0.21.0
* 支持Android 安卓app [https://github.com/TelDragon/frpc-Android](https://github.com/TelDragon/frpc-Android)
* 用户平台登录
* 获取用户位置信息收录统计
* 获取frps服务器列表信息，提供用户服务器选择匹配
* 保存配置信息
* 抛弃frpc.ini 启动文件，直接使用“execute”函数执行命令
  
## 为 frpc-IOS 做贡献

frpc-IOS 是一个免费且开源的项目，我们欢迎任何人为其开发和进步贡献力量。

* 在使用过程中出现任何问题，可以通过 [issues](https://github.com/FrpcCluster/frpc-IOS/issues) 来反馈。
* Bug 的修复可以直接提交 Pull Request 到 dev 分支。
* 如果是增加新的功能特性，请先创建一个 issue 并做简单描述以及大致的实现方法，提议被采纳后，就可以创建一个实现新特性的 Pull Request。
* 欢迎对说明文档做出改善，帮助更多的人使用 frp，特别是英文文档。
* 贡献代码请提交 PR 至 dev 分支，master 分支仅用于发布稳定可用版本。
* 如果你有任何其他方面的问题，欢迎反馈至 542867428@qq.com 共同交流。

**提醒：和项目相关的问题最好在 [issues](https://github.com/FrpcCluster/frpc-IOS/issues) 中反馈，这样方便其他有类似问题的人可以快速查找解决方法，并且也避免了我们重复回答一些问题。**

## 捐助

* 如果您觉得[frpc-IOS](https://github.com/FrpcCluster/frpc-IOS)对你有帮助，欢迎给予我们一定的捐助来维持项目的长期发展。

<img src="https://github.com/TelDragon/Dragon/blob/master/image/WeChat.png" width="266" alt="frp-Android-02.png"> <img src="https://github.com/TelDragon/Dragon/blob/master/image/Alipay.png" width="266" alt="frp-Android-02.png">
 
