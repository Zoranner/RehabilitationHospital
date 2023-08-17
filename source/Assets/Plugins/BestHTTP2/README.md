# Best HTTP2

如果你想要一个可以通过 **HTTP/2** 支持 **REST、WebSocket、Socket.IO、SignalR、SignalR Core、Server-Sent Events**（以及更多）的自定义请求并且具有开发者定期更新和出色支持功能的现成插件，那么 BestHTTP/2 就是你需要的！

您可以在其自己的[演示页面](https://besthttpdemosite.azurewebsites.net/)上试用该资源包，并阅读在线[文档](https://besthttp-documentation.readthedocs.io/en/latest/)。

**内含所有源代码！**

[支持的平台](https://besthttp-documentation.readthedocs.io/en/latest/#platforms/)：

- WebGL
- iOS、Android
- UWP、Windows、Mac OS X、Linux

最值得注意的功能是：

- [HTTP/2](https://besthttp-documentation.readthedocs.io/en/latest/#7.GlobalTopics/HTTP2/)
- [自定义您的请求的所有部分](https://besthttp-documentation.readthedocs.io/en/latest/#1.HTTPRequest/GettingStarted/)：
  - 方法（GET、HEAD、POST、PUT、DELETE、PATCH）
  - 标头
  - Cookie
  - 最大重定向计数
  - 超时
- 访问服务器发送的每个比特位：
  - 标头
  - 状态代码
  - Cookie
  - 原始内容
  - 尾部标头
- **连接**和**内存**池
- 连接和请求**超时**
- 自动 **Cookie** 处理
- 支持众多**代理**（Fiddler、Charles 等）
- 支持 HTTP 和 Socks 代理
- 自动**缓存**和缓存验证
- 设置缓存大小和新鲜度
- **gzip** 内容编码
- 基本和摘要式身份验证
- 多种格式类型（**URL 编码**和**多部分/格式数据**）
- 自动**重定向**处理
- **上传和下载进度跟踪**
- 下载时访问您的数据
- 您可以使用 Range 标头**恢复**下载
- **HTTPS**
- 自定义各种[全局设置](https://besthttp-documentation.readthedocs.io/en/latest/#7.GlobalTopics/GlobalSettings/)：
  - 每个服务器的最大连接数
  - 启用/禁用Cookie
  - 隐私浏览模式
  - Cookie Jar 大小
  - 等等

[WebSocket](https://besthttp-documentation.readthedocs.io/en/latest/#2.WebSocket/) 功能：

- 完全符合 RFC
- 易于使用，“可行”的体验
- 支持扩展：
  - WebSocket 的压缩扩展 (RFC7692)

[Socket.IO](https://besthttp-documentation.readthedocs.io/en/latest/#3.Socket.IO/) 功能：

- 符合最新的（1.x 和 2.x）Socket.IO 实现
- 自动**传输升级**和降级
- **二进制数据**的发送和接收
- 您可以插入自己喜欢的 Json 解码器

[SignalR Core](https://besthttp-documentation.readthedocs.io/en/latest/#6.SignalRCore/) 功能：

- 支持最新的 SignalR Core
- 支持 [MessagePack 编码](https://besthttp-documentation.readthedocs.io/en/latest/#6.SignalRCore/3.Encoders/#messagepack)
- 强类型回调
- 使用具有后备选项的最快的 Websocket 传输进行长轮询
- 程序包中包含基于标头的身份验证器
- 上传和下载串流

[SignalR](https://besthttp-documentation.readthedocs.io/en/latest/#4.SignalR/) 功能：

- 适用于最新的 [SignalR](http://www.asp.net/signalr) 实现
- 易于使用的 API
- 中心
- 支持身份验证
- 长时间运行的作业的进度消息
- 自动**传输升级**/降级
- 您可以插入自己喜欢的 Json 解码器

[服务器发送事件](https://besthttp-documentation.readthedocs.io/en/latest/#5.EventSource/)功能：

- 与[最新规格](http://www.w3.org/TR/eventsource/)兼容
- 易于使用的 API

有用的链接：

- [文档](https://besthttp-documentation.readthedocs.io/en/latest/)
- [示例代码仓库](https://github.com/Benedicht/BestHTTP_Examples)
- [服务器代码仓库](https://github.com/Benedicht/BestHTTP_DemoSite)
- [问题，疑问](https://github.com/Benedicht/BestHTTP-Issues)
- [Discord](https://discord.gg/yD9tXwQ)
- [Twitter](https://twitter.com/Best_HTTP)
- [LinkedIn](http://hu.linkedin.com/in/tivadargyorgy)

如果要咨询支持、功能申请或普通问题，您可以发送电子邮件到 [besthttp@gmail.com](mailto:besthttp@gmail.com) 联系我，或在插件的公共问题库中创建新的问题：<https://github.com/Benedicht/BestHTTP-Issues>

该资源采用微软公共许可证 (MS-PL) 下的 **DotNetZip**、MIT 下的 **BouncyCastle** 和 Public Domain 下的 **LitJson**；详情请参阅该资源包中的 [Third-Party Notices.txt](https://besthttp-documentation.readthedocs.io/en/latest/#ThirdPartyNotices/) 文件。
