# 特性 Features


* **Switch between template engines**: Select the way you like to parse your html files,   
  switchable via one-line configuration, [read more](render.md)

  **模版引擎切换**: 只要通过一行配置代码，即可选择你喜欢的解析html文件的方式，[阅读更多](render.md)

* **Typescript**: Auto-compile & Watch your client side code via the [typescript plugin](plugin-typescript.md)

 **Typescript**: 可以自动编译、监视你的客户端代码，只需使用插件 ［typescript 插件](plugin-typescript.md)
 
* **Online IDE**: Edit & Compile your client side code when you are not home via the [editor plugin](plugin-editor.md)

 **在线IDE** 当你不在家时可以通过 [编辑器插件](plugin-editor.md) 来编辑、编译你的客户端代码。

* **Iris Online Control**:   
  Web-based interface to control the basics functionalities of your server via the [iriscontrol plugin](plugin-iriscontrol.md).   
  \(Note that Iris control is still young\).
  
  **Iris在线控制**: 通过 [iris控制插件](plugin-iriscontrol.md) 你可以使用基于Web的接口来控制服务器基本功能。\(需要注意的是Iris控制插件还很年轻\).
  
* **Subdomains**:   
  Easy way to express your api via custom and dynamic subdomains[\*](subdomains.md)

  **子域名**: 通过自定义或动态子域名这种简单的方式来发布你的API [*](subdomains.md)

* **Named Path Parameters**: Probably you already know what this means. If not, [It's easy to learn about](named-parameters.md)

   **命名路径参数**: 可能你已经知道这意味着什么。如果不知道的话，[学起来很简单](named-parameters.md)

* **Custom HTTP Errors**: Define your own html templates or plain messages when http errors occur[\*](custom-http-errors.md)
  
  **自定义 HTTP 错误**: 当HTTP错误发生时，定义你自己的html模版或文本消息 [*](custom-http-errors.md)

* **Internationalization**: [i18n](middleware-internationalization-and-localization.md)

 **国际化**: [i18n](middleware-internationalization-and-localization.md)

* **Bindings**: Need a fast way to convert data from body or form into an object? Take a look [here](request-body-bind.md)

 **绑定**: 需要一种快速绑定并转换body或form数据为一个对象的方式？看一看这里 [here](request-body-bind.md)

* **Streaming**: You have only one option when streaming comes into play[\*](streaming.md)
	
  **数据流**: 数据流出现时你只有一个选择 [*][streaming.md]
  
* **Middlewares**: Create and\/or use global or per route middleware with Iris' simplicity[\*](middlewares.md)

   **中间件**: Iris 可以很简单的 创建／使用 全局或单独路由中间件 [*](middlewares.md)

* **Sessions**:  Sessions provide a secure way to authenticate your clients\/users [\*](package-sessions.md)

  **会话 Sessions**: 会话提供了一种 客户端／用户 进行身份认证的安全方式 [*](package-sessions.md)

* **Realtime**: Realtime is fun when you use websockets[\*](package-websocket.md)

  **实时性**: 当你使用websockets时它的实时性很有趣 [*](package-websocket.md)

* **Context**:  [Context](context.md) is used for storing route params, storing handlers,   
  sharing variables between middleware, render rich content, send files and much more[\*](context.md)
  
  **上下文 Context**: [Context](context.md) 被用来 存储路由参数、存储操作器、中间件间共享变量、 渲染富内容、发送文件 和 更多其它的操作[*](context.md)
  
* **Plugins**: You can inject your own plugins into the Iris framework[\*](plugins.md)

  **插件**: 你可以将自己构建的插件注入到 Iris 框架中 [*](plugins.md)

* **Full API**: All http methods are supported[\*](api.md)

  **完备的API**: 支持所有的HTTP方法 [*](api.md)

* **Party**:  Group routes when sharing the same resources or middleware. You can organise a party with domains too! [\*](party.md)

  **派别**: 共享相同资源或中间件时可使用派别 Party 对路由进行分组。你也可以使用域名来组织派别! [*](party.md)

* **Transport Layer Security**: Provide privacy, authenticity and data integrity between your server and the client, you can serve using letsencrypt.org, automatic tls too[\*](tls.md)

  **安全传输层 TLS**: 提供你的服务器和客户端之间的私密性、可靠性和数据完整性，你也可以使用 letsencrypt.org 自动实现 tls 伺服 [*](tls.md)

* **Multi server instances**: Not only does Iris have a default main server, =you can declare as many as you need[\*](declaration.md)

  **多服务器实例**: Iris不是只能拥有一个默认的主服务器，你可以根据需要声明任意数量的服务器 [*](declaration.md)

* **Zero configuration**:  No need to configure anything for typical usage.   
  Well-structured default configurations everywhere, which you can change with ease.
  
  **零配置**: 经典用例不需要配置任何东西。不论哪儿都具有优良结构的默认配置，你可以很容易的修改它。
  
* **Zero allocations**: Iris generates zero garbage

  **零内存分配**: Iris生成0内存垃圾

* **Auto updater**: You're able to turn on the version checker & updater in case you forget to update your iris

  **自动更新器**: 为防止忘记更新你的iris，你可以开启版本检测器和更新器

Iris is one of the most featured web frameworks out there, not all features are here and don't expect from me to write down all of their usages in this gitbook, if you see that I'm missing something please make a PR to the [gitbook repository](https://github.com/iris-contrib/gitbook)!

Iris 是最富有特色的网站框架之一，不是所有的特性都书写在这里了，不要期望我在此gitbook中写下所有特性的用例，如果你发现我漏掉了哪些特性，请在 [gitbook 仓库](https://github.com/iris-contrib/gitbook) 上创建一个PR!

