# Kayrx是多方面

`Kayrx`的基础是`Rust`强大的`Async Fiber`系统。`Kayrx::web`给了你是一个有趣和非常快速的`Web`开发框架, 很容易上手。

`Kayrx`开发的应用程序在本机可执行文件中包含HTTP服务器。您可以将其放在其他HTTP服务器（如nginx）之后，也可以按原样提供:即在完全不存在另一个HTTP服务器（如nginx）的情况下，其功能也足以提供`HTTP 1`和`HTTP 2`支持以及`SSL / TLS`。这对于构建可分发的微型服务很有用。

最重要的是：`Kayrx`在 Rust 的`1.39`或更高版本上运行，并且使用稳定版本.
