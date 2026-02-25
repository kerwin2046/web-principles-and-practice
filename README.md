# 全栈 + AI 工程实践

> 本系列从「工程落地」视角出发，系统讲解如何用现代 Web 全栈技术 + 大模型能力，搭建可线上运行的 AI 应用（聊天助手、RAG 知识库、智能代理、工作流编排等）。
>
> **2025 年持续更新**：围绕 TypeScript/Node.js、React/Next.js、Go、Python、PostgreSQL、Redis、向量数据库、OpenAI/Claude 等主流技术栈，强调「从 0 到 1 可上线」的工程实践，而不是停留在 Demo。


## 宏观视角上的浏览器

- [Chrome架构：仅仅打开1个页面，为什么有4个进程](./宏观视角上的浏览器/Chrome架构：仅仅打开1个页面，为什么有4个进程/index.md)
- [TCP协议：如何保证页面文件能被完整送达浏览器](./宏观视角上的浏览器/TCP协议：如何保证页面文件能被完整送达浏览器/index.md)
- [HTTP请求流程：为什么很多站点第二次打开速度会很快](./宏观视角上的浏览器/HTTP请求流程：为什么很多站点第二次打开速度会很快/index.md)
- [导航流程：从输入URL到页面展示这中间发生了什么](./宏观视角上的浏览器/导航流程：从输入URL到页面展示这中间发生了什么/index.md)
- [渲染流程（上）：HTML、CSS和JavaScript是如何变成页面的](./宏观视角上的浏览器/渲染流程（上）：HTML、CSS和JavaScript是如何变成页面的/index.md)
- [渲染流程（下）：HTML、CSS和JavaScript是如何变成页面的](./宏观视角上的浏览器/渲染流程（下）：HTML、CSS和JavaScript是如何变成页面的/index.md)

## 浏览器中的JavaScript执行机制

- [变量提升：JavaScript代码是按顺序执行的吗](./浏览器中的JavaScript执行机制/变量提升：JavaScript代码是按顺序执行的吗/index.md)
- [调用栈：为什么JavaScript代码会出现栈溢出](./浏览器中的JavaScript执行机制/调用栈：为什么JavaScript代码会出现栈溢出/index.md)
- [块级作用域：var缺陷以及为什么要引入let和const](./浏览器中的JavaScript执行机制/块级作用域：var缺陷以及为什么要引入let和const/index.md)
- [深度解析作用域链和闭包：代码中出现相同的变量，JavaScript引擎如何选择](./浏览器中的JavaScript执行机制/作用域链和闭包：代码中出现相同的变量，JavaScript引擎如何选择/index.md)
- [this：从JavaScript执行上下文视角讲this](./浏览器中的JavaScript执行机制/this：从JavaScript执行上下文视角讲this/index.md)

## V8工作原理

- [栈空间和堆空间：数据是如何存储的](./V8工作原理/栈空间和堆空间：数据是如何存储的/index.md)
- [垃圾回收：垃圾数据如何自动回收](./V8工作原理/垃圾回收：垃圾数据如何自动回收/index.md)
- [编译器和解析器：V8如何执行一段JavaScript代码的](./V8工作原理/编译器和解析器：V8如何执行一段JavaScript代码的/index.md)

## 浏览器中的页面循环系统

- [消息队列和事件循环：页面是怎么活起来的](./浏览器中的页面循环系统/消息队列和事件循环：页面是怎么活起来的/index.md)
- [Webapi：setTimeout是怎么实现的](./浏览器中的页面循环系统/Webapi：setTimeout是怎么实现的/index.md)
- [Webapi：XMLHttpRequest是怎么实现的](./浏览器中的页面循环系统/Webapi：XMLHttpRequest是怎么实现的/index.md)
- [宏任务和微任务：不是所有的任务都是一个待遇](./浏览器中的页面循环系统/宏任务和微任务：不是所有的任务都是一个待遇/index.md)
- [使用Promise告别回调函数](./浏览器中的页面循环系统/使用Promise告别回调函数/index.md)
- [async-await使用同步方式写异步代码](./浏览器中的页面循环系统/async-await使用同步方式写异步代码/index.md)

## 浏览器中的页面

- [页面性能分析：利用chrome做web性能分析](./浏览器中的页面/页面性能分析：利用chrome做web性能分析/index.md)
- [DOM树：JavaScript是如何影响DOM树构建的](./浏览器中的页面/DOM树：JavaScript是如何影响DOM树构建的/index.md)
- [渲染流水线：CSS如何影响首次加载时的白屏时间](./浏览器中的页面/渲染流水线：CSS如何影响首次加载时的白屏时间/index.md)
- [分层和合成机制：为什么CSS动画比JavaScript高效](./浏览器中的页面/分层和合成机制：为什么CSS动画比JavaScript高效/index.md)
- [页面性能：如何系统优化页面](./浏览器中的页面/页面性能：如何系统优化页面/index.md)
- [虚拟DOM：虚拟DOM和实际DOM有何不同](./浏览器中的页面/虚拟DOM：虚拟DOM和实际DOM有何不同/index.md)
- [PWA：解决了web应用哪些问题](./浏览器中的页面/PWA：解决了web应用哪些问题/index.md)
- [webComponent：像搭积木一样构建web应用](./浏览器中的页面/webComponent：像搭积木一样构建web应用/index.md)

## 浏览器中的网络

- [HTTP1：HTTP性能优化](./浏览器中的网络/HTTP1：HTTP性能优化/index.md)
- [HTTP2：如何提升网络速度](./浏览器中的网络/HTTP2：如何提升网络速度/index.md)
- [HTTP3：甩掉TCP、TCL包袱，构建高效网络](./浏览器中的网络/HTTP3：甩掉TCP、TCL包袱，构建高效网络/index.md)
- [同源策略：为什么XMLHttpRequest不能跨域请求资源](./浏览器中的网络/同源策略：为什么XMLHttpRequest不能跨域请求资源/index.md)
- [跨站脚本攻击XSS：为什么cookie中有httpOnly属性](./浏览器中的网络/跨站脚本攻击XSS：为什么cookie中有httpOnly属性/index.md)
- [CSRF攻击：陌生链接不要随便点](./浏览器中的网络/CSRF攻击：陌生链接不要随便点/index.md)
- [沙盒：页面和系统之间的隔离墙](./浏览器中的网络/沙盒：页面和系统之间的隔离墙/index.md)
- [HTTPS：让数据传输更安全](./浏览器中的网络/HTTPS：让数据传输更安全/index.md)

---

## 2025 更新要点速览

### JavaScript 执行机制
- 补充 **TDZ（暂时性死区）** 深层机制、`const` 不可变性本质
- 新增 **尾调用优化（TCO）** 现状分析、**蹦床函数** 等现代栈溢出解决方案
- 新增 **闭包在 React Hooks 中的陈旧闭包问题**、WeakRef/FinalizationRegistry
- 新增 **this 绑定优先级**、ES6+ 箭头函数/class 字段绑定、`globalThis`

### V8 工作原理
- 新增 V8 **Tagged Pointer/SMI 优化**、Hidden Class、Inline Cache
- 新增 **Orinoco 项目**：并发标记、并行清理、三色标记法
- 更新 V8 编译管线：**Ignition → Sparkplug → Maglev → TurboFan** 四层架构
- 新增 **WebAssembly 编译管线**（Liftoff + TurboFan）

### 页面循环系统
- 新增 **scheduler.postTask()/scheduler.yield()** 优先级调度 API
- 新增 **queueMicrotask()** 标准 API
- 新增 **Fetch API** 全面介绍（替代 XMLHttpRequest）
- 新增 **Top-Level Await**、Promise.allSettled/any/withResolvers

### 浏览器网络
- **HTTP/2 Server Push 已废弃**，替代方案 103 Early Hints
- **HTTP/3 (RFC 9114) 和 QUIC (RFC 9000)** 已全面标准化和部署
- 新增 **TLS 1.3**、Let's Encrypt/ACME、HSTS
- 新增 **Trusted Types API**、SameSite=Lax 默认值、Privacy Sandbox

### 浏览器页面
- 新增 **Core Web Vitals**（LCP/INP/CLS）性能框架
- 新增 **View Transitions API**、CSS scroll-driven animations
- 更新 **React 18/19**（Concurrent/Compiler/Server Components）
- 新增 **Declarative Shadow DOM**、ElementInternals
- 新增 **Lighthouse**、Long Animation Frames (LoAF) API

### 宏观架构
- 更新 Chrome **Site Isolation** 全平台部署、Servicification 进展
- 新增 **QUIC/HTTP3** 传输层介绍
- 更新 **LayoutNG** 为当前默认引擎
- 新增 **Speculation Rules API** 等现代导航优化


## 书籍
 
https://zh.d2l.ai/chapter_introduction/index.html 
