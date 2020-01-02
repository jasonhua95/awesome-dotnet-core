# awesome-dotnet-core
.NET Core框架、库和软件的中文收录大全。内容包括：库、工具、框架、模板引擎、身份认证、数据库、ORM框架、图片处理、文本处理、机器学习、日志、代码分析、教程等。
这里记录的大部分可以链接到github上，Nuget上也有对应的包，这里只记录比较牛的项目。
  
[国内](README_CN.md)  | [中文](README.md)  | [English](README_EN.md) 

## 目录
* [微软](#微软)
* [ORM](#ORM)
* [IOC](#IOC)
* [日志](#日志)
* [分布式](#分布式)
* [测试](#测试)
* [性能](#性能)
* [消息队列](#消息队列)
* [数据库](#数据库)
* [服务器](#服务器)
* [缓存](#缓存)
* [框架](#框架)
* [项目](#项目)
* [序列化](#序列化)
* [定时任务](#定时任务)
* [Actor模型](#Actor模型)
* [二维码](#二维码)
* [异常](#异常)
* [邮件](#邮件)
* [Office](#Office)
* [其他](#其他)
* [博客](#博客)

### 微软
* [ASP.NET Core官方文档](https://docs.microsoft.com/zh-cn/aspnet/core/?view=aspnetcore-3.1)
* [.NET指南](https://docs.microsoft.com/zh-cn/dotnet/welcome)
* [C#指南](https://docs.microsoft.com/zh-cn/dotnet/csharp/)
* [.NET Standard 指南](https://docs.microsoft.com/zh-cn/dotnet/standard/)
* [.NET Core 指南](https://docs.microsoft.com/zh-cn/dotnet/core/)
* [.NET Core源码](https://github.com/aspnet/AspNetCore)
* [.NET Framework源码](https://referencesource.microsoft.com/)
* [.NET Core官方播客](https://devblogs.microsoft.com/dotnet/tag/net-core/)
* [.NET 官方播客](https://devblogs.microsoft.com/dotnet/)
* [Visual Studio Code](https://github.com/Microsoft/vscode)
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx)

### ORM
> 比较流行的对象关系映射（ORM），支持主流的数据库SQLite, SQL CE, Firebird, Oracle, MySQL, PostgreSQL and SQL Server等。
* [StackExchange/Dapper](https://github.com/StackExchange/Dapper)
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite)
* [NHibernate](https://github.com/nhibernate/nhibernate-core)
* [sqlite-net-pcl](https://github.com/praeclarum/sqlite-net)
* [NPoco](https://github.com/schotime/NPoco)
* [SqlSugar](https://github.com/sunkaixuan/SqlSugar) 
* [EF](https://github.com/aspnet/EntityFrameworkCore)
* [linq2db](https://github.com/linq2db/linq2db)
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco)
* [LINQKit](https://github.com/scottksmith95/LINQKit)
* [FreeSql](https://github.com/2881099/FreeSql)
* [AutoMapper](https://github.com/AutoMapper/AutoMapper)

### IOC
> 比较流行的控制反转（IOC），最常见的依赖注入（DI）
* [Autofac](https://github.com/autofac/Autofac)
* [DryIoc](https://github.com/dadhi/DryIoc)
* [structuremap](https://github.com/structuremap/structuremap)
* [Ninject](https://github.com/ninject/ninject)
* [CommonServiceLocator](https://github.com/unitycontainer/commonservicelocator)
* [Unity](https://github.com/unitycontainer/unity)
* [IoC.Container](https://github.com/DevTeam/IoCContainer/)

### 日志
* [NLog](https://github.com/NLog/NLog/)
* [log4net](https://github.com/apache/logging-log4net/)

### 分布式
* Orleans
  * [Microsoft.Orleans.OrleansProviders](https://github.com/dotnet/Orleans)
* HealthChecks
  * [Microsoft.Extensions.Diagnostics.HealthChecks](https://github.com/aspnet/Extensions)
  * [Microsoft.AspNetCore.HealthChecks](https://github.com/seven1986/HealthChecks)
  * [AspNetCore.HealthChecks.SqlServer](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks)
  * [AspNetCore.HealthChecks.Rabbitmq](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks)
* [Ocelot](https://github.com/ThreeMammals/Ocelot)
* [Polly](https://github.com/App-vNext/Polly)
* [ElasticSearch]
  * [Elasticsearch.Net](https://github.com/elastic/elasticsearch-net)

### 测试
* [XUnit](https://github.com/xunit/xunit)
* [Moq](https://github.com/moq/moq4)
* [NUnit](https://github.com/nunit/nunit)

### 性能
* [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet)

### 消息队列
* RabbitMQ
  * [RabbitMQ.Client](https://github.com/rabbitmq/rabbitmq-dotnet-client)
  * [MassTransit.RabbitMQ](https://github.com/MassTransit/MassTransit)


### 数据库
* EF
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/aspnet/EntityFrameworkCore)
  * [Microsoft.EntityFrameworkCore.SqlServer](https://github.com/aspnet/EntityFrameworkCore)
  * [Microsoft.EntityFrameworkCore.Sqlite](https://github.com/aspnet/EntityFrameworkCore)
  * [Microsoft.EntityFrameworkCore.InMemory](https://github.com/aspnet/EntityFrameworkCore)
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/efcore.pg)
* [Npgsql](https://github.com/npgsql/npgsql)
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0)
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector)
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver)
  * [Neo4jClient](https://github.com/Readify/Neo4jClient)
* NoSql
  * [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net)
  * [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver)
  * [LiteDB](https://github.com/mbdavid/LiteDB)
  * Redis
    * [StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis/)
    * [Microsoft.Extensions.Caching.Redis](https://github.com/aspnet/Extensions)
    * [ServiceStack.Redis](https://github.com/ServiceStack/ServiceStack.Redis)
    * [Microsoft.AspNetCore.SignalR.Redis](https://github.com/aspnet/AspNetCore)

### 服务器
* [Nginx](https://www.nginx.com/)
* Kestrel
  * [Microsoft.AspNetCore.Server.Kestrel](https://github.com/aspnet/KestrelHttpServer)

### 缓存
* [CacheManager](http://cachemanager.michaco.net/)
  * [CacheManager.Core](https://github.com/MichaCo/CacheManager)
* [EasyCaching](https://easycaching.readthedocs.io/en/latest/)
  * [EasyCaching.Core](https://github.com/dotnetcore/EasyCaching)
* [Memcached](https://memcached.org/)
  * [EnyimMemcached](https://github.com/enyim/EnyimMemcached)
  * [CacheManager.Core](https://github.com/MichaCo/CacheManager)

### 框架
* [Nancy](https://github.com/NancyFx/Nancy)
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) 
* [Abp vNext](https://github.com/abpframework/abp)

### 项目
* CMS
  * [OrchardCore](https://github.com/OrchardCMS/OrchardCore)
* [Serenity](https://github.com/volkanceylan/Serenity) 
* [eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers)
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS)
* [nopCommerce](https://github.com/nopSolutions/nopCommerce)
* [grandnode](https://github.com/grandnode/grandnode)
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce)

### 序列化
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)
* [Json.Net](https://github.com/obarlik/Json.Net)

### 定时任务
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler)
* [Quartz.NET](https://github.com/quartznet/quartznet)

### Actor模型
* [Akka.NET](https://github.com/akkadotnet/akka.net)
* [System.Reactive(Rx.NET)](https://github.com/Reactive-Extensions/Rx.NET) 

### 二维码
* [QRCoder](https://github.com/codebude/QRCoder/)

### 异常
* [Ben.Demystifier](https://github.com/benaadams/Ben.Demystifier)
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net)

### 邮件
* [MailKit](https://github.com/jstedfast/MailKit)
* [FluentEmail](https://github.com/lukencode/FluentEmail)

### Office
* [EPPlus](https://github.com/JanKallman/EPPlus)
* [npoi](https://github.com/tonyqus/npoi)
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK)

### 其他
* Swagger - api生成文档
  * [Swashbuckle.AspNetCore.Swagger](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
* [Topshelf](https://github.com/Topshelf/Topshelf) - Windows服务框架。
* [ML.NET](https://github.com/dotnet/machinelearning) - 机器学习框架。

### 博客
* [博客园](https://www.cnblogs.com/)














