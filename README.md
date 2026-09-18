[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/uhub-awesome-go-badge.png)](https://mseep.ai/app/uhub-awesome-go)

# awesome-go

A curated list of awesome Go frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Web Servers and Proxies](#web-servers-and-proxies)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Game Development](#game-development)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Date and Time](#date-and-time)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [astaxie/build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) - A golang ebook intro how to build a web with golang
* [unknwon/the-way-to-go_ZH_CN](https://github.com/unknwon/the-way-to-go_ZH_CN) - 《The Way to Go》中文译本，中文正式名《Go 入门指南》
* [tmrts/go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms
* [quii/learn-go-with-tests](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development
* [chai2010/advanced-go-programming-book](https://github.com/chai2010/advanced-go-programming-book) - :books: 《Go语言高级编程》开源图书，涵盖CGO、Go汇编语言、RPC实现、Protobuf插件实现、Web框架实现、分布式系统等高阶主题(完稿)
* [hoanhan101/ultimate-go](https://github.com/hoanhan101/ultimate-go) - The Ultimate Go Study Guide
* [halfrost/Halfrost-Field](https://github.com/halfrost/Halfrost-Field) - ✍🏻 Source Code Deep Dives, System Design & Engineering Blogs | Halfrost-Field 冰霜之地：源码解析、系统设计与工程实践笔记
* [talkgo/night](https://github.com/talkgo/night) - Weekly Go Online Meetup via Bilibili｜Go 夜读｜通过 bilibili 在线直播的方式分享 Go 相关的技术话题，每天大家在微信/telegram/Slack 上及时沟通交流编程技术话题。
* [ardanlabs/gotraining](https://github.com/ardanlabs/gotraining) - Go Training Class Material :
* [GoesToEleven/GolangTraining](https://github.com/GoesToEleven/GolangTraining) - Training for Golang (go language)
* [polaris1119/The-Golang-Standard-Library-by-Example](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) - Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。
* [unknwon/go-fundamental-programming](https://github.com/unknwon/go-fundamental-programming) - 《Go 编程基础》是一套针对 Google 出品的 Go 语言的视频语音教程，主要面向新手级别的学习者。
* [mmcgrana/gobyexample](https://github.com/mmcgrana/gobyexample) - Go by Example
* [xxjwxc/uber_go_guide_cn](https://github.com/xxjwxc/uber_go_guide_cn) - Uber Go 语言编码规范中文版. The Uber Go Style Guide .
* [teivah/100-go-mistakes](https://github.com/teivah/100-go-mistakes) - 📖 100 Go Mistakes and How to Avoid Them
* [teh-cmc/go-internals](https://github.com/teh-cmc/go-internals) - A book about the internals of the Go programming language.
* [eranyanay/1m-go-websockets](https://github.com/eranyanay/1m-go-websockets) - handling 1M websockets connections in Go
* [chai2010/go-ast-book](https://github.com/chai2010/go-ast-book) - :books: 《Go语言定制指南》(原名：Go语法树入门/开源免费图书/Go语言进阶/掌握抽象语法树/Go语言AST)
* [OWASP/Go-SCP](https://github.com/OWASP/Go-SCP) - Golang Secure Coding Practices guide
* [darjun/go-daily-lib](https://github.com/darjun/go-daily-lib) - Go 每日一库
* [ffhelicopter/Go42](https://github.com/ffhelicopter/Go42) - 《Go语言四十二章经》详细讲述Go语言规范与语法细节及开发中常见的误区，通过研读标准库等经典代码设计模式，启发读者深刻理解Go语言的核心思维，进入Go语言开发的更高阶段。
* [gopl-zh/gopl-zh.github.com](https://github.com/gopl-zh/gopl-zh.github.com) - :books: Go语言圣经中文版 🇨🇳
* [xinliangnote/Go](https://github.com/xinliangnote/Go) - 【Go 从入门到实战】学习笔记，从零开始学 Go、Gin 框架，基本语法包括 26 个Demo，Gin 框架包括：Gin 自定义路由配置、Gin 使用 Logrus 进行日志记录、Gin 数据绑定和验证、Gin 自定义错误处理、Go gRPC Hello World... 持续更新中...
* [overnote/over-golang](https://github.com/overnote/over-golang) - Golang相关：[审稿进度80%]Go语法、Go并发思想、Go与web开发、Go微服务设施等
* [golang-design/under-the-hood](https://github.com/golang-design/under-the-hood) - 📚 Go: Under The Hood | Go 语言原本 | https://golang.design/under-the-hood
* [hwholiday/learning_tools](https://github.com/hwholiday/learning_tools) - Go 学习、Go 进阶、Go 实用工具类、Go DDD 项目落地、Go-kit 、Go-Micro 、Go 推送平台、微服务实践
* [mao888/golang-guide](https://github.com/mao888/golang-guide) - 「Golang学习+面试指南」一份涵盖大部分 Golang程序员所需要掌握的核心知识。准备 Golang面试，首选 GolangGuide！
* [geektutu/high-performance-go](https://github.com/geektutu/high-performance-go) - high performance coding with golang（Go 语言高性能编程，Go 语言陷阱，Gotchas，Traps）
* [golang/proposal](https://github.com/golang/proposal) - Go Project Design Documents
* [hantmac/Mastering_Go_ZH_CN](https://github.com/hantmac/Mastering_Go_ZH_CN) - 《Mastering GO》中文译本，《玩转 GO》。
* [cristaloleg/go-advice](https://github.com/cristaloleg/go-advice) - List of advice and tricks for Go ʕ◔ϖ◔ʔ
* [Pradumnasaraf/DevOps](https://github.com/Pradumnasaraf/DevOps) - I created this repository to keep my learning, notes, and code in one place for various tools in DevOps. Now, it's helping thousands of learners, practitioners, and professionals every day in their DevOps journey.
* [thewhitetulip/web-dev-golang-anti-textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook) - Learn how to write webapps without a framework in Go.
* [luk4z7/go-concurrency-guide](https://github.com/luk4z7/go-concurrency-guide) - Practical concurrency guide in Go, communication by channels, patterns
* [campoy/go-tooling-workshop](https://github.com/campoy/go-tooling-workshop) - A workshop covering all the tools gophers use in their day to day life
* [unknwon/go-web-foundation](https://github.com/unknwon/go-web-foundation) - 《Go Web 基础》是一套针对 Google 出品的 Go 语言的视频语音教程，主要面向完成《Go 编程基础》教程后希望进一步了解有关 Go Web 开发的学习者。
* [mikespook/Learning-Go-zh-cn](https://github.com/mikespook/Learning-Go-zh-cn) - 一本学习 Go 语言的免费电子书。
* [novalagung/dasarpemrogramangolang](https://github.com/novalagung/dasarpemrogramangolang) - 📖 Source Code Website/Ebook Dasar Pemrograman Golang
* [StephenGrider/GoCasts](https://github.com/StephenGrider/GoCasts) - Companion Repo to https://www.udemy.com/go-the-complete-developers-guide/
* [betty200744/ultimate-go](https://github.com/betty200744/ultimate-go) - This repo contains my notes on working with Go and computer systems.
* [akutz/go-generics-the-hard-way](https://github.com/akutz/go-generics-the-hard-way) - A hands-on approach to getting started with Go generics.
* [golang-china/go2-book](https://github.com/golang-china/go2-book) - :books: 《Go2编程指南》开源图书，重点讲解Go2新特性，以及Go1教程中较少涉及的特性

### Examples and Exercises

* [halfrost/LeetCode-Go](https://github.com/halfrost/LeetCode-Go) - ✅ Solutions to LeetCode by Go, 100% test coverage, runtime beats 100% | LeetCode 题解
* [inancgumus/learngo](https://github.com/inancgumus/learngo) - ❤️ 1000+ Hand-Crafted Go Examples, Exercises, and Quizzes. 🚀 Learn Go by fixing 1000+ tiny programs.
* [TheAlgorithms/Go](https://github.com/TheAlgorithms/Go) - Algorithms and Data Structures implemented in Go for beginners, following best practices.
* [geektutu/7days-golang](https://github.com/geektutu/7days-golang) - 7 days golang programs from scratch (web framework Gee, distributed cache GeeCache, object relational mapping ORM framework GeeORM, rpc framework GeeRPC etc) 7天用Go动手写/从零实现系列
* [bxcodec/go-clean-arch](https://github.com/bxcodec/go-clean-arch) - Go (Golang) Clean Architecture based on Reading Uncle Bob's Clean Architecture
* [senghoo/golang-design-pattern](https://github.com/senghoo/golang-design-pattern) - 设计模式 Golang实现－《研磨设计模式》读书笔记
* [EndlessCheng/codeforces-go](https://github.com/EndlessCheng/codeforces-go) - 算法竞赛模板库 by 灵茶山艾府 💭💡🎈
* [adonovan/gopl.io](https://github.com/adonovan/gopl.io) - Example programs from "The Go Programming Language"
* [evrone/go-clean-template](https://github.com/evrone/go-clean-template) - Clean Architecture template for Golang services
* [eddycjy/go-gin-example](https://github.com/eddycjy/go-gin-example) - An example of gin
* [xiaobaiTech/golangFamily](https://github.com/xiaobaiTech/golangFamily) - 【超全golang面试题合集+golang学习指南+golang知识图谱+入门成长路线】 一份涵盖大部分golang程序员所需要掌握的核心知识。常用第三方库(mysql,mq,es,redis等)+机器学习库+算法库+游戏库+开源框架+自然语言处理nlp库+网络库+视频库+微服务框架+视频教程+音频音乐库+图形图片库+物联网库+地理位置信息+嵌入式脚本库+编译器库+数据库+金融库+电子邮件库+电子书籍+分词+数据结构+设计模式+去html tag标签等+go学习+go面试+计算机网络基础+图解网络+操作系统面试题+数据库面试题+面试题合集
* [techschool/simplebank](https://github.com/techschool/simplebank) - Backend master class: build a simple bank service in Go
* [ThreeDotsLabs/wild-workouts-go-ddd-example](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Go DDD example application. Complete project to show how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
* [golang-design/go-questions](https://github.com/golang-design/go-questions) - 📖 Go 程序员面试笔试宝典 | 从问题切入，串连 Go 语言相关的所有知识，融会贯通。 https://golang.design/go-questions
* [amitshekhariitbhu/go-backend-clean-architecture](https://github.com/amitshekhariitbhu/go-backend-clean-architecture) - A Go (Golang) Backend Clean Architecture project with Gin, MongoDB, JWT Authentication Middleware, Test, and Docker.
* [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) - Go microservice template for Kubernetes
* [lifei6671/interview-go](https://github.com/lifei6671/interview-go) - golang面试题集合https://interview.disign.me/
* [Mikaelemmmm/go-zero-looklook](https://github.com/Mikaelemmmm/go-zero-looklook) - 🔥基于go-zero(go zero) 微服务全技术栈开发最佳实践项目。Develop best practice projects based on the full technology stack of go zero (go zero) microservices.
* [miguelmota/golang-for-nodejs-developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning 🤓 By @miguelmota *(archived)*
* [shomali11/go-interview](https://github.com/shomali11/go-interview) - Collection of Technical Interview Questions solved with Go
* [GoogleCloudPlatform/golang-samples](https://github.com/GoogleCloudPlatform/golang-samples) - Sample apps and code written for Google Cloud in the Go programming language.
* [gin-gonic/examples](https://github.com/gin-gonic/examples) - A repository to host examples and tutorials for Gin.
* [goinaction/code](https://github.com/goinaction/code) - Source Code for Go In Action examples
* [Jeiwan/blockchain_go](https://github.com/Jeiwan/blockchain_go) - A simplified blockchain implementation in Golang
* [thangchung/go-coffeeshop](https://github.com/thangchung/go-coffeeshop) - ☕ A practical event-driven microservices demo built with Golang. Nomad, Consul Connect, Vault, and Terraform for deployment
* [marmotedu/iam](https://github.com/marmotedu/iam) - 企业级的 Go 语言实战项目：认证和授权系统（带配套课程）
* [ardanlabs/service](https://github.com/ardanlabs/service) - Starter-kit for writing services in Go using Kubernetes.
* [hoanhan101/algo](https://github.com/hoanhan101/algo) - 101+ coding interview problems in Go
* [6boris/awesome-golang-algorithm](https://github.com/6boris/awesome-golang-algorithm) - :memo: LeetCode of algorithms with golang solution(updating).
* [astaxie/go-best-practice](https://github.com/astaxie/go-best-practice) - Trying to complete over 100 projects in various categories in golang.
* [lotusirous/go-concurrency-patterns](https://github.com/lotusirous/go-concurrency-patterns) - Concurrency patterns in Go
* [aQuaYi/LeetCode-in-Go](https://github.com/aQuaYi/LeetCode-in-Go) - Go Solution for LeetCode algorithms problems, 100% coverage. *(archived)*
* [golang/example](https://github.com/golang/example) - Go example projects
* [olebedev/go-starter-kit](https://github.com/olebedev/go-starter-kit) - [abandoned] Golang isomorphic react/hot reloadable/redux/css-modules/SSR starter kit *(archived)*
* [ua-nick/Data-Structures-and-Algorithms](https://github.com/ua-nick/Data-Structures-and-Algorithms) - Data Structures and Algorithms implementation in Go
* [gothinkster/golang-gin-realworld-example-app](https://github.com/gothinkster/golang-gin-realworld-example-app) - Exemplary real world application built with Golang + Gin
* [pibigstar/go-demo](https://github.com/pibigstar/go-demo) - Go语言实例教程从入门到进阶，包括基础库使用、设计模式、面试易错点、工具类、对接第三方等
* [hyper0x/Golang_Puzzlers](https://github.com/hyper0x/Golang_Puzzlers) - An example project, for my column named "Core Golang - 36 lessons"
* [marcusolsson/goddd](https://github.com/marcusolsson/goddd) - Exploring DDD in Go *(archived)*
* [katzien/go-structure-examples](https://github.com/katzien/go-structure-examples) - Examples for my talk on structuring go apps
* [cdarwin/go-koans](https://github.com/cdarwin/go-koans) - koans for go
* [0xAX/go-algorithms](https://github.com/0xAX/go-algorithms) - Algorithms and data structures for golang
* [arnauddri/algorithms](https://github.com/arnauddri/algorithms) - Algorithms & Data Structures in Go
* [austingebauer/go-leetcode](https://github.com/austingebauer/go-leetcode) - A collection of 100+ popular LeetCode problems solved in Go.

### Awesome Lists and Collections

* [avelino/awesome-go](https://github.com/avelino/awesome-go) - A curated list of awesome Go frameworks, libraries and software
* [dariubs/GoBooks](https://github.com/dariubs/GoBooks) - List of Golang books
* [hackstoic/golang-open-source-projects](https://github.com/hackstoic/golang-open-source-projects) - 为互联网IT人打造的中文版awesome-go
* [0voice/Introduction-to-Golang](https://github.com/0voice/Introduction-to-Golang) - 【未来服务器端编程语言】最全空降golang资料补给包（满血战斗），包含文章，书籍，作者论文，理论分析，开源框架，云原生，大佬视频，大厂实战分享ppt
* [nikivdev/go](https://github.com/nikivdev/go) - Go tools, libraries
* [nikolaydubina/go-recipes](https://github.com/nikolaydubina/go-recipes) - 🦩 Tools for Go projects
* [mingrammer/go-web-framework-stars](https://github.com/mingrammer/go-web-framework-stars) - :star: Web frameworks for Go, most starred on GitHub
* [ksimka/go-is-not-good](https://github.com/ksimka/go-is-not-good) - A curated list of articles complaining that go (golang) isn't good enough
* [jiujuan/go-collection](https://github.com/jiujuan/go-collection) - :tulip: awesome awesome go, study golang from basic to proficient。Go Study Guide。从学习 Go 基础语法和高级特性，到实战项目，再到架构微服务，最后到跑路。
* [yangwenmai/learning-golang](https://github.com/yangwenmai/learning-golang) - Go 学习之路：Go 开发者博客、Go 微信公众号、Go 学习资料（文档、书籍、视频）

## Language and Tooling

### Compilers and Interpreters

* [golang/go](https://github.com/golang/go) - The Go programming language
* [microsoft/typescript-go](https://github.com/microsoft/typescript-go) - Staging repo for development of native port of TypeScript *(archived)*
* [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.
* [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) - A compiler from Go to JavaScript for running Go code in a browser
* [google/grumpy](https://github.com/google/grumpy) - Grumpy is a Python to Go source code transcompiler and runtime. *(archived)*
* [goplus/xgo](https://github.com/goplus/xgo) - XGo is a programming language that reads like plain English. But it's also incredibly powerful — it lets you leverage assets from C/C++, Go, Python, and JavaScript/TypeScript, creating a unified software engineering ecosystem. Our vision is to enable everyone to become a builder of the world.
* [mvdan/sh](https://github.com/mvdan/sh) - A shell parser, formatter, and interpreter with bash and zsh support; includes shfmt
* [robertkrimen/otto](https://github.com/robertkrimen/otto) - A JavaScript interpreter in Go (golang)
* [traefik/yaegi](https://github.com/traefik/yaegi) - Yaegi is Another Elegant Go Interpreter
* [expr-lang/expr](https://github.com/expr-lang/expr) - Expression language and expression evaluation for Go
* [dop251/goja](https://github.com/dop251/goja) - ECMAScript/JavaScript engine in pure Go
* [yuin/gopher-lua](https://github.com/yuin/gopher-lua) - GopherLua: VM and compiler for Lua in Go
* [elves/elvish](https://github.com/elves/elvish) - Powerful scripting language & versatile interactive shell
* [wazero/wazero](https://github.com/wazero/wazero) - wazero: the zero dependency WebAssembly runtime for Go developers
* [x-motemen/gore](https://github.com/x-motemen/gore) - Yet another Go REPL that works nicely. Featured with line editing, code completion, and more.
* [Knetic/govaluate](https://github.com/Knetic/govaluate) - Arbitrary expression evaluation for golang *(archived)*
* [alecthomas/participle](https://github.com/alecthomas/participle) - A parser library for Go
* [d5/tengo](https://github.com/d5/tengo) - A fast script language for Go
* [zxh0/jvm.go](https://github.com/zxh0/jvm.go) - A toy JVM written in Go
* [goby-lang/goby](https://github.com/goby-lang/goby) - Goby - Yet another programming language written in Go *(archived)*
* [rogchap/v8go](https://github.com/rogchap/v8go) - Execute JavaScript from Go
* [Shopify/go-lua](https://github.com/Shopify/go-lua) - A Lua VM in Go
* [cel-expr/cel-go](https://github.com/cel-expr/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing (Go)
* [wasmerio/wasmer-go](https://github.com/wasmerio/wasmer-go) - 🐹🕸️ WebAssembly runtime for Go
* [google/starlark-go](https://github.com/google/starlark-go) - Starlark in Go: the Starlark configuration language, implemented in Go
* [yassinebenaid/bunster](https://github.com/yassinebenaid/bunster) - Compile shell scripts to static binaries.
* [yunabe/lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter
* [cosmos72/gomacro](https://github.com/cosmos72/gomacro) - Interactive Go interpreter and debugger with REPL, Eval, generics and Lisp-like macros
* [elliotchance/c2go](https://github.com/elliotchance/c2go) - ⚖️ A tool for transpiling C to Go.
* [Azure/golua](https://github.com/Azure/golua) - A Lua 5.3 engine implemented in Go *(archived)*

### Build Systems

* [air-verse/air](https://github.com/air-verse/air) - ☁️ Live reload for Go apps
* [go-task/task](https://github.com/go-task/task) - A fast, cross-platform build tool inspired by Make, designed for modern workflows.
* [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) - Release engineering, simplified
* [google/wire](https://github.com/google/wire) - Compile-time Dependency Injection for Go *(archived)*
* [magefile/mage](https://github.com/magefile/mage) - a Make/rake-like dev tool using Go
* [mitchellh/gox](https://github.com/mitchellh/gox) - A dead simple, no frills Go cross compile tool *(archived)*
* [oxequa/realize](https://github.com/oxequa/realize) - Realize is the #1 Golang Task Runner which enhance your workflow by automating the most common tasks and using the best performing Golang live reloading.
* [codegangsta/gin](https://github.com/codegangsta/gin) - Live reload utility for Go web servers
* [tdewolff/minify](https://github.com/tdewolff/minify) - Go minifiers for web formats
* [gravityblast/fresh](https://github.com/gravityblast/fresh) - Build and (re)start go web apps after saving/creating/deleting source files.
* [rakyll/statik](https://github.com/rakyll/statik) - Embed files into a Go executable
* [dave/jennifer](https://github.com/dave/jennifer) - Jennifer is a code generator for Go
* [Shpota/goxygen](https://github.com/Shpota/goxygen) - Generate a modern Web project with Go and Angular, React, or Vue in seconds 🎲
* [gobuffalo/packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries. *(archived)*
* [create-go-app/cli](https://github.com/create-go-app/cli) - ✨ A complete and self-contained solution for developers of any qualification to create a production-ready project with backend (Go), frontend (JavaScript, TypeScript) and deploy automation (Ansible, Docker) by running only one CLI command.
* [constabulary/gb](https://github.com/constabulary/gb) - gb, the project based build tool for Go *(archived)*

### Package Management

* [nvm-windows/nvm](https://github.com/nvm-windows/nvm) - The Node.js version manager for Windows.
* [Jguer/yay](https://github.com/Jguer/yay) - Yet another Yogurt - An AUR Helper written in Go
* [golang/dep](https://github.com/golang/dep) - Go dependency management tool experiment (deprecated) *(archived)*
* [Masterminds/glide](https://github.com/Masterminds/glide) - Package Management for Golang
* [goproxyio/goproxy](https://github.com/goproxyio/goproxy) - A global proxy for Go modules.
* [tools/godep](https://github.com/tools/godep) - dependency tool for go *(archived)*
* [kardianos/govendor](https://github.com/kardianos/govendor) - Use Go Modules. *(archived)*
* [gomods/athens](https://github.com/gomods/athens) - A Go module datastore and proxy
* [aptly-dev/aptly](https://github.com/aptly-dev/aptly) - aptly - Debian repository management tool
* [goreleaser/nfpm](https://github.com/goreleaser/nfpm) - nFPM is Not FPM - a simple deb, rpm, apk, ipk, and arch linux packager written in Go
* [gpmgo/gopm](https://github.com/gpmgo/gopm) - Go Package Manager (gopm) is a package manager and build tool for Go. *(archived)*

### Linters and Formatters

* [golangci/golangci-lint](https://github.com/golangci/golangci-lint) - Fast linters runner for Go
* [reviewdog/reviewdog](https://github.com/reviewdog/reviewdog) - 🐶 Automated code review tool integrated with any code analysis tools regardless of programming language
* [dominikh/go-tools](https://github.com/dominikh/go-tools) - Staticcheck - The advanced Go linter
* [ondrajz/go-callvis](https://github.com/ondrajz/go-callvis) - Visualize call graph of a Go program using Graphviz
* [mgechev/revive](https://github.com/mgechev/revive) - 🔥 ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for golint
* [mvdan/gofumpt](https://github.com/mvdan/gofumpt) - A stricter gofmt
* [golang/lint](https://github.com/golang/lint) - [mirror] This is a linter for Go source code. (deprecated) *(archived)*
* [uber-go/nilaway](https://github.com/uber-go/nilaway) - Static analysis tool to detect potential nil panics in Go code
* [alecthomas/gometalinter](https://github.com/alecthomas/gometalinter) - DEPRECATED: Use https://github.com/golangci/golangci-lint *(archived)*
* [qax-os/goreporter](https://github.com/qax-os/goreporter) - A Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [kisielk/errcheck](https://github.com/kisielk/errcheck) - errcheck checks that you checked errors.
* [gojp/goreportcard](https://github.com/gojp/goreportcard) - A report card for your Go application *(archived)*

### Debugging and Profiling

* [go-delve/delve](https://github.com/go-delve/delve) - Delve is a debugger for the Go programming language.
* [google/gops](https://github.com/google/gops) - A tool to list and diagnose Go processes currently running on your system
* [davecgh/go-spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging
* [uber-archive/go-torch](https://github.com/uber-archive/go-torch) - Stochastic flame graph profiler for Go programs *(archived)*
* [maruel/panicparse](https://github.com/maruel/panicparse) - Crash your app in style (Golang)
* [loov/lensm](https://github.com/loov/lensm) - Go assembly and source viewer
* [arl/statsviz](https://github.com/arl/statsviz) - Visualise Go runtime metrics in real time
* [open-telemetry/opentelemetry-ebpf-profiler](https://github.com/open-telemetry/opentelemetry-ebpf-profiler) - The production-scale datacenter profiler (C/C++, Go, Rust, Python, Java, NodeJS, .NET, PHP, Ruby, Perl, ...)
* [felixge/fgprof](https://github.com/felixge/fgprof) - 🚀 fgprof is a sampling Go profiler that allows you to analyze On-CPU as well as Off-CPU (e.g. I/O) time together.
* [d4l3k/go-pry](https://github.com/d4l3k/go-pry) - An interactive REPL for Go that allows you to drop into your code at any point.
* [mailgun/godebug](https://github.com/mailgun/godebug) - DEPRECATED! https://github.com/derekparker/delve
* [pkg/profile](https://github.com/pkg/profile) - Simple profiling for Go
* [bcicen/grmon](https://github.com/bcicen/grmon) - Command line monitoring for goroutines

## Web

### Web Frameworks

* [gin-gonic/gin](https://github.com/gin-gonic/gin) - Gin is a high-performance HTTP web framework written in Go. It provides a Martini-like API but with significantly better performance—up to 40 times faster—thanks to httprouter. Gin is designed for building REST APIs, web applications, and microservices.
* [gofiber/fiber](https://github.com/gofiber/fiber) - ⚡️ Express inspired web framework written in Go
* [zeromicro/go-zero](https://github.com/zeromicro/go-zero) - A cloud-native Go microservices framework with cli tool for productivity.
* [labstack/echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework
* [beego/beego](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [go-kit/kit](https://github.com/go-kit/kit) - A standard library for microservices.
* [go-kratos/kratos](https://github.com/go-kratos/kratos) - Your ultimate Go microservices framework for the cloud-native era.
* [kataras/iris](https://github.com/kataras/iris) - The fastest HTTP/2 Go Web Framework. New, modern and easy to learn. Fast development with Code you control. Unbeatable cost-performance ratio :rocket:
* [flipped-aurora/gin-vue-admin](https://github.com/flipped-aurora/gin-vue-admin) - 🚀Vite+Vue3+Gin拥有AI辅助的基础开发平台，企业级业务AI+开发解决方案，内置mcp辅助服务，内置skills管理，支持TS和JS混用。它集成了JWT鉴权、权限管理、动态路由、显隐可控组件、分页封装、多点登录拦截、资源权限、上传下载、代码生成器、表单生成器和可配置的导入导出等开发必备功能。
* [go-chi/chi](https://github.com/go-chi/chi) - lightweight, idiomatic and composable router for building Go HTTP services
* [gorilla/mux](https://github.com/gorilla/mux) - Package gorilla/mux is a powerful HTTP router and URL matcher for building Go web servers with 🦍
* [gofr-dev/gofr](https://github.com/gofr-dev/gofr) - An opinionated GoLang framework for accelerated microservice development. Built in support for databases and observability.
* [julienschmidt/httprouter](https://github.com/julienschmidt/httprouter) - A high performance HTTP request router that scales well
* [gogf/gf](https://github.com/gogf/gf) - A powerful framework for faster, easier, and more efficient project development.
* [revel/revel](https://github.com/revel/revel) - A high productivity, full-stack web framework for the Go language.
* [go-admin-team/go-admin](https://github.com/go-admin-team/go-admin) - 基于Gin + Vue + Element UI & Arco Design & Ant Design 的前后端分离权限管理系统脚手架（包含了：多租户的支持，基础用户管理功能，jwt鉴权，代码生成器，RBAC资源控制，表单构建，定时任务等）3分钟构建自己的中后台项目；项目文档》：https://www.go-admin.pro Demo： https://vue.go-admin.pro Antd PRO：https://antd.go-admin.pro
* [go-martini/martini](https://github.com/go-martini/martini) - Classy web framework for Go
* [GoAdminGroup/go-admin](https://github.com/GoAdminGroup/go-admin) - A golang framework helps gopher to build a data visualization and admin panel in ten minutes
* [gobuffalo/buffalo](https://github.com/gobuffalo/buffalo) - Rapid Web Development w/ Go
* [cloudwego/hertz](https://github.com/cloudwego/hertz) - Go HTTP framework with high-performance and strong-extensibility for building micro-services.
* [xinliangnote/go-gin-api](https://github.com/xinliangnote/go-gin-api) - 基于 Gin 进行模块化设计的 API 框架，封装了常用功能，使用简单，致力于进行快速的业务研发。比如，支持 cors 跨域、jwt 签名验证、zap 日志收集、panic 异常捕获、trace 链路追踪、prometheus 监控指标、swagger 文档生成、viper 配置文件解析、gorm 数据库组件、gormgen 代码生成工具、graphql 查询语言、errno 统一定义错误码、gRPC 的使用、cron 定时任务 等等。
* [livebud/bud](https://github.com/livebud/bud) - The Full-Stack Web Framework for Go
* [qor/qor](https://github.com/qor/qor) - QOR is a set of libraries written in Go that abstracts common features needed for business applications, CMSs, and E-commerce systems.
* [emicklei/go-restful](https://github.com/emicklei/go-restful) - package for building REST-style Web Services using Go
* [goravel/goravel](https://github.com/goravel/goravel) - The full-featured Golang Development Framework skeleton
* [douyu/jupiter](https://github.com/douyu/jupiter) - Jupiter: Governance-oriented Microservice Framework.
* [nytimes/gizmo](https://github.com/nytimes/gizmo) - A Microservice Toolkit from The New York Times
* [hoisie/web](https://github.com/hoisie/web) - The easiest way to create web applications with Go
* [zenazn/goji](https://github.com/zenazn/goji) - Goji is a minimalistic web framework for Golang that's high in antioxidants.
* [go-macaron/macaron](https://github.com/go-macaron/macaron) - Package macaron is a high productive and modular web framework in Go.
* [ant0ine/go-json-rest](https://github.com/ant0ine/go-json-rest) - A quick and easy way to setup a RESTful JSON API
* [justinas/alice](https://github.com/justinas/alice) - Painless middleware chaining for Go
* [mikestefanello/pagoda](https://github.com/mikestefanello/pagoda) - Rapid, easy full-stack web development starter kit and admin panel in Go
* [rs/cors](https://github.com/rs/cors) - Go net/http configurable handler to handle CORS requests
* [go-dev-frame/sponge](https://github.com/go-dev-frame/sponge) - A powerful and easy-to-use Go development framework that enables you to effortlessly build stable, reliable, and high-performance backend services with a "low-code" approach.
* [LyricTian/gin-admin](https://github.com/LyricTian/gin-admin) - A lightweight, flexible, elegant and full-featured RBAC scaffolding based on GIN + GORM 2.0 + Casbin 2.0 + Wire DI.基于 Golang + Gin + GORM 2.0 + Casbin 2.0 + Wire DI 的轻量级、灵活、优雅且功能齐全的 RBAC 脚手架。
* [alexedwards/scs](https://github.com/alexedwards/scs) - HTTP Session Management for Go
* [go-eagle/eagle](https://github.com/go-eagle/eagle) - 🦅 A Go framework for the API or Microservice
* [unrolled/secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [8treenet/freedom](https://github.com/8treenet/freedom) - Freedom是一个基于六边形架构的框架，可以支撑充血的领域模型范式。
* [gernest/utron](https://github.com/gernest/utron) - A lightweight MVC framework for Go(Golang) *(archived)*

### HTTP and Networking Clients

* [ccxt/ccxt](https://github.com/ccxt/ccxt) - A unified trading API with more than 100 crypto exchanges and prediction markets in JavaScript / TypeScript / Python / C# / PHP / Go / Java / Rust
* [go-resty/resty](https://github.com/go-resty/resty) - Simple HTTP, REST, and SSE client library for Go
* [google/go-github](https://github.com/google/go-github) - Go library for accessing the GitHub v3 API
* [asciimoo/wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection
* [tulir/whatsmeow](https://github.com/tulir/whatsmeow) - Go library for the WhatsApp web multidevice API
* [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) - (Golang) Go bindings for Discord
* [go-pay/gopay](https://github.com/go-pay/gopay) - 微信、支付宝、抖音、通联支付、拉卡拉、PayPal、Apple 的Go版本SDK。【极简、易用的聚合支付SDK】
* [eatmoreapple/openwechat](https://github.com/eatmoreapple/openwechat) - golang微信SDK
* [silenceper/wechat](https://github.com/silenceper/wechat) - WeChat SDK for Go （微信SDK：简单、易用）
* [slack-go/slack](https://github.com/slack-go/slack) - Slack API in Go
* [imroc/req](https://github.com/imroc/req) - Simple Go HTTP client with Black Magic
* [rs/curlie](https://github.com/rs/curlie) - The power of curl, the ease of use of httpie.
* [parnurzeal/gorequest](https://github.com/parnurzeal/gorequest) - GoRequest -- Simplified HTTP client ( inspired by nodejs SuperAgent )
* [gojek/heimdall](https://github.com/gojek/heimdall) - An enhanced HTTP client for Go
* [chanxuehong/wechat](https://github.com/chanxuehong/wechat) - weixin/wechat/微信公众平台/微信企业号/微信商户平台/微信支付 go/golang sdk
* [stripe/stripe-go](https://github.com/stripe/stripe-go) - Go library for the Stripe API.
* [astaxie/bat](https://github.com/astaxie/bat) - Go implement CLI, cURL-like tool for humans
* [xanzy/go-gitlab](https://github.com/xanzy/go-gitlab) - GitLab Go SDK *(archived)*
* [Rhymen/go-whatsapp](https://github.com/Rhymen/go-whatsapp) - WhatsApp Web API
* [levigross/grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library *(archived)*
* [kjk/notionapi](https://github.com/kjk/notionapi) - Unofficial Go API for Notion.so

### API and GraphQL

* [grpc-ecosystem/grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway) - gRPC to JSON proxy generator following the gRPC HTTP spec
* [swaggo/swag](https://github.com/swaggo/swag) - Automatically generate RESTful API documentation with Swagger 2.0 for Go.
* [99designs/gqlgen](https://github.com/99designs/gqlgen) - go generate based graphql server library
* [graphql-go/graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go / Golang
* [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go
* [oapi-codegen/oapi-codegen](https://github.com/oapi-codegen/oapi-codegen) - Generate Go client and server boilerplate from OpenAPI 3 specifications
* [goadesign/goa](https://github.com/goadesign/goa) - Design-first Go framework that generates API code, documentation, and clients. Define once in an elegant DSL, deploy as HTTP and gRPC services with zero drift between code and docs.
* [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use
* [prest/prest](https://github.com/prest/prest) - PostgreSQL ➕ REST, low-code, simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new, MCP server
* [getkin/kin-openapi](https://github.com/getkin/kin-openapi) - OpenAPI 3.0 and 3.1 and 3.2 (and Swagger v2) implementation for Go (parsing, converting, validation, and more)
* [dosco/graphjin](https://github.com/dosco/graphjin) - One governed graph for AI agents — GraphQL + MCP over your databases, files, APIs, and code
* [pksunkara/alpaca](https://github.com/pksunkara/alpaca) - Given a web API, Generate client libraries in node, php, python, ruby *(archived)*

### Web Servers and Proxies

* [fatedier/frp](https://github.com/fatedier/frp) - A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet.
* [caddyserver/caddy](https://github.com/caddyserver/caddy) - Fast and extensible multi-platform HTTP/1-2-3 web server with automatic HTTPS
* [traefik/traefik](https://github.com/traefik/traefik) - The Cloud Native Application Proxy
* [ehang-io/nps](https://github.com/ehang-io/nps) - 一款轻量级、高性能、功能强大的内网穿透代理服务器。支持tcp、udp、socks5、http等几乎所有流量转发，可用来访问内网网站、本地支付接口调试、ssh访问、远程桌面，内网dns解析、内网socks5代理等等……，并带有功能强大的web管理端。a lightweight, high-performance, powerful intranet penetration proxy server, with a powerful web management terminal.
* [valyala/fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http
* [snail007/goproxy](https://github.com/snail007/goproxy) - 🔥 Proxy is a high performance HTTP(S) proxies, SOCKS5 proxies,WEBSOCKET, TCP, UDP proxy server implemented by golang. Now, it supports chain-style proxies,nat forwarding in different lan,TCP/UDP port forwarding, SSH forwarding.Proxy是golang实现的高性能http,https,websocket,tcp,socks5代理服务器,支持内网穿透,链式代理,通讯加密,智能HTTP,SOCKS5代理,黑白名单,限速,限流量,限连接数,跨平台,KCP支持,认证API。
* [php/frankenphp](https://github.com/php/frankenphp) - 🧟 The modern PHP app server
* [TykTechnologies/tyk](https://github.com/TykTechnologies/tyk) - Tyk Open Source API Gateway written in Go, supporting REST, GraphQL, TCP and gRPC protocols
* [roadrunner-server/roadrunner](https://github.com/roadrunner-server/roadrunner) - 🤯 High-performance PHP application server, process manager written in Go and powered with plugins
* [cyfdecyf/cow](https://github.com/cyfdecyf/cow) - HTTP proxy written in Go. COW can automatically identify blocked sites and use parent proxies to access.
* [fabiolb/fabio](https://github.com/fabiolb/fabio) - Consul Load-Balancing made simple
* [luraproject/lura](https://github.com/luraproject/lura) - Ultra performant API Gateway with middlewares. A project hosted at The Linux Foundation
* [elazarl/goproxy](https://github.com/elazarl/goproxy) - An HTTP proxy library for Go
* [easegress-io/easegress](https://github.com/easegress-io/easegress) - A Cloud Native traffic orchestration system. (CNCF Project)
* [hacdias/webdav](https://github.com/hacdias/webdav) - A simple and standalone WebDAV server.
* [facebookarchive/grace](https://github.com/facebookarchive/grace) - Graceful restart & zero downtime deploy for Go servers. *(archived)*
* [fvbock/endless](https://github.com/fvbock/endless) - Zero downtime restarts for go servers (Drop in replacement for http.ListenAndServe)
* [yusing/godoxy](https://github.com/yusing/godoxy) - High-performance reverse proxy and container orchestrator for self-hosters
* [tus/tusd](https://github.com/tus/tusd) - Reference server implementation in Go of tus: the open protocol for resumable file uploads
* [zalando/skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress
* [fagongzi/manba](https://github.com/fagongzi/manba) - HTTP API Gateway
* [eolinker/goku_lite](https://github.com/eolinker/goku_lite) - A Powerful HTTP API Gateway in pure golang！Goku API Gateway （中文名：悟空 API 网关）是一个基于 Golang开发的微服务网关，能够实现高性能 HTTP API 转发、服务编排、多租户管理、API 访问权限控制等目的，拥有强大的自定义插件系统可以自行扩展，并且提供友好的图形化配置界面，能够快速帮助企业进行 API 服务治理、提高 API 服务的稳定性和安全性。
* [xyproto/algernon](https://github.com/xyproto/algernon) - Small self-contained pure-Go web server with Lua, Teal, Markdown, HTTP/2, QUIC, Redis, TypeScript, npm-less React 19, SQLite, and PostgreSQL support ++
* [motiv-labs/janus](https://github.com/motiv-labs/janus) - An API Gateway written in Go
* [envoyproxy/ratelimit](https://github.com/envoyproxy/ratelimit) - Go/gRPC service designed to enable generic rate limit scenarios from different types of applications.
* [vulcand/oxy](https://github.com/vulcand/oxy) - Go middlewares for HTTP servers & proxies
* [sipt/shuttle](https://github.com/sipt/shuttle) - A web proxy in Golang with amazing features.
* [rendora/rendora](https://github.com/rendora/rendora) - Dynamic server-side rendering using headless Chrome *(archived)*
* [yyyar/gobetween](https://github.com/yyyar/gobetween) - :cloud: Modern & minimalistic load balancer for the Сloud era

### Scraping and Crawling

* [gocolly/colly](https://github.com/gocolly/colly) - Elegant Scraper and Crawler Framework for Golang
* [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) - A little like that j-thing, only in Go.
* [crawlab-team/crawlab](https://github.com/crawlab-team/crawlab) - Distributed web crawler admin platform for spiders management regardless of languages and frameworks. 分布式爬虫管理平台，支持任何语言和框架
* [go-rod/rod](https://github.com/go-rod/rod) - A Chrome DevTools Protocol driver for web automation and scraping.
* [MontFerret/ferret](https://github.com/MontFerret/ferret) - Declarative data automation language and Go runtime for structured extraction workflows.
* [gosom/google-maps-scraper](https://github.com/gosom/google-maps-scraper) - scrape data from Google Maps. Extracts data such as the name, address, phone number, website URL, rating, reviews number, latitude and longitude, reviews,email and more for each place
* [mxschmitt/playwright-go](https://github.com/mxschmitt/playwright-go) - Playwright for Go a browser automation library to control Chromium, Firefox and WebKit with a single API.
* [jaeles-project/gospider](https://github.com/jaeles-project/gospider) - Gospider - Fast web spider written in Go
* [geziyor/geziyor](https://github.com/geziyor/geziyor) - Geziyor, blazing fast web crawling & scraping framework for Go. Supports JS rendering.
* [tebeka/selenium](https://github.com/tebeka/selenium) - Selenium/Webdriver client for Go
* [anaskhan96/soup](https://github.com/anaskhan96/soup) - Web Scraper in Go, similar to BeautifulSoup
* [PuerkitoBio/gocrawl](https://github.com/PuerkitoBio/gocrawl) - Polite, slim and concurrent web crawler.
* [hu17889/go_spider](https://github.com/hu17889/go_spider) - [爬虫框架 (golang)] An awesome Go concurrent Crawler(spider) framework. The crawler is flexible and modular. It can be expanded to an Individualized crawler easily or you can use the default crawl components only.

## Data and Storage

### Databases

* [pingcap/tidb](https://github.com/pingcap/tidb) - TiDB is built for agentic workloads that grow unpredictably, with ACID guarantees and native support for transactions, analytics, and vector search. No data silos. No noisy neighbors. No infrastructure ceiling.
* [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) - CockroachDB — the cloud native, distributed SQL database designed for high availability, effortless scale, and control over data placement.
* [influxdata/influxdb](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics
* [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) - high-performance graph database for real-time use cases
* [rqlite/rqlite](https://github.com/rqlite/rqlite) - The lightweight, fault-tolerant database built on SQLite. Designed to keep your data highly available with minimal effort.
* [dgraph-io/badger](https://github.com/dgraph-io/badger) - Fast key-value DB in Go.
* [cayleygraph/cayley](https://github.com/cayleygraph/cayley) - An open-source graph database
* [boltdb/bolt](https://github.com/boltdb/bolt) - An embedded key/value database for Go. *(archived)*
* [FerretDB/FerretDB](https://github.com/FerretDB/FerretDB) - A truly Open Source MongoDB alternative
* [etcd-io/bbolt](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
* [codenotary/immudb](https://github.com/codenotary/immudb) - immudb - immutable database based on zero trust, SQL/Key-Value/Document model, tamperproof, data change history
* [syndtr/goleveldb](https://github.com/syndtr/goleveldb) - LevelDB key/value database in Go.
* [cockroachdb/pebble](https://github.com/cockroachdb/pebble) - RocksDB/LevelDB inspired key-value database in Go
* [rosedblabs/rosedb](https://github.com/rosedblabs/rosedb) - Lightweight, fast and reliable key/value storage engine based on Bitcask.
* [tidwall/buntdb](https://github.com/tidwall/buntdb) - BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support
* [ledisdb/ledisdb](https://github.com/ledisdb/ledisdb) - A high performance NoSQL Database Server powered by Go
* [HDT3213/godis](https://github.com/HDT3213/godis) - A Golang implemented Redis Server and Cluster. Go 语言实现的 Redis 服务器和分布式集群
* [nutsdb/nutsdb](https://github.com/nutsdb/nutsdb) - A simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
* [hashicorp/go-memdb](https://github.com/hashicorp/go-memdb) - Golang in-memory database built on immutable radix trees
* [lindb/lindb](https://github.com/lindb/lindb) - LinDB is a scalable, high performance, high availability distributed time series database.
* [HouzuoGuo/tiedot](https://github.com/HouzuoGuo/tiedot) - A rudimentary implementation of a basic document (NoSQL) database in Go
* [dolthub/go-mysql-server](https://github.com/dolthub/go-mysql-server) - A MySQL-compatible relational database with a storage agnostic query engine. Implemented in Go.
* [FeatureBaseDB/featurebase](https://github.com/FeatureBaseDB/featurebase) - A crazy fast analytical database, built on bitmaps. Perfect for ML applications. Learn more at: http://docs.featurebase.com/. Start a Docker instance: https://hub.docker.com/r/featurebasedb/featurebase *(archived)*
* [tidwall/redcon](https://github.com/tidwall/redcon) - Redis compatible server framework for Go
* [src-d/gitbase](https://github.com/src-d/gitbase) - SQL interface to git repositories, written in Go. https://docs.sourced.tech/gitbase

### Database Clients and ORMs

* [go-gorm/gorm](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly
* [redis/go-redis](https://github.com/redis/go-redis) - Redis Go client
* [golang-migrate/migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* [sqlc-dev/sqlc](https://github.com/sqlc-dev/sqlc) - Generate type-safe code from SQL
* [ent/ent](https://github.com/ent/ent) - An entity framework for Go
* [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - Go MySQL Driver is a MySQL driver for Go's (golang) database/sql package
* [jackc/pgx](https://github.com/jackc/pgx) - PostgreSQL driver and toolkit for Go
* [pressly/goose](https://github.com/pressly/goose) - A database migration tool. Supports SQL migrations and Go functions.
* [xo/usql](https://github.com/xo/usql) - Universal command-line interface for SQL databases
* [lib/pq](https://github.com/lib/pq) - Go PostgreSQL driver for database/sql
* [gomodule/redigo](https://github.com/gomodule/redigo) - Go client for Redis
* [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - The Official Golang driver for MongoDB
* [olivere/elastic](https://github.com/olivere/elastic) - Deprecated: Use the official Elasticsearch client for Go at https://github.com/elastic/go-elasticsearch
* [amacneil/dbmate](https://github.com/amacneil/dbmate) - 🚀 A lightweight, framework-agnostic database migration tool.
* [aarondl/sqlboiler](https://github.com/aarondl/sqlboiler) - Generate a Go ORM tailored to your database schema.
* [go-xorm/xorm](https://github.com/go-xorm/xorm) - Simple and Powerful ORM for Go, support mysql,postgres,tidb,sqlite3,mssql,oracle, Moved to https://gitea.com/xorm/xorm *(archived)*
* [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) - The official Go client for Elasticsearch
* [go-pg/pg](https://github.com/go-pg/pg) - Golang ORM with focus on PostgreSQL features and performance
* [uptrace/bun](https://github.com/uptrace/bun) - SQL-first Golang ORM
* [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) - a powerful mysql toolset with Go
* [k1LoW/tbls](https://github.com/k1LoW/tbls) - tbls is a CI-Friendly tool to document a database, written in Go.
* [wal-g/wal-g](https://github.com/wal-g/wal-g) - Archival and Restoration for databases in the Cloud
* [xo/dbtpl](https://github.com/xo/dbtpl) - Command line tool to generate idiomatic Go code for SQL databases supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server
* [go-gorp/gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence - an ORM-ish library for Go
* [upper/db](https://github.com/upper/db) - Data Access Layer (DAL) for PostgreSQL, CockroachDB, MySQL, SQLite and MongoDB with ORM-like features.
* [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) - SQL schema migration tool for Go.
* [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) - Golang driver for ClickHouse
* [redis/rueidis](https://github.com/redis/rueidis) - A fast Golang Redis client that supports Client Side Caching, Auto Pipelining, RDMA, etc.
* [go-mgo/mgo](https://github.com/go-mgo/mgo) - The MongoDB driver for Go. UNMAINTAINED - SEE BELOW
* [apache/cassandra-gocql-driver](https://github.com/apache/cassandra-gocql-driver) - GoCQL Driver for Apache Cassandra®
* [doug-martin/goqu](https://github.com/doug-martin/goqu) - SQL builder and query library for golang
* [xxjwxc/gormt](https://github.com/xxjwxc/gormt) - database to golang struct
* [mattes/migrate](https://github.com/mattes/migrate) - Database migrations. CLI and Golang library. *(archived)*
* [steebchen/prisma-client-go](https://github.com/steebchen/prisma-client-go) - Prisma Client Go is an auto-generated and fully type-safe database client *(archived)*
* [gocraft/dbr](https://github.com/gocraft/dbr) - Additions to Go's database/sql for super fast performance and convenience.

### Serialization and Formats

* [qax-os/excelize](https://github.com/qax-os/excelize) - Go language library for reading and writing Microsoft Excel™ (XLAM / XLSM / XLSX / XLTM / XLTX) spreadsheets
* [tidwall/gjson](https://github.com/tidwall/gjson) - Get JSON values quickly - JSON parser for Go
* [json-iterator/go](https://github.com/json-iterator/go) - A high-performance 100% compatible drop-in replacement of "encoding/json" *(archived)*
* [wader/fq](https://github.com/wader/fq) - fq - jq for binary formats. Tool, language and decoders for working with binary formats.
* [golang/protobuf](https://github.com/golang/protobuf) - Go support for Google's protocol buffers
* [TomWright/dasel](https://github.com/TomWright/dasel) - Unified querying, transformation, and modification of JSON, TOML, YAML, XML, INI, HCL, KDL and CSV.
* [mitchellh/mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures and vice versa. *(archived)*
* [go-yaml/yaml](https://github.com/go-yaml/yaml) - YAML support for the Go language. *(archived)*
* [tealeg/xlsx](https://github.com/tealeg/xlsx) - Go library for reading and writing XLSX files. *(archived)*
* [gogo/protobuf](https://github.com/gogo/protobuf) - [Deprecated] Protocol Buffers for Go with Gadgets
* [buger/jsonparser](https://github.com/buger/jsonparser) - THE fastest alternative JSON parser for Go that does not require schema
* [unidoc/unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents
* [jung-kurt/gofpdf](https://github.com/jung-kurt/gofpdf) - A PDF document generator with high level support for text, drawing and images *(archived)*
* [itchyny/gojq](https://github.com/itchyny/gojq) - Pure Go implementation of jq
* [bitly/go-simplejson](https://github.com/bitly/go-simplejson) - a Go package to interact with arbitrary JSON
* [goccy/go-json](https://github.com/goccy/go-json) - Fast JSON encoder/decoder compatible with encoding/json for Go
* [Jeffail/gabs](https://github.com/Jeffail/gabs) - For parsing, creating and editing unknown or dynamic JSON in Go
* [protocolbuffers/protobuf-go](https://github.com/protocolbuffers/protobuf-go) - Go support for Google's protocol buffers
* [pquerna/ffjson](https://github.com/pquerna/ffjson) - faster JSON serialization for Go
* [mmcdole/gofeed](https://github.com/mmcdole/gofeed) - Parse RSS, Atom and JSON feeds in Go
* [pseudomuto/protoc-gen-doc](https://github.com/pseudomuto/protoc-gen-doc) - Documentation generator plugin for Google Protocol Buffers
* [tidwall/sjson](https://github.com/tidwall/sjson) - Set JSON values very quickly in Go
* [xeipuuv/gojsonschema](https://github.com/xeipuuv/gojsonschema) - An implementation of JSON Schema, draft v4 v6 & v7 - Go language
* [ChimeraCoder/gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON
* [vmihailenco/msgpack](https://github.com/vmihailenco/msgpack) - msgpack.org[Go] MessagePack encoding for Golang
* [valyala/fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection
* [thedevsaddam/gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package for querying over JSON, YAML, XML, and CSV data.
* [francoispqt/gojay](https://github.com/francoispqt/gojay) - high performance JSON encoder/decoder with stream API for Golang

### Caching and Queues

* [nsqio/nsq](https://github.com/nsqio/nsq) - A realtime distributed messaging platform
* [hibiken/asynq](https://github.com/hibiken/asynq) - Simple, reliable, and efficient distributed task queue in Go
* [CodisLabs/codis](https://github.com/CodisLabs/codis) - Proxy based Redis cluster solution supporting pipeline and scaling dynamically
* [IBM/sarama](https://github.com/IBM/sarama) - Sarama is a Go library for Apache Kafka.
* [patrickmn/go-cache](https://github.com/patrickmn/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [redpanda-data/connect](https://github.com/redpanda-data/connect) - Fancy stream processing made operationally mundane
* [segmentio/kafka-go](https://github.com/segmentio/kafka-go) - Kafka library in Go
* [allegro/bigcache](https://github.com/allegro/bigcache) - Efficient cache for gigabytes of data written in Go.
* [RichardKnop/machinery](https://github.com/RichardKnop/machinery) - Machinery is an asynchronous task queue/job queue based on distributed message passing.
* [dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) - A high performance memory-bound Go cache
* [riverqueue/river](https://github.com/riverqueue/river) - Fast and reliable background jobs in Go
* [coocood/freecache](https://github.com/coocood/freecache) - A cache library for Go with zero GC overhead.
* [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) - Confluent's Apache Kafka Golang client
* [hashicorp/golang-lru](https://github.com/hashicorp/golang-lru) - Golang LRU cache
* [travisjeffery/jocko](https://github.com/travisjeffery/jocko) - Kafka implemented in Golang with built-in coordination (No ZK dep, single binary install, Cloud Native)
* [streadway/amqp](https://github.com/streadway/amqp) - Go client for AMQP 0.9.1
* [olric-data/olric](https://github.com/olric-data/olric) - Distributed, in-memory key/value store and cache. It can be used as an embedded Go library and a language-independent service.
* [twmb/franz-go](https://github.com/twmb/franz-go) - franz-go is a feature complete, pure Go library for Kafka from 0.8.0 through 4.2+. Producing, consuming, transacting, administrating, etc.
* [eko/gocache](https://github.com/eko/gocache) - ☔️ A complete Go cache library that brings you multiple ways of managing your caches
* [benmanns/goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker that runs 10 to 100,000* times faster than Ruby-based workers.
* [liftbridge-io/liftbridge](https://github.com/liftbridge-io/liftbridge) - Kafka-style message streaming in Go. Built on NATS. Single binary, no JVM, no ZooKeeper.
* [bluele/gcache](https://github.com/bluele/gcache) - An in-memory cache library for golang. It supports multiple eviction policies: LRU, LFU, ARC
* [nsqio/go-nsq](https://github.com/nsqio/go-nsq) - The official Go package for NSQ
* [lovoo/goka](https://github.com/lovoo/goka) - Goka is a compact yet powerful distributed stream processing library for Apache Kafka written in Go.
* [gocraft/work](https://github.com/gocraft/work) - Process background jobs in Go
* [gocelery/gocelery](https://github.com/gocelery/gocelery) - Celery Distributed Task Queue in Go
* [bilibili/overlord](https://github.com/bilibili/overlord) - Overlord是哔哩哔哩基于Go语言编写的memcache和redis&cluster的代理及集群管理功能，致力于提供自动化高可用的缓存服务解决方案。
* [muesli/cache2go](https://github.com/muesli/cache2go) - Concurrency-safe Go caching library with expiration capabilities and access counters

## Machine Learning and AI

### LLM and Inference

* [ollama/ollama](https://github.com/ollama/ollama) - Get up and running with Kimi-K2.6, GLM-5.2, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models.
* [cloudwego/eino](https://github.com/cloudwego/eino) - The ultimate LLM/AI application development framework in Go.
* [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) - OpenAI, GPT 5.6, GPT-Image-2, Whisper API clients for Go
* [tmc/langchaingo](https://github.com/tmc/langchaingo) - LangChain for Go, the easiest way to write LLM-based programs in Go
* [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) - A Go implementation of the Model Context Protocol (MCP), enabling seamless integration between LLM applications and external data sources and tools.
* [google/adk-go](https://github.com/google/adk-go) - An open-source, code-first Go toolkit for building, evaluating, and deploying sophisticated AI agents with flexibility and control.
* [qualcomm/GenieX](https://github.com/qualcomm/GenieX) - Run frontier LLMs and VLMs locally on Qualcomm devices across NPU, GPU, and CPU with a few lines of code
* [YaoApp/yao](https://github.com/YaoApp/yao) - ✨ All your agents and workspaces in one place, on every device you own. Track tasks on a board, accessible from desktop, mobile, browser, or API. Self-hosted.
* [tbphp/gpt-load](https://github.com/tbphp/gpt-load) - Self-hosted AI gateway for multi-channel, multi-credential setups — API keys and subscription accounts, scheduling, failover, request logs and usage. 自托管 AI 网关：多渠道多凭据统一接入，含密钥与订阅账号、调度容错、日志与用量。
* [Gentleman-Programming/engram](https://github.com/Gentleman-Programming/engram) - Persistent memory system for AI coding agents. Agent-agnostic Go binary with SQLite + FTS5, MCP server, HTTP API, CLI, and TUI.
* [fengshao1227/ccg-workflow](https://github.com/fengshao1227/ccg-workflow) - 多模型协作工作流引擎 — /ccg:go 一个命令，AI 自动分析意图、选择策略、编排 Codex + Gemini + Claude 协作执行
* [ConnectAI-E/feishu-openai](https://github.com/ConnectAI-E/feishu-openai) - 🎒 飞书 ×（GPT-4 + GPT-4V + DALL·E-3 + Whisper）= 飞一般的工作体验 🚀 语音对话、角色扮演、多话题讨论、图片创作、表格分析、文档导出 🚀
* [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk) - The official Go SDK for Model Context Protocol servers and clients. Maintained in collaboration with Google.
* [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api) - DeepSeek-Compatible Middleware Interface: A technical exploration project in Go, focusing on high-concurrency protocol adaptation. It serves as a reference implementation for converting diverse web protocols into standardized formats. *(archived)*
* [53AI/53AIHub](https://github.com/53AI/53AIHub) - 53AI Hub is an open-source AI portal and knowledge base for managing enterprise knowledge, AI agents, prompts, and AI tools, seamlessly integrating with Coze, Dify, FastGPT, RAGFlow. 一个AI知识库与Agent门户
* [nextlevelbuilder/goclaw](https://github.com/nextlevelbuilder/goclaw) - GoClaw - GoClaw is OpenClaw rebuilt in Go — with multi-tenant isolation, 5-layer security, and native concurrency. Deploy AI agent teams at scale without compromising on safety.
* [openai/openai-go](https://github.com/openai/openai-go) - The official Go library for the OpenAI API
* [aandrew-me/tgpt](https://github.com/aandrew-me/tgpt) - AI Chatbots in terminal for free

### Data Science and Analytics

* [go-echarts/go-echarts](https://github.com/go-echarts/go-echarts) - 🎨 The adorable charts library for Golang.
* [cloudquery/cloudquery](https://github.com/cloudquery/cloudquery) - Data pipelines for cloud config and security data. Build cloud asset inventory, CSPM, FinOps, and vulnerability management solutions. Extract from AWS, Azure, GCP, and 70+ cloud and SaaS sources.
* [pachyderm/pachyderm](https://github.com/pachyderm/pachyderm) - Data-Centric Pipelines and Data Versioning
* [treeverse/lakeFS](https://github.com/treeverse/lakeFS) - lakeFS - Data version control for your data lake | Git for data
* [cube2222/octosql](https://github.com/cube2222/octosql) - OctoSQL is a query tool that allows you to join, analyse and transform data from multiple databases and file formats using SQL.
* [rudderlabs/rudder-server](https://github.com/rudderlabs/rudder-server) - Privacy and Security focused Segment-alternative, in Golang and React
* [go-mysql-org/go-mysql-elasticsearch](https://github.com/go-mysql-org/go-mysql-elasticsearch) - Sync MySQL data into elasticsearch
* [wcharczuk/go-chart](https://github.com/wcharczuk/go-chart) - go chart is a basic charting library in go. *(archived)*
* [gopherdata/gophernotes](https://github.com/gopherdata/gophernotes) - The Go kernel for Jupyter notebooks and nteract.
* [go-gota/gota](https://github.com/go-gota/gota) - Gota: DataFrames and data wrangling in Go (Golang) *(archived)*

## Networking and Distributed

### Networking

* [XIU2/CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) - 🌩「自选优选 IP」测试 Cloudflare CDN 延迟和速度，获取最快 IP ！当然也支持其他 CDN / 多个解析 IP 的网站 ~
* [gorilla/websocket](https://github.com/gorilla/websocket) - Package gorilla/websocket is a fast, well-tested and widely used WebSocket implementation for Go.
* [ginuerzh/gost](https://github.com/ginuerzh/gost) - GO Simple Tunnel - a simple tunnel written in golang
* [jeessy2/ddns-go](https://github.com/jeessy2/ddns-go) - Simple and easy to use DDNS. Support Aliyun, Tencent Cloud, Dnspod, Cloudflare, Callback, Huawei Cloud, Baidu Cloud, Porkbun, GoDaddy, Namecheap, NameSilo...
* [pion/webrtc](https://github.com/pion/webrtc) - Pure Go implementation of the WebRTC API
* [passteque/gluetun](https://github.com/passteque/gluetun) - VPN client in a thin Docker container for multiple VPN providers, written in Go, and using OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in.
* [coredns/coredns](https://github.com/coredns/coredns) - CoreDNS is a DNS server that chains plugins
* [quic-go/quic-go](https://github.com/quic-go/quic-go) - A production-ready QUIC implementation in pure Go
* [panjf2000/gnet](https://github.com/panjf2000/gnet) - 🚀 gnet is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
* [gcla/termshark](https://github.com/gcla/termshark) - A terminal UI for tshark, inspired by Wireshark
* [flannel-io/flannel](https://github.com/flannel-io/flannel) - flannel is a network fabric for containers, designed for Kubernetes
* [miekg/dns](https://github.com/miekg/dns) - DNS library in Go
* [p4gefau1t/trojan-go](https://github.com/p4gefau1t/trojan-go) - Go实现的Trojan代理，支持多路复用/路由功能/CDN中转/Shadowsocks混淆插件，多平台，无依赖。A Trojan proxy written in Go. An unidentifiable mechanism that helps you bypass GFW. https://p4gefau1t.github.io/trojan-go/
* [aceld/zinx](https://github.com/aceld/zinx) - A lightweight concurrent server framework based on Golang.
* [go-gost/gost](https://github.com/go-gost/gost) - GO Simple Tunnel - a simple tunnel written in golang
* [libp2p/go-libp2p](https://github.com/libp2p/go-libp2p) - libp2p implementation in Go
* [google/gopacket](https://github.com/google/gopacket) - Provides packet processing capabilities for Go
* [shadowsocks/shadowsocks-go](https://github.com/shadowsocks/shadowsocks-go) - go port of shadowsocks (Deprecated) *(archived)*
* [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip) - 🌚 🌍 🌝 GeoIP 增强版，自由定制多种格式 GeoIP 文件，包括但不限于 V2Ray dat 格式文件 geoip.dat、MaxMind mmdb 格式文件、sing-box SRS 格式文件、mihomo MRS 格式文件、Clash ruleset、Surge ruleset、Nginx allow & deny 规则文件等。Enhanced edition of GeoIP for Nginx, V2Ray, Xray-core, Clash, mihomo, sing-box, Shadowrocket, Quantumult X, Surge, hysteria, Trojan-Go, dae, etc.
* [gobwas/ws](https://github.com/gobwas/ws) - A tiny WebSocket library for Go.
* [anacrolix/torrent](https://github.com/anacrolix/torrent) - Full-featured BitTorrent client package and utilities
* [tidwall/evio](https://github.com/tidwall/evio) - Fast event-loop networking for Go
* [googollee/go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. *(archived)*
* [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks) - tun2socks - powered by gVisor TCP/IP stack
* [coder/websocket](https://github.com/coder/websocket) - Minimal and idiomatic WebSocket library for Go
* [yggdrasil-network/yggdrasil-go](https://github.com/yggdrasil-network/yggdrasil-go) - An experiment in scalable routing as an encrypted IPv6 overlay network
* [xvzc/spoofdpi](https://github.com/xvzc/spoofdpi) - Simple and fast anti-censorship tool written in Go
* [fiorix/freegeoip](https://github.com/fiorix/freegeoip) - IP geolocation web server
* [go-gomail/gomail](https://github.com/go-gomail/gomail) - The best way to send emails in Go.
* [xtaci/kcp-go](https://github.com/xtaci/kcp-go) - A crypto-secure Reliable-UDP library for Golang with FEC support.
* [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go) - Mirror only. Official repository is at https://git.zx2c4.com/wireguard-go
* [mpolden/echoip](https://github.com/mpolden/echoip) - A simple IP address lookup service.
* [coyove/goflyway](https://github.com/coyove/goflyway) - An encrypted HTTP server
* [osrg/gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language
* [olahol/melody](https://github.com/olahol/melody) - :notes: Minimalist websocket framework for Go
* [ionorg/ion](https://github.com/ionorg/ion) - Real-Distributed RTC System by pure Go and Flutter *(archived)*
* [nadoo/glider](https://github.com/nadoo/glider) - glider is a forward proxy with multiple protocols support, and also a dns/dhcp server with ipset management features.
* [pgrok/pgrok](https://github.com/pgrok/pgrok) - Poor man's ngrok - a multi-tenant HTTP/TCP reverse tunnel solution through SSH remote port forwarding
* [mmatczuk/go-http-tunnel](https://github.com/mmatczuk/go-http-tunnel) - Fast and secure tunnels over HTTP/2
* [ergochat/ergo](https://github.com/ergochat/ergo) - A modern IRC server (daemon/ircd) written in Go.
* [vishvananda/netlink](https://github.com/vishvananda/netlink) - Simple netlink library for go.
* [golang/net](https://github.com/golang/net) - [mirror] Go supplementary network libraries
* [flashmob/go-guerrilla](https://github.com/flashmob/go-guerrilla) - Mini SMTP server written in golang
* [jordan-wright/email](https://github.com/jordan-wright/email) - Robust and flexible email library for Go
* [rtr7/router7](https://github.com/rtr7/router7) - router7 is a small home internet router completely written in Go. It is implemented as a gokrazy appliance.
* [yann-shi/dht](https://github.com/yann-shi/dht) - BitTorrent DHT Protocol && DHT Spider.
* [lesismal/nbio](https://github.com/lesismal/nbio) - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
* [go-ldap/ldap](https://github.com/go-ldap/ldap) - Basic LDAP v3 functionality for the GO programming language.
* [40t/go-sniffer](https://github.com/40t/go-sniffer) - 🔎Sniffing and parsing mysql,redis,http,mongodb etc protocol. 抓包截取项目中的数据库请求并解析成相应的语句。
* [perlin-network/noise](https://github.com/perlin-network/noise) - A decentralized P2P networking stack written in Go.
* [brutella/hc](https://github.com/brutella/hc) - hc is a lightweight framework to develop HomeKit accessories in Go.

### RPC and Messaging

* [micro/go-micro](https://github.com/micro/go-micro) - A Go agent harness and service framework
* [grpc/grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC
* [nats-io/nats-server](https://github.com/nats-io/nats-server) - High-Performance server for NATS.io, the cloud and edge native messaging system.
* [openimsdk/open-im-server](https://github.com/openimsdk/open-im-server) - IM Chat OpenClaw
* [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) - Building event-driven applications the easy way in Go.
* [smallnest/rpcx](https://github.com/smallnest/rpcx) - Best microservices framework in Go, like alibaba Dubbo, but with more features, Scale easily. Try it. Test it. If you feel it's better, use it! 𝐉𝐚𝐯𝐚有𝐝𝐮𝐛𝐛𝐨, 𝐆𝐨𝐥𝐚𝐧𝐠有𝐫𝐩𝐜𝐱! build for cloud!
* [cloudwego/kitex](https://github.com/cloudwego/kitex) - Go RPC framework with high-performance and strong-extensibility for building micro-services.
* [twitchtv/twirp](https://github.com/twitchtv/twirp) - A simple RPC framework with protobuf service definitions
* [grpc-ecosystem/go-grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware) - Golang gRPC Middlewares: interceptor chaining, auth, logging, retries and more.
* [nats-io/nats.go](https://github.com/nats-io/nats.go) - Golang client for NATS, the cloud native messaging system.
* [hashicorp/go-plugin](https://github.com/hashicorp/go-plugin) - Golang plugin system over RPC.
* [apache/dubbo-go](https://github.com/apache/dubbo-go) - Go Implementation For Apache Dubbo .
* [connectrpc/connect-go](https://github.com/connectrpc/connect-go) - The Go implementation of Connect: Protobuf RPC that works.
* [apache/dubbo-admin](https://github.com/apache/dubbo-admin) - The ops and reference implementation for Apache Dubbo.
* [emitter-io/emitter](https://github.com/emitter-io/emitter) - High performance, distributed and low latency publish-subscribe platform.
* [nikoksr/notify](https://github.com/nikoksr/notify) - A dead simple Go library for sending notifications to various messaging services.
* [juggleim/im-server](https://github.com/juggleim/im-server) - IM Chat, High-performance, scalable, self-hosted instant messaging server in Go — private chat, groups, chatrooms, WebSocket and REST APIs.
* [TarsCloud/TarsGo](https://github.com/TarsCloud/TarsGo) - A high performance microservice framework in golang. A linux foundation project.
* [koding/kite](https://github.com/koding/kite) - Micro-service framework in Go
* [sideshow/apns2](https://github.com/sideshow/apns2) - ⚡ HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol.
* [link1st/gowebsocket](https://github.com/link1st/gowebsocket) - golang基于websocket单台机器支持百万连接分布式聊天(IM)系统
* [LockGit/gochat](https://github.com/LockGit/gochat) - goim server write by golang !🚀
* [go-chassis/go-chassis](https://github.com/go-chassis/go-chassis) - a cloud native application framework for Go with rich eco-system
* [andeya/erpc](https://github.com/andeya/erpc) - An efficient, extensible and easy-to-use RPC framework.
* [docker-archive-public/docker.libchan](https://github.com/docker-archive-public/docker.libchan) - Like Go channels over the network *(archived)*
* [Terry-Mao/gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - Golang push server cluster
* [GoBelieveIO/im_service](https://github.com/GoBelieveIO/im_service) - golang im server
* [bufbuild/connect-go](https://github.com/bufbuild/connect-go) - Moved to https://github.com/connectrpc/connect-go *(archived)*

### Distributed Systems

* [etcd-io/etcd](https://github.com/etcd-io/etcd) - Distributed reliable key-value store for the most critical data of a distributed system
* [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) - Go implementation of the Ethereum protocol
* [ipfs/kubo](https://github.com/ipfs/kubo) - IPFS implementation in Go: a daemon that stores and serves content-addressed data, with a CLI, HTTP Gateway, and RPC API
* [canopy-network/canopy](https://github.com/canopy-network/canopy) - The official go implementation of the Canopy Network protocol
* [dtm-labs/dtm](https://github.com/dtm-labs/dtm) - A distributed transaction framework, supports workflow, saga, tcc, xa, 2-phase message, outbox patterns, supports many languages.
* [IBAX-io/go-ibax](https://github.com/IBAX-io/go-ibax) - An innovative Blockchain Protocol Platform, which everyone can deploy their own applications quickly and easily, such as Dapp, DeFi, DAO, Cross-Blockchain transactions, etc.
* [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) - Framework for building performant, customizable blockchains with native interoperability
* [btcsuite/btcd](https://github.com/btcsuite/btcd) - An alternative full node bitcoin implementation written in Go (golang)
* [tendermint/tendermint](https://github.com/tendermint/tendermint) - ⟁ Tendermint Core (BFT Consensus) in Go
* [lni/dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
* [Consensys-Incorporated/quorum](https://github.com/Consensys-Incorporated/quorum) - A permissioned implementation of Ethereum supporting data privacy *(archived)*
* [afex/hystrix-go](https://github.com/afex/hystrix-go) - Netflix's Hystrix latency and fault tolerance library, for Go
* [sjqzhang/go-fastdfs](https://github.com/sjqzhang/go-fastdfs) - go-fastdfs 是一个简单的分布式文件系统(私有云存储)，具有无中心、高性能，高可靠，免维护等优点，支持断点续传，分块上传，小文件合并，自动同步，自动修复。Go-fastdfs is a simple distributed file system (private cloud storage), with no center, high performance, high reliability, maintenance free and other advantages, support breakpoint continuation, block upload, small file merge, automatic synchronization, automatic repair.(similar fastdfs).
* [go-redsync/redsync](https://github.com/go-redsync/redsync) - Distributed mutual exclusion lock using Redis for Go
* [OffchainLabs/prysm](https://github.com/OffchainLabs/prysm) - Go implementation of Ethereum proof of stake
* [chrislusf/gleam](https://github.com/chrislusf/gleam) - Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly.
* [bnb-chain/bsc](https://github.com/bnb-chain/bsc) - A BNB Smart Chain client based on the go-ethereum fork
* [chrislusf/glow](https://github.com/chrislusf/glow) - Glow is an easy-to-use distributed computation system written in Go, similar to Hadoop Map Reduce, Spark, Flink, Storm, etc. I am also working on another similar pure Go system, https://github.com/chrislusf/gleam , which is more flexible and more performant.
* [filecoin-project/lotus](https://github.com/filecoin-project/lotus) - Reference implementation of the Filecoin protocol, written in Go
* [alibaba/sentinel-golang](https://github.com/alibaba/sentinel-golang) - Sentinel Go enables reliability and resiliency for Go microservices
* [goraft/raft](https://github.com/goraft/raft) - UNMAINTAINED: A Go implementation of the Raft distributed consensus protocol. *(archived)*
* [dominant-strategies/go-quai](https://github.com/dominant-strategies/go-quai) - Official Go Implementation of the Quai Network
* [atomix/atomix](https://github.com/atomix/atomix) - A Kubernetes toolkit for building distributed applications using cloud native principles
* [ava-labs/avalanchego](https://github.com/ava-labs/avalanchego) - Go implementation of an Avalanche node.
* [OdyseeTeam/chainquery](https://github.com/OdyseeTeam/chainquery) - Chainquery parses and syncs the LBRY blockchain data into structured SQL
* [filecoin-project/venus](https://github.com/filecoin-project/venus) - Filecoin Full Node Implementation in Go
* [skynetservices/skynet-archive](https://github.com/skynetservices/skynet-archive) - Skynet is a framework for distributed services in Go. *(archived)*

### Cloud and Infrastructure

* [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) - Production-Grade Container Scheduling and Management
* [moby/moby](https://github.com/moby/moby) - The Moby Project - a collaborative project for the container ecosystem to assemble container-based systems
* [minio/minio](https://github.com/minio/minio) - MinIO is a high-performance, S3 compatible object store, open sourced under GNU AGPLv3 license. *(archived)*
* [harness/harness](https://github.com/harness/harness) - Harness Open Source is an end-to-end developer platform with Source Control Management, CI/CD Pipelines, Hosted Developer Environments, and Artifact Registries.
* [docker/compose](https://github.com/docker/compose) - Define and run multi-container applications with Docker
* [derailed/k9s](https://github.com/derailed/k9s) - 🐶 Kubernetes CLI To Manage Your Clusters In Style!
* [kubernetes/minikube](https://github.com/kubernetes/minikube) - Run Kubernetes locally
* [pulumi/pulumi](https://github.com/pulumi/pulumi) - Pulumi - Infrastructure as Code in any programming language 🚀
* [slimtoolkit/slim](https://github.com/slimtoolkit/slim) - Slim(toolkit): Don't change anything in your container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source)
* [kubernetes/kops](https://github.com/kubernetes/kops) - Kubernetes Operations (kOps) - Production Grade k8s Installation, Upgrades and Management
* [coder/coder](https://github.com/coder/coder) - Secure environments for developers and their agents
* [semaphoreui/semaphore](https://github.com/semaphoreui/semaphore) - Modern UI and powerful API for Ansible, Terraform/OpenTofu/Terragrunt, PowerShell and other DevOps tools.
* [encoredev/encore](https://github.com/encoredev/encore) - The infrastructure platform for the intelligence era
* [siderolabs/talos](https://github.com/siderolabs/talos) - Talos Linux is a modern Linux distribution built for Kubernetes.
* [kubernetes/kompose](https://github.com/kubernetes/kompose) - Convert Compose to Kubernetes
* [moby/buildkit](https://github.com/moby/buildkit) - concurrent, cache-efficient, and Dockerfile-agnostic builder toolkit
* [google/go-cloud](https://github.com/google/go-cloud) - The Go Cloud Development Kit (Go CDK): A library and tools for open cloud development in Go.
* [kubernetes/client-go](https://github.com/kubernetes/client-go) - Go client for Kubernetes.
* [runatlantis/atlantis](https://github.com/runatlantis/atlantis) - Terraform Pull Request Automation
* [fission/fission](https://github.com/fission/fission) - Fast and Simple Serverless Functions for Kubernetes
* [rkt/rkt](https://github.com/rkt/rkt) - [Project ended] rkt is a pod-native container engine for Linux. It is composable, secure, and built on standards. *(archived)*
* [openshift/origin](https://github.com/openshift/origin) - Conformance test suite for OpenShift
* [aws/aws-sdk-go](https://github.com/aws/aws-sdk-go) - This SDK has reached end-of-support. The AWS SDK for Go v2 is available here: https://github.com/aws/aws-sdk-go-v2 *(archived)*
* [ko-build/ko](https://github.com/ko-build/ko) - Build and deploy Go applications
* [concourse/concourse](https://github.com/concourse/concourse) - Concourse is a container-based automation system written in Go. It's mostly used for CI/CD.
* [alexellis/k3sup](https://github.com/alexellis/k3sup) - bootstrap K3s over SSH in < 60s 🚀
* [getarcaneapp/arcane](https://github.com/getarcaneapp/arcane) - Modern Docker Management, Designed for Everyone
* [superplanehq/superplane](https://github.com/superplanehq/superplane) - Open source factory for one-shot engineering
* [agones-dev/agones](https://github.com/agones-dev/agones) - Dedicated Game Server Hosting and Scaling for Multiplayer Games on Kubernetes
* [weaveworks/weave](https://github.com/weaveworks/weave) - Simple, resilient multi-host containers networking and more. *(archived)*
* [k3d-io/k3d](https://github.com/k3d-io/k3d) - Little helper to run CNCF's k3s in Docker
* [derailed/popeye](https://github.com/derailed/popeye) - 👀 A Kubernetes cluster resource sanitizer
* [vmware-archive/octant](https://github.com/vmware-archive/octant) - Highly extensible platform for developers to better understand the complexity of Kubernetes clusters. *(archived)*
* [lxc/incus](https://github.com/lxc/incus) - Powerful system container and virtual machine manager
* [nuclio/nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform
* [tsuru/tsuru](https://github.com/tsuru/tsuru) - Open source and extensible Platform as a Service (PaaS).
* [gaia-pipeline/gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language. *(archived)*
* [jwilder/dockerize](https://github.com/jwilder/dockerize) - Utility to simplify running applications in docker containers
* [nginx/kubernetes-ingress](https://github.com/nginx/kubernetes-ingress) - NGINX and NGINX Plus Ingress Controllers for Kubernetes
* [canonical/lxd](https://github.com/canonical/lxd) - Powerful system container and virtual machine manager
* [AliyunContainerService/pouch](https://github.com/AliyunContainerService/pouch) - An Efficient Enterprise-class Container Engine
* [nginx-proxy/docker-gen](https://github.com/nginx-proxy/docker-gen) - Generate files from docker container meta-data
* [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) - Google Cloud Client Libraries for Go.
* [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) - Auto-generated Google APIs for Go.
* [nicholas-fedor/watchtower](https://github.com/nicholas-fedor/watchtower) - Automate Docker container image updates
* [purpleidea/mgmt](https://github.com/purpleidea/mgmt) - Next generation distributed, event-driven, parallel config management!
* [peak/s5cmd](https://github.com/peak/s5cmd) - Parallel S3 and local filesystem execution tool.
* [donknap/dpanel](https://github.com/donknap/dpanel) - 轻量化 docker 可视化管理面板。lightweight panel for docker
* [google/go-containerregistry](https://github.com/google/go-containerregistry) - Go library and CLIs for working with container registries
* [DNSControl/dnscontrol](https://github.com/DNSControl/dnscontrol) - Infrastructure as code for DNS!
* [spaceandtimefdn/SxT-Go-SDK](https://github.com/spaceandtimefdn/SxT-Go-SDK) - GO based SDK for interacting with the Space and Time API.
* [aws/aws-lambda-go](https://github.com/aws/aws-lambda-go) - Libraries, samples and tools to help Go developers develop AWS Lambda functions.
* [spegel-org/spegel](https://github.com/spegel-org/spegel) - Stateless cluster local OCI registry mirror.
* [aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2) - AWS SDK for the Go programming language.
* [glasskube/glasskube](https://github.com/glasskube/glasskube) - 🧊 The next generation Package Manager for Kubernetes 📦 Featuring a GUI and a CLI. Glasskube packages are dependency aware, GitOps ready and can get automatic updates via a central public package repository. *(archived)*
* [FairwindsOps/goldilocks](https://github.com/FairwindsOps/goldilocks) - Get your resource requests "Just Right"
* [cyclops-ui/cyclops](https://github.com/cyclops-ui/cyclops) - Developer Friendly Kubernetes 👁️
* [zegl/kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security. kube-score actively prevents downtime and bugs in your Kubernetes YAML and Charts. Static code analysis for Kubernetes.
* [asobti/kube-monkey](https://github.com/asobti/kube-monkey) - An implementation of Netflix's Chaos Monkey for Kubernetes clusters
* [minio/minio-go](https://github.com/minio/minio-go) - MinIO Go client SDK for S3 compatible object storage
* [elastic/cloud-on-k8s](https://github.com/elastic/cloud-on-k8s) - Elastic Cloud on Kubernetes
* [erda-project/erda](https://github.com/erda-project/erda) - An enterprise-grade Cloud-Native application platform for Kubernetes.
* [hashicorp/terraform-provider-google](https://github.com/hashicorp/terraform-provider-google) - Terraform Provider for Google Cloud Platform
* [vmware/govmomi](https://github.com/vmware/govmomi) - Go library for the VMware vSphere API
* [minishift/minishift](https://github.com/minishift/minishift) - Run OpenShift 3.x locally | This project does not see active developement and maintenance. *(archived)*
* [cycloidio/terracognita](https://github.com/cycloidio/terracognita) - Reads from existing public and private cloud providers (reverse Terraform) and generates your infrastructure as code on Terraform configuration
* [LeanerCloud/AutoSpotting](https://github.com/LeanerCloud/AutoSpotting) - Saves up to 90% of AWS EC2 costs by automating the use of spot instances on existing AutoScaling groups. Installs in minutes using CloudFormation or Terraform. Convenient to deploy at scale using StackSets. Uses tagging to avoid launch configuration changes. Automated spot termination handling. Reliable fallback to on-demand instances.
* [fsouza/go-dockerclient](https://github.com/fsouza/go-dockerclient) - Go client for the Docker Engine API.
* [dreamans/syncd](https://github.com/dreamans/syncd) - syncd是一款开源的代码部署工具，它具有简单、高效、易用等特点，可以提高团队的工作效率.
* [rexray/rexray](https://github.com/rexray/rexray) - REX-Ray is a container storage orchestration engine enabling persistence for cloud native workloads
* [aws/amazon-ecs-agent](https://github.com/aws/amazon-ecs-agent) - Amazon Elastic Container Service Agent

### Monitoring and Observability

* [thanos-io/thanos](https://github.com/thanos-io/thanos) - Highly available Prometheus setup with long term storage capabilities. A CNCF Incubating project.
* [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) - eBPF-powered network observability for Kubernetes. Indexes L4/L7 traffic with full K8s context, decrypts TLS without keys. Queryable by AI agents via MCP and humans via dashboard.
* [TwiN/gatus](https://github.com/TwiN/gatus) - Automated developer-oriented status page with alerting and incident support
* [aceberg/WatchYourLAN](https://github.com/aceberg/WatchYourLAN) - Lightweight network IP scanner written in Go. With notifications, history, export to Grafana
* [rcourtman/Pulse](https://github.com/rcourtman/Pulse) - Monitoring for Proxmox, Docker, Kubernetes, TrueNAS, and vSphere that watches your infrastructure for you: smart alerts, AI patrols that catch silent failures, and verified fixes
* [open-telemetry/opentelemetry-go](https://github.com/open-telemetry/opentelemetry-go) - OpenTelemetry Go API and SDK
* [prometheus/client_golang](https://github.com/prometheus/client_golang) - Prometheus instrumentation library for Go applications
* [google/mtail](https://github.com/google/mtail) - extract internal monitoring data from application logs for collection in a timeseries database
* [DataDog/datadog-agent](https://github.com/DataDog/datadog-agent) - Main repository for Datadog Agent
* [oliver006/redis_exporter](https://github.com/oliver006/redis_exporter) - Prometheus Exporter for Valkey & Redis Metrics. Supports Valkey 9.x, 8.x, 7.x and various Redis versions
* [odigos-io/odigos](https://github.com/odigos-io/odigos) - Distributed tracing without code changes. 🚀 Instantly monitor any application using OpenTelemetry and eBPF
* [opentracing/opentracing-go](https://github.com/opentracing/opentracing-go) - OpenTracing API for Go. 🛑 This library is DEPRECATED! https://github.com/opentracing/specification/issues/163 *(archived)*
* [rcrowley/go-metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library *(archived)*
* [bosun-monitor/bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework *(archived)*
* [target/goalert](https://github.com/target/goalert) - Open source on-call scheduling, automated escalations, and notifications so you never miss a critical alert
* [divan/expvarmon](https://github.com/divan/expvarmon) - TermUI based monitor for Go apps using expvars (/debug/vars). Quickest way to monitor your Go app(s).
* [census-instrumentation/opencensus-go](https://github.com/census-instrumentation/opencensus-go) - A stats collection and distributed tracing framework *(archived)*
* [sourcegraph/appdash](https://github.com/sourcegraph/appdash) - Application tracing system for Go, based on Google's Dapper. *(archived)*

## User Interface

### GUI Toolkits

* [wailsapp/wails](https://github.com/wailsapp/wails) - Create beautiful applications using Go
* [fyne-io/fyne](https://github.com/fyne-io/fyne) - Cross platform GUI toolkit in Go inspired by Material Design
* [therecipe/qt](https://github.com/therecipe/qt) - Qt binding for Go (Golang) with support for Windows / macOS / Linux / FreeBSD / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS / Ubuntu Touch / JavaScript / WebAssembly
* [andlabs/ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go.
* [zserge/lorca](https://github.com/zserge/lorca) - Build cross-platform modern desktop apps in Go + HTML5
* [lxn/walk](https://github.com/lxn/walk) - A Windows GUI toolkit for the Go Programming Language
* [go-flutter-desktop/go-flutter](https://github.com/go-flutter-desktop/go-flutter) - Flutter on Windows, MacOS and Linux - based on Flutter Embedding, Go and GLFW.
* [asticode/go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron) *(archived)*
* [google/gxui](https://github.com/google/gxui) - An experimental Go cross platform UI library. *(archived)*
* [getlantern/systray](https://github.com/getlantern/systray) - a cross platfrom Go library to place an icon and menu in the notification area
* [alexflint/gallium](https://github.com/alexflint/gallium) - Build desktop applications in Go and HTML.
* [ying32/govcl](https://github.com/ying32/govcl) - Cross-platform Go/Golang GUI library.
* [gotk3/gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3
* [mattn/go-gtk](https://github.com/mattn/go-gtk) - Go binding for GTK
* [go-qml/qml](https://github.com/go-qml/qml) - QML support for the Go language

### Terminal and Console UI

* [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) - A powerful little TUI framework 🏗
* [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) - Style definitions for nice terminal layouts 👄
* [jroimartin/gocui](https://github.com/jroimartin/gocui) - Minimalist Go package aimed at creating Console User Interfaces.
* [fatih/color](https://github.com/fatih/color) - Color package for Go (golang)
* [pterm/pterm](https://github.com/pterm/pterm) - ✨ PTerm is a modern Go module to easily beautify console output. Featuring charts, progressbars, tables, trees, text input, select menus and much more 🚀 It's completely configurable and 100% cross-platform compatible.
* [c-bata/go-prompt](https://github.com/c-bata/go-prompt) - Building powerful interactive prompts in Go, inspired by python-prompt-toolkit.
* [nsf/termbox-go](https://github.com/nsf/termbox-go) - Pure Go termbox implementation
* [schollz/progressbar](https://github.com/schollz/progressbar) - A really basic thread-safe progress bar for Golang applications
* [cheggaaa/pb](https://github.com/cheggaaa/pb) - Console progress bar for Golang
* [charmbracelet/glamour](https://github.com/charmbracelet/glamour) - Stylesheet-based markdown rendering for your CLI apps 💇🏻‍♀️
* [jedib0t/go-pretty](https://github.com/jedib0t/go-pretty) - Table-writer and more in golang!
* [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [justjanne/powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt for your shell, written in go
* [briandowns/spinner](https://github.com/briandowns/spinner) - Go (golang) package with 90 configurable terminal spinner/progress indicators.
* [vbauerster/mpb](https://github.com/vbauerster/mpb) - multi progress bar for Go cli applications
* [charmbracelet/charm](https://github.com/charmbracelet/charm) - The Charm Tool and Library 🌟 *(archived)*
* [chzyer/readline](https://github.com/chzyer/readline) - Readline is a pure go(golang) implementation for GNU-Readline kind library
* [gosuri/uiprogress](https://github.com/gosuri/uiprogress) - A go library to render progress bars in terminal applications
* [marcusolsson/tui-go](https://github.com/marcusolsson/tui-go) - A UI library for terminal applications. *(archived)*

### Applications and End User Tools

* [gohugoio/hugo](https://github.com/gohugoio/hugo) - The world’s fastest framework for building websites.
* [syncthing/syncthing](https://github.com/syncthing/syncthing) - Open Source Continuous File Synchronization
* [usememos/memos](https://github.com/usememos/memos) - Open-source, self-hosted note-taking tool built for quick capture. Markdown-native, lightweight, and fully yours.
* [go-gitea/gitea](https://github.com/go-gitea/gitea) - Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD
* [gogs/gogs](https://github.com/gogs/gogs) - The painless way to host your own Git service
* [glanceapp/glance](https://github.com/glanceapp/glance) - A self-hosted dashboard that puts all your feeds in one place
* [restic/restic](https://github.com/restic/restic) - Fast, secure, efficient backup program
* [filebrowser/filebrowser](https://github.com/filebrowser/filebrowser) - File Browser provides a file managing interface within a specified directory and it can be used to upload, delete, preview and edit your files. *(archived)*
* [micro-editor/micro](https://github.com/micro-editor/micro) - A modern and intuitive terminal-based text editor
* [GopeedLab/gopeed](https://github.com/GopeedLab/gopeed) - A fast, modern download manager for HTTP, BitTorrent, Magnet, and ed2k. Cross-platform, built with Golang and Flutter.
* [yuaotian/go-cursor-help](https://github.com/yuaotian/go-cursor-help) - 解决Cursor在免费订阅期间出现以下提示的问题: Your request has been blocked as our system has detected suspicious activity / You've reached your trial request limit. / Too many free trial accounts used on this machine.
* [yudai/gotty](https://github.com/yudai/gotty) - Share your terminal as a web application
* [wtfutil/wtf](https://github.com/wtfutil/wtf) - The personal information dashboard for your terminal
* [apache/answer](https://github.com/apache/answer) - A Q&A platform software for teams at any scales. Whether it's a community forum, help center, or knowledge management platform, you can always count on Apache Answer.
* [tinode/chat](https://github.com/tinode/chat) - Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots
* [gotenberg/gotenberg](https://github.com/gotenberg/gotenberg) - A developer-friendly API for converting many document formats into PDF files, and more!
* [stashapp/stash](https://github.com/stashapp/stash) - An organizer for your porn, written in Go. Documentation: https://docs.stashapp.cc
* [drakkan/sftpgo](https://github.com/drakkan/sftpgo) - Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server - S3, Google Cloud Storage, Azure Blob
* [go-shiori/shiori](https://github.com/go-shiori/shiori) - Simple bookmark manager built with Go
* [0xJacky/nginx-ui](https://github.com/0xJacky/nginx-ui) - Yet another WebUI for Nginx
* [getlago/lago](https://github.com/getlago/lago) - Open Source Metering and Usage Based Billing API ⭐️ Consumption tracking, Subscription management, Pricing iterations, Payment orchestration & Revenue analytics
* [screego/server](https://github.com/screego/server) - screen sharing for developers https://screego.net/
* [miniflux/v2](https://github.com/miniflux/v2) - Minimalist and opinionated feed reader
* [keybase/client](https://github.com/keybase/client) - Keybase Go Library, Client, Service, OS X, iOS, Android, Electron
* [cookieY/Yearning](https://github.com/cookieY/Yearning) - 🐳 A most popular sql audit platform for mysql
* [appleboy/gorush](https://github.com/appleboy/gorush) - A push notification server written in Go (Golang).
* [schachmat/wego](https://github.com/schachmat/wego) - weather app for the terminal
* [mindoc-org/mindoc](https://github.com/mindoc-org/mindoc) - Golang实现的基于beego框架的接口在线文档管理系统
* [ArvinLovegood/go-stock](https://github.com/ArvinLovegood/go-stock) - 🦄🦄🦄AI赋能股票分析：AI加持的股票分析/选股工具。股票行情获取，AI热点资讯分析，AI资金/财务分析，涨跌报警推送。支持A股，港股，美股。支持市场整体/个股情绪分析，AI辅助选股等。数据全部保留在本地。支持DeepSeek，OpenAI， Ollama，LMStudio，AnythingLLM，硅基流动，火山方舟，阿里云百炼等平台或模型。
* [cjbassi/gotop](https://github.com/cjbassi/gotop) - A terminal based graphical activity monitor inspired by gtop and vtop *(archived)*
* [rorkai/App-Store-Connect-CLI](https://github.com/rorkai/App-Store-Connect-CLI) - Fast, scriptable CLI for the App Store Connect API. Automate TestFlight, builds, submissions, signing, analytics, screenshots, subscriptions, and more
* [simulot/immich-go](https://github.com/simulot/immich-go) - An alternative to the immich-CLI command that doesn't depend on nodejs installation. It tries its best for importing google photos takeout archives.
* [jpbruinsslot/slack-term](https://github.com/jpbruinsslot/slack-term) - Slack client for your terminal
* [seriousm4x/UpSnap](https://github.com/seriousm4x/UpSnap) - A simple wake on lan web app written with SvelteKit, Go and PocketBase.
* [dundee/gdu](https://github.com/dundee/gdu) - Fast disk usage analyzer with console interface written in Go
* [arp242/goatcounter](https://github.com/arp242/goatcounter) - Easy web analytics. No tracking of personal data.
* [ankitpokhrel/jira-cli](https://github.com/ankitpokhrel/jira-cli) - 🔥 Feature-rich interactive Jira command line.
* [ayn2op/discordo](https://github.com/ayn2op/discordo) - A lightweight, secure, and feature-rich Discord terminal (TUI) client.
* [ponzu-cms/ponzu](https://github.com/ponzu-cms/ponzu) - Headless CMS with automatic JSON API. Featuring auto-HTTPS from Let's Encrypt, HTTP/2 Server Push, and flexible server framework written in Go.
* [bililive-go/bililive-go](https://github.com/bililive-go/bililive-go) - 一个直播录制工具
* [matrix-org/dendrite](https://github.com/matrix-org/dendrite) - Dendrite is a second-generation Matrix homeserver written in Go! *(archived)*
* [qjfoidnh/BaiduPCS-Go](https://github.com/qjfoidnh/BaiduPCS-Go) - iikira/BaiduPCS-Go原版基础上集成了分享链接/秒传链接转存功能
* [omriharel/deej](https://github.com/omriharel/deej) - Set app volumes with real sliders! deej is an Arduino & Go project to let you build your own hardware mixer for Windows and Linux
* [flexprice/flexprice](https://github.com/flexprice/flexprice) - Usage-based pricing and billing for developers 🔓 Cloud or self-hosted ⚙️ No-code UI 💰 Realtime usage metering 🎟 Credits & top-ups 🔑 Control feature access
* [knqyf263/pet](https://github.com/knqyf263/pet) - Simple command-line snippet manager
* [writefreely/writefreely](https://github.com/writefreely/writefreely) - A clean, Markdown-based publishing platform made for writers. Write together and build a community.
* [johnste/finicky](https://github.com/johnste/finicky) - A macOS app for customizing which browser to start
* [wxbool/video-srt-windows](https://github.com/wxbool/video-srt-windows) - 这是一个可以识别视频语音自动生成字幕SRT文件的开源 Windows-GUI 软件工具。
* [taigrr/spank](https://github.com/taigrr/spank) - Slap your MacBook, it yells back. Uses Apple Silicon accelerometer via IOKit HID.
* [flipt-io/flipt](https://github.com/flipt-io/flipt) - Enterprise-ready, Git native feature management solution
* [aldinokemal/go-whatsapp-web-multidevice](https://github.com/aldinokemal/go-whatsapp-web-multidevice) - GOWA - WhatsApp REST API with support for UI, Multi Account, Webhooks, and MCP, and Chatwoot. Built with Golang for efficient memory use.
* [tophubs/TopList](https://github.com/tophubs/TopList) - 今日热榜，一个获取各大热门网站热门头条的聚合网站，使用Go语言编写，多协程异步快速抓取信息，预览:https://mo.fish
* [rocboss/paopao-ce](https://github.com/rocboss/paopao-ce) - A scalable social community platform powered by Gin backend and modern TypeScript/Vue frontend architecture
* [autobrr/qui](https://github.com/autobrr/qui) - A fast, single-binary qBittorrent web UI: manage multiple instances, automate torrent workflows, and cross-seed across trackers.
* [cointop-sh/cointop](https://github.com/cointop-sh/cointop) - A fast and lightweight interactive terminal based UI application for tracking cryptocurrencies 🚀 by @miguelmota *(archived)*
* [redpanda-data/console](https://github.com/redpanda-data/console) - Redpanda Console is a developer-friendly UI for managing your Kafka/Redpanda workloads. Console gives you a simple, interactive approach for gaining visibility into your topics, masking data, managing consumer groups, and exploring real-time data with time-travel debugging.
* [jorgerojas26/lazysql](https://github.com/jorgerojas26/lazysql) - A cross-platform TUI database management tool written in Go.
* [guohuiyuan/go-music-dl](https://github.com/guohuiyuan/go-music-dl) - 一个基于 Go 语言的全网音乐搜索与下载工具。支持 CLI 命令行与 Web 服务双模式，内置网易云、QQ、酷狗、Bilibili、汽水音乐等 10+ 个主流平台，支持多源并发搜索与无损音质解析。music-dl交流群：755087923
* [irbis-sh/zen-desktop](https://github.com/irbis-sh/zen-desktop) - Ad-blocker and privacy guard for Windows, macOS and Linux.
* [5rahim/seanime](https://github.com/5rahim/seanime) - Open-source media server with a web interface and desktop app for anime and manga.
* [rgburke/grv](https://github.com/rgburke/grv) - GRV is a terminal interface for viewing git repositories
* [Adembc/lazyssh](https://github.com/Adembc/lazyssh) - A terminal-based SSH manager inspired by lazydocker and k9s - Written in go
* [SurgeDM/Surge](https://github.com/SurgeDM/Surge) - Blazing fast TUI download manager built in Go for power users
* [mlogclub/bbs-go](https://github.com/mlogclub/bbs-go) - A lightweight community and Q&A platform for forums, knowledge bases, and discussions.一个轻量级社区和问答平台。
* [thrasher-corp/gocryptotrader](https://github.com/thrasher-corp/gocryptotrader) - A cryptocurrency trading bot and framework supporting multiple exchanges written in Golang.
* [thomiceli/opengist](https://github.com/thomiceli/opengist) - Self-hosted pastebin powered by Git, open-source alternative to Github Gist.
* [yourselfhosted/slash](https://github.com/yourselfhosted/slash) - An open source, self-hosted platform for sharing and managing your most frequently used links. Easily create customizable, human-readable shortcuts to streamline your link management.
* [studygolang/studygolang](https://github.com/studygolang/studygolang) - Go 语言中文网 | Golang中文社区 | Go语言学习园地 源码
* [0xDkd/auxpi](https://github.com/0xDkd/auxpi) - 🍭 集合多家 API 的新一代图床
* [akiyosi/goneovim](https://github.com/akiyosi/goneovim) - A GUI frontend for neovim.
* [taoshihan1991/goflylivechat](https://github.com/taoshihan1991/goflylivechat) - 开源在线客服系统GO语言开发GO-FLY,免费在线客服系统/GOFLY LIVE CHAT: open source self-hosted private cloud customer support live chat software by golang
* [bemasher/rtlamr](https://github.com/bemasher/rtlamr) - An rtl-sdr receiver for Itron ERT compatible smart meters operating in the 900MHz ISM band.
* [shen100/wemall](https://github.com/shen100/wemall) - 基于react, node.js, go开发的微商城（含微信小程序）
* [mop-tracker/mop](https://github.com/mop-tracker/mop) - Stock market tracker for hackers.
* [kabukky/journey](https://github.com/kabukky/journey) - A blog engine written in Go, compatible with Ghost themes.

## Graphics and Media

### Game Development

* [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) - A dead simple 2D game engine for Go
* [heroiclabs/nakama](https://github.com/heroiclabs/nakama) - Scalable open-source game backend server: multiplayer, matchmaking, leaderboards, chat, and social features for games.
* [OpenDiablo2/OpenDiablo2](https://github.com/OpenDiablo2/OpenDiablo2) - An open source re-implementation of Diablo 2 *(archived)*
* [fogleman/nes](https://github.com/fogleman/nes) - NES emulator written in Go.
* [name5566/leaf](https://github.com/name5566/leaf) - A game server framework in Go (golang)
* [KaijuEngine/kaiju](https://github.com/KaijuEngine/kaiju) - General purpose 3D and 2D game engine using Go (golang) and Vulkan with built in editor
* [faiface/pixel](https://github.com/faiface/pixel) - A hand-crafted 2D game library in Go
* [googleforgames/open-match](https://github.com/googleforgames/open-match) - Flexible, extensible, and scalable video game matchmaking.
* [g3n/engine](https://github.com/g3n/engine) - Go 3D Game Engine (http://g3n.rocks)
* [xiaonanln/goworld](https://github.com/xiaonanln/goworld) - Scalable Distributed Game Server Engine with Hot Swapping in Golang
* [Humpheh/goboy](https://github.com/Humpheh/goboy) - Multi-platform Nintendo Game Boy Color emulator written in Go
* [zachlatta/sshtron](https://github.com/zachlatta/sshtron) - $ ssh sshtron.zachlatta.com
* [giongto35/cloud-game](https://github.com/giongto35/cloud-game) - Web-based Cloud Gaming service for Retro Game
* [icexin/gocraft](https://github.com/icexin/gocraft) - A Minecraft like game written in go

### Image and Video

* [livekit/livekit](https://github.com/livekit/livekit) - End-to-end realtime stack for connecting humans and AI
* [bluenviron/mediamtx](https://github.com/bluenviron/mediamtx) - Ready-to-use Media-over-QUIC / SRT / WebRTC / RTSP / RTMP / LL-HLS / MPEG-TS / RTP live media server and media proxy that allows to read, publish, proxy, record and playback real-time video and audio streams.
* [AlexxIT/go2rtc](https://github.com/AlexxIT/go2rtc) - Ultimate camera streaming application
* [fogleman/primitive](https://github.com/fogleman/primitive) - Reproducing images with geometric primitives.
* [EasyDarwin/EasyDarwin](https://github.com/EasyDarwin/EasyDarwin) - open source、high performance、industrial rtsp streaming server,a lot of optimization on streaming relay,KeyFrame cache,RESTful,and web management,also EasyDarwin support distributed load balancing,a simple streaming media cloud platform architecture.
* [disintegration/imaging](https://github.com/disintegration/imaging) - Imaging is a simple image processing package for Go
* [anthonynsimon/bild](https://github.com/anthonynsimon/bild) - Image processing algorithms in pure Go
* [cshum/imagor](https://github.com/cshum/imagor) - Fast, secure image processing server and Go library, using libvips
* [willnorris/imageproxy](https://github.com/willnorris/imageproxy) - A caching, resizing image proxy written in Go
* [rh12503/triangula](https://github.com/rh12503/triangula) - Generate high-quality triangulated and polygonal art from images.
* [nfnt/resize](https://github.com/nfnt/resize) - Pure golang image resizing *(archived)*
* [h2non/bimg](https://github.com/h2non/bimg) - Go package for fast high-level image processing powered by libvips C library
* [skip2/go-qrcode](https://github.com/skip2/go-qrcode) - :sparkles: QR Code encoder (Go)
* [thoas/picfit](https://github.com/thoas/picfit) - An image resizing server written in Go
* [giorgisio/goav](https://github.com/giorgisio/goav) - Golang bindings for FFmpeg (This repository is no longer maintained)
* [pierrre/imageserver](https://github.com/pierrre/imageserver) - Image server toolkit in Go

## Security

### Cryptography

* [hashicorp/vault](https://github.com/hashicorp/vault) - A tool for secrets management, encryption as a service, and privileged access management
* [FiloSottile/age](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
* [go-acme/lego](https://github.com/go-acme/lego) - Let's Encrypt/ACME client and library written in Go
* [smallstep/certificates](https://github.com/smallstep/certificates) - 🛡️ A private certificate authority (X.509 & SSH) & ACME server for secure automated certificate management, so you can use TLS everywhere & SSO for SSH.
* [openbao/openbao](https://github.com/openbao/openbao) - OpenBao is a software solution to manage, store, and distribute sensitive data including secrets, certificates, and keys.
* [gopasspw/gopass](https://github.com/gopasspw/gopass) - The slightly more awesome standard unix password manager for teams
* [letsencrypt/boulder](https://github.com/letsencrypt/boulder) - An ACME-based certificate authority, written in Go.
* [caddyserver/certmagic](https://github.com/caddyserver/certmagic) - Automatic HTTPS for any Go program: fully-managed TLS certificate issuance and renewal
* [golang/crypto](https://github.com/golang/crypto) - [mirror] Go supplementary cryptography libraries
* [tellerops/teller](https://github.com/tellerops/teller) - Cloud native secrets management for developers - never leave your command line for secrets.
* [awnumar/memguard](https://github.com/awnumar/memguard) - Software sandbox for storage of sensitive information in memory.
* [cloudflare/gokey](https://github.com/cloudflare/gokey) - A simple vaultless password manager in Go
* [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults) - A Vault swiss-army knife: A CLI tool to init, unseal and configure Vault (auth methods, secret engines). *(archived)*

### Security Tools

* [aquasecurity/trivy](https://github.com/aquasecurity/trivy) - Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more
* [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) - Find secrets with Gitleaks 🔑
* [trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog) - Find, verify, and analyze leaked credentials
* [ffuf/ffuf](https://github.com/ffuf/ffuf) - Fast web fuzzer written in Go
* [owasp-amass/amass](https://github.com/owasp-amass/amass) - In-depth attack surface mapping and asset discovery
* [gophish/gophish](https://github.com/gophish/gophish) - Open-Source Phishing Toolkit
* [OJ/gobuster](https://github.com/OJ/gobuster) - Directory/File, DNS and VHost busting tool written in Go
* [safing/portmaster](https://github.com/safing/portmaster) - 🏔 Love Freedom - ❌ Block Mass Surveillance
* [anchore/grype](https://github.com/anchore/grype) - A vulnerability scanner for container images and filesystems
* [future-architect/vuls](https://github.com/future-architect/vuls) - Agent-less vulnerability scanner for Linux, FreeBSD, Container, WordPress, Programming language libraries, Network devices
* [quay/clair](https://github.com/quay/clair) - Vulnerability Static Analysis for Containers
* [google/osv-scanner](https://github.com/google/osv-scanner) - Vulnerability scanner written in Go which uses the data provided by https://osv.dev
* [anchore/syft](https://github.com/anchore/syft) - CLI tool and library for generating a Software Bill of Materials from container images and filesystems
* [securego/gosec](https://github.com/securego/gosec) - Go security checker
* [aquasecurity/tfsec](https://github.com/aquasecurity/tfsec) - Tfsec is now part of Trivy
* [j3ssie/osmedeus](https://github.com/j3ssie/osmedeus) - A Modern Orchestration Engine for Security
* [projectdiscovery/naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in go with a focus on reliability and simplicity. Designed to be used in combination with other tools for attack surface discovery in bug bounties and pentests
* [alpkeskin/mosint](https://github.com/alpkeskin/mosint) - An automated e-mail OSINT tool
* [burrowers/garble](https://github.com/burrowers/garble) - Obfuscate Go builds
* [google/google-ctf](https://github.com/google/google-ctf) - Google CTF
* [sensepost/gowitness](https://github.com/sensepost/gowitness) - 🔍 gowitness - a golang, web screenshot utility using Chrome Headless
* [lcvvvv/kscan](https://github.com/lcvvvv/kscan) - Kscan是一款纯go开发的全方位扫描器，具备端口扫描、协议检测、指纹识别，暴力破解等功能。支持协议1200+，协议指纹10000+，应用指纹20000+，暴力破解协议10余种。
* [corazawaf/coraza](https://github.com/corazawaf/coraza) - OWASP Coraza WAF is a golang modsecurity compatible web application firewall library
* [edoardottt/cariddi](https://github.com/edoardottt/cariddi) - Take a list of domains, crawl urls and scan for endpoints, secrets, api keys, file extensions, tokens and more
* [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) - bluemonday: a fast golang HTML sanitizer (inspired by the OWASP Java HTML Sanitizer) to scrub user generated content of XSS
* [ibnaleem/gosearch](https://github.com/ibnaleem/gosearch) - 🔍 Search anyone's digital footprint across 300+ websites
* [goodwithtech/dockle](https://github.com/goodwithtech/dockle) - Container Image Linter for Security, Helping build the Best-Practice Docker Image, Easy to start
* [teler-sh/teler](https://github.com/teler-sh/teler) - Real-time HTTP Intrusion Detection *(archived)*
* [projectdiscovery/proxify](https://github.com/projectdiscovery/proxify) - A versatile and portable proxy for capturing, manipulating, and replaying HTTP/HTTPS traffic on the go.
* [praetorian-inc/gokart](https://github.com/praetorian-inc/gokart) - A static analysis tool for securing Go code *(archived)*
* [wgpsec/ENScan_GO](https://github.com/wgpsec/ENScan_GO) - 一款基于各大企业信息API的工具，解决在遇到的各种针对国内企业信息收集难题。一键收集控股公司ICP备案、APP、小程序、微信公众号等信息聚合导出。支持MCP接入

### Authentication and Authorization

* [gravitational/teleport](https://github.com/gravitational/teleport) - The easiest, and most secure way to access and protect all of your infrastructure.
* [apache/casbin](https://github.com/apache/casbin) - Apache Casbin: an authorization library that supports access control models like ACL, RBAC, ABAC.
* [ory/hydra](https://github.com/ory/hydra) - Internet-scale OpenID Certified™ OpenID Connect and OAuth2.1 provider that integrates with your user management through headless APIs. Solve OIDC/OAuth2 user cases over night. Consume as a service on Ory Network or self-host. Trusted by OpenAI and many others for scale and security. Written in Go.
* [casdoor/casdoor](https://github.com/casdoor/casdoor) - An open-source Agent-first Identity and Access Management (IAM) /LLM MCP & agent gateway and auth server with web UI supporting OpenClaw, MCP, OAuth, OIDC, SAML, CAS, LDAP, SCIM, WebAuthn, TOTP, MFA, Face ID, Google Workspace, Azure AD
* [ory/kratos](https://github.com/ory/kratos) - Headless cloud-native authentication and identity management written in Go. Scales to a billion+ users. Replace Homegrown, Auth0, Okta, Firebase with better UX and DX. Passkeys, Social Sign In, OIDC, Magic Link, Multi-Factor Auth, SMS, SAML, TOTP, and more. Runs everywhere, runs best on Ory Network.
* [dgrijalva/jwt-go](https://github.com/dgrijalva/jwt-go) - ARCHIVE - Golang implementation of JSON Web Tokens (JWT). This project is now maintained at: *(archived)*
* [golang-jwt/jwt](https://github.com/golang-jwt/jwt) - Go implementation of JSON Web Tokens (JWT).
* [teamhanko/hanko](https://github.com/teamhanko/hanko) - Modern authentication, on your terms. Open source alternative to Auth0, Clerk, WorkOS, Stytch.
* [tinyauthapp/tinyauth](https://github.com/tinyauthapp/tinyauth) - The tiniest OpenID Certified™ authorization and authentication server you have ever seen.
* [markbates/goth](https://github.com/markbates/goth) - Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications.
* [golang/oauth2](https://github.com/golang/oauth2) - Go OAuth2
* [openfga/openfga](https://github.com/openfga/openfga) - A high performance and flexible authorization/permission engine built for developers and inspired by Google Zanzibar
* [ory/keto](https://github.com/ory/keto) - The most scalable and customizable permission server on the market. Fix your slow or broken permission system with Google's proven "Zanzibar" approach. Supports ACL, RBAC, and more. Written in Go, cloud native, headless, API-first. Available as a service on Ory Network and for self-hosters.
* [pomerium/pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity and context-aware access proxy.
* [cerbos/cerbos](https://github.com/cerbos/cerbos) - Cerbos is an open-core authorization management platform for authorizing every identity and governing every action across applications, gateways, workloads, and AI agents.
* [netlify/gotrue](https://github.com/netlify/gotrue) - An JWT based API for managing users and issuing JWT tokens.
* [go-oauth2/oauth2](https://github.com/go-oauth2/oauth2) - OAuth 2.0 server library for the Go programming language.
* [ory/oathkeeper](https://github.com/ory/oathkeeper) - A cloud native Identity & Access Proxy / API (IAP) and Access Control Decision API that authenticates, authorizes, and mutates incoming HTTP(s) requests. Inspired by the BeyondCorp / Zero Trust white paper. Written in Go.
* [gorilla/sessions](https://github.com/gorilla/sessions) - Package gorilla/sessions provides cookie and filesystem sessions and infrastructure for custom session backends.
* [buzzfeed/sso](https://github.com/buzzfeed/sso) - sso, aka S.S.Octopus, aka octoboi, is a single sign-on solution for securing internal services *(archived)*
* [pquerna/otp](https://github.com/pquerna/otp) - TOTP library for Go
* [glauth/glauth](https://github.com/glauth/glauth) - A lightweight LDAP server for development, home use, or CI
* [ory/fosite](https://github.com/ory/fosite) - Extensible security first OAuth 2.0 and OpenID Connect SDK for Go.
* [ory/ladon](https://github.com/ory/ladon) - A SDK for access control policies: authorization for the microservice and IoT age. Inspired by AWS IAM policies. Written for Go.
* [RichardKnop/go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - A standalone, specification-compliant, OAuth2 server written in Golang.

## Concurrency and Performance

### Concurrency and Parallelism

* [panjf2000/ants](https://github.com/panjf2000/ants) - 🐜🐜🐜 ants is the most powerful and reliable pooling solution for Go.
* [sourcegraph/conc](https://github.com/sourcegraph/conc) - Better structured concurrency for go
* [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin
* [ReactiveX/RxGo](https://github.com/ReactiveX/RxGo) - Reactive Extensions for the Go language.
* [uber-go/ratelimit](https://github.com/uber-go/ratelimit) - A Go blocking leaky-bucket rate limit implementation
* [ergo-services/ergo](https://github.com/ergo-services/ergo) - An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang. Zero dependencies.
* [orcaman/concurrent-map](https://github.com/orcaman/concurrent-map) - a thread-safe concurrent map for go
* [Jeffail/tunny](https://github.com/Jeffail/tunny) - A goroutine pool for Go

### Performance and Optimization

* [codesenberg/bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in Go
* [klauspost/compress](https://github.com/klauspost/compress) - Optimized Go Compression Packages
* [uber-go/automaxprocs](https://github.com/uber-go/automaxprocs) - Automatically set GOMAXPROCS to match Linux container CPU quota.
* [rakyll/boom](https://github.com/rakyll/boom) - HTTP(S) load generator, ApacheBench (ab) replacement, written in Go *(archived)*
* [link1st/go-stress-testing](https://github.com/link1st/go-stress-testing) - go 实现的压测工具，ab、locust、Jmeter压测工具介绍【单台机器100w连接压测实战】
* [mholt/archiver](https://github.com/mholt/archiver) - DEPRECATED. Please use mholt/archives instead. *(archived)*
* [mmcloughlin/avo](https://github.com/mmcloughlin/avo) - Generate x86 Assembly with Go
* [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - :zap: Go web framework benchmark

## Testing and Quality

### Testing

* [grafana/k6](https://github.com/grafana/k6) - A modern load testing tool, using Go and JavaScript
* [stretchr/testify](https://github.com/stretchr/testify) - A toolkit with common assertions and mocks that plays nicely with the standard library
* [tsenart/vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [probelabs/goreplay](https://github.com/probelabs/goreplay) - GoReplay is an open-source tool for capturing and replaying live HTTP traffic into a test environment in order to continuously test your system with real data. It can be used to increase confidence in code deployments, configuration changes and infrastructure changes.
* [keploy/keploy](https://github.com/keploy/keploy) - Open-source platform for creating safe, isolated production sandboxes for API, integration, and E2E testing.
* [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) - :alarm_clock: :fire: A TCP proxy to simulate network and system conditions for chaos and resiliency testing
* [tylertreat/comcast](https://github.com/tylertreat/comcast) - Simulating shitty network connections so you can build better systems.
* [axllent/mailpit](https://github.com/axllent/mailpit) - An email and SMTP testing tool with API for developers
* [golang/mock](https://github.com/golang/mock) - GoMock is a mocking framework for the Go programming language. *(archived)*
* [onsi/ginkgo](https://github.com/onsi/ginkgo) - A Modern Testing Framework for Go
* [getanteon/anteon](https://github.com/getanteon/anteon) - Anteon (formerly Ddosify): eBPF-based Kubernetes Monitoring and Performance Testing
* [smartystreets/goconvey](https://github.com/smartystreets/goconvey) - Go testing in the browser. Integrates with `go test`. Write behavioral tests in Go.
* [gruntwork-io/terratest](https://github.com/gruntwork-io/terratest) - Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.
* [vektra/mockery](https://github.com/vektra/mockery) - A mock code autogenerator for Go
* [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Sql mock driver for golang to test database interactions
* [goss-org/goss](https://github.com/goss-org/goss) - Quick and Easy server testing/validation
* [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) - Random fake data generator written in go
* [cweill/gotests](https://github.com/cweill/gotests) - Automatically generate Go test boilerplate from your source code.
* [uber-go/goleak](https://github.com/uber-go/goleak) - Goroutine leak detector
* [testcontainers/testcontainers-go](https://github.com/testcontainers/testcontainers-go) - Testcontainers for Go is a Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done.
* [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing for Go
* [google/go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests
* [ory/dockertest](https://github.com/ory/dockertest) - Write better integration tests! Dockertest helps you boot up ephermal docker images for your Go tests with minimal work.
* [nakabonne/ali](https://github.com/nakabonne/ali) - Generate HTTP load and plot the results in real-time
* [fortio/fortio](https://github.com/fortio/fortio) - Fortio load testing library, command line tool, advanced echo server and web UI in go (golang). Allows to specify a set query-per-second load and record latency histograms and other useful stats.
* [alicebob/miniredis](https://github.com/alicebob/miniredis) - Pure Go Redis server for Go unittests
* [bouk/monkey](https://github.com/bouk/monkey) - Monkey patching in Go *(archived)*
* [uber-go/mock](https://github.com/uber-go/mock) - GoMock is a mocking framework for the Go programming language.
* [gavv/httpexpect](https://github.com/gavv/httpexpect) - End-to-end HTTP and REST API testing for Go.
* [gotestyourself/gotestsum](https://github.com/gotestyourself/gotestsum) - 'go test' runner with output optimized for humans, JUnit XML for CI integration, and a summary of the test results.
* [cucumber/godog](https://github.com/cucumber/godog) - Cucumber for golang
* [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) - Lightweight service virtualization/ API simulation / API mocking tool for developers and testers
* [onsi/gomega](https://github.com/onsi/gomega) - Ginkgo's Preferred Matcher Library
* [h2non/gock](https://github.com/h2non/gock) - HTTP traffic mocking and testing made easy in Go ༼ʘ̚ل͜ʘ̚༽
* [bxcodec/faker](https://github.com/bxcodec/faker) - Go (Golang) Fake Data Generator for Struct. [Notes]This repository is archived, moved to the new repository https://github.com/go-faker/faker *(archived)*
* [goadapp/goad](https://github.com/goadapp/goad) - Goad is an AWS Lambda powered, highly distributed, load testing tool *(archived)*

## Utilities

### Command Line Tools

* [junegunn/fzf](https://github.com/junegunn/fzf) - :cherry_blossom: A command-line fuzzy finder
* [rclone/rclone](https://github.com/rclone/rclone) - "rsync for cloud storage" - Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Azure Blob, Azure Files, Yandex Files
* [spf13/cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions
* [iawia002/lux](https://github.com/iawia002/lux) - 👾 Fast and simple video download library and CLI tool written in Go
* [urfave/cli](https://github.com/urfave/cli) - A declarative, simple, fast, and fun package for building command line tools in Go
* [mislav/hub](https://github.com/mislav/hub) - A command-line tool that makes git easier to use with GitHub.
* [pranshuparmar/witr](https://github.com/pranshuparmar/witr) - Why is this running? Trace any process, port, container, or file back to what started it - CLI + TUI.
* [git-lfs/git-lfs](https://github.com/git-lfs/git-lfs) - Git extension for versioning large files
* [dlvhdr/gh-dash](https://github.com/dlvhdr/gh-dash) - A rich terminal UI for GitHub that doesn't break your flow.
* [majd/ipatool](https://github.com/majd/ipatool) - Command-line tool that allows you to search for iOS, iPadOS, tvOS, visionOS, and macOS apps on the App Store, and download .ipa or macOS .pkg app packages.
* [Melkeydev/go-blueprint](https://github.com/Melkeydev/go-blueprint) - Go-blueprint allows users to spin up a quick Go project using a popular framework
* [boyter/scc](https://github.com/boyter/scc) - Sloc, Cloc and Code: scc is a very fast accurate code counter with complexity calculations and COCOMO estimates written in pure Go
* [openclaw/gogcli](https://github.com/openclaw/gogcli) - Google Workspace in your terminal.
* [simeji/jid](https://github.com/simeji/jid) - json incremental digger
* [filhodanuvem/gitql](https://github.com/filhodanuvem/gitql) - 💊 A git query language
* [kkdai/youtube](https://github.com/kkdai/youtube) - Download Youtube Video in Golang
* [alecthomas/kingpin](https://github.com/alecthomas/kingpin) - CONTRIBUTIONS ONLY: A Go (golang) command line and flag parser
* [mergestat/mergestat-lite](https://github.com/mergestat/mergestat-lite) - Query git repositories with SQL. Generate reports, perform status checks, analyze codebases. 🔍 📊
* [ssut/payload-dumper-go](https://github.com/ssut/payload-dumper-go) - an android OTA payload dumper written in Go
* [minio/mc](https://github.com/minio/mc) - Unix like utilities for object store *(archived)*
* [alecthomas/kong](https://github.com/alecthomas/kong) - Kong is a command-line parser for Go
* [git-chglog/git-chglog](https://github.com/git-chglog/git-chglog) - [DEPRECATED] CHANGELOG generator implemented in Go (Golang) -> Use now the actively maintained git-cliff *(archived)*
* [noahgorstein/jqp](https://github.com/noahgorstein/jqp) - A TUI playground to experiment with jq
* [Narasimha1997/fake-sms](https://github.com/Narasimha1997/fake-sms) - A simple command line tool using which you can skip phone number based SMS verification by using a temporary phone number that acts like a proxy.
* [go-jira/jira](https://github.com/go-jira/jira) - simple jira command line client in Go
* [jessevdk/go-flags](https://github.com/jessevdk/go-flags) - go command line option parser
* [raviqqe/muffet](https://github.com/raviqqe/muffet) - Fast website link checker in Go
* [birdayz/kaf](https://github.com/birdayz/kaf) - Modern CLI for Apache Kafka, written in Go.
* [sheepla/pingu](https://github.com/sheepla/pingu) - 🐧ping command but with pingu
* [profclems/glab](https://github.com/profclems/glab) - The GitLab CLI tool. Archived: now officially adopted by GitLab as the official CLI tool and maintained at https://gitlab.com/gitlab-org/cli. See https://github.com/profclems/glab/issues/983 *(archived)*
* [mkchoi212/fac](https://github.com/mkchoi212/fac) - Easy-to-use CUI for fixing git conflicts

### Logging and Configuration

* [spf13/viper](https://github.com/spf13/viper) - Go configuration with fangs
* [sirupsen/logrus](https://github.com/sirupsen/logrus) - Structured, pluggable logging for Go.
* [uber-go/zap](https://github.com/uber-go/zap) - Blazing fast, structured, leveled logging in Go.
* [joho/godotenv](https://github.com/joho/godotenv) - A Go port of Ruby's dotenv library (Loads environment variables from .env files)
* [caarlos0/env](https://github.com/caarlos0/env) - A simple, zero-dependencies library to parse environment variables into structs
* [natefinch/lumberjack](https://github.com/natefinch/lumberjack) - lumberjack is a log rolling package for Go
* [knadh/koanf](https://github.com/knadh/koanf) - Simple, extremely lightweight, extensible, configuration management library for Go. Supports JSON, TOML, YAML, env, command line, file, S3 etc. Alternative to viper.
* [golang/glog](https://github.com/golang/glog) - Leveled execution logs for Go
* [go-ini/ini](https://github.com/go-ini/ini) - Package ini provides INI file read and write functionality in Go
* [charmbracelet/log](https://github.com/charmbracelet/log) - A minimal, colorful Go logging library 🪵
* [op/go-logging](https://github.com/op/go-logging) - Golang logging library

### Text Processing

* [a-h/templ](https://github.com/a-h/templ) - A language for writing HTML user interfaces in Go.
* [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) - PDF tooling for Go and the command line.
* [russross/blackfriday](https://github.com/russross/blackfriday) - Blackfriday: a markdown processor for Go
* [alecthomas/chroma](https://github.com/alecthomas/chroma) - A general purpose syntax highlighter in pure Go
* [yuin/goldmark](https://github.com/yuin/goldmark) - :trophy: The Golden Swiss Army Knife for markdown processing. 100% CommonMark compliant, AST w/ CST, Extensible, Fast, CJK-friendly.
* [dustin/go-humanize](https://github.com/dustin/go-humanize) - Go Humans! (formatters for units to human friendly sizes)
* [Masterminds/sprig](https://github.com/Masterminds/sprig) - Useful template functions for Go templates.
* [JohannesKaufmann/html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - ⚙️ Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
* [geekjourneyx/md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) - Markdown to WeChat CLI | 一键排版发布到微信公众号：支持 40+ 排版样式和专业主题 、AI 配图 、批量发布 、多账号管理、多平台发布
* [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) - Translate your Go program into multiple languages.
* [valyala/quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template
* [hairyhenderson/gomplate](https://github.com/hairyhenderson/gomplate) - A flexible commandline tool for template rendering. Supports lots of local and remote datasources.
* [unidoc/unipdf](https://github.com/unidoc/unipdf) - Golang PDF library for creating and processing PDF files (pure go)
* [flosch/pongo2](https://github.com/flosch/pongo2) - Django-syntax like template-engine for Go
* [signintech/gopdf](https://github.com/signintech/gopdf) - A simple library for generating PDF written in Go lang
* [arachnys/athenapdf](https://github.com/arachnys/athenapdf) - Drop-in replacement for wkhtmltopdf built on Go, Electron and Docker *(archived)*

### Files and Operating System

* [juicedata/juicefs](https://github.com/juicedata/juicefs) - JuiceFS is a distributed POSIX file system built on top of Redis and S3.
* [shirou/gopsutil](https://github.com/shirou/gopsutil) - psutil for golang
* [fsnotify/fsnotify](https://github.com/fsnotify/fsnotify) - Cross-platform filesystem notifications for Go.
* [cilium/ebpf](https://github.com/cilium/ebpf) - ebpf-go is a pure-Go library to read, modify and load eBPF programs and attach them to various hooks in the Linux kernel.
* [spf13/afero](https://github.com/spf13/afero) - The Universal Filesystem Abstraction for Go
* [kahing/goofys](https://github.com/kahing/goofys) - a high-performance, POSIX-ish Amazon S3 file system written in Go
* [progrium/darwinkit](https://github.com/progrium/darwinkit) - Native Mac APIs for Go. Previously known as MacDriver
* [tianon/gosu](https://github.com/tianon/gosu) - Simple Go-based setuid+setgid+setgroups+exec
* [kardianos/service](https://github.com/kardianos/service) - Run go programs as a service on major platforms.
* [rfjakob/gocryptfs](https://github.com/rfjakob/gocryptfs) - Encrypted overlay filesystem written in Go
* [ochinchina/supervisord](https://github.com/ochinchina/supervisord) - a go-lang supervisor implementation
* [gokrazy/gokrazy](https://github.com/gokrazy/gokrazy) - turn your Go program(s) into an appliance running on the Raspberry Pi 3, Pi 4, Pi 5, Pi Zero 2 W, or PCs (x86_64 or ARM64)!
* [cloudflare/tableflip](https://github.com/cloudflare/tableflip) - Graceful process restarts in Go
* [u-root/u-root](https://github.com/u-root/u-root) - A fully Go userland with Linux bootloaders! u-root can create a one-binary root file system (initramfs) containing a busybox-like set of tools written in Go.
* [hpcloud/tail](https://github.com/hpcloud/tail) - Go package for reading from continously updated files (tail -f)
* [coreos/go-systemd](https://github.com/coreos/go-systemd) - Go bindings to systemd socket activation, journal, D-Bus, and unit files
* [mattn/goreman](https://github.com/mattn/goreman) - foreman clone written in go language
* [GeertJohan/go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images,templates, etc very easy.
* [jpillora/overseer](https://github.com/jpillora/overseer) - Monitorable, gracefully restarting, self-upgrading binaries in Go (golang)
* [sevlyar/go-daemon](https://github.com/sevlyar/go-daemon) - A library for writing system daemons in golang.
* [inconshreveable/go-update](https://github.com/inconshreveable/go-update) - Build self-updating Golang programs
* [oniony/TMSU](https://github.com/oniony/TMSU) - TMSU lets you tags your files and then access them through a nifty virtual filesystem from any other application.
* [rcrowley/goagain](https://github.com/rcrowley/goagain) - Zero-downtime restarts in Go
* [libgit2/git2go](https://github.com/libgit2/git2go) - Git to Go; bindings for libgit2. Like McDonald's but tastier.
* [takama/daemon](https://github.com/takama/daemon) - A daemon package for use with Go (golang) services
* [howeyc/fsnotify](https://github.com/howeyc/fsnotify) - File system notification for Go *(archived)*

### Date and Time

* [robfig/cron](https://github.com/robfig/cron) - a cron library for go
* [go-co-op/gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go cron scheduling. This is a fork from https://github.com/jasonlvhit/gocron
* [ouqiang/gocron](https://github.com/ouqiang/gocron) - 定时任务管理系统
* [jinzhu/now](https://github.com/jinzhu/now) - Now is a time toolkit for golang
* [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron) - A Golang Job Scheduling Package.
* [shunfei/cronsun](https://github.com/shunfei/cronsun) - A Distributed, Fault-Tolerant Cron-Style Job System.
* [ajvb/kala](https://github.com/ajvb/kala) - Modern Job Scheduler

### Automation and Scripting

* [adnanh/webhook](https://github.com/adnanh/webhook) - webhook is a lightweight incoming webhook server to run shell commands
* [go-vgo/robotgo](https://github.com/go-vgo/robotgo) - RobotGo, Go Native cross-platform RPA, GUI automation, Auto test and Computer use @vcaesar
* [Mrs4s/go-cqhttp](https://github.com/Mrs4s/go-cqhttp) - cqhttp的golang实现，轻量、原生跨平台.
* [evilmartians/lefthook](https://github.com/evilmartians/lefthook) - Fast and powerful Git hooks manager for any type of projects.
* [bitfield/script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go
* [tucnak/telebot](https://github.com/tucnak/telebot) - Telebot is a Telegram bot framework in Go.
* [FloatTech/ZeroBot-Plugin](https://github.com/FloatTech/ZeroBot-Plugin) - 基于 ZeroBot 的 OneBot 插件

### General Purpose Libraries

* [samber/lo](https://github.com/samber/lo) - 💥 A Lodash-style Go library based on Go 1.18+ Generics (map, filter, contains, find...)
* [go-playground/validator](https://github.com/go-playground/validator) - :100:Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving
* [emirpasic/gods](https://github.com/emirpasic/gods) - GoDS (Go Data Structures) - Sets, Lists, Stacks, Maps, Trees, Queues, and much more
* [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) - A collection of useful, performant, and threadsafe Go datastructures.
* [uber-go/fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go.
* [asaskevich/govalidator](https://github.com/asaskevich/govalidator) - [Go] Package of validators and sanitizers for strings, numerics, slices and structs
* [jinzhu/copier](https://github.com/jinzhu/copier) - Copier for golang, copy value from struct to struct and more
* [google/uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
* [duke-git/lancet](https://github.com/duke-git/lancet) - A comprehensive, efficient, and reusable util function library of Go.
* [segmentio/ksuid](https://github.com/segmentio/ksuid) - K-Sortable Globally Unique IDs
* [oklog/ulid](https://github.com/oklog/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID) in Go
* [thoas/go-funk](https://github.com/thoas/go-funk) - A modern Go utility library which provides helpers (map, find, contains, filter, ...)
* [satori/go.uuid](https://github.com/satori/go.uuid) - UUID package for Go
* [deckarep/golang-set](https://github.com/deckarep/golang-set) - A simple, battle-tested and generic set type for the Go language. Trusted by GoogleCloudPlatform, Docker, 1Password, Ethereum and Hashicorp.
* [uber-go/dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* [dropbox/godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications.
* [google/btree](https://github.com/google/btree) - BTree provides a simple, ordered, in-memory data structure for Go programs. *(archived)*
* [go-ozzo/ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - An idiomatic Go (golang) validation package. Supports configurable and extensible validation rules (validators) using normal language constructs instead of error-prone struct tags.
* [cenkalti/backoff](https://github.com/cenkalti/backoff) - ⏱ The exponential backoff algorithm in Go
* [spf13/cast](https://github.com/spf13/cast) - safe and easy casting from one type to another in Go
* [fatih/structs](https://github.com/fatih/structs) - Utilities for Go structs *(archived)*
* [ahmetb/go-linq](https://github.com/ahmetb/go-linq) - .NET LINQ capabilities in Go
* [sony/gobreaker](https://github.com/sony/gobreaker) - Circuit Breaker implemented in Go
* [looplab/fsm](https://github.com/looplab/fsm) - Finite State Machine for Go
* [samber/mo](https://github.com/samber/mo) - 🦄 Monads and popular FP abstractions, powered by Go 1.18+ Generics (Option, Result, Either...)
* [bwmarrin/snowflake](https://github.com/bwmarrin/snowflake) - A simple to use Go (golang) package to generate or parse Twitter snowflake IDs
* [darccio/mergo](https://github.com/darccio/mergo) - Mergo: merging Go structs and maps since 2013
* [avast/retry-go](https://github.com/avast/retry-go) - Simple golang library for retry mechanism
* [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) - Roaring bitmaps in Go (golang), used by InfluxDB, Bleve, DataDog
* [bits-and-blooms/bloom](https://github.com/bits-and-blooms/bloom) - Go package implementing Bloom filters, used by many important systems
* [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) - A Go (golang) package for representing a list of errors as a single error.
* [eapache/go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang
* [openacid/slim](https://github.com/openacid/slim) - Surprisingly space efficient trie in Golang(11 bits/key; 100 ns/get).

## Other

* [microsoft/TypeScript](https://github.com/microsoft/TypeScript) - TypeScript is a superset of JavaScript that compiles to clean JavaScript output.
* [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) - 🪨 why use many token when few token do trick — Claude Code skill that cuts 65% of tokens by talking like caveman
* [infiniflow/ragflow](https://github.com/infiniflow/ragflow) - RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capabilities to create a superior context layer for LLMs
* [jesseduffield/lazygit](https://github.com/jesseduffield/lazygit) - simple terminal UI for git commands
* [netdata/netdata](https://github.com/netdata/netdata) - The fastest path to AI-powered full stack observability, even for lean teams.
* [nektos/act](https://github.com/nektos/act) - Run your GitHub Actions locally 🚀
* [prometheus/prometheus](https://github.com/prometheus/prometheus) - The Prometheus monitoring system and time series database.
* [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) - Open Source realtime backend in 1 file
* [FiloSottile/mkcert](https://github.com/FiloSottile/mkcert) - A simple zero-config tool to make locally trusted development certificates with any names you'd like.
* [wagoodman/dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image
* [jesseduffield/lazydocker](https://github.com/jesseduffield/lazydocker) - The lazier way to manage everything docker
* [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) - Wrap Antigravity, ChatGPT Codex, Claude Code, Grok Build as an OpenAI/Gemini/Claude/Codex compatible API service, allowing you to enjoy the free Gemini 3.1 Pro, GPT 5.6 Series, Grok 4.5, Claude model through API
* [AlistGo/alist](https://github.com/AlistGo/alist) - 🗂️A file list/WebDAV program that supports multiple storages, powered by Gin and Solidjs. / 一个支持多存储的文件列表/WebDAV程序，使用 Gin 和 Solidjs。
* [multica-ai/multica](https://github.com/multica-ai/multica) - Make humans and AI agents work as one team — open-source and self-hostable.
* [hashicorp/terraform](https://github.com/hashicorp/terraform) - Terraform enables you to safely and predictably create, change, and improve infrastructure. It is a source-available tool that codifies APIs into declarative configuration files that can be shared amongst team members, treated as code, edited, reviewed, and versioned.
* [mudler/LocalAI](https://github.com/mudler/LocalAI) - LocalAI is the open-source AI engine. Run any model - LLMs, vision, voice, image, video - on any hardware. No GPU required.
* [QuantumNous/new-api](https://github.com/QuantumNous/new-api) - A unified AI model hub for aggregation & distribution. It supports cross-converting various LLMs into OpenAI-compatible, Claude-compatible, or Gemini-compatible formats. A centralized gateway for personal and enterprise model management.
* [v2ray/v2ray-core](https://github.com/v2ray/v2ray-core) - A platform for building proxies to bypass network restrictions.
* [MHSanaei/3x-ui](https://github.com/MHSanaei/3x-ui) - Supporting multi-protocol multi-user(Vmess, Vless, Trojan, ShadowSocks, Wireguard, Hysteria, Tunnel, Mixed, HTTP, Tun, MTProto، AmneziaWG)
* [cli/cli](https://github.com/cli/cli) - GitHub’s official command line tool
* [milvus-io/milvus](https://github.com/milvus-io/milvus) - Milvus is a high-performance, cloud-native vector database built for scalable vector ANN search
* [danielmiessler/Fabric](https://github.com/danielmiessler/Fabric) - Fabric is an open-source framework for augmenting humans using AI. It provides a modular system for solving specific problems using a crowdsourced set of AI prompts that can be used anywhere.
* [juanfont/headscale](https://github.com/juanfont/headscale) - An open source, self-hosted implementation of the Tailscale control server
* [XTLS/Xray-core](https://github.com/XTLS/Xray-core) - Xray, Penetrates Everything. Also the best v2ray-core. Where the magic happens. An open platform for various uses.
* [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api) - Sub2API 一站式开源中转服务，让 Claude、Openai 、Gemini、Grok订阅统一接入，支持拼车共享，更高效分摊成本，原生工具无缝使用。
* [schollz/croc](https://github.com/schollz/croc) - Easily and securely send things from one computer to another :crocodile: :package:
* [photoprism/photoprism](https://github.com/photoprism/photoprism) - AI-Powered Photos App 🌈💎✨
* [evanw/esbuild](https://github.com/evanw/esbuild) - An extremely fast bundler for the web
* [istio/istio](https://github.com/istio/istio) - Connect, secure, control, and observe services.
* [SagerNet/sing-box](https://github.com/SagerNet/sing-box) - The universal proxy platform
* [IceWhaleTech/CasaOS](https://github.com/IceWhaleTech/CasaOS) - CasaOS - A simple, easy-to-use, elegant open-source Personal Cloud system.
* [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - 🔥 1Panel is a modern, open-source Linux server management panel and a lightweight AI management platform.
* [tailscale/tailscale](https://github.com/tailscale/tailscale) - The easiest, most secure way to use WireGuard and 2FA.
* [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) - DeepSeek-native AI coding agent for your terminal. Engineered around prefix-cache stability — leave it running.
* [seaweedfs/seaweedfs](https://github.com/seaweedfs/seaweedfs) - SeaweedFS is a distributed storage system for object storage (S3), file systems, and Iceberg tables, designed to handle billions of files with O(1) disk access and effortless horizontal scaling.
* [v2fly/v2ray-core](https://github.com/v2fly/v2ray-core) - A platform for building proxies to bypass network restrictions.
* [binwiederhier/ntfy](https://github.com/binwiederhier/ntfy) - Send push notifications to your phone or desktop using PUT/POST
* [k3s-io/k3s](https://github.com/k3s-io/k3s) - Lightweight Kubernetes
* [github/github-mcp-server](https://github.com/github/github-mcp-server) - GitHub's official MCP Server
* [podman-container-tools/podman](https://github.com/podman-container-tools/podman) - Podman: A tool for managing OCI containers and pods.
* [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) - Nuclei is a fast, customizable vulnerability scanner powered by the global security community and built on a simple YAML-based DSL, enabling collaboration to tackle trending vulnerabilities on the internet. It helps you find vulnerabilities in your applications, APIs, networks, DNS, and cloud configurations.
* [abiosoft/colima](https://github.com/abiosoft/colima) - Container runtimes on macOS (and Linux) with minimal setup
* [chubin/wttr.in](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather
* [helm/helm](https://github.com/helm/helm) - The Kubernetes Package Manager
* [opentofu/opentofu](https://github.com/opentofu/opentofu) - OpenTofu lets you declaratively manage your cloud infrastructure.
* [hashicorp/consul](https://github.com/hashicorp/consul) - Consul is a distributed, highly available, and data center aware solution to connect and configure applications across dynamic, distributed infrastructure.
* [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Tiny, Fast, and Deployable anywhere — automate the mundane, unleash your creativity
* [goharbor/harbor](https://github.com/goharbor/harbor) - An open source trusted cloud native registry project that stores, signs, and scans content.
* [netbirdio/netbird](https://github.com/netbirdio/netbird) - Connect your devices into a secure WireGuard®-based overlay network with SSO, MFA and granular access controls.
* [authelia/authelia](https://github.com/authelia/authelia) - The Single Sign-On Multi-Factor portal for web apps. OpenID Certified™ and Post-Quantum Cryptography Ready.
* [grafana/loki](https://github.com/grafana/loki) - Like Prometheus, but for logs.
* [cloudreve/cloudreve](https://github.com/cloudreve/cloudreve) - 🌩 Self-hosted file management and sharing system, supports multiple storage providers
* [charmbracelet/crush](https://github.com/charmbracelet/crush) - Glamourous agentic coding for all 💘
* [Wox-launcher/Wox](https://github.com/Wox-launcher/Wox) - A cross-platform launcher that simply works
* [charmbracelet/glow](https://github.com/charmbracelet/glow) - Render markdown on the CLI, with pizzazz! 💅🏻
* [gastownhall/beads](https://github.com/gastownhall/beads) - Beads - A memory upgrade for your coding agent
* [yeasy/docker_practice](https://github.com/yeasy/docker_practice) - 最新Docker容器技术，从真实案例中学习最佳实践！| Learn and understand Docker&Container technologies, with real DevOps practice!
* [openfaas/faas](https://github.com/openfaas/faas) - OpenFaaS - Serverless Functions Made Simple
* [dapr/dapr](https://github.com/dapr/dapr) - Dapr is a portable runtime for building distributed applications across cloud and edge, combining event-driven architecture with workflow orchestration.
* [rancher/rancher](https://github.com/rancher/rancher) - Complete container management platform
* [asdf-vm/asdf](https://github.com/asdf-vm/asdf) - Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more
* [d2lang/d2](https://github.com/d2lang/d2) - D2 is a modern diagram scripting language that turns text to diagrams.
* [henrygd/beszel](https://github.com/henrygd/beszel) - Lightweight server monitoring with historical data, docker stats, and alerts.
* [cilium/cilium](https://github.com/cilium/cilium) - eBPF-based Networking, Security, and Observability
* [alibaba/open-code-review](https://github.com/alibaba/open-code-review) - Fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.
* [containrrr/watchtower](https://github.com/containrrr/watchtower) - A process for automating Docker container base image updates. *(archived)*
* [OpenListTeam/OpenList](https://github.com/OpenListTeam/OpenList) - A new AList Fork to Anti Trust Crisis
* [dolthub/dolt](https://github.com/dolthub/dolt) - Dolt – Git for Data
* [inconshreveable/ngrok](https://github.com/inconshreveable/ngrok) - Unified ingress for developers *(archived)*
* [charmbracelet/gum](https://github.com/charmbracelet/gum) - A tool for glamorous shell scripts 🎀
* [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) - Fully autonomous AI Agents system capable of performing complex penetration testing tasks
* [argoproj/argo-cd](https://github.com/argoproj/argo-cd) - Declarative Continuous Deployment for Kubernetes
* [navidrome/navidrome](https://github.com/navidrome/navidrome) - 🎧 Your Personal Streaming Service
* [JanDeDobbeleer/oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) - The most customisable and low-latency cross platform/shell prompt renderer
* [knadh/listmonk](https://github.com/knadh/listmonk) - High performance, self-hosted, newsletter and mailing list manager with a modern dashboard. Single binary app.
* [yorukot/superfile](https://github.com/yorukot/superfile) - Pretty fancy and modern terminal file manager
* [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) - CNCF Jaeger, a Distributed Tracing Platform
* [getsops/sops](https://github.com/getsops/sops) - Simple and flexible tool for managing secrets
* [Tencent/WeKnora](https://github.com/Tencent/WeKnora) - Open-source LLM knowledge platform: turn raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki.
* [temporalio/temporal](https://github.com/temporalio/temporal) - Temporal service
* [chaitin/SafeLine](https://github.com/chaitin/SafeLine) - SafeLine is a self-hosted WAF(Web Application Firewall) / reverse proxy to protect your web apps from attacks and exploits.
* [HyNetworks/hysteria](https://github.com/HyNetworks/hysteria) - Hysteria is powerful, lightning-fast, and censorship-resistant open-source proxy software
* [TecharoHQ/anubis](https://github.com/TecharoHQ/anubis) - Weighs the soul of incoming HTTP requests to stop AI crawlers
* [m1k1o/neko](https://github.com/m1k1o/neko) - A self hosted virtual browser that runs in docker and uses WebRTC.
* [wavetermdev/waveterm](https://github.com/wavetermdev/waveterm) - An open-source, AI-integrated, cross-platform terminal for seamless workflows
* [lima-vm/lima](https://github.com/lima-vm/lima) - Linux virtual machines, with a focus on running containers
* [twpayne/chezmoi](https://github.com/twpayne/chezmoi) - Manage your dotfiles across multiple diverse machines, securely.
* [vitessio/vitess](https://github.com/vitessio/vitess) - Vitess is a database clustering system for horizontal scaling of MySQL.
* [containerd/containerd](https://github.com/containerd/containerd) - An open and reliable container runtime
* [GoogleCloudPlatform/microservices-demo](https://github.com/GoogleCloudPlatform/microservices-demo) - Sample cloud-first application with 10 microservices showcasing Kubernetes, Istio, and gRPC.
* [charmbracelet/vhs](https://github.com/charmbracelet/vhs) - Your CLI home video recorder 📼
* [antonmedv/fx](https://github.com/antonmedv/fx) - Terminal JSON viewer & processor
* [rakyll/hey](https://github.com/rakyll/hey) - HTTP load generator, ApacheBench (ab) replacement
* [ahmetb/kubectx](https://github.com/ahmetb/kubectx) - Faster way to switch between clusters and namespaces in kubectl
* [bettercap/bettercap](https://github.com/bettercap/bettercap) - The Swiss Army knife for 802.11, BLE, HID, CAN-bus, IPv4 and IPv6 networks reconnaissance and MITM attacks.
* [putyy/res-downloader](https://github.com/putyy/res-downloader) - 视频号、小程序、抖音、快手、小红书、直播流、m3u8、酷狗、QQ音乐等常见网络资源下载!
* [lionsoul2014/ip2region](https://github.com/lionsoul2014/ip2region) - Ip2region is an offline IP-to-Region localization library and IP data management framework with both IPv4 and IPv6 supports, 10-microsecond level query efficiency, xdb search client for many programming languages
* [kubernetes/ingress-nginx](https://github.com/kubernetes/ingress-nginx) - Ingress NGINX Controller for Kubernetes *(archived)*
* [google/cadvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers.
* [google/gvisor](https://github.com/google/gvisor) - Application Kernel for Containers
* [slackhq/nebula](https://github.com/slackhq/nebula) - A scalable overlay networking tool with a focus on performance, simplicity and security
* [matryer/xbar](https://github.com/matryer/xbar) - Put the output from any script or program into your macOS Menu Bar (the BitBar reboot)
* [gastownhall/gastown](https://github.com/gastownhall/gastown) - Gas Town - multi-agent workspace manager
* [zincsearch/zincsearch](https://github.com/zincsearch/zincsearch) - ZincSearch . A lightweight alternative to elasticsearch that requires minimal resources, written in Go.
* [sundowndev/phoneinfoga](https://github.com/sundowndev/phoneinfoga) - Information gathering framework for phone numbers
* [bcicen/ctop](https://github.com/bcicen/ctop) - Top-like interface for container metrics
* [influxdata/telegraf](https://github.com/influxdata/telegraf) - Agent for collecting, processing, aggregating, and writing metrics, logs, and other arbitrary data.
* [jmoiron/sqlx](https://github.com/jmoiron/sqlx) - general purpose extensions to golang's database/sql
* [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - VictoriaMetrics: fast, cost-effective monitoring solution and time series database
* [projectdiscovery/katana](https://github.com/projectdiscovery/katana) - A next-generation crawling and spidering framework.
* [joewalnes/websocketd](https://github.com/joewalnes/websocketd) - Turn any program that uses STDIN/STDOUT into a WebSocket server. Like inetd, but for WebSockets.
* [larksuite/cli](https://github.com/larksuite/cli) - The official Lark/飞书 CLI tool, maintained by the larksuite team — built for humans and AI Agents. Covers core business domains including Messenger, Docs, Base, Sheets, Calendar, Mail, Tasks, Meetings, and more, with 200+ commands and 20+ AI Agent Skills.
* [Netflix/chaosmonkey](https://github.com/Netflix/chaosmonkey) - Chaos Monkey is a resiliency tool that helps applications tolerate random instance failures.
* [kubesphere/kubesphere](https://github.com/kubesphere/kubesphere) - The container platform tailored for Kubernetes multi-cloud, datacenter, and edge management ⎈ 🖥 ☁️
* [argoproj/argo-workflows](https://github.com/argoproj/argo-workflows) - Workflow Engine for Kubernetes
* [hashicorp/nomad](https://github.com/hashicorp/nomad) - Nomad is an easy-to-use, flexible, and performant workload orchestrator that can deploy a mix of microservice, batch, containerized, and non-containerized applications. Nomad is easy to operate and scale and has native Consul and Vault integrations.
* [weaviate/weaviate](https://github.com/weaviate/weaviate) - Weaviate is an open-source vector database that stores both objects and vectors, allowing for the combination of vector search with structured filtering with the fault tolerance and scalability of a cloud-native database​.
* [hyperledger/fabric](https://github.com/hyperledger/fabric) - Hyperledger Fabric is an enterprise-grade permissioned distributed ledger framework for developing solutions and applications. Its modular and versatile design satisfies a broad range of industry use cases. It offers a unique approach to consensus that enables performance at scale while preserving privacy.
* [jpillora/chisel](https://github.com/jpillora/chisel) - A fast TCP/UDP tunnel over HTTP
* [googleapis/mcp-toolbox](https://github.com/googleapis/mcp-toolbox) - MCP Toolbox for Databases is an open source MCP server for databases.
* [dagger/dagger](https://github.com/dagger/dagger) - Automation engine to build, test and ship any codebase. Runs locally, in CI, or directly in the cloud
* [mailhog/MailHog](https://github.com/mailhog/MailHog) - Web and API based SMTP testing
* [mikefarah/yq](https://github.com/mikefarah/yq) - yq is a portable command-line YAML, JSON, XML, CSV, TOML, HCL and properties processor
* [dutchcoders/transfer.sh](https://github.com/dutchcoders/transfer.sh) - Easy and fast file sharing from the command-line.
* [gotify/server](https://github.com/gotify/server) - A simple server for sending and receiving messages in real-time per WebSocket. (Includes a sleek web-ui)
* [GoogleContainerTools/skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development
* [hashicorp/packer](https://github.com/hashicorp/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [xpzouying/xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) - MCP for xiaohongshu.com
* [GoogleContainerTools/kaniko](https://github.com/GoogleContainerTools/kaniko) - Build Container Images In Kubernetes *(archived)*
* [plandex-ai/plandex](https://github.com/plandex-ai/plandex) - Open source AI coding agent. Designed for large projects and real world tasks.
* [kgretzky/evilginx2](https://github.com/kgretzky/evilginx2) - Standalone man-in-the-middle attack framework used for phishing login credentials along with session cookies, allowing for the bypass of 2-factor authentication
* [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) - Cloudflare Tunnel client
* [Billionmail/BillionMail](https://github.com/Billionmail/BillionMail) - BillionMail gives you open-source MailServer, NewsLetter, Email Marketing — fully self-hosted, dev-friendly, and free from monthly fees. Join the discord: https://discord.gg/asfXzBUhZr
* [v2rayA/v2rayA](https://github.com/v2rayA/v2rayA) - A web GUI client of Project V which supports VMess, VLESS, SS, SSR, Trojan, Tuic and Juicity protocols. 🚀
* [chenhg5/cc-connect](https://github.com/chenhg5/cc-connect) - Bridge local AI coding agents (Claude Code, Cursor, Gemini CLI, Codex) to messaging platforms (Feishu/Lark, DingTalk, Slack, Telegram, Discord, LINE, WeChat Work). Chat with your AI dev assistant from anywhere — no public IP required for most platforms.
* [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) - Kubernetes IN Docker - local clusters for testing Kubernetes
* [greyireland/algorithm-pattern](https://github.com/greyireland/algorithm-pattern) - Algorithm Patterns — the most scientific way to practice, the fastest path to an offer. You deserve it~ 算法模板，最科学的刷题方式，最快速的刷题路径，你值得拥有~
* [direnv/direnv](https://github.com/direnv/direnv) - unclutter your .profile
* [kubernetes-retired/dashboard](https://github.com/kubernetes-retired/dashboard) - General-purpose web UI for Kubernetes clusters *(archived)*
* [helm/charts](https://github.com/helm/charts) - ⚠️(OBSOLETE) Curated applications for Kubernetes *(archived)*
* [muesli/duf](https://github.com/muesli/duf) - Disk Usage/Free Utility - a better 'df' alternative
* [opensandbox-group/OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) - Secure, Fast, and Extensible Sandbox runtime for AI agents.
* [loft-sh/devpod](https://github.com/loft-sh/devpod) - Codespaces but open-source, client-only and unopinionated: Works with any IDE and lets you use any cloud, kubernetes or just localhost docker.
* [txthinking/brook](https://github.com/txthinking/brook) - A cross-platform programmable network tool
* [zitadel/zitadel](https://github.com/zitadel/zitadel) - ZITADEL - Identity infrastructure, simplified for you.
* [oauth2-proxy/oauth2-proxy](https://github.com/oauth2-proxy/oauth2-proxy) - A reverse proxy that provides authentication with Google, Azure, OpenID Connect and many more identity providers.
* [crowdsecurity/crowdsec](https://github.com/crowdsecurity/crowdsec) - CrowdSec - the open-source and participative security solution offering crowdsourced protection against malicious IPs and access to the most advanced real-world CTI.
* [sqshq/sampler](https://github.com/sqshq/sampler) - Tool for shell commands execution, visualization and alerting. Configured with a simple YAML file.
* [mickael-kerjean/filestash](https://github.com/mickael-kerjean/filestash) - :file_folder: Universal File Storage Client
* [fish2018/pansou](https://github.com/fish2018/pansou) - PanSou是一款高性能的网盘资源搜索API服务，支持TG频道和插件搜索。系统设计以性能和可扩展性为核心，支持多频道多插件并发搜索、结果智能排序和网盘类型分类。docker集成前后端，一键启动，开箱即用。仅供学习研究，请勿以各种形式用于盈利目的。 https://t.me/s/webhtv
* [GoogleCloudPlatform/terraformer](https://github.com/GoogleCloudPlatform/terraformer) - CLI tool to generate terraform files from existing infrastructure (reverse Terraform). Infrastructure to Code *(archived)*
* [shadow1ng/fscan](https://github.com/shadow1ng/fscan) - 一款内网综合扫描工具，方便一键自动化、全方位漏扫扫描。(An intranet comprehensive scanning tool, enabling one-click automated, all-round vulnerability scanning)
* [moonD4rk/HackBrowserData](https://github.com/moonD4rk/HackBrowserData) - Extract and decrypt browser data, supporting multiple data types, runnable on various operating systems (macOS, Windows, Linux).
* [tomnomnom/gron](https://github.com/tomnomnom/gron) - Make JSON greppable!
* [bytebase/bytebase](https://github.com/bytebase/bytebase) - Database governance built for humans and agents — controlling changes and access across every major database.
* [projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder) - Fast passive subdomain enumeration tool.
* [amir20/dozzle](https://github.com/amir20/dozzle) - Realtime log viewer for containers. Supports Docker, Swarm and K8s.
* [benbjohnson/litestream](https://github.com/benbjohnson/litestream) - Streaming replication for SQLite.
* [kopia/kopia](https://github.com/kopia/kopia) - Cross-platform backup tool for Windows, macOS & Linux with fast, incremental backups, client-side end-to-end encryption, compression and data deduplication. CLI and GUI included.
* [rivo/tview](https://github.com/rivo/tview) - Terminal UI library with rich, interactive widgets — written in Golang
* [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager) - Automatically provision and manage TLS certificates in Kubernetes
* [OpenNHP/opennhp](https://github.com/OpenNHP/opennhp) - A lightweight, cryptography-powered, open-source toolkit built to enforce Zero Trust security for infrastructure, applications, and data in the AI-driven world.
* [prometheus/node_exporter](https://github.com/prometheus/node_exporter) - Exporter for machine metrics
* [opencode-ai/opencode](https://github.com/opencode-ai/opencode) - A powerful AI coding agent. Built for the terminal. *(archived)*
* [DNSCrypt/dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) - dnscrypt-proxy 2 - A flexible DNS proxy, with support for encrypted DNS protocols.
* [rook/rook](https://github.com/rook/rook) - Storage Orchestration for Kubernetes
* [gizak/termui](https://github.com/gizak/termui) - Golang terminal dashboard
* [github/gh-ost](https://github.com/github/gh-ost) - GitHub's Online Schema-migration Tool for MySQL
* [cheat/cheat](https://github.com/cheat/cheat) - cheat allows you to create and view interactive cheatsheets on the command-line. It was designed to help remind *nix system administrators of options for commands that they use frequently, but not frequently enough to remember.
* [opencontainers/runc](https://github.com/opencontainers/runc) - CLI tool for spawning and running containers according to the OCI specification
* [golang/groupcache](https://github.com/golang/groupcache) - groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [ccfos/nightingale](https://github.com/ccfos/nightingale) - Nightingale is to monitoring and alerting what Grafana is to visualization.
* [chromedp/chromedp](https://github.com/chromedp/chromedp) - A faster, simpler way to drive browsers supporting the Chrome DevTools Protocol.
* [89luca89/distrobox](https://github.com/89luca89/distrobox) - Use any linux distribution inside your terminal. Enable both backward and forward compatibility with software and freedom to use whatever distribution you’re more comfortable with. Mirror available at: https://gitlab.com/89luca89/distrobox
* [NoFxAiOS/nofx](https://github.com/NoFxAiOS/nofx) - Your AI trading terminal assistant for US stocks, commodities, forex, and crypto.
* [fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl) - Like cURL, but for gRPC: Command-line tool for interacting with gRPC servers
* [elastic/beats](https://github.com/elastic/beats) - :tropical_fish: Beats - Lightweight shippers for Elasticsearch & Logstash
* [infracost/infracost](https://github.com/infracost/infracost) - Cloud cost intelligence for engineers, AI coding agents, and CI/CD 💰📉 Shift FinOps Left!
* [rs/zerolog](https://github.com/rs/zerolog) - Zero Allocation JSON Logger
* [dstotijn/hetty](https://github.com/dstotijn/hetty) - An HTTP toolkit for security research.
* [jetify-com/devbox](https://github.com/jetify-com/devbox) - Instant, easy, and predictable development environments
* [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox) - Instant, Concurrent, Secure & Lightweight Sandbox for AI Agents.
* [open-policy-agent/opa](https://github.com/open-policy-agent/opa) - Open Policy Agent (OPA) is an open source, general-purpose policy engine.
* [kubernetes-sigs/kustomize](https://github.com/kubernetes-sigs/kustomize) - Customization of kubernetes YAML configurations
* [peterq/pan-light](https://github.com/peterq/pan-light) - 百度网盘不限速客户端, golang + qt5, 跨平台图形界面
* [crossplane/crossplane](https://github.com/crossplane/crossplane) - The Cloud Native Control Plane
* [earthly/earthly](https://github.com/earthly/earthly) - Super simple build framework with fast, repeatable builds and an instantly familiar syntax – like Dockerfile and Makefile had a baby.
* [Untrivial-ai/agent-orchestrator](https://github.com/Untrivial-ai/agent-orchestrator) - Run and supervise teams of coding agents from planning to merge. Any harness (Claude code, codex, +25 more). Desktop, web, mobile, and cloud agents.
* [BishopFox/sliver](https://github.com/BishopFox/sliver) - Adversary Emulation Framework
* [gravitl/netmaker](https://github.com/gravitl/netmaker) - Netmaker makes networks with WireGuard. Netmaker automates fast, secure, and distributed virtual networks.
* [kubescape/kubescape](https://github.com/kubescape/kubescape) - Kubescape is an open-source Kubernetes security platform for your IDE, CI/CD pipelines, and clusters. It includes risk analysis, security, compliance, and misconfiguration scanning, saving Kubernetes users and administrators precious time, effort, and resources.
* [grafana/pyroscope](https://github.com/grafana/pyroscope) - Continuous Profiling Platform. Debug performance issues down to a single line of code
* [maaslalani/slides](https://github.com/maaslalani/slides) - Terminal based presentation tool
* [owncast/owncast](https://github.com/owncast/owncast) - Take control over your live stream video by running it yourself. Streaming + chat out of the box.
* [linkerd/linkerd2](https://github.com/linkerd/linkerd2) - Ultralight, security-first service mesh for Kubernetes. Main repo for Linkerd 2.x.
* [bufbuild/buf](https://github.com/bufbuild/buf) - The best way of working with Protocol Buffers.
* [loft-sh/vcluster](https://github.com/loft-sh/vcluster) - vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.
* [podman-container-tools/skopeo](https://github.com/podman-container-tools/skopeo) - Work with remote images registries - retrieving information, images, signing content
* [blevesearch/bleve](https://github.com/blevesearch/bleve) - A modern text/numeric/geo-spatial/vector indexing library for go
* [dexidp/dex](https://github.com/dexidp/dex) - OpenID Connect (OIDC) identity and OAuth 2.0 provider with pluggable connectors
* [hashicorp/terraform-provider-aws](https://github.com/hashicorp/terraform-provider-aws) - The AWS Provider enables Terraform to manage AWS resources.
* [imgproxy/imgproxy](https://github.com/imgproxy/imgproxy) - Fast and secure standalone server for resizing, processing, and converting images on the fly
* [centrifugal/centrifugo](https://github.com/centrifugal/centrifugo) - Scalable real-time messaging server in a language-agnostic way. Self-hosted alternative to Pubnub, Pusher, Ably, socket.io, Phoenix.PubSub, SignalR. Set up once and forever.
* [distribution/distribution](https://github.com/distribution/distribution) - The toolkit to pack, ship, store, and deliver container content
* [kedacore/keda](https://github.com/kedacore/keda) - KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes
* [claudiodangelis/qrcp](https://github.com/claudiodangelis/qrcp) - :zap: Transfer files over wifi from your computer to your mobile device by scanning a QR code without leaving the terminal.
* [esimov/caire](https://github.com/esimov/caire) - Content aware image resize library
* [stakater/Reloader](https://github.com/stakater/Reloader) - A Kubernetes controller to watch changes in ConfigMap and Secrets and do rolling upgrades on Pods with their associated Deployment, StatefulSet, DaemonSet and DeploymentConfig – [✩Star] if you're using it!
* [projectdiscovery/httpx](https://github.com/projectdiscovery/httpx) - httpx is a fast and multi-purpose HTTP toolkit that allows running multiple probes using the retryablehttp library.
* [containerd/nerdctl](https://github.com/containerd/nerdctl) - contaiNERD CTL - Docker-compatible CLI for containerd, with support for Compose, Rootless, eStargz, OCIcrypt, IPFS, ...
* [noisetorch/NoiseTorch](https://github.com/noisetorch/NoiseTorch) - Real-time microphone noise suppression on Linux.
* [nezhahq/nezha](https://github.com/nezhahq/nezha) - :trollface: Self-hosted, lightweight server and website monitoring and O&M tool
* [sourcegraph/sourcegraph-public-snapshot](https://github.com/sourcegraph/sourcegraph-public-snapshot) - Code AI platform with Code Search & Cody *(archived)*
* [velero-io/velero](https://github.com/velero-io/velero) - Backup and migrate Kubernetes applications and their persistent volumes
* [pinchtab/pinchtab](https://github.com/pinchtab/pinchtab) - High-performance browser automation bridge and multi-instance orchestrator with advanced stealth injection and real-time dashboard.
* [gwuhaolin/livego](https://github.com/gwuhaolin/livego) - live video streaming server in golang
* [tilt-dev/tilt](https://github.com/tilt-dev/tilt) - Define your dev environment as code. For microservice apps on Kubernetes.
* [git-bug/git-bug](https://github.com/git-bug/git-bug) - Distributed, offline-first bug tracker embedded in git
* [johnkerl/miller](https://github.com/johnkerl/miller) - Miller is like awk, sed, cut, join, and sort for name-indexed data such as CSV, TSV, and tabular JSON
* [prometheus-operator/prometheus-operator](https://github.com/prometheus-operator/prometheus-operator) - Prometheus Operator creates/configures/manages Prometheus clusters atop Kubernetes
* [lk-geimfari/awesomo](https://github.com/lk-geimfari/awesomo) - Cool open source projects. Choose your project and get involved in Open Source development now.
* [alireza0/s-ui](https://github.com/alireza0/s-ui) - An advanced Web Panel • Built for SagerNet/Sing-Box
* [gruntwork-io/terragrunt](https://github.com/gruntwork-io/terragrunt) - Terragrunt is a flexible orchestration tool that allows Infrastructure as Code written in OpenTofu/Terraform to scale.
* [gorse-io/gorse](https://github.com/gorse-io/gorse) - AI powered open source recommender system engine supports classical/LLM rankers and multimodal content via embedding
* [tidwall/tile38](https://github.com/tidwall/tile38) - Real-time Geospatial and Geofencing
* [bytedance/sonic](https://github.com/bytedance/sonic) - A blazingly fast JSON serializing & deserializing library
* [gokcehan/lf](https://github.com/gokcehan/lf) - Terminal file manager
* [sosedoff/pgweb](https://github.com/sosedoff/pgweb) - Cross-platform client for PostgreSQL databases
* [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community) - Community managed domain list. Generate geosite.dat for V2Ray.
* [replicate/cog](https://github.com/replicate/cog) - Containers for machine learning
* [hybridgroup/gobot](https://github.com/hybridgroup/gobot) - Golang framework for robotics, drones, and the Internet of Things (IoT)
* [cloudflare/cfssl](https://github.com/cloudflare/cfssl) - CFSSL: Cloudflare's PKI and TLS toolkit
* [cadence-workflow/cadence](https://github.com/cadence-workflow/cadence) - Cadence is a distributed, scalable, durable, and highly available orchestration engine to execute asynchronous long-running business logic in a scalable and resilient way.
* [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) - Machine Learning for Go
* [higress-group/higress](https://github.com/higress-group/higress) - 🤖 AI Gateway | AI Native API Gateway
* [kubernetes-sigs/kubebuilder](https://github.com/kubernetes-sigs/kubebuilder) - Kubebuilder - SDK for building Kubernetes APIs using CRDs
* [certimate-go/certimate](https://github.com/certimate-go/certimate) - An open-source and free self-hosted SSL certificates ACME tool, automates the full-cycle of issuance, deployment, renewal, and monitoring visually. 完全开源免费的自托管 SSL 证书 ACME 工具，申请、部署、续期、监控全流程自动化可视化，支持各大主流云厂商。
* [nhost/nhost](https://github.com/nhost/nhost) - The Open Source Firebase Alternative with GraphQL.
* [cloudnative-pg/cloudnative-pg](https://github.com/cloudnative-pg/cloudnative-pg) - The most popular Kubernetes Operator for PostgreSQL.
* [bitnami/sealed-secrets](https://github.com/bitnami/sealed-secrets) - A Kubernetes controller and tool for one-way encrypted Secrets
* [google/pprof](https://github.com/google/pprof) - pprof is a tool for visualization and analysis of profiling data
* [ltaoo/wx_channels_download](https://github.com/ltaoo/wx_channels_download) - 微信视频号下载器
* [pocket-id/pocket-id](https://github.com/pocket-id/pocket-id) - The most user-friendly OpenID Connect Certified™ and OAuth 2.0 provider that lets users sign in to your applications with passkeys.
* [hashicorp/raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol
* [dinedal/textql](https://github.com/dinedal/textql) - Execute SQL against structured text like CSV or TSV
* [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns) - Configure external DNS servers dynamically from Kubernetes resources
* [tektoncd/pipeline](https://github.com/tektoncd/pipeline) - A cloud-native Pipeline resource.
* [podman-container-tools/buildah](https://github.com/podman-container-tools/buildah) - A tool that facilitates building OCI images.
* [99designs/aws-vault](https://github.com/99designs/aws-vault) - A vault for securely storing and accessing AWS credentials in development environments
* [everywall/ladder](https://github.com/everywall/ladder) - Selfhosted alternative to 12ft.io. and 1ft.io. Proxy to remove CORS headers and modify HTML
* [kubernetes/autoscaler](https://github.com/kubernetes/autoscaler) - Autoscaling components for Kubernetes
* [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) - A package to build progressive web apps with Go programming language and WebAssembly.
* [prasmussen/gdrive](https://github.com/prasmussen/gdrive) - Google Drive CLI Client *(archived)*
* [charmbracelet/bubbles](https://github.com/charmbracelet/bubbles) - TUI components for Bubble Tea 🫧
* [akavel/up](https://github.com/akavel/up) - Ultimate Plumber is a tool for writing Linux pipes with instant live preview
* [apex/up](https://github.com/apex/up) - Deploy infinitely scalable serverless apps, apis, and sites in seconds to AWS.
* [XiaoMi/soar](https://github.com/XiaoMi/soar) - SQL Optimizer And Rewriter
* [ariga/atlas](https://github.com/ariga/atlas) - Declarative schema migrations with schema-as-code workflows
* [OwO-Network/DLX](https://github.com/OwO-Network/DLX) - DLX - Self-hosted translation API server. Unofficial; not affiliated with DeepL SE.
* [ViRb3/wgcf](https://github.com/ViRb3/wgcf) - 🚤 Cross-platform, unofficial CLI for Cloudflare Warp
* [SeleniumHQ/docker-selenium](https://github.com/SeleniumHQ/docker-selenium) - Provides a simple way to run Selenium Grid with Chrome, Firefox, and Edge using Container Platform, making it easier to perform browser automation at scale
* [linuxkit/linuxkit](https://github.com/linuxkit/linuxkit) - A toolkit for building secure, portable and lean operating systems for containers
* [prometheus/alertmanager](https://github.com/prometheus/alertmanager) - Prometheus Alertmanager
* [HavocFramework/Havoc](https://github.com/HavocFramework/Havoc) - The Havoc Framework *(archived)*
* [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad) - Manage multiple AI terminal agents like Claude Code, Codex, OpenCode, and Amp.
* [kunchenguid/no-mistakes](https://github.com/kunchenguid/no-mistakes) - git push no-mistakes
* [kelseyhightower/confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul
* [gonum/gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more
* [fluxcd/flux2](https://github.com/fluxcd/flux2) - Open and extensible continuous delivery solution for Kubernetes. Powered by GitOps Toolkit.
* [metallb/metallb](https://github.com/metallb/metallb) - A network load-balancer implementation for Kubernetes using standard routing protocols
* [gtsteffaniak/filebrowser](https://github.com/gtsteffaniak/filebrowser) - 📂 Web File Browser
* [pkg/errors](https://github.com/pkg/errors) - Simple error handling primitives
* [smartcontractkit/chainlink](https://github.com/smartcontractkit/chainlink) - node of the decentralized oracle network, bridging on and off-chain computation
* [AnalogJ/scrutiny](https://github.com/AnalogJ/scrutiny) - Hard Drive S.M.A.R.T Monitoring, Historical Trends & Real World Failure Thresholds
* [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) - Lightning Network Daemon ⚡️
* [aquasecurity/kube-bench](https://github.com/aquasecurity/kube-bench) - Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark
* [k8sgpt-ai/k8sgpt](https://github.com/k8sgpt-ai/k8sgpt) - Giving Kubernetes Superpowers to everyone
* [nxtrace/NTrace-core](https://github.com/nxtrace/NTrace-core) - NextTrace, an open source visual route tracking CLI tool
* [kyverno/kyverno](https://github.com/kyverno/kyverno) - Unified Policy as Code
* [gdy666/lucky](https://github.com/gdy666/lucky) - 软硬路由公网神器,ipv6/ipv4 端口转发,反向代理,DDNS,WOL,ipv4 stun内网穿透,cron,acme,rclone,ftp,webdav,filebrowser
* [mmulet/term.everything](https://github.com/mmulet/term.everything) - Run any GUI app in the terminal❗
* [iyear/tdl](https://github.com/iyear/tdl) - 📥 A Telegram toolkit written in Golang
* [maximhq/bifrost](https://github.com/maximhq/bifrost) - Fastest enterprise AI gateway (50x faster than LiteLLM) with adaptive load balancer, cluster mode, guardrails, 1000+ models support & <100 µs overhead at 5k RPS.
* [usefathom/fathom](https://github.com/usefathom/fathom) - Fathom Lite. Simple, privacy-focused website analytics. Built with Golang & Preact.
* [cortexlabs/cortex](https://github.com/cortexlabs/cortex) - Production infrastructure for machine learning at scale
* [golang/tools](https://github.com/golang/tools) - [mirror] Go Tools
* [Masterminds/squirrel](https://github.com/Masterminds/squirrel) - Fluent SQL generation for golang
* [turbot/steampipe](https://github.com/turbot/steampipe) - Zero-ETL, infinite possibilities. Live query APIs, code & more with SQL. No DB required.
* [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) - 🪓 An orchestration engine for background tasks, AI agents, and durable workflows
* [coroot/coroot](https://github.com/coroot/coroot) - Coroot is an open-source observability and APM tool with AI-powered Root Cause Analysis. It combines metrics, logs, traces, continuous profiling, and SLO-based alerting with predefined dashboards and inspections.
* [peco/peco](https://github.com/peco/peco) - Simplistic interactive filtering tool
* [chaos-mesh/chaos-mesh](https://github.com/chaos-mesh/chaos-mesh) - A Chaos Engineering Platform for Kubernetes.
* [kubevela/kubevela](https://github.com/kubevela/kubevela) - The Modern Application Platform.
* [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) - Woodpecker is a simple, yet powerful CI/CD engine with great extensibility.
* [flynn/flynn](https://github.com/flynn/flynn) - [UNMAINTAINED] A next generation open source platform as a service (PaaS) *(archived)*
* [aws/karpenter-provider-aws](https://github.com/aws/karpenter-provider-aws) - Karpenter is a Kubernetes Node Autoscaler built for flexibility, performance, and simplicity.
* [go-git/go-git](https://github.com/go-git/go-git) - A highly extensible Git implementation in pure Go.
* [operator-framework/operator-sdk](https://github.com/operator-framework/operator-sdk) - SDK for building Kubernetes applications. Provides high level APIs, useful abstractions, and project scaffolding.
* [chenyme/grok2api](https://github.com/chenyme/grok2api) - Multi-account API gateway for Grok Build, Grok Web, and Grok Console
* [MightyMoud/sidekick](https://github.com/MightyMoud/sidekick) - Bare metal to production ready in mins; your own fly server on your VPS.
* [andeya/pholcus](https://github.com/andeya/pholcus) - Pholcus is a distributed high-concurrency crawler software written in pure golang
* [kubeedge/kubeedge](https://github.com/kubeedge/kubeedge) - Kubernetes Native Edge Computing Framework (project under CNCF)
* [42wim/matterbridge](https://github.com/42wim/matterbridge) - bridge between mattermost, IRC, gitter, xmpp, slack, discord, telegram, rocketchat, twitch, ssh-chat, zulip, whatsapp, keybase, matrix, microsoft teams, nextcloud, mumble, vk and more with REST API (mattermost not required!)
* [GoogleCloudPlatform/kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - AI powered Kubernetes Assistant
* [open-telemetry/opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) - OpenTelemetry Collector
* [urfave/negroni](https://github.com/urfave/negroni) - Idiomatic HTTP Middleware for Golang
* [hybridgroup/gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 4 and beyond. Includes support for DNN, CUDA, OpenCV Contrib, and OpenVINO.
* [flyteorg/flyte](https://github.com/flyteorg/flyte) - Dynamic, resilient AI orchestration. Coordinate data, models, and compute as you build AI workflows.
* [shopspring/decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers in Go
* [attic-labs/noms](https://github.com/attic-labs/noms) - The versioned, forkable, syncable database *(archived)*
* [Hackl0us/GeoIP2-CN](https://github.com/Hackl0us/GeoIP2-CN) - 小巧精悍、准确、实用 GeoIP2 数据库
* [Terry-Mao/goim](https://github.com/Terry-Mao/goim) - goim
* [projectcalico/calico](https://github.com/projectcalico/calico) - Cloud native networking and network security
* [telepresenceio/telepresence](https://github.com/telepresenceio/telepresence) - Local development against a remote Kubernetes or OpenShift cluster
* [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) - A community driven registry service for Model Context Protocol (MCP) servers.
* [perkeep/perkeep](https://github.com/perkeep/perkeep) - Perkeep (née Camlistore) is your personal storage system for life: a way of storing, syncing, sharing, modelling and backing up content.
* [evcc-io/evcc](https://github.com/evcc-io/evcc) - solar charging ☀️🚘
* [open-falcon/falcon-plus](https://github.com/open-falcon/falcon-plus) - An open-source and enterprise-level monitoring system. *(archived)*
* [sysadminsmedia/homebox](https://github.com/sysadminsmedia/homebox) - A continuation of HomeBox the inventory and organization system built for the Home User
* [charmbracelet/soft-serve](https://github.com/charmbracelet/soft-serve) - The mighty, self-hostable Git server for the command line🍦
* [davecheney/httpstat](https://github.com/davecheney/httpstat) - It's like curl -v, with colours.
* [charmbracelet/huh](https://github.com/charmbracelet/huh) - Build terminal forms and prompts 🤷🏻‍♀️
* [liamg/traitor](https://github.com/liamg/traitor) - :arrow_up: :skull_and_crossbones: :fire: Automatic Linux privesc via exploitation of low-hanging fruit e.g. gtfobins, pwnkit, dirty pipe, +w docker.sock
* [kubevirt/kubevirt](https://github.com/kubevirt/kubevirt) - Kubernetes Virtualization API and runtime in order to define and manage virtual machines.
* [authzed/spicedb](https://github.com/authzed/spicedb) - Open Source, Google Zanzibar-inspired database for scalably storing and querying fine-grained authorization data
* [kubernetes-sigs/krew](https://github.com/kubernetes-sigs/krew) - 📦 Find and install kubectl plugins
* [tailscale/tailcat](https://github.com/tailscale/tailcat) - like netcat, but over Tailscale's data plane, without Tailscale's control plane
* [masterking32/MasterDnsVPN](https://github.com/masterking32/MasterDnsVPN) - Advanced DNS tunneling VPN for censorship bypass, optimized beyond DNSTT and SlipStream with low-overhead ARQ, resolver load balancing, high packet-loss stability and speed.
* [CarterPerez-dev/Cybersecurity-Projects](https://github.com/CarterPerez-dev/Cybersecurity-Projects) - Building 70 Projects ranging from beginner to advanced so anyone can — learn from, build upon, use as a reference, or even copy directly. Gamified Cybersecurity learning 👇
* [0xERR0R/blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features
* [external-secrets/external-secrets](https://github.com/external-secrets/external-secrets) - External Secrets Operator reads information from a third-party service like AWS Secrets Manager and automatically injects the values as Kubernetes Secrets.
* [fluxcd/flux](https://github.com/fluxcd/flux) - Successor: https://github.com/fluxcd/flux2 *(archived)*
* [fleetdm/fleet](https://github.com/fleetdm/fleet) - Open device management
* [vmware-archive/kubeless](https://github.com/vmware-archive/kubeless) - Kubernetes Native Serverless Framework *(archived)*
* [StackExchange/blackbox](https://github.com/StackExchange/blackbox) - Safely store secrets in Git/Mercurial/Subversion *(archived)*
* [Gentleman-Programming/gentle-ai](https://github.com/Gentleman-Programming/gentle-ai) - Gentle-AI configures the AI coding agents you already use: Claude Code, Cursor, OpenCode, Codex, Pi, and more. Choose persistent memory, Spec-Driven Development, curated skills, MCP servers, personas, and optional bounded review. Open source, no agent lock-in.
* [opencost/opencost](https://github.com/opencost/opencost) - Cost monitoring for Kubernetes workloads and cloud costs
* [uber/kraken](https://github.com/uber/kraken) - P2P Docker registry capable of distributing TBs of data in seconds
* [kubernetes-sigs/metrics-server](https://github.com/kubernetes-sigs/metrics-server) - Scalable and efficient source of container resource metrics for Kubernetes built-in autoscaling pipelines.
* [AIPentest/CyberStrikeAI](https://github.com/AIPentest/CyberStrikeAI) - The system of action for AI-native cybersecurity—where intent becomes governed execution, evidence becomes operational memory, and every operation improves the next.
* [docker-archive-public/docker.machine](https://github.com/docker-archive-public/docker.machine) - Machine management for a container-centric world *(archived)*
* [xataio/pgroll](https://github.com/xataio/pgroll) - PostgreSQL zero-downtime migrations made easy
* [photoview/photoview](https://github.com/photoview/photoview) - Photo gallery for self-hosted personal servers
* [actions/actions-runner-controller](https://github.com/actions/actions-runner-controller) - Kubernetes controller for GitHub Actions self-hosted runners
* [muesli/beehive](https://github.com/muesli/beehive) - A flexible event/agent & automation system with lots of bees 🐝
* [k0sproject/k0s](https://github.com/k0sproject/k0s) - k0s - The Zero Friction Kubernetes
* [ethereum-optimism/optimism](https://github.com/ethereum-optimism/optimism) - Optimism is Ethereum, scaled.
* [rancher/os](https://github.com/rancher/os) - Tiny Linux distro that runs the entire OS as Docker containers *(archived)*
* [manifoldco/promptui](https://github.com/manifoldco/promptui) - Interactive prompt for command-line applications
* [upspin/upspin](https://github.com/upspin/upspin) - Upspin: A framework for naming everyone's everything.
* [go-telegram-bot-api/telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) - Golang bindings for the Telegram Bot API
* [flike/kingshard](https://github.com/flike/kingshard) - A high-performance MySQL proxy
* [datreeio/datree](https://github.com/datreeio/datree) - Prevent Kubernetes misconfigurations from reaching production (again 😤 )! From code to cloud, Datree provides an E2E policy enforcement solution to run automatic checks for rule violations. See our docs: https://hub.datree.io *(archived)*
* [google/syzkaller](https://github.com/google/syzkaller) - syzkaller is an unsupervised coverage-guided kernel fuzzer
* [sigstore/cosign](https://github.com/sigstore/cosign) - Code signing and transparency for containers and binaries
* [goodrain/rainbond](https://github.com/goodrain/rainbond) - Rainbond is an AI application runtime platform. Its core capabilities are 100% open source. Rainbond provides a unified platform for running and managing AI-generated projects, large language model services, open-source AI software, and business applications. With AI-powered deployment, troubleshooting, upgrades, and operations, it keeps applicati
* [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) - WhatsApp MCP server
* [bfenetworks/bfe](https://github.com/bfenetworks/bfe) - A modern layer 7 load balancer from baidu
* [cue-lang/cue](https://github.com/cue-lang/cue) - The home of the CUE language! Validate and define text-based and dynamic configuration
* [jpillora/cloud-torrent](https://github.com/jpillora/cloud-torrent) - ☁️ Cloud Torrent: a self-hosted remote torrent client
* [achannarasappa/ticker](https://github.com/achannarasappa/ticker) - Track stocks, crypto, and derivatives prices and positions in real time from your terminal
* [golang/mobile](https://github.com/golang/mobile) - [mirror] Go on Mobile
* [kubernetes/kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) - Add-on agent to generate and expose cluster-level metrics.
* [michenriksen/gitrob](https://github.com/michenriksen/gitrob) - Reconnaissance tool for GitHub organizations *(archived)*
* [daeuniverse/dae](https://github.com/daeuniverse/dae) - eBPF-based Linux high-performance transparent proxy solution.
* [komari-monitor/komari](https://github.com/komari-monitor/komari) - A simple server monitor tool.
* [DominicBreuker/pspy](https://github.com/DominicBreuker/pspy) - Monitor linux processes without root permissions
* [GhostTroops/scan4all](https://github.com/GhostTroops/scan4all) - Official repository vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)...
* [azukaar/Cosmos-Server](https://github.com/azukaar/Cosmos-Server) - ☁️ The Most Secure and Easy Selfhosted Home Server. Take control of your data and privacy without sacrificing security and stability (Authentication, anti-DDOS, anti-bot)
* [contribsys/faktory](https://github.com/contribsys/faktory) - Language-agnostic persistent background job server
* [containernetworking/cni](https://github.com/containernetworking/cni) - Container Network Interface - networking for Linux containers
* [vale-cli/vale](https://github.com/vale-cli/vale) - :pencil: A markup-aware linter for prose built with speed and extensibility in mind.
* [chriswalz/bit](https://github.com/chriswalz/bit) - Bit is a modern Git CLI
* [knative/serving](https://github.com/knative/serving) - Kubernetes-based, scale-to-zero, request-driven compute
* [foxcpp/maddy](https://github.com/foxcpp/maddy) - ✉️ Composable all-in-one mail server.
* [h2non/imaginary](https://github.com/h2non/imaginary) - Fast, simple, scalable, Docker-ready HTTP microservice for high-level image processing
* [hashicorp/serf](https://github.com/hashicorp/serf) - Service orchestration and management tool.
* [docker/cli](https://github.com/docker/cli) - The Docker CLI
* [vcaesar/riot](https://github.com/vcaesar/riot) - Go Open Source, Distributed, Simple and efficient Search Engine
* [Ackites/KillWxapkg](https://github.com/Ackites/KillWxapkg) - 自动化反编译微信小程序，小程序安全评估工具，发现小程序安全问题，自动解密，解包，可还原工程目录，支持Hook，小程序修改
* [opencloud-eu/opencloud](https://github.com/opencloud-eu/opencloud) - 🌤️ OpenCloud is the open source platform for file management, sharing and collaboration. Simple and sovereign.
* [michenriksen/aquatone](https://github.com/michenriksen/aquatone) - A Tool for Domain Flyovers *(archived)*
* [Permify/permify](https://github.com/Permify/permify) - An open-source authorization as a service inspired by Google Zanzibar, designed to build and manage fine-grained and scalable authorization systems for any application. — Permify is now part of FusionAuth 🎉
* [guangzhengli/k8s-tutorials](https://github.com/guangzhengli/k8s-tutorials) - k8s tutorials | k8s 教程
* [fnproject/fn](https://github.com/fnproject/fn) - The container native, cloud agnostic serverless platform.
* [nilsherzig/LLocalSearch](https://github.com/nilsherzig/LLocalSearch) - LLocalSearch is a completely locally running search aggregator using LLM Agents. The user can ask a question and the system will use a chain of LLMs to find the answer. The user can see the progress of the agents and the final answer. No OpenAI or Google API keys are needed. *(archived)*
* [alda-lang/alda](https://github.com/alda-lang/alda) - A music programming language for musicians. :notes:
* [volcano-sh/volcano](https://github.com/volcano-sh/volcano) - A Cloud Native Batch System (Project under CNCF)
* [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) - Gorgonia is a library that helps facilitate machine learning in Go.
* [dragonflyoss/dragonfly-archived](https://github.com/dragonflyoss/dragonfly-archived) - This repository has be archived and moved to the new repository https://github.com/dragonflyoss/Dragonfly2. *(archived)*
* [shazow/ssh-chat](https://github.com/shazow/ssh-chat) - Chat over SSH.
* [weaveworks/scope](https://github.com/weaveworks/scope) - Monitoring, visualisation & management for Docker & Kubernetes
* [samchon/typia](https://github.com/samchon/typia) - Super-fast/easy runtime validators and serializers via transformation
* [kenn-io/agentsview](https://github.com/kenn-io/agentsview) - Local-first session search, analytics, insights, and token use statistics for coding agents, supporting Claude Code, Codex, and more than 20 other agents.
* [kserve/kserve](https://github.com/kserve/kserve) - Standardized Distributed Generative and Predictive AI Inference Platform for Scalable, Multi-Framework Deployment on Kubernetes
* [prometheus/blackbox_exporter](https://github.com/prometheus/blackbox_exporter) - Blackbox prober exporter
* [microsoft/ethr](https://github.com/microsoft/ethr) - Ethr is a Comprehensive Network Measurement Tool for TCP, UDP & ICMP.
* [cortexproject/cortex](https://github.com/cortexproject/cortex) - A horizontally scalable, highly available, multi-tenant, long term Prometheus.
* [mjl-/mox](https://github.com/mjl-/mox) - modern full-featured open source secure mail server for low-maintenance self-hosted email
* [sammwyy/MikuMikuBeam](https://github.com/sammwyy/MikuMikuBeam) - An open-source network stresser tool but it's Hatsune Miku
* [inngest/inngest](https://github.com/inngest/inngest) - The leading workflow orchestration platform. Run stateful step functions and AI workflows on serverless, servers, or the edge.
* [ghuntley/how-to-build-a-coding-agent](https://github.com/ghuntley/how-to-build-a-coding-agent) - A workshop that teaches you how to build your own coding agent. Similar to Roo code, Cline, Amp, Cursor, Windsurf or OpenCode.
* [terraform-linters/tflint](https://github.com/terraform-linters/tflint) - A Pluggable Terraform Linter
* [marcel-dempers/docker-development-youtube-series](https://github.com/marcel-dempers/docker-development-youtube-series)
* [hashicorp/hcl](https://github.com/hashicorp/hcl) - HCL is the HashiCorp configuration language.
* [vllm-project/semantic-router](https://github.com/vllm-project/semantic-router) - A programmable Mixture-of-Models router for heterogeneous LLM inference
* [windtf/wireproxy](https://github.com/windtf/wireproxy) - Wireguard client that exposes itself as a socks5 proxy
* [rebuy-de/aws-nuke](https://github.com/rebuy-de/aws-nuke) - Nuke a whole AWS account and delete all its resources. *(archived)*
* [openark/orchestrator](https://github.com/openark/orchestrator) - MySQL replication topology management and HA *(archived)*
* [TencentBlueKing/bk-cmdb](https://github.com/TencentBlueKing/bk-cmdb) - 蓝鲸智云配置平台(BlueKing CMDB)
* [docker-archive/docker-ce](https://github.com/docker-archive/docker-ce) - :warning: This repository is deprecated and will be archived (Docker CE itself is NOT deprecated) see the https://github.com/docker/docker-ce/blob/master/README.md :warning: *(archived)*
* [coze-dev/coze-loop](https://github.com/coze-dev/coze-loop) - Next-generation AI Agent Optimization Platform: Cozeloop addresses challenges in AI agent development by providing full-lifecycle management capabilities from development, debugging, and evaluation to monitoring.
* [docker-archive/classicswarm](https://github.com/docker-archive/classicswarm) - Swarm Classic: a container clustering system. Not to be confused with Docker Swarm which is at https://github.com/docker/swarmkit *(archived)*
* [coder/sshcode](https://github.com/coder/sshcode) - Run VS Code on any server over SSH. *(archived)*
* [ossf/scorecard](https://github.com/ossf/scorecard) - OpenSSF Scorecard - Security health metrics for Open Source
* [kgateway-dev/kgateway](https://github.com/kgateway-dev/kgateway) - The Cloud-Native API Gateway and AI Gateway
* [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy) - A new generation cloud backup tool
* [google/seesaw](https://github.com/google/seesaw) - Seesaw v2 is a Linux Virtual Server (LVS) based load balancing platform.
* [mostlygeek/llama-swap](https://github.com/mostlygeek/llama-swap) - Reliable model swapping for any local OpenAI/Anthropic compatible server - llama.cpp, vllm, etc
* [cri-o/cri-o](https://github.com/cri-o/cri-o) - Open Container Initiative-based implementation of Kubernetes Container Runtime Interface
* [cubefs/cubefs](https://github.com/cubefs/cubefs) - cloud-native distributed storage
* [Jrohy/trojan](https://github.com/Jrohy/trojan) - trojan多用户管理部署程序, 支持web页面管理
* [karmada-io/karmada](https://github.com/karmada-io/karmada) - Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration
* [agentscope-ai/AgentTeams](https://github.com/agentscope-ai/AgentTeams) - An open-source Collaborative Multi-Agent OS for transparent, human-in-the-loop task coordination via Matrix rooms.
* [the-open-agent/openagent](https://github.com/the-open-agent/openagent) - ⚡️next-generation personal AI assistant powered by LLM, RAG and agent loops, supporting computer-use, browser-use and coding agent, demo: https://demo.openagentai.org
* [umputun/remark42](https://github.com/umputun/remark42) - comment engine
* [litmuschaos/litmus](https://github.com/litmuschaos/litmus) - Litmus helps SREs and developers practice chaos engineering in a Cloud-native way. Chaos experiments are published at the ChaosHub (https://hub.litmuschaos.io). Community notes is at https://hackmd.io/a4Zu_sH4TZGeih-xCimi3Q
* [cgzirim/seek-tune](https://github.com/cgzirim/seek-tune) - An implementation of Shazam's song recognition algorithm.
* [Ne0nd0g/merlin](https://github.com/Ne0nd0g/merlin) - Merlin is a cross-platform post-exploitation HTTP/2 Command & Control server and agent written in golang.
* [devtron-labs/devtron](https://github.com/devtron-labs/devtron) - The only Kubernetes dashboard you need
* [mayswind/ezbookkeeping](https://github.com/mayswind/ezbookkeeping) - ezBookkeeping is an open source, powerful, self-hosted personal finance app that is easy to use.
* [kubernetes-sigs/descheduler](https://github.com/kubernetes-sigs/descheduler) - Descheduler for Kubernetes
* [charmbracelet/wish](https://github.com/charmbracelet/wish) - Make SSH apps, just like that! 💫
* [psviderski/uncloud](https://github.com/psviderski/uncloud) - A lightweight tool for deploying and managing containerised applications across a network of Docker hosts. Bridging the gap between Docker and Kubernetes ✨
* [XTLS/REALITY](https://github.com/XTLS/REALITY) - THE NEXT FUTURE
* [grafana/tempo](https://github.com/grafana/tempo) - Grafana Tempo is a high volume, minimal dependency distributed tracing backend.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Golang library for managing configuration data from environment variables
* [unkeyed/unkey](https://github.com/unkeyed/unkey) - The Developer Platform for Modern APIs
* [drk1wi/Modlishka](https://github.com/drk1wi/Modlishka) - Modlishka. Reverse Proxy.
* [google/battery-historian](https://github.com/google/battery-historian) - Battery Historian is a tool to analyze battery consumers using Android "bugreport" files. *(archived)*
* [fluxcd/flagger](https://github.com/fluxcd/flagger) - Progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments)
* [go-vikunja/vikunja](https://github.com/go-vikunja/vikunja) - The task manager you actually own.
* [trustwallet/assets](https://github.com/trustwallet/assets) - A comprehensive, up-to-date collection of information about several thousands (!) of crypto tokens.
* [openkruise/kruise](https://github.com/openkruise/kruise) - Automated management of large-scale applications on Kubernetes (incubating project under CNCF)
* [dunglas/mercure](https://github.com/dunglas/mercure) - 🪽 An open, easy, fast, reliable and battery-efficient solution for real-time communications
* [google/git-appraise](https://github.com/google/git-appraise) - Distributed code review system for Git repos
* [beclab/Olares](https://github.com/beclab/Olares) - Open-Source Personal Cloud OS for Always-On Agents
* [zalando/postgres-operator](https://github.com/zalando/postgres-operator) - Postgres operator creates and manages PostgreSQL clusters running in Kubernetes
* [grafana/mimir](https://github.com/grafana/mimir) - Grafana Mimir provides horizontally scalable, highly available, multi-tenant, long-term storage for Prometheus.
* [blushft/go-diagrams](https://github.com/blushft/go-diagrams) - Create beautiful system diagrams with Go
* [dromara/carbon](https://github.com/dromara/carbon) - A simple, semantic and developer-friendly time package for golang
* [looplj/axonhub](https://github.com/looplj/axonhub) - ⚡️ Open-source AI Gateway — Use any SDK to call 100+ LLMs. Built-in failover, load balancing, cost control & end-to-end tracing.
* [gdamore/tcell](https://github.com/gdamore/tcell) - Tcell is an alternate terminal package, similar in some ways to termbox, but better in others.
* [tenable/terrascan](https://github.com/tenable/terrascan) - Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure. *(archived)*
* [eksctl-io/eksctl](https://github.com/eksctl-io/eksctl) - The official CLI for Amazon EKS
* [crazy-max/WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker) - Block spying and tracking on Windows
* [helmfile/helmfile](https://github.com/helmfile/helmfile) - Declaratively deploy your Kubernetes manifests, Kustomize configs, and Charts as Helm releases. Generate all-in-one manifests for use with ArgoCD.
* [Ullaakut/cameradar](https://github.com/Ullaakut/cameradar) - Cameradar hacks its way into RTSP videosurveillance cameras
* [sql-machine-learning/sqlflow](https://github.com/sql-machine-learning/sqlflow) - Brings SQL and AI together.
* [devspace-sh/devspace](https://github.com/devspace-sh/devspace) - DevSpace - The Fastest Developer Tool for Kubernetes ⚡ Automate your deployment workflow with DevSpace and develop software directly inside Kubernetes.
* [harvester/harvester](https://github.com/harvester/harvester) - Open source hyperconverged infrastructure (HCI) software
* [ngoduykhanh/wireguard-ui](https://github.com/ngoduykhanh/wireguard-ui) - Wireguard web interface
* [taubyte/tau](https://github.com/taubyte/tau) - Fullstack Workspace for Humans & Machines
* [github/gh-aw](https://github.com/github/gh-aw) - GitHub Agentic Workflows
* [hakluke/hakrawler](https://github.com/hakluke/hakrawler) - Simple, fast web crawler designed for easy, quick discovery of endpoints and assets within a web application
* [tickstep/aliyunpan](https://github.com/tickstep/aliyunpan) - 阿里云盘命令行客户端，支持JavaScript插件，支持同步备份功能。
* [vmware-tanzu/kubeapps](https://github.com/vmware-tanzu/kubeapps) - A web-based UI for deploying and managing applications in Kubernetes clusters *(archived)*
* [jesseduffield/horcrux](https://github.com/jesseduffield/horcrux) - Split your file into encrypted fragments so that you don't need to remember a passcode
* [schollz/find](https://github.com/schollz/find) - High-precision indoor positioning framework for most wifi-enabled devices.
* [NdoleStudio/httpsms](https://github.com/NdoleStudio/httpsms) - Send and receive SMS messages using your Android phone programmatically via a simple HTTP API
* [entireio/cli](https://github.com/entireio/cli) - 📜 Entire CLI hooks into your Git workflow to capture AI agent sessions as you work. Sessions are indexed alongside commits, creating a searchable record of how code was written in your repo.
* [lc/gau](https://github.com/lc/gau) - Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl.
* [vllm-project/aibrix](https://github.com/vllm-project/aibrix) - Cost-efficient and pluggable Infrastructure components for GenAI inference
* [bitly/oauth2_proxy](https://github.com/bitly/oauth2_proxy) - A reverse proxy that provides authentication with Google, Github or other provider *(archived)*
* [diggerhq/digger](https://github.com/diggerhq/digger) - Digger is an open source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline ⚡️
* [uber/prototool](https://github.com/uber/prototool) - Your Swiss Army Knife for Protocol Buffers *(archived)*
* [clidey/whodb](https://github.com/clidey/whodb) - Where data access meets operational intelligence
* [arduino/arduino-cli](https://github.com/arduino/arduino-cli) - Arduino command line tool
* [francoismichel/ssh3](https://github.com/francoismichel/ssh3) - SSH3: faster and rich secure shell using HTTP/3, checkout our article here: https://arxiv.org/abs/2312.08396 and our Internet-Draft: https://datatracker.ietf.org/doc/draft-michel-ssh3/
* [perplexityai/bumblebee](https://github.com/perplexityai/bumblebee) - Read-only developer endpoint scanner for on-disk package, extension, and developer-tool metadata, built to check exposure to known software supply-chain compromises.
* [BurntSushi/toml](https://github.com/BurntSushi/toml) - TOML parser for Golang with reflection.
* [vugu/vugu](https://github.com/vugu/vugu) - Vugu: A modern UI library for Go+WebAssembly (experimental)
* [nsf/gocode](https://github.com/nsf/gocode) - An autocompletion daemon for the Go programming language
* [nicocha30/ligolo-ng](https://github.com/nicocha30/ligolo-ng) - An advanced, yet simple, tunneling/pivoting tool that uses a TUN interface.
* [KubeOperator/KubeOperator](https://github.com/KubeOperator/KubeOperator) - KubeOperator 是一个开源的轻量级 Kubernetes 发行版，专注于帮助企业规划、部署和运营生产级别的 K8s 集群。 *(archived)*
* [hashicorp/terraform-provider-azurerm](https://github.com/hashicorp/terraform-provider-azurerm) - Terraform provider for Azure Resource Manager
* [wallix/awless](https://github.com/wallix/awless) - A Mighty CLI for AWS
* [WuKongIM/WuKongIM](https://github.com/WuKongIM/WuKongIM) - More than just IM 不只是即时通讯(IM)
* [open-telemetry/opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) - Contrib repository for the OpenTelemetry Collector
* [crazy-max/diun](https://github.com/crazy-max/diun) - Receive notifications when an image is updated on a Docker registry
* [mailru/easyjson](https://github.com/mailru/easyjson) - Fast JSON serializer for golang.
* [m3db/m3](https://github.com/m3db/m3) - M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform
* [HFO4/gameboy.live](https://github.com/HFO4/gameboy.live) - 🕹️ A basic gameboy emulator with terminal "Cloud Gaming" support
* [googlecodelabs/tools](https://github.com/googlecodelabs/tools) - Codelabs management & hosting tools *(archived)*
* [superfly/litefs](https://github.com/superfly/litefs) - FUSE-based file system for replicating SQLite databases across a cluster of machines
* [src-d/go-git](https://github.com/src-d/go-git) - Project has been moved to: https://github.com/go-git/go-git *(archived)*
* [variadico/noti](https://github.com/variadico/noti) - Moved to Codeberg *(archived)*
* [fogleman/gg](https://github.com/fogleman/gg) - Go Graphics - 2D rendering in Go with a simple API.
* [esimov/pigo](https://github.com/esimov/pigo) - Fast face detection, pupil/eyes localization and facial landmark points detection library in pure Go.
* [MariaLetta/free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) - ✨ This pack of 100+ gopher pictures and elements will help you to build own design of almost anything related to Go Programming Language: presentations, posts in blogs or social media, courses, videos and many, many more.
* [egonelbre/gophers](https://github.com/egonelbre/gophers) - Free gophers
* [olivia-ai/olivia](https://github.com/olivia-ai/olivia) - 💁‍♀️Your new best friend powered by an artificial neural network *(archived)*
* [gomatcha/matcha](https://github.com/gomatcha/matcha) - Build native mobile apps in Go.
* [DisposaBoy/GoSublime](https://github.com/DisposaBoy/GoSublime) - A Golang plugin collection for SublimeText 3, providing code completion and other IDE-like features.
* [otiai10/gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library
* [ashleymcnamara/gophers](https://github.com/ashleymcnamara/gophers) - Gopher Artwork by Ashley McNamara
* [montanaflynn/stats](https://github.com/montanaflynn/stats) - A well tested and comprehensive Golang statistics library package with no dependencies.
* [hexops/vecty](https://github.com/hexops/vecty) - Vecty lets you build responsive and dynamic web frontends in Go using WebAssembly, competing with modern web frameworks like React & VueJS. *(archived)*
* [go-ego/gse](https://github.com/go-ego/gse) - Go efficient multilingual NLP and text segmentation; support English, Chinese, Japanese and others.
* [yanyiwu/gojieba](https://github.com/yanyiwu/gojieba) - "结巴"中文分词的Golang版本
* [gopher-os/gopher-os](https://github.com/gopher-os/gopher-os) - A proof of concept OS kernel written in Go
* [galeone/tfgo](https://github.com/galeone/tfgo) - Tensorflow + Go, the gopher way
* [fatih/gomodifytags](https://github.com/fatih/gomodifytags) - Go tool to modify struct field tags
* [icexin/eggos](https://github.com/icexin/eggos) - A Go unikernel running on x86 bare metal
* [stianeikeland/go-rpio](https://github.com/stianeikeland/go-rpio) - :electric_plug: Raspberry Pi GPIO library for go-lang
* [ajstarks/svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation
* [faiface/beep](https://github.com/faiface/beep) - A little package that brings sound to any Go application. Suitable for playback and audio-processing.
* [fogleman/pt](https://github.com/fogleman/pt) - A path tracer written in Go.
* [google/periph](https://github.com/google/periph) - Older version of periph, see new version at https://github.com/periph *(archived)*
* [krillinai/OpenCreator](https://github.com/krillinai/OpenCreator) - AI video translation & dubbing tool for humans and AI Agents, powered by LLMs. Full pipeline: download, transcribe, translate, TTS dub, reformat, cover generation. 100+ languages, optimized for YouTube, TikTok, Bilibili, Douyin, and more.AI视频翻译配音工具，面向人类与AI Agent，100+语言全链路，CLI分阶段调用，适配抖音、小红书、哔哩哔哩、视频号、TikTok、YouTube
