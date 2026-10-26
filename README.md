# 精彩的自托管软件列表 (Awesome Selfhosted)

这是一个包含免费网络应用程序和在线服务的列表,可以托管在你自己的服务器上。这些是开源软件、MIT许可或类似许可证的替代方案。

**目录**

- [精彩的自托管软件列表](#精彩的自托管软件列表-awesome-selfhosted)
  - [关于](#关于)
  - [如何使用此列表](#如何使用此列表)
  - [什么是自托管？](#什么是自托管)
  - [重要说明](#重要说明)
  - [软件/服务](#软件服务)
    - [自动化](#自动化)
    - [书籍和图书馆](#书籍和图书馆)
    - [日历和联系人](#日历和联系人)
    - [通讯录管理](#通讯录管理)
    - [内容管理系统(CMS)](#内容管理系统cms)
    - [数据库管理工具](#数据库管理工具)
    - [DNS和域名](#dns和域名)
    - [开发-项目管理](#开发---项目管理)
    - [文档管理](#文档管理)
    - [电子商务](#电子商务)
    - [电子邮件](#电子邮件)
    - [文件传输-单向分享和同步](#文件传输---单向分享和同步)
    - [文件传输-双向同步和共享](#文件传输---双向同步和共享)
    - [财务和会计](#财务和会计)
    - [游戏服务器](#游戏服务器)
    - [组群管理](#组群管理)
    - [健康跟踪器](#健康跟踪器)
    - [主页和仪表板](#主页和仪表板)
    - [人类资源管理(HRM)](#人类资源管理hrm)
    - [图片和视频画廊](#图片和视频画廊)
    - [即时消息(IM)](#即时消息im)
    - [学习课程管理系统(LMS)](#学习课程管理系统lms)
    - [地图和全球定位系统(GPS)](#地图和全球定位系统gps)
    - [媒体流媒体-音频流](#媒体流媒体---音频流)
    - [媒体流媒体-视频流](#媒体流媒体---视频流)
    - [媒体流媒体-多媒体流](#媒体流媒体---多媒体流)
    - [监控](#监控)
    - [网络统计和分析](#网络统计和分析)
    - [笔记和编辑器](#笔记和编辑器)
    - [办公套件](#办公室套件)
    - [密码管理器](#密码管理器)
    - [个人知识管理(PKM)](#个人知识管理pkm)
    - [照片和视频库](#照片和视频库)
    - [代理](#代理)
    - [阅读和电子书](#阅读和电子书)
    - [搜索引擎](#搜索引擎)
    - [安全-身份验证](#安全---身份验证)
    - [安全-证书颁发机构(CA)](#安全---证书颁发机构ca)
    - [软件集成](#软件集成)
    - [软件开发-API管理](#软件开发---api管理)
    - [软件开发-代码审查](#软件开发---代码审查)
    - [软件开发-持续集成(CI/CD)](#软件开发---持续集成cicd)
    - [软件开发-Git服务](#软件开发---git服务)
    - [软件开发-问题追踪和项目管理](#软件开发---问题追踪和项目管理)
    - [软件开发-低代码平台](#软件开发---低代码平台)
    - [状态页面和Uptime监控](#状态页面和uptime监控)
    - [任务管理和待办事项列表](#任务管理和待办事项列表)
    - [工单系统](#工单系统)
    - [时间跟踪](#时间跟踪)
    - [旅行组织](#旅行组织)
    - [URL缩短器](#url缩短器)
    - [视频监控](#视频监控)
    - [VPN](#vpn)
    - [Web服务器](#web服务器)
    - [维基(Wiki)](#维基wiki)
  - [许可证列表](#许可证列表)
  - [反功能特性](#反功能特性)
  - [外部链接](#外部链接)
  - [贡献指南](#贡献指南)
  - [许可证](#license)

## 关于

这是一个社区项目,于2015年6月由[Kevon Quisimber](https://github.com/KevonQuisimber)作为[awesome列表](https://github.com/sindresorhus/awesome)的一部分创建。

该列表已从[原始仓库](https://github.com/awesome-selfhosted/awesome-selfhosted)迁移到此仓库。数据存储在[awesome-selfhosted-data](https://github.com/awesome-selfhosted/awesome-selfhosted-data)仓库中。

## 如何使用此列表

- 使用浏览器的查找功能(Ctrl+F或Command+F)搜索关键词
- 点击分类标题旁边的锚点链接(`^`)可返回目录顶部
- 每个条目都标记有`⚠️`(如果它依赖于专有在线服务)、许可证和技术栈信息

## 什么是自托管？

自托管是在你自己的服务器或云实例上运行你拥有的软件和服务,而不是使用第三方托管的SaaS(软件即服务)替代方案。

**自托管的好处:**

- 数据隐私 - 你拥有并控制你的数据
- 成本节约 - 无订阅费用
- 定制化 - 完全控制配置和功能
- 可靠性 - 不依赖外部服务的可用性
- 安全性 - 你负责实施安全措施
- 学习机会 - 了解系统管理和DevOps

**自托管需要考虑的因素:**

- 技术知识 - 需要一定的系统管理技能
- 维护责任 - 你负责更新、备份和安全
- 硬件成本 - 服务器或VPS的费用
- 时间投入 - 初始设置和持续维护的时间

## 重要说明

⚠️ **请仔细阅读以下重要信息:**

1. **安全性:** 自托管软件需要你自行负责安全性。请确保:
   - 保持软件更新到最新版本
   - 配置适当的防火墙规则
   - 使用强密码和双因素认证
   - 定期备份数据
   - 监控系统日志

2. **许可证合规:** 请尊重每个软件的许可证要求。某些许可证可能对商业使用有特殊限制。

3. **依赖项:** 标记为 `⚠️` 的条目表示该软件依赖于用户无法控制的专有服务。在使用前请了解其依赖关系。

4. **技术支持:** 大多数开源软件通过GitHub Issues、Discord或论坛提供社区支持。商业支持可能需要付费。

## 软件/服务

### 自动化

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[自动化](https://en.wikipedia.org/wiki/Automation)是通过技术减少人工工作的过程。

_相关: [软件集成](#软件集成)_

- [Activepieces](https://www.activepieces.com/) - 高效且灵活的业务自动化工具。开源的Zapier和Power Automate替代品。([源代码](https://github.com/activepieces/activepieces)) `MIT` `Nodejs/Docker`
- [Automatisch](https://automatis.io/) - 开源的Zapier替代品。你可以自我托管它,并且它可以在你的基础设施上运行。([演示](https://cloud.automatis.io), [源代码](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [Dify](https://dify.ai/) - 开源的LLM应用开发平台。Dify的直观界面结合了AI工作流、RAG管道、智能体能力、模型管理、可观测性功能和更多功能,让你快速从原型转向生产。([源代码](https://github.com/langgenius/dify)) `Apache-2.0` `Docker`
- [Huginn](https://github.com/huginn/huginn) - Huginn是一个用于构建agent的系统,它在互联网上为你执行自动化的任务。你可以将它们视为你自己的个人Ifttt或Zapier。`MIT` `Ruby/multi`
- [n8n](https://n8n.io/) - 自托管的基于节点的自动化工具,具有基于浏览器的界面,易于使用。([源代码](https://github.com/n8n-io/n8n)) `Sustainable Use` `Nodejs/Docker`
- [Windmill](https://www.windmill.dev/) - 开发者优先的工作流和内部工具平台,将Python、Typescript、Go脚本转换为强大的UI、工作流和内部工具。([源代码](https://github.com/windmill-labs/windmill)) `AGPL-3.0/Apache-2.0` `Rust/Python/TypeScript/Docker/K8S`

### 书籍和图书馆

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

数字图书馆和电子书管理软件。

- [Audiobookshelf](https://www.audiobookshelf.org/) - 一个自托管的Audible服务器,用于管理和流式传输你的电子书和有声读物。([源代码](https://github.com/advplyr/audiobookshelf)) `MIT` `Nodejs/Docker`
- [BookWyrm](https://joinbookwyrm.com/) - 用于追踪阅读的社交网络,具有联邦式/去中心化的结构。([源代码](https://github.com/bookwyrm-social/bookwyrm)) `AGPL-3.0` `Python/Docker`
- [Calibre-Web](https://github.com/janeczku/calibre-web) - Calibre的Web应用,提供整洁的界面用于通过浏览器浏览、阅读和下载电子书。`GPL-3.0` `Python/Docker/K8S`
- [Kavita](https://www.kavitareader.com/) - 一个快速、功能丰富、跨平台的漫画、Manga和电子书服务器,建立在Greed之上。([演示](https://demo.kavitareader.com), [源代码](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [Komga](https://komga.org/) - 一个漫画/Manga媒体服务器。([源代码](https://github.com/gotson/komga)) `BSD-3-Clause` `Kotlin/Docker`
- [LibrarySphere](https://github.com/Library-Sphere/LibrarySphere) - LibrarySphere是一个现代的、用户友好的图书管理系统,旨在简化图书馆操作。它提供了全面的功能集,包括图书编目、用户管理和借阅跟踪。`MIT` `Docker/Nodejs`
- [Stump](https://stumpapp.dev/) - 一个快速、美观且功能丰富的漫画和电子书阅读器/服务器。(替代Komga和Kavita)。([源代码](https://github.com/stump-app/stump)) `MIT` `Rust/Docker`
- [TachiyomiMi](https://github.com/nickvdyck/tachiyomi-mi) - 一个免费的、开源的Manga阅读器,适用于Android、iOS、MacOS、Linux和Windows。([源代码](https://github.com/nickvdyck/tachiyomi-mi)) `Apache-2.0` `Docker/K8S`

### 日历和联系人

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于组织日程安排和管理联系信息的软件。

- [Baïkal](https://sabre.io/baikal/) - 轻量级的CalDAV + CardDAV服务器。([源代码](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [Caldav](https://github.com/niclas-nicklern/caldav) - 一个简单的CalDAV日历服务器,专注于性能和易用性。([源代码](https://github.com/niclas-nicklern/caldav)) `MIT` `Go/Docker`
- [DAViCal](https://gitlab.com/davical-project/davical) - 服务器端CalDAV和CardDAV服务器。([源代码](https://gitlab.com/davical-project/davical/-/blob/master/README.md)) `GPL-2.0+` `PHP/deb`
- [Etebase](https://etebase.com/) - Etebase是一个安全的、端到端加密的后端,用于同步日历、联系人和任务(替代Nextcloud)。([源代码](https://github.com/etesync/server)) `AGPL-3.0` `Python/Docker/K8S`
- [EteSync](https://www.etesync.com/security/) - EteSync是一个安全的、端到端加密的同步解决方案,用于你的日历、联系人和任务。(注意:EteSync v1已被弃用;请改用Etebase) ([源代码](https://github.com/etesync/server)) `AGPL-3.0` `Python/Docker/K8S`
- [InfCloud](https://www.inf-it.com/open-source/index.html) - 带有CalDAV/CardDAV支持的基于Web的日历和客户端。`AGPL-3.0或商业` `Javascript`
- [JMAP Proxy](https://github.com/fastmailteam/jmap-proxy) - JMAP代理是IMAP/SMTP/LDAP/Caldav/CardDAV服务器和任何兼容JMAP客户端之间的桥梁。([源代码](https://github.com/fastmailteam/jmap-proxy)) `MIT` `Perl`
- [Monica](https://www.monicahq.com/) - 个人CRM。记住你认识的人的一切。([演示](https://app.monicahq.com/), [源代码](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP/Docker`
- [Nextcloud Calendar & Contacts](https://nextcloud.com/) - 具有CalDAV和CardDAV功能的日历和联系人解决方案。([源代码](https://github.com/nextcloud/calendar), [源代码](https://github.com/nextcloud/contacts)) `AGPL-3.0` `PHP/Docker`
- [Open WebCalendar](https://open-web-calendar.hosted.quelltext.org/) - 在网页中嵌入高度可定制的日历。无需手动更新事件。从多个源获取数据:iCal/.ics URL(通过Fetch API或CORS代理)、远程JSON、本地JSON或Google Calendar URL。([源代码](https://niccokunzmann/open-web-calendar)) `MIT` `Docker`
- [Radicale](https://radicale.org/) - CalDAV和CardDAV服务器(目标:简单的安装和配置)。([源代码](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python/Docker/deb`
- [SnappyMail](https://snappymail.eu/) - 具有日历功能的简单、现代和快速的基于Web的电子邮件客户端。([源代码](https://github.com/the-djmaze/snappymail)) `AGPL-3.0` `PHP/Docker`
- [Zimbra](https://www.zimbra.com/) - 协作软件套件,其中包括电子邮件、日历、文件共享、任务、通讯录管理、即时消息和视频会议。([源代码](https://github.com/Zimbra/zm-build)) `Commons Clause 1.0` `Java/deb/Docker/K8S`

### 通讯录管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

通讯录管理软件用于组织和存储联系人信息。

- [Addressbook](https://github.com/twostairs/paperwork-addressbook) - Paperwork的一个简单但功能强大的地址簿/联系人管理插件。`GPL-3.0` `PHP`
- [bitwarden_rs / Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Bitwarden服务器API的非官方兼容实现,用Rust编写。`GPL-3.0` `Rust/Docker`
- [Contacts](https://github.com/nextcloud/contacts) - Nextcloud的联系人管理应用。`AGPL-3.0` `PHP/Docker`
- [Monica Personal CRM](https://github.com/monicahq/monica) - 个人关系管理器。`AGPL-3.0` `PHP/Docker`
- [phpIPAM](https://phpipam.net/) - 开源的IP地址管理Web应用程序。其目标是提供轻量级、现代和有用的IP地址管理。([源代码](https://github.com/phpipam/phpipam)) `GPL-3.0` `PHP`


### 自动化

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[自动化](https://zh.wikipedia.org/wiki/自动化)软件旨在减少流程中的人工干预。

_相关: [物联网(IoT)](#物联网iot), [软件开发 - 持续集成与部署](#软件开发---持续集成与部署), [媒体管理](#媒体管理)_

- [Activepieces](https://www.activepieces.com) - 无代码业务自动化工具,类似于Zapier或Tray。例如,您可以为每个新的Trello卡片发送Slack通知。([源代码](https://github.com/activepieces/activepieces)) `MIT` `Docker`
- [Apache Airflow](https://airflow.apache.org/) - 用于以编程方式编写、调度和监控工作流的平台。([源代码](https://github.com/apache/airflow/)) `Apache-2.0` `Python/Docker`
- [Automatisch](https://automatisch.io) - 业务自动化工具,允许您连接不同的服务(如Twitter、Slack等)来自动化您的业务流程(Zapier的替代品)。([源代码](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Docker`
- [BookBounty](https://github.com/TheWicklowWolf/BookBounty) `⚠` - 从Library Genesis获取Readarr缺失的书籍。`MPL-2.0` `Docker`
- [changedetection.io](https://changedetection.io/) - 及时了解网站内容的变更。([源代码](https://github.com/dgtlmoon/changedetection.io)) `Apache-2.0` `Python/Docker`
- [ChiefOnboarding](https://chiefonboarding.com) - 员工入职平台,允许您配置用户帐户并创建包含待办事项、资源、文本/电子邮件/Slack消息等的序列!可作为Web门户和Slack机器人使用。([源代码](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Docker`
- [Cronicle](https://cronicle.net/) - 简单的分布式任务调度器和运行器,具有基于Web的用户界面。([源代码](https://github.com/jhuckaby/Cronicle)) `MIT` `Nodejs`
- [Cronmaster](https://github.com/fccview/cronmaster) - Cronjob管理界面,具有人类可读的语法、实时日志记录和cronjob日志历史记录。`AGPL-3.0` `Docker`
- [Dagu](https://docs.dagu.cloud/) - 强大的Cron替代品,具有Web UI。它允许您以声明式YAML格式将命令之间的依赖关系定义为有向无环图(DAG)。([源代码](https://github.com/dagucloud/dagu)) `GPL-3.0` `Go/Docker`
- [Discount Bandit](https://discount-bandit.cybrarist.com/) `⚠` - 跟踪Amazon、Ebay、Walmart等多个商店的产品价格和库存状态。([源代码](https://github.com/Cybrarist/Discount-Bandit)) `GPL-3.0` `PHP/Docker`
- [Dittofeed](https://www.dittofeed.com) - 全渠道客户参与和消息自动化平台(Braze、Customer.io、Iterable的替代品)。([演示](https://demo.dittofeed.com/dashboard/journeys), [源代码](https://github.com/dittofeed/dittofeed)) `MIT` `Docker`
- [flowctl](https://flowctl.net) - 具有审批、远程执行和调度功能的自助服务工作流执行平台。([演示](https://demo.flowctl.net), [源代码](https://github.com/cvhariharan/flowctl)) `Apache-2.0` `Go/Docker`
- [Fredy](https://fredy.orange-coding.net/) `⚠` - 在ImmoScout24、Immowelt等平台上搜索德国的新公寓、房屋和公寓,并通过Slack、Telegram等即时将结果发送给您。([演示](https://fredy-demo.orange-coding.net), [源代码](https://github.com/orangecoding/fredy)) `Apache-2.0` `Nodejs/Docker`
- [gocron](https://github.com/flohoss/gocron) - 任务调度器,允许用户通过简单的YAML配置文件指定周期性任务。`MIT` `Docker`
- [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web) - 通过Web界面在无头设备上使用一个或多个HandBrake视频转码实例。`AGPL-3.0` `Docker`
- [Healthchecks](https://healthchecks.io/) - 监听ping请求,并在ping延迟时发送警报。([源代码](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python/Docker`
- [Huginn](https://github.com/huginn/huginn) - 构建代理来监控并代表您执行操作。`MIT` `Ruby`
- [Kestra](https://kestra.io) - 事件驱动、与语言无关的平台,用于创建、调度和监控工作流。使用代码方式。协调数据管道和任务(如ETL和ELT)。([源代码](https://github.com/kestra-io/kestra)) `Apache-2.0` `Docker`
- [Kibitzr](https://kibitzr.github.io) - 轻量级个人Web助手,具有强大的集成功能。([源代码](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - 关注作者并为您的所有数字阅读需求获取元数据。它使用Goodreads、Librarything的组合,以及可选的GoogleBooks作为作者信息和书籍信息的来源。`GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 可以驻留在您服务器上的个人助手。([源代码](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Matchering](https://github.com/sergree/matchering) - 自动化音乐母带处理(LANDR、eMastered和MajorDecibel的替代品)。`GPL-3.0` `Docker`
- [Mylar3](https://mylar.nerdfirehurricane.com/) - 自动漫画书(cbr/cbz)下载程序,用于配合NZB和torrent使用。([源代码](https://github.com/MylarComics/mylar3)) `GPL-3.0` `Python/Docker`
- [OliveTin](https://www.olivetin.app/) - 用于运行Linux shell命令的Web界面。([源代码](https://github.com/OliveTin/OliveTin)) `AGPL-3.0` `Go`
- [pyLoad](https://pyload.net/) - 轻量级、可定制且可远程管理的下载器,适用于rapidshare.com或uploaded.to等一键托管网站。([源代码](https://github.com/pyload/pyload)) `AGPL-3.0` `Python`
- [StackStorm](https://stackstorm.com) - StackStorm(也称为_Ops的IFTTT_)是事件驱动的自动化工具,用于自动修复、安全响应、故障排除、部署等。包括规则引擎、工作流、160个集成包(包含6000+操作)和ChatOps。([源代码](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [µTask](https://github.com/ovh/utask) - 自动化引擎,用于建模和执行在yaml中声明的业务流程。`BSD-3-Clause` `Go/Docker`


### 备份

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[备份](https://zh.wikipedia.org/wiki/备份)软件。

**请访问 [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups)**

_相关: [归档和数字保存(DP)](#归档和数字保存dp)_



### 博客平台

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[博客](https://zh.wikipedia.org/wiki/博客)是一个讨论或信息网站,由独立的、日记风格的文本条目(帖子)组成。

_相关: [静态站点生成器](#静态站点生成器), [内容管理系统(CMS)](#内容管理系统cms)_

_另见: [WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - 免费的开源项目,旨在开发高性能、功能丰富的博客托管软件。([源代码](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [bloglite](https://github.com/rikhuijzer/bloglite) - 微型博客工具,提供内置语法高亮、移动发布等功能(Twitter、Bluesky的替代品)。`MIT` `Docker`
- [Chyrp Lite](https://chyrplite.net) - 超级棒、超轻量级的博客引擎。([源代码](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dotclear](https://git.dotclear.org/dev/dotclear) - 掌控您的博客。`GPL-2.0` `PHP`
- [Ech0](https://ech0.app/) - 轻量级联合发布平台,专注于个人想法分享(中文文档)。([演示](https://memo.vaaat.com/), [源代码](https://github.com/lin-snow/Ech0)) `AGPL-3.0` `Docker/K8S`
- [FlatPress](https://flatpress.org/) - 轻量级、易于设置的平面文件博客引擎。([源代码](https://github.com/flatpressblog/flatpress)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - 仅仅是一个博客平台。([源代码](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - 私有博客系统,具有markdown编辑功能和内置RSS阅读器。([演示](https://havenweb.org/demo.html), [源代码](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [HTMLy](https://www.htmly.com/) - 无数据库PHP博客平台。这是一个平面文件CMS,允许您在几秒钟内创建快速、安全且强大的网站或博客。([演示](http://demo.htmly.com/), [源代码](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - 协作式社交发布平台。([源代码](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- [Mataroa](https://mataroa.blog/) - 面向极简主义者的裸博客平台。([源代码](https://github.com/mataroablog/mataroa)) `MIT` `Python`
- [PluXml](https://pluxml.org) - 基于XML的博客/CMS平台。([源代码](https://github.com/pluxml/PluXml)) `GPL-3.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity (s9y)是一个高度可扩展和可定制的PHP博客引擎,使用Smarty模板。([源代码](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`
- [WriteFreely](https://writefreely.org) - 用于启动极简主义、联合博客——或整个社区的写作软件。([源代码](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### 预订和调度

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

事件调度、预订和预约管理软件。

_相关: [投票和活动](#投票和活动), [群件](#群件)_

- [Alf.io](https://alf.io/) - 票务预订系统。([演示](https://demo.alf.io/authentication), [源代码](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.diy](https://cal.diy/) - 在线预约调度系统。([源代码](https://github.com/calcom/cal.diy)) `MIT` `Nodejs`
- [Easy!Appointments](https://easyappointments.org/) - 允许您的客户通过Web与您预约。([演示](https://demo.easyappointments.org/), [源代码](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- [Hi.Events](https://hi.events) - 活动管理和票务平台,适用于会议、音乐会等。提供可自定义的活动页面和可嵌入的票务小部件。([演示](https://demo.hi.events/event/1/dog-conf-2030), [源代码](https://github.com/HiEventsDev/hi.events)) `AGPL-3.0` `Docker`
- [LibreBooking](https://librebooking.readthedocs.io/) - 资源调度解决方案,为组织管理资源预订提供灵活、移动友好且可扩展的界面。([演示](https://librebooking-demo.fly.dev/), [源代码](https://github.com/LibreBooking/librebooking)) `GPL-3.0` `PHP/Docker`
- [QloApps](https://qloapps.com/) - 可定制且直观的基于Web的酒店预订系统和预订引擎。([演示](https://demo.qloapps.com/), [源代码](https://github.com/Qloapps/QloApps)) `OSL-3.0` `PHP/Nodejs`
- [Rallly](https://rallly.co) - 创建投票来选择日期和时间(Doodle的替代品)。([演示](https://app.rallly.co), [源代码](https://github.com/lukevella/rallly)) `AGPL-3.0` `Nodejs/Docker`
- [Seatsurfing](https://seatsurfing.app/) - 基于Web的应用程序,用于办公室的座位、办公桌和房间预订。([源代码](https://github.com/seatsurfing/seatsurfing)) `GPL-3.0` `Docker`


### 书签和链接分享

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

允许用户添加、注释、编辑和分享Web文档[书签](https://zh.wikipedia.org/wiki/书签)的软件。

_相关: [个人仪表板](#个人仪表板)_

- [Betula](https://joinbetula.org) - 单用户联合书签管理器,支持Fediverse和存档功能。([源代码](https://codeberg.org/bouncepaw/betula)) `AGPL-3.0` `Go`
- [Buku](https://github.com/jarun/Buku) - 强大的书签管理器和个人文本迷你网络。`GPL-3.0` `Python/deb`
- [Digibunch](https://ladigitale.dev/digibunch/#/) - 创建链接集合,与您的学习者或同事分享。([演示](https://ladigitale.dev/digibunch/#/b/5f67b12092b60), [源代码](https://codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- [Espial](https://github.com/jonschoning/espial) - 基于Web的书签服务器,支持多个用户帐户。`AGPL-3.0` `Haskell`
- [Faved](https://faved.to/) - 手工制作的书签管理器,结合了强大的标签功能、即时搜索和简洁无干扰的界面。为大容量收藏和高级工作流程构建,经过优化以提高效率和易用性。([演示](https://demo.faved.to/), [源代码](https://github.com/denho/faved)) `MIT` `Docker`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 托管您自己的Firefox帐户服务器。([源代码](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs/Java`
- [Karakeep](https://karakeep.app/) - 书签收集应用,为数据囤积者带来一点AI功能。([演示](https://try.karakeep.app/signin), [源代码](https://github.com/karakeep-app/karakeep)) `AGPL-3.0` `Docker`
- [LinkAce](https://www.linkace.org/) - 带有自动备份到Internet Archive、链接监视和完整REST API的书档。通过Docker安装,或作为简单的PHP应用程序安装。([演示](https://demo.linkace.org/guest/links), [源代码](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `Docker/PHP`
- [linkding](https://linkding.link/) - 极简书签管理,具有快速简洁的UI。通过Docker简单安装,可以在树莓派上运行。([演示](https://demo.linkding.link/login/), [源代码](https://github.com/sissbruecker/linkding)) `MIT` `Docker`
- [LinkWarden](https://linkwarden.app/) - 书签和存档管理器,用于存储您的有用链接。([源代码](https://github.com/linkwarden/linkwarden)) `MIT` `Docker/Nodejs`
- [NeonLink](https://github.com/AlexSciFier/neonlink) - 具有独特设计和Docker简单安装的书签服务。`MIT` `Docker`
- [Readeck](https://readeck.org/en/) - 保存您喜欢并希望永久保留的网页的可读内容。将其视为书签管理器和稍后阅读工具。([源代码](https://codeberg.org/readeck/readeck), [客户端](https://codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- [Servas](https://github.com/beromir/Servas) - 自托管书签管理工具。它允许使用标签、组和一个专门用于稍后访问的列表进行组织。支持多用户和双因素认证(2FA)。提供Firefox和Chrome的配套浏览器扩展。([客户端](https://github.com/beromir/Servas#browser-extensions)) `GPL-3.0` `Docker/Nodejs/PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - 个人化的、极简主义的、超快速的、无数据库的书签和链接分享平台。([演示](https://demo.shaarli.org)) `Zlib` `PHP/deb`
- [Shiori](https://github.com/go-shiori/shiori) - 用Go构建的简单书签管理器。`MIT` `Go/Docker`
- [Slash](https://github.com/yourselfhosted/slash) - 一个开源的、自托管的书签和链接分享平台。`GPL-3.0` `Docker`
- [SyncMarks](https://codeberg.org/Offerel/SyncMarks-Webapp) - 从Edge、Firefox和Chromium同步和管理浏览器书签。([客户端](https://codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### 通讯 - 自定义通信系统

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于提供对系统的远程访问以及在不同计算机或用户之间以文本、音频和/或视频格式交换文件和消息的[通信软件](https://zh.wikipedia.org/wiki/通信软件),使用其自己的自定义协议。

- [AnyCable](https://anycable.io/) - 通过WebSocket、服务器发送事件等实现可靠双向通信的实时服务器。([演示](https://demo.anycable.io), [源代码](https://github.com/anycable/anycable)) `MIT` `Go/Docker`
- [Apprise](https://github.com/caronc/apprise) - Apprise允许您向当今几乎所有最流行的通知服务发送通知,例如:Telegram、Discord、Slack、Amazon SNS、Gotify等。`MIT` `Python/Docker/deb`
- [Centrifugo](https://centrifugal.dev/) - 与语言无关的实时消息(Websocket或SockJS)服务器。([演示](https://github.com/centrifugal/centrifugo#demo), [源代码](https://github.com/centrifugal/centrifugo)) `MIT` `Go/Docker/K8S`
- [Chitchatter](https://chitchatter.im/) - 无服务器、去中心化和临时的点对点聊天应用。([源代码](https://github.com/jeremyckahn/chitchatter)) `GPL-2.0` `Nodejs`
- [Conduit](https://conduit.rs/) - 一个简单、快速且可靠的基于Matrix的聊天服务器。([源代码](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Continuwuity](https://continuwuity.org/) - 社区驱动的Matrix主服务器,是conduwuit的延续,专注于用户体验和新功能(Conduit的分支)。([源代码](https://forgejo.ellis.link/continuwuation/continuwuity)) `Apache-2.0` `Rust/Docker/K8S/deb`
- [Databag](https://github.com/balzack/databag) - 联合的、端到端加密的消息服务,适用于Web、iOS和Android,支持文本、照片、视频以及WebRTC视频和音频通话。`Apache-2.0` `Docker`
- [Element](https://element.io) - 功能齐全的Matrix客户端,适用于Web、iOS和Android。([源代码](https://github.com/element-hq/element-web)) `Apache-2.0` `Nodejs`
- [Fluxer](https://fluxer.app) - 为朋友、群组和社区构建的即时消息和VoIP平台(Discord的替代品)。([演示](https://fluxer.app), [源代码](https://github.com/fluxerapp/fluxer), [客户端](https://github.com/awesome-fluxer/awesome-fluxer)) `AGPL-3.0` `Docker`
- [GlobaLeaks](https://www.globaleaks.org/) - 吹哨软件,使任何人都能轻松设置和维护安全的报告平台。([演示](https://demo.globaleaks.org), [源代码](https://github.com/globaleaks/globaleaks-whistleblowing-software)) `AGPL-0` `Python/deb/Docker`
- [GNUnet](https://gnunet.org/) - 用于去中心化、点对点网络的软件框架。([源代码](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 具有Android和CLI客户端的通知服务器(PushBullet的替代品)。([源代码](https://github.com/gotify/server), [客户端](https://github.com/gotify/android)) `MIT` `Go/Docker`
- [Hyphanet](https://hyphanet.org/) - 匿名共享文件、浏览和发布_自由站点_(只能通过Hyphanet访问的网站)以及在论坛上聊天。([源代码](https://github.com/hyphanet/fred)) `GPL-2.0` `Java`
- [Jami](https://jami.net/) - 保护用户隐私和自由的通用通信平台。([源代码](https://git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- [Live Helper Chat](https://livehelperchat.com/) - 为您的网站提供实时支持聊天。([源代码](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延迟、高质量的语音/文字聊天软件。([源代码](https://github.com/mumble-voip/mumble), [客户端](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- [Notifo](https://github.com/notifo-io/notifo) - 多渠道通知服务器,支持电子邮件、移动推送、Web推送、SMS、消息传递和javascript插件。`MIT` `C#`
- [Novu](https://novu.co/) - 面向开发者的通知基础设施。([源代码](https://github.com/novuhq/novu/)) `MIT` `Docker/Nodejs`
- [ntfy](https://ntfy.sh/) - 使用HTTP PUT/POST向手机或桌面发送推送通知,具有Android应用、CLI和Web应用程序,类似于Pushover和Gotify。([演示](https://ntfy.sh/app), [源代码](https://github.com/binwiederhier/ntfy), [客户端](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- [One Time Secret](https://docs.onetimesecret.com) - 使用自毁链接安全地分享敏感信息,链接只能查看一次。([演示](https://onetimesecret.com), [源代码](https://github.com/onetimesecret/onetimesecret)) `MIT` `Docker/Ruby/Nodejs`
- [OpenWA](https://www.open-wa.org) `⚠` - WhatsApp API网关,将消息作为REST端点暴露,具有Web仪表板、多帐户会话和webhook事件(WhatsApp Business API提供商的替代品)。([源代码](https://github.com/rmyndharis/OpenWA), [客户端](https://github.com/rmyndharis/OpenWA-plugins)) `MIT` `Docker`
- [OTS](https://ots.fyi/) - 一次性秘密分享平台,在浏览器中使用对称256位AES加密。([源代码](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [PushBits](https://github.com/pushbits/server) - 通过Matrix中继推送通知的通知服务器,类似于PushBullet和Gotify。`ISC` `Go`
- [RetroShare](https://retroshare.cc) - 安全且去中心化的通信系统。提供去中心化聊天、论坛、消息传递、文件传输。([源代码](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Rocket.Chat](https://rocket.chat/) - 将数据保护放在首位的通信平台(Gitter.im和Slack的替代品)。([源代码](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs/Docker/K8S`
- [SAMA](https://samacloud.io) - 下一代自托管聊天服务器和客户端。([演示](https://app.samacloud.io/demo), [源代码](https://github.com/SAMA-Communications/sama-server), [客户端](https://github.com/SAMA-Communications/sama-client)) `GPL-3.0` `Nodejs/Docker`
- [Screego](https://screego.net) - Screego是一个简单的工具,可以通过Web浏览器快速将您的屏幕共享给一个或多个人。([演示](https://app.screego.net/), [源代码](https://github.com/screego/server)) `GPL-3.0` `Docker/Go`
- [Shhh](https://github.com/smallwat3r/shhh) - 将秘密信息从电子邮件或聊天日志中移出,使用带有密码短语和过期日期的安全链接来分享它们。`MIT` `Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密和安全的应用程序平台——现在具有双棘轮端到端加密。`AGPL-3.0` `Haskell`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2是一个开源的即时消息传输工具。它允许用户即使使用不同的IM网络也能一起聊天。([源代码](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Stoat](https://stoat.chat/) - Stoat是一个以用户为先的聊天平台,使用现代Web技术构建。([源代码](https://github.com/stoatchat/self-hosted)) `AGPL-3.0/MIT` `Rust`
- [Synapse](https://element-hq.github.io/synapse/latest/index.html) - [Matrix](https://matrix.org/)的服务器,这是一个去中心化持久通信的开放标准。([源代码](https://github.com/element-hq/synapse)) `Apache-2.0` `Python/deb`
- [Tiledesk](https://tiledesk.com) - 全方位客户参与平台,从潜在客户生成到售后,从WhatsApp到您的网站。具有全渠道实时代理和AI驱动的聊天机器人(Intercom、Zendesk、Tawk.to和Tidio的替代品)。([源代码](https://github.com/Tiledesk/tiledesk)) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - 即时消息平台。后端使用Go。客户端:Swift iOS、Java Android、JS Webapp、可编写脚本的命令行;聊天机器人。([演示](https://sandbox.tinode.co/), [源代码](https://github.com/tinode/chat), [客户端](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 分布式、安全的消息传递程序,具有音频和视频聊天功能。([源代码](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Tuwunel](https://tuwunel.chat) - 高性能且功能丰富的Matrix聊天服务器,是conduwuit的继任者(Conduit的分支)。([演示](https://try.tuwunel.chat/), [源代码](https://github.com/matrix-construct/tuwunel)) `Apache-2.0` `deb/Docker/Nix/Rust`
- [Typebot](https://typebot.io) - 对话式应用程序构建器(Typeform和Landbot的替代品)。([源代码](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir) - 用于在模式、绘图和笔记上进行实时协作的Web白板。([演示](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [Zulip](https://zulip.org) - Zulip是一个强大的开源群聊应用程序。([源代码](https://github.com/zulip/zulip)) `Apache-2.0` `Python`


### 通讯 - 电子邮件 - 完整解决方案

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[电子邮件](https://zh.wikipedia.org/wiki/电子邮件)服务器的简单部署,例如针对缺乏经验或不耐心的管理员。

- [AnonAddy](https://anonaddy.com) - 用于创建别名的电子邮件转发服务。([源代码](https://github.com/anonaddy/anonaddy)) `MIT` `PHP/Docker`
- [b1gMail](https://www.b1gmail.eu) - 可在任何具有PHP和MariaDB的网络空间上运行的完整电子邮件解决方案。它支持POP3 catchall邮箱,如果您运行自己的服务器,还可以与Postfix或b1gMailServer集成。([源代码](https://codeberg.org/b1gMail/b1gMail), [客户端](https://www.b1gmail.eu/en/start/addon-b1gmailserver/)) `GPL-2.0` `PHP`
- [DebOps](https://docs.debops.org/) - 您的基于Debian的数据中心即服务。一组可用于管理Debian或Ubuntu主机的通用Ansible角色。([源代码](https://github.com/debops/debops)) `GPL-3.0` `Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 生产就绪的全栈但简单的邮件服务器(SMTP、IMAP、LDAP、反垃圾邮件、反病毒等)在容器内运行。仅使用配置文件,没有SQL数据库。([源代码](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [Inboxen](https://inboxen.org) - 让您拥有无限数量的唯一收件箱。([源代码](https://codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于Postfix和Dovecot的功能齐全的邮件服务器解决方案。([源代码](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy Mail Server](https://maddy.email/) - 一体化邮件服务器,实现SMTP(MTA和MX)和IMAP。用单个守护进程替换Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。([源代码](https://github.com/foxcpp/maddy)) `GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 用一条命令将任何Ubuntu服务器变成功能齐全的邮件服务器。([源代码](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于Dovecot、Postfix和其他开源软件的邮件服务器套件,提供用于管理的现代Web UI。([源代码](https://github.com/mailcow/mailcow-dockerized)) `GPL-3.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - 简单但功能齐全的邮件服务器,以一组Docker镜像的形式提供。([源代码](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - 邮件托管和管理平台,包括现代简化的Web用户界面。([源代码](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Mox](https://www.xmox.nl/) - 完整的电子邮件解决方案,具有IMAP4、SMTP、SPF、DKIM、DMARC、MTA-STS、DANE和DNSSEC,基于声誉和内容的垃圾邮件过滤,国际化(IDNA),通过ACME和Let's Encrypt实现自动TLS,帐户自动配置和Webmail。([源代码](https://github.com/mjl-/mox)) `MIT` `Go`
- [Postal](https://docs.postalserver.io/) - 完整且功能齐全的邮件服务器,供网站和Web服务器使用。([源代码](https://github.com/postalserver/postal)) `MIT` `Docker/Ruby`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用Nix生态系统的完整邮件服务器解决方案。`GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 开源电子邮件别名解决方案,用于保护您的电子邮件地址。附带浏览器扩展和移动应用程序。([源代码](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [Stalwart Mail Server](https://stalw.art) - 一体化邮件服务器,支持JMAP、IMAP4和SMTP以及广泛的现代功能。([源代码](https://github.com/stalwartlabs/stalwart)) `AGPL-3.0` `Rust/Docker`
- [wildduck](https://wildduck.email/) - 可扩展的无单点故障(IMAP/POP3)邮件服务器。([源代码](https://github.com/zone-eu/wildduck)) `EUPL-1.2` `Nodejs/Docker`


### 通讯 - 电子邮件 - 邮件投递代理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[邮件投递代理](https://zh.wikipedia.org/wiki/邮件投递代理)(MDA) - [IMAP](https://zh.wikipedia.org/wiki/互联网消息访问协议)/[POP3](https://zh.wikipedia.org/wiki/邮局协议)服务器软件。

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件(IMAP/POP3)、联系人和日历服务器。([源代码](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [DavMail](https://davmail.sourceforge.net/) `⚠` - POP/IMAP/SMTP/Caldav/Carddav/LDAP Exchange网关,允许用户使用任何邮件/日历客户端与Exchange服务器通信,即使从互联网或防火墙后面通过Outlook Web Access也是如此。([源代码](https://github.com/mguessan/davmail)) `GPL-2.0` `Java`
- [Dovecot](https://www.dovecot.org/) - 主要考虑安全性的IMAP和POP3服务器。([源代码](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C/deb`


### 通讯 - 电子邮件 - 邮件传输代理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[邮件传输代理](https://zh.wikipedia.org/wiki/邮件传输代理)(MTA) - [SMTP](https://zh.wikipedia.org/wiki/简单邮件传输协议)服务器。

- [chasquid](https://blitiri.com.ar/p/chasquid/) - 专注于简单性、安全性和易用性的SMTP(电子邮件)服务器。([源代码](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业邮件/群件服务器,提供ESMTP、IMAP、POP3、Webmail、邮件列表、基本的基于Web的日历和调度服务。([源代码](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- [DragonFly](https://github.com/corecode/dma) - 适用于家庭和办公室使用的小型MTA。可在Linux和FreeBSD上工作。`BSD-3-Clause` `C`
- [EmailRelay](https://emailrelay.sourceforge.net/) - 适用于Windows和Linux的小型且易于配置的SMTP和POP3服务器。([源代码](https://sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- [Exim](https://www.exim.org/) - 在剑桥大学开发的邮件传输代理(MTA)。([源代码](https://git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- [Haraka](https://haraka.github.io/) - 快速、高度可扩展且事件驱动的SMTP服务器。([源代码](https://github.com/haraka/Haraka)) `MIT` `Nodejs`
- [OpenSMTPD](https://opensmtpd.org/) - 来自OpenBSD项目的安全SMTP服务器实现。([源代码](https://github.com/OpenSMTPD/OpenSMTPD/)) `ISC` `C/deb`
- [Postfix](http://www.postfix.org/) - 快速、易于管理且安全的Sendmail替代品。`IPL-1.0` `C/deb`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 邮件传输代理(MTA)。`Sendmail` `C/deb`


### 通讯 - 电子邮件 - 邮件列表和新闻通讯

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[邮件列表](https://zh.wikipedia.org/wiki/邮件列表)服务器和群发邮件软件 - 一条消息发给多个收件人。

_相关: [客户关系管理(CRM)](#客户关系管理crm)_

- [HyperKitty](https://wiki.list.org/HyperKitty) - 访问GNU Mailman v3存档。([演示](https://lists.mailman3.org/), [源代码](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Keila](https://www.keila.io) - 可靠且易于使用的新闻通讯工具(Mailchimp和Sendinblue的替代品)。([演示](https://app.keila.io), [源代码](https://github.com/pentacent/keila)) `AGPL-3.0` `Docker`
- [Listmonk](https://listmonk.app/) - 高性能、自托管的新闻通讯和邮件列表管理器,具有现代仪表板。([演示](https://demo.listmonk.app/), [源代码](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go/Docker`
- [Mailman](https://www.list.org/) - 管理电子邮件讨论和电子新闻通讯列表。([源代码](https://gitlab.com/mailman/)) `GPL-3.0` `Python`
- [Mautic](https://www.mautic.org/) - 营销自动化软件(电子邮件、社交等)。([源代码](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [mlmmj](https://mlmmj.org/) - 让邮件列表管理变得愉快。([源代码](https://codeberg.org/mlmmj/mlmmj)) `MIT` `C`
- [phpList](https://www.phplist.org) - 新闻通讯和电子邮件营销,具有高级订阅者、退回和插件管理功能。([源代码](https://github.com/phpList/phplist3)) `AGPL-3.0` `PHP`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 访问GNU Mailman的Web用户界面。([源代码](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 支持GPG并具有转发功能的邮件列表管理器。([源代码](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.community/) - 邮件列表管理器。([源代码](https://github.com/sympa-community/sympa)) `GPL-2.0` `Perl`


### 通讯 - 电子邮件 - Webmail客户端

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[Webmail](https://zh.wikipedia.org/wiki/Webmail)客户端。

- [Cypht](https://cypht.org) - 您的电子邮件帐户的RSS阅读器。([源代码](https://github.com/cypht-org/cypht)) `LGPL-2.1` `PHP`
- [Roundcube](https://roundcube.net) - 基于浏览器的IMAP客户端,具有类似应用程序的用户界面。([源代码](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP/deb`
- [SnappyMail](https://github.com/the-djmaze/snappymail) - 简单、现代、轻量级且快速的基于Web的电子邮件客户端(RainLoop的分支)。`AGPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一个基于浏览器的IMAP客户端。([源代码](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### 通讯 - IRC

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[IRC](https://zh.wikipedia.org/wiki/互联网中继聊天)通信软件。

- [Ergo](https://ergo.chat/) - 用Go编写的现代IRCv3服务器,结合了ircd、服务框架和bouncer的功能。([源代码](https://github.com/ergochat/ergo)) `MIT` `Go/Docker`
- [Glowing Bear](https://github.com/glowing-bear/glowing-bear) - WeeChat的Web前端。([演示](https://www.glowing-bear.org)) `GPL-3.0` `Nodejs`
- [InspIRCd](https://www.inspircd.org/) - 用C++编写的模块化IRC服务器,适用于Linux、BSD、Windows和macOS。([源代码](https://github.com/inspircd/inspircd)) `GPL-2.0` `C++/Docker`
- [Kiwi IRC](https://kiwiirc.com/) - 具有主题支持的响应式Web IRC客户端。([演示](https://kiwiirc.com/nextclient/), [源代码](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [ngircd](https://ngircd.barton.de/) - 适用于小型或私有网络的可移植轻量级Internet Relay Chat服务器。([源代码](https://github.com/ngircd/ngircd)) `GPL-2.0` `C/deb`
- [Quassel IRC](https://quassel-irc.org/) - 分布式IRC客户端,意味着一个(或多个)客户端可以连接到中央核心并从中断开连接。([源代码](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - 没有网络分裂的IRC。基于RobustSession协议的分布式IRC服务器。([源代码](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.chat/) - 自托管Web IRC客户端。([演示](https://demo.thelounge.chat/), [源代码](https://github.com/thelounge/thelounge)) `MIT` `Nodejs/Docker`
- [UnrealIRCd](https://www.unrealircd.org/) - 用C编写的模块化、高级且高度可配置的IRC服务器,适用于Linux、BSD、Windows和macOS。([源代码](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [Weechat](https://weechat.org/) - 快速、轻量且可扩展的聊天客户端。([源代码](https://github.com/weechat/weechat)) `GPL-3.0` `C/Docker/deb`
- [ZNC](https://wiki.znc.in/ZNC) - 高级IRC bouncer。([源代码](https://github.com/znc/znc)) `Apache-2.0` `C++/deb`


### 通讯 - SIP

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[SIP](https://zh.wikipedia.org/wiki/会话发起协议)/[IPBX](https://zh.wikipedia.org/wiki/IP_PBX)电话软件。

- [Asterisk](https://www.asterisk.org/) - 易于使用但先进的IP PBX系统、VoIP网关和会议服务器。([源代码](https://github.com/asterisk/asterisk)) `GPL-2.0` `C/deb`
- [Flexisip](https://www.linphone.org/en/flexisip-sip-server/) - 完整、模块化且可扩展的SIP服务器,包括推送网关,用于在需要推送通知才能接收信息的移动设备平台上传送SIP来电或短信。([源代码](https://github.com/BelledonneCommunications/flexisip)) `AGPL-3.0` `C/Docker`
- [Freepbx](https://www.freepbx.org) - 基于Web的开源GUI,用于控制和管理Asterisk。([源代码](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可扩展的开源跨平台电话平台。([源代码](https://github.com/signalwire/freeswitch)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 用于名为FreeSWITCH的多平台语音交换机的Web界面。([源代码](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模块化SIP服务器(注册器/代理/路由器等)。([源代码](https://github.com/kamailio/kamailio)) `GPL-2.0` `C/deb`
- [openSIPS](https://opensips.org/) - 用于语音、视频、IM、在线状态和任何其他SIP扩展的SIP代理/服务器。([源代码](https://github.com/OpenSIPS/opensips)) `GPL-2.0` `C`
- [Routr](https://routr.io) - 轻量级SIP代理、位置服务器和注册器,用于可靠且可扩展的SIP基础设施。([源代码](https://github.com/fonoster/routr)) `MIT` `Docker/K8S`
- [SIP3](https://sip3.io/) - VoIP故障排除和监控平台。([演示](https://demo.sip3.io), [源代码](https://github.com/sip3io/)) `Apache-2.0` `Java`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - VoIP呼叫故障排除和监控。([源代码](https://github.com/sipcapture/homer)) `AGPL-3.0` `Nodejs/Go/Docker`
- [Wazo](https://wazo-platform.org/) - 基于Asterisk构建的功能齐全的IPBX解决方案,具有集成的Web管理界面和RESTful API。([源代码](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 具有集成计费和路由引擎以及REST API的Transit class4软交换机(SBC)。([演示](https://demo.yeti-switch.org/), [源代码](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 通讯 - 社交网络和论坛

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[社交网络](https://zh.wikipedia.org/wiki/社交网络服务)和[论坛](https://zh.wikipedia.org/wiki/网络论坛)软件。

- [Akkoma](https://akkoma.social/) - 具有Mastodon、GNU social和ActivityPub兼容性的联合微博客服务器。([源代码](https://akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- [Answer](https://answer.apache.org) - 基于知识的社区软件。您可以使用它快速构建Q&A社区,用于产品技术支持、客户支持、用户沟通等。([源代码](https://github.com/apache/answer)) `Apache-2.0` `Docker/Go`
- [Artalk](https://artalk.js.org/) - 用Golang构建的评论系统,为网站添加评论提供轻量级且高度可定制的解决方案。([源代码](https://github.com/ArtalkJS/Artalk)) `MIT` `Go/Docker`
- [AsmBB](https://board.asm32.info) - 用ASM编写的快速、基于SQLite的论坛引擎。([源代码](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [BuddyPress](https://buddypress.org/about/) - 强大的插件,通过用户个人资料、活动流、用户组等社交网络功能,使您的WordPress.org网站超越博客。([源代码](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Coral](https://coralproject.net/) - 来自Vox Media的更好的评论体验。([源代码](https://github.com/coralproject/talk)) `Apache-2.0` `Docker/Nodejs`
- [diaspora*](https://diasporafoundation.org/) - 分布式社交网络服务器。([源代码](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基于Ruby和JS的高级论坛/社区解决方案。([演示](https://try.discourse.org/), [源代码](https://github.com/discourse/discourse)) `GPL-2.0` `Docker`
- [Elgg](https://elgg.org/) - 强大的开源社交网络引擎。([源代码](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Enigma 1/2 BBS](https://nuskooler.github.io/enigma-bbs/) - Enigma 1/2是一个现代的、多平台BBS引擎,具有无限"呼叫者"支持和传统DOS门游戏支持。([源代码](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Shell/Docker/Nodejs`
- [Flarum](https://flarum.org) - 令人愉悦的简单论坛。Flarum是下一代论坛软件,让在线讨论再次变得有趣。([源代码](https://github.com/flarum/flarum)) `MIT` `PHP`
- [Friendica](https://friendi.ca/) - 社交通信服务器。([源代码](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [GoToSocial](https://docs.gotosocial.org/en/latest/) - 实现Mastodon客户端API的ActivityPub联合社交网络服务器。([源代码](https://codeberg.org/superseriousbusiness/gotosocial)) `AGPL-3.0` `Docker/Go`
- [Habitat](https://gethabitat.org/) - 本地社区平台。([源代码](https://github.com/carlnewton/habitat)) `AGPL-3.0` `Docker`
- [Hatsu](https://hatsu.cli.rs/) - 代表您的静态站点与Fediverse交互的桥梁。([源代码](https://github.com/importantimport/hatsu)) `AGPL-3.0` `Docker/Rust`
- [Hubzilla](https://hubzilla.org) - 去中心化身份、隐私、发布、共享、云存储和通信/社交平台。([源代码](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 私有社交网络的灵活工具包。([源代码](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Iceshrimp.NET](https://iceshrimp.net) - 通过ActivityPub通信的联合微博客服务器。([源代码](https://iceshrimp.dev/iceshrimp/iceshrimp.net)) `EUPL-1.2` `.NET/C#/Docker`
- [Isso](https://isso-comments.de/) - 用Python和Javascript编写的轻量级评论服务器。旨在成为Disqus的替代品。([源代码](https://github.com/isso-comments/isso)) `MIT` `Python/Docker`
- [Lemmy](https://join-lemmy.org/) - Fediverse的链接聚合器(Reddit的替代品)。([源代码](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Docker/Rust`
- [Loomio](https://www.loomio.org/) - 协作决策工具,让任何人都能轻松参与影响他们的决策。([源代码](https://github.com/loomio/loomio)) `AGPL-3.0` `Docker`
- [Mastodon](https://joinmastodon.org/) - 联合微博客服务器。([源代码](https://github.com/mastodon/mastodon), [客户端](https://github.com/hyperupcall/awesome-mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - 功能齐全的现代论坛应用程序,快速、可扩展且响应迅速。([源代码](https://github.com/rafalp/Misago)) `GPL-2.0` `Docker`
- [Misskey](https://misskey.io/) - 面向Fediverse的去中心化的类似应用程序的微博客服务器/SNS,像GNU social和Mastodon一样使用ActivityPub协议。([源代码](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs/Docker`
- [Movim](https://movim.eu/) - 基于XMPP的现代联合社交网络,具有全功能的群聊、订阅和微博客功能。([源代码](https://github.com/movim/movim)) `AGPL-3.0` `PHP/Docker`
- [MyBB](https://mybb.com/) - 免费、可扩展的论坛软件包。([源代码](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [NodeBB](https://nodebb.org/) - 为现代Web构建的论坛软件。([演示](https://try.nodebb.org/), [源代码](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs/Docker`
- [OSSN](https://www.opensource-socialnetwork.org/) - 社交网络软件,允许您创建社交网络网站,帮助您的成员与具有相似专业或个人兴趣的人建立社交关系。([源代码](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `CAL-1.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 平面论坛公告板软件解决方案,可用于与一群人保持联系,或为您的整个网站提供动力。([源代码](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PieFed](https://join.piefed.social) - Fediverse的链接聚合器/reddit克隆(Reddit的替代品)。([演示](https://piefed.social), [源代码](https://codeberg.org/rimu/pyfedi)) `AGPL-3.0` `Python/Docker`
- [PixelFed](https://pixelfed.social) - 合乎道德的照片分享平台,由ActivityPub联合驱动(Instagram的替代品)。([源代码](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 联合微博客服务器,兼容Mastodon、GNU social和ActivityPub。([源代码](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [qpixel](https://codidact.com/) - 基于Q&A的社区知识共享软件。([源代码](https://github.com/codidact/qpixel)) `AGPL-3.0` `Ruby`
- [Redlib](https://github.com/redlib-org/redlib) `⚠` - Reddit的替代私有前端,起源于Libreddit。`AGPL-3.0` `Rust`
- [remark42](https://remark42.com/) - 轻量级且简单的评论引擎,不会监视用户。可以嵌入到博客、文章或读者添加评论的任何其他地方。([演示](https://remark42.com/demo/), [源代码](https://github.com/umputun/remark42)) `MIT` `Docker/Go`
- [Scoold](https://scoold.com) - JAR中的Stack Overflow。企业就绪的Q&A平台,具有全文搜索、SAML、LDAP集成和社交登录支持。([演示](https://live.scoold.com), [源代码](https://github.com/Erudika/scoold)) `Apache-2.0` `Java/Docker/K8S`
- [Simple Machines Forum](https://www.simplemachines.org/) - 允许您在几分钟内建立自己在线社区的免费专业级软件包。([源代码](https://github.com/SimpleMachines/SMF)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 联合和去中心化的配置文件构建器和社交网络引擎。([演示](https://socialhome.network/), [源代码](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Docker/Python`
- [Talkyard](https://www.talkyard.io/) - 创建一个社区,您的用户可以在其中建议想法并获得问题答案。并进行友好的开放式讨论和聊天(Slack/StackOverflow/Discourse/Reddit/Disqus混合体)。([演示](https://www.talkyard.io/forum/latest), [源代码](https://github.com/debiki/talkyard)) `AGPL-3.0` `Docker/Scala`
- [yarn.social](https://yarn.social) - 自托管、类似Twitter™的去中心化微型博客平台。无广告、无跟踪、您的内容、您的数据。([源代码](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`


### 通讯 - 视频会议

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[视频/Web会议](https://zh.wikipedia.org/wiki/网络会议)工具和软件。

_相关: [会议管理](#会议管理)_

- [BigBlueButton](https://bigbluebutton.org/) - 支持音频、视频、幻灯片(带白板控件)、聊天和屏幕的实时共享。教师可以使用投票、表情符号和分组讨论室与远程学生互动。([源代码](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Galene](https://galene.org/) - 易于部署且需要适度服务器资源的视频会议服务器。([源代码](https://github.com/jech/galene)) `MIT` `Go`
- [Janus](https://janus.conf.meetecho.com/) - 通用、轻量级、极简主义的WebRTC服务器。([演示](https://janus.conf.meetecho.com/demos/), [源代码](https://github.com/meetecho/janus-gateway)) `GPL-3.0` `C`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - 使用Jitsi Videobridge提供高质量、可扩展视频会议的WebRTC应用程序。([演示](https://meet.jit.si), [源代码](https://github.com/jitsi/jitsi-meet)) `Apache-2.0` `Nodejs/Docker/deb`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 与Web兼容的选择性转发单元(SFU),允许多用户视频通信。([源代码](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java/deb`
- [MiroTalk C2C](https://c2c.mirotalk.com) - 实时摄像头到摄像头视频通话和屏幕共享,端到端加密,可通过简单的iframe嵌入任何网站。([源代码](https://github.com/miroslavpejic85/mirotalkc2c)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk P2P](https://p2p.mirotalk.com) - 简单、安全、快速的实时视频会议,最高支持4k和60fps,兼容所有浏览器和平台。([演示](https://p2p.mirotalk.com/newcall), [源代码](https://github.com/miroslavpejic85/mirotalk)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk SFU](https://sfu.mirotalk.com) - 简单、安全、可扩展的实时视频会议,最高支持4k,兼容所有浏览器和平台。([演示](https://sfu.mirotalk.com/newroom), [源代码](https://github.com/miroslavpejic85/mirotalksfu)) `AGPL-3.0` `Nodejs/Docker`
- [plugNmeet](https://www.plugnmeet.org/) - 可扩展且高性能的Web会议系统。([演示](https://demo.plugnmeet.com/login.html), [源代码](https://github.com/mynaparrot/plugNmeet-server)) `MIT` `Docker/Go`


### 通讯 - XMPP - 服务器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[可扩展消息和存在协议](https://zh.wikipedia.org/wiki/XMPP)服务器。

- [ejabberd](https://www.ejabberd.im/) - XMPP即时消息服务器。([源代码](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang/Docker`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 专注于性能和可扩展性的移动消息平台。([源代码](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang/Docker/K8S`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 实时协作(RTC)服务器。([源代码](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能丰富且易于配置的XMPP服务器。([源代码](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 一体化的Docker化简易XMPP解决方案,包括Web管理和客户端。([源代码](https://github.com/snikket-im/snikket-server), [客户端](https://snikket.org/app/)) `Apache-2.0` `Docker`
- [Tigase](https://tigase.net/xmpp-server) - 用Java实现的XMPP服务器。([源代码](https://github.com/tigase/tigase-server)) `GPL-3.0` `Java`


### 通讯 - XMPP - Web客户端

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[可扩展消息和存在协议](https://zh.wikipedia.org/wiki/XMPP)Web客户端/界面。

- [Converse.js](https://conversejs.org/) - 浏览器中的XMPP聊天客户端。([源代码](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [Libervia](https://repos.goffi.org/libervia-web) - 来自Salut à Toi的Web前端。`AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由和去中心化的通信工具。([源代码](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 社区支持农业(CSA)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

社区支持农业和食品合作社的管理和行政工具。

_相关: [电子商务](#电子商务)_

- [ACP Admin](https://acp-admin.ch/) - CSA行政管理。管理成员、订阅、交付、取货地点、成员参与、发票和电子邮件(法语文档)。([源代码](https://github.com/csa-admin-org/csa-admin)) `MIT` `Ruby`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 用户友好的食品合作社软件。([源代码](https://github.com/foodcoopshop/foodcoopshop)) `AGPL-3.0` `PHP/Docker`
- [Foodsoft](https://foodcoops.net/) - 管理非营利性食品合作社(产品目录、订购、会计、作业调度)。([源代码](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Docker/Ruby`
- [Hive-Pal](https://hivepal.app) - 移动优先的养蜂管理应用程序,用于追踪蜂巢、检查、蜂王记录和设备,具有为现场使用优化的简化数据输入。([演示](https://hivepal.app), [源代码](https://github.com/martinhrvn/hive-pal)) `MIT` `Nodejs/Docker`
- [juntagrico](https://juntagrico.org/) - 社区花园和蔬菜合作社的管理平台。([源代码](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Open Food Network](https://www.openfoodnetwork.org/) - 本地食品的在线市场。它使独立的在线食品商店网络能够将农民和食品中心与个人和本地企业联系起来。([源代码](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - 社区支持农业团体的管理平台。([源代码](https://github.com/OpenOlitor/openolitor-server)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 基于众包数据绘制社区支持农业地图的Web应用程序。([演示](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### 会议管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于提交[摘要](https://zh.wikipedia.org/wiki/摘要管理)和准备/管理学术会议的软件。

_相关: [通讯 - 视频会议](#通讯---视频会议)_

- [indico](https://getindico.io/) - 功能丰富的活动管理系统,由CERN制作,这里是Web的诞生地。([演示](https://sandbox.getindico.io/), [源代码](https://github.com/indico/indico)) `MIT` `Python`
- [motion.tools (Antragsgrün)](https://motion.tools/) - 管理(政治)会议的动议和修正案。([演示](https://sandbox.motion.tools/createsite), [源代码](https://github.com/CatoTH/antragsgruen)) `AGPL-3.0` `PHP/Docker`
- [OpenSlides](https://openslides.com/) - 用于管理和投影会议议程、动议和选举的演示和会议系统。([演示](https://demo.openslides.org/login), [源代码](https://github.com/OpenSlides/OpenSlides)) `MIT` `Docker`
- [osem](https://osem.io/) - 专为自由软件会议量身定制的活动管理。([源代码](https://github.com/openSUSE/osem)) `MIT` `Ruby/Docker`
- [pretalx](https://pretalx.org) - 基于Web的活动管理,包括运行论文征集、审查提交和安排演讲。支持各种相关工具的导出和导入。([源代码](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 内容管理系统(CMS)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[内容管理系统](https://zh.wikipedia.org/wiki/内容管理系统)提供了一种实用的方式来设置具有许多功能的网站,使用第三方插件、主题和功能,这些都可以轻松添加和自定义。

_相关: [博客平台](#博客平台), [静态站点生成器](#静态站点生成器), [照片画廊](#照片画廊)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - 处理任何类型内容的开源企业内容管理软件,允许用户轻松共享和协作处理内容。([源代码](https://github.com/Alfresco/alfresco-community-repo)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.com/) - 专注于可扩展上下文编辑工具的CMS。([演示](https://demo.apostrophecms.com/), [源代码](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [Automad](https://automad.org/) - 平面文件内容管理系统和模板引擎。([演示](https://try.automad.org/), [源代码](https://github.com/marcantondahmen/automad)) `MIT` `PHP/Docker`
- [Backdrop CMS](https://backdropcms.org/) - 面向中小型企业和非营利组织的综合CMS。([源代码](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - 在几秒钟内构建网站或博客。Bludit使用平面文件(JSON格式的文本文件)来存储帖子和页面。([源代码](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Bolt CMS](https://boltcms.io/) - 内容管理工具,力求尽可能简单直接。([源代码](https://github.com/bolt/core)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 更快更轻松地管理网站内容,可从小型企业扩展到大公司。([源代码](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- [Cockpit](https://getcockpit.com) - 简单的内容平台,用于管理任何结构化内容。([源代码](https://github.com/Cockpit-HQ/Cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 开源内容管理系统。([源代码](https://github.com/concretecms/concretecms)) `MIT` `PHP`
- [Contao](https://contao.org/) - 强大的CMS,允许您创建专业的网站和可扩展的Web应用程序。([演示](https://demo.contao.org/contao), [源代码](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 面向设计者的CMS。([源代码](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Drupal](https://www.drupal.org/) - 高级开源内容管理平台。([源代码](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 研究实验室的在线实验笔记本。存储实验,使用数据库查找试剂或方案,使用可信时间戳对实验进行合法时间戳,导出为pdf或zip存档,与协作者共享...。([演示](https://demo.elabftw.net), [源代码](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 使用JSON模式为数据库驱动的网站提供动力的内容管理系统。提供权限管理和自动REST API。`MIT` `Nodejs`
- [Joomla!](https://www.joomla.org/) - 高级内容管理系统(CMS)。([源代码](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS和Web应用程序平台。([源代码](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [Localess](https://localess.org/home) `⚠` - 强大的翻译管理和内容管理系统。管理和翻译您的网站或应用程序内容到多种语言,使用AI更快地进行翻译。([源代码](https://github.com/Lessify/localess)) `MIT` `Docker`
- [MODX](https://modx.com/) - 高级内容管理和发布平台。当前版本称为'Revolution'。([源代码](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos或TYPO3 Neos(对于版本1)是一个现代化的开源CMS。([源代码](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - 社会和团结经济网络平台,在同一系统中具有博客、电子作品集、CMS、RSS、主题讨论、活动议程和集体智能,用于团结经济。`AGPL-3.0` `Ruby`
- [Omeka](https://omeka.org) - 创建复杂的叙事并分享丰富的集合,在您的服务器上遵循都柏林核心标准的Omeka,专为学者、博物馆、图书馆、档案馆和爱好者设计。([演示](https://omeka.org/classic/showcase/), [源代码](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Payload CMS](https://payloadcms.com/) - 以开发者优先的无头CMS和应用程序框架。([源代码](https://github.com/payloadcms/payload)) `MIT` `Nodejs`
- [Pimcore](http://www.pimcore.com/) - 多渠道体验和参与管理平台。([源代码](https://github.com/pimcore/pimcore)) `GPL-3.0` `PHP/Docker`
- [Plone](https://plone.org/) - 用于创建、编辑和管理数字内容(如网站、内网和自定义解决方案)的CMS系统。([源代码](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- [Publify](https://publify.github.io/) - 简单但功能齐全的Web发布软件。([源代码](https://github.com/publify/publify)) `MIT` `Ruby`
- [Pushword](https://pushword.piedweb.com) - 基于Symfony构建的内容管理系统,其中页面是Markdown,主题是Twig,可选基于Git的平面文件存储。([源代码](https://github.com/Pushword/Pushword), [客户端](https://pushword.piedweb.com/extensions)) `MIT` `PHP`
- [REDAXO](https://www.redaxo.org) - 简单、灵活且有用的内容管理系统(德语文档)。([源代码](https://github.com/redaxo/core)) `MIT` `PHP/Docker`
- [SilverStripe](https://www.silverstripe.org) - 易于使用的CMS,底层具有强大的MVC框架。([演示](https://demo.silverstripe.org/), [源代码](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 面向互联网的发布系统,旨在实现协作工作、多语言环境以及Web作者的易用性。([源代码](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 无头CMS,基于MongoDB、CQRS和事件溯源。([演示](https://cloud.squidex.io), [源代码](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 无头CMS,让开发者能够快速构建内容API,同时为内容创建者提供友好的编辑界面。([源代码](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Superdesk](https://superdesk.org/) `⚠` - 端到端的新闻创建、生产、策划、分发和发布平台。([源代码](https://github.com/superdesk/superdesk)) `AGPL-3.0` `Docker/Python/PHP`
- [Textpattern](https://textpattern.com/) - 灵活、优雅且易于使用的CMS。([演示](https://textpattern.co/demo), [源代码](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 对作者友好的平面文件CMS,具有基于vue.js的可视化markdown编辑器。([源代码](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 功能强大且高级的CMS,拥有庞大的社区。([源代码](https://github.com/TYPO3/typo3)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的CMS。免费且开源,拥有令人惊叹的社区。([源代码](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Vvveb CMS](https://www.vvveb.com) - 强大且易于使用的CMS,用于构建网站、博客或电子商务商店。([演示](https://demo.vvveb.com), [源代码](https://github.com/givanz/Vvveb)) `AGPL-3.0` `PHP/Docker`
- [Wagtail](https://wagtail.io/) - 专注于灵活性和用户体验的Django内容管理系统。([源代码](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基于Laravel PHP框架构建的快速且安全的内容管理系统。([源代码](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - WonderCMS是自2008年以来最小的平面文件CMS。([演示](https://www.wondercms.com/demo), [源代码](https://github.com/WonderCMS/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 全球使用最广泛的博客和CMS引擎。([源代码](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`


### 客户关系管理(CRM)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[客户关系管理(CRM)](https://zh.wikipedia.org/wiki/客户关系管理)是组织用来管理、分析和改善与客户互动的战略过程。

_相关: [通讯 - 电子邮件 - 邮件列表和新闻通讯](#通讯---电子邮件---邮件列表和新闻通讯), [分析](#分析), [日历和联系人](#日历和联系人)_

- [Corteza](https://docs.cortezaproject.org) - 包括统一工作区、企业消息传递和低代码环境的CRM,用于快速安全地交付基于记录的管理解决方案。([演示](https://latest.cortezaproject.org), [源代码](https://github.com/cortezaproject/corteza)) `Apache-2.0` `Go`
- [Django-CRM](https://DjangoCRM.github.io/info/) - 具有任务管理、电子邮件营销等功能的分析型CRM。Django CRM专为个人使用、任何规模的企业或自由职业者构建,旨在提供轻松的定制和快速开发。([源代码](https://github.com/DjangoCRM/django-crm)) `AGPL-3.0` `Python`
- [EspoCRM](https://www.espocrm.com/) - 具有作为单页应用程序设计的前端和REST API的CRM。([演示](https://demo.espocrm.com/), [源代码](https://github.com/espocrm/espocrm)) `AGPL-3.0` `PHP`
- [Krayin](https://krayincrm.com/) - 面向中小企业和企业完整的客户生命周期管理的CRM解决方案。([演示](https://demo.krayincrm.com/), [源代码](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [Relaticle](https://relaticle.com) - 具有MCP服务器、AI助手(带人工审批更改)、REST API、自定义字段和看板的CRM。([源代码](https://github.com/relaticle/relaticle)) `AGPL-3.0` `PHP/Docker`
- [SuiteCRM](https://suitecrm.com) - 获奖的企业级开源CRM。([源代码](https://github.com/SuiteCRM/SuiteCRM)) `AGPL-3.0` `PHP`
- [Twenty](https://twenty.com) - 现代化CRM,提供开源的灵活性、先进功能和时尚的设计。([源代码](https://github.com/twentyhq/twenty)) `AGPL-3.0` `Docker`


### 数据库管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[数据库](https://zh.wikipedia.org/wiki/数据库)管理的Web界面。包括数据库分析和可视化工具。

_相关: [分析](#分析), [自动化](#自动化)_

_另见: [dbdb.io - 数据库之数据库](https://dbdb.io/)_

- [Adminer](https://www.adminer.org/) - 单个PHP文件中的数据库管理。适用于MySQL、MariaDB、PostgreSQL、SQLite、MS SQL、Oracle、Elasticsearch、MongoDB等。([源代码](https://github.com/vrana/adminer)) `Apache-2.0/GPL-2.0` `PHP`
- [Azimutt](https://azimutt.app) - 为真实世界数据库(大型和杂乱)制作的可视数据库探索工具。探索您的数据库模式以及数据、记录它们、扩展它们,甚至获得分析和指导。([演示](https://azimutt.app/gallery/gospeak), [源代码](https://github.com/azimuttapp/azimutt)) `MIT` `Elixir/Nodejs/Docker`
- [Baserow](https://baserow.io/) - 无需技术经验即可创建您自己的数据库(Airtable的替代品)。([源代码](https://gitlab.com/baserow/baserow)) `MIT` `Docker`
- [Bytebase](https://www.bytebase.com/) - 面向DevOps团队的安全数据库模式变更和版本控制,支持MySQL、PostgreSQL、TiDB、ClickHouse和Snowflake。([源代码](https://github.com/bytebase/bytebase)) `MIT` `Docker/K8S/Go`
- [Chartbrew](https://chartbrew.com) - 直接连接到数据库和API,并使用数据创建漂亮的图表。([演示](https://app.chartbrew.com/live-demo), [源代码](https://github.com/chartbrew/chartbrew)) `MIT` `Nodejs/Docker`
- [ChartDB](https://chartdb.io/) - 数据库图表编辑器,允许您通过单个查询可视化和设计您的数据库。([演示](https://app.chartdb.io), [源代码](https://github.com/chartdb/chartdb)) `AGPL-3.0` `Nodejs/Docker`
- [CloudBeaver](https://dbeaver.com/) - 管理数据库,支持PostgreSQL、MySQL、SQLite等。DBeaver的Web/托管版本。([源代码](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`
- [d9](https://d9.webcapsule.io) - 通过直观的管理界面将SQL数据库转换为安全API。数据平台和无头CMS(Directus的分支)。([源代码](https://github.com/LaWebcapsule/d9)) `GPL-3.0` `Nodejs`
- [Databunker](https://databunker.org/) - 基于网络的、自托管的、符合GDPR的、安全的个人数据或PII数据库。([源代码](https://github.com/securitybunker/databunker)) `MIT` `Docker`
- [datannur](https://datannur.com) - 用于记录和探索结构化数据文件和数据库的轻量级数据目录。([演示](https://dev.datannur.com/), [源代码](https://github.com/datannur/datannur)) `MIT` `Python`
- [Datasette](https://datasette.io/) - 通过简单的导入导出和数据库管理来探索和发布数据。([源代码](https://github.com/simonw/datasette)) `Apache-2.0` `Python/Docker`
- [drawDB](https://www.drawdb.app) - 基于浏览器的可视化和DBML数据库图表编辑器以及适用于MySQL、PostgreSQL、SQLite、MariaDB、MSSQL和Oracle的SQL生成器。([演示](https://www.drawdb.app/editor), [源代码](https://github.com/drawdb-io/drawdb)) `AGPL-3.0` `Nodejs/Docker`
- [Evidence](https://evidence.dev) - 基于代码的BI工具。使用SQL和markdown编写报告,它们将渲染为网站。([源代码](https://github.com/evidence-dev/evidence)) `MIT` `Nodejs`
- [LibreDB Studio](https://libredb.org) - 基于浏览器的SQL IDE,适用于PostgreSQL、MySQL、Oracle、SQL Server、MongoDB、Redis、ClickHouse、DuckDB等,具有SSO、审计跟踪、ER图和可选的AI辅助功能(使用您自己的模型密钥)(DataGrip、DBeaver、CloudBeaver的替代品)。([源代码](https://github.com/libredb/libredb-studio)) `MIT` `Docker/K8S`
- [Limbas](https://www.limbas.com/en/) - 用于创建数据库驱动的业务应用程序的数据库框架。作为图形数据库前端,它能够高效处理数据存量和灵活开发舒适的数据库应用程序。([源代码](https://github.com/limbas/limbas)) `GPL-2.0` `PHP`
- [Mathesar](https://mathesar.org/) - 直观的UI,用于协作管理数据,适用于所有技术技能级别的用户。基于Postgres构建——连接现有数据库或设置新数据库。([源代码](https://github.com/mathesar-foundation/mathesar)) `GPL-3.0` `Docker/Python`
- [OrcaQ](https://orca-q.com) - 现代数据库客户端和IDE,用于管理、查询和探索多种数据库类型,具有内置AI助手。([源代码](https://github.com/cin12211/orca-q)) `MIT` `Nodejs/deb/Docker`
- [StackRender](https://stackrender.io/) - 数据库模式设计和SQL迁移生成器,支持PostgreSQL、MySQL、MariaDB、SQLite、SQL Server和Oracle。([演示](https://app.stackrender.io/), [源代码](https://github.com/stackrender/stackrender)) `AGPL-3.0` `Nodejs/Docker`


### DNS

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[DNS](https://zh.wikipedia.org/wiki/域名系统)服务器和管理工具,具有广告拦截功能,主要针对家庭或小型网络。

_另见: [awesome-sysadmin/DNS - 服务器](https://github.com/awesome-foss/awesome-sysadmin#dns---服务器), [awesome-sysadmin/DNS - 控制面板和域名管理](https://github.com/awesome-foss/awesome-sysadmin#dns---控制面板--域名管理)_

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - 用户友好的广告和跟踪器拦截DNS服务器。([源代码](https://github.com/AdguardTeam/AdGuardHome)) `GPL-3.0` `Docker`
- [blocky](https://0xerr0r.github.io/blocky/latest/) - 快速轻量级的DNS代理,作为本地网络的广告拦截器,具有许多功能(Pi-hole的替代品)。([源代码](https://github.com/0xERR0R/blocky)) `Apache-2.0` `Go/Docker`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - 本地广告拦截器。像Pi-hole但是本地的,使用您的操作系统。([源代码](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Shell`
- [Numa](https://numa.rs/) - 广告拦截DNS解析器,具有DNSSEC验证递归解析、DoH/DoT/Oblivious DoH、临时覆盖和本地服务域,单个Rust二进制文件(Pi-hole、AdGuard Home、NextDNS的替代品)。([源代码](https://github.com/razvandimescu/numa)) `MIT` `Rust/Docker/Nix`
- [Pi-hole](https://pi-hole.net/) - 互联网广告黑洞,具有用于管理和监控的GUI。([源代码](https://github.com/pi-hole/pi-hole)) `EUPL-1.2` `Shell/PHP/Docker`
- [Technitium DNS Server](https://technitium.com/dns/) - 具有广告拦截功能的权威/递归DNS服务器。([源代码](https://github.com/TechnitiumSoftware/DnsServer)) `GPL-3.0` `Docker/C#`


### 文档管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[文档管理系统](https://zh.wikipedia.org/wiki/文档管理系统)(DMS)是用于接收、跟踪、管理和存储文档并减少纸张的系统。

- [BentoPDF](https://bentopdf.com) `⚠` - 强大的、以隐私优先的、客户端PDF工具包,允许您直接在浏览器中操作、编辑、合并和处理PDF文件。([演示](https://bentopdf.com), [源代码](https://github.com/alam00000/bentopdf)) `AGPL-3.0` `Nodejs/Docker`
- [Bottle Rocket](https://bottle-rocket.app/) - 文档扫描和管理应用程序,兼容Rocketbook和Scribzee格式。([源代码](https://github.com/gman-au/bottle-rocket-server)) `MIT` `C#/Docker`
- [Docspell](https://docspell.org) - 自动标记文档整理器和归档。([源代码](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java/Docker`
- [Documenso](https://documenso.com) - 数字文档签名平台(DocuSign的替代品)。([源代码](https://github.com/documenso/documenso)) `AGPL-3.0` `Nodejs/Docker`
- [Docuseal](https://www.docuseal.co) - 创建、填写和签署数字文档(DocuSign的替代品)。([演示](https://demo.docuseal.tech/), [源代码](https://github.com/docusealco/docuseal)) `AGPL-3.0` `Docker`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core) - 用于私人使用的简单文档管理系统,具有基本功能来数字化组织您的文档。`GPL-3.0` `Docker/Ruby`
- [Gotenberg](https://gotenberg.dev) - 对开发者友好的API,与Chromium和LibreOffice等强大工具交互,将多种文档格式(HTML、Markdown、Word、Excel等)转换为PDF文件等。([源代码](https://github.com/gotenberg/gotenberg)) `MIT` `Docker`
- [I, Librarian](https://i-librarian.net) - 组织PDF论文和办公文档。它为行业和学术界的学生和研究小组提供了许多额外功能。([演示](https://eu1.i-librarian.net/demo), [源代码](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - 电子文档管理系统,用于管理您的文档,具有预览生成、OCR和自动分类等功能。([源代码](https://gitlab.com/mayan-edms/mayan-edms)) `GPL-2.0` `Docker/K8S`
- [OpenSign](https://www.opensignlabs.com) `⚠` - 文档签名软件(DocuSign的替代品)。([源代码](https://github.com/opensignlabs/opensign)) `AGPL-3.0` `Nodejs/Docker`
- [Paperless-ngx](https://docs.paperless-ngx.com/) - 扫描、索引和归档所有纸质文档,具有改进的界面(Paperless的分支)。([演示](https://demo.paperless-ngx.com/), [源代码](https://github.com/paperless-ngx/paperless-ngx)) `GPL-3.0` `Python/Docker`
- [Papermerge](https://papermerge.com) - 专注于扫描文档(电子档案)的文档管理系统。具有类似dropbox/google drive的文件浏览功能。OCR、全文搜索、文本覆盖/选择。([源代码](https://github.com/papermerge/papermerge-core)) `Apache-2.0` `Docker/K8S`
- [Papra](https://papra.app) - 极简主义文档存储、管理和归档平台,设计简单易用,人人可访问。([演示](https://demo.papra.app/), [源代码](https://github.com/papra-hq/papra/)) `AGPL-3.0` `Docker`
- [PdfDing](https://www.pdfding.com) - PDF管理器、查看器和编辑器,在多设备上提供无缝的用户体验。它设计为极简、快速,并使用Docker易于设置。([演示](https://demo.pdfding.com), [源代码](https://codeberg.org/mrmn/PdfDing)) `AGPL-3.0` `Docker/K8S`
- [SeedDMS](https://www.seeddms.org) - 具有工作流、访问权限、全文搜索等的文档管理系统。([演示](https://www.seeddms.org/about/), [源代码](https://sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- [Signature PDF](https://github.com/24eme/signaturepdf) - 签署和操作PDF,具有协作、组织、压缩和元数据编辑功能。([演示](https://pdf.24eme.fr/)) `AGPL-3.0` `PHP/deb/Docker`
- [SimpleDMS](https://simpledms.eu) - 易于使用的、元数据驱动的文档管理系统(DMS),面向小型企业,几乎自动对文档进行排序。([源代码](https://github.com/simpledms/simpledms), [客户端](https://simpledms.eu/en/product/integrations)) `AGPL-3.0` `Docker`
- [SnapOtter](https://snapotter.com) - 200多种Web工具套件,用于转换和编辑图像、视频、音频和PDF,包括基于图层的图像编辑器、OCR、转录、背景去除和批处理管道(SmallPDF、iLovePDF、CloudConvert的替代品)。([演示](https://demo.snapotter.com), [源代码](https://github.com/snapotter-hq/SnapOtter)) `AGPL-3.0` `Docker`
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - 本地托管的Web应用程序,允许您对PDF文件执行各种操作,如合并、拆分、文件转换和OCR。`Apache-2.0` `Docker/Java`


### 文档管理 - 电子书

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[电子书](https://zh.wikipedia.org/wiki/电子书)图书馆管理软件。

- [Atsumeru](https://atsumeru.xyz) - 漫画/漫画/轻小说媒体服务器,具有Windows、Linux、macOS和Android客户端。([源代码](https://github.com/Atsumeru-xyz/Atsumeru), [客户端](https://atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- [Bindery](https://github.com/jarynclouatre/bindery) - 文件夹监视转换器,用于电子书和漫画。通过kepubify将EPUB转换为Kobo KEPUB,通过Kindle Comic Converter转换CBZ/CBR/PDF,具有每设备配置文件、ComicInfo.xml命名、章节到卷捆绑和Web UI。`MIT` `Docker`
- [BookLogr](https://github.com/Mozzo1000/booklogr) - 轻松管理您的个人图书库。([演示](https://demo.booklogr.app/)) `Apache-2.0` `Docker`
- [Calibre Web Automated](https://github.com/crocodilestick/Calibre-Web-Automated) - 一体化解决方案,结合了Calibre-Web的现代轻量级Web UI和Calibre的强大多功能特性集(Calibre Web的分支)。`GPL-3.0` `Docker`
- [Calibre Web](https://github.com/janeczku/calibre-web) - 使用现有Calibre数据库浏览、阅读和下载电子书。`GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 电子书图书馆管理器,可以查看、转换和编目大多数主要电子书格式的电子书,并为远程客户端提供内置Web服务器。([演示](https://calibre-ebook.com/demo), [源代码](https://github.com/kovidgoyal/calibre)) `GPL-3.0` `Python/deb`
- [Grimmory](https://grimmory.org/) - 用于电子书、漫画和有声读物的图书馆,具有内置阅读器、元数据查找、多用户支持、OPDS以及Kobo/KOReader同步功能。([源代码](https://github.com/grimmory-tools/grimmory)) `AGPL-3.0` `Docker`
- [Inkheart](https://gitlab.com/Nystik/inkheart) - 轻量级PDF库和阅读器。`Apache-2.0` `Docker`
- [Kapowarr](https://casvt.github.io/Kapowarr/) - 构建和管理漫画图书馆。下载、重命名、移动和转换您喜欢的卷期。([源代码](https://github.com/Casvt/Kapowarr)) `GPL-3.0` `Docker/Python`
- [Kavita](https://www.kavitareader.com/) - 跨平台电子书/漫画/漫画/pdf服务器和Web阅读器,具有用户管理、评分和评论以及元数据支持。([演示](https://www.kavitareader.com/#demo), [源代码](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [kiwix-serve](https://github.com/kiwix/kiwix-tools) - 用于从ZIM文件提供维基百科服务的HTTP守护进程。`GPL-3.0` `C++`
- [Komga](https://komga.org) - 漫画/漫画/BD的媒体服务器,具有API和OPDS支持,用于探索您的图书馆的现代Web界面,以及Web阅读器。([源代码](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [MyMangaDB](https://github.com/FabianRolfMatthiasNoll/MyMangaDB) `⚠` - 漫画收藏管理器,具有自动元数据、MyAnimeList导入和详细的收藏统计信息。`GPL-3.0` `Docker`
- [Stump](https://www.stumpapp.dev) - 一个快速、免费且开源的漫画、漫画和数字图书服务器,支持OPDS。([源代码](https://github.com/stumpapp/stump)) `MIT` `Rust`


### 文档管理 - 机构库和数字图书馆软件

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[机构库](https://zh.wikipedia.org/wiki/机构库)和[数字图书馆](https://zh.wikipedia.org/wiki/数字图书馆)管理软件。

- [DSpace](http://www.dspace.org/) - 提供对数字资源持久访问的交钥匙仓库应用程序。([源代码](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - 具有灵活元数据和工作流模型的数字文档管理系统,主要面向学术机构。([演示](http://tryme.demo.eprints-hosting.org/), [源代码](https://github.com/eprints/eprints3.4)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - 强大且模块化的仓库系统,用于管理和传播数字内容,特别适合数字图书馆和档案,既用于访问也用于保存。([源代码](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [InvenioRDM](https://inveniordm.docs.cern.ch/) - 高度可扩展的交钥匙研究数据管理平台,具有出色的用户体验。([演示](https://inveniordm.web.cern.ch/), [源代码](https://github.com/inveniosoftware/invenio-app-rdm), [客户端](https://inveniosoftware.org/products/rdm/)) `MIT` `Python`
- [Islandora](https://www.islandora.ca/) - 用于浏览和管理基于Fedora的数字仓库的Drupal模块。([演示](https://sandbox.islandora.ca/), [源代码](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Samvera框架的前端,Samvera本身是一个用于浏览和管理基于Fedora的数字仓库的Ruby on Rails应用程序。([源代码](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### 文档管理 - 集成图书馆系统(ILS)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[集成图书馆系统](https://zh.wikipedia.org/wiki/集成图书馆系统)是图书馆的企业资源规划系统,用于跟踪拥有的物品、下的订单、支付的账单以及借阅的读者。

_相关: [内容管理系统(CMS)](#内容管理系统cms), [归档和数字保存(DP)](#归档和数字保存dp)_

- [Evergreen](https://evergreen-ils.org) - 高度可扩展的图书馆软件,帮助图书馆读者查找图书馆资料,并帮助图书馆管理、编目和流通这些资料。([源代码](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PLpgSQL`
- [Koha](https://koha-community.org/) - 企业级ILS,具有采购、流通、编目、标签打印、离线流通(当无法访问互联网时)等模块,以及更多功能。([演示](https://koha-community.org/demo/), [源代码](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - 可作为服务运行的大规模ILS,具有联盟功能,主要面向图书馆网络。包括大多数标准模块(流通、采购、编目等)以及基于Web的公共和专业界面。([演示](https://ils.test.rero.ch/), [源代码](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Docker`


### 电子商务

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[电子商务](https://zh.wikipedia.org/wiki/电子商务)软件。

_相关: [社区支持农业(CSA)](#社区支持农业csa)_

- [Aimeos](https://aimeos.org/) - 电子商务框架,用于使用Laravel构建自定义在线商店、市场和可扩展到数十亿商品的复杂B2B应用程序。([演示](https://demo.aimeos.org/), [源代码](https://github.com/aimeos/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Bagisto](https://bagisto.com/en/) - 领先的Laravel开源电子商务框架,具有多库存来源、税务、本地化、代发货等更多激动人心的功能。([演示](https://demo.bagisto.com/), [源代码](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - Pimcore的电子商务插件。([源代码](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal CMS的热门电子商务模块,支持数十种支付、运输和购物相关模块。([源代码](https://git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- [EverShop](https://evershop.io/) `⚠` - 具有基本商务功能的电子商务平台。模块化架构,完全可定制。([演示](https://demo.evershop.io/), [源代码](https://github.com/evershopcommerce/evershop)) `GPL-3.0` `Docker/Nodejs`
- [Magento Open Source](https://business.adobe.com/products/magento/magento-commerce.html) - 开放全渠道创新的领先提供商。([源代码](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [MedusaJs](https://medusajs.com/) - 无头商务引擎,使开发者能够创建令人惊叹的数字商务体验。([演示](https://next.medusajs.com/), [源代码](https://github.com/medusajs/medusa)) `MIT` `Nodejs`
- [myCart](https://github.com/shurco/mycart) `⚠` - 单文件购物车(支持通过卡或加密货币支付)。`MIT` `Go/Docker`
- [Open Source POS](https://github.com/opensourcepos/opensourcepos) - 开源销售点是基于Web的销售点系统。`MIT` `PHP`
- [OpenCart](https://www.opencart.com) - 购物车解决方案。([源代码](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [PrestaShop](https://www.prestashop.com/) - 完全可扩展的电子商务解决方案。([演示](https://demo.prestashop.com/), [源代码](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - 活动票务销售平台。([源代码](https://github.com/pretix/pretix)) `AGPL-3.0` `Python/Docker`
- [s-cart](https://s-cart.org/) - 面向个人和企业的电子商务网站,基于Laravel框架构建。([演示](https://demo.s-cart.org/), [源代码](https://github.com/gp247net/s-cart)) `MIT` `PHP`
- [Saleor](https://saleor.io) - GraphQL原生、仅API的平台,用于可扩展的可组合电子商务店面。([演示](https://demo.saleor.io/), [源代码](https://github.com/saleor/saleor)) `BSD-3-Clause` `Docker/Python`
- [Shopware Community Edition](https://www.shopware.com/en/community/community-edition/) - 基于PHP的德国制造的开源电子商务软件。([演示](https://www.shopware.com/en/test-demo/), [源代码](https://github.com/shopware/shopware)) `MIT` `PHP`
- [Solidus](https://solidus.io/) - 电子商务平台,让您完全控制您的商店。([源代码](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby/Docker`
- [Spree Commerce](https://spreecommerce.org) - Spree是一个完整的、模块化的、API驱动的Ruby on Rails开源电子商务解决方案。([演示](https://demo.spreecommerce.org/), [源代码](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - 基于Symfony2的开源全栈电子商务平台。([演示](https://sylius.com/try/), [源代码](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - Thelia是一个开源且灵活的电子商务解决方案。([演示](https://demo.thelia.net/), [源代码](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [Vendure](https://www.vendure.io) - 无头商务框架。([演示](https://demo.vendure.io), [源代码](https://github.com/vendurehq/vendure)) `MIT` `Nodejs`
- [WooCommerce](https://woocommerce.com/) - 基于WordPress的电子商务解决方案。([源代码](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`


### 联合身份和认证

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[联合身份](https://zh.wikipedia.org/wiki/联合身份)和[认证](https://zh.wikipedia.org/wiki/电子认证)软件。

**请访问 [awesome-sysadmin/身份管理](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### Feed阅读器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[新闻聚合器](https://zh.wikipedia.org/wiki/新闻聚合器),也称为feed聚合器、feed阅读器、新闻阅读器、[RSS](https://zh.wikipedia.org/wiki/RSS)阅读器,是一种将网络内容(如报纸/博客/vlog/播客)聚合在一个位置以便于查看的应用程序。

- [Bubo Reader](https://github.com/georgemandis/bubo-rss) - 极简主义RSS feed阅读器。([演示](https://bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- [CommaFeed](https://www.commafeed.com/) - 受Google Reader启发的自托管RSS阅读器。([演示](https://www.commafeed.com/#/app/category/all), [源代码](https://github.com/Athou/commafeed)) `Apache-2.0` `Java/Docker`
- [Feeds Fun](https://feeds.fun/) - 具有标签、评分和AI功能的新闻阅读器。([源代码](https://github.com/Tiendil/feeds.fun)) `BSD-3-Clause` `Python`
- [FreshRSS](https://freshrss.org/) - 可自托管的RSS feed聚合器。([演示](https://demo.freshrss.org/i/), [源代码](https://github.com/FreshRSS/FreshRSS)) `AGPL-3.0` `PHP/Docker`
- [Fusion](https://github.com/0x2E/fusion) - 轻量级RSS聚合器和阅读器。`MIT` `Go/Docker`
- [Goeland](https://github.com/slurdge/goeland) - 将任何RSS/Atom feed转换为漂亮的电子邮件摘要。`MIT` `Go/Docker`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR(Just Another RSS Reader)是基于Web的新闻聚合器和阅读器(Newspipe的分支)。([演示](https://www.jarr.info/), [源代码](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Docker/Python`
- [Kriss Feed](https://github.com/tontof/kriss_feed) - 简单而智能(或愚蠢)的feed阅读器。`CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed(轻量级Feed)是一个免费且极简主义的RSS聚合器。`AGPL-3.0` `PHP`
- [Miniflux](https://miniflux.app/) - 极简主义新闻阅读器。([源代码](https://github.com/miniflux/v2)) `Apache-2.0` `Go/deb/Docker`
- [NewsBlur](https://www.newsblur.com/) - 个人新闻阅读器,将人们聚集在一起讨论世界。一种旧乐器的新声音。([源代码](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Web新闻阅读器。([演示](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [reader](https://github.com/lemon24/reader) - Feed阅读器Web应用程序和库(因此您可以使用它来构建自己的),仅依赖标准库和纯Python。`BSD-3-Clause` `Python`
- [Readflow](https://readflow.app) - 轻量级新闻阅读器,具有现代界面和功能:全文搜索、自动分类、归档、离线支持、通知。([源代码](https://github.com/ncarlier/readflow)) `AGPL-3.0` `Go/Docker`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - 为没有RSS/ATOM feed的网站生成RSS/ATOM feed。`Unlicense` `PHP/Docker`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - 易于使用的基于Web的RSS聚合器和阅读器,兼容Fever API(Google Reader的替代品)。`MIT` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - 获取RSS/Atom-feed并将新内容推送到任何电子邮件接收器,支持OPML。`GPL-2.0` `Python/deb`
- [RSSHub](https://docs.rsshub.app) - 易于使用且可扩展的RSS feed聚合器,能够从几乎所有内容(从社交媒体到大学部门)生成RSS feed。([演示](https://rsshub.app), [源代码](https://github.com/DIYgod/RSSHub)) `MIT` `Nodejs/Docker`
- [Selfoss](https://selfoss.aditu.de/) - 新的多用途rss阅读器、直播流、混搭、聚合Web应用程序。([源代码](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Stringer](https://github.com/stringer-rss/stringer) - 开发中的自托管、反社交RSS阅读器。`MIT` `Ruby`
- [Tiny Tiny RSS](https://tt-rss.org) - 基于Web的新闻feed(RSS/Atom)阅读器和聚合器。([源代码](https://github.com/tt-rss/tt-rss)) `GPL-3.0` `Docker/PHP`
- [TinyFeed](https://feed.lovergne.dev/) - 使用简单的CLI从feed集合生成静态HTML页面。([演示](https://feed.lovergne.dev/demo), [源代码](https://github.com/TheBigRoomXXL/tinyfeed)) `MIT` `Go/Docker`
- [Upvote RSS](https://www.upvote-rss.com/) `⚠` - 从Reddit、Hacker News、Lemmy、Mbin等生成丰富的RSS feed。([演示](https://www.upvote-rss.com/), [源代码](https://github.com/johnwarne/upvote-rss)) `MIT` `Docker/PHP`
- [Yarr](https://github.com/nkanaev/yarr) - Yarr(yet another rss reader)是基于Web的feed聚合器,可用作桌面应用程序和个人自托管服务器。`MIT` `Go`


### 文件传输和同步

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[文件传输](https://zh.wikipedia.org/wiki/文件传输)、[共享](https://zh.wikipedia.org/wiki/文件共享)和[同步软件](https://zh.wikipedia.org/wiki/文件同步)。

_相关: [群件](#群件)_

- [bewCloud](https://bewcloud.com) - 文件共享+同步、笔记和照片(Nextcloud和ownCloud的RSS阅读器的替代品)。([源代码](https://github.com/bewcloud/bewcloud), [客户端](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- [Cloudreve](https://cloudreve.org/) - 文件管理和共享系统,支持多种存储提供商。([演示](https://demo.cloudreve.org), [源代码](https://github.com/cloudreve/cloudreve)) `GPL-3.0` `Docker/Go`
- [Git Annex](https://git-annex.branchable.com/) - 计算机之间、服务器之间、外部驱动器之间的文件同步。([源代码](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - 具有同步和共享能力的极简主义JSON存储服务。([源代码](https://github.com/Kinto/kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - 从任何设备访问和共享您的文件、日历、联系人、邮件和[更多内容](https://apps.nextcloud.com/),按照您的条件。([演示](https://try.nextcloud.com/), [源代码](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP/deb`
- [OpenCloud](https://docs.opencloud.eu/) - 文件共享和协作平台。([源代码](https://github.com/opencloud-eu/opencloud)) `Apache-2.0` `Docker/Go/Nodejs`
- [OpenSSH SFTP server](https://www.openssh.com/) - 安全文件传输程序。([源代码](https://cvsweb.openbsd.org/src/usr.bin/ssh?sort=File)) `BSD-2-Clause` `C/deb`
- [ownCloud](https://owncloud.org/) - 用于保存、同步、查看、编辑和共享文件、日历、通讯录等的一体化解决方案。([源代码](https://github.com/owncloud/core), [客户端](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP/Docker/deb`
- [Peergos](https://peergos.org) - 安全且私密的在线空间,您可以在其中存储、共享和查看您的照片、视频、音乐和文档。还包括日历、新闻feed、任务列表、聊天和电子邮件客户端。([源代码](https://github.com/Peergos/Peergos)) `AGPL-3.0` `Java`
- [Puter](https://puter.com/) - 基于Web的操作系统,设计为功能丰富、异常快速且高度可扩展。([演示](https://puter.com/), [源代码](https://github.com/heyputer/puter)) `AGPL-3.0` `Nodejs/Docker`
- [Pydio](https://pydio.com/) - 将任何Web服务器转换为强大的文件管理系统,是主流云存储提供商的替代品。([演示](https://pydio.com/en/demo), [源代码](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba是Linux和Unix的标准Windows互操作性程序套件。它为所有使用SMB/CIFS协议的客户端提供安全、稳定和快速的文件和打印服务。([源代码](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要面向团队和组织的文件托管和共享解决方案。([源代码](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [Sync-in](https://sync-in.com) - 文件存储、同步、共享和协作,具有实时编辑、权限管理和桌面/CLI客户端。([演示](https://sync-in.com/docs/demo), [源代码](https://github.com/Sync-in/server), [客户端](https://github.com/Sync-in/desktop)) `AGPL-3.0` `Nodejs/Docker`
- [Syncthing](https://syncthing.net/) - Syncthing是一个开源的点对点文件同步工具。([源代码](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go/Docker/deb`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison是一个适用于OSX、Unix和Windows的文件同步工具。([源代码](https://github.com/bcpierce00/unison)) `GPL-3.0` `deb/OCaml`


### 文件传输 - 分布式文件系统

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

网络分布式文件系统。

**请访问 [awesome-sysadmin/分布式文件系统](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**



### 文件传输 - 对象存储和文件服务器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[对象存储](https://zh.wikipedia.org/wiki/对象存储)是一种计算机数据存储,它将数据作为对象进行管理,与其他存储架构(如将数据作为文件层次结构管理的文件系统,以及将数据作为扇区内的块进行管理的块存储)不同。

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 地理分布式的S3兼容存储服务,可以满足许多需求。([源代码](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- [Harbor](https://goharbor.io/) - 云原生镜像仓库,用于存储、签名和扫描内容。([源代码](https://github.com/goharbor/harbor)) `Apache-2.0` `Docker/K8S`
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - SeaweedFS是一个开源分布式文件系统,支持WebDAV、S3 API、FUSE挂载、HDFS等,针对大量小文件进行了优化,易于扩展容量。`Apache-2.0` `Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - 在前端实现Amazon S3协议,在后端具有多个云(包括Azure和Google)的存储能力。([源代码](https://github.com/scality/cloudserver)) `Apache-2.0` `Docker/Nodejs`
- [ZOT OCI Registry](https://zotregistry.dev) - 生产就绪的中立供应商OCI原生容器镜像仓库。([演示](https://zothub.io), [源代码](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`


### 文件传输 - 点对点文件共享

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[点对点文件共享](https://zh.wikipedia.org/wiki/点对点文件共享)是使用[点对点](https://zh.wikipedia.org/wiki/点对点)(P2P)网络技术分发和[共享](https://zh.wikipedia.org/wiki/文件共享)数字媒体。

- [bittorrent-tracker](https://webtorrent.io/) - 简单、健壮的BitTorrent跟踪器(客户端和服务器)实现。([源代码](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [Deluge](https://deluge-torrent.org/) - 轻量级跨平台BitTorrent客户端。([源代码](https://git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- [PrivyDrop](https://www.privydrop.app) - 简单易用的基于WebRTC的可断点续传点对点文本、图像和文件传输工具。([源代码](https://github.com/david-bai00/PrivyDrop)) `MIT` `Docker/Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - 具有功能丰富的用于远程访问的Web UI的免费跨平台bittorrent客户端。([源代码](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [slskd](https://github.com/slskd/slskd) `⚠` - Soulseek文件共享网络的现代客户端-服务器应用程序。`AGPL-3.0` `Docker/C#`
- [Transmission](https://transmissionbt.com/) - 快速、简单、免费的Bittorrent客户端。([源代码](https://github.com/transmission/transmission)) `GPL-3.0` `C++/deb`
- [Webtor](https://github.com/webtor-io/self-hosted) - 具有即时音频/视频流功能的基于Web的torrent客户端。([演示](https://webtor.io)) `MIT` `Docker`


### 文件传输 - 单击和拖放上传

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

简化的文件服务器,用于共享一次性/短期/临时文件,提供单击或[拖放](https://zh.wikipedia.org/wiki/拖放)上传功能。

- [015](https://send.fudaoyuan.icu) - 临时文件共享平台。专注于提供一次性、临时文件和文本的上传、处理和共享服务。([源代码](https://github.com/keven1024/015)) `AGPL-3.0` `Docker`
- [Chibisafe](https://chibisafe.app) - 文件上传服务,旨在易于使用和设置。它接受文件、照片、文档以及您能想象的任何东西,并返回一个可共享的链接供您发送给其他人。([源代码](https://github.com/chibisafe/chibisafe)) `MIT` `Docker/Nodejs`
- [Digirecord](https://ladigitale.dev/digirecord/) - 录制和共享音频文件(法语文档)。([源代码](https://codeberg.org/ladigitale/digirecord)) `AGPL-3.0` `Nodejs/PHP`
- [elixire](https://gitlab.com/elixire/elixire) - 简单而高级的截图上传和链接缩短服务。([客户端](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [Files Sharing](https://github.com/axeloz/filesharing) - 基于唯一和临时链接的文件共享应用程序。`GPL-3.0` `PHP/Docker`
- [Flare](https://github.com/FlintSH/Flare) - 一个非臃肿的、现代的、高度可配置的文件/截图保险库服务器,支持ShareX、Flameshot和Spectacle。提供OCR搜索等功能。`MIT` `Docker/Nodejs`
- [Gokapi](https://github.com/Forceu/gokapi) - 轻量级服务器,用于共享在设定的下载次数或天数后过期的文件。类似于已停止服务的Firefox Send,区别在于只有管理员被允许上传文件。`GPL-3.0` `Go/Docker`
- [goploader](https://depado.github.io/goploader/) - 具有服务器端加密的简易文件共享,兼容curl/httpie/wget。([源代码](https://github.com/Depado/goploader)) `MIT` `Go`
- [GoSƐ](https://codeberg.org/stv0g/gose) - 专注于可扩展性和简洁性的现代文件上传器。它仅依赖于S3存储后端,因此可以水平扩展而无需额外的数据库或缓存。`Apache-2.0` `Go/Docker`
- [Jirafeau](https://gitlab.com/jirafeau/Jirafeau) - 一键文件共享项目。选择您的文件,上传并共享链接。就这样。`AGPL-3.0` `PHP/Docker`
- [OnionShare](https://github.com/onionshare/onionshare) - 安全且匿名地共享任何大小的文件。`GPL-3.0` `Python/deb`
- [PicoShare](https://github.com/mtlynch/picoshare) - 极简主义的、易于托管的图像和其他文件共享服务。([客户端](https://github.com/mtlynch/picoshare#third-party-clients)) `AGPL-3.0` `Go/Docker`
- [PictShare](https://www.pictshare.net/) - 多语言图像托管服务,具有简单的调整大小和上传API。([源代码](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP/Docker`
- [Pingvin Share X](https://github.com/smp46/pingvin-share-x) - 文件共享平台,支持登录、反向共享、共享过期、S3 Bucket、高级认证、ClamAV安全扫描等(Pingvin Share的分支)。`BSD-2-Clause` `Docker/Nodejs`
- [Plik](https://github.com/root-gg/plik) - 可扩展且友好的临时文件上传系统。([演示](https://plik.root.gg/)) `MIT` `Go/Docker`
- [ProjectSend](https://www.projectsend.org/) - 上传文件并将其分配给您创建的特定客户端。让您的客户访问这些文件。([源代码](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - 具有健壮的上传/下载续传和密码保护的简单文件共享解决方案。`BSD-2-Clause` `Nodejs`
- [QuickShare](https://ihexxa.github.io/quickshare.site/) - 不同设备之间的快速简单文件共享。([源代码](https://github.com/ihexxa/quickshare)) `LGPL-3.0` `Docker/Go`
- [Safebucket](https://docs.safebucket.io/) - 具有可插拔基础设施的文件共享平台,其中上传和下载直接在客户端和S3兼容存储之间进行。([源代码](https://github.com/safebucket/safebucket)) `Apache-2.0` `Go/Docker`
- [sE2EEnd](https://github.com/sE2EEnd/sE2EEnd) - 端到端加密文件共享,具有密码保护、下载限制和自动过期,与Keycloak集成进行身份验证。`AGPL-3.0` `Docker`
- [Sharry](https://github.com/eikek/sharry) - 在经过身份验证和匿名用户之间(双向)轻松共享文件,支持可恢复的上传和下载。`GPL-3.0` `Scala/Java/deb/Docker`
- [Shifter](https://github.com/TobySuch/Shifter) - 一个简单的、自托管的文件共享Web应用,由Django驱动。`MIT` `Docker`
- [Slink](https://docs.slinkapp.io/) - 图像共享平台,旨在让用户完全控制其媒体共享体验。([源代码](https://github.com/andrii-kryvoviaz/slink)) `AGPL-3.0` `Docker`
- [snowshare](https://github.com/TuroYT/snowshare) - 文件和链接共享平台,具有URL缩短、代码片段共享和文件上传功能,具有可定制的过期时间、隐私设置和二维码。([演示](https://s.romain-pinsolle.fr)) `CC0-1.0` `Nodejs/Docker`
- [transfer.sh](https://github.com/dutchcoders/transfer.sh) - 从命令行轻松共享文件。`MIT` `Go`
- [Uguu](https://github.com/nokonoko/uguu) - 存储文件并在X时间后删除。`MIT` `PHP`
- [XBackBone](https://xbackbone.app/) - 简单、快速且轻量级的文件管理器,集成即时共享工具,如ShareX。([源代码](https://github.com/SergiX44/XBackBone)) `AGPL-3.0` `PHP/Docker`
- [Zipline](https://github.com/diced/zipline) - 一个轻量级、快速且可靠的文件共享服务器,通常与ShareX一起使用,提供基于React的Web UI和快速API。`MIT` `Docker/Nodejs`


### 文件传输 - 基于Web的文件管理器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

基于Web的[文件管理器](https://zh.wikipedia.org/wiki/文件管理器)。

_相关: [群件](#群件)_

- [Apaxy](https://oupala.github.io/apaxy/) - 主题构建,用于增强浏览Web目录的体验,使用mod_autoindex Apache模块和一些CSS来覆盖目录列表的默认样式。([源代码](https://github.com/oupala/apaxy)) `GPL-3.0` `Javascript`
- [ClyoCloud](https://clyo.cloud/) - 个人自托管云存储和媒体管理应用,专为隐私、效率和美学而构建。([源代码](https://code.weexnes.dev/ClyoCloud)) `AGPL-3.0` `Nodejs`
- [copyparty](https://github.com/9001/copyparty) - 便携式文件服务器,具有加速的可恢复上传、去重、WebDAV、FTP、zeroconf、媒体索引器、视频缩略图、音频转码和只写文件夹,单个文件,无强制依赖项。([演示](https://a.ocv.me/pub/demo/)) `MIT` `Python`
- [Directory Lister](https://www.directorylister.com/) - 基于PHP的简单目录列表器,列出目录及其所有子目录并允许您在其中导航。([源代码](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP/Docker`
- [FileGator](https://filegator.io/) - FileGator是一个强大的多用户文件管理器,具有单页前端。([演示](https://demo.filegator.io), [源代码](https://github.com/filegator/filegator)) `MIT` `PHP/Docker`
- [FileRise](https://github.com/error311/FileRise) - Web文件管理器,具有上传、标签、共享链接、画廊/表格视图和浏览器内编辑器。([演示](https://github.com/error311/FileRise?tab=readme-ov-file#live-demo)) `MIT` `Docker/PHP`
- [Filestash](https://www.filestash.app/) - Web文件管理器,让您在任何位置管理您的数据:FTP、SFTP、WebDAV、Git、S3、Minio、Dropbox或Google Drive。([演示](https://demo.filestash.app/), [源代码](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Docker`
- [IFM](https://github.com/misterunknown/ifm) - 单脚本文件管理器。`MIT` `PHP`
- [mikochi](https://github.com/zer0tonin/Mikochi) - 浏览远程文件夹,上传文件,删除、重命名、下载和流式传输文件到VLC/mpv。`MIT` `Go/Docker/K8S`
- [miniserve](https://github.com/svenstaro/miniserve) - 通过HTTP提供文件和目录的CLI工具。`MIT` `Rust`
- [ResourceSpace](https://www.resourcespace.com) - 组织数字资产的简单、快速且免费的方式。([演示](https://www.resourcespace.com/trial), [源代码](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [slcl](https://codeberg.org/xavidcr/slcl) - 简单轻量级的Web云存储。`AGPL-3.0` `C`
- [Surfer](https://git.cloudron.io/cloudron/surfer) - 具有用于管理文件的WebUI的简单静态文件服务器。`MIT` `Nodejs`
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces是一个离线、跨平台的文件管理器和组织者,也可以作为笔记应用运行。该应用程序的WebDAV版本可以安装在Nextcloud或ownCloud等WebDAV服务器之上。([演示](https://demo.tagspaces.com), [源代码](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Nodejs`
- [Tiny File Manager](https://tinyfilemanager.github.io) - 基于PHP的Web文件管理器,简单、快速且小的文件管理器,单个文件。([演示](https://tinyfilemanager.github.io/demo/), [源代码](https://github.com/prasathmani/tinyfilemanager)) `GPL-3.0` `PHP`


### 游戏

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

多人游戏服务器和[浏览器游戏](https://zh.wikipedia.org/wiki/浏览器游戏)。

_相关: [游戏 - 管理工具和控制面板](#游戏---管理工具和控制面板)_

- [0 A.D.](https://play0ad.com/) - 古代战争的跨平台实时战略游戏。([源代码](https://gitea.wildfiregames.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - 为浏览器设计的极简主义文本冒险游戏。([演示](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `Javascript`
- [DDraceNetwork](https://ddnet.org/) - DDRace的合作平台版本,这是Teeworlds的一个修改版本,具有独特的合作玩法。([源代码](https://github.com/ddnet/ddnet)) `Zlib` `C++`
- [Digibuzzer](https://digibuzzer.app/) - 围绕连接的蜂鸣器创建虚拟游戏室(法语文档)。([演示](https://digibuzzer.app/), [源代码](https://codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Nodejs`
- [Hypersomnia](https://github.com/TeamHypersomnia/Hypersomnia) - 竞技性俯视射击游戏,融合了反恐精英和迈阿密热线风格。可在Linux、Windows、MacOS和Web上运行。([演示](https://hypersomnia.io)) `AGPL-3.0` `C++/Docker`
- [Lila](https://lichess.org/) - 驱动lichess.org的无广告国际象棋服务器,具有官方iOS和Android客户端应用。([源代码](https://github.com/lichess-org/lila)) `AGPL-3.0` `Scala`
- [Luanti](https://www.luanti.org/) - 体素游戏引擎(前身为Minetest)。玩我们的众多游戏之一,根据您的喜好修改游戏,制作自己的游戏,或在多人服务器上玩游戏。([源代码](https://github.com/luanti-org/luanti)) `LGPL-2.1/MIT/Zlib` `C++/Lua/deb`
- [Mindustry](https://mindustrygame.github.io/) - 类似异星工厂的塔防游戏。构建生产链以收集更多资源,并建设复杂的设施。([源代码](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [MTA:SA](https://multitheftauto.com/) `⚠` - 为Rockstar North的侠盗猎车手系列添加网络游戏功能,该系列原本没有此功能。([源代码](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [OpenTTD](https://www.openttd.org/) - 运输大亨模拟游戏。([源代码](https://github.com/OpenTTD/OpenTTD), [客户端](https://bananas.openttd.org/)) `GPL-2.0` `C++/Docker`
- [piqueserver](https://github.com/piqueserver/piqueserver) - openspades的服务器,这是一个位于可破坏体素世界中的第一人称射击游戏。([客户端](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - 地理多人游戏。`MIT` `Python`
- [Razzia](https://github.com/Ralex91/Razzia) - 测验游戏平台,专为较小的自托管活动设计(Kahoot!的替代品)。`MIT` `Nodejs/Docker`
- [Red Eclipse 2](https://www.redeclipse.net/) - 类似于虚幻竞技场的竞技场第一人称射击游戏。([源代码](https://github.com/redeclipse/base)) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- [Scribble.rs](https://github.com/scribble-rs/scribble.rs) - 基于Web的你画我猜游戏。([演示](https://scribblers.fly.dev)) `BSD-3-Clause` `Go/Docker`
- [Suroi](https://suroi.io/) - 受surviv.io启发的2D大逃杀游戏。([演示](https://suroi.io/), [源代码](https://github.com/HasangerGames/suroi)) `GPL-3.0` `Nodejs`
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - Wesnoth之战是一个开源的、基于回合的战术战略游戏,具有高奇幻主题,具有单人游戏和在线/热座多人战斗。`GPL-2.0` `C++/deb`
- [Veloren](https://veloren.net/) - 多人RPG。受Cube World、塞尔达传说、矮人堡垒和Minecraft启发。([源代码](https://gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- [Zero-K](https://zero-k.info/) - 基于Springrts引擎的开源项目。Zero-K是一款传统的实时战略游戏,专注于通过地形操作、物理和大量独特单位来实现玩家创造力——同时保持平衡以支持竞技性游戏。([源代码](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### 游戏 - 管理工具和控制面板

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于管理游戏服务器和游戏库的工具。

_相关: [游戏](#游戏)_

- [auto-mcs](https://www.auto-mcs.com) - 跨平台Minecraft服务器管理器。([源代码](https://github.com/macarooni-man/auto-mcs)) `AGPL-3.0` `Python`
- [Calagopus](https://calagopus.com) - 现代游戏服务器管理面板。部署、监控和管理Minecraft、Hytale和其他游戏服务器,具有行业领先性能。([源代码](https://github.com/calagopus/panel)) `MIT` `Rust/Docker/deb`
- [Crafty Controller](https://craftycontrol.com/) - Minecraft启动器和管理器,允许用户从友好的界面启动和管理Minecraft服务器。([源代码](https://gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- [Drop](https://droposs.org) - 游戏分发平台,旨在高效分发和共享无DRM游戏(Steam、GameVault的替代品)。([源代码](https://github.com/Drop-OSS/drop), [客户端](https://github.com/Drop-OSS/drop-app)) `AGPL-3.0` `Docker`
- [EasyWI](https://easy-wi.com) - Easy-Wi是一个Web界面,允许您管理游戏服务器等服务器守护进程。此外,它还提供了一个CMS,其中包括完全自动化的游戏和语音服务器租赁服务。([源代码](https://github.com/easy-wi/developer/)) `GPL-3.0` `PHP/Shell`
- [GameAP](https://gameap.com/) - 用于在Linux和Windows上管理游戏服务器的游戏管理面板。([演示](https://demo.gameap.com/), [源代码](https://github.com/gameap/gameap), [客户端](https://plugins.gameap.dev/)) `MIT` `Go/Docker`
- [Gameyfin](https://gameyfin.org) - 视频游戏库管理器,具有自动扫描、Web访问、下载和插件支持。([源代码](https://github.com/gameyfin/gameyfin)) `AGPL-3.0` `Docker`
- [Gaseous Server](https://github.com/gaseous-project/gaseous-server) `⚠` - 游戏ROM管理器,具有基于Web的内置模拟器,使用多个来源来识别和提供元数据。`AGPL-3.0` `Docker/.NET`
- [Lancache](https://lancache.net) `⚠` - 让LAN Party游戏缓存变得简单。([源代码](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [LinuxGSM](https://linuxgsm.com/) - 用于在Linux上部署和管理专用游戏服务器的CLI工具:支持超过120个游戏。([源代码](https://github.com/GameServerManagers/LinuxGSM)) `MIT` `Shell`
- [Minus Games](https://accessory.github.io/minus_games_user_guide) - 在多台设备之间同步游戏和存档文件。([源代码](https://github.com/Accessory/minus_games)) `MIT` `Rust`
- [Ownfoil](https://github.com/a1ex4/ownfoil) - Nintendo Switch库管理器,具有自动化管理任务(文件识别和组织,缺失的更新/DLC),将您的库提供给Switch上的多个支持的客户端,具有商店定制和多用户身份验证。`AGPL-3.0` `Docker/Python`
- [Pelican Panel](https://pelican.dev/) - 用于轻松管理游戏服务器的Web应用程序,提供用于部署、配置和管理服务器的用户友好界面,服务器监控工具和广泛的自定义选项(Pterodactyl的分支)。([源代码](https://github.com/pelican/panel)) `AGPL-3.0` `PHP/Docker`
- [PKVault](https://github.com/Chnapy/PKVault) - 集中式宝可梦存储管理和图鉴应用(宝可梦之家的替代品)。([演示](https://pkvault-demo.chnapy.dev)) `GPL-3.0` `Docker`
- [Pterodactyl](https://pterodactyl.io/) - 游戏服务器管理面板,为最终用户提供直观的UI。([源代码](https://github.com/pterodactyl/panel)) `MIT` `PHP`
- [PufferPanel](https://www.pufferpanel.com/) - 游戏服务器管理面板,专为小型网络和游戏服务器提供商设计。([源代码](https://github.com/pufferpanel/pufferpanel)) `Apache-2.0` `Go`
- [RetroArr](https://retroarr.app) `⚠` - PC和复古控制台的游戏库管理器,具有元数据抓取、索引器搜索、下载自动化和基于浏览器的模拟(RomM的替代品)。([源代码](https://github.com/RiDDiX/RetroArr)) `MIT` `Docker/.NET`
- [Retrom](https://github.com/JMBeresford/retrom) - 私有云游戏库分发服务器+前端/启动器。`GPL-3.0` `Docker/Rust`
- [RomM](https://romm.app/) `⚠` - ROM管理器,用于组织、丰富和玩复古游戏,支持400+平台。([演示](https://demo.romm.app/), [源代码](https://github.com/rommapp/romm)) `AGPL-3.0` `Docker`
- [SourceBans++](https://sbpp.github.io/) - 运行在Source引擎上的游戏的管理员、封禁和通信管理系统。([源代码](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Sunshine](https://app.lizardbyte.dev/Sunshine/) - 面向Moonlight的远程游戏流主机,支持高达每秒120帧和4K分辨率。([源代码](https://github.com/LizardByte/Sunshine)) `GPL-3.0` `C++/deb/Docker`


### 家谱学

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[家谱软件](https://zh.wikipedia.org/wiki/家谱软件)用于记录、组织和发布家谱数据。

- [Genea.app](https://www.genea.app/) - 专为隐私而设计的家谱工具,任何人都可以使用它来编写或编辑他们的家谱树。数据以GEDCOM格式存储,所有处理都在浏览器中完成。([源代码](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- [Genealogy](https://genealogy.kreaweb.be/) - 记录家庭成员及其关系并构建家谱树。([演示](https://genealogy.kreaweb.be/), [源代码](https://github.com/MGeurts/genealogy)) `MIT` `PHP`
- [GeneWeb](https://github.com/geneweb/geneweb/wiki) - 可以离线使用或作为Web服务的家谱软件。([源代码](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [Gramps Web](https://www.grampsweb.org/) - 用于协作家谱学的Web应用,基于开源家谱桌面应用Gramps构建并与之互操作。([演示](https://gramps-project.github.io/gramps-web-api/), [源代码](https://github.com/gramps-project/gramps-web-api)) `AGPL-3.0` `Docker`
- [webtrees](https://www.webtrees.net) - webtrees是Web领先的在线协作家谱应用。([演示](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [源代码](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### 生成式人工智能(GenAI)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[生成式人工智能(GenAI)](https://zh.wikipedia.org/wiki/生成式人工智能)是[人工智能](https://zh.wikipedia.org/wiki/人工智能)的一个子集,使用生成模型来产生文本、图像、视频或其他形式的数据。

- [Agenta](https://agenta.ai/) - LLMOps平台,用于提示词管理、LLM评估和可观察性。通过协作式提示词工程构建、评估和监控生产级LLM应用。([源代码](https://github.com/agenta-ai/agenta)) `MIT` `Docker`
- [AnythingLLM](https://anythingllm.com/) - 一体化桌面和Docker AI应用,具有内置RAG、AI代理、无代码代理构建器、MCP兼容性等。([源代码](https://github.com/Mintplex-Labs/anything-llm)) `MIT` `Nodejs/Docker`
- [GoModel](https://gomodel.enterpilot.io/) - 用Go编写的AI网关,具有统一的OpenAI兼容API,适用于多个LLM提供商,USD成本跟踪、预算、使用分析、护栏、缓存和管理仪表板。([源代码](https://github.com/ENTERPILOT/GoModel)) `MIT` `Go/Docker`
- [Khoj](https://khoj.dev/) - 您的AI第二大脑。从网络或您的文档中获取答案。构建自定义代理,安排自动化,进行深入研究。将任何在线或本地LLM转变为您的个人自主AI。([演示](https://app.khoj.dev/), [源代码](https://github.com/khoj-ai/khoj)) `AGPL-3.0` `Python/Docker`
- [LibreChat](https://www.librechat.ai) `⚠` - 增强的ChatGPT兼容AI聊天界面,支持多个AI提供商,具有多用户认证、消息搜索和插件支持。([演示](https://chat.librechat.ai), [源代码](https://github.com/LibreChat-AI/LibreChat)) `MIT` `Nodejs/Docker`
- [LLM Harbor](https://github.com/av/harbor) - 容器化LLM工具包。通过简洁的CLI运行LLM后端、API、前端和附加服务。`Apache-2.0` `Docker/Shell`
- [LLMKube](https://llmkube.com) - 用于自托管LLM推理的Kubernetes运算符,具有可插拔运行时(llama.cpp、vLLM、TGI、Ollama、vllm-swift)、多GPU分片、NVIDIA CUDA + Apple Silicon Metal支持和OpenAI兼容API。([源代码](https://github.com/defilantech/LLMKube)) `Apache-2.0` `Go/Docker/K8S`
- [Local Deep Research](https://github.com/LearningCircuit/local-deep-research) - AI驱动的深度研究工具,具有多源搜索(arXiv、PubMed、网络)、PDF文本提取和加密本地存储。`MIT` `Docker/Python`
- [LocalAI](https://localai.io/) - 在本地运行您的AI模型并生成图像和音频(OpenAI和Claude的替代品)。([源代码](https://github.com/mudler/LocalAI), [客户端](https://localai.io/gallery.html)) `MIT` `Docker/K8S`
- [Ollama](https://ollama.com/) - 快速上手Llama 3.3、DeepSeek-R1、Phi-4、Gemma 3和其他大语言模型。([源代码](https://github.com/ollama/ollama)) `MIT` `Docker/Python`
- [Onyx Community Edition](https://onyx.app) - 与任何LLM配合使用的聊天UI。它加载了大量高级功能,如代理、Web搜索、RAG、MCP、深度研究、连接40+知识源的连接器等。([源代码](https://github.com/onyx-dot-app/onyx)) `MIT` `Docker/K8S`
- [Open-WebUI](https://openwebui.com) - 用户友好的AI界面,支持Ollama、OpenAI API。([源代码](https://github.com/open-webui/open-webui)) `BSD-3-Clause` `Docker/Python`
- [Vane](https://github.com/ItzCrazyKns/Vane) - AI驱动的搜索引擎(Perplexity AI的替代品)。`MIT` `Docker`


### 群件

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

协作软件或[群件](https://zh.wikipedia.org/wiki/协作软件)旨在帮助从事共同任务的人们实现其目标。群件通常将多种服务(如文件共享、日历/事件管理、预约调度、通讯录等)组合在一个集成的应用程序中。

_相关: [预订和调度](#预订和调度)_

- [Citadel](https://www.citadel.org/) - 包括电子邮件、日历/调度、通讯录、论坛、邮件列表、IM、维基和博客引擎、RSS聚合等的群件。([源代码](https://www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- [Colanode](https://colanode.com) - 协作套件,具有实时消息、富文本页面、文件管理和动态数据库 - 为离线工作而构建(Slack、Notion的替代品)。([源代码](https://github.com/colanode/colanode)) `Apache-2.0` `K8S/Docker`
- [Cozy Cloud](https://cozy.io/) - 个人云,您可以在其中管理和同步您的文件、笔记、联系人、密码和文档。([源代码](https://github.com/cozy/), [客户端](https://github.com/cozy/cozy-store)) `GPL-3.0` `Nodejs`
- [Digipad](https://digipad.app/) - 用于创建协作数字记事本的在线自托管应用(法语文档)。([源代码](https://codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Nodejs`
- [Digistorm](https://digistorm.app/) - 创建协作调查、测验、头脑风暴和词云(法语文档)。([演示](https://digistorm.app/), [源代码](https://codeberg.org/ladigitale/digistorm)) `AGPL-3.0` `Nodejs`
- [Digiwall](https://digiwall.app/) - 为面对面或远程工作创建多媒体协作墙(法语文档)。([源代码](https://codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Nodejs`
- [egroupware](https://www.egroupware.org/) - 软件套件,包括日历、通讯录、记事本、项目管理工具、客户关系管理工具(CRM)、知识管理工具、维基和CMS。([源代码](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [Group Office](https://www.group-office.com) - 企业CRM和群件工具。与同事和客户在线共享项目、日历、文件和电子邮件。([源代码](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - 视频会议、即时消息、白板、协作文档编辑和其他群件工具,使用Red5流媒体服务器的API功能进行远程和流媒体传输。([源代码](https://github.com/apache/openmeetings)) `Apache-2.0` `Java`
- [SOGo](https://www.sogo.nu/) - SOgo提供多种方式访问日历和消息数据。CalDAV、CardDAV、GroupDAV以及ActiveSync,包括原生Outlook兼容性和Web界面。([演示](https://demo.sogo.nu/SOGo/), [源代码](https://github.com/Alinto/sogo)) `LGPL-2.1` `Objective-C`
- [Tine](https://www.tine-groupware.de/) - 用于公司和组织数字协作的软件。从强大的群件功能到智能附加组件,tine将所有内容结合起来,使日常团队协作更容易。([源代码](https://github.com/tine-groupware/tine)) `AGPL-3.0` `Docker`
- [Tracim](https://github.com/tracim/tracim) - 团队协作协作平台:文件、线程、笔记、议程等。`AGPL-3.0/LGPL-3.0/MIT` `Python`
- [Zimbra Collaboration](https://www.zimbra.com/) - 电子邮件、日历、协作服务器,具有Web界面和大量集成。([源代码](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### 健康和健身

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[医疗](https://zh.wikipedia.org/wiki/医疗软件)、[健康](https://zh.wikipedia.org/wiki/健康信息科技)和[健身](https://zh.wikipedia.org/wiki/健身追踪器)软件。

- [Endurain](https://docs.endurain.com/) - 健身追踪服务,旨在让用户完全控制其数据和托管环境。([源代码](https://codeberg.org/endurain-project/endurain)) `AGPL-3.0` `Docker`
- [FitTrackee](https://docs.fittrackee.org/) - 简单的锻炼/活动追踪器。([源代码](https://github.com/SamR1/FitTrackee)) `AGPL-3.0` `Python/Docker`
- [Mere Medical](https://meremedical.co/) `⚠` - 从一个地方管理您来自Epic MyChart、Cerner和OnPatient患者门户的所有医疗记录。以隐私为中心、自托管、离线优先。([演示](https://demo.meremedical.co), [源代码](https://github.com/cfu288/mere-medical)) `GPL-3.0` `Docker/Nodejs`
- [NutriTrace](https://traceapps.github.io/docs/) - 营养和饮食追踪器,具有条码扫描、可穿戴设备集成(Fitbit、Withings、Garmin、Health Connect)、自适应卡路里目标、多用户共享和内置AI助手(MyFitnessPal、Cronometer的替代品)。([源代码](https://github.com/TraceApps/nutritrace)) `AGPL-3.0` `Docker`
- [OpenELIS Global](https://openelis-global.org) - 实验室信息系统(LIS/LIMS),适用于临床、公共卫生、环境和媒介监测实验室。FHIR原生,具有分析器集成(ASTM/HL7)、质量控制和国家级报告。([演示](https://openelis-global.org/getting-started/demo/), [源代码](https://github.com/DIGI-UW/OpenELIS-Global-2)) `MPL-2.0` `Java/Docker`
- [OpenEMR](https://www.open-emr.org/) - 电子健康记录和医疗实践管理解决方案。([演示](https://www.open-emr.org/demo/), [源代码](https://github.com/openemr/openemr)) `GPL-3.0` `PHP/Docker`
- [wger](https://wger.de/) - 基于Web的个人锻炼、健身和体重记录/追踪器。也可以用作简单的健身房管理实用程序,并提供完整的REST API。([演示](https://wger.de/en/dashboard), [源代码](https://github.com/wger-project/wger)) `AGPL-3.0` `Python/Docker`


### 人力资源管理(HRM)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[人力资源管理系统](https://zh.wikipedia.org/wiki/人力资源管理系统)结合了多个系统和流程,以确保[人力资源](https://zh.wikipedia.org/wiki/人力资源)、业务流程和数据的易于管理。

- [admidio](https://www.admidio.org/) - 组织和团体网站的用户管理系统。该系统具有灵活的角色模型,因此可以反映您组织的结构和权限。([演示](https://www.admidio.org/demo/), [源代码](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP/Docker`
- [Frappe HR](https://frappe.io/hr) - 完整的HRMS解决方案,拥有超过13个不同的模块,从员工管理、入职、休假到薪资、税务等。([源代码](https://github.com/frappe/hrms)) `GPL-3.0` `Docker/Python/Nodejs`
- [MintHCM](https://minthcm.org/) - 基于两个流行且知名的业务应用SugarCRM社区版和SuiteCRM的人力资本管理工具。([源代码](https://github.com/minthcm/minthcm)) `AGPL-3.0` `PHP`


### 身份管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[身份管理](https://zh.wikipedia.org/wiki/身份管理)(IdM),也称为身份和访问管理(IAM或IdAM),是一组策略和技术框架,确保正确的用户对技术资源拥有适当的访问权限。

**请访问 [awesome-sysadmin/身份管理](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### 物联网(IoT)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[物联网](https://zh.wikipedia.org/wiki/物联网)描述了具有传感器、处理能力、软件和其他技术的物理对象,这些对象通过互联网与其他设备连接和交换数据。

_相关: [自动化](#自动化)_

- [Domoticz](https://www.domoticz.com/) - 家庭自动化系统,让您监控和配置各种设备,如:灯光、开关、各种传感器/仪表,如温度、雨、风、UV、电、气、水等。([源代码](https://github.com/domoticz/domoticz), [客户端](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++/Docker/Shell`
- [EMQX](https://www.emqx.com/) - 可扩展的MQTT代理。在单个集群中连接1亿+物联网设备,以100万条消息/秒的吞吐量和1ms延迟移动和处理实时物联网数据。([演示](https://www.emqx.com/en/mqtt/public-mqtt5-broker), [源代码](https://github.com/emqx/emqx)) `Apache-2.0` `Docker/Erlang`
- [evcc](https://evcc.io/) - 可扩展电动汽车充电控制器和家庭能源管理系统。([源代码](https://github.com/evcc-io/evcc)) `MIT` `deb/Docker/Go`
- [FHEM](https://fhem.de/fhem.html) - 自动化家庭中的常见任务,如切换灯具和加热。它还可以用于记录温度或功耗等事件。您可以通过Web或智能手机前端、telnet或TCP/IP直接控制它。([源代码](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [FlowForge](https://flowforge.com/) - 以可靠、可扩展和安全的方式部署Node-RED应用程序。FlowForge平台为Node-RED开发团队提供DevOps能力。([源代码](https://github.com/FlowFuse/flowfuse)) `Apache-2.0` `Nodejs/Docker/K8S`
- [FMD Server](https://fmd-foss.org) - 与FMD(Find My Device)Android应用通信的服务器,用于定位和控制您的设备。([源代码](https://gitlab.com/fmd-foss/fmd-server), [客户端](https://gitlab.com/fmd-foss/fmd-android)) `GPL-3.0` `Docker/Go`
- [Gladys](https://gladysassistant.com/) - 以隐私优先的家庭助手。([源代码](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs/Docker`
- [Home Assistant](https://home-assistant.io/) - 家庭自动化平台。([演示](https://home-assistant.io/demo/), [源代码](https://github.com/home-assistant/core)) `Apache-2.0` `Python/Docker`
- [ioBroker](https://www.iobroker.net/) - 物联网集成平台,专注于楼宇自动化、智能计量、环境辅助生活、过程自动化、可视化和数据记录。([源代码](https://github.com/ioBroker/ioBroker)) `MIT` `Nodejs`
- [LHA](https://github.com/javalikescript/lha) - 轻量级家庭自动化应用,完全可扩展,使用Blockly、HTML或Lua。它包括ConBee、Philips Hue或Z-Wave JS等扩展。`MIT` `Lua`
- [Node RED](https://nodered.org/) - 基于浏览器的流编辑器,帮助您连接硬件设备、API和在线服务以创建IoT解决方案。([源代码](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs/Docker`
- [Onloc](https://onloc.app) - 实时跟踪和共享您的位置。控制和锁定被盗或丢失的手机。([源代码](https://github.com/onloc-app/onloc-api), [客户端](https://github.com/onloc-app/onloc-android)) `AGPL-3.0` `Docker`
- [openHAB](https://www.openhab.org) - 供应商和技术无关的开源家庭自动化软件。([源代码](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - IoT资产管理、流规则和WHEN-THEN规则、数据可视化、边缘网关。([演示](https://demo.openremote.io/), [源代码](https://github.com/openremote/core)) `AGPL-3.0` `Java`
- [polluSensWeb](https://wespeakenglish.github.io/polluSensWeb/) - 基于Web的串行接口和图表工具,用于可视化和记录UART污染传感器(PM2.5、VOC等)的数据。具有实时数据采集、动态图表、CSV导出和webhook集成功能。([演示](https://wespeakenglish.github.io/polluSensWeb/), [源代码](https://github.com/WeSpeakEnglish/polluSensWeb), [客户端](https://github.com/WeSpeakEnglish/polluSensWeb/releases)) `MIT` `Javascript`
- [SIP Irrigation Control](https://dan-in-ca.github.io/SIP/) - 用于喷灌/灌溉控制的开源软件。([源代码](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [SOLECTRUS](https://solectrus.de) - 光伏仪表板,显示能源生产和消耗以及成本和节省计算。([演示](https://demo.solectrus.de), [源代码](https://github.com/solectrus/solectrus)) `AGPL-3.0` `Docker`
- [Tasmota](https://tasmota.com) - ESP设备的开源固件。完全本地控制,快速设置和更新。使用MQTT、Web UI、HTTP或串行进行控制。使用定时器、规则或脚本进行自动化。与家庭自动化解决方案集成。([源代码](https://github.com/arendst/Tasmota)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - IoT平台 - 设备管理、数据收集、处理和可视化。([演示](https://demo.thingsboard.io/signup), [源代码](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java/Docker/K8S`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings是Web of Things的开源实现,包括WebThings网关和WebThings框架。([源代码](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### 库存管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[库存管理软件](https://zh.wikipedia.org/wiki/库存管理软件)。

_相关: [金钱、预算和管理](#金钱预算和管理), [资源规划](#资源规划)_

_另见: [awesome-sysadmin/IT资产管理](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Cannery](https://cannery.app) - 枪支和弹药追踪应用。([源代码](https://gitlab.com/shibaobun/cannery)) `AGPL-3.0` `Docker`
- [CellarBoss](https://cellarboss.org) - 葡萄酒库存管理系统。([源代码](https://github.com/CellarBoss/cellarboss)) `GPL-3.0` `Docker/Nodejs`
- [DVinyl](https://github.com/Kyonew/DVinyl) `⚠` - 现代化物理媒体(黑胶唱片、CD、磁带、书籍、电影和电子游戏)收藏管理器。`MIT` `Nodejs/Docker`
- [HomeBox (SysAdminsMedia)](https://homebox.software/) - 为家庭用户构建的库存和组织系统。([演示](https://demo.homebox.software/), [源代码](https://github.com/sysadminsmedia/homebox)) `AGPL-3.0` `Docker/Go`
- [Inventaire](https://inventaire.io/welcome) - 协作资源映射项目,目前仅专注于使用wikidata和ISBN探索书籍映射。([源代码](https://codeberg.org/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://docs.inventree.org/en/latest/) - 提供直观的零件管理和库存控制的库存管理系统。([演示](https://inventree.org/demo), [源代码](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Open QuarterMaster](https://openquartermaster.com/) - 强大的库存管理系统,设计为灵活且可扩展。([源代码](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster)) `GPL-3.0` `deb/Docker`
- [Part-DB](https://docs.part-db.de/) - 电子元件的库存管理系统。([演示](https://demo.part-db.de/en/), [源代码](https://github.com/Part-DB/Part-DB-server)) `AGPL-3.0` `Docker/PHP/Nodejs`
- [Spoolman](https://github.com/Donkie/Spoolman) - 跟踪您的3D打印机耗材线轴的库存。`MIT` `Docker/Python`


### 知识管理工具

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[知识管理](https://zh.wikipedia.org/wiki/知识管理)是与创建、共享、使用和管理知识和信息相关的方法集合。

_相关: [笔记和编辑器](#笔记和编辑器), [维基](#维基), [数据库管理](#数据库管理)_

- [Atomic Server](https://atomicserver.eu/) - 具有文档(类似于Notion)、表格、搜索和强大的链接数据API的知识图谱数据库。轻量级、非常快速且无运行时依赖。([演示](https://atomicdata.dev/), [源代码](https://github.com/ontola/atomic-server)) `MIT` `Docker/Rust`
- [Digimindmap](https://ladigitale.dev/digimindmap/#/) - 创建简单的思维导图(法语文档)。([演示](https://ladigitale.dev/digimindmap/#/), [源代码](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- [LibreKB](https://librekb.com/) - 基于Web的知识库解决方案。一个简单的Web应用,几乎可以在任何具有PHP和MySQL的Web服务器或托管提供商上运行。([源代码](https://github.com/michaelstaake/LibreKB/)) `GPL-3.0` `PHP`
- [Marmot](https://marmotdata.io) - 用于发现和整理整个技术栈中数据资产的数据目录,包括数据库、API、消息队列和管道。([演示](https://demo.marmotdata.io), [源代码](https://github.com/marmotdata/marmot)) `MIT` `Docker`
- [memEx](https://memex-app.shibao.dev) - 结构化的个人知识库,受zettlekasten和org-mode启发。([源代码](https://gitlab.com/shibaobun/memex)) `AGPL-3.0` `Docker`
- [SiYuan](https://b3log.org/siyuan/) - 以隐私优先的个人知识管理软件,用typescript和golang编写。([源代码](https://github.com/siyuan-note/siyuan)) `AGPL-3.0` `Docker/Go`
- [TeamMapper](https://github.com/b310-digital/teammapper) - 托管和创建您自己的思维导图。与您的团队共享您的思维导图会话并实时协作思维导图。([演示](https://map.kits.blog)) `MIT` `Docker/Nodejs`


### 学习和课程

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

有助于教育和学习的工具和软件。

- [Canvas LMS](https://www.instructure.com/canvas/) - 正在彻底改变我们教育方式的学习管理系统(LMS)。([源代码](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - 创建虚拟校园以提供在线或半在线培训。([源代码](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 用于课堂的交互式白板/壁纸,面对面或远程(法语文档)。([演示](https://ladigitale.dev/digiscreen/), [源代码](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- [Digitools](https://ladigitale.dev/digitools) - 一套简单的工具,用于辅助面对面或远程的课程动画。(法语文档)。([演示](https://ladigitale.dev/digitools/), [源代码](https://codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- [edX](https://www.edx.org/) - 为edx.org网站提供动力的在线学习平台。([源代码](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://gibbonedu.org/) - 灵活的学校管理平台,旨在让教师、学生、家长和领导者的生活更美好。([源代码](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [Helium](https://www.heliumedu.com) - 颜色编码的学生计划器,用于课程、作业、成绩和笔记,具有智能通知和多设备同步功能。([演示](https://app.heliumedu.com), [源代码](https://github.com/HeliumEdu/platform)) `MIT` `Python/Docker`
- [ILIAS](https://www.ilias.de) - 可以应对任何挑战的学习管理系统。([演示](https://demo.ilias.de), [源代码](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [INGInious](https://inginious.org/?lang=en) - 智能评分系统,允许安全且自动地测试学生编写的代码。([源代码](https://github.com/INGInious/INGInious), [客户端](https://github.com/INGInious/plugins)) `AGPL-3.0` `Python/Docker`
- [Moodle](https://moodle.org/) - 拥有全球最大开源社区之一的学习和课程平台。([演示](https://moodle.org/demo/), [源代码](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass是一种高级电子学习解决方案,可以增强教学和学习过程。([演示](https://demo.openeclass.org/), [源代码](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - 用于教学、教育、评估和沟通的学习管理系统。([演示](https://learn.olat.com), [源代码](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [QST](https://qstonline.org) - 在线评估软件。从手机上的快速测验到大规模、高风险、监考的桌面测试,简单、安全且经济。([演示](https://qstonline.org/free_account.htm), [源代码](https://sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- [RELATE](https://documen.tician.de/relate/) - 课程包,包括以下功能:灵活的规则、统计信息、多课程支持、班级日历。([源代码](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - 用于学校管理的学生信息系统。功能包括学生人口统计、成绩、排课、出勤、学生计费、纪律和餐饮服务模块。([演示](https://www.rosariosis.org/demo/), [源代码](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`


### 制造业

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于管理[3D打印机](https://zh.wikipedia.org/wiki/3D打印)、[CNC机床](https://zh.wikipedia.org/wiki/数控机床)和其他物理制造工具的软件。

- [CNCjs](https://cnc.js.org/) - 运行Grbl、Smoothieware或TinyG的CNC铣床控制器的Web界面。([源代码](https://github.com/cncjs/cncjs/)) `MIT` `Nodejs`
- [Fluidd](https://docs.fluidd.xyz/) - 3D打印机固件Klipper的轻量级响应式用户界面。([源代码](https://github.com/fluidd-core/fluidd)) `GPL-3.0` `Docker/Nodejs`
- [LinuxCNC](https://www.linuxcnc.org/) - 基于Linux的CNC机床控制器。它可以驱动铣床、车床、3D打印机、激光切割机、等离子切割机、机械臂、六足机器人等。([源代码](https://github.com/LinuxCNC/linuxcnc)) `GPL-2.0/LGPL-3.0` `C/deb`
- [Mainsail](https://docs.mainsail.xyz/) - Klipper 3D打印机固件的现代响应式用户界面。从任何设备从任何地方控制和监控您的打印机。([源代码](https://github.com/mainsail-crew/mainsail)) `GPL-3.0` `Docker/Python`
- [Manyfold](https://manyfold.app) - 3D打印文件的数字资产管理器;STL、OBJ、3MF等。([源代码](https://github.com/manyfold3d/manyfold)) `MIT` `Docker`
- [Octoprint](https://octoprint.org/) - 用于控制消费级3D打印机的简洁Web界面。([源代码](https://github.com/OctoPrint/OctoPrint)) `AGPL-3.0` `Docker/Python`


### 地图和全球定位系统(GPS)

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[地图](https://zh.wikipedia.org/wiki/地图)、[制图学](https://zh.wikipedia.org/wiki/制图学)、[GIS](https://zh.wikipedia.org/wiki/地理信息系统)和[GPS](https://zh.wikipedia.org/wiki/全球定位系统)软件。

_相关: [旅行组织](#旅行组织)_

_另见: [awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap), [awesome-gis](https://github.com/sshuair/awesome-gis)_

- [AdventureLog](https://adventurelog.app) - 旅行追踪器和行程规划器。([演示](https://demo.adventurelog.app/signup), [源代码](https://github.com/seanmorley15/AdventureLog)) `GPL-3.0` `Docker`
- [AirTrail](https://airtrail.johan.ohly.dk) - 个人飞行跟踪系统。([源代码](https://github.com/johanohly/AirTrail)) `GPL-3.0` `Docker/Nodejs`
- [Bicimon](https://github.com/knrdl/bicimon) - 作为渐进式Web应用的自行车速度计。([演示](https://knrdl.github.io/bicimon/)) `MIT` `Javascript`
- [Dawarich](https://dawarich.app/) - 可视化您的位置历史,跟踪您的移动,并以完全隐私和控制分析您的旅行模式(Google时间线即Google位置历史的替代品)。([源代码](https://github.com/Freika/dawarich)) `AGPL-3.0` `Docker`
- [Geo2tz](https://github.com/noandrea/geo2tz) - 从地理坐标(纬度、经度)获取时区。`MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 使用OpenStreetMap的快速路由库和服务器。([源代码](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [NextGIS Web](https://nextgis.com/nextgis-web/) - 用于地理空间数据管理、Web地图发布和以QGIS为中心的协作工作流的Web GIS服务器。([演示](https://sandbox.nextgis.com), [源代码](https://github.com/nextgis/nextgisweb)) `GPL-3.0` `Docker`
- [Nominatim](https://nominatim.org/) - 用于OpenStreetMap数据的地理编码(地址->坐标)和反向地理编码(坐标->地址)服务器应用程序。([源代码](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - 高性能路由引擎,设计为在OpenStreetMap数据上运行,提供HTTP API、C++库接口和Nodejs包装器。([演示](https://map.project-osrm.org/), [源代码](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenRouteService](https://openrouteservice.org/) - 具有方向、等时线、时间距离矩阵、路线优化等的路线服务。([演示](https://openrouteservice.org/dev/#/api-docs/introduction), [源代码](https://github.com/GIScience/openrouteservice)) `GPL-3.0` `Docker/Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 创建可自由编辑的世界地图的协作项目。([源代码](https://github.com/openstreetmap/openstreetmap-website), [客户端](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基于OpenStreetMap数据的多模态行程规划软件,使用已发布的GTFS格式数据来建议使用本地公共交通系统的路线。([源代码](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - 存储和访问由[OwnTracks](https://owntracks.org/)位置跟踪应用发布的数据。`GPL-2.0` `C/Lua/deb/Docker`
- [TileServer GL](https://tileserver.readthedocs.io/) - 具有GL样式的矢量和栅格地图。通过Mapbox GL Native进行服务器端渲染。适用于Mapbox GL JS、Android、iOS、Leaflet、OpenLayers、通过WMTS进行GIS等的地图瓦片服务器。([源代码](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs/Docker`
- [Traccar](https://www.traccar.org/) - 跟踪GPS位置的Java应用。支持大量跟踪设备和协议,具有Android和iOS应用。具有查看您旅行的Web界面。([演示](https://demo.traccar.org/), [源代码](https://github.com/traccar)) `Apache-2.0` `Java`
- [TRIP](https://itskovacs-trip.netlify.app/) - 极简主义POI地图跟踪器和行程规划器。([演示](https://itskovacs-trip.netlify.app/home), [源代码](https://github.com/itskovacs/trip)) `MIT` `Docker`
- [wanderer](https://github.com/open-wanderer/wanderer) - 轨迹数据库,您可以上传记录的轨迹或创建新轨迹并添加各种元数据以构建易于搜索的目录。([演示](https://demo.wanderer.to)) `AGPL-3.0` `Docker/Go/Nodejs`


### 媒体管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[数字媒体](https://zh.wikipedia.org/wiki/数字媒体)管理工具和软件。

_相关: [自动化](#自动化), [媒体流媒体](#媒体流媒体), [媒体流媒体 - 音频流媒体](#媒体流媒体---音频流媒体), [媒体流媒体 - 多媒体流媒体](#媒体流媒体---多媒体流媒体), [媒体流媒体 - 视频流媒体](#媒体流媒体---视频流媒体), [媒体管理](#媒体管理)_

- [ChannelTube](https://github.com/TheWicklowWolf/ChannelTube) `⚠` - 通过yt-dlp按计划从YouTube频道下载视频或音频。`AGPL-3.0` `Docker`
- [Deleterr](https://github.com/rfsbraz/deleterr) - 自动化媒体清理工具,根据可配置规则从Plex、Sonarr和Radarr中删除已观看和过时的内容。`MIT` `Docker`
- [Downtify](https://downtify.henriquesebastiao.com) `⚠` - 下载带有专辑封面和元数据的Spotify音乐。([源代码](https://github.com/henriquesebastiao/downtify)) `GPL-3.0` `Docker`
- [Elengrab](https://github.com/neosy/elengrab) - 快速跨平台视频和音频下载器和媒体查看器,具有灵活的格式和质量选项。支持1000+网站,包括YouTube、Instagram、TikTok、Twitch等。([演示](https://elengrab.n-hub.ru)) `AGPL-3.0` `Go/Docker`
- [HomeTube](https://hometube.latentnoise.dev) `⚠` - Web UI,用于从1700+个站点将视频和播放列表下载到Plex或Jellyfin库中,具有质量选择、SponsorBlock赞助商移除、字幕、片段剪辑和弹性播放列表同步功能。([源代码](https://github.com/EgalitarianMonkey/hometube)) `AGPL-3.0` `Python/Docker`
- [Houndarr](https://av1155.github.io/houndarr/) - Radarr、Sonarr、Lidarr、Readarr和Whisparr的计划积压搜索。通过缺失和未达到截止日期的项目以小批量速率限制批次处理,每个项目都有冷却时间和每小时上限,以避免使索引器过载。([源代码](https://github.com/av1155/houndarr)) `AGPL-3.0` `Python/Docker`
- [Lidarr](https://lidarr.audio/) - 面向Usenet和BitTorrent用户的音乐收藏管理器。([源代码](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#/Docker`
- [LidaTube](https://github.com/TheWicklowWolf/LidaTube) `⚠` - 通过yt-dlp查找和获取缺少的Lidarr专辑。`GPL-3.0` `Docker`
- [Lidify](https://github.com/TheWicklowWolf/Lidify) `⚠` - 音乐发现工具,根据选定的Lidarr艺术家提供推荐,使用Spotify或LastFM。`MIT` `Docker`
- [Lingarr](https://lingarr.com) - 自动翻译Radarr和Sonarr媒体库中的字幕文件,使用LibreTranslate、本地AI模型或SaaS翻译服务。([源代码](https://github.com/lingarr-translate/lingarr)) `AGPL-3.0` `Docker`
- [Medusa](https://github.com/pymedusa/Medusa) - 电视剧的自动视频库管理器。它监视您喜欢的新剧集,当它们发布时会发挥其魔力。([客户端](https://github.com/medusajs/nextjs-starter-medusa)) `GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - youtube-dl的Web GUI,支持播放列表。允许从数十个网站下载视频。`AGPL-3.0` `Python/Nodejs/Docker`
- [MKVPriority](https://github.com/kennethsible/mkvpriority) - 使用可配置的优先级分数选择首选音频和字幕轨道,并设置适当的默认和强制标志。`MIT` `Python/Docker`
- [MyTube](https://github.com/franklioxygen/MyTube) `⚠` - yt-dlp支持的网站的下载器和播放器,具有频道订阅、云上传支持和本地库组织功能。([演示](https://mytube-demo.vercel.app)) `MIT` `Nodejs/Docker`
- [nefarious](https://lardbit.github.io/nefarious/) - 自动下载电影和电视剧。([源代码](https://github.com/lardbit/nefarious)) `GPL-3.0` `Python`
- [Ombi](https://ombi.io/) - Plex/Emby的内容请求系统,连接到SickRage、CouchPotato、Sonarr,具有不断增长的功能集。([演示](https://app.ombi.io/), [源代码](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#/deb`
- [Pinchflat](https://github.com/kieraneglin/pinchflat) `⚠` - 使用yt-dlp下载YouTube内容。`AGPL-3.0` `Docker`
- [PodFetch](https://samtv12345.github.io/PodFetch) - 时髦高效的播客下载器。([源代码](https://github.com/SamTV12345/PodFetch)) `Apache-2.0` `Docker/Rust`
- [Radarr](https://radarr.video/) - 通过Usenet和BitTorrent自动下载电影(Sonarr的分支)。([源代码](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#/Docker`
- [Ratelog](https://ratelog.org) - 电影追踪器和评分应用(Letterboxd的替代品)。([源代码](https://github.com/golmenero/ratelog)) `AGPL-3.0` `Docker`
- [Reaparr](https://www.reaparr.rocks/) `⚠` - 跨平台Plex媒体下载器,无缝地将其他Plex服务器的媒体添加到您自己的服务器。([源代码](https://github.com/Reaparr/Reaparr)) `GPL-3.0` `Docker`
- [Seerr](https://github.com/seerr-team/seerr) - 管理您的媒体库的请求,支持Plex、Jellyfin和Emby媒体服务器(Overseerr的分支)。`MIT` `Docker/Nodejs`
- [Sonarr](https://sonarr.tv/) - 面向Usenet和BitTorrent的自动电视剧下载器和管理器。它可以抓取、排序和重命名新剧集,并在更好的质量格式可用时自动升级已下载文件的质量。([源代码](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#/Docker`
- [TrackWatch](https://trackwatch.emlopezr.com) `⚠` - Spotify的自动音乐发布追踪器,具有电子邮件通知、唱片目录生成器和幽灵曲目清理功能(Release Radar的替代品)。([源代码](https://github.com/emlopezr/trackwatch)) `MIT` `Docker`
- [tubesync](https://github.com/meeb/tubesync) `⚠` - 将YouTube频道和播放列表同步到本地托管的媒体服务器。`AGPL-3.0` `Docker/Python`
- [Watcharr](https://github.com/sbondCo/Watcharr) - 添加和跟踪您正在观看的所有节目和电影。具有用户认证、现代简洁的UI和非常简单的设置。`MIT` `Docker`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 简单的youtube-dl REST API,用于在远程服务器上启动下载。`GPL-3.0` `Python`
- [Youtarr](https://github.com/DialmasterOrg/Youtarr) `⚠` - 通过yt-dlp按计划从YouTube频道下载视频,具有用于浏览和选择性下载视频的Web UI。与Plex Media Server集成,并为Jellyfin、Kodi和Emby生成NFO元数据。`ISC` `Docker`
- [youtube-dl-nas](https://hyeonsangjeon.github.io/youtube-dl-nas/) `⚠` - 经过身份验证的yt-dlp下载队列,用于视频、音频和字幕,具有历史记录、移动共享和NAS文件管理功能(youtube-dl-server的分支)。([源代码](https://github.com/hyeonsangjeon/youtube-dl-nas)) `MIT` `Python/Docker`
- [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server) - Youtube-DL的Web和REST接口,用于将视频下载到服务器上。`MIT` `Python/Docker`


### 媒体流媒体

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[流媒体](https://zh.wikipedia.org/wiki/流媒体)是一种以连续方式从源端传输和消费的多媒体形式,在网络元素中几乎没有或完全没有中间存储。

**请访问 [媒体流媒体 - 音频流媒体](#媒体流媒体---音频流媒体), [媒体流媒体 - 多媒体流媒体](#媒体流媒体---多媒体流媒体), [媒体流媒体 - 视频流媒体](#媒体流媒体---视频流媒体), [媒体管理](#媒体管理)**

_相关: [媒体流媒体](#媒体流媒体)_

_另见: [流媒体系统列表 - Wikipedia](https://en.wikipedia.org/wiki/List_of_streaming_media_systems), [流媒体系统比较 - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_


### 媒体流媒体 - 音频流媒体

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[音频](https://zh.wikipedia.org/wiki/音频)流媒体工具和软件。

_相关: [媒体管理](#媒体管理)_

- [Ampache](https://ampache.org/) - 基于Web的音频/视频流媒体应用程序。([演示](https://play.dogmazic.net/), [源代码](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audiobookshelf](https://www.audiobookshelf.org/) - 有声书和播客服务器。它可以流式传输所有音频格式,保持并在设备间同步播放进度。提供Android和iOS应用。([源代码](https://github.com/advplyr/audiobookshelf), [客户端](https://github.com/advplyr/audiobookshelf-app)) `GPL-3.0` `Docker/deb/Nodejs`
- [Audioserve](https://github.com/izderadicka/audioserve) - 简单的个人服务器,用于提供目录中的音频文件(有声书、音乐、播客等)。专注于简单性,支持客户端之间的播放位置同步。`MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - 现代且易于访问的网络电台管理套件。([源代码](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `Docker`
- [Beets](https://beets.io/) - 音乐库管理器和MusicBrainz标签工具(命令行和Web界面)。([源代码](https://github.com/beetbox/beets)) `MIT` `Python/deb`
- [Black Candy](https://github.com/blackcandy-org/blackcandy) - 音乐流媒体服务器。`MIT` `Docker/Ruby`
- [BotWave](https://botwave.dpip.lol) - 具有服务器-客户端架构的FM广播系统,用于远程管理多个树莓派发射器。([源代码](https://github.com/dpipstudio/botwave)) `GPL-3.0` `Python`
- [Funkwhale](https://dev.funkwhale.audio/funkwhale) - 现代的、基于Web的、友好的、多用户且免费的音乐服务器。`BSD-3-Clause` `Python`
- [gonic](https://github.com/sentriz/gonic) - 轻量级音乐流媒体服务器。兼容Subsonic。`GPL-3.0` `Go/Docker`
- [koel](https://koel.dev/) - 可以工作的个人音乐流媒体服务器。([演示](https://demo.koel.dev/), [源代码](https://github.com/koel/koel)) `MIT` `PHP`
- [LibreTime](https://libretime.org) - 在网络上进行广播流媒体电台([Airtime](https://github.com/sourcefabric/Airtime)的分支)。([源代码](https://github.com/LibreTime/libretime)) `AGPL-3.0` `Docker/PHP`
- [LMS](https://github.com/epoupon/lms) - 使用Web界面访问您自托管的音乐。`GPL-3.0` `Docker/deb/C++`
- [Lyrion Music Server](https://lyrion.org/) - 控制各种Squeezebox/Slim Devices音频播放器和兼容硬件的服务器软件(前身为Logitech Media Server)。([源代码](https://github.com/lms-community/slimserver), [客户端](https://lyrion.org/extensions/applications/)) `GPL-2.0` `deb/Docker/Perl`
- [moOde Audio](https://moodeaudio.org/) - 为美妙的树莓派单板电脑系列提供的发烧级质量音乐播放。([源代码](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Mopidy](https://docs.mopidy.com/) `⚠` - 可扩展的音乐服务器。提供mpd API的超集,以及与Spotify、SoundCloud等第三方服务的集成。([源代码](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python/deb`
- [mpd](https://www.musicpd.org/) - 用于远程播放音乐、流式传输音乐、处理和组织播放列表的守护进程。有许多客户端可用。([源代码](https://github.com/MusicPlayerDaemon/MPD), [客户端](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 具有GUI管理工具的音乐流媒体服务器。在Mac、Windows和Linux上运行。([源代码](https://github.com/IrosTheBeggar/mStream)) `GPL-3.0` `Nodejs`
- [multi-scrobbler](https://foxxmd.github.io/multi-scrobbler) - 从多个来源将播放记录到多个scrobbling服务。([源代码](https://github.com/FoxxMD/multi-scrobbler)) `MIT` `Nodejs/Docker`
- [musikcube](https://github.com/clangen/musikcube) - 流式音频服务器,具有Linux/macOS/Windows/Android客户端。`BSD-3-Clause` `C++/deb`
- [Navidrome Music Server](https://www.navidrome.org) - 现代音乐服务器和流媒体器,兼容Subsonic/Airsonic。([演示](https://www.navidrome.org/demo), [源代码](https://github.com/navidrome/navidrome), [客户端](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- [Pinepods](https://www.pinepods.online/) - 支持多用户的播客管理系统。Pinepods使用中央数据库,因此收听时间和主题等设置可以在设备间同步。([演示](https://try.pinepods.online), [源代码](https://github.com/madeofpendletonwool/PinePods)) `GPL-3.0` `Docker`
- [Polaris](https://github.com/agersant/polaris) - 针对大型音乐集合优化的音乐浏览和流媒体应用程序,易于使用且高性能。`MIT` `Rust/Docker`
- [Snapcast](https://github.com/snapcast/snapcast) - 同步多房间音频服务器。`GPL-3.0` `C++/deb`
- [Stretto](https://github.com/benkaiser/stretto) `⚠` - 具有YouTube/Soundcloud导入和iTunes/Spotify发现功能的音乐播放器。([演示](https://next.kaiserapps.com), [客户端](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic服务器API的Python实现。`AGPL-3.0` `Python/deb`
- [SwingMusic](https://swingmusic.vercel.app/) - Swing Music是一个漂亮的、自托管的音乐播放器和流媒体服务器,用于您的本地音频文件。就像更酷的Spotify......但是需要您自己带音乐。([源代码](https://github.com/swingmx/swingmusic)) `MIT` `Python/Docker`
- [vod2pod-rss](https://github.com/madiele/vod2pod-rss) `⚠` - 将YouTube和Twitch频道转换为播客,无需存储。即时将VoD转码为MP3 192k,生成可在播客客户端中使用的RSS feed。`MIT` `Docker`


### 媒体流媒体 - 多媒体流媒体

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[多媒体](https://zh.wikipedia.org/wiki/多媒体)流媒体工具和软件。

_相关: [媒体流媒体 - 视频流媒体](#媒体流媒体---视频流媒体), [媒体流媒体 - 音频流媒体](#媒体流媒体---音频流媒体), [媒体管理](#媒体管理)_

- [ClipBucket](https://clipbucket.fr/) - 在几分钟内启动您自己的视频分享网站(YouTube/Netflix克隆)。([演示](https://demo.clipbucket.oxygenz.fr/), [源代码](https://github.com/MacWarrior/clipbucket-v5)) `AAL` `Docker/PHP`
- [cmyflix](https://github.com/farfalleflickan/cmyflix) - 极简主义的Plex/Jellyfin替代品,用于流式传输视频。`AGPL-3.0` `C/deb`
- [Gerbera](https://gerbera.io/) - UPnP媒体服务器,允许您在整个家庭网络中流式传输您的数字媒体,并在各种UPnP兼容设备上收听/观看。([源代码](https://github.com/gerbera/gerbera)) `GPL-2.0` `Docker/deb/C++`
- [Icecast 2](https://icecast.org) - 流式音频/视频服务器,可用于创建互联网电台或私人运行的点唱机以及介于两者之间的许多其他用途。([源代码](https://gitlab.xiph.org/xiph/icecast-server), [客户端](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 用于音频、视频、书籍、漫画和照片的媒体服务器,具有时尚的界面和强大的转码能力。几乎所有现代平台都有客户端,包括Roku、Android TV、iOS和Kodi。([演示](https://demo.jellyfin.org/stable), [源代码](https://github.com/jellyfin/jellyfin), [客户端](https://github.com/awesome-jellyfin/awesome-jellyfin)) `GPL-2.0` `C#/deb/Docker`
- [Karaoke Eternal](https://www.karaoke-eternal.com) - 托管很棒的卡拉OK派对,每个人都可以轻松地从手机浏览器中找到并排队歌曲。播放器也是完全基于浏览器的,支持MP3+G、MP4和WebGL可视化。([源代码](https://github.com/bhj/KaraokeEternal)) `ISC` `Docker/Nodejs`
- [Kodi](https://kodi.tv/) - 多媒体/娱乐中心,前身为XBMC。运行在Android、BSD、Linux、macOS、iOS和Windows上。([源代码](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++/deb`
- [Kyoo](https://github.com/zoriya/kyoo) - 创新的媒体浏览器,专为动漫、系列和电影的无缝流媒体而设计,提供动态转码、自动观看历史记录和智能元数据检索等高级功能。([演示](https://kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- [MediaMTX](https://mediamtx.org) - 即用型、零依赖的实时媒体服务器和代理,用于通过SRT、WebRTC、RTSP、RTMP、HLS、MPEG-TS、RTP发布、读取、录制、回放和路由视频/音频流。([源代码](https://github.com/bluenviron/mediamtx), [客户端](https://mediamtx.org/docs/kickoff/introduction)) `MIT` `Go/Docker`
- [Meelo](https://github.com/Arthi-chaud/Meelo) - 个人音乐服务器,为收藏家和音乐狂热者设计。`GPL-3.0` `Docker`
- [MistServer](https://mistserver.org/) - 公共领域流媒体服务器,适用于任何设备和任何格式。([源代码](https://github.com/DDVTECH/mistserver)) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - 将您选择的Linux兼容硬件转变为电视或有源扬声器的音频和视频源(Chromecast的替代品)。([源代码](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Rygel](https://gnome.pages.gitlab.gnome.org/rygel/) - UPnP AV MediaServer,允许您轻松共享音频、视频和图片。媒体播放器软件可以使用Rygel成为MediaRenderer,可以由UPnP或DLNA控制器远程控制。([源代码](https://gitlab.gnome.org/GNOME/rygel/)) `LGPL-2.1` `C`
- [Stash](https://stashapp.cc) - 基于Web的成人媒体库组织器和播放器,支持自动标记和元数据抓取。([源代码](https://github.com/stashapp/stash)) `AGPL-3.0` `Docker/Go`
- [µStreamer](https://github.com/pikvm/ustreamer) - 轻量级且非常快速的服务器,用于将任何V4L2设备的MJPEG视频流式传输到网络。`GPL-3.0` `C/deb`
- [üWave](https://u-wave.net/) `⚠` - 自托管的协作聆听平台。用户轮流播放来自各种媒体源(如YouTube和SoundCloud)的媒体——歌曲、谈话、游戏视频或其他任何内容。([演示](https://wlk.yt/), [源代码](https://github.com/u-wave)) `MIT` `Nodejs`


### 媒体流媒体 - 视频流媒体

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[视频](https://zh.wikipedia.org/wiki/视频)流媒体工具和软件。

_相关: [视频监控](#视频监控), [媒体流媒体 - 多媒体流媒体](#媒体流媒体---多媒体流媒体), [照片画廊](#照片画廊), [媒体管理](#媒体管理)_

- [CyTube](https://github.com/calzoneman/sync) - 同步任意数量的频道的媒体、聊天等。([演示](https://cytu.be)) `MIT` `Nodejs`
- [Invidious](https://github.com/iv-org/invidious) `⚠` - YouTube的替代前端。([演示](https://docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- [MediaCMS](https://mediacms.io) - 现代、功能齐全的开源视频和媒体CMS,使用Python/Django/React编写,具有REST API。([源代码](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [OvenMediaEngine](https://github.com/OvenMediaLabs/OvenMediaEngine) - 具有亚秒级延迟的流媒体服务器。([演示](https://demo.ovenplayer.com)) `AGPL-3.0` `C++/Docker`
- [Owncast](https://owncast.online/) - 去中心化的单用户实时视频流媒体和聊天服务器,用于运行您自己的直播流,风格类似于主流大平台选项。([源代码](https://github.com/owncast/owncast)) `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - 使用P2P(BitTorrent)直接在Web浏览器中的去中心化视频流媒体平台。([源代码](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 视频流服务/ torrent客户端,允许在浏览器或Chromecast/AppleTV/智能电视上搜索和播放torrent中的视频。`MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - 无需流媒体提供商即可在您的网站上访问H.264实时视频流。([源代码](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [SRS](https://ossrs.io/) - 一个简单、高效和实时的视频服务器,支持RTMP、WebRTC、HLS、HTTP-FLV和SRT。([源代码](https://github.com/ossrs/srs)) `MIT` `Docker/C++`
- [SyncTube](https://github.com/RblSb/SyncTube) - 轻量级且非常简单的CyTube替代品,用于与朋友一起观看视频和聊天。`MIT` `Nodejs/Haxe`
- [Tiramisu](https://github.com/MrRobotoGit/tiramisu) - 具有FUSE虚拟文件系统的BitTorrent引擎,可以将torrent实时流式传输到Plex/Jellyfin而无需下载(Real-Debrid的替代品)。`GPL-2.0` `Go/Docker`
- [Tube Archivist](https://tubearchivist.com/) `⚠` - 组织、搜索和享受您的YouTube收藏集。订阅、下载和跟踪已查看的内容,具有元数据索引和用户友好的界面。([源代码](https://github.com/tubearchivist/tubearchivist), [客户端](https://docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- [Tube](https://git.mills.io/prologic/tube) - 类似YouTube(_没有审查和您不需要的功能!_)的视频分享应用,使用Go编写,还支持自动转码为MP4 H.265 AAC、多个收藏集和RSS feed。`MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 跨平台多媒体播放器客户端和服务器,支持大多数多媒体文件以及DVD、Audio CD、VCD和各种流媒体协议。([源代码](https://code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`


### 杂项

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

不适合放在其他部分的软件。

- [2FAuth](https://github.com/Bubka/2FAuth) - 管理您的双因素认证(2FA)账户并生成其安全码。([演示](https://demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- [Anchr](https://anchr.io) - 用于互联网小任务的工具箱,包括书签收集、URL缩短和(加密)图片上传。([源代码](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [Anubis](https://anubis.techaro.lol/) - Web AI防火墙实用程序,保护上游资源免受爬虫机器人侵害。([源代码](https://github.com/TecharoHQ/anubis)) `MIT` `Docker/deb/Go`
- [asciinema](https://asciinema.org/) - 用于托管asciicast的Web应用。([演示](https://asciinema.org/explore), [源代码](https://github.com/asciinema/asciinema-server)) `Apache-2.0` `Elixir/Docker`
- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 帮助照顾者跟踪婴儿睡眠、喂食、换尿布和俯卧时间。([演示](https://github.com/babybuddy/babybuddy#-demo)) `BSD-2-Clause` `Python`
- [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade) - 即时跨多个设备同步剪贴板,无需任何按钮按下。适用于Windows、macOS、Linux和Android,提供无缝且安全的剪贴板共享,具有端到端数据加密功能。`GPL-3.0` `Java/Docker`
- [Cloudlog](https://magicbug.co.uk/cloudlog/) - 在任何地方记录您的业余无线电联系。([源代码](https://github.com/magicbug/cloudlog)) `MIT` `PHP/Docker`
- [ConvertX](https://github.com/C4illin/ConvertX) - 在线文件转换器,支持一千多种不同格式。`AGPL-3.0` `Docker`
- [CUPS](https://www.cups.org/) - 通用Unix打印系统使用互联网打印协议(IPP)支持打印到本地和网络打印机。([源代码](https://github.com/OpenPrinting/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - 在Web浏览器中执行各种操作,如AES、DES和Blowfish加密和解密、创建十六进制转储、计算哈希值等等。([演示](https://gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- [Digiboard](https://digiboard.app/) - 创建协作白板(法语文档)。([源代码](https://codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Nodejs`
- [Digicard](https://codeberg.org/ladigitale/digicard) - 创建简单的图形组合(法语文档)。([演示](https://ladigitale.dev/digicard/)) `AGPL-3.0` `Nodejs`
- [Digicut](https://ladigitale.dev/digicut/) - 使用FFMPEG.wasm剪切音频和视频文件(法语文档)。([源代码](https://codeberg.org/ladigitale/digicut)) `AGPL-3.0` `Nodejs`
- [Digiface](https://ladigitale.dev/digiface/) - 使用Avataaars库创建头像(法语文档)。([演示](https://ladigitale.dev/digiface/), [源代码](https://codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Nodejs`
- [Digiflashcards](https://ladigitale.dev/digiflashcards/) - 创建闪卡在线应用(法语文档)。([源代码](https://codeberg.org/ladigitale/digiflashcards)) `AGPL-3.0` `Nodejs/PHP`
- [Digimerge](https://ladigitale.dev/digimerge/) - 直接在浏览器中组装音频和视频文件(法语文档)。([演示](https://ladigitale.dev/digimerge/), [源代码](https://codeberg.org/ladigitale/Digimerge)) `AGPL-3.0` `Nodejs`
- [Digiquiz](https://ladigitale.dev/digiquiz/) - 发布使用H5P创建的内容的在线应用(法语文档)。([源代码](https://codeberg.org/ladigitale/digiquiz)) `AGPL-3.0` `Nodejs`
- [Digiread](https://ladigitale.dev/digiread/) `⚠` - 使用Mozilla的Readability清理在线页面和文章(法语文档)。([源代码](https://codeberg.org/ladigitale/digiread)) `AGPL-3.0` `Nodejs/PHP`
- [Digisteps](https://ladigitale.dev/digisteps/) - 创建在线教育路径的简单应用(法语文档)。([源代码](https://codeberg.org/ladigitale/digisteps)) `AGPL-3.0` `Nodejs/PHP`
- [Digitranscode](https://ladigitale.dev/digitranscode) - 直接在浏览器中转换音频文件和视频(法语文档)。([演示](https://ladigitale.dev/digitranscode), [源代码](https://codeberg.org/ladigitale/digitranscode)) `AGPL-3.0` `Nodejs`
- [Digiview](https://ladigitale.dev/digiview/) `⚠` - 在无干扰界面中观看YouTube视频(法语文档)。([演示](https://ladigitale.dev/digiview/), [源代码](https://codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Nodejs/PHP`
- [Digiwords](https://ladigitale.dev/digiwords/) - 创建词云的简单在线应用(法语文档)。([源代码](https://codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Nodejs/PHP`
- [DOCAT](https://github.com/docat-org/docat) - 托管您的文档。简单。版本化。精美。`MIT` `Python/Docker`
- [Domain Locker](https://domain-locker.com) - 域名投资组合管理和追踪器。([演示](https://demo.domain-locker.com), [源代码](https://github.com/lissy93/domain-locker)) `MIT` `Deno/Docker`
- [DOMJudge](https://www.domjudge.org/) - 用于运行编程竞赛的系统,如ICPC区域赛和世界锦标赛编程竞赛。([演示](https://www.domjudge.org/demo), [源代码](https://github.com/DOMjudge/domjudge)) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- [ESMira](https://esmira.kl.ac.at) - 进行纵向研究(ESM、AA、EMA),数据收集和与参与者的通信完全匿名。([演示](https://demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), [源代码](https://github.com/KL-Psychological-Methodology/ESMira)) `AGPL-3.0` `PHP`
- [F-Droid](https://f-droid.org) - 用于维护F-Droid仓库系统的服务器工具。([源代码](https://gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- [Flyimg](https://flyimg.io) - 即时调整大小和裁剪图像。使用ImageMagick获取经过MozJPEG、WebP或PNG优化的图像,具有高效的缓存系统。([演示](https://demo.flyimg.io), [源代码](https://github.com/flyimg/flyimg)) `MIT` `Docker`
- [Garlic-Hub](https://garlic-signage.com/garlic-hub/) - 具有SMIL播放列表支持和调度的数字标牌设备和内容管理系统。([源代码](https://github.com/garlic-signage/garlic-hub)) `AGPL-3.0` `Docker`
- [Geeftlist](https://codeberg.org/nanawel/geeftlist) - 用于在朋友和家人之间管理、分享和预订礼物的协作平台。`GPL-3.0` `Docker`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - 自托管Google字体的无忧方式。获取eot、ttf、svg、woff和woff2文件+ CSS片段。([演示](https://gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- [Habitica](https://habitica.com/) - 将您的目标视为角色扮演游戏的习惯追踪应用。([源代码](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- [HortusFox](https://hortusfox.github.io) - 为植物爱好者设计的协作植物管理和跟踪系统。([源代码](https://github.com/danielbrendel/hortusfox-web)) `MIT` `PHP/Docker`
- [ImgCompress](https://imgcompress.karimzouine.com) - 完全在Docker中运行的图像处理工具。压缩、转换、调整大小、批量处理图像,并使用本地AI去除背景,无需云依赖。([源代码](https://github.com/karimz1/imgcompress)) `GPL-3.0` `Docker`
- [Infisical Community Edition](https://infisical.com/) - 用于密钥、证书和特权访问管理的平台。([源代码](https://github.com/Infisical/infisical)) `MIT` `Docker/K8S/deb`
- [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV) `⚠` - 屏蔽和跳过赞助商,同时静音和跳过YouTube上的广告。`GPL-3.0` `Docker/Python`
- [IT-Tools by sharevb](https://github.com/sharevb/it-tools) - 开发人员实用的在线工具集合([it-tools](https://github.com/CorentinTh/it-tools)的分支)。([演示](https://sharevb-it-tools.vercel.app/)) `GPL-3.0` `Docker`
- [Jelu](https://bayang.github.io/jelu-web) - 已读和待读书籍追踪器。([源代码](https://github.com/bayang/jelu)) `MIT` `Java/Docker`
- [jetlog](https://github.com/pbogre/jetlog) - 个人飞行追踪器和查看器。`GPL-2.0` `Docker`
- [Kasm Workspaces](https://kasmweb.com/) - 将容器化应用和桌面流式传输给最终用户。示例包括浏览器中的Ubuntu,或者仅仅是单个应用,如Chrome、OpenOffice、Gimp、Filezilla等。([演示](https://www.kasmweb.com/#demo), [源代码](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- [Koillection](https://koillection.github.io/) - Koillection是一个允许用户管理任何类型收藏的服务。([源代码](https://github.com/benjaminjonard/koillection)) `MIT` `Docker/PHP`
- [LanguageTool](https://languagetool.org/) - 校对20多种语言。它能发现许多简单拼写检查器无法检测到的错误。([源代码](https://github.com/languagetool-org/languagetool), [客户端](https://languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- [Libre Translate](https://libretranslate.com/) - 机器翻译API。([源代码](https://github.com/LibreTranslate/LibreTranslate)) `AGPL-3.0` `Docker/Python`
- [LubeLogger](https://lubelogger.com) - 基于Web的车辆维护和燃油里程追踪器。([演示](https://github.com/hargata/lubelog?tab=readme-ov-file#demo), [源代码](https://github.com/hargata/lubelog)) `MIT` `Docker/K8S/C#`
- [Mirumoji](https://svdc1.github.io/mirumoji/docs) - 日语沉浸式工具包,提供可点击的、分词的字幕,带有字典查找和转录生成功能。([演示](https://svdc1.github.io/mirumoji/), [源代码](https://github.com/svdC1/mirumoji)) `MIT` `Docker/Python`
- [mosparo](https://mosparo.io/) - 现代垃圾邮件保护工具。它用一个简单易用的垃圾邮件保护解决方案替换了其他验证码方法。([源代码](https://github.com/mosparo/mosparo)) `MIT` `PHP`
- [Movary](https://github.com/leepeuker/movary) `⚠` - 用于跟踪和评分您观看的电影的Web应用。([演示](https://github.com/leepeuker/movary?tab=readme-ov-file#demo)) `MIT` `Docker/PHP`
- [Neko](https://neko.m1k1o.net) - 在docker中运行并使用WebRTC的虚拟浏览器。([源代码](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [OmniTools](https://omnitools.app/) - 用于日常任务的强大基于Web的工具集合(编码、操作图像/视频、PDF或处理数字等)。([源代码](https://github.com/iib0011/omni-tools)) `MIT` `Docker`
- [Open-Meteo](https://open-meteo.com/) - 天气API,提供来自所有主要国家气象服务的开放数据预报、历史和气候数据。([演示](https://open-meteo.com/en/docs), [源代码](https://github.com/open-meteo/open-meteo)) `AGPL-3.0` `Docker`
- [OpenReader](https://docs.openreader.richardr.dev/) - EPUB、PDF、DOCX、MD和TXT文件文本转语音文档阅读器。使用高质量TTS实时阅读文档;或提取有声书。([源代码](https://github.com/richardr1126/openreader)) `MIT` `Docker`
- [OpenZiti](https://openziti.io/) - 功能齐全、零信任的全网格覆盖网络。开箱即支持2FA,具有所有主要桌面/移动操作系统客户端。([源代码](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- [Operational.co](https://operational.co) - 在实时时间线中接收来自您产品的警报。([演示](https://app.operational.co/?signinas=kevin), [源代码](https://github.com/operational-co/operational.co)) `AGPL-3.0` `Nodejs/Docker`
- [penpot](https://penpot.app/) - 基于Web的设计和原型制作平台,专为跨领域团队设计。([源代码](https://github.com/penpot/penpot)) `MPL-2.0` `Docker`
- [POMjs](https://password.oppetmoln.se/) - 随机密码生成器。([源代码](https://github.com/joho1968/POMjs)) `GPL-2.0` `Javascript`
- [Pønskelisten](https://github.com/aunefyren/poenskelisten) - 分享愿望清单并协作处理礼物和礼物。`GPL-3.0` `Docker/Go`
- [re:Director](https://re-director.github.io/) - 简单的域名重定向管理工具。([源代码](https://github.com/re-Director/re-director)) `Apache-2.0` `Java/Docker`
- [Reactive Resume](https://rxresu.me/) - 独一无二的简历构建器,注重您的隐私保护。完全安全、可定制且可移植。([演示](https://rxresu.me/), [源代码](https://github.com/reactive-resume/reactive-resume)) `MIT` `Docker/Nodejs`
- [revealjs](https://revealjs.com) - 使用HTML轻松创建精美演示文稿的框架。([演示](https://revealjs.com/), [源代码](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - 广告投放系统。前身为OpenX Adserver和phpAdsNew。([源代码](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - 允许远程客户端访问本地主机上可用的图像采集设备(扫描仪)。([源代码](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [string.is](https://string.is/) - 面向开发者的在线字符串工具包。([源代码](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
- [Teleport](https://goteleport.com/) - SSH、Kubernetes、Web应用程序和数据库的证书颁发机构和访问平面。([源代码](https://github.com/gravitational/teleport)) `Apache-2.0` `Go/Docker/K8S`
- [TeslaMate](https://github.com/teslamate-org/teslamate) - 强大的特斯拉车辆数据记录器。`MIT` `Elixir/Docker`
- [Transmute](https://transmute.sh) - 图像、视频、音频、json、excel等的文件转换器。支持2000多种转换!。([源代码](https://github.com/transmute-app/transmute)) `MIT` `Docker`
- [URL-to-PNG](https://github.com/jasonraimondi/url-to-png) - URL转PNG实用程序,使用Playwright进行并行渲染以截屏,并通过Local、S3或CouchDB进行存储缓存。`MIT` `Nodejs/Docker`
- [Usertour](https://www.usertour.io/) - 用户引导平台,允许您轻松创建应用内产品导览、清单和调查。([源代码](https://github.com/usertour/usertour/)) `AGPL-3.0` `Docker`
- [Warracker](https://warracker.com) - 保修追踪器,让您监控到期日期,上传收据/文件,并在保修到期前获取警报。([源代码](https://github.com/sassanix/Warracker)) `AGPL-3.0` `Docker`
- [Wavelog](https://www.wavelog.org) - 基于Web的业余无线电日志软件。为您的浏览器提供增强的QSO日志记录、统计和地图功能。([演示](https://demo.wavelog.org), [源代码](https://github.com/wavelog/wavelog)) `MIT` `PHP/Docker`
- [WeeWX](https://weewx.com/) - 您的气象站的开源软件。([演示](https://weewx.com/showcase.html), [源代码](https://github.com/weewx/weewx)) `GPL-3.0` `Python/deb`
- [WeTTY](https://butlerx.github.io/wetty/#/) - 通过http/https在浏览器中的终端。([源代码](https://github.com/butlerx/wetty)) `MIT` `Docker/Nodejs`
- [Wishlist](https://github.com/cmintey/wishlist) - 您可以与朋友和家人分享的愿望清单应用。`MIT` `Docker/K8S`
- [Yamtrack](https://github.com/FuzzyGrim/Yamtrack) `⚠` - 电影、电视节目、动漫、漫画、视频游戏和书籍的媒体追踪器。([演示](https://github.com/FuzzyGrim/Yamtrack?tab=readme-ov-file#demo)) `AGPL-3.0` `Docker/Python`
- [Zero-TOTP](https://zero-totp.com) - 完整、可靠、安全且基于零信任的Web应用,使用零知识加密存储您的TOTP代码。([源代码](https://github.com/SeaweedbrainCY/zero-totp)) `GPL-3.0` `Docker`


### 金钱、预算和管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[金钱管理](https://zh.wikipedia.org/wiki/金钱管理)和预算软件。

_相关: [库存管理](#库存管理), [资源规划](#资源规划)_

- [Actual](https://actualbudget.org) - 基于零和预算的本地优先个人财务工具,支持跨设备同步、自定义规则、手动交易导入(从QIF、OFX和QFX文件),以及与许多银行的可选自动同步。([源代码](https://github.com/actualbudget/actual)) `MIT` `Nodejs/Docker`
- [Bigcapital](https://bigcapital.app/) - 面向中小企业的财务会计和库存管理软件。([源代码](https://github.com/bigcapitalhq/bigcapital)) `AGPL-3.0` `Docker`
- [Bitcart](https://bitcart.ai) - 加密货币支付处理器和开发平台。([演示](https://admin.bitcart.ai), [源代码](https://github.com/bitcart/bitcart)) `MIT` `Docker/Python/Nodejs`
- [BTCPay Server](https://btcpayserver.org/) - 比特币和其他加密货币支付处理器。([演示](https://mainnet.demo.btcpayserver.org/), [源代码](https://github.com/btcpayserver/btcpayserver)) `MIT` `C#`
- [Budget Board](https://budgetboard.net/) - 用于跟踪月度支出和实现财务目标的简单应用。([源代码](https://github.com/teelur/budget-board)) `GPL-3.0` `Docker`
- [DePay](https://depay.com) - 直接点对点接受Web3支付到您的钱包。([演示](https://depay.com/products/payments), [源代码](https://github.com/depayfi/widgets)) `MIT` `Nodejs`
- [Econumo](https://econumo.com) - 用于管理个人和家庭财务的预算应用,支持多货币、联合账户和预算。([演示](https://demo.econumo.com), [源代码](https://github.com/econumo/econumo)) `MIT` `Docker`
- [Expensave](https://github.com/algirdasc/expensave) - 用于个人和家庭预算管理的费用追踪器。在共享日历上跟踪支出,导入银行对账单并通过报告监控财务。`GPL-3.0` `Docker`
- [ezbookkeeping](https://ezbookkeeping.mayswind.net/) - 由您自己托管的轻量级个人记账应用。([演示](https://ezbookkeeping-demo.mayswind.net/), [源代码](https://github.com/mayswind/ezbookkeeping)) `MIT` `Go/Docker`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - 面向具有部分共享开支的合作伙伴的基于Web的财务管理工具。`Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Beancount的Web前端,这是一个基于文本的复式记账系统。([演示](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [源代码](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III是一个现代财务管理器。它帮助您跟踪资金并进行预算预测。它支持信用卡,具有高级规则引擎,可以从许多银行导入数据。([演示](https://demo.firefly-iii.org/), [源代码](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP/Docker`
- [FOSSBilling](https://fossbilling.org/) - 托管和计费自动化。与WHM、CWP、cPanel和HestiaCP集成。完整的API且易于扩展。([演示](https://fossbilling.org/demo), [源代码](https://github.com/FOSSBilling/FOSSBilling)) `Apache-2.0` `PHP/Docker`
- [Galette](https://galette.eu/) - 面向非营利组织的会员管理Web应用。([源代码](https://github.com/galette/galette)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 用于跟踪股票、ETF和加密货币的财富管理软件。([源代码](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- [GRR](https://grr.devome.com/?lang=en) - 面向中小企业的资产管理和预订系统。([源代码](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [HyperSwitch](https://hyperswitch.io/) `⚠` - 支付交换机,使支付快速、可靠且经济实惠。连接多个支付处理器并轻松路由流量,所有这些只需一次API集成。([源代码](https://github.com/juspay/hyperswitch)) `Apache-2.0` `Docker/Rust`
- [IHateMoney](https://ihatemoney.org/) - 轻松管理您的共享开支。([演示](https://ihatemoney.org/demo/), [源代码](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [InvoicePlane](https://www.invoiceplane.com/) - 为您的小企业管理报价单、发票、付款和客户。([源代码](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
- [InvoiceShelf](https://invoiceshelf.com/) - 跟踪支出、付款并创建专业发票和估算(Crater的分支)。([源代码](https://github.com/InvoiceShelf/InvoiceShelf)) `AGPL-3.0` `PHP/Docker`
- [Kill Bill](https://killbill.io/) - 订阅计费和支付平台。可以访问实时分析报告和财务报告。([源代码](https://github.com/killbill/killbill)) `Apache-2.0` `Java/Docker`
- [Kresus](https://kresus.org/) - 个人财务经理。([演示](https://kresus.org/en/demo.html), [源代码](https://github.com/kresusapp/kresus)) `AGPL-3.0` `Nodejs/Docker`
- [Lago](https://www.getlago.com/) - 计量和基于用量的计费。([源代码](https://github.com/getlago/lago)) `AGPL-3.0` `Docker`
- [Mybucks.online](https://mybucks.online) - 安全、基于浏览器、仅密码的自我托管加密货币钱包。([演示](https://app.mybucks.online), [源代码](https://github.com/mybucks-online/app)) `MIT` `Nodejs`
- [MyFin Budget](https://myfinbudget.com) - 个人财务平台(Web + REST API + Android),将帮助您进行预算,跟踪收入/支出并预测您的财务未来。([演示](https://github.com/afaneca/myfin?tab=readme-ov-file#demo-account---try-it-for-yourself), [源代码](https://github.com/afaneca/myfin), [客户端](https://github.com/afaneca/myfin-api)) `GPL-3.0` `Nodejs/Docker`
- [OctoBot](https://www.octobot.cloud/) - 加密货币交易机器人。([源代码](https://github.com/Drakkar-Software/OctoBot)) `GPL-3.0` `Python/Docker`
- [Ocular](https://simonwep.github.io/ocular/) - 简单直接的预算应用,用于跨月和年跟踪预算。([演示](https://simonwep.github.io/ocular/demo/#demo), [源代码](https://github.com/simonwep/ocular)) `MIT` `Docker`
- [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer) - 基于桶式预算原则的预算应用。`AGPL-3.0` `Docker/C#`
- [Receipt Wrangler](https://receiptwrangler.io) `⚠` - 易于使用的收据管理器,由AI驱动。允许用户轻松快速地创建收据,分类等。([演示](https://demo.receiptwrangler.io), [源代码](https://github.com/Receipt-Wrangler/receipt-wrangler)) `AGPL-3.0` `Docker`
- [REI3](https://rei3.de/home_en/) - 在您的业务中管理任务、时间、资产等。([演示](https://rei3.de/demo_en/), [源代码](https://github.com/r3-team/r3)) `MIT` `Go`
- [SHKeeper](https://shkeeper.io/) - 加密货币支付处理器,具有网关和商家的独特组合,允许您接受多种加密货币的支付,无需费用和中间商。([演示](https://github.com/vsys-host/shkeeper.io?tab=readme-ov-file#11-demo), [源代码](https://github.com/vsys-host/shkeeper.io)) `GPL-3.0` `Python`
- [SolidInvoice](https://solidinvoice.co) - 开源发票和报价应用。([源代码](https://github.com/SolidInvoice/SolidInvoice)) `MIT` `PHP`
- [Sure](https://github.com/we-promise/sure) - 适合每个人的个人财务应用(Maybe的分支)。`AGPL-3.0` `Docker`
- [VoucherVault](https://github.com/l4rm4nd/VoucherVault) - 数字化存储和管理代金券、优惠券、忠诚度和礼品卡。支持到期通知、交易历史、文件上传和OIDC SSO。`GPL-3.0` `Docker`
- [Wallos](https://wallosapp.com) - 具有统计信息和可选通知功能的轻量级个人订阅追踪器。([演示](https://github.com/ellite/wallos?tab=readme-ov-file#demo), [源代码](https://github.com/ellite/wallos)) `GPL-3.0` `PHP/Docker`
- [WYGIWYH](https://github.com/eitchtee/WYGIWYH) - 简单而强大的财务追踪器。([演示](https://wygiwyh-demo.herculino.com/)) `AGPL-3.0` `Docker/Python`
- [YAFFA](https://www.yaffa.cc) - 个人财务Web应用,可用于跟踪您的金钱、支出、预算和投资。它还有助于长期财务规划。([演示](https://sandbox.yaffa.cc), [源代码](https://github.com/kantorge/yaffa)) `MIT` `PHP`


### 监控和状态页面

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于[监控](https://zh.wikipedia.org/wiki/Monitoring#Computing)系统、网络、应用程序和网站的软件。

**请访问 [awesome-sysadmin/监控](https://github.com/awesome-foss/awesome-sysadmin#monitoring--status-pages), [awesome-sysadmin/指标和指标收集](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection)**

_相关: [个人仪表板](#个人仪表板)_


### 网络工具

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

网络工具是帮助管理、监视和排除计算机网络故障的工具和软件。

_另见: [awesome-sysadmin/监控](https://github.com/awesome-foss/awesome-sysadmin#monitoring)_

- [beelzebub](https://beelzebub-honeypot.com/) `⚠` - 蜜罐框架,旨在为检测和分析网络攻击提供高度安全的环境。([源代码](https://github.com/beelzebub-labs/beelzebub)) `MIT` `Docker/K8S/Go`
- [Canary Tokens](https://canarytokens.org) - 生成轻量级的嵌入式蜜罐触发器(称为canary tokens),用于检测未经授权的访问。([源代码](https://github.com/thinkst/opencanary)) `BSD-3-Clause` `Docker/Python`
- [MyIP](https://ipcheck.ing) `⚠` - 一站式IP工具箱。易于检查您的IP地址、IP地理位置、检查DNS泄漏、检查WebRTC连接、速度测试、ping测试、MTR测试、检查网站可用性等。([演示](https://ipcheck.ing), [源代码](https://github.com/jason5ng32/MyIP)) `MIT` `Nodejs/Docker`
- [MySpeed](https://myspeed.dev/) - 显示您30天内互联网速度的速度测试分析软件。([源代码](https://github.com/gnmyt/myspeed)) `MIT` `Docker/Nodejs`
- [NetAlertX](https://netalertx.com/) - 网络入侵者和存在检测器。扫描连接到您网络的设备,如果发现新的未知设备会提醒您。([源代码](https://github.com/netalertx/NetAlertX)) `GPL-3.0` `Docker`
- [PlugNPiN](https://deepspace2.github.io/PlugNPiN) - 自动抓取具有特定标签的容器,并在Pi-Hole/AdGuard Home中创建本地DNS/CNAME条目,在Nginx Proxy Manager中创建代理主机。([源代码](https://github.com/deepspace2/plugnpin)) `GPL-3.0` `Docker`
- [Speed Test by OpenSpeedTest™](https://openspeedtest.com/) - HTML5网络性能估算工具。([源代码](https://github.com/openspeedtest/Speed-Test)) `MIT` `Docker`
- [Speedtest Tracker](https://docs.speedtest-tracker.dev/) - 监控您的互联网连接的性能和正常运行时间。([源代码](https://github.com/alexjustesen/speedtest-tracker)) `MIT` `Docker/K8S`
- [Upsnap](https://github.com/seriousm4x/UpSnap) - 一个简单的Wake on LAN (WOL)仪表板应用。唤醒您网络上的设备并查看当前状态。`MIT` `Go/Docker`
- [Wakupator](https://github.com/Gibus21250/Wakupator) - 基于网络流量的LAN唤醒机器管理器。`MIT` `C`
- [whois](https://github.com/KincaidYang/whois) - 面向域名、IP地址、CIDR前缀和ASN的WHOIS/RDAP查询API,具有统一的JSON输出、缓存、API密钥认证、批量查询和对AI助手的MCP支持。([演示](https://whois.ddnsip.cn/example.com)) `MIT` `Go/Docker`


### 笔记和编辑器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[笔记](https://zh.wikipedia.org/wiki/笔记)编辑器。

_相关: [维基](#维基)_

- [Blinko](https://blinko.space/) - 具有AI功能的个人笔记工具。([源代码](https://github.com/blinkospace/blinko)) `AGPL-3.0` `Docker`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密日记Web应用,用于保存您每天的个人记忆。包括搜索功能和加密文件上传。([演示](https://dailytxt.phitux.de)) `MIT` `Docker`
- [Docs](https://docs.numerique.gouv.fr/) - 可扩展的协作笔记、维基和文档平台。([源代码](https://github.com/suitenumerique/docs)) `MIT` `K8S`
- [draw.io](https://draw.io) - 用于制作流程图、过程图、组织结构图、UML、ER和网络图的图表软件。([源代码](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript/Docker`
- [flatnotes](https://github.com/dullage/flatnotes) - 无数据库笔记Web应用,利用扁平的markdown文件夹进行存储。([演示](https://demo.flatnotes.io)) `MIT` `Docker`
- [HedgeDoc](https://hedgedoc.org/) - 在所有平台上实时协作markdown笔记,前身为CodiMD和HackMD CE。([演示](https://demo.hedgedoc.org/), [源代码](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Nodejs`
- [Joplin](https://joplinapp.org/) - 具有markdown编辑器和加密支持的笔记应用,适用于移动和桌面平台。运行客户端并通过自托管的Nextcloud实例或类似服务进行同步(Evernote的替代品)。([源代码](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Jotty](https://jotty.page) - 轻量但强大的替代品,用于管理您的个人、基于文件的笔记和清单。([源代码](https://github.com/fccview/jotty)) `AGPL-3.0` `Docker`
- [Livebook](https://livebook.dev) - 基于Markdown的实时协作笔记本应用,支持运行Elixir代码片段、TeX和Mermaid图表。可以使用Docker或Elixir轻松部署。([源代码](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir/Docker`
- [Many Notes](https://github.com/brufdev/many-notes) - 为简洁而设计的Markdown笔记Web应用。`MIT` `Docker`
- [Memos](https://usememos.com/) - 使用SQLite数据库文件工作的知识库。([演示](https://demo.usememos.com/explore), [源代码](https://github.com/usememos/memos)) `MIT` `Docker/Go`
- [Neverkin](https://neverkin.com/) - 协作写作、世界构建和D&D会话规划应用。用于组织您的笔记和故事的工具。([演示](https://app.neverkin.com/guest-login), [源代码](https://github.com/Tenebrie/neverkin/)) `GPL-3.0` `Nodejs/Docker`
- [Note Mark](https://notemark.docs.enchantedcode.co.uk/) - 极简主义基于Web的Markdown笔记应用。([源代码](https://github.com/enchant97/note-mark)) `AGPL-3.0` `Docker`
- [NoteDiscovery](https://www.notediscovery.com/) - 具有纯文件存储、图形视图和MCP集成的Markdown笔记应用(Obsidian、Notion的替代品)。([演示](https://gamosoft-notediscovery-demo.hf.space), [源代码](https://github.com/gamosoft/NoteDiscovery)) `MIT` `Docker/Python`
- [Overleaf](https://www.overleaf.com/) - 基于Web的协作LaTeX编辑器。([源代码](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Plainpad](https://plainpad.org) - 云端的现代笔记应用,利用渐进式Web应用技术的最佳功能。([演示](https://demo.plainpad.org), [源代码](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [plumio](https://plumio.app/) - 具有实时预览、文档加密、多用户支持、多组织能力等的Markdown笔记应用。([演示](https://demo.plumio.app/homepage), [源代码](https://github.com/albertasaftei/plumio)) `AGPL-3.0` `Nodejs/Docker`
- [SilverBullet](https://silverbullet.md/) - 针对具有黑客心态的人优化的笔记应用。([演示](https://play.silverbullet.md/), [源代码](https://github.com/silverbulletmd/silverbullet), [客户端](https://silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- [Standard Notes](https://docs.standardnotes.com/self-hosting/getting-started) - 简单且私密的笔记应用。在保护隐私的同时提高工作效率。这就是Standard Notes。([演示](https://app.standardnotes.com/), [源代码](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
- [TriliumNext Notes](https://github.com/TriliumNext/Trilium) - 跨平台分层笔记应用,专注于构建大型个人知识库(Trilium Notes的分支)。`AGPL-3.0` `Nodejs/Docker/K8S`
- [Turtl](https://turtl.it/) - 完全私密的个人数据库和笔记应用。([源代码](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Writing](https://josephernest.github.io/writing/) - 轻量级无干扰文本编辑器,在浏览器中(支持Markdown和LaTeX)。书写时无延迟。([源代码](https://github.com/josephernest/writing)) `MIT` `Javascript`


### 办公套件

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[办公套件](https://zh.wikipedia.org/wiki/办公套件列表)是生产力软件的集合,通常至少包含文字处理程序、电子表格和演示程序。

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE)是一个强大的基于LibreOffice的在线办公套件,支持所有主要的文档、电子表格和演示文件格式,您可以将其集成到自己的基础设施中。([源代码](https://gerrit.collaboraoffice.com/plugins/gitiles/online)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.org) - 协作套件,旨在实现协作,实时同步文档更改。([源代码](https://github.com/cryptpad/cryptpad)) `AGPL-3.0` `Nodejs/Docker`
- [Digislides](https://ladigitale.dev/digislides/) - 快速简单地创建多媒体演示文稿(法语文档)。([演示](https://ladigitale.dev/digislides/), [源代码](https://codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Nodejs/PHP`
- [Etherpad](https://etherpad.org/) - 高度可定制的在线编辑器,提供实时协作编辑功能。([演示](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [源代码](https://github.com/ether/etherpad)) `Apache-2.0` `Nodejs/Docker`
- [Grist](https://getgrist.com/) - 具有关系结构、基于公式的访问控制和便携式自包含格式的下一代电子表格(Airtable的替代品)。([演示](https://docs.getgrist.com), [源代码](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python/Docker`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - 办公套件,允许您在一个地方管理文档、项目、团队和客户关系。([源代码](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs/Docker`


### 密码管理器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[密码管理器](https://zh.wikipedia.org/wiki/密码管理器)允许用户存储、生成和管理其本地应用程序和在线服务的密码。

- [AliasVault](https://www.aliasvault.net) - 具有内置电子邮件别名生成器和服务器的端到端加密密码管理器。([源代码](https://github.com/aliasvault/aliasvault)) `MIT` `Docker`
- [Bitwarden](https://bitwarden.com/) `⚠` - 具有Web应用、浏览器扩展和移动应用的密码管理器。([源代码](https://github.com/bitwarden/server)) `AGPL-3.0` `Docker/C#`
- [Passbolt](https://www.passbolt.com/) - 协作密码管理器。([源代码](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP/deb/K8S/Docker`
- [PassIt](https://passit.io/) - 具有按组和用户共享功能的简单密码管理器,但没有管理界面。([演示](https://app.passit.io/), [源代码](https://gitlab.com/passit)) `AGPL-3.0` `Docker/Python`
- [Psono](https://psono.com/) - 面向公司的密码管理器。([演示](https://www.psono.pw), [源代码](https://gitlab.com/esaqa/psono/psono-fileserver)) `Apache-2.0` `Python`
- [Teampass](https://teampass.net/) - 专用于以协作方式管理密码的密码管理器。使用一个对称密钥加密所有共享/团队密码,并以文件形式存储在服务器端和数据库中。适用于任何运行Apache、MySQL和PHP的服务器。([源代码](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用Rust编写的轻量级Bitwarden服务器API实现。`GPL-3.0` `Rust/Docker`


### 粘贴板

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[粘贴板](https://zh.wikipedia.org/wiki/Pastebin)是一种用于共享和存储代码和文本的在线内容托管服务。

- [1time](https://1time.io) - 零知识一次性秘密分享。为密码、API密钥或文件创建一次性链接。在浏览器中进行客户端加密,永远不会以明文形式到达服务器,在允许的查看次数后自动销毁(默认为一次)。([演示](https://1time.io), [源代码](https://github.com/shingrus/1time.io)) `MIT` `Docker`
- [BinPastes](https://github.com/querwurzel/BinPastes) - 支持客户端加密、全文搜索、一次性消息的极简粘贴板。旨在为一到少数寻找简单粘贴板部署的用户提供服务。`Apache-2.0` `Java`
- [ByteStash](https://github.com/jordan-dalby/ByteStash) - 具有简单Web界面的粘贴板和文件存储服务。支持语法高亮、可选用户认证和公共共享。([演示](https://github.com/jordan-dalby/ByteStash?tab=readme-ov-file#demo)) `GPL-3.0` `Docker`
- [Chiyogami](https://github.com/rhee876527/chiyogami) - 具有API、客户端加密、用户账户、语法高亮、markdown渲染等功能的粘贴板。([演示](https://chiyogami.myaddr.dev/)) `BSD-3-Clause` `Docker`
- [dpaste](https://dpaste.org/) - 具有多种文本和代码选项的简单粘贴板,具有易于记忆的短URL结果。([源代码](https://github.com/DarrenOfficial/dpaste)) `MIT` `Docker/Python`
- [lesma](https://lesma.eu) - 对浏览器和命令行友好的简单粘贴应用。([演示](https://lesma.eu), [源代码](https://gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- [Local Content Share](https://github.com/Tanq16/local-content-share) - 在您的局域网内存储和共享文本片段和文件。`MIT` `Docker/Go`
- [not-th.re](https://not-th.re) - 简单的粘贴共享平台,具有客户端加密功能,采用基于monaco浏览器的代码编辑器。([演示](https://not-th.re), [源代码](https://github.com/not-three/main)) `AGPL-3.0` `Nodejs/Docker`
- [Opengist](https://opengist.io) - 由Git驱动的粘贴板。([演示](https://demo.opengist.io), [源代码](https://github.com/thomiceli/opengist)) `AGPL-3.0` `Docker/Go/Nodejs`
- [paaster](https://paaster.io) - 以简洁为目标构建的端到端加密粘贴板。([源代码](https://github.com/WardPearce/paaster)) `AGPL-3.0` `Docker`
- [pacebin](https://git.crueter.xyz/crueter/pacebin) - 超极简粘贴板和文件上传服务,专注于小型可执行文件大小、便携性和易配置性。([演示](https://paste.crueter.xyz)) `AGPL-3.0` `C`
- [Password Pusher](https://pwpush.com) - 通过网络安全地通信密码(或文本)的极其简单的应用程序。密码在一定数量的查看次数和/或时间过后会自动过期。([源代码](https://github.com/pglombardo/PasswordPusher)) `Apache-2.0` `Docker/K8S/Ruby`
- [Pastefy](https://pastefy.app/) - 美观、简单且易于部署的粘贴板,具有可选的客户端加密、多标签页粘贴、API、高亮编辑器等功能。([源代码](https://github.com/interaapps/pastefy), [客户端](https://github.com/topics/pastefy-addon)) `MIT` `Docker/K8S/Java`
- [PrivateBin](https://privatebin.info/) - 极简主义粘贴板/讨论板,服务器对托管数据零知情。([演示](https://privatebin.net/), [源代码](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [rustypaste](https://github.com/orhun/rustypaste) - 极简文件上传/粘贴板服务。`MIT` `Rust`
- [Snipo](https://github.com/MohamedElashri/snipo) - 轻量级自托管片段管理器,用于保存和组织代码和文本片段,具有文件夹、标签、API和GitHub Gist同步功能。([演示](https://snipo.melashri.dev/)) `AGPL-3.0` `Go/Docker`
- [SnyPy](https://snypy.com) - 开源本地部署代码片段管理器。([演示](https://app.snypy.com), [源代码](https://github.com/snypy)) `MIT` `Docker`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 非常简单(部署和使用)的秘密消息服务,使用Hashicorp Vault作为秘密存储。`MIT` `Go`
- [Wastebin](https://github.com/matze/wastebin) - 具有SQLite后端的轻量级、极简快速粘贴板。([演示](https://bin.bloerg.net)) `MIT` `Rust/Docker`
- [Yopass](https://github.com/jhaals/yopass) - 安全地共享秘密、密码和文件。([演示](https://yopass.se/)) `Apache-2.0` `Go/Docker`


### 个人仪表板

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于访问信息和应用程序的仪表板。

_相关: [监控和状态页面](#监控和状态页面), [书签和链接分享](#书签和链接分享)_

- [Compass](https://adinhodovic.github.io/compass/) - 服务、仪表板和文档的着陆页,支持从Docker、Kubernetes和Tailscale等来源进行自动发现。([源代码](https://github.com/adinhodovic/compass)) `Apache-2.0` `Go/Docker/K8S`
- [Dashy](https://dashy.to/) - 功能丰富的家庭实验室主页,具有简单的YAML配置。([演示](https://demo.dashy.to/), [源代码](https://github.com/lissy93/dashy)) `MIT` `Nodejs/Docker`
- [Glance](https://github.com/glanceapp/glance) - 高度可定制的仪表板,将所有信息流集中在一个地方。`AGPL-3.0` `Docker/Go`
- [gobookmarks](https://github.com/arran4/gobookmarks) - 用于显示存储在GitHub、GitLab或本地Git中的书签的着陆页。`AGPL-3.0` `Go/Docker`
- [Heimdall](https://heimdall.site/) - 组织所有Web应用的优雅解决方案。([源代码](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Homarr](https://homarr.dev) - 流线型现代仪表板,具有许多集成和基于Web的配置。([源代码](https://github.com/homarr-labs/homarr)) `MIT` `Docker/Nodejs`
- [Homepage by gethomepage](https://github.com/gethomepage/homepage) - 高度可定制的主页(或起始页/应用仪表板),具有Docker和服务API集成。`GPL-3.0` `Docker/Nodejs`
- [Homepage by tomershvueli](https://github.com/tomershvueli/homepage) - 简单、独立、自托管的PHP页面,是您访问服务器和网络的窗口。`MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 极简静态主页,用于暴露您的服务器服务,具有简单的yaml配置和连接检查。([演示](https://homer-demo.netlify.app)) `Apache-2.0` `Docker/K8S/Nodejs`
- [Hubleys](https://github.com/knrdl/hubleys-dashboard) - 用于通过中央yaml配置为多个用户组织链接的个人仪表板。`MIT` `Docker`
- [LinkStack](https://linkstack.org/) - 将您所有的社交媒体平台轻松链接到一个页面上,可通过直观、易于使用的用户/管理员界面进行自定义(Linktree和Manylink的替代品)。([演示](https://linksta.cc/), [源代码](https://github.com/LinkStackOrg/LinkStack)) `AGPL-3.0` `PHP/Docker`
- [LittleLink](https://littlelink.io/) - 简化的个人简介链接方法,具有100+品牌按钮(Linktree的替代品)。([演示](https://littlelink.io/), [源代码](https://github.com/sethcottle/littlelink)) `MIT` `Javascript`
- [Mafl](https://mafl.hywax.space/) - 极简灵活的主页。([源代码](https://github.com/hywax/mafl)) `MIT` `Docker/Nodejs`
- [Nimbus](https://nimbus.turboot.com/) - 具有可视编辑器和简单配置的现代拖放式家庭实验室仪表板。([演示](https://nimbus.turboot.com/), [源代码](https://github.com/Turbootzz/Nimbus)) `AGPL-3.0` `Docker`
- [Personal Management System](https://volmarg.github.io/) - 组织日常生活的基本要素,从简单的待办事项列表和笔记,到付款和日程安排等一切。([演示](https://github.com/Volmarg/personal-management-system#documentation--demo), [源代码](https://github.com/Volmarg/personal-management-system)) `MIT` `Docker`
- [portkey](https://portkey.page) - 作为启动页面的简单Web门户,显示链接和URL的汇编,同时允许添加自定义页面,所有这些都通过单个配置文件进行管理。([演示](https://demo.portkey.page), [源代码](https://github.com/kodehat/portkey)) `AGPL-3.0` `Go/Docker`
- [ryot](https://github.com/ignisda/ryot) - 跟踪您生活的各个方面 - 媒体、健身等。([演示](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo)) `GPL-3.0` `Docker`
- [Starbase 80](https://github.com/notclickable-jordan/starbase-80) - 具有iPad风格应用网格的简单主页,适用于移动设备和桌面。一个JSON配置文件。`MIT` `Docker`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - 允许您记录您的Spotify收听活动并通过Web应用程序获取相关统计信息。`MIT` `Nodejs/Docker`


### 照片画廊

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[画廊](https://zh.wikipedia.org/wiki/画廊软件)是帮助用户发布或共享照片、图片、视频或其他数字媒体的软件。

_相关: [静态站点生成器](#静态站点生成器), [媒体流媒体 - 视频流媒体](#媒体流媒体---视频流媒体), [内容管理系统(CMS)](#内容管理系统cms)_

- [Chevereto](https://chevereto.com/) - 终极图像共享软件。只需几分钟即可创建您自己的个人图像托管网站。([源代码](https://github.com/chevereto/chevereto)) `AGPL-3.0` `PHP/Docker`
- [ChronoFrame](https://chronoframe.bh8.ga/) - 具有在线照片管理的个人画廊应用,支持Live/Motion Photos和探索地图。([演示](https://lens.bh8.ga/), [源代码](https://github.com/HoshinoSuzumi/chronoframe)) `MIT` `Nodejs/Docker`
- [Damselfly](https://damselfly.info) - 用于大型图像集合的快速基于服务器的照片管理系统。包括人脸检测、人脸和对象识别、强大的搜索和EXIF关键词标记。可在Linux、MacOS和Windows上运行。([源代码](https://github.com/webreaper/damselfly)) `GPL-3.0` `Docker/C#/.NET`
- [Ente](https://ente.com/) - 端到端加密的照片共享平台(Google Photos、Apple Photos的替代品)。([源代码](https://github.com/ente/ente)) `AGPL-3.0` `Docker/Nodejs/Go`
- [HomeGallery](https://home-gallery.org) - 浏览个人照片和视频,具有标记、移动友好和AI驱动的图像发现功能。([演示](https://demo.home-gallery.org), [源代码](https://github.com/xemle/home-gallery)) `MIT` `Nodejs/Docker`
- [Immich Kiosk](https://github.com/damongolding/immich-kiosk) - 在信息亭设备和浏览器上运行的轻量级幻灯片,使用Immich作为数据源。([客户端](https://github.com/immich-app/immich)) `GPL-3.0` `Docker/Go`
- [Immich](https://immich.app/) - 直接从手机备份照片和视频的解决方案(Google Photos的替代品)。([演示](https://github.com/immich-app/immich#demo), [源代码](https://github.com/immich-app/immich)) `AGPL-3.0` `Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 略微侧重于酷炫图表的照片管理服务(Google Photos的替代品)。([客户端](https://docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- [Lychee](https://lycheeorg.github.io/) - 基于网格和相册的照片管理系统。([源代码](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP/Docker`
- [Mediagoblin](https://mediagoblin.org) - 任何人都可以运行的媒体发布平台(Flickr、YouTube、SoundCloud的替代品)。([源代码](https://git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- [Memtly](https://docs.memtly.com/) - 活动照片共享平台和画廊,具有幻灯片功能,允许客人通过二维码查看和共享回忆。([演示](https://demo.memtly.com/), [源代码](https://github.com/Memtly/Memtly.Community)) `GPL-3.0` `C#/Docker`
- [Nextcloud Memories](https://memories.gallery/) - 快速、现代且高级的照片管理套件。作为Nextcloud应用运行。([演示](https://demo.memories.gallery/apps/memories/), [源代码](https://github.com/pulsejet/memories)) `AGPL-3.0` `PHP`
- [Photofield](https://github.com/SmilyOrg/photofield) - 实验性的快速照片查看器。`MIT` `Docker/Go`
- [PhotoPrism](https://photoprism.org) - 由Go和Google TensorFlow驱动的个人照片管理。浏览、组织和共享您的个人照片集,使用最新技术自动标记和查找图片。([演示](https://demo.photoprism.app/library/browse), [源代码](https://github.com/photoprism/photoprism)) `AGPL-3.0` `Go/Docker`
- [Photoview](https://photoview.github.io/) - 为个人服务器设计的简单且用户友好的照片画廊。专为摄影师设计,旨在提供一种轻松快捷的方式来导航包含数千张高分辨率照片的目录。([演示](https://photoview.github.io/), [源代码](https://github.com/photoview/photoview)) `GPL-3.0` `Go/Docker`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 以目录优先的照片画廊网站,具有丰富的UI,针对在低资源服务器上运行进行了优化。([源代码](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - Web照片画廊软件,由活跃的用户和开发者社区构建。([源代码](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [SPIS](https://github.com/gbbirkisson/spis) - 一个简单、轻量级且快速的媒体服务器,具有不错的移动设备支持。`GPL-3.0` `Docker/Rust`
- [This week in past](https://github.com/RouHim/this-week-in-past) - 汇总本周拍摄的往年图像,并在网页上以简单的幻灯片形式呈现。`MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - 智能成像服务,能够按需裁剪、调整大小、应用过滤器和优化图像。([源代码](https://github.com/thumbor/thumbor)) `MIT` `Python/Docker`
- [Zenphoto](https://www.zenphoto.org/) - 画廊和CMS项目。([源代码](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 投票和活动

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于组织[投票](https://zh.wikipedia.org/wiki/民意调查)和[活动](https://zh.wikipedia.org/wiki/事件)的软件。

_相关: [预订和调度](#预订和调度)_

- [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - 对日期、时间或一般问题进行投票。([演示](https://bitpoll.de/)) `GPL-3.0` `Docker/Python`
- [Bracket](https://docs.bracketapp.nl/) - 灵活的锦标赛系统,用于构建锦标赛设置、添加团队、安排比赛、跟踪分数并向公众实时展示排名。([演示](https://www.bracketapp.nl/demo), [源代码](https://github.com/evroon/bracket)) `AGPL-3.0` `Docker/Nodejs`
- [Christmas Community](https://github.com/Wingysam/Christmas-Community) - 为您的整个家庭创建一个简单的地方,用于查找人们想要的礼物,避免重复送礼。`AGPL-3.0` `Docker/Nodejs`
- [Claper](https://claper.co/) - 与观众互动的终极工具(Slido、AhaSlides和Mentimeter的替代品)。([源代码](https://github.com/ClaperCo/Claper)) `GPL-3.0` `Elixir/Docker`
- [ClearFlask](https://clearflask.com) - 社区反馈工具,用于管理传入反馈并确定公共路线图的优先级(Canny、UserVoice、Upvoty的替代品)。([演示](https://product.clearflask.com), [源代码](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [docassemble](https://docassemble.org/) - 基于Python、YAML和Markdown的引导式访谈和文档组装系统。([演示](https://demo.docassemble.org/run/legal), [源代码](https://github.com/jhpyle/docassemble)) `MIT` `Docker/Python`
- [EventSchedule](https://eventschedule.com/) - 分享活动、销售门票并将社区聚集在一起。([源代码](https://github.com/eventschedule/eventschedule)) `AAL` `PHP/Docker`
- [Fider](https://fider.io) - 收集和确定反馈优先级的开放平台(UserVoice的替代品)。([演示](https://demo.fider.io), [源代码](https://github.com/getfider/fider)) `MIT` `Docker`
- [Formbricks](https://formbricks.com) - 建立在全球最大开源调查堆栈上的体验管理套件。优雅地在客户旅程的每一步收集反馈,了解客户的需求。([演示](https://app.formbricks.com), [源代码](https://github.com/formbricks/formbricks)) `AGPL-3.0` `Nodejs/Docker`
- [Framadate](https://framadate.org/abc/) - 用于规划约会或快速轻松做出决定的在线服务:创建投票、定义要选择的日期或主题、向朋友或同事发送投票链接、讨论并做出决定。([演示](https://framadate.org/aqg259dth55iuhwm), [源代码](https://framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - 本地社区活动和议程共享。([演示](https://demo.gancio.org/), [源代码](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [gathio](https://docs.gath.io/) - 自毁、可共享、无需注册的活动页面。([演示](https://gath.io/), [源代码](https://github.com/lowercasename/gathio)) `GPL-3.0` `Nodejs/Docker`
- [HeyForm](https://heyform.net) - 表单构建器,允许任何人创建引人入胜的对话式表单,用于调查、问卷、测验和投票。([源代码](https://github.com/heyform/heyform)) `AGPL-3.0` `Docker`
- [hitobito](https://hitobito.com) - 管理复杂的组层次结构,包括成员、活动等。([演示](https://demo.hitobito.com/en/users/sign_in), [源代码](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [LimeSurvey](https://www.limesurvey.org) - 功能丰富的基于Web的投票软件。支持广泛的调查逻辑。([演示](https://demo.limesurvey.org), [源代码](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://events.indieweb.org) - 极简活动聚合器。([源代码](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 联邦化工具,帮助您查找、创建和组织活动和群组。([源代码](https://framagit.org/framasoft/mobilizon/)) `AGPL-3.0` `Elixir/Docker`
- [OpnForm](https://opnform.com) - 美观的表单构建器。([演示](https://opnform.com/forms/create/guest), [源代码](https://github.com/OpnForm/OpnForm)) `AGPL-3.0` `PHP/Nodejs/Docker`
- [Revel](https://www.letsrevel.io) `⚠` - 以社区为中心的活动管理和票务平台。([演示](https://demo.letsrevel.io), [源代码](https://github.com/letsrevel/revel-backend), [客户端](https://github.com/letsrevel)) `MIT` `Python/Docker`


### 代理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[代理](https://zh.wikipedia.org/wiki/代理服务器)是作为请求资源的客户端和提供该资源的服务器之间的中介的服务器应用程序。本节关于转发(即出站)代理。对于反向代理,请参阅Web服务器部分。

_相关: [Web服务器](#web服务器)_

- [g3proxy](https://g3-project.readthedocs.io/projects/g3proxy/en/latest/) - 支持代理链、协议检查、MITM拦截、ICAP适配和透明代理的转发代理服务器。([源代码](https://github.com/bytedance/g3/tree/master/g3proxy)) `Apache-2.0` `Rust/deb`
- [GitProxy](https://git-proxy.finos.org/) - Git代理,对所有出站git推送操作应用规则和工作流程,确保它们符合要求。它支持HTTP/HTTPS和SSH协议,具有安全扫描和验证功能。([源代码](https://github.com/finos/git-proxy)) `Apache-2.0` `Nodejs/Docker`
- [imagor](https://github.com/cshum/imagor) - 基于 libvips 构建的快速、安全的图像处理服务器和Go库,具有按需调整大小、裁剪、过滤、格式转换和图像合成功能,签名URL和高并发吞吐量的流式管道。`Apache-2.0` `Docker`
- [imgproxy](https://imgproxy.net/) - 用于调整大小和转换远程图像的快速且安全的独立服务器。([源代码](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker/K8S`
- [Outline Server](https://getoutline.org/) - 代理服务器,为每个访问密钥运行一个Shadowsocks实例,并提供用于管理访问密钥的REST API。([源代码](https://github.com/OutlineFoundation/outline-server)) `Apache-2.0` `Docker/Nodejs`
- [Privoxy](https://www.privoxy.org) - 具有高级过滤功能的非缓存Web代理,用于增强隐私、修改网页数据和HTTP头、控制访问以及删除广告和其他令人讨厌的互联网垃圾。`GPL-2.0` `C/deb`
- [sish](https://github.com/antoniomika/sish) - 仅使用SSH将HTTP(S)/WS(S)/TCP隧道到本地主机(serveo/ngrok的替代品)。`MIT` `Go/Docker`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 具有内置身份验证和Telegram机器人的SOCKS5代理服务器,用于用户管理和用户数据使用统计(在按GB付费数据时非常方便)。它已Docker化且易于安装。`Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - 支持HTTP、HTTPS、FTP等的Web缓存代理。通过缓存和重用频繁请求的网页来减少带宽并提高响应时间。([源代码](https://code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- [Tinyproxy](https://tinyproxy.github.io/) - 轻量级HTTP/HTTPS代理守护进程。([源代码](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C/deb`


### 食谱管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于管理[食谱](https://zh.wikipedia.org/wiki/食谱)的软件和工具。

- [Bar Assistant](https://barassistant.app/) - 管理您的家庭酒吧,同时添加配料,搜索鸡尾酒并创建自定义鸡尾酒配方。([演示](https://demo.barassistant.app/), [源代码](https://github.com/karlomikus/bar-assistant)) `MIT` `PHP/Docker`
- [CookCLI](https://cooklang.org) - 使用Cooklang食谱自动化膳食计划和购物的命令行工具,可编写脚本以适应UNIX工作流程,包括Web服务器。([源代码](https://github.com/cooklang/CookCLI)) `MIT` `Rust`
- [Fork Recipes](https://mikebgrep.github.io/forkapi/latest/clients/) - 简单地管理您的食物食谱。([源代码](https://github.com/mikebgrep/fork.recipes)) `BSD-3-Clause` `Docker`
- [ManageMeals](https://managemeals.com/) - 管理食谱,通过URL导入食谱并在没有广告或不必要文本的情况下组织它们。([源代码](https://github.com/managemeals/manage-meals-web)) `GPL-3.0` `Docker`
- [Mealie](https://nightly.mealie.io/) - 受Material design启发的食谱管理器,具有分类和标签管理、购物清单、餐食规划和网站自定义功能。Mealie专注于简单的用户交互,以保持全家人使用该应用。([演示](https://demo.mealie.io), [源代码](https://github.com/mealie-recipes/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 食谱保存器、餐食计划组织和购物清单管理器,可以从任何URL直接导入食谱。([演示](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Recipya](https://recipes.musicavis.ca) - 干净、简单且强大的食谱管理器,您全家都会喜欢。([演示](https://recipes.musicavis.ca/guide/login), [源代码](https://github.com/reaper47/recipya)) `GPL-3.0` `Docker/Go`
- [Tamari](https://tamariapp.com) - 具有内置食谱集合的食谱管理器Web应用。按收藏夹和类别组织,创建购物清单,并规划餐食。([演示](https://app.tamariapp.com), [源代码](https://github.com/alexbates/Tamari)) `GPL-3.0` `Docker/Python`
- [Vanilla Cookbook](https://vanilla-cookbook.readthedocs.io/en/) - 设计复杂度隐藏在底层,用户体验尽可能简洁的食谱管理器,就像香草一样简单。([源代码](https://github.com/jt196/vanilla-cookbook)) `GPL-3.0` `Docker/Nodejs`
- [What To Cook?](https://github.com/kassner/whattocook) - 根据您家里的食材获取今天的烹饪食谱。`AGPL-3.0` `Docker`


### 远程访问

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[远程桌面](https://zh.wikipedia.org/wiki/远程桌面软件)和[SSH](https://zh.wikipedia.org/wiki/安全外壳协议)服务器及Web界面,用于远程管理系统。

- [Cardea](https://github.com/hectorm/cardea) - 具有访问控制、会话记录和可选TPM支持的密钥保护的SSH堡垒机。`EUPL-1.2` `Go/Docker`
- [Engity's Bifröst](https://bifroest.engity.org/) - 高度可定制的SSH服务器,具有多种用户授权方式以及执行用户会话的位置和方式选项。([源代码](https://github.com/engity-com/bifroest)) `Apache-2.0` `Go/Docker`
- [Firezone](https://www.firezone.dev/) - 支持WireGuard协议的安全远程访问网关。提供Web GUI、1行安装脚本、多因素认证(MFA)和SSO。([源代码](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Docker`
- [Guacamole](https://guacamole.apache.org) - 支持VNC和RDP等标准协议的无客户端远程桌面网关。([源代码](https://github.com/apache/guacamole-server)) `Apache-2.0` `Java/C`
- [MeshCentral](https://meshcentral.com/) - 运行您自己的Web服务器,以远程管理和控制局域网或互联网上任何地方的计算机。([源代码](https://github.com/Ylianst/MeshCentral)) `Apache-2.0` `Nodejs`
- [ShellHub](https://www.shellhub.io) - 现代SSH服务器,用于通过命令行(使用任何SSH客户端)或基于Web的用户界面(sshd的替代品)远程访问Linux设备。([源代码](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Docker`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty是为Web制作的SSH和Telnet连接器。([演示](https://sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- [Termix](https://docs.termix.site/) - 无客户端基于Web的服务器管理平台,具有SSH终端、隧道和文件编辑功能。([源代码](https://github.com/Termix-SSH/Termix)) `Apache-2.0` `Docker`
- [Warpgate](https://github.com/warp-tech/warpgate) - 完全透明的SSH、HTTPS、Kubernetes、MySQL和Postgres堡垒/PAM,不需要额外的客户端软件。`Apache-2.0` `Rust/Docker`


### 资源规划

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

帮助进行[资源和供应规划](https://zh.wikipedia.org/wiki/资源规划)的软件和工具,包括[企业资源和供应规划(ERP)](https://zh.wikipedia.org/wiki/企业资源计划)。

_相关: [金钱、预算和管理](#金钱预算和管理), [库存管理](#库存管理)_

- [Dolibarr](https://www.dolibarr.org/) - 现代CRM软件包,用于管理您公司或基金会的活动(联系人、供应商、发票、订单、库存、日程、会计等)。([演示](https://www.dolibarr.org/onlinedemo.php), [源代码](https://github.com/Dolibarr/dolibarr)) `GPL-3.0` `PHP/deb`
- [ERPNext](https://frappe.io/erpnext) - 帮助您运营业务的ERP系统。([源代码](https://github.com/frappe/erpnext)) `GPL-3.0` `Python/Docker`
- [farmOS](https://farmos.org/) - 基于Web的农场记录保存应用。([演示](https://farmos-demo.rootedsolutions.io/), [源代码](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP/Docker`
- [grocy](https://grocy.info/) - 冰箱之外的ERP。您家庭的杂货和家居管理解决方案。([演示](https://en.demo.grocy.info/), [源代码](https://github.com/grocy/grocy)) `MIT` `PHP/Docker`
- [LedgerSMB](https://ledgersmb.org/) - 面向中小企业的集成会计和ERP系统,具有复式记账、预算、发票、报价、项目、订单和库存管理、运输等功能。([源代码](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Docker/Perl`
- [Odoo](https://www.odoo.com) - 免费开源ERP系统。([演示](https://demo.odoo.com/), [源代码](https://github.com/odoo/odoo)) `LGPL-3.0` `Python/deb/Docker`
- [OFBiz](https://ofbiz.apache.org/) - 企业资源规划系统,具有一套足够灵活的业务应用程序,可在任何行业中使用。([源代码](https://github.com/apache/ofbiz-framework)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免费开源业务解决方案。([演示](https://www.tryton.org/demo), [源代码](https://foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### 搜索引擎

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[搜索引擎](https://zh.wikipedia.org/wiki/搜索引擎_(计算))是一种[信息检索系统](https://zh.wikipedia.org/wiki/信息检索),旨在帮助查找存储在计算机系统中的信息。这包括[Web搜索引擎](https://zh.wikipedia.org/wiki/网络搜索引擎)。

- [Aleph](https://aleph.occrp.org/) - 用于索引大量文档(PDF、Word、HTML)和结构化(CSV、XLS、SQL)数据的工具,以便轻松浏览和搜索。它以调查报道为主要用例构建。([演示](https://aleph.occrp.org/), [源代码](https://github.com/alephdata/aleph)) `MIT` `Docker/K8S`
- [Amgix](https://amgix.io) - 为灵活部署和现实世界混乱数据而构建的混合搜索引擎。([演示](https://findgovdata.org), [源代码](https://github.com/amgix/amgix-server), [客户端](https://github.com/orgs/amgix/repositories)) `AGPL-3.0` `Docker/K8S`
- [Apache Solr](https://lucene.apache.org/solr/) - 企业搜索平台,具有全文搜索、命中高亮、分面搜索、实时索引、动态聚类和丰富文档(如Word、PDF)处理功能。([源代码](https://github.com/apache/solr)) `Apache-2.0` `Java/Docker/K8S`
- [Fess](https://fess.codelibs.org/) - 功能强大且易于部署的企业搜索服务器。([演示](https://search.n2sm.co.jp/), [源代码](https://github.com/codelibs/fess)) `Apache-2.0` `Java/Docker`
- [Hister](https://hister.org/) - 具有自动索引访问网站的个人Web搜索引擎。支持离线本地结果预览、本地文件、多用户处理和可选的语义搜索。([演示](https://demo.hister.org/), [源代码](https://github.com/asciimoo/hister)) `AGPL-3.0` `Go/Docker`
- [Manticore Search](https://github.com/manticoresoftware/manticoresearch/) - 全文搜索和数据分析,对中小型大数据具有快速响应时间(Elasticsearch的替代品)。`GPL-3.0` `Docker/deb/C++/K8S`
- [MeiliSearch](https://www.meilisearch.com) - 超相关、即时且容错的全文搜索API。([源代码](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust/Docker/deb`
- [Meme Search](https://github.com/neonwatty/meme-search) - AI驱动的表情包搜索引擎。使用视觉语言模型从图像中自动提取描述,然后使用向量嵌入建立索引以进行语义和关键词搜索。([源代码](https://github.com/meme-search/meme-search)) `Apache-2.0` `Docker`
- [OpenSearch](https://opensearch.org) - 分布式RESTful搜索引擎。([源代码](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java/Docker/K8S/deb`
- [SearXNG](https://docs.searxng.org/) `⚠` - 互联网元搜索引擎,聚合来自各种搜索服务和数据库的结果(Searx的分支)。([源代码](https://github.com/searxng/searxng/)) `AGPL-3.0` `Python/Docker`
- [Sosse](https://sosse.readthedocs.io/en/stable/) - 基于Selenium的搜索引擎和爬虫,具有离线归档功能。([源代码](https://gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- [Typesense](https://typesense.org) - 极快、容错的开源搜索引擎,针对开发者的幸福感和易用性进行了优化。([源代码](https://github.com/typesense/typesense)) `GPL-3.0` `C++/Docker/K8S/deb`
- [Websurfx](https://github.com/neon-mmd/websurfx) `⚠` - 从其他搜索引擎聚合结果(元搜索引擎),没有广告,同时考虑隐私和安全。它极其快速并提供高度可定制性(SearX的替代品)。`AGPL-3.0` `Rust/Docker`
- [Yacy](https://yacy.net/en/index.html) - 基于对等体的去中心化搜索引擎服务器。([源代码](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java/Docker/K8S`


### 自托管解决方案

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于轻松安装、管理和配置自托管服务和应用的软件。

- [DietPi](https://dietpi.com/) - 针对单板计算机优化的最小Debian操作系统,允许您轻松安装和管理多个家庭自托管服务。([源代码](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer帮助您开始在Docker中运行家庭服务器应用。([源代码](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [Dropserver](https://dropserver.org) - 您个人Web服务的应用平台。([源代码](https://github.com/teleclimber/Dropserver/)) `Apache-2.0` `Go/Deno`
- [FreedomBox](https://freedombox.org/) - 社区项目,旨在开发、设计和推广运行自由软件的个人服务器,用于私人、个人的通信。([源代码](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- [HomeButler](https://homebutler.dev) - 通过Docker Compose安装和管理精选的应用目录,映射容器和暴露端口,验证备份恢复,并通过CLI、JSON、Web和MCP接口报告自上次运行以来的更改。([源代码](https://github.com/Higangssh/homebutler)) `MIT` `Docker/Go`
- [HomelabOS](https://homelabos.com) - 以隐私为中心的离线数据中心。只需几个命令即可部署100多个服务。([源代码](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [HomeServerHQ](https://www.homeserverhq.com/) - 一体式家庭服务器基础设施和安装程序。即使位于CGNAT后面,也能在一小时内设置完全配置的电子邮件服务器、VPN和公共网站。([源代码](https://github.com/homeserverhq/hshq)) `GPL-3.0` `Shell`
- [LibreServer](https://libreserver.org/) - 基于Debian的家庭服务器配置。([源代码](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
- [Mother-of-All-Self-Hosting](https://github.com/mother-of-all-self-hosting/mash-playbook) - Ansible playbook,帮助您在自己的服务器上作为Docker容器托管服务。`AGPL-3.0` `Ansible/Docker`
- [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - 预装和预配置的Nextcloud,具有文本和Web管理界面以及自托管私有数据所需的所有工具。提供适用于树莓派、Odroid、Rock64、Docker的安装镜像,以及Armbian/Debian的curl安装程序。`GPL-2.0` `Shell/PHP`
- [Nirvati](https://nirvati.org) - 通过方便的Web界面轻松一键启动流行的自托管应用。([源代码](https://gitlab.com/nirvati-ug/nirvati/backend)) `AGPL-3.0` `Rust/K8S`
- [OpenMediaVault](https://www.openmediavault.org/) - 基于Debian Linux的网络附加存储(NAS)解决方案。包含SSH、(S)FTP、SMB/CIFS、DAAP媒体服务器、RSync、BitTorrent客户端等服务。([源代码](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 个人服务器,用于轻松安全地运行自托管应用。([演示](https://demo.sandstorm.io/), [源代码](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Shell`
- [Self Host Blocks](https://github.com/ibizaman/selfhostblocks) `⚠` - 基于NixOS模块的模块化服务器管理,专注于最佳实践。`AGPL-3.0` `Nix`
- [StartOS](https://start9.com) - 基于浏览器的图形操作系统(OS),使运行个人服务器像运行个人电脑一样容易。([源代码](https://github.com/Start9Labs/start-technologies)) `MIT` `Rust`
- [Syncloud](https://syncloud.org/) - 具有应用商店和自动更新的操作系统,适用于Nextcloud、Jellyfin、Bitwarden和Paperless等应用,包括HTTPS、域名和无需公网IP的远程访问。([源代码](https://github.com/syncloud/platform)) `GPL-3.0` `Go/Shell`
- [Tipi](https://runtipi.io/) - 家庭服务器管理器。一键设置,一键安装您喜欢的自托管应用。([源代码](https://github.com/runtipi/runtipi)) `GPL-3.0` `Shell`
- [UBOS](https://ubos.net/) - 运行在独立盒子(个人服务器和IoT设备)上的Linux发行版。应用的单命令安装和管理 - Jenkins、Mediawiki、Owncloud、WordPress等,以及其他功能。`GPL-3.0` `Perl`
- [Websoft9](https://www.websoft9.com) `⚠` - 由GitOps驱动的云服务器和家庭服务器的多应用托管,200+开源应用的一键部署。([演示](https://www.websoft9.com/demo), [源代码](https://github.com/websoft9/websoft9), [客户端](https://www.websoft9.com/apps)) `LGPL-3.0` `Shell/Python`
- [WikiSuite](https://wikisuite.org) - 最全面和集成的自由/开源/开放源码企业软件套件。([源代码](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- [xsrv](https://xsrv.readthedocs.io/) - 在您自己的服务器上安装和管理自托管服务/应用。([源代码](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Ansible/Shell`
- [YunoHost](https://yunohost.org/) - 旨在让每个人都能访问自托管的服务器操作系统。([演示](https://yunohost.org/#/try), [源代码](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### 软件开发

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[软件开发](https://zh.wikipedia.org/wiki/软件开发)是涉及创建和维护应用程序、框架或其他软件组件的构思、规范、设计、编程、文档编制、测试和错误修复的过程。

**请访问 [软件开发 - API管理](#软件开发---api管理), [软件开发 - 持续集成与部署](#软件开发---持续集成与部署), [软件开发 - FaaS和无服务器](#软件开发---faas和无服务器), [软件开发 - IDE和工具](#软件开发---ide和工具), [软件开发 - 本地化](#软件开发---本地化), [软件开发 - 低代码](#软件开发---低代码), [软件开发 - 项目管理](#软件开发---项目管理), [软件开发 - 测试](#软件开发---测试), [软件开发 - 功能开关](#软件开发---功能开关)**


### 软件开发 - API管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[API管理](https://zh.wikipedia.org/wiki/API管理)是创建和发布[应用程序编程接口(API)](https://zh.wikipedia.org/wiki/API)、强制执行其使用策略、控制访问、培养订阅者社区、收集和分析使用统计信息以及报告性能的过程。

- [Aastro](https://voidrunner3074.github.io/aastro-docs) - 用Go编写的可扩展API网关。([源代码](https://github.com/voidrunner3074/aastro)) `Apache-2.0` `Go/Docker`
- [DreamFactory](https://www.dreamfactory.com/) - 将任何SQL/NoSQL/结构化数据转换为Restful API。([源代码](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP/Docker/K8S`
- [form.io](https://form.io) - 一个利用拖放式表单构建器的REST API构建平台,与应用程序框架无关。包含开源和企业版本。([演示](https://portal.form.io), [源代码](https://github.com/formio)) `MIT` `Nodejs/Docker`
- [Fusio](https://www.fusio-project.org/) - 有助于构建和管理REST API的API管理平台。([演示](https://fusio-project.org/demo), [源代码](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP/Docker`
- [Graphweaver](https://graphweaver.com/) - 将多个数据源转换为单个GraphQL API。([源代码](https://github.com/exogee-technology/graphweaver)) `MIT` `Nodejs`
- [Hasura](https://hasura.io) - 在Postgres上快速、即时实时的GraphQL API,具有细粒度的访问控制,还可以在数据库事件上触发webhook。([源代码](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell/Docker/K8S`
- [Hoppscotch Community Edition](https://hoppscotch.io) - 快速美观的API请求构建器。([源代码](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Docker`
- [Kong](https://konghq.com/kong/) - 微服务API网关和平台。([源代码](https://github.com/Kong/kong)) `Apache-2.0` `Lua/Docker/K8S/deb`
- [Lura](https://luraproject.org/) - 高性能API网关。([源代码](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Opik](https://www.comet.com/site/products/opik/) `⚠` - 评估、测试和发布LLM应用程序,使用一套可观测性工具在整个开发和生产生命周期中校准语言模型输出。([源代码](https://github.com/comet-ml/opik)) `Apache-2.0` `Docker/Python`
- [Para](https://paraio.org) - 灵活且模块化的后端框架/服务器,用于对象持久化、API开发和身份验证。([源代码](https://github.com/erudika/para)) `Apache-2.0` `Java/Docker`
- [Svix](https://svix.com) - Webhooks即服务,使API提供商能够超级轻松地发送webhook。([源代码](https://github.com/svix/svix-webhooks)) `MIT` `Docker/Rust`
- [Tyk](https://tyk.io) - 快速且可扩展的开源API网关。开箱即用,Tyk提供一个API管理平台,包括API网关、API分析、开发者门户和API管理仪表板。([源代码](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go/Docker/K8S`


### 软件开发 - 持续集成与部署

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[持续集成](https://zh.wikipedia.org/wiki/持续集成)和[持续部署](https://zh.wikipedia.org/wiki/持续部署)软件和工具。

**请访问 [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**

_相关: [自动化](#自动化)_


### 软件开发 - FaaS和无服务器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[无服务器计算](https://zh.wikipedia.org/wiki/无服务器计算)、[功能即服务(FaaS)](https://zh.wikipedia.org/wiki/功能即服务)和[平台即服务(PaaS)](https://zh.wikipedia.org/wiki/平台即服务)管理软件。

**请访问 [awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas)**


### 软件开发 - 功能开关

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

软件开发中的[功能开关](https://zh.wikipedia.org/wiki/功能切换)提供了在源代码中维护多个功能分支的替代方案。

_相关: [软件开发 - IDE和工具](#软件开发---ide和工具)_

- [Featbit](https://www.featbit.co/) - 企业级功能标志平台,您可以自托管。([源代码](https://github.com/featbit/featbit)) `MIT` `Docker/K8S`
- [Flagsmith](https://flagsmith.com) - 用于向应用程序添加功能标志的仪表板、API和SDK(LaunchDarkly的替代品)。([源代码](https://github.com/flagsmith/flagsmith)) `BSD-3-Clause` `Docker/K8S`
- [Flipt](https://flipt.io) - 支持多种数据后端的功能标志解决方案(LaunchDarkly的替代品)。([源代码](https://github.com/flipt-io/flipt)) `GPL-3.0` `Docker/K8S/Go`
- [GO Feature Flag](https://gofeatureflag.org) - 简单、完整且轻量级的功能标志解决方案(LaunchDarkly的替代品)。([源代码](https://github.com/thomaspoignant/go-feature-flag)) `MIT` `Go`
- [Nona](https://nonaconfig.com) - 远程配置和功能标志服务,具有单个REST API、多环境以及官方JavaScript和.NET客户端(Firebase Remote Config的替代品)。([源代码](https://github.com/Ryware/nona-config)) `Apache-2.0` `Docker`


### 软件开发 - IDE和工具

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[集成开发环境(IDE)](https://zh.wikipedia.org/wiki/集成开发环境)是一种软件应用程序,为计算机程序员提供全面的软件开发设施。

_相关: [软件开发 - 低代码](#软件开发---低代码)_

- [Atheos](https://www.atheos.io) - 基于Web的IDE框架,占用空间小,要求最低,从Codiad延续而来。([源代码](https://github.com/Atheos/Atheos)) `MIT` `PHP/Docker`
- [code-server](https://github.com/coder/code-server) - 浏览器中的VS Code,托管在远程服务器上。`MIT` `Nodejs/Docker`
- [Coder](https://coder.com/) - 在您自己的基础设施上的远程开发机器。([源代码](https://github.com/coder/coder)) `AGPL-3.0` `Go/Docker/K8S/deb`
- [Eclipse Che](https://www.eclipse.org/che/) - 开源工作区服务器和云IDE。([源代码](https://github.com/eclipse-che/che)) `EPL-1.0` `Docker/Java`
- [Hopp](https://gethopp.app) - 远程配对编程应用,具有低延迟4K屏幕共享、绘图和远程控制功能,提供macOS和Windows客户端(Tuple、Pop、Drovio、Coscreen的替代品)。([源代码](https://github.com/gethopp/hopp)) `AGPL-3.0` `Docker`
- [Judge0 CE](https://judge0.com) - 用于编译和运行源代码的API。([源代码](https://github.com/judge0/judge0)) `GPL-3.0` `Docker`
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - 用于交互式和可重现计算的基于Web的环境。([演示](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [源代码](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Langfuse](https://langfuse.com) - LLM工程平台,用于模型追踪、提示管理和应用评估。Langfuse帮助团队协作调试、分析和迭代他们的LLM应用程序,如聊天机器人或AI代理。([演示](https://langfuse.com/docs/demo), [源代码](https://github.com/langfuse/langfuse), [客户端](https://langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- [LiveCodes](https://livecodes.io/docs/features/self-hosting) `⚠` - 功能丰富的客户端代码游乐场,支持React、Vue、Svelte、Solid、Typescript、Python、Go、Ruby、PHP等90多种语言。([演示](https://livecodes.io), [源代码](https://github.com/live-codes/livecodes)) `MIT` `Nodejs`
- [Lowdefy](https://www.lowdefy.com/) - 使用YAML / JSON在几分钟内构建内部工具、BI仪表板、管理面板、CRUD应用和工作流。([源代码](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs/Docker`
- [RapidForge](https://rapidforge.io/) - 用于构建webhook、计划任务和页面的轻量级平台。使用Bash或Lua实现您的逻辑。([源代码](https://github.com/rapidforge-io/rapidforge)) `Apache-2.0` `Go/Nodejs`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于Web浏览器的R语言IDE。([源代码](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`


### 软件开发 - 本地化

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[本地化](https://zh.wikipedia.org/wiki/国际化和本地化)是将代码和软件适配到其他语言的过程。

- [Accent](https://www.accent.reviews/) - 面向开发者的翻译工具。([源代码](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir/Docker`
- [Tolgee](https://tolgee.io) - 对开发者和翻译者友好的基于Web的本地化平台,使用户可以直接在他们开发的应用中进行翻译。([源代码](https://github.com/tolgee/tolgee-platform)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.co) - 团队的翻译管理平台。([源代码](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/K8S/Nodejs`
- [Weblate](https://weblate.org) - 具有紧密版本控制集成的基于Web的翻译工具。([源代码](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python/Docker/K8S`


### 软件开发 - 低代码

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[低代码](https://zh.wikipedia.org/wiki/低代码开发平台)开发平台(LCDP)提供一个开发环境,用于通过图形用户界面创建应用软件。

_相关: [软件开发 - IDE和工具](#软件开发---ide和工具)_

- [Appsmith](https://www.appsmith.com/) - 构建管理面板、CRUD应用和工作流。构建您需要的一切,速度快10倍。([源代码](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker/K8S`
- [Appwrite](https://appwrite.io) - 面向Web、原生和移动开发者的端到端后端服务器 🚀。([源代码](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `Docker`
- [Halo](https://www.halo.run) - 一个强大且易于使用的网站构建工具(文档为中文)。([演示](https://docs.halo.run/#%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C), [源代码](https://github.com/halo-dev/halo), [客户端](https://github.com/halo-sigs/awesome-halo)) `GPL-3.0` `Java/Docker`
- [Manifest](https://manifest.build) - 适合放入1个YAML文件的完整后端。([演示](https://manifest.new), [源代码](https://github.com/mnfst/llm-gateway)) `MIT` `Nodejs`
- [PocketBase](https://pocketbase.io/) - 您下一个SaaS和移动应用的后端,只需一个文件。([源代码](https://github.com/pocketbase/pocketbase)) `MIT` `Go/Docker`
- [Saltcorn](https://saltcorn.com/) - 用于Web和移动应用的无代码数据库应用构建器。一个平台涵盖用户界面、数据后端、持久工作流、电子邮件、PDF生成和AI应用。([源代码](https://github.com/saltcorn/saltcorn)) `MIT` `Docker/Nodejs`
- [SQLPage](https://sql-page.com) - 仅使用SQL的动态网站构建器。([源代码](https://github.com/sqlpage/SQLPage)) `MIT` `Rust/Docker`
- [ToolJet](https://tooljet.io/) - 低代码框架,以最小的工程工作量构建和部署内部工具(Retool和Mendix的替代品)。([源代码](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs/Docker/K8S`
- [TrailBase](https://trailbase.io/) - 开放、亚毫秒级、单可执行文件的FireBase替代品,具有类型安全的REST和实时API、内置JS/TS运行时、认证和管理UI。([演示](https://demo.trailbase.io), [源代码](https://github.com/trailbaseio/trailbase)) `OSL-3.0` `Rust/Docker`


### 软件开发 - 项目管理

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于[软件项目管理](https://zh.wikipedia.org/wiki/软件项目管理)的工具和软件。

_相关: [工单系统](#工单系统), [任务管理和待办事项列表](#任务管理和待办事项列表)_

- [Cgit](https://git.zx2c4.com/cgit/about/) - 快速轻量级的git仓库Web界面。([源代码](https://git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- [Forgejo](https://forgejo.org) - 专注于可扩展性、联邦化和隐私的轻量级软件锻造平台(Gitea的分支)。([演示](https://next.forgejo.org), [源代码](https://codeberg.org/forgejo/forgejo/), [客户端](https://codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 具有wiki和错误跟踪功能的分布式版本控制系统。`BSD-2-Clause-FreeBSD` `C`
- [Gerrit](https://www.gerritcodereview.com/) - 基于Git项目的代码审查和项目管理工具。([源代码](https://github.com/GerritCodeReview/gerrit)) `Apache-2.0` `Java/Docker`
- [gitbucket](https://gitbucket.github.io/) - Git平台,具有易于安装、高扩展性和GitHub API兼容性(GitHub的替代品)。([源代码](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.com) - 用一杯茶来享受Git! 无痛的自托管一站式软件开发服务,包括Git托管、代码审查、团队协作、包注册表和CI/CD。([演示](https://gitea.com/explore/repos), [源代码](https://github.com/go-gitea/gitea)) `MIT` `Go/Docker/K8S`
- [GitLab](https://about.gitlab.com) - 自托管Git仓库管理、代码审查、问题跟踪、活动流和wiki。([演示](https://gitlab.com/), [源代码](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- [Gogs](https://gogs.io/) - 用Go编写的无痛自托管Git服务。([源代码](https://github.com/gogs/gogs)) `MIT` `Go`
- [Huly](https://huly.io) - 一体化项目管理平台(Linear、Jira、Slack、Notion、Motion的替代品)。([演示](https://app.huly.io), [源代码](https://github.com/hcengineering/platform)) `EPL-2.0` `Docker/K8S/Nodejs`
- [Ideon](https://www.theideon.com) - 围绕无限画布构建的项目工作区;将GitHub、GitLab、Gitea和Forgejo仓库与笔记、链接和任务一起嵌入,支持实时协作。([源代码](https://github.com/3xpyth0n/ideon)) `AGPL-3.0` `Docker`
- [Kaneo](https://kaneo.app/) - 专注于简单性和效率的项目管理平台。([演示](https://demo.kaneo.app/), [源代码](https://github.com/usekaneo/kaneo)) `MIT` `K8S/Docker`
- [Leantime](https://leantime.io) - 面向小团队和初创公司的精益项目管理系统,帮助从构思到交付管理项目。([源代码](https://github.com/leantime/leantime)) `AGPL-3.0` `PHP/Docker`
- [Mindwendel](https://www.mindwendel.com/) - 团队内头脑风暴和投票想法与思考。([演示](https://www.mindwendel.com), [源代码](https://github.com/b310-digital/mindwendel)) `AGPL-3.0` `Docker/Elixir`
- [minimal-git-server](https://github.com/mcarbonne/minimal-git-server) - 具有基本CLI的轻量级git服务器,用于管理仓库,支持多个账户并在容器中运行。`MIT` `Docker`
- [Octobox](https://octobox.io/) `⚠` - 重新控制您的GitHub通知。([源代码](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby/Docker`
- [OneDev](https://onedev.io/) - 一体化DevOps平台。具有Git管理、问题跟踪和CI/CD。简单而强大。([源代码](https://github.com/theonedev/onedev)) `MIT` `Java/Docker/K8S`
- [OpenProject](https://www.openproject.org) - 管理您的项目、任务和目标。通过工作包进行协作,并将它们链接到Github上的拉取请求。([源代码](https://github.com/opf/openproject)) `GPL-3.0` `Ruby/deb/Docker`
- [Paca](https://paca-ai.org) - AI原生项目管理平台,AI代理和人类在同一看板和冲刺中作为Scrum队友协作。可通过配置文件和WASM插件进行配置(Jira、Trello、ClickUp和Monday的替代品)。([源代码](https://github.com/Paca-AI/paca)) `Apache-2.0` `Docker/K8S`
- [Pagure](https://pagure.io/pagure) - 轻量级、强大且灵活的以git为中心的锻造平台,具有为联邦化和去中心化开发奠定基础的功能。([演示](https://pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- [Phorge](https://we.phorge.it/) - 社区驱动的平台,用于协作、管理、组织和审查软件开发项目。([源代码](https://we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- [Plane](https://plane.so) - 以最简单的方式跟踪问题、史诗和产品路线图(JIRA、Linear和Height的替代品)。([演示](https://app.plane.so), [源代码](https://github.com/makeplane/plane)) `AGPL-3.0` `Docker`
- [ProjeQtOr](https://www.projeqtor.org/) - 完整、成熟的多用户项目管理系统,具有适用于项目所有阶段的广泛功能。([演示](https://demo.projeqtor.org/), [源代码](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](https://www.redmine.org/) - 灵活的项目管理Web应用。([源代码](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [Review Board](https://www.reviewboard.org/) - 可扩展且友好的代码审查工具,适用于各种规模的项目和公司。([演示](https://demo.reviewboard.org/), [源代码](https://github.com/reviewboard/reviewboard)) `MIT` `Python/Docker`
- [RhodeCode](https://rhodecode.com/) - 统一和简化Git、Subversion和Mercurial的仓库管理。([源代码](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [Rukovoditel](https://www.rukovoditel.net/) - 可配置的开源项目管理,基于Web的应用程序。([源代码](https://www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- [SCM Manager](https://www.scm-manager.org/) - 通过http共享和管理Git、Mercurial和Subversion仓库的最简单方法。([源代码](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java/deb/Docker/K8S`
- [Smederee](https://smeder.ee) - 一个节俭的平台,致力于帮助人们利用Darcs版本控制系统的力量一起构建优秀的软件。([源代码](https://smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- [Sourcehut](https://sourcehut.org/) - 完整的无JavaScript Web git界面。([演示](https://sr.ht/), [源代码](https://git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- [Taiga](https://www.taiga.io/) - 基于看板和Scrum方法的敏捷项目管理工具。([源代码](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- [Titra](https://titra.io/) - 面向自由职业者和小团队的时间跟踪解决方案。([源代码](https://github.com/titraio/titra)) `GPL-3.0` `Javascript/Docker`
- [Trac](https://trac.edgewall.org/) - Trac是软件开发项目的增强型wiki和问题跟踪系统。`BSD-3-Clause` `Python/deb`
- [Traq](https://traq.io/) - 用PHP编写的项目管理和问题跟踪系统。([源代码](https://github.com/nirix/traq)) `GPL-3.0` `PHP/Nodejs`
- [Tuleap](https://www.tuleap.org/) - Tuleap是一套自由软件套件,用于规划、跟踪、编码和协作软件项目。([源代码](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [ZenTao](https://www.zentao.pm/) - 敏捷(scrum)项目管理系统/工具。([源代码](https://github.com/easysoft/zentaopms)) `AGPL-3.0` `PHP`


### 软件开发 - 测试

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

用于[软件测试](https://zh.wikipedia.org/wiki/软件测试)的工具和软件。

- [Bencher](https://bencher.dev/) - 一套持续基准测试工具,旨在捕获CI中的性能回归。([源代码](https://github.com/bencherdev/bencher)) `MIT/Apache-2.0` `Rust`
- [Request Inbox](https://request-inbox.com/) - 收集和检查HTTP请求以进行测试和调试。创建和管理收件箱,捕获详细的请求数据,配置自定义响应。([演示](https://request-inbox.com/), [源代码](https://github.com/jesusnoseq/request-inbox)) `Apache-2.0` `Docker`
- [WebHook Tester](https://github.com/tarampampam/webhook-tester) - 用于测试WebHook等的强大工具。`MIT` `Docker/Go/deb/K8S`


### 静态站点生成器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[静态站点生成器](https://zh.wikipedia.org/wiki/Web模板系统#静态站点生成器)基于原始数据、纯文本文件和一组模板生成完整的静态HTML网站。

**请访问 [staticsitegenerators.bevry.me](https://staticsitegenerators.bevry.me), [staticgen.com](https://www.staticgen.com)**

_相关: [博客平台](#博客平台), [照片画廊](#照片画廊), [内容管理系统(CMS)](#内容管理系统cms)_


### 任务管理和待办事项列表

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[任务管理](https://zh.wikipedia.org/wiki/任务管理#任务管理软件)软件。

_相关: [软件开发 - 项目管理](#软件开发---项目管理), [工单系统](#工单系统)_

- [4ga Boards](https://4gaboards.com) - 简单直观的实时看板管理,用于直观的任务跟踪。具有优雅的深色模式、可折叠的待办事项列表和多任务工具,以提升团队生产力。([演示](https://demo.4gaboards.com), [源代码](https://github.com/RARgames/4gaBoards)) `MIT` `Nodejs/Docker/K8S`
- [AppFlowy](https://appflowy.io/) - 为不同项目构建详细的待办事项列表,同时跟踪每个项目的状态。开源Notion替代品。([源代码](https://github.com/AppFlowy-IO/appflowy)) `AGPL-3.0` `Rust/Dart/Docker`
- [dayGLANCE](https://dayglance.app) - 具有拖放时间块、收件箱、重复任务、习惯、例程、目标、项目和番茄钟专注模式的日程规划器,以及iCal和CalDAV日历同步。数据保留在浏览器中,可选择WebDAV或GLANCEvault同步。([源代码](https://github.com/krelltunez/dayGLANCE), [客户端](https://github.com/glance-apps/glance-vault)) `MIT` `Javascript/Docker`
- [Donetick](https://donetick.com) - 个人和家庭使用的任务和家务管理工具,具有高级调度、灵活分配和组共享功能,详细历史记录,通过API自动化,简单现代的设计。([演示](https://app.donetick.com/), [源代码](https://github.com/donetick/donetick)) `AGPL-3.0` `Go/Docker`
- [Focus Flow](https://github.com/francesco-gaglione/focus_flow_cloud) - 使用番茄钟技术进行时间管理的完整生态系统。`MIT` `Docker/K8S`
- [HamsterBase Tasks](https://tasks.hamsterbase.com) - 帮助您组织想法并构建伟大事物的工具。规划、组织、构建和发布。([演示](https://tasks-app.hamsterbase.com), [源代码](https://github.com/hamsterbase/tasks)) `AGPL-3.0` `Docker`
- [Kan](https://kan.bn/) - 灵活的看板应用,帮助您组织工作、跟踪进度和交付结果(Trello的替代品)。([源代码](https://github.com/kanbn/kan)) `AGPL-3.0` `Docker`
- [Kanboard](https://kanboard.org/) - 简单的可视化任务板。([源代码](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [Listaway](https://github.com/jeffrpowell/listaway/) - 用于创建和公开共享项目列表的列表管理应用。支持身份验证、管理工具、项目注释和优先级,以及可选择加入的带随机URL的公共只读链接(Amazon Lists的替代品)。([源代码](https://github.com/jeffrpowell/listaway)) `MIT` `Docker`
- [myTinyTodo](https://www.mytinytodo.net/) - 以AJAX风格管理您的待办事项列表的简单方法。使用PHP、jQuery、SQLite/MySQL。符合GTD标准。([演示](https://www.mytinytodo.net/demo/), [源代码](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页面极简主义看板;紧凑、高度易读且快速使用。([演示](https://nullboard.io/preview)) `BSD-2-Clause` `Javascript`
- [OpenHabitTracker](https://openhabittracker.net) - 跟踪习惯、任务和笔记,具有时间跟踪、日历视图和完成统计。([演示](https://pwa.openhabittracker.net), [源代码](https://github.com/Jinjinov/OpenHabitTracker)) `GPL-3.0` `Docker`
- [Our Shopping List](https://codeberg.org/nanawel/our-shopping-list) - 简单的共享列表应用,包括购物清单和任何其他需要协作使用的小型待办事项列表。([演示](https://osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- [Super Productivity](https://super-productivity.com) - 高级待办事项列表应用,具有集成的时间盒和时间跟踪功能。与Jira、GitHub、GitLab、Redmine和OpenProject集成。([源代码](https://github.com/super-productivity/super-productivity)) `MIT` `Docker`
- [Task Keeper](https://github.com/nymanjens/piga) - 面向高级用户的列表编辑器,由自托管服务器支持。`Apache-2.0` `Scala`
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) - 基于文件的自托管任务管理板,支持Markdown语法。`MIT` `Docker`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior是免费开源软件,从命令行管理您的TODO列表。它灵活、快速、高效且不引人注目。它完成工作后就会让路。([源代码](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tellor](https://tellor.cc/) - 极简主义单用户看板待办应用。干净、简洁且紧凑的UI。可以从Trello导入看板。([演示](https://tellor.cc/demo/?b=18486f63be6bb5f2), [源代码](https://github.com/Voldrix/Tellor)) `MIT` `PHP`
- [Tracks](https://www.getontracks.org/) - 基于Web的应用程序,帮助您实施David Allen的[Getting Things Done™](https://zh.wikipedia.org/wiki/GTD工作法)方法论。([源代码](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [tududi](https://tududi.com/) - 具有分层结构、智能重复任务和无缝Telegram集成的任务管理工具。([源代码](https://github.com/chrisvel/tududi)) `MIT` `Docker`
- [Vikunja](https://vikunja.io/) - 组织您生活的待办应用。([演示](https://try.vikunja.io/login), [源代码](https://github.com/go-vikunja/vikunja)) `AGPL-3.0/GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 类似Trello的看板。([源代码](https://github.com/wekan/wekan)) `MIT` `Nodejs`
- [Will Be Done](https://will-be-done.app/) - 以离线优先的任务管理器,具有周计划、项目看板、实时同步、Vim键绑定、桌面快速添加和从流行任务管理器导入的功能(TickTick、Todoist的替代品)。([演示](https://demo.will-be-done.app/), [源代码](https://github.com/will-be-done/will-be-done)) `AGPL-3.0` `Docker/Nodejs`


### 工单系统

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[帮助台](https://zh.wikipedia.org/wiki/帮助台软件)、[错误](https://zh.wikipedia.org/wiki/缺陷跟踪系统)和[问题](https://zh.wikipedia.org/wiki/问题跟踪系统)跟踪软件,用于帮助跟踪用户请求、错误和缺失功能。

_相关: [任务管理和待办事项列表](#任务管理和待办事项列表), [软件开发 - 项目管理](#软件开发---项目管理)_

- [BugPin](https://bugpin.io) - Web应用的可视化错误报告和工单工具。([源代码](https://github.com/aranticlabs/bugpin)) `AGPL-3.0/MIT` `Docker`
- [Bugzilla](https://www.bugzilla.org/) - 通用错误跟踪器和测试工具,最初由Mozilla项目开发和使用。([源代码](https://github.com/bugzilla/bugzilla)) `MPL-2.0` `Perl`
- [Frappe Helpdesk](https://frappe.io/helpdesk) - 帮助台软件,帮助您简化公司支持,提供易于设置、简洁的用户界面和自动化工具,以高效解决客户查询。([源代码](https://github.com/frappe/helpdesk)) `AGPL-3.0` `Docker`
- [FreeScout](https://freescout.net/) - 基于电子邮件的客户支持应用、帮助台和共享邮箱(Zendesk和Help Scout的替代品)。([演示](https://demo.freescout.net/login), [源代码](https://github.com/freescout-help-desk/freescout)) `AGPL-3.0` `PHP/Docker`
- [GlitchTip](https://glitchtip.com) - 错误跟踪应用,用于收集应用程序报告的错误。([源代码](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- [ITFlow](https://itflow.org) - 面向MSP(托管服务提供商)的客户IT文档、工单、发票和会计系统。([演示](https://demo.itflow.org), [源代码](https://github.com/itflow-org/itflow)) `GPL-3.0` `PHP`
- [Libredesk](https://libredesk.io/) - 现代全渠道客户支持台。实时聊天、电子邮件等,全部在一个二进制文件中。([演示](https://demo.libredesk.io), [源代码](https://github.com/abhinavxd/libredesk)) `AGPL-3.0` `Docker/Go/Nodejs`
- [MantisBT](https://www.mantisbt.org/) - 错误跟踪器,最适合用于软件开发。([演示](https://www.mantisbt.org/bugs/my_view_page.php), [源代码](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.io/en/) - 灵活的基于Web的工单系统,用于客户服务、帮助台和IT服务管理。([演示](https://otobo.io/en/service-management-plattform/otobo-demo/), [源代码](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl/Docker`
- [Request Tracker](https://www.bestpractical.com/rt/) - 企业级问题跟踪系统。([源代码](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup Issue Tracker](https://www.roundup-tracker.org/) - 简单易用和安装的问题跟踪系统,具有命令行、Web、REST、XML-RPC和电子邮件接口。设计时考虑了灵活性 - 不仅仅是另一个错误跟踪器。([源代码](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- [Rustrak](https://rustrak.github.io/rustrak/) - 与Sentry SDK兼容的错误跟踪服务器,空闲时使用32MB内存和SQLite存储。([源代码](https://github.com/rustrak/rustrak)) `GPL-3.0` `Rust/Docker`
- [Zammad](https://zammad.org/) - 易于使用但强大的支持和工单系统。([源代码](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby/deb`


### 时间跟踪

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[时间跟踪软件](https://zh.wikipedia.org/wiki/时间跟踪软件)是一类计算机软件,允许其用户记录在任务或项目上花费的时间。

- [ActivityWatch](https://activitywatch.net) - 自动跟踪您在设备上花费的时间。([源代码](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits) - 习惯跟踪应用,保存您短暂生命中的珍贵时刻。([演示](https://beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- [Ever Gauzy](https://gauzy.co) - 开放式业务管理平台,适用于协作、按需和共享经济(ERP/CRM/HRM/ATS/PM)。([演示](https://demo.gauzy.co), [源代码](https://github.com/ever-co/ever-gauzy)) `AGPL-3.0` `Docker/Nodejs`
- [Kimai](https://www.kimai.org/) - 跟踪工作时间并按需打印活动摘要。([演示](https://www.kimai.org/demo/), [源代码](https://github.com/kimai/kimai)) `AGPL-3.0` `PHP`
- [solidtime](https://www.solidtime.io) - 面向自由职业者和代理机构的现代时间跟踪应用。([源代码](https://github.com/solidtime-io/solidtime)) `AGPL-3.0` `Docker`
- [TimeTagger](https://timetagger.app) - 基于交互式时间线和强大报告的开源时间跟踪器。([演示](https://timetagger.app/app/demo), [源代码](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`
- [TimeTracker](https://timetracker.drytrix.com/) - 跨项目和客户端跟踪时间,具有计时器、看板任务、CRM、费用跟踪、多货币发票(PDF、Peppol/ZugFerd电子发票)、报告、OIDC/SSO和REST API。([源代码](https://github.com/drytrix/TimeTracker)) `GPL-3.0` `Docker`
- [Traggo](https://traggo.net/) - Traggo是基于标签的时间跟踪工具。在Traggo中没有任务,只有带标签的时间段。([源代码](https://github.com/traggo/server)) `GPL-3.0` `Docker/Go`
- [Wakapi](https://wakapi.dev/) - 编码统计跟踪工具,兼容WakaTime。([源代码](https://github.com/muety/wakapi)) `GPL-3.0` `Go/Docker`
- [Ziit](https://ziit.app) - 代码时间跟踪的瑞士军刀(WakaTime的替代品)。([源代码](https://github.com/0pandadev/ziit)) `AGPL-3.0` `Docker`


### 旅行组织

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

旅行组织软件,用于记录预订、查看行程、规划活动和跟踪费用。

_相关: [预订和调度](#预订和调度), [地图和全球定位系统(GPS)](#地图和全球定位系统gps)_

- [Surmai](https://surmai.app/) - 协作式个人和家庭旅行组织者。([演示](https://demo.surmai.app), [源代码](https://github.com/rohitkumbhar/surmai)) `MIT` `Docker`
- [TREK](https://github.com/liketrek/TREK) - 具有交互式地图、逐日行程、预算、打包清单、预订、旅行日志和PWA支持的协作式旅行规划器。([演示](https://demo.liketrek.com/)) `AGPL-3.0` `Docker/K8S`


### URL缩短服务

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[URL缩短](https://zh.wikipedia.org/wiki/URL缩短)是将[URL](https://zh.wikipedia.org/wiki/统一资源定位符)缩短使其明显变短但仍能定向到所需页面的操作。在托管之前,请参阅URL缩短服务的[缺点](https://zh.wikipedia.org/wiki/URL缩短#缺点)。

- [bit](https://github.com/sjdonado/bit) - 快速、轻量级、资源高效的编译型URL缩短器。`MIT` `Docker/Crystal`
- [Chhoto URL](https://chhoto.link) - 简单、闪电般快速的URL缩短器,没有臃肿功能(simply-shorten的分支)。([演示](https://github.com/SinTan1729/chhoto-url?tab=readme-ov-file#demo), [源代码](https://github.com/SinTan1729/chhoto-url), [客户端](https://github.com/SinTan1729/chhoto-url/blob/main/TOOLS.md)) `MIT` `Rust/Docker`
- [clink](https://git.crueter.xyz/crueter/clink) - 用纯C编写的超极简链接缩短服务,专注于小型可执行文件大小、便携性和易于配置。([演示](https://short.crueter.xyz)) `AGPL-3.0` `C`
- [Flink](https://gitlab.com/rtraceio/web/flink) - 创建QR码、为您的网站创建可嵌入的链接预览,并抓取/爬取元数据。([演示](https://flink.is)) `MIT` `Docker`
- [Kutt](https://kutt.to) - 支持自定义域和自定义URL的现代URL缩短器。([演示](https://kutt.to), [源代码](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs/Docker`
- [rs-short](https://git.42l.fr/42l/rs-short) - 用Rust编写的轻量级链接缩短器,具有缓存、垃圾邮件机器人保护和钓鱼检测等功能。([演示](https://s.42l.fr/)) `MPL-2.0` `Rust`
- [Shlink](https://shlink.io) - 具有REST API和命令行界面的URL缩短器。包括官方渐进式Web应用和Docker镜像。([源代码](https://github.com/shlinkio/shlink), [客户端](https://shlink.io/apps)) `MIT` `PHP/Docker`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL缩短器,公共或私有(带账户)。极简主义且轻量级。无依赖。([演示](https://u.azlux.fr)) `MIT` `PHP`
- [YOURLS](https://yourls.org/) - YOURLS是一套允许您运行自己的URL缩短器的PHP脚本。功能包括密码保护、URL自定义、书签小工具、统计信息、API、插件、jsonp。([源代码](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### 视频监控

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

视频监控,也称为[闭路电视(CCTV)](https://zh.wikipedia.org/wiki/闭路电视),是在需要额外安全或持续监控的区域使用摄像机进行监控。

_相关: [媒体流媒体 - 视频流媒体](#媒体流媒体---视频流媒体)_

- [Bluecherry](https://github.com/bluecherrydvr/bluecherry-apps) - 支持IP和模拟摄像机的闭路电视(CCTV)软件应用。`GPL-2.0` `PHP`
- [Frigate](https://frigate.video/) - 使用本地处理AI监控您的安全摄像头。([源代码](https://github.com/blakeblackshear/frigate)) `MIT` `Docker/Python/Nodejs`
- [motionEye](https://github.com/motioneye-project/motioneye) - 软件Motion的在线界面,这是一个具有运动检测功能的视频监控程序。`GPL-3.0` `Python/Docker`
- [Secluso](https://secluso.com) - 面向树莓派的私有DIY家庭安全摄像头系统,具有端到端加密的远程访问和用于实时视频、警报和录制回放的移动应用。([源代码](https://github.com/secluso/core)) `GPL-3.0` `Rust`
- [SentryShot](https://codeberg.org/SentryShot/sentryshot) - 视频监控系统。`GPL-2.0` `Docker/Rust`
- [Strix](https://github.com/eduard256/Strix) - 自动发现IP摄像头的有效流URL,并生成即用型Frigate和go2rtc配置。`MIT` `Go/Docker`
- [Viseron](https://viseron.netlify.app/) - 自托管、仅本地的NVR和AI计算机视觉软件。具有目标检测、运动检测、人脸识别等功能,让您能够监视家庭、办公室或任何您想要监控的地方。([源代码](https://github.com/roflcoopter/viseron)) `MIT` `Docker`
- [Zoneminder](https://www.zoneminder.com/) - 支持IP、USB和模拟摄像机的闭路电视(CCTV)软件应用。([源代码](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP/deb`


### VPN

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[虚拟专用网络(VPN)](https://zh.wikipedia.org/wiki/虚拟专用网络)将专用网络扩展到公共网络上,并允许用户通过共享或公共网络发送和接收数据,就像其计算设备直接连接到专用网络一样。

**请访问 [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**

_另见: [Awesome-Tunneling](https://github.com/anderspitman/awesome-tunneling)_


### Web服务器

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

Web服务器和反向代理。[Web服务器](https://zh.wikipedia.org/wiki/Web服务器)是通过[HTTP](https://zh.wikipedia.org/wiki/超文本传输协议)(为分发Web内容而创建的网络协议)或其安全变体[HTTPS](https://zh.wikipedia.org/wiki/HTTPS)接受请求的软件和底层硬件。[反向代理](https://zh.wikipedia.org/wiki/反向代理)是一个代理服务器,对任何客户端来说看起来像普通的Web服务器,但实际上仅作为将请求转发到一个或多个普通Web服务器的中间人。

_相关: [代理](#代理)_

- [Algernon](https://algernon.roboticoverlords.org/) - 小型自包含的纯Go Web服务器,支持Lua、Markdown、HTTP/2、QUIC、Redis和PostgreSQL。([源代码](https://github.com/xyproto/algernon)) `BSD-3-Clause` `Go/Docker`
- [Apache HTTP Server](https://httpd.apache.org/) - 安全、高效且可扩展的服务器,提供与当前HTTP标准同步的HTTP服务。([源代码](https://svn.apache.org/repos/asf/httpd/httpd/trunk/)) `Apache-2.0` `C/deb/Docker`
- [BunkerWeb](https://www.bunkerweb.io) - 下一代Web应用防火墙(WAF),保护您的Web服务。([演示](https://demo.bunkerweb.io), [源代码](https://github.com/bunkerity/bunkerweb), [客户端](https://docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- [Caddy](https://caddyserver.com/) - 功能强大、企业就绪、具有自动HTTPS的开源Web服务器。([源代码](https://github.com/caddyserver/caddy)) `Apache-2.0` `Go/deb/Docker`
- [Ferron](https://ferron.sh/) - 用Rust编写的快速、内存安全的Web服务器。([源代码](https://github.com/ferronweb/ferron)) `MIT` `Rust/Docker/deb`
- [go-doxy](https://github.com/yusing/godoxy) - 轻量级、简单且高性能的反向代理,具有WebUI、Docker集成、基于流量的容器自动关闭/启动。`MIT` `Docker/Go`
- [HAProxy](https://www.haproxy.org/) - 非常快速可靠的反向代理,为基于TCP和HTTP的应用提供高可用性、负载均衡和代理。([源代码](https://git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- [Lighttpd](https://www.lighttpd.net/) - 安全、快速、合规且非常灵活的Web服务器,已针对高性能环境进行优化。([源代码](https://git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - 用于管理Nginx代理主机的Docker容器,具有简单而强大的界面。([源代码](https://github.com/NginxProxyManager/nginx-proxy-manager)) `MIT` `Docker`
- [NGINX](https://nginx.org/en/) - HTTP和反向代理服务器、邮件代理服务器以及通用TCP/UDP代理服务器。([源代码](https://github.com/nginx/nginx)) `BSD-2-Clause` `C/deb/Docker`
- [Pangolin](https://digpangolin.com/) - 具有身份感知的隧道反向代理,具有仪表板UI、访问控制和基于WireGuard的隧道(Cloudflare Tunnel、Tailscale的替代品)。([源代码](https://github.com/fosrl/pangolin)) `AGPL-3.0` `Docker`
- [Pomerium](https://www.pomerium.io) - 具有身份感知的反向代理,现已过时的oauth_proxy的继任者。它在将您的请求代理到后端之前插入OAuth步骤,以便您可以安全地将自托管网站暴露到公共互联网。([源代码](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go/Docker`
- [SafeLine](https://waf.chaitin.com/) - Web应用防火墙/反向代理,保护您的Web应用免受攻击和利用。([演示](https://demo.waf.chaitin.com/), [源代码](https://github.com/chaitin/SafeLine)) `GPL-3.0` `Docker`
- [Static Web Server](https://static-web-server.net/) - 跨平台、高性能且异步的静态文件服务Web服务器。([源代码](https://github.com/static-web-server/static-web-server)) `Apache-2.0/MIT` `Rust/Docker`
- [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - 具有PHP支持的Nginx Web服务器和反向代理,内置Certbot(Let's Encrypt)客户端和fail2ban集成。`GPL-3.0` `Docker`
- [Traefik](https://traefik.io/) - HTTP反向代理和负载均衡器,使部署微服务变得容易。([源代码](https://github.com/traefik/traefik)) `MIT` `Go/Docker`
- [UUSEC WAF](https://waf.uusec.com/) - 行业领先的高性能、AI和语义技术Web应用防火墙和API安全网关(nginx的分支)。([源代码](https://github.com/Safe3/uusec-waf)) `GPL-3.0` `C/Lua/Docker`
- [Vinyl Cache](https://vinyl-cache.org/) - Web应用加速器/缓存HTTP反向代理(原Varnish)。([源代码](https://code.vinyl-cache.org/vinyl-cache/vinyl-cache)) `BSD-2-Clause` `Go/deb/Docker`
- [Zoraxy](https://zoraxy.aroz.org/) - 通用HTTP反向代理和转发工具。([源代码](https://github.com/tobychui/zoraxy)) `AGPL-3.0` `Go/Docker`


### 维基

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

[维基](https://zh.wikipedia.org/wiki/维基)是一种由其受众直接使用Web浏览器协作编辑和管理的出版物。

_相关: [笔记和编辑器](#笔记和编辑器), [静态站点生成器](#静态站点生成器), [知识管理工具](#知识管理工具)_

_另见: [Wikimatrix](https://www.wikimatrix.org/), [维基软件列表 - Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [维基软件比较 - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [AmuseWiki](https://amusewiki.org/) - Amusewiki基于Emacs Muse标记,主要与原始实现兼容。它可以作为只读站点、审核维基或完全开放的维基甚至私有站点工作。([源代码](https://github.com/melmothx/amusewiki)) `GPL-1.0` `Perl/Docker`
- [BookStack](https://www.bookstackapp.com/) - 组织和存储信息。以书籍方式存储文档。([演示](https://www.bookstackapp.com/#demo), [源代码](https://codeberg.org/bookstack/bookstack)) `MIT` `PHP/Docker`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 具有复杂功能的维基系统,用于简单集成和出色的界面。用风格存储您的知识:使用django模型。([演示](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [docmost Community Edition](https://docmost.com/) - 协作式维基和文档软件(Confluence、Notion的替代品)。([源代码](https://github.com/docmost/docmost)) `AGPL-3.0` `Docker/Nodejs`
- [Documize](https://documize.com) - 现代文档+维基软件,具有内置工作流,单二进制可执行文件,只需提供MySQL/Percona。([源代码](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - 易于使用、轻量级、符合标准的维基引擎,具有简单的语法,允许在维基之外读取数据。所有数据存储在纯文本文件中,因此不需要数据库。([源代码](https://github.com/dokuwiki/dokuwiki)) `GPL-2.0` `PHP`
- [Feather Wiki](https://feather.wiki) - 一个闪电般快速且无限可扩展的工具,用于创建个人非线性笔记本、数据库和维基,完全自包含,在浏览器中运行,大小仅为58千字节。([演示](https://feather.wiki/?page=gallery#wikis), [源代码](https://codeberg.org/Alamantus/FeatherWiki), [客户端](https://feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `Javascript`
- [Gitit](https://github.com/jgm/gitit) - 将页面和上传文件存储在git仓库中的维基程序,然后可以使用VCS命令行工具或维基的Web界面进行修改。`GPL-2.0` `Haskell`
- [LeafWiki](https://github.com/perber/leafwiki) - 适合按文件夹而非信息流思考的人们的快速维基。快速编辑。树形导航。磁盘上的Markdown。([演示](https://demo.leafwiki.com)) `MIT` `Docker/Go`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - 为Wikipedia和所有其他Wikimedia项目提供动力的维基软件包,每月为数亿用户提供服务。([演示](https://en.wikipedia.org/wiki/Main_Page), [源代码](https://phabricator.wikimedia.org/source/mediawiki/)) `GPL-2.0` `PHP`
- [Otter Wiki](https://otterwiki.com/) - 使用markdown的简单易用的维基软件。([源代码](https://github.com/redimp/otterwiki)) `MIT` `Docker`
- [PmWiki](https://www.pmwiki.org) - 基于维基的系统,用于协作创建和维护网站。`GPL-3.0` `PHP`
- [Raneto](https://raneto.com/) - 使用静态Markdown文件的知识库平台。([源代码](https://github.com/ryanlelek/Raneto)) `MIT` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - 可重用的非线性个人Web笔记本。([源代码](https://github.com/TiddlyWiki/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org/HomePage) - 具有最多内置功能的维基CMS群件。([演示](https://tiki.org/Try-Tiki), [源代码](https://gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- [W](https://w.club1.fr) - 轻量级、多用户、平面文件数据库维基引擎。使用Mardown/HTML/CSS/JS快速创建页面并在Web浏览器中编辑它们。与其他维基的主要区别在于鼓励您单独自定义每个页面样式。([源代码](https://github.com/vincent-peugnet/wcms)) `AGPL-3.0` `PHP`
- [WackoWiki](https://wackowiki.org/) - WackoWiki是一个轻量级且易于安装的多语言维基引擎。([源代码](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki-Go](https://leomoon.com/downloads/web-apps/wiki-go/) - 一个现代、功能丰富、无数据库的平面文件维基平台。([演示](https://wikigo.leomoon.com), [源代码](https://github.com/leomoon-studios/wiki-go)) `GPL-3.0` `Go/Docker`
- [Wiki.js](https://js.wiki/) - 使用Git和Markdown的现代、轻量级且功能强大的维基应用。([演示](https://docs.requarks.io), [源代码](https://github.com/Requarks/wiki)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](https://www.wikidocs.app/) - 无数据库的markdown平面文件维基引擎。([源代码](https://github.com/Zavy86/WikiDocs)) `MIT` `PHP/Docker`
- [WiKiss](https://wikiss.tuxfamily.org/) - 维基,简单易用和安装。([源代码](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [XWiki](https://www.xwiki.org) - 第二代维基,允许用户通过强大的基于扩展的架构扩展其功能。([演示](https://www.xwikiplayground.org/xwiki/bin/view/Main/), [源代码](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java/Docker/deb`
- [Zim](https://zim-wiki.org/) - 用于维护维基页面集合的图形化文本编辑器。每个页面可以包含指向其他页面的链接、简单格式和图像。([源代码](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python/deb`


--------------------

## 许可证列表

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

- `0BSD` - [BSD零条款许可证](https://spdx.org/licenses/0BSD.html)
- `AAL` - [归属保证许可证](https://spdx.org/licenses/AAL.html)
- `AGPL-3.0` - [GNU Affero通用公共许可证 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache许可证 2.0版](https://spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - [Apple公共源代码许可证 2.0版](https://spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - [艺术许可协议 2.0版](https://spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - [啤酒软件许可证](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD双条款"简化版"](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - [BSD双条款FreeBSD许可证](https://spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - [BSD三条款"新版"或"修订版"](https://spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - [带归属的BSD](https://spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - [BSD四条款"原始版"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CAL-1.0` - [密码自治许可证 1.0](https://spdx.org/licenses/CAL-1.0.html)
- `CC-BY-SA-3.0` - [知识共享署名-相同方式共享 3.0 许可证](https://spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - [知识共享署名-相同方式共享 4.0 许可证](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - [公有领域/知识共享零 1.0](https://spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - [通用开发和分发许可证](https://spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - [CEA CNRS INRIA 自由软件许可证](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [公共属性许可协议 1.0版](https://spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - [教育社区许可证 2.0版](https://spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - [Eclipse公共许可证 1.0版](https://spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - [Eclipse公共许可证 2.0版](https://spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - [欧盟公共许可证 1.2](https://spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - [GNU通用公共许可证 1.0](https://spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - [GNU通用公共许可证 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU通用公共许可证 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - [IBM公共许可证](https://spdx.org/licenses/IPL-1.0.html)
- `ISC` - [互联网系统联盟许可证](https://spdx.org/licenses/ISC.html)
- `LGPL-2.1` - [较宽松公共许可证 2.1](https://spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - [较宽松公共许可证 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT许可证](https://spdx.org/licenses/MIT.html)
- `MPL-1.1` - [Mozilla公共许可证 1.1版](https://spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - [Mozilla公共许可证](https://spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - [开放软件许可证 3.0](https://spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - [Sendmail许可证](https://spdx.org/licenses/Sendmail.html)
- `Ruby` - [Ruby许可证](https://spdx.org/licenses/Ruby.html)
- `Unlicense` - [放弃版权许可证](https://spdx.org/licenses/Unlicense.html)
- `WTFPL` - [你想干什么就干什么公共许可证](https://spdx.org/licenses/WTFPL.html)
- `Zlib` - [Zlib/libpng许可证](https://spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - [Zope公共许可证 2.0](https://spdx.org/licenses/ZPL-2.0.html)


--------------------

## 反特性

- `⚠ ` - 依赖于用户无法控制的专有服务


--------------------

## 外部链接

**[`^        返回顶部        ^`](#精彩的自托管软件列表)**

- 发现/筛选awesome-selfhosted应用的替代前端/门户: [awweso.me](https://awweso.me/), [awesome-web.theravenhub](https://awesome-web.theravenhub.com/browse.html)
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 精选的令人惊叹的开源系统管理员资源列表。
- 以某种形式专注于隐私和去中心化的软件列表: [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](https://libreprojects.net/), [Easy Indie App](https://easyindie.app)
- 其他Awesome列表: [Awesome Big Data](https://github.com/0xnr/awesome-bigdata), [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- 动态域名服务: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- 社区/论坛: [/c/selfhosted on lemmy.world](https://lemmy.world/c/selfhosted), [/c/selfhost on lemmy.ml](https://lemmy.ml/c/selfhost), [/r/selfhosted on reddit](https://old.reddit.com/r/selfhosted/), [/r/selfhosted Matrix Channel](https://matrix.to/#/#selfhosted:selfhosted.chat), [/r/homelab on reddit](https://old.reddit.com/r/homelab/), [IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 50个自托管应用的主题/皮肤集合! ([源代码](https://github.com/GilbN/theme.park/)) `MIT` `CSS`


--------------------

## 贡献

贡献指南可以在[这里](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md)找到。

## 许可证

本列表采用[知识共享署名-相同方式共享 3.0 未本地化版本](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE)许可证。
许可证条款摘要见[这里](https://creativecommons.org/licenses/by-sa/3.0/)。
作者列表可在[AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS)文件中找到。