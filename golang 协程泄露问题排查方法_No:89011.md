最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 协程泄露问题排查方法
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.29fr26.asia/arts/678886.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.29fr26.asia/arts/105365.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.29fr26.asia/arts/127746.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.29fr26.asia/arts/597792.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.29fr26.asia/arts/784606.Doc

原标题：版本升级服务启动失败处理
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.29fr26.asia/arts/851774.Doc

原标题：多规则数据脱敏组件开发
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.29fr26.asia/arts/712509.Doc

原标题：golang 错误处理最佳实践汇总
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.29fr26.asia/arts/084811.Doc

原标题：golang mysql 主从同步延迟兼容
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.29fr26.asia/arts/201703.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.29fr26.asia/arts/725047.Doc

原标题：前端下载导出文件功能实现
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.29fr26.asia/arts/447011.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.29fr26.asia/arts/859992.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.29fr26.asia/arts/529367.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.29fr26.asia/arts/268745.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.29fr26.asia/arts/274556.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.29fr26.asia/arts/593667.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.29fr26.asia/arts/497206.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.29fr26.asia/arts/866115.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.29fr26.asia/arts/826506.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.29fr26.asia/arts/020117.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.29fr26.asia/arts/726589.Doc

原标题：golang 消息死信处理业务逻辑
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.29fr26.asia/arts/726882.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.29fr26.asia/arts/286565.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.29fr26.asia/arts/175906.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.29fr26.asia/arts/268416.Doc

原标题：单元测试用例编写入门实操
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.29fr26.asia/arts/964363.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.29fr26.asia/arts/157639.Doc

原标题：golang redis 缓存穿透解决方案
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.29fr26.asia/arts/060659.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.29fr26.asia/arts/345831.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.29fr26.asia/arts/014654.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.29fr26.asia/arts/266088.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.29fr26.asia/arts/523338.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.29fr26.asia/arts/540958.Doc

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.29fr26.asia/arts/294652.Doc

原标题：端口占用释放资源重启服务
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.29fr26.asia/arts/095289.Doc

原标题：golang proto 默认值坑点梳理
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.29fr26.asia/arts/931781.Doc

原标题：nodejs 内存溢出问题排查修复
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.29fr26.asia/arts/907641.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.29fr26.asia/arts/995745.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.29fr26.asia/arts/077747.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.29fr26.asia/arts/115234.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.29fr26.asia/arts/896863.Doc

原标题：缓存过期打散防止缓存雪崩
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.29fr26.asia/arts/512637.Doc

原标题：跨平台换行符统一异常修复
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.29fr26.asia/arts/961074.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.29fr26.asia/arts/722746.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.29fr26.asia/arts/304217.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.29fr26.asia/arts/505876.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.29fr26.asia/arts/979734.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.29fr26.asia/arts/523560.Doc

原标题：业务幂等键设计防重复逻辑
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.29fr26.asia/arts/156532.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.29fr26.asia/arts/888584.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.29fr26.asia/arts/729111.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.29fr26.asia/arts/930288.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.29fr26.asia/arts/983227.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.29fr26.asia/arts/941249.Doc

原标题：快速上手简单信号处理脚本编写
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.29fr26.asia/arts/860066.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.29fr26.asia/arts/416522.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.29fr26.asia/arts/997911.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.29fr26.asia/arts/504336.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.29fr26.asia/arts/422688.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.29fr26.asia/arts/977285.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.29fr26.asia/arts/663343.Doc

原标题：golang 单元测试 mock http 请求
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.29fr26.asia/arts/631108.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.29fr26.asia/arts/012474.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.29fr26.asia/arts/318484.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.29fr26.asia/arts/908753.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.29fr26.asia/arts/803218.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.29fr26.asia/arts/264181.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.29fr26.asia/arts/012207.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.29fr26.asia/arts/964609.Doc

原标题：golang goroutine 池任务调度
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.29fr26.asia/arts/305703.Doc

原标题：文件读写与异常捕获代码示例
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.29fr26.asia/arts/637679.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.29fr26.asia/arts/070871.Doc

原标题：前端错误监控上报系统搭建
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.29fr26.asia/arts/575475.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.29fr26.asia/arts/226962.Doc

原标题：golang 系统设计热点数据缓存处理
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.29fr26.asia/arts/827904.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.29fr26.asia/arts/855606.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.29fr26.asia/arts/764222.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.29fr26.asia/arts/727991.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.29fr26.asia/arts/635987.Doc

原标题：Shell 脚本自动化命令编写
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.29fr26.asia/arts/943244.Doc

三、实战开发｜Practice
原标题：文件分片上传断点续传功能
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.29fr26.asia/arts/464525.Doc

原标题：入门实践：简单批量处理脚本编写
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.29fr26.asia/arts/582121.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.29fr26.asia/arts/649008.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.29fr26.asia/arts/765267.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.29fr26.asia/arts/585322.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.29fr26.asia/arts/226269.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.29fr26.asia/arts/421308.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.29fr26.asia/arts/787212.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.29fr26.asia/arts/963571.Doc

原标题：看懂报错日志快速定位问题
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.29fr26.asia/arts/251322.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.29fr26.asia/arts/117637.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.29fr26.asia/arts/764585.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.29fr26.asia/arts/461511.Doc

原标题：golang etcd 配置中心简单使用
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.29fr26.asia/arts/542661.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.29fr26.asia/arts/823736.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.29fr26.asia/arts/471100.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.29fr26.asia/arts/262904.Doc

原标题：API 接口调试与异常处理实战
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.29fr26.asia/arts/864544.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.29fr26.asia/arts/676476.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.29fr26.asia/arts/096153.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.29fr26.asia/arts/522780.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.29fr26.asia/arts/716284.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.29fr26.asia/arts/693982.Doc

原标题：golang redis 连接池参数最佳值
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.29fr26.asia/arts/392824.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.29fr26.asia/arts/899671.Doc

原标题：golang redis 网络超时参数调优
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.29fr26.asia/arts/190036.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.29fr26.asia/arts/425881.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.29fr26.asia/arts/506835.Doc

原标题：浏览器内存泄漏排查前端页面
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.29fr26.asia/arts/881033.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.29fr26.asia/arts/226558.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.29fr26.asia/arts/581267.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.29fr26.asia/arts/310256.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.29fr26.asia/arts/085589.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.29fr26.asia/arts/237065.Doc

原标题：golang es 索引生命周期管理思路
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.29fr26.asia/arts/421621.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.29fr26.asia/arts/193535.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.29fr26.asia/arts/675705.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.29fr26.asia/arts/059176.Doc

原标题：eslint prettier 代码规范落地
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.29fr26.asia/arts/208159.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.29fr26.asia/arts/833222.Doc

四、架构设计｜Architecture
原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.29fr26.asia/arts/410633.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.29fr26.asia/arts/290669.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.29fr26.asia/arts/498711.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.29fr26.asia/arts/525625.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.29fr26.asia/arts/468273.Doc

原标题：接口压测定位系统性能瓶颈
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.29fr26.asia/arts/056261.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.29fr26.asia/arts/058833.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.29fr26.asia/arts/349872.Doc

原标题：Performance：数据库join优化，大表join规避
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.29fr26.asia/arts/611136.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.29fr26.asia/arts/340105.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.29fr26.asia/arts/374418.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.29fr26.asia/arts/522097.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.29fr26.asia/arts/101580.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.29fr26.asia/arts/808257.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.29fr26.asia/arts/127306.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.29fr26.asia/arts/820855.Doc

原标题：golang mysql json 字段查询使用
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.29fr26.asia/arts/067300.Doc

原标题：Performance：JSON序列化性能优化实践
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.29fr26.asia/arts/321183.Doc

?
