# 说明
此项目是[awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core)中文版，根据个人对项目的理解进行说明，有些是google翻译，有空会继续修改，如有错误，欢迎指正。  
最后一次同步时间：2020-04-24（每月同步一次）  
      
[国内](README_CN.md)  | [中文](README.md)  | [English](README_EN.md) 
    
> 国内：国内优秀的库，框架，工具，软件，播客，公众号等。  
> 中文：英文awesome-dotnet-core的翻译版本  
> English：英文awesome-dotnet-core  

# Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

灵感来自[awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

永远欢迎贡献! 请先查看[贡献准则](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md). 我们也接受专有和商业软件.

感谢所有的[贡献者](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), 没有你的参与awesome的创建将不能想象! 此项目的目的是建立一个以社区驱动的知名的资源分类集合。

查看我的[博客](https://medium.com/@thangchung) 或者在[Twitter](https://twitter.com/thangchung)打声招呼!

## 内容
* [一般](#一般)
* [框架, 库和工具](#框架-库和工具)
  * [API](#api)
  * [应用程序框架](#应用程序框架)
  * [应用程序模板](#应用程序模板)
  * [身份认证和授权](#身份认证和授权)
  * [区块链](#区块链)
  * [机器人](#机器人)
  * [自动部署](#自动部署)
  * [css, js帮助工具](#css-js帮助工具)
  * [缓存](#缓存)
  * [内容管理系统CMS](#cms)
  * [代码分析和指标](#代码分析和指标)  
  * [压缩](#压缩)
  * [编译器](#编译器)
  * [密码](#密码)
  * [数据库](#数据库)
  * [数据库驱动程序](#数据库驱动程序)
  * [数据库工具库](#数据库工具库)
  * [日期和时间](#日期和时间)
  * [分布式计算](#分布式计算)
  * [电子商务与计算](#电子商务与计算)
  * [异常](#异常)
  * [响应式编程](#响应式编程)
  * [图片](#图片)
  * [图形用户界面GUI](#图形用户界面gui)
  * [集成开发环境IDE](#集成开发环境ide)
  * [国际化](#国际化)
  * [控制反转IOC](#控制反转ioc)
  * [日志](#日志)
  * [机器学习和科学研究](#机器学习和科学研究)
  * [邮件](#邮件)
  * [数学](#数学)
  * [网络](#网络)
  * [大杂烩](#大杂烩)
  * [办公软件](#办公软件)
  * [对象关系映射ORM](#对象关系映射orm)
  * [分析](#分析)
  * [消息队列](#消息队列)
  * [sql生成器](#sql生成器)
  * [任务计划](#任务计划])
  * [开发工具包SDKs](#开发工具包sdks)
  * [安全](#安全)
  * [搜索](#搜索)
  * [序列化](#序列化)
  * [模板引擎](#模板引擎)
  * [测试](#测试)
  * [工具](#工具)
  * [Web框架](#Web框架)
  * [Web Socket](#web-socket)
  * [Windows服务](#windows服务)
  * [工作流](#工作流)
* [线路图](#线路图)
* [入门套件](#入门套件)
* [例子](#例子)
* [文章](#文章)
* [书籍](#书籍)
* [备忘录](#备忘录)
* [视频学习](#视频学习)
* [视频播客](#视频播客)
* [社区](#社区)
* [组织](#组织)

## 一般

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - 官方ASP.NET核心文档站点。
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - .NET Core，C#，F#和Visual Basic技术文档的主页，包括基本概念，入门说明，教程和示例。
* [.NET Core SDK](https://www.microsoft.com/net/core) -  .NET Core SDK是由Microsoft和.NET社区在[GitHub](https://github.com/dotnet/core)上维护的通用开发平台。
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/1719a3fe2a5c81b67a4909787da4a02fb0d0d419/Documentation/architecture/net-platform-standard.md) - 旧版本和新版本的.NET之间存在差异。
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - 介绍.NET Standard 2.0的内容和当前.NET标准中某些缺失部分的路线图。
* [.NET/.NET Core代码整洁](https://github.com/thangchung/clean-code-dotnet) - 适用于.NET / .NET Core的代码整洁。
* [.NET Framework源码](https://referencesource.microsoft.com/)

## 框架, 库和工具

### API

* [autorest](https://github.com/Azure/autorest) -  Swagger(OpenAPI)规范代码生成器，具有C#和Razor模板。支持C#，Java，Node.js，TypeScript，Python和Ruby。
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) - 提供一组库，这些库可将服务API版本添加到ASP.NET Web API，具有ASP.NET Web API的OData和ASP.NET Core。
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) -  ASP.NET限速中间件。
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - 使用Kestrel和Consul的API Condenser / Reverse Proxy，包括轻量级consul库。
* [Flurl](https://github.com/tmenier/Flurl) - 适用于.NET的Fluent URL构建器和可测试的HTTP。
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) - 一个旨在将Dapper和graphql-dotnet项目集成在一起的库，主要考虑的是易用性和性能。
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) -  ASP.NET Core MiddleWare创建GraphQL端点。
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - 该库是GraphQL的补充层，使您可以使用现有的属性和方法作为字段解析器，将.NET类自动包装到GraphQL模式定义中。
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - 用于ASP.NET Core的GraphiQL中间件。
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - 基于[graphql-js](https://github.com/graphql/graphql-js)的.NETQL GraphQL。
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET。
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) - GraphQL for .NET - 订阅传输WebSockets。
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - .Net Core和.NET Framework的GraphQL服务器。
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) - Facebook GraphQL查询语言的[FSharp]((https://fsprojects.github.io/FSharp.Data.GraphQL))实现。
  * [parser](https://github.com/graphql-dotnet/parser) - .NET中GraphQL的词法分析器和解析器。
  * [tanka-graphql](https://github.com/pekkah/tanka-graphql) - GraphQL执行库和服务器库，支持SignalR，Apollo，模式操纵以及Apollo和graphql-js熟悉的其他功能。
* [halcyon](https://github.com/visualeyes/halcyon) -  ASP.NET的HAL实现。
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - 用于ASP.Net Core的JSON API框架。
* [LightNode](https://github.com/neuecc/LightNode) - 基于OWIN构建的Micro RPC / REST框架
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) - 适用于.NET Standard 2.0的类型安全的分布式REST库(NetCoreStack Flying Proxy)
* [NSwag](https://github.com/RSuter/NSwag) - 用于.NET，Web API和TypeScript的Swagger / OpenAPI工具链。
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) - 开放数据协议(OData)支持创建基于HTTP的数据服务，允许使用统一资源标识符识别资源( URIs)并在抽象数据模型中定义，由Web客户端使用简单的HTTP消息进行发布和编辑。
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) - 可以通过 OpenAPI Generator，在给定 OpenAPI 规范(v2, v3)的情况下自动生成 API 客户端库、server stubs、文档以及配置。
* [refit](https://github.com/paulcbetts/refit) -  适用于.NET Core，Xamarin和.NET的自动类型安全REST库。
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) - 适用于所有C#跨平台的REST客户端。
* [RestEase](https://github.com/canton7/RestEase) - 易于使用的类型安全REST API客户端库，简单且可自定义。
* [RestLess](https://github.com/letsar/RestLess) -  .Net Standard的自动类型安全无反射REST API客户端库。
* [Restier](https://github.com/OData/RESTier) -  RESTier是一个RESTful API开发框架，用于在.NET平台上构建基于OData V4的标准化RESTful服务。
* [Restsharp](https://github.com/restsharp/RestSharp) - 用于.NET的简单REST和HTTP API客户端
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - Swagger工具，生成API文档，包括用于测试的UI。
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) - 向Swagger添加FluentValidation规则。
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) - 一堆有用的Swashbuckle.AspNetCore筛选器。
 * [WebAnchor](https://github.com/mattiasnordqvist/Web-Anchor) - Web Anchor 提供了类型安全，可测试和灵活的，运行时生成的Web资源访问。简单来说提供了Web APi灵活的访问方式。
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - ASP.NET Core的附加组件和扩展库。

### 应用程序框架
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) -  ABP是一个通用的WEB应用程序框架和项目模板。
* [Abp vNext](https://github.com/abpframework/abp) - 该项目是ABP Web应用程序框架的下一代。
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) -  async / await的帮助程序库。
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - 高效可靠的UDP单播，UDP组播和IPC消息传输。
* [akka.net](https://github.com/akkadotnet/akka.net) - Akka是一个基于scala语言的Actor模型库，旨在构建一套高并发、分布式、自动容错、消息驱动应用的工具集。
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) -  Aggregates.NET是一个框架，可以帮助开发人员将优秀的NServiceBus和EventStore库集成在一起。
* [ASP.NET MVC](https://github.com/dotnet/aspnetcore/tree/master/src/Mvc) - 官方WEB应用程序框架，MVC。
* [ASP.NET Core](https://github.com/aspnet/AspNetCore) - ASP.NET Core是一个跨平台的.NET框架。
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet) - 允许用最少的工作量构建实时Web应用程序，分布式追踪的服务器端库。
* [CAP](https://github.com/dotnetcore/CAP) - CAP是处理分布式事务的解决方案，还具有EventBus功能，它轻巧，易于使用且高效。
* [Carter](https://github.com/CarterCommunity/Carter) -  Carter是一个路由框架，使代码更加简单明确。
* [Chromely](https://github.com/mattkol/Chromely) -  Electron.NET的轻量级替代品，构建HTML5桌面应用程序框架。
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) - 用于.NET的ETL框架(用于CSV，Flat，Xml，JSON，键值对格式文件的分析器/写入器)。
* [CQRSlite](https://github.com/gautema/CQRSlite) - 用于帮助在C#中编写CQRS和Eventsourcing应用程序的轻量级框架。
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) -  EF的UnitOfWork和Repositories的基类。
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) - DNTFrameworkCore 是一个轻量级且可扩展的基础结构，用于基于ASP.NET Core构建高质量的Web应用程序
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) - 用于动态加载.NET Core程序集，将其作为主应用程序的扩展来执行与Assembly.LoadFrom不同。
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) -  DotnetSpider，一个类似于WebMagic和Scrapy的.NET标准爬虫库。它是轻量级，高效且快速的高级Web爬网和抓取框架。
* [DotNetty](https://github.com/Azure/DotNetty) -  netty端口，事件驱动的异步网络应用程序框架。
* [dotvvm](https://github.com/riganti/dotvvm) -  Web应用程序的开源MVVM框架。
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) - 使用ASP.NET NET Core构建跨平台桌面应用程序。
* [EmbedIO](https://github.com/unosquare/embedio) - 一个小型的，跨平台，基于模块的Web服务器。
* [Ether.Network](https://github.com/aloisdg/Ether.Network) - Ether.Network是一个开源网络库，允许开发人员通过sockets创建简单，快速和可扩展的套接字服务器或客户端的基本库。
* [EventFlow](https://github.com/eventflow/EventFlow) - EventFlow是一个易于使用的基本CQRS + ES框架。
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - 用C#编写的轻量级快速库，用于读取Microsoft Excel文件。
* [ExtCore](https://github.com/ExtCore) - 用于创建模块化和可扩展的Web应用程序框​​架。
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant) -  Finbuckle.MultiTenant是ASP.NET Core的多租户库。它提供用于租户解析，每个租户应用程序配置和每个租户数据隔离的功能。
* [fission](https://github.com/fission/fission) -  Fission 是一个构建在 Kubernetes 之上的 FaaS框架。ission 利用Kubernetes 集群管理、调度、网络管理等，将容器编排功能留给 Kubernetes，而 Fission 就专注于 FaaS 特性。
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - 远程过程调用(RPC)为构建分布式应用程序和服务提供了有用的抽象，grpc库。
* [Halibut](https://github.com/OctopusDeploy/Halibut) - 使用基于SSL的JSON-RPC的.NET安全通信框架。
* [MagicOnion](https://github.com/neuecc/MagicOnion) - MagicOnion是一个实时网络引擎，如SignalR，Socket.io和RPC-Web API框架。
* [MassTransit](https://github.com/MassTransit/MassTransit) -  .NET分布式应用程序框架。
* [microdot](https://github.com/gigya/microdot) - 一个开源的.NET微服务框架。
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) -  LINQ to Objects的扩展。
* [Nancy](https://github.com/NancyFx/Nancy) - 用于在.NET和Mono上构建基于HTTP的服务的轻量级框架。
* [opencvsharp](https://github.com/shimat/opencvsharp) -  OpenCV的跨平台库。
* [orleans](https://github.com/dotnet/orleans) - Orleans是一个跨平台的，用于构建分布式应用程序框架
* [Prism](https://github.com/PrismLibrary/Prism) - Prism是一个框架，用于在WPF，Windows 10 UWP和Xamarin Forms中构建松耦合，可维护和可测试的XAML应用程序。
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) -  Golang和C#的快速分布式Actor。
* [resin](https://github.com/kreeben/resin) - 面向文档的搜索引擎，具有列索引，多重集合查询，基于JSON的查询语言和HTTP API。
* [RService.io](https://github.com/Stoom/RService.IO) -  用于ASP.NET Core的轻量级REST服务框架
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - ServiceStack是一个简单，快速，通用和高效的全功能Web和 Web服务框架。
* [Steeltoe OSS](https://github.com/SteelToeOSS) - 用于常见微服务模式的.NET工具包。
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) - 一个在ASP.NET Core MVC项目中启用强类型路由的库。
* [surging](https://github.com/dotnetcore/surging) - Surging是一种微服务引擎，提供了轻量级，高性能的模块化RPC请求管道。服务引擎支持http，TCP，WS，Mqtt，UDP和DNS协议。它使用ZooKeeper和Consul作为注册表，使用哈希算法，随机，轮询，压力最小优先级作为负载平衡算法，内置服务管理以确保可靠的RPC通信。
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - 轻巧易用的CQRS + DDD库。
* [X.PagedList](https://github.com/dncuug/X.PagedList) - 用于轻松分页ASP.NET / ASP.NET Core中任何IEnumerable / IQueryable的库。

### 应用程序模板
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates) - .NET项目模板，包裹API，GraphQL，Orleans。
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) -  ASP.NET Core/ React SPA应用程序模板。
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) - Asp.Net Core和Angular 8 SPA Fullstack应用程序模板。
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) - 带有Angular的ASP.NET MVC 5，ASP.NET Core和ASP.NET Core的现成模板。
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - 为ASP.NET Core中的MVC控制器和视图启用功能文件夹。
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio) - 用于Webpack，Visual Studio，ASP.NET Core和Angular的模板。应用程序的客户端和服务器端都在一个ASP.NET Core项目中实现，这使得部署更容易。
* [CleanArchitecture](https://github.com/JasonGT/CleanArchitecture) - 遵循Clean Architecture的原理使用Angular 8和ASP.NET Core 3创建单页应用程序（SPA）的解决方案模板
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) - 基于[DNTFrameworkCore]的Boilerplate项目模板。
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju) - 代码整洁框架，[clean-architecture-manga](https://github.com/ivanpaulovich/clean-architecture-manga)。
* [EISK](https://github.com/EISK/eisk.webapi) - 为开发人员资源提供简单的用例，以使用[体系结构最佳实践]在.NET Core之上构建可伸缩的应用程序 (DDD, onion architecture etc)
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) -  Microsoft ASP.NET核心JavaScript服务。
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - 一个基于jQuery的HTML5小部件库，用于构建现代Web应用程序。
* [QuickApp](https://github.com/emonney/QuickApp) - 具有完整登录，用户和角色管理的ASP.NET Core / Angular4启动项目模板。
* [Serenity](https://github.com/volkanceylan/Serenity) -  Serenity是一个ASP.NET MVC / TypeScript应用程序框架，旨在通过基于服务的体系结构，简化和缩短以数据为中心的应用程序开发。
* [Toucan](https://github.com/mrellipse/toucan) - 用于构建单页应用程序的Boilerplate。服务器是围绕SOLID原则设计的多项目.Net Core解决方案。客户端是TypeScript 2，Vuejs 2，Vuex 2。

### 身份认证和授权
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - 用于OWIN / Katana和ASP.NET Core的OpenID Connect / OAuth2服务器框架。
* [Auth0](https://github.com/auth0/auth0.net) - Auth0身份验证和管理API的.NET客户端。
* [Casbin.NET](https://github.com/casbin-net/Casbin.NET) - 支持ACL，RBAC，ABAC的授权库。
* [Identity](https://github.com/aspnet/AspNetCore) -  ASP.NET Core Identity是用于构建ASP.NET Core Web应用程序的身份验证库。
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - IdentityServer4，适用于ASP.NET Core的OpenID Connect和OAuth 2.0框架 。
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EF的IdentityServer4库。
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) - MongoDB 的IdentityServer4库。
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - EF Core 的IdentityServer4库。
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) - IdentityServer4模板.
* [openiddict](https://github.com/openiddict/openiddict-core) - 易于使用的OpenID Connect服务器。
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) - OAuth 2.0和OpenID Connect调试工具
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Stormpath使开发人员能够将用户身份验证，用户管理和安全工作流程快速构建到其应用程序中。
* [stuntman](https://github.com/ritterim/stuntman) - 用于在开发过程中利用ASP.NET Identity模仿用户的库

### 区块链
* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) - BTCPay Server是一个免费的开源加密货币支付处理器，它使您可以直接以比特币和山寨币接收支付，而无需任何费用，交易成本或中间商。
* [Meadow](https://github.com/MeadowSuite/Meadow) - 一个集成的以太坊实施和工具套件，专注于Solidity测试和开发。
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - 用于.NET框架的综合比特币库。
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) - 用于构建支持区块链的应用程序的.NET标准库
* [NBXplorer](https://github.com/dgarage/NBXplorer) - 比特币和NBitcoin资源管理器客户端。
* [NEO](https://github.com/neo-project/neo) - 为智能经济打造的开放网络，Neo利用区块链技术。
* [Nethereum](https://github.com/Nethereum) - 将以太坊的热爱带到.NET。
* [Nethermind](https://github.com/NethermindEth/nethermind) -  .NET Core以太坊客户端
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - 简单且经济实惠的端到端解决方案，用于在.Net框架上开发，测试和部署本机C#区块链应用程序。
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) - Trezor加密货币硬件钱包的跨平台C＃库。
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) - 注重隐私的比特币钱包。内置Tor，CoinJoin和硬币控制功能。

### 机器人
* [BotSharp](https://github.com/SciSharp/BotSharp) - BotSharp是AI Bot平台构建者的开源机器学习框架。
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - 用C#编写的开源，通用的Discord聊天机器人。
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) -  Telegram Bot API客户端。
* [Funogram](https://github.com/Dolfik1/Funogram) -  F#Telegram Bot Api库。

### 自动部署
* [cake-build](https://github.com/cake-build/cake) - 跨平台构建自动化系统。
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - 设置您的C#控制台输出样式！
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - 用于.NET Core和.NET Core Tools的基本Docker镜像。
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) - .NET Cli工具，用于将.NET Core应用程序打包到Docker映像中：“ dotnet dockerize”
* [FlubuCore](https://github.com/dotnetcore/FlubuCore) - 跨平台构建和自动化部署系统，用C#代码构建项目，执行，部署脚本。
* [GitInfo](https://github.com/kzu/GitInfo) - 来自MSBuild，C#和VB的Git和SemVer信息，一种MSBuild编译工具。
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) - 使用version.json文件生成的唯一版本标记程序集和程序包等，并包括用于非官方构建的git commit ID。
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - .NET Core Runtime的PoC Go包装器。
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) - 将现有Windows应用程序工作，移植到Docker的PowerShell模块。
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) - .NET Core全局工具，可将appveyor.yml部署AppVeyor到本地。
* [msbuild](https://github.com/Microsoft/msbuild) -  Microsoft Build Engine是一个用于构建应用程序的平台。
* [Nuke](https://github.com/nuke-build/nuke) - 跨平台构建自动化系统。
* [Opserver](https://github.com/opserver/Opserver) -  Stack Exchange的监控系统。
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) -  Visual Studio Team Services构建和发布代理。

### css, js帮助工具
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) -  Visual Studio扩展，让您可以配置JS，CSS和HTML文件的捆绑和缩小。
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - 用于在JavaScript环境中呈现标记的ASP.NET MVC ViewEngine。适用于React和Angular服务器端呈现。
* [Smidge](https://github.com/Shazwazza/Smidge/) - 用于ASP.NET Core的轻量级运行时CSS / JavaScript文件缩小，组合，压缩和管理库。
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) - 包含一组标记最小化器的.NET库。该项目的目标是通过减少HTML，XHTML和XML代码的大小来提高Web应用程序的性能。

### 缓存
* [CacheManager](https://github.com/MichaCo/CacheManager) - 用C#编写的.NET的开源缓存抽象层。它支持各种缓存提供程序并实现许多高级功能。
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) - 开源缓存库，包含基本用法和缓存的一些高级用法，可以帮助我们更轻松地处理缓存。
* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs) - Microsoft的快速key，value存储库。
* [Foundatio](https://github.com/exceptionless/Foundatio) - 用于构建分布式应用程序的可插入基础库。
* [Microsoft Caching](https://github.com/aspnet/Caching) - 用于内存缓存和分布式缓存的库。
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - 用于.NET语言的高性能通用redis客户端(C#等)。

### 内容管理系统CMS
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) - Awesome-CMS-Core是一个使用ASP.Net Core和ReactJS构建的开源CMS，考虑到模块分离问题并提供最新的技术趋势，如.Net Core，React，Webpack，SASS，后台作业，Message Queue。
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) - Blogifier是用ASP.NET Core编写的简单，美观，轻巧的开源博客。
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry) - Cofoundry是一个可扩展且灵活的.NET Core CMS和应用程序框架，专注于代码优先开发。
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) - 一个简单的ASP.NET core wiki。
* [dasblog-core](https://github.com/poppastring/dasblog-core) - DasBlog博客项目。
* [Lynicon](https://github.com/jamesej/lyniconanc) - Lynicon CMS系统。
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) - ASP.NET Core博客引擎。
* [Mixcore CMS](https://github.com/mixcore/mix.core) - 由DotNet Core支持的开源CMS。 Mixcore CMS是一个可扩展的开放平台，用于Web内容管理和数字体验。 Mixcore CMS在网络上提供了强大的功能和无限的灵活性。
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS) - NetCoreCMS是使用ASP.Net Core 2.0 MVC开发的模块化主题支持的内容管理系统。
* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore) - 在模块化和可扩展的应用程序框架之上使用ASP.NET Core构建的开源内容管理系统。
* [Piranha CMS](https://github.com/piranhacms/piranha.core) - 用于ASP.NET核心和实体框架核心的轻量级且不显眼的开源CMS。
* [Platformus](https://github.com/Platformus) - 基于ASP.NET Core 1.0和ExtCore框架的免费，开源和跨平台的CMS。
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) - 用于ASP.NET Core的简单而灵活的内容和博客引擎，可以使用或不使用数据库。
* [Squidex](https://github.com/Squidex/squidex) - Squidex是一个开源的CMS，基于MongoDB，CQRS和事件。
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core) - 基于SIOH框架的ASP.NET Core / Dotnet核心系统（例如CMS，电子商务，论坛，问题解答，CRM ...）
* [Weapsy](https://github.com/Weapsy/Weapsy) - 基于DDD和CQRS的开源ASP.NET核心CMS。它支持开箱即用的MSSQL，MySQL，SQLite和PostgreSQL。
* [Wyam](https://github.com/Wyamio/Wyam) - 模块化静态内容和静态站点生成器。
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) - 视觉设计，通过拖放构建网站。

### 代码分析和指标
* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) - 针对各种编程语言的静态分析工具，链接和代码质量检查器的精选列表。
* Code Analysis
  * [CodeFormatter](https://github.com/dotnet/codeformatter) - CodeFormatter是使用Roslyn来自动重写我们的代码格式。
  * [DevSkim](https://github.com/Microsoft/DevSkim) - DevSkim是IDE扩展和语言分析器的框架，可在开发人员编写代码时在开发环境中提供内联安全性分析。
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - Visual Studio扩展工具，支持分析和重构代码。
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) - Roslyn分析器分析您的代码的样式，质量和可维护性，设计和其他问题。
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - StyleCop规则实现的.NET编译器平台。
* Metrics
  * [AppMetrics](https://github.com/alhardy/AppMetrics) - 用于记录和报告应用程序中的指标。
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) - 一个可扩展的框架，用于审核.NET和.NET Core中的执行操作。
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - 用于基准测试的强大.NET库。
  * [coverlet](https://github.com/tonerdo/coverlet) - Coverlet是.NET的跨平台代码覆盖框架。
  * [MiniCover](https://github.com/lucaslorentz/minicover) - 跨平台代码覆盖工具
  * [NBench](https://github.com/petabridge/NBench) - .NET应用程序的性能基准测试框架
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) - 用于在.NET中收集应用程序指标并将其导出到Prometheus的库。
  * [OpenCover](https://github.com/OpenCover/opencover) - 代码覆盖工具（仅适用于WINDOWS OS）
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor) - .NET应用程序性能监视器。
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net) - .NET指标,监视系统,检测应用程序的prometheus库。
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) - Prometheus客户端。

### 压缩
* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) - 适用于所有.NET平台的超快速压缩算法。
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - 完全管理的C#库，用于处理许多压缩类型和格式。

### 编译器
* [Fable](https://github.com/fable-compiler/Fable) -  F#到JavaScript编译器。
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) -  F#和C#的解析器组合库。
* [IL2C](https://github.com/kekyo/IL2C) - IL2C-ECMA-335 CIL / MSIL到C语言的翻译器。
* [Mond](https://github.com/Rohansi/Mond) - 用C#编写的动态类型脚本语言，带有REPL，调试器和简单的嵌入API。
* [peachpie](https://github.com/peachpiecompiler/peachpie) -  .NET的开源PHP编译器。
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - 用于C#的轻量级，快速且灵活的解析库，由Stack Overflow开发。
* [roslyn](https://github.com/dotnet/roslyn) -  Roslyn .NET编译器提供具有丰富代码分析API的C＃和Visual Basic语言。 
* [Sprache](https://github.com/sprache/Sprache) -  小型，友好的C＃解析器框架。

### 密码
* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) - BCrypt密码库。
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - 用于安全存储密码的BCrypt.NET库。
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) -  Bouncy Castle Crypto包是加密算法和协议的库。
* [multiformats](https://github.com/multiformats/cs-multihash) - 用于编码/解码Multihashes的库，它是一个“容器”，用于描述计算摘要的散列算法。
* [nsec](https://github.com/ektrah/nsec) -  NSec是基于libsodium的.NET Core新加密库。
* [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) - 专业的加密库。

### 数据库
* [DBreeze](https://github.com/hhblaze/DBreeze) -  C#.NET MONO NOSQL(嵌入式键值存储)ACID多范例数据库管理系统。
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) - 简单的JSON平面文件数据存储，支持打字和动态数据。
* [LiteDB](https://github.com/mbdavid/LiteDB) -  LiteDB是一个小型，快速，轻量的NoSQL嵌入式数据库。
* [NoDb](https://github.com/joeaudette/NoDb) -  文档数据库，个人博客和网站以及小型小册子网站是不使用数据库的不错的选择。
* [marten](https://github.com/JasperFx/marten) -  Postgresql作为.NET应用程序的文档数据库和事件存储的库。
* [StringDB](https://github.com/SirJosh3917/StringDB) - StringDB是一个模块化的键/值对档案数据库，旨在消耗少量的ram并生成少量的数据库。
* [yessql](https://github.com/sebastienros/yessql) - 适用于任何RDBMS的.NET文档数据库。

### 数据库驱动程序
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - 用于Apache Cassandra的DataStax C#驱动程序。
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) -  Confluent的Apache Kafka .NET客户端。
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) - 一个轻量级，面向文档(NoSQL)，可同步的.NET数据库引擎。
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) -  MongoDB的.NET驱动程序。
* [MongoDB.Entities](https://github.com/dj-nitehawk/MongoDB.Entities) - MongoDB的数据访问库，具有精美的API，LINQ支持和内置实体关系管理
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) - ADO.NET驱动和MySQL的链接库。
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) - 异步MySQL连接库。
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - Neo4j .NET驱动程序。
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) - Neo4j客户端。
* [npgsql](https://github.com/npgsql/npgsql) -  它允许为.NET框架开发的任何程序访问PostgreSQL数据库服务器的库。
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - 支持Linq的.NET文档数据库。
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - RethinkDB 数据库的驱动程序。
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) -  Tarantool NoSql数据库的.NET客户端。

### 数据库工具库
* [DbUp](https://github.com/DbUp/DbUp) -  可帮助您将更改部署到SQL Server数据库，跟踪已经运行的SQL脚本，并运行使数据库更新所需的更改脚本。
* [Evolve](https://github.com/lecaillon/Evolve) - 使用纯SQL脚本的简单数据库迁移工具。受到Flyway的启发。
* [EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools) - EF工具库 - reverse engineering, migrations and model。
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) -  .NET的迁移框架，就像Ruby on Rails Migrations一样。
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency) - 获取有关记录表更改的SQL Server通知。
* [roundhouse](https://github.com/chucknorris/roundhouse) - RoundhousE是用于.NET的数据库迁移实用程序，它使用sql文件和基于源代码控制的版本控制。
* [SapphireDb](https://github.com/SapphireDb/SapphireDb) - SapphireDb的服务器实现，这是一个通过实时数据同步轻松开发应用程序的框架，并且是asp.net核心和ef核心的Firebase实时数据库/ firestore的自托管替代方案。
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) -  SharpRepository是一个用C#编写的通用存储库，它包括对各种关系，文档和对象数据库的支持，包括Entity Framework，RavenDB，MongoDb和Db4o。 SharpRepository还包括Xml和InMemory存储库实现。
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) - 使用.NET Core跨服务边界进行更改跟踪。
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) - MongoDB的即时迁移库。
* [EntityFrameworkCore.DataEncryption](https://github.com/Eastrall/EntityFrameworkCore.DataEncryption) - Microsoft.EntityFrameworkCore的插件，可以使用内置或自定义加密提供程序添加对加密字段的支持。

### 日期和时间
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) -  DateTimeRange，工作日和各种DateTime，DateTimeOffset，TimeSpan扩展方法。
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) - 允许您编写更清晰的DateTime表达式和操作。部分灵感来自Ruby DateTime Extensions。
* [nodatime](https://github.com/nodatime/nodatime) - 日期和时间API库。

### 分布式计算
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) - HealthChecks企业级核心诊断程序。
  - [BeatPulse](https://github.com/Xabaril/BeatPulse) - ASP.NET Core应用程序的活动状况，健康检查库。
* [Foundatio](https://github.com/exceptionless/Foundatio) - 可插拔的，用于构建松耦合的分布式应用程序库。
* [jasper](https://github.com/JasperFx/jasper) - .NET的下一代应用程序开发框架
* [Rafty](https://github.com/ThreeMammals/Rafty) - RAFT 的实现库。
* [Obvs](https://github.com/christopherread/Obvs) - 一个可观察微服务总线的库，基于Rx的接口。
* [Ocelot](https://github.com/ThreeMammals/Ocelot) - Ocelot创建的API网关。
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) -API和分布式跟踪工具。
* [Polly](https://github.com/App-vNext/Polly) -  Polly是一个.NET弹性和瞬态故障处理库，允许开发人员以流畅和线程安全的方式表达诸如重试，断路器，超时，隔离头和回退之类的策略。
* [ProxyKit](https://github.com/damianh/ProxyKit) - HTTP反向代理的工具包。

### 电子商务与支付
* [nopCommerce](https://github.com/nopSolutions/nopCommerce) - 免费的开源电子商务购物车(ASP.NET MVC / ASP.NET核心MVC)，拥有庞大的社区和充满新功能的市场，主题和插件。
* [GrandNode](https://github.com/grandnode/grandnode) - 基于ASP.NET Core 2.1和MongoDB的多平台免费开源电子商务购物车。
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) - 用于PayPal的RESTful API的.NET SDK。
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - 基于.NET Core构建的超级简单电子商务系统。
* [Stripe](https://github.com/ServiceStack/Stripe) - 用于stripe.com REST API的类型.NET客户端。


### 异常
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) - 高性能的堆栈跟踪库。
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 异常客户端库。
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) -  将异常处理为ASP.NET中间件，而不是在每个控制器操作中显式处理它们。
* [Sentry](https://github.com/getsentry/sentry-dotnet) - .NET SDK for Sentry，一种开源错误跟踪，可帮助开发人员实时监控和修复崩溃。

### 响应式编程
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) -  C#的功能扩展。
* [DynamicData](https://github.com/RolandPheasant/DynamicData) - 基于Rx.NET的Reactive 集合。
* [echo-process](https://github.com/louthy/echo-process) -  C#的Actor库，其中包含支持Redis持久性的其他模块，以及JS集成。
* [FsCheck](https://github.com/fscheck/FsCheck) -  FsCheck是用于自动测试.NET程序的工具。
* [Giraffe](https://github.com/dustinmoris/Giraffe) - 适用于F#开发人员的本机功能ASP.NET核心Web框架。
* [language-ext](https://github.com/louthy/language-ext) -  C#功能语言扩展。
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - C＃中的函数式编程的代码示例。
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions) - 使用Reactive Extensions(RX)轻松地在网络上的任何位置发送消息。传输协议是ZeroMQ。
* [Optional](https://github.com/nlkl/Optional) - Optional类型库.
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - Reactive库。
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - 一个MVVM框架，它与Reactive Extensions for .NET集成，以创建在任何移动或桌面平台上运行的优雅，可测试的用户界面。
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) -  Rx.NET库。
* [Qactive](https://github.com/RxDave/Qactive) - Reactive 可查询库。
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/) - Reactive 多语言库。

### 图片
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) -  GLFW的.NET绑定。
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - 一个流畅的System.Drawing包装器，用于处理图像文件。
* [ImageSharp](https://github.com/SixLabors/ImageSharp) - 图像文件处理库。
* [LibVLCSharp](https://github.com/videolan/libvlcsharp) - LibVLCSharp是基于VideoLAN的LibVLC库的.NET平台的跨平台音频和视频API。
* [Magick.NET](https://github.com/dlemstra/Magick.NET) -  功能强大的图像处理库，支持超过100种主要文件格式（不包括子格式）。
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) - 适用于.NET的MagicScaler高性能，高质量图像处理管道
* [QRCoder](https://github.com/codebude/QRCoder) - 二维码实现库
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) -  bgfx图形库的C#绑定。
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - 用于支持.NET Core的.NET应用程序的图像处理库。
* [veldrid](https://github.com/mellinoe/veldrid) - 一个用于.NET的低级硬件加速3D图形库。
* [ZXing.Net](https://github.com/micjahn/ZXing.Net/) 二维码、条形码的生成和读取

### 图形用户界面GUI
* [AdonisUI](https://github.com/benruehl/adonis-ui) - 用于WPF应用程序的轻量级UI工具包，提供经典但增强的Windows视觉效果。
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - 跨平台UI框架。
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - 基于Avalonia的文本编辑器组件。
* [HandyControls](https://github.com/ghost1372/HandyControls) - 包含一些简单且常用的WPF控件。
* [ShellProgressBar](https://github.com/Mpdreamz/shellprogressbar) - 可视化（并行）控制台应用程序库。
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - 使用Qml.Net在.NET中构建跨平台的桌面应用程序。
* [WinApi](https://github.com/prasannavl/WinApi) - 一个简单，直接，超薄的CLR库，用于高性能Win32 Native Interop，具有自动化，窗口，DirectX，OpenGL和Skia助手。

### 集成开发环境IDE
* [Mono](https://github.com/mono/monodevelop) -  MonoDevelop使开发人员能够在Linux，Windows和Mac OS X上快速编写桌面和Web应用程序。
* [rider](https://www.jetbrains.com/rider/) - 基于IntelliJ平台和ReSharper的跨平台C#IDE。
* [Omnisharp](http://www.omnisharp.net/) - 开源项目系列，每个项目都有一个目标：在您选择的编辑器中实现出色的.NET体验。
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) -  SharpDevelop是一个免费的集成开发环境(IDE)，适用于Microsoft.NET平台上的C#，VB.NET，Boo，IronPython，IronRuby和F#项目。它(几乎)完全用C#编写，并带有您期望在IDE中使用的功能以及更多功能。
* [Visual Studio Code](https://github.com/Microsoft/vscode) - 它结合了代码编辑器的简单性和开发人员的核心编辑 - 构建 - 调试周期所需的工具。VS Code提供全面的编辑和调试支持，可扩展性模型以及与现有工具的轻量级集成。
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - 功能完备且可扩展的免费 IDE，可用于创建新式 Android、iOS、Windows 应用以及 Web 应用和云服务。

### 国际化
* [Localization](https://github.com/aspnet/Localization) -  ASP.NET Core应用程序的本地化抽象和实现库。
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) - 具带有实体框架和内存缓存中的.NET Core的数据库资源本地化库。
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) -  数据库驱动资源本地化库。

### 控制反转IOC
* [AutoDI](https://github.com/Keboo/AutoDI) - 使用IL编译的超快依赖注入库。
* [Autofac](https://github.com/autofac/Autofac) - IoC容器。
* [Castle.Windsor](https://github.com/castleproject/Windsor) -  IoC容器。
* [DryIoc](https://github.com/dadhi/DryIoc) - 快速，小巧，功能齐全的IoC。
* [Grace](https://github.com/ipjohnson/Grace) -  Grace是一款功能丰富的依赖注入容器，其设计考虑了易用性和性能。
* [Inyector](https://github.com/davidrevoledo/Inyector) -  AspNetCore的依赖注入自动化。
* [Lamar](https://github.com/JasperFx/lamar) - 快速的IOC工具库。
* [LightInject](https://github.com/seesharper/LightInject) - 超轻量级IoC容器。
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - 简单，灵活，快速的依赖注入库。
* [Stashbox](https://github.com/z4kn4fein/stashbox) - 基于.NET的解决方案的轻量级，可移植依赖注入框架。
* [Unity](https://github.com/unitycontainer/unity) - 轻量级，可扩展的依赖项注入容器。

### 日志
* [common-logging](https://github.com/net-commons/common-logging) -  抽象的日志记录库。
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - 具有UDP和Redis传输的.NET Core应用程序的Logstash日志记录扩展库。
* [ElmahCore](https://github.com/ElmahCore/ElmahCore) - 错误日志库。
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - 异常客户端。
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - 日志记录API库。
* [Karambolo.Extensions.Logging.File](https://github.com/adams85/filelogger) - 轻量级但功能丰富的文件记录库。
* [log4net](https://github.com/apache/logging-log4net) -  log4net日志记录。
* [NLog](https://github.com/NLog/NLog) - Nlog日志记录。
 * [NLog for ASP.NET and ASP.NET Core](https://github.com/NLog/NLog.Web) - 用于ASP.NET和ASP.NET Core 1-3的NLog集成
  * [NLog.Extensions.Logging](https://github.com/NLog/NLog.Extensions.Logging) - 用于.NET标准库和.NET Core应用程序的Microsoft.Extensions.Logging的NLog提供程序
  * [NLog.Windows.Forms](https://github.com/NLog/NLog.Windows.Forms) - 特定于Windows.Forms的日志目标
  * [NLog.MailKit](https://github.com/NLog/NLog.MailKit) - 使用using MailKit库的替代邮件目标
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - 用于在ASP.NET Core日志中构建的日志附加程序，以将所有日志发送到Application Insights。
* [serilog](https://github.com/serilog/serilog) - 具有完全结构化事件的简单.NET日志记录。
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) - Serilog集成库。
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) - Serilog异常库。
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) - Serilog设置库。
* [SEQ](https://getseq.net) - Seq是收集，搜索，分析和警报结构化日志数据服务器。

### 机器学习和科学研究
* [Accord](https://github.com/accord-net/framework) -  Accord.NET项目为.NET提供了机器学习，统计，人工智能，计算机视觉和图像处理方法。
* [Catalyst](https://github.com/curiosity-ai/catalyst) 受spaCy启发的跨平台自然语言处理（NLP）库，具有预训练的模型，对单词和文档嵌入进行训练的现成支持以及灵活的实体识别模型
* [ML.NET](https://github.com/dotnet/machinelearning) - ML.NET是.NET的开源和跨平台机器学习框架。
* [Spreads](https://github.com/Spreads/Spreads/) - 用于数据流实时探索和分析的库。
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - 适用于.NET语言的TensorFlow API。
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - 借助量子力学的思想，从单个例子​​生成itmap和tilemap。
* [SiaNet](https://github.com/SciSharp/SiaNet) - 具有CUDA / OpenCL支持的易于使用的C＃深度学习。

### 邮件
* [FluentEmail](https://github.com/lukencode/FluentEmail) -  电子邮件发送库。
* [MailBody](https://github.com/doxakis/MailBody) - 使用流畅的界面(.NET)创建电子邮件。
* [MailKit](https://github.com/jstedfast/MailKit) - 用于IMAP，POP3和SMTP的跨平台.NET库。
* [MailMergeLib](https://github.com/axuno/MailMergeLib) -  SMTP邮件客户端库，为文本，内嵌图像和附件提供邮件合并功能，以及发送邮件的良好吞吐量和容错能力。
* [MimeKit](https://github.com/jstedfast/MimeKit) - 跨平台.NET MIME创建和解析器库，支持S/MIME, PGP, DKIM, TNEF and Unix mbox。
* [netDumbster](https://github.com/cmendible/netDumbster) - 用于测试的.Net假SMTP服务器。克隆流行的Dumbster。
* [Papercut](https://github.com/ChangemakerStudios/Papercut) - 简单桌面SMTP服务器。
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - css和样式结合的邮件库。
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.
* [SmtpServer](https://github.com/cosullivan/SmtpServer) - 用于创建自己的SMTP服务器的库。
* [StrongGrid](https://github.com/Jericho/StrongGrid) -  SendGrid的v3 API客户端。不仅允许您发送电子邮件，还允许您批量导入联系人，管理列表和段，为列表创建自定义字段等。还包括SendGrid Webhooks的解析器。

### 数学
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - 用于.NET Core和.NET Framework的可扩展单元转换库。
* [AutoDiff](https://github.com/alexshtf/autodiff) - 一个库，提供快速，准确和自动的数学函数微分(计算导数/梯度)。

### Media
* [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor-dotnet) - 使用简单易用的API从媒体（图像，视频，音频）中提取元数据。

### 大杂烩
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport) - 基于P/Invoke的库。
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - 尖括号解析器库。它解析HTML5，MathML，SVG和CSS，以构建基于官方W3C规范的DOM。可与python的beautifulsoup4相媲美。
* [AgileMapper](https://github.com/agileobjects/AgileMapper) -  AgileMapper是一个零配置，高度可配置的对象 - 对象映射库，具有可查看的执行计划。
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore) - ASP.NET Core扩展库。
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) -  .NET中基于约定的对象关系映射库。
* [Baget](https://github.com/loic-sharma/BaGet) - 轻量级NuGet服务器。
* [Bleak](https://github.com/Akaion/Bleak) -  Windows本机DLL注入库。
* [Bullseye](https://github.com/adamralph/bullseye/) - 用于描述和运行目标及其依赖项的.NET包。
* [Castle.Core](https://github.com/castleproject/Core) -  Castle Core提供常见的Castle Project抽象，包括日志记录服务。
* [Chessie](https://github.com/fsprojects/Chessie) - Railway-oriented编程库。
* [CliWrap](https://github.com/Tyrrrz/CliWrap) - 命令行界面的包装库。
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) - 在类中为您的命令行应用程序接口建模。
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - 在C#中实现CommonMark规范，用于将Markdown文档转换为HTML。
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - 用于为.NET控制台应用程序创建表的Fluent库。
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp) - 一个可以快速格式化和转换地理坐标以及提供基于位置的太阳和月亮信息(日落，日出，月亮照明等)的库。 )。
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) -  jQuery DataTables的帮助程序。
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - 用于wkhtmltopdf库的C#.NET包装库，它使用Webkit引擎将HTML页面转换为PDF。
* [dotnet-env](https://github.com/tonerdo/dotnet-env) - 用于从.env文件加载环境变量的.NET库。
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob) - 快速通配库。优于正则表达式。
* [Dotnet outdated](https://github.com/jerriep/dotnet-outdated) - 显示过时的NuGet的工具库。
* [Dotnet Script](https://github.com/filipw/dotnet-script) - 从.NET CLI运行C#脚本。
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) - 用于.NET Core CLI的简单命令行HTTP服务器。
* [Eighty](https://github.com/benjamin-hodgson/Eighty) - 一个简单的HTML生成库
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) -  Enums.NET是一个高性能类型安全的.NET枚举实用程序库
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) - 快速ExpressionTree编译器。
* [FluentDocker](https://github.com/mariotoffia/FluentDocker) - FluentDocker是一个与docker-machine，docker-compose和docker交互的库。
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) -  FTP和FTPS客户端，具有广泛的FTP命令，SSL / TLS连接，散列/校验等。
* [Fody](https://github.com/Fody/Fody) - 编辑.net程序集的可扩展工具。
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) - 高动态范围(HDR)直方图。
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - 用于拦截服务器端HTTP依赖关系的.NET标准库。
* [Humanizer](https://github.com/Humanizr/Humanizer) -  Humanizer满足您操作和显示字符串，枚举，日期，时间，时间跨度，数字和数量的所有.NET需求。
* [Humidifier](https://github.com/jakejscott/Humidifier) - Humidifier允许您以编程方式构建AWS CloudFormation模板。
* [impromptu-interface](https://github.com/ekonbenefits/impromptu-interface) - 将DLR与Reflect.Emit结合使用的库。
* [JqueryDataTablesServerSide](https://github.com/fingers10/JqueryDataTablesServerSide) - 用于jQuery DataTable的Asp.Net Core服务器端库，具有分页，过滤，排序和Excel导出功能。
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) - 围绕LibSass库的.NET包装器，能够支持虚拟文件系统。
* [markdig](https://github.com/lunet-io/markdig) - 可兼容Markdown处理库。
* [NetCoreBeauty](https://github.com/nulastudio/NetCoreBeauty) - 简单的库，用于将.NET Core应用程序运行时组件和依赖项移动到子目录中，并使其美观。
* [NFlags](https://github.com/bartoszgolek/NFlags) - 解析CLI和开箱即用功能的库。
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - 将字符串表达式(公式，方法调用，条件)解析为LINQ表达式树，可以编译为lambda并进行求值。
* [NuGet Trends](https://github.com/NuGetTrends/nuget-trends) - 查看NuGet软件包的采用情况以及NuGet的最新趋势程序。
* [NYoutubeDL](https://gitlab.com/BrianAllred/NYoutubeDL) - youtube-dl库。
* [Otp.NET](https://github.com/kspearrin/Otp.NET) - 在C#中实现TOTP RFC 6238和HOTP RFC 4226。
* [pose](https://github.com/tonerdo/pose) - 用委托替换任何.NET方法(包括静态和非虚拟)
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) -  Puppeteer Sharp是官方Node.JS Puppeteer API的.NET端口。
* [readline](https://github.com/tsolarin/readline) - 可以代替内置组件Console.ReadLine()的库。
* [ReflectionMagic](https://github.com/ReflectionMagic/ReflectionMagic) - Framework to drastically simplify your private reflection code using C# dynamic
* [Relinq](https://github.com/re-motion/Relinq) - 使用re-linq，现在比以往更容易创建功能齐全的LINQ提供商。
* [Remote.Linq](https://github.com/6bee/Remote.Linq) - Remote Linq是一个小型且易于使用但功能非常强大的库，可将LINQ表达树转换为强类型可序列化的表达树，反之亦然。
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) -  Html到Markdown转换器库，附带一些unix shell终端优势。
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) -  PdfReport.Core是一个代码优先的报告引擎，它建立在iTextSharp.LGPLv2.Core和EPPlus.Core库之上。
* [Scientist](https://github.com/github/Scientist.net) - 用于重构关键路径的.NET库。它是GitHub的Ruby Scientist库的一个端口。
* [Scrutor](https://github.com/khellang/Scrutor) -  Microsoft.Extensions.DependencyInjection的程序集扫描扩展。
* [Sheller](https://github.com/twitchax/Sheller) - 读取Shell脚本的库。
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) -  string.Format的可扩展替代品。
* Stocks
  * [Trady](https://github.com/lppkarl/Trady) - Trady是一个用于计算技术指标的便捷库，它的目标是成为一个自动交易系统，提供股票数据馈送，指标计算，策略建立和自动交易。
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) - System Linq Dynamic功能。
* [UnitsNet](https://github.com/angularsen/UnitsNet) -  Units.NET为您提供所有常用的度量单位和它们之间的转换。
* Validation
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - 流行的.NET验证库，用于构建强类型的验证规则。
  * [Guard](https://github.com/safakgur/guard) - 高性能，可扩展的参数验证库。
  * [Valit](https://github.com/valit-stack/Valit) - Valit是对.NET Core的简单验证库，减少if的使用。
* [Vanara](https://github.com/dahall/Vanara) - 一组用于Windows的.NET库，通过支持的包装程序实现了对许多本机Windows API的PInvoke调用。
* [warden-stack](https://github.com/warden-stack) - 针对您的应用程序，资源和基础架构的“运行状况检查”。让守望者守在手表上。
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) -  ASP.NET核心渐进式Web应用程序。
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) - 用于FFmpeg的.NET标准包装器。它允许在不知道FFmpeg如何工作的情况下处理媒体，并且可以用于将自定义参数传递给来自C#应用程序的FFmpeg。
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) - 用于提取元数据和下载Youtube视频和播放列表的终极库。

### 网络
* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy) -  Proxy代理库。
* [CurlThin](https://github.com/stil/CurlThin) - 轻量级cURL绑定库，支持通过curl_multi接口进行多个同时传输。
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) - HttpListener(NETStandard)。
* [Networker](https://github.com/MarkioE/Networker) - 一个简单易用的.NET TCP和UDP网络库，旨在实现灵活，可扩展和快速。

### 办公软件
* [EPPlus](https://github.com/JanKallman/EPPlus) - 使用.NET创建高级Excel电子表格。
* [npoi](https://github.com/tonyqus/npoi) - 可以读取/写入未安装Microsoft Office的Office格式的.NET库。没有COM +，没有互操作。
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) -  Open XML SDK提供了使用Office Word，Excel和PowerPoint文档的工具。

### 操作系统
* [CosmosOS](https://github.com/CosmosOS/Cosmos) - Cosmos是操作系统的“构建工具包”。使用托管语言（例如C＃，VB.NET等）构建自己的OS！

### 对象关系映射ORM
* [Chloe](https://github.com/shuxinqin/Chloe) - 用于.NET的轻量级高性能对象/关系映射(ORM)库。
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - EF，包括LINQ，POCO和Code First支持。
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) - EF的批量操作库
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - EF扩展库，包括过滤器，审核，缓存，查询将来，批删除，批更新等。
  * [EntityFramework.Exceptions](https://github.com/Giorgi/EntityFramework.Exceptions) - 当您的SQL查询违反SqlServer，MySql或PostgreSQL中的数据库约束时，请对EntityFrameworkCore使用类型化的异常处理。
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) - EF触发器.
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) - EF的Reactive 扩展程序。
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) - PostgreSQL的EF驱动程序
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) - EF的主键库。
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) - 获取实体属性.
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) -  EF找那个属性库。
  * [LINQKit](https://github.com/scottksmith95/LINQKit) - LINQKit是LINQ对SQL和Entity Framework的免费扩展集。
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - mysql的EF驱动程序。
  * [spectre.query](https://github.com/spectresystems/spectre.query) - EF的简单查询库。
* [Dapper](https://github.com/StackExchange/Dapper) -  .NET的简单对象映射器。
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Dapper的扩展。
  * [Dommel](https://github.com/henkmollema/Dommel) - Dapper的CRUD操作。
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - Dapper的CRUD操作。
* [FreeSql](https://github.com/2881099/FreeSql) -  ORM支持Mysql, Postgresql, SqlServer, Oracle and Sqlite.
* [Limebean](https://nick-lucas.github.io/LimeBean/) -  Hybrid-ORM，设计简单易用，不完全隐藏SQL，同时拥有您期望从ORM获得的所有好处。灵感来自RedBeanPHP。
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - LINQ to DB是最快的LINQ数据库访问库，在POCO对象和数据库之间提供了一个简单，轻便，快速且类型安全的层。
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) -  NHibernate对象关系映射器。
* [NEventStore](https://github.com/NEventStore/NEventStore) - 持久性库，该库的开发特别关注DDD / CQRS应用程序。
* [NPoco](https://github.com/schotime/NPoco) - 简单的microORM，可将查询结果映射到POCO对象。项目基于Schotime的PetaPoco。
* [NReco.Data](https://github.com/nreco/data) - 用于SQL命令生成，CRUD操作和简单POCO映射的轻量级的独立DAL。
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) - 对于你的POCO来说，这是一个很小的ORM东西。
* [querybuilder](https://github.com/sqlkata/querybuilder) -  SqlKata Query Builder是一个用C#编写的功能强大的Sql查询。
* [RepoDb](https://github.com/mikependon/RepoDb) - 用于.NET的动态，轻量，高效且非常快速的混合ORM库。
  * [RepoDb.MySql](https://github.com/mikependon/RepoDb/tree/master/RepoDb.MySql) - MySql的ORM库.
  * [RepoDb.SqLite](https://github.com/mikependon/RepoDb/tree/master/RepoDb.SqLite) - SqLite的ORM库.
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - 轻松，简单，快速的基于约定的POCO ORM。
* [SqlFu](https://github.com/sapiens/SqlFu) - 快速且通用的Micro-ORM。
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) -  SmartSql = MyBatis + Cache(Memory | Redis)+ ZooKeeper + R / W Splitting + Dynamic Repository ....
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) - 针对基于SQL的.NET实现的Stream Store库。

### 分析
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype) - 适用于.NET的轻量级，开源，实时诊断和洞察分析器。 `不稳定的版本`
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - 一个简单但有效的ASP.NET网站迷你探查器。

### sql生成器
* [SqlKata](https://github.com/sqlkata/querybuilder) - 优雅的Sql查询生成器，支持复杂查询，连接，子查询，嵌套条件，供应商引擎目标等等

### 消息队列
* [emitter](https://emitter.io/) - 连接所有设备的免费开源实时消息服务。此发布 - 订阅消息传递API是为了提高速度和安全性而构建的。
* [EventStore](https://github.com/EventStore/EventStore) - 使用JavaScript中的复杂事件处理的开源，功能数据库。
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - 内存，redis和azure实现的通用接口。
* [MediatR](https://github.com/jbogard/MediatR) -  中介模式库。
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR的扩展程序
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) -  .Net的简单中介，用于发送支持管道的命令，发布事件和请求响应。
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - MicroBus中介模式库。
* [MQTTnet](https://github.com/chkr1011/MQTTnet) -  MQTTnet是一个用于基于MQTT的通信的高性能.NET库。
* [netmq](https://github.com/zeromq/netmq) -  NetMQ是轻量级消息传递库。
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS) - 用于DDD，CQRS和事件的.NET核心库，具有Azure Service Bus集成。 Command和Event存储支持的数据库提供程序包括：DocumentDB，MongoDB，SQL Server，MySQL，PostgreSQL和SQLite。
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) -  RabbitMQ .NET客户端。
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - 用于通过RabbitMq进行通信的现代.NET框架。
* [Rebus](https://github.com/rebus-org/Rebus) -  .NET的简单和精简服务总线实现。
* [Restbus](http://restbus.org) -  RabbitMq的消息传递库。
* [Tossit](https://github.com/turgayozgur/tossit) - 简单易用的库，用于分布式作业/工作人员逻辑。内置RabbitMQ实现处理的分布式消息。

### 报表
* [FastReport](https://github.com/FastReports/FastReport) -  .NET Core 2.x / .Net Framework 4.x的开源报告生成器。 FastReport可用于MVC，Web API应用程序。

### 任务计划
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - 用于在日程安排上运行任务(作业)的轻量级健壮库。
* [Coravel](https://github.com/jamesmh/coravel) -  .Net Core符合Laravel：调度，排队等
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - 具有流畅界面的自动作业调度程序。
* [Gofer.NET](https://github.com/brthor/Gofer.NET) - 用于.NET Core的分布式后台任务/作业的简易C#API。
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - 在ASP.NET应用程序内执行即发即忘，延迟和重复性工作。
* [LiquidState](https://github.com/prasannavl/LiquidState) - 高效异步和同步状态机。
* [NCrontab](https://github.com/atifaziz/NCrontab) - 用于.NET的Crontab。
* [quartznet](https://github.com/quartznet/quartznet/) -  Quartz.NET任务计划程序。
* [stateless](https://github.com/dotnet-state-machine/stateless) - 用于在C#代码中创建状态机的简单库。

### 开发工具包SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net) -  Amazon Web Services(AWS).NET Core SDK组件。每个AWS服务都有自己的NuGet包。
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) -  Azure事件中心的.NET标准客户端库。
* Blockchain clients
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - Bittrex web API的库 。
  * [Binance.Net](https://github.com/JKorf/Binance.Net) - Binance Web的API库。
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient) -  CakeMail API的客户端。允许您发送交易电子邮件，批量电子邮件，管理列表和联系人等。
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - 面向领事的.NET API。
* [csharp-nats](https://github.com/nats-io/csharp-nats) - 用于NATS消息传递系统的C#.NET客户端。
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) -  .NET标准库，用于使用Dark Sky API
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - 用于Docker API的.NET(C#)客户端库。
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet) -  Firebase Admin .NET SDK
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) - 适用于.NET的Google Cloud Client Libraries。
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) - 一个完全面向对象的.Net包装器，用于Trello用C#编写的RESTful API。
* [Microphone](https://github.com/rogeralsing/Microphone) - 使用Consul或ETCD集群的Web Api或NancyFx运行自托管REST服务的轻量级框架。
* [octokit.net](https://github.com/octokit/octokit.net) - 用于.NET的GitHub API客户端库。
* [PreStorm](https://github.com/jshirota/PreStorm) -  ArcGIS Server的并行REST客户端。
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - 用于使用完整SendGrid API的C#客户端库。
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - 与.NET标准兼容的C#客户端与Etsy的优秀服务器。
* [tweetinvi](https://github.com/linvi/tweetinvi) - 直观的.NET C#库，用于访问Twitter REST和STREAM API。

### 安全
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) - 用于向ASP.NET Core应用程序添加安全标头的中间件。
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - 清除HTML以避免XSS攻击。
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - 用于处理JOSE对象的库(JWT，JWA，JWS及相关)。
* [Jwt.Net](https://github.com/jwt-dotnet/jwt) -  Jwt.Net，一个用于.NET的JWT(JSON Web令牌)实现。
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) - 用于ASP.NET Core的轻量级动态jwt服务器。
* [NWebsec](https://github.com/NWebsec/NWebsec) -  ASP.NET的安全库。
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - 用于ASP.NET Core的reCAPTCHA 2.0。
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) - 旨在帮助.NET应用程序进行安全审计的Roslyn分析器。
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) -  .NET Core中间件，用于注入Owasp推荐的HTTP标头，以提高安全性。
* [Security](https://github.com/aspnet/Security) - 于Web应用程序的安全性和授权的中间件。
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - 允许向ASP.NET Core网站添加安全标头的小包。

### 搜索
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) - 官方Algolia .NET客户端的存储库。
* [AutoComplete](https://github.com/omerfarukz/autocomplete) - 持久，简单，强大且可移植的自动完成库。
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - NEST和Elasticsearch.Net的存储库，这是两个官方Elasticsearch .NET客户端。
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) -  Elasticsearch .NET API。
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) -  IQueryable接口的高级搜索功能，例如Entity Framework查询。
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) - 相似度量标准库，例如从编辑距离(Levenshtein，Gotoh，Jaro等)到其他指标，(例如Soundex，Chapman)
* [SolrExpress](https://github.com/solr-express/solr-express) - 用于Solr的简单轻量级查询.NET库，采用可控，可构建和快速失败的方式。

### 序列化
* [BinarySerializer](https://github.com/jefffhaynes/BinarySerializer) - 二进制序列化库，用于控制字节和位级别的数据格式。
* [bond](https://github.com/Microsoft/bond) - 用于处理模式化数据的跨平台框架。它支持跨语言的序列化和强大的通用机制，可以有效地处理数据。 Bond广泛用于Microsoft的高规模服务。
* [Channels](https://github.com/davidfowl/Channels) - 基于推送的.NET流。
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - 帮助读写CSV文件的库。
* [Edi.Net](https://github.com/indice-co/EDI.Net) -  EDI Serializer / Deserializer。支持EDIFact，X12和TRADACOMS格式。
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - 用于.NET的扩展Xml序列化程序。
* [Jil](https://github.com/kevin-montrose/Jil) - 基于Sigil构建的快速.NET JSON(De)串行器。
* MessagePack 
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) - 公共语言基础结构的MessagePack实现。
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - MessagePack序列化程序库。
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - 适用于.NET的流行高性能JSON框架。
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - 用于惯用.NET的协议缓冲库。
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) -  Schema.org对象变成了强类型的C#POCO类，用于.NET。所有类都可以序列化为JSON / JSON-LD和XML，通常用于表示html页面头部的结构化数据。
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) -  JSON，JSV和CSV文本序列化器。
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - 易于使用，易于扩展和高性能的库，用于使用.NET进行CSV解析。
* [Wire](https://github.com/rogeralsing/Wire) -  POCO对象的二进制序列化程序。
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) -  .NET
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - 用于.NET的快速二进制(de)序列化程序。
* [Utf8Json](https://github.com/neuecc/Utf8Json) - 用于C#(.NET，.NET Core，Unity，Xamarin)的绝对最快和零分配JSON序列化器。
* [YAXLib](https://github.com/sinairv/YAXLib) - 用于.NET Framework和.NET Core的XML序列化库。非常灵活和强大。

### 模板引擎
* [dotliquid](https://github.com/dotliquid/dotliquid) - TobiasLütke的Liquid模板语言的.NET端口。
* [fluid](https://github.com/sebastienros/fluid) - 开源.NET模板引擎，尽可能接近Liquid模板语言。
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) - 用于读/写xaml文件的可移植.NET库。
* [Razor](https://github.com/aspnet/Razor) - 用于MVC Web应用程序视图页面的CSHTML文件的分析器和代码生成器。
* [RazorLight](https://github.com/toddams/RazorLight) - 基于Microsoft针对.NET Core的Razor解析引擎的模板引擎。
* [Scriban](https://github.com/lunet-io/scriban) - A fast, powerful, safe and lightweight text templating language and engine for .NET.

### 测试
* [Atata](https://github.com/atata-framework/atata) - 基于Selenium WebDriver的Web UI测试自动化全功能框架。
* [Bogus](https://github.com/bchavez/Bogus) - 简单而健全的C#假数据生成器。基于并从着名的faker.js移植。
* [CoreBDD](https://github.com/stevenknox/CoreBDD) -  xUnit.net的BDD框架
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) -  .NET的简易模拟库。
* [FluentAssertions](https://github.com/fluentassertions/fluentassertions) - 一组.NET扩展方法，允许您更自然地指定TDD或BDD样式测试的预期结果。
* [GenFu](https://github.com/MisterJames/GenFu) - 可用于生成实际测试数据的库。
* [LightBDD](https://github.com/LightBDD/LightBDD) -  BDD框架允许创建易于阅读和维护的测试。
* [mockhttp](https://github.com/richardszalay/mockhttp) - 为Microsoft的HttpClient库测试图层。
* [moq.netcore](https://github.com/Moq/moq4) - 最受欢迎且最友好的.NET模拟框架。
* [MSpec](https://github.com/machine/machine.specifications) - 用于编写BDD样式测试的流行测试框架。
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - 流畅的测试
  framework for ASP.NET Core MVC.
* [Netling](https://github.com/hallatore/Netling) - 加载测试客户端，以便轻松进行Web测试。
* [NSpec](https://github.com/nspec/NSpec) - 针对C#的战斗强化测试框架，受Mocha和RSpec的启发。
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) -  .NET模拟框架的友好替代品。
* [nunit](https://github.com/nunit/dotnet-test-nunit) - 面向.NET Core的NUnit测试运行器。
* [shouldly](https://github.com/shouldly/shouldly) - 断言框架*Should* be! 
* [SpecFlow](https://github.com/techtalk/SpecFlow) - SpecFlow是用于.NET的实用BDD解决方案。
* [Storyteller](https://github.com/storyteller/Storyteller) - 一种制定可执行规范的工具。
* [Stubbery](https://markvincze.github.io/Stubbery/) - 一个用于在.NET中创建和运行Api存根的简单库。
* [Testavior](https://github.com/geeklearningio/Testavior) -  Testavior是一个轻量级解决方案，可帮助您开发ASP.NET Core的行为测试。
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - 最简单的BDD框架！
* [xBehave.net](https://github.com/xbehave/xbehave.net) - 一个xUnit.net扩展，用于描述使用自然语言的测试。
* [xUnit.net](https://github.com/xunit/xunit) - 一个免费的，开源的，以社区为中心的.NET Framework单元测试工具。

### 工具
* [CliFx](https://github.com/Tyrrrz/CliFx) - 用于构建命令行界面的声明性框架。
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) -  .NET Core和.NET Framework的命令行解析和实用程序。
* [docfx](https://github.com/dotnet/docfx) - 用于构建和发布.NET项目API文档的工具
* [dotnetfiddle](https://dotnetfiddle.net) -  .NET沙箱，供开发人员快速尝试代码和共享代码片段。
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) -  .NET Core命令行(dotnet CLI)的工具扩展列表。
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) - 安装第三方库的工具.
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) -  .Net Core和.Net Framework 4.5+的可组合CLI(命令行)参数解析器。
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server) - 用于原型设计或作为CRUD后端的假REST API。无需定义类型，使用动态类型。数据存储在单个JSON文件中。具有身份验证，WebSocket通知，异步长时间运行操作，错误/延迟的随机生成以及实验性GraphQL支持。
* [gitignore.io](https://github.com/joeblau/gitignore.io) - 为您的项目创建有用的.gitignore文件。
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - 扫描上传的packages.config文件或GitHub存储库，并确定nuget包是否针对.NET Standard。
* [json2csharp](http://json2csharp.com) - 从JSON生成C#类。
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - 适用于Windows的简单ACME客户端。
* [Linq_Faster](https://github.com/jackmott/LinqFaster) - 数组，Span <T>和List <T>的类似于Linq的扩展。
 
* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) - 下一代mRemote，开源，标签，多协议，远程连接管理器
* [NJsonSchema](https://github.com/RSuter/NJsonSchema) -  NJsonSchema是一个.NET库，用于读取，生成和验证JSON Schema draft v4 + schemas。
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) - 自动更新.NET项目中的nuget包。
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - 使用GUI创建，更新和部署Nuget软件包。
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) - 为一组给定的git存储库或文件夹可视化所有nuget包及其相应的版本。
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用适用于GitHub的OctoLinker浏览器扩展，有效地浏览`projects.json`文件。
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) -  [dotnet CLI]的“PowerShell”标签完成(https://github.com/dotnet/cli)。
* [Rin](https://github.com/mayuki/Rin) -  ASP.NET Core的请求/响应Inspector中间件。像Glimpse。
* [scoop](https://github.com/lukesampson/scoop) -  Windows的命令行安装程序。
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer) - 使用Serilog日志库对基于Roslyn的代码进行分析。检查常见错误和使用问题。
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) -  #ziplib是一个完全用C#编写的适用于.NET平台的Zip，GZip，Tar和BZip2库。
* [ShareX](https://github.com/ShareX/ShareX) - 免费的开源程序，可让您捕捉或记录屏幕的任何区域，只需按一下键即可共享。它还允许将图像，文本或其他类型的文件上传到80多个支持的目的地，您可以从中选择。 [https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab) -  .NET代码游乐场，显示代码编译的中间步骤和结果。 [https://sharplab.io](https://sharplab.io)
* [sourcelink](https://github.com/dotnet/sourcelink) -  SourceLink是一个语言和源代码控制不可知系统，用于为二进制文件提供一流的源代码调试体验。
* [System.CommandLine](https://github.com/dotnet/command-line-api) - System.CommandLine：命令行解析，调用和呈现终端输出。
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) – 简单站点地图生成器。
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) – 简单站点RSS生成器。
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode) – SmartCode= IDataSource -> IBuildTask -> IOutput => Build Everything!!! (Including [Code generator])
* [Common.Utility](https://github.com/Jimmey-Jiang/Common.Utility) - 各种工具类，例如：上传下载，加密解密等

### Web框架
* WebAssembly
  * [Blazor](https://github.com/aspnet/blazor) - Blazor是使用C＃/ Razor和HTML的.NET Web框架，可在带有WebAssembly的浏览器中运行。 
    * [Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor) - Blazor的资源，Blazor是使用C＃/ Razor和HTML的.NET Web框架，可在具有WebAssembly的浏览器中运行。
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) - 将Redux状态存储与Blazor连接。
  * [Ooui](https://github.com/praeclarum/Ooui) - 是使用Web技术的.NET跨平台的小型UI库。
* [ReactJS.NET](https://github.com/reactjs/React.NET) - 用于JSX编译和React组件的服务器端呈现的.NET库。
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) -  .NET应用程序的可预测状态容器。

### Web Socket
* [Fleck](https://github.com/statianzo/Fleck) -  Fleck是C#中的WebSocket服务器实现。 Fleck不需要继承，容器或其他引用。
* [SignalR Server](https://github.com/aspnet/signalr) -  Web应用程序的实时Web功能，包括服务器端推送。
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - 轻量级，跨平台和可扩展的套接字服务器应用程序框架。
* [WampSharp](https://github.com/Code-Sharp/WampSharp) -  [Web应用程序消息传递协议]的C#实现- 提供远程消息传递模式的协议过程通过WebSockets调用和发布/预订。
* [websocket-manager](https://github.com/radu-matei/websocket-manager) -  ASP .NET Core的实时库。

### Windows服务
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - 直接从.NET Core设置并运行Windows服务。
* [Topshelf](https://github.com/Topshelf/Topshelf) - Windows服务框架。

### 工作流
* [CoreWF](https://github.com/dmetzgar/corewf/) -  Windows Workflow Foundation(WF)到.NET Core的端口。
* [workflow-core](https://github.com/danielgerlag/workflow-core) -  .NET Standard的轻量级工作流引擎。
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) - 在应用程序中添加工作流程的组件。
* [Wexflow](https://github.com/aelassas/Wexflow) - 高性能，可扩展，模块化和跨平台的工作流引擎。

## 线路图
* [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) - 2019年成为ASP.NET Core开发人员的路线图

## 入门套件
* [Arch](https://github.com/Arch) -  .NET Core库的集合。
  * [AutoHistory](https://github.com/Arch/AutoHistory) - 自动记录数据更改历史记录的插件。
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - 跨平台 - 用于SEO，Bootstrap，i18n国际化(ngx-translate)，Webpack的服务器端渲染，TypeScript，带Karma的单元测试，WebAPI REST设置，SignalR，Swagger文档等等！
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - 使用Visual Studio Code，C＃，F＃，JavaScript，ASP.NET Core，EF Core，React（ReactJS），Redux，Babel进行跨平台的Web开发。单页应用样板。
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) -  Yeoman生成器，用于构建全新的ASP.NET Core单页面应用程序，该应用程序使用Angular 2 / React / React与Redux / Knockout / Aurelia在客户端上。
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) -  Asp.NETCore 2.0 Vue 2(ES6)SPA入门套件，包含路由，Vuex等等！
* [bitwarden-core](https://github.com/bitwarden/core) - 核心基础设施后端(API，数据库等)[https://bitwarden.com](https://bitwarden.com)。
* [dotNetify](https://github.com/dsuryd/dotNetify) - 构建实时HTML5 / C#.NET Web应用程序的简单，轻量级但功能强大的方法。
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - 用于ASP.NET Core的yo生成器。
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) - 在后端使用ASP.NET Core API分层架构和基于JWT的身份验证的Vue启动应用程序模板
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - 使用ASP.NET Core 1构建同构React应用程序的起点，利用现有技术。
* [saaskit](https://github.com/saaskit/saaskit) - 用于构建SaaS应用程序的开发人员工具包。
* [serverlessDotNetStarter](https://github.com/pharindoko/serverlessDotNetStarter) - .NET Core入门解决方案-通过无服务器框架进行部署，并且可以在VS Code中进行本地调试。

## 例子
* Microservices & Service Mesh
 * [A lightweight Contact management (CRM)](https://github.com/tungphuong/crm) - 这是一个由微服务架构（.Net Core 3.0，React，Ract，GraphQL，Identity Server 4，gRPC，CQRS，RabbitMQ，Monitoring，Jaeger，Azure Pipeline，Seq，K8s，Linkerd，Helm 3组成的简化的联系人管理系统。
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices) -  一个基于Kubernetes的多语言微服务应用程序，带有Istio服务网格
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) - 带有Vagrant，Consul，Docker和ASP.NET Core的分布式服务游乐场。
  * [DNC-DShop](https://github.com/devmentors) - 分布式.NET核心项目和免费课程。 (DDD，CQRS，RabbitMQ，MongoDB，Redis，监控，记录，CI，CD)
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc) -   使用.NET Core(EF Core，MediatR，Marten，Eureka)在微服务架构中制作的简化保险销售系统，Ocelot，RabbitMQ，Polly，ElasticSearch，Dapper)与博客文章系列。
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - 基于微服务架构和容器的参考应用程序。
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) - Akka.NET参考架构 - CQRS + Sharding +内存中复制
  * [magazine-website](https://github.com/thangchung/magazine-website) -  应用DDD，CQRS，微服务，异步编程的杂志网站(使用.NET Core，ASP.NET Core，EF Core)。
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnet-book-second-edition) - 我的微服务书中的代码示例
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - 实时交易平台演示，展示在整个应用程序堆栈中应用的反应式编程原理。
* Monoliths
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5示例。
  * [allReady](https://github.com/HTBox/allReady) - 开源解决方案，重点是提高准备活动的意识，效率和影响，因为它们由当地社区的人道主义和灾害响应组织提供。[http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET核心MVC Geo Elasticsearch Swashbuckle Swagger。
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - 使用ASP.NET Core实现服务发现模式的示例。
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - 一个研讨会，用于浏览ASP.NET核心授权中的各个新部分。
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) - BikeSharing360应用套件
    * [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), 
    * [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), 
    * [Websites](https://github.com/Microsoft/BikeSharing360_Websites), 
    * [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), 
    * [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), 
    * [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
	* [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
  * [Clean Architecture Manga](https://github.com/ivanpaulovich/clean-architecture-manga) - .NET Core的清洁架构原理的示例
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) - ASP.NET核心多租户Web应用程序基础。
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - 一个开源小型本地开发活动的开源网站。
  * [DotNetClub](https://github.com/scheshan/DotNetClub) - 用ASP.NET Core编写的小型俱乐部。
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - 具有单一部署模型的分层应用程序架构。
  * [Entropy](https://github.com/aspnet/Entropy) - 用于新功能和想法的混乱实验游乐场 - 请在此处查看针对各个功能的小型和简单样本。
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - 具有DDD，CQRS和事件源的完整ASP.NET Core 2.0应用程序。
  * [GenVue](https://github.com/herbat73/GenVue) - 如何管理多租户应用中的用户身份Microsoft Azure，使用Azure Active Directory进行身份验证。
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - Microsoft Azure中多租户应用程序的身份管理例子。
  * [JustA.ML](https://github.com/mustakimali/JustA.ML) -  一个Web应用程序，允许您在使用ASP.NET Core 2.0编写的设备之间共享文件/ URL /文本。
  * [MegaMine](https://github.com/Nootus/MegaMine) - 开源挖掘解决方案，帮助矿工提取黄金，石英，花岗岩等。此解决方案使用ASP.NET Core和AngularJS利用多个轻量级组件构建以微服务的方式。
  * [MusicStore](https://github.com/dotnet/aspnetcore/tree/master/src/MusicStore) - 使用MVC和Entity Framework的示例MusicStore应用程序。
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - 带有.NET Core Preview 2的NLayerAppV3 N层架构。
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) - Northwind Traders是使用ASP.NET Core和Entity Framework Core构建的示例应用程序。
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) - 使用Orchard Core Framework创建模块化和多租户应用程序。
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - 使用ASP.NET Core，Angular 2和TypeScript的跨平台单页应用程序
  * [PokeR](https://github.com/halomademeapc/pokeR) - 在ASP.NET Core的SPA托管中使用SignalR和Angular进行实时Scrum。 包括Docker支持。. [Demo](https://planning.halomademeapc.com)
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - 每日更新的ASP.NET核心功能和设施的微量示例。
  * [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) -  使用Clean Architecture的原始SQL和DDD的.NET Core REST API CQRS实现。
  * [StarWars](https://github.com/JacekKosciesza/StarWars) - 使用GraphQL for .NET，ASP.NET Core，Entity Framework Core的GraphQL“星球大战”示例。
 
## 文章
* 基础知识
  * [具有相关视频的综合BikeSharing360演示应用程序套件的Microsoft架构概述](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [将.NET Framework库移植到.NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [在执行一行代码之前CLR执行的68件事](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * .NET核心和Nodejs在[这里]的比较 [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [了解ASP.NET核心初始化](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [为什么要加入.NET Core和ASP.NET Core列车](https://codingblast.com/why-you-should-join-asp-net-core/)
* Cloud Development
  * [在.NET Core中配置AWS开发工具包](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [使用C#和AWS Amazon Gateway Api / Lambda的无服务器架构](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [在Amazon Web Services(AWS)Lambda中使用C#和.NET Core *配置和部署](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* Configuration and deployment
  * [.NET项目结构](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [将Travis CI构建添加到.NET Core应用程序](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - 配置ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy，nginx，Angular 2，ASP.NET Core，Redis和Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json到MSBuild转换指南](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [使用Appveyor和NuGet发布.NET项目](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [ASP.NET核心中的新配置模型 *实体框架核心](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Entity Framework Core
  * [.NET核心数据访问](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [关于EF Core的一个很好的例子](https://github.com/rowanmiller/Demo-EFCore)
  * [使用EF Core连接到Postgres *神奇](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
* Miraculous
  * [Orchard Core作为NuGet包入门](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [如何在ASP.NET Core中将HTML导出为PDF](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [使用ASP.NET Core进行Vue.js服务器端渲染 *安全](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET持续交付微服务](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0身份验证和授权系统揭秘](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [ASP.NET授权实验室的演练](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [ASP.NET核心中的身份验证 *测试](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [使用.NET Core的Selenium](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)
- [InfoQ .NET articles](https://www.infoq.com/dotnet) -  Collection of best .NET articles on InfoQ site

## 书籍
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [C# in Depth 4](https://www.amazon.com/C-Depth-Jon-Skeet/dp/1617294535)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Essencial C# 7.0](https://www.amazon.com/Essential-7-0-Addison-Wesley-Microsoft-Technology/dp/1509303588)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)

## 备忘录
* [dotnet cli Cheat Sheet](http://en.otomatikmuhendis.com/2018/07/02/cheat-sheet-for-dotnet-cli/)

## 视频学习
* [Channel9](https://channel9.msdn.com) -  MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) -  YouTube
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

## 视频播客
* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## 社区
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [.NET Blog](https://devblogs.microsoft.com/dotnet/)
* [CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects)
* [ASP.NET](https://forums.asp.net)
* [Channel9](https://channel9.msdn.com)
* [Awesome .NET open source & community resources](https://discoverdot.net)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* [BuiltWithDot.Net](https://builtwithdot.net)
* Stack Overflow
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)
* [Trending .NET repositories on GitHub today](https://github.com/trending?l=csharp)

## 组织
* [ASP.NET](https://github.com/aspnet) - ASP.NET and Entity Framework
* [.NET Platform](https://github.com/dotnet) - 开源.NET源码
* [microsoft](https://github.com/microsoft) - 微软
* [.NET Core Community](https://github.com/dotnetcore) - .NET中文社区组织
* [.NET 社区联盟](https://dotnet-china.com/) - 中国.NET社区联盟


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.

