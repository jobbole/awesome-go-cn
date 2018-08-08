# Go 资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。本列表翻译自[awesome-Go](https://github.com/avelino/awesome-Go)
Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

### 如何为列表贡献新资源？

欢迎大家为列表贡献高质量的新资源，提交 PR 时请参照以下要求：

* 请确保推荐的资源自己使用过
* 提交 PR 时请注明推荐理由

资源列表管理收到 PR 请求后，会定期（每周）在微博转发本周提交的 PR 列表，并在微博上面听取使用过这些资源的意见。确认通过后，会加入资源大全。

感谢您的贡献！

本项目的参与者
维护者：tangyouhua

贡献者：[艾凌风](https://github.com/hanxiaomax)

注：名单不分排名，不定期补充更新

### 参与

烦请诸位参与前看一眼[参与指南](https://github.com/avelino/awesome-Go/blob/master/CONTRIBUTING.md) 。感谢各位贡献者，你们是最棒的！ [contributors](https://github.com/avelino/awesome-Go/graphs/contributors)

#### _如果你发现某个项目已经不维护了，或者它并不好，请发起一个 pull request 来帮助我们改善此列表。感谢。_

##资源列表

## 音频和音乐

_用于操作音频的库_

* [flac](https://github.com/eaburns/flac) - 原生 Go FLAC 解码器
* [flac](https://github.com/mewkiz/flac) - 原生 Go FLAC 解码器
* [gaad](https://github.com/Comcast/gaad) - 原生 Go AAC 比特流解析器
* [Go-sox](https://github.com/krig/Go-sox) - libsox 的 Go 语言接口
* [Go_mediainfo](https://github.com/zhulik/Go_mediainfo) - libmediainfo 的 Go 语言接口
* [Gosamplerate](https://github.com/dh1tw/Gosamplerate) - libsamplerate 的 Go 语言接口
* [id3v2](https://github.com/bogem/id3v2) - 快速且稳定的 ID3 解析及写入库
* [mix](https://github.com/Go-mix/mix) - 基于序列的 Go 语言混音器，可用于音乐 app。
* [mp3](https://github.com/tcolgate/mp3) - 原生 Go MP3 解码器
* [music-theory](https://github.com/Go-music-theory/music-theory) - Go 语言编写的音乐理论模型
* [PortAudio](https://github.com/Gordonklaus/portaudio) - 音频 I/O 库的 Go 语言接口
* [portmidi](https://github.com/rakyll/portmidi) - PortMidi 的 Go 语言接口
* [taglib](https://github.com/wtolson/Go-taglib) - taglib 的 Go 语言接口
* [vorbis](https://github.com/mccoyst/vorbis) - "原生" Go Vorbis 解码器 (使用 CGo, 但是没有其他依赖).
* [waveform](https://github.com/mdlayher/waveform) - 一个可以通过音频流生成波形图像的包

## 认证和授权

_用来生成认证授权模板的库_

* [authboss](https://github.com/volatiletech/authboss) - 用于 web 开发的组件化认证授权系统。它尝试尽可能的移除模板代码以及硬编码，这使你每次新建 web 项目的时候，可以做到即插即用、配置并开始开发你的 web 英语，而不必每次都重新创建一个认证授权系统。
* [casbin](https://github.com/hsluoyz/casbin) - 一个支持接入控制模型（例如:ACL,RBAC,ABAC）的授权库
* [Go-AWS-Auth](https://github.com/smartystreets/Go-aws-auth) - AWS 请求签名库
* [Go-jose](https://github.com/square/Go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web 签名以及JSON Web 加密 specs.
* [Go-oauth2-server](https://github.com/RichardKnop/Go-oauth2-server) - 使用 Go 语言编写的独立、符合标准的 OAuth2 服务器
* [Go.auth](https://github.com/bradrydzewski/Go.auth) - 为 Go 语言 web 应用提供的授权 API.
* [Gologin](https://github.com/dghubble/Gologin) - 可以串连使用OAuth1 和 OAuth2 认证服务
* [Gorbac](https://github.com/mikespook/Gorbac) - 一个用 Go 语言实现的轻量级RBAC
* [Goth](https://github.com/markbates/Goth) - 提供了一种简洁的、惯用的方式来使用OAuth 和 OAuth2.
* [httpauth](https://github.com/Goji/httpauth) - HTTP 认证中间件
* [jwt](https://github.com/robbert229/jwt) - 简单易用的一个JSON Web Tokens (JWT)的实现
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT 为 Go 语言 HTTP 服务器编写的 jwt 中间件，有多种配置选项
* [jwt-Go](https://github.com/dgrijalva/jwt-Go) - Go 语言实现的JSON Web Tokens (JWT).
* [loginsrv](https://github.com/tarent/loginsrv) - JWT 登录微服务，可以继承OAuth2 (Github), htpasswd, osiam等后端。
* [oauth2](https://github.com/Golang/oauth2) - Goauth2的继承者。 通用 OAuth 2.0 库，集成了对JWT, Google APIs, Compute Engine 和 App Engine的支持.
* [osin](https://github.com/RangelReale/osin) - Go 语言 OAuth2 服务器库
* [permissions2](https://github.com/xyproto/permissions2) - 用于追踪用户，登录状态和许可的库。使用安全 cookies 和 bcrypt.
* [session](https://github.com/icza/session) - Go 语言会话管理(支持 Google App Engine - GAE)
* [sessions](https://github.com/adam-hanna/sessions) - 为 Go 语言 HTTP 服务器开发的非常简单的、高性能的、高可定制的会话服务
* [traefik](https://github.com/containous/traefik) - 反向代理和负载均衡库，支持多种后端
* [yubiGo](https://github.com/GeertJohan/yubiGo) - Yubikey 客户端，提供了用于在 Go 语言应用中集成Yubico Yubikey 的 API

## 命令行

### 标准命令行交互

_用于构建标准或基础命令行应用的库_

* [argv](https://github.com/cosiner/argv) - 用于分隔命令行字符串并将其作为参数的 Go 语言库，使用 bash 的语法
* [cli](https://github.com/mkideal/cli) - 功能强大，使用简单的命令行软件包，基于Golang tag
* [cli-init](https://github.com/tcnksm/gcli) - 提供一种简单、易上手的方式 来使用 Go 语言编写命令行程序
* [climax](http://github.com/tucnak/climax) - 一个更为人性化的命令行工具，继承了 Go command 的精神
* [cobra](https://github.com/spf13/cobra) - 用于现代 Go 语言命令行交互的工具
* [complete](https://github.com/posener/complete) - 使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具
* [docopt.Go](https://github.com/docopt/docopt.Go) - 能令你会心一笑的命令行参数解析器
* [drive](https://github.com/odeke-em/drive) - 命令行的 Google Drive 客户端
* [flag](https://github.com/cosiner/flag) - 简单、强大的命令行选项解析库，支持 Go 语言子命令
* [Go-arg](https://github.com/alexflint/Go-arg) - 使用 Go 语言编写的基于结构的命令行参数解析库
* [Go-flags](https://github.com/jessevdk/Go-flags) - Go 语言命令行选项解析器
* [kingpin](https://github.com/alecthomas/kingpin) - 命令行及标记解析器，支持子命令
* [liner](https://github.com/peterh/liner) - 命令行文本编辑器
* [mitchellh/cli](https://github.com/mitchellh/cli) - 用于实现命令行交互的 Go 语言库
* [mow.cli](https://github.com/jawher/mow.cli) - 用于构建命令行程序的库，支持更加精准的标记及选项解析和验证
* [pflag](https://github.com/spf13/pflag) - Go flag 软件包的替代品, 实现了POSIX/GNU-风格的 --flags.
* [readline](https://github.com/chzyer/readline) - 纯 Go 语言实现的 GNU-Readline 支持其大部分功能，基于MIT 协议发布。
* [sflags](https://github.com/octaGo/sflags) - 基于结构的 flag 生成器，支持flag, urfave/cli, pflag, cobra, kingpin等其他库
* [ukautz/clif](https://github.com/ukautz/clif) - 一个小型命令行程序开发框架
* [urfave/cli](https://github.com/urfave/cli) - 简单、快速、有趣的、用于构建 Go 语言命令行程序的软件包(formerly codegangsta/cli).
* [wlog](https://github.com/dixonwille/wlog) - 简单的登录接口，支持跨平台颜色和并发
* [wmenu](https://github.com/dixonwille/wmenu) - 为命令行程序提供简单的菜单结构选项，供用户进行选择

### 高级控制台界面

_用于构建命令行程序以及控制台界面的库_

* [aurora](https://github.com/logrusorgru/aurora) - ANSI 终端颜色，支持 fmt.Printf/Sprintf
* [chalk](https://github.com/ttacon/chalk) - 符合直觉的用于美化命令行输出的库
* [color](https://github.com/fatih/color) - 多功能的用于彩色化命令行输出的库
* [colourize](https://github.com/TreyBastian/colourize) - 用于实现 ANSI 彩色文本的 Go 语言库
* [Go-ataman](https://github.com/workanator/Go-ataman) - 用于渲染 ANSI 彩色文本模板的库
* [Go-colorable](https://github.com/mattn/Go-colorable) - Windows 上使用的可以输出彩色文本的库
* [Go-colortext](https://github.com/daviddengcn/Go-colortext) - 用于在终端进行多彩文字输出的库
* [Go-isatty](https://github.com/mattn/Go-isatty) - Go 语言使用的 isatty
* [Gocui](https://github.com/jroimartin/Gocui) - 一个用于构建控制台界面的极简的 Go 语言库
* [Gommon/color](https://github.com/labstack/Gommon/tree/master/color) - 多样的命令行文本
* [mpb](https://github.com/vbauerster/mpb) - 为命令行提供多个进度条的工具
* [termbox-Go](https://github.com/nsf/termbox-Go) - Termbox 是一个用于构建跨平台的、与文本的交互界面的库
* [termtables](https://github.com/apcera/termtables) - Ruby 库的 Go 语言接口
* [terminal-tables](https://github.com/tj/terminal-table) 用于生成简单的 ASCII 表格，同时支持 markdown 和 HTML 输出
* [termui](https://github.com/gizak/termui) - Go 终端控制面板，基于 **termbox-Go** 并受到了[blessed-contrib](https://github.com/yaronn/blessed-contrib)的启发
* [uilive](https://github.com/Gosuri/uilive) - 用于实时更新终端输出的库
* [uiprogress](https://github.com/Gosuri/uiprogress) - 一个很灵活的用于渲染进度条的库
* [uitable](https://github.com/Gosuri/uitable) - 一个用于改善命令行中表格数据可读性的库

## 配置

_用于进行配置解析的库_

* [config](https://github.com/olebedev/config) - JSON 或 YAML 配置的封装，支持环境变量和标记解析
* [configure](https://github.com/paked/configure) - 可以通过多种途径进行配置，包括 JSON, 标记位以及环境变量
* [env](https://github.com/caarlos0/env) - 解析环境变量为 Go 语言结构体
* [envcfg](https://github.com/tomazk/envcfg) - 解析环境变量为 Go 语言结构体
* [envconf](https://github.com/ian-kent/envconf) - 通过环境变量来配置
* [envconfig](https://github.com/vrischmann/envconfig) - 通过环境变量读取配置
* [gcfg](https://github.com/Go-gcfg/gcfg) - 读取类 INI 类型的配置文件为 Go 语言结构体，支持自定义变量和节
* [GoConfig](https://github.com/crgimenes/GoConfig) - 通过命令行的输入、环境变量、配置文件来初始化一个结构体兵将一个结构体解析为输入
* [Godotenv](https://github.com/joho/Godotenv) - Ruby 库 dotenv 的 Go 语言接口 (通过 `.env` 来获取环境变量)
* [Gofigure](https://github.com/ian-kent/Gofigure) - 让 Go 语言应用程序配置变得简单
* [Gone/jconf](https://github.com/One-com/Gone/tree/master/jconf#readme) - 模块化 JSON 配置工具。允许你将配置参数结构体和使用它的代码放在一起，而不需要让主配置文件了解所有子模块的细节来进行序列化
* [hjson](https://github.com/hjson/hjson-Go) - 人性化的 JSON，一个便于程序员使用和阅读的配置文件格式。更加轻松的语法，更少的错误和更多的注释
* [inGo](https://github.com/schachmat/inGo) - 将配置标记持久化到一个类似 ini 的文件中
* [ini](https://github.com/Go-ini/ini) - 用于读写INI 文件的库
* [joshbetz/config](https://github.com/joshbetz/config) - 消息配置库，可以解析环境变量、JSON 文件并根据SIGHUP自动重新载入
* [mini](https://github.com/sasbury/mini) -用于解析类 ini 文件的库
* [store](https://github.com/tucnak/store) - 轻量级配置管理
* [viper](https://github.com/spf13/viper) - 长牙的（这个库名叫毒蛇）Go 语言配置工具
* [xdg](https://github.com/OpenPeeDeeP/xdg) -遵守 [XDG 标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html) 的配置工具

## 持续集成

_帮助你进行持续集成的库_

* [drone](https://github.com/drone/drone) - Drone 是一个基于 Docker的持续集成平台，使用 Go 语言编写
* [Goveralls](https://github.com/mattn/Goveralls) - Coveralls.io 是一个持续代码覆盖率检测系统，这个库提供了 Go 语言的支持
* [overalls](https://github.com/Go-playground/overalls) - 针对多package 的 Go 语言项目，为 Goveralls 这样的工具生成覆盖率报告
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - 回归覆盖测试工具

## CSS 预处理器

_用于对 CSS 文件预处理的工具_

* [c6](https://github.com/c9s/c6) - 高性能、兼容 SAAS 的编译器
* [gcss](https://github.com/yosssi/gcss) - 纯 Go 语言编写的 CSS 预处理器
* [Go-libsass](https://github.com/wellington/Go-libsass) - 100%兼容 Sass 的库 libsass 的 Go 语言封装

## 数据结构

_通用数据结构及算法_

* [binpacker](https://github.com/zhuangsirui/binpacker) - 二进制数据封包拆包工具，帮你构建自定义的二进制数据流
* [bit](https://github.com/yourbasic/bit) - Go 语言集合数据结构。提供了额外的位操作功能
* [bitset](https://github.com/willf/bitset) - 实现了 bitset 的 Go 语言包.
* [bloom](https://github.com/zhenjl/bloom) - Go 语言实现的布隆过滤器（bloom filter）
* [bloom](https://github.com/yourbasic/bloom) - Go 语言实现的布隆过滤器
* [boomfilters](https://github.com/tylertreat/BoomFilters) - 概率统计数据结构，用于处理大量连续的数据。
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go 语言实现的 Count-Min-Log sketch 算法(类似 Count-Min sketch 算法，但是使用的内存更少).
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo 过滤器：一个用go语言实现的计数布隆过滤器的替代品
* [encoding](https://github.com/zhenjl/encoding) - 整型压缩库
* [Go-adaptive-radix-tree](https://github.com/plar/Go-adaptive-radix-tree) - Go 语言实现的自适应基数树
* [Go-datastructures](https://github.com/Workiva/Go-datastructures) - 一组有用的、高性能的、线程安全的数据结构
* [Go-geoindex](https://github.com/hailocab/Go-geoindex) - 基于内存存储的地理索引
* [Go-rquad](https://github.com/aurelien-rainone/Go-rquad) - 区域四叉树，支持有效点位置和领域发现
* [Gods](https://github.com/emirpasic/Gods) - Go 语言数据结构、容器、集合、列表、栈、键值对、 BidiMaps、树、HashSet 等
* [Golang-set](https://github.com/deckarep/Golang-set) - 线程安全和非线程安全的高性能集合
* [Goskiplist](https://github.com/ryszard/Goskiplist) - Go 语言实现的跳跃表
* [Gota](https://github.com/kniren/Gota) - 为go语言实现了数据帧，序列以及数据噪音的方法
* [hilbert](https://github.com/Google/hilbert) - 用于映射空间填充曲线（例如希尔伯特曲线和皮亚诺曲线）和数值的库。
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [levenshtein](https://github.com/agext/levenshtein) - 编辑距离（levenshtein distance）和相似性度量， 可以自定义编辑代价和and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) - Go 语言实现计算编辑距离
* [mafsa](https://github.com/smartystreets/mafsa) - Go 语言实现的 MA-FSA ，包含最小完美哈希
* [merkletree](https://github.com/cberGoon/merkletree) - 实现了梅克尔树，提供了一种高效、安全的数据结构内容验证方法
* [roaring](https://github.com/RoaringBitmap/roaring) - 实现了压缩 bitsets 的Go语言库
* [skiplist](https://github.com/gansidui/skiplist) - Go语言实现的跳跃表
* [trie](https://github.com/derekparker/trie) - Go语言实现的Trie树
* [ttlcache](https://github.com/dieGobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for Golang
* [willf/bloom](https://github.com/willf/bloom) - 实现了布隆过滤器的库

## 数据库

*   Go 语言实现的数据库*
* [BigCache](https://github.com/allegro/bigcache) - 为 gigabytes 量级数据设计的高效键/值缓存
* [bolt](https://github.com/boltdb/bolt) - 底层键值数据库
* [buntdb](https://github.com/tidwall/buntdb) - 快速，可嵌入的，内存键值数据库，可定义索引及 spatial
* [cache2Go](https://github.com/muesli/cache2Go) - 基于内存存储的键值缓存，支持自动基于超时的自动失效
* [cockroach](https://github.com/cockroachdb/cockroach) - 可扩展的、一致的事务型数据库
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful 缓存微服务，基于Couchbase
* [dgraph](https://github.com/dgraph-io/dgraph) - 可扩展的、分布式的、低延时、高吞吐的图数据库
* [diskv](https://github.com/peterbourGon/diskv) - 具有 disk-backed 功能的持久化键值存储
* [eliasdb](https://github.com/krotik/eliasdb) - 无依赖、事物型图数据库，支持 REST API、短语搜索以及类 SQL 的查询语言
* [forestdb](https://github.com/couchbase/Goforestdb) - ForestDB 的 Go 语言借口
* [GCache](https://github.com/bluele/gcache) - 支持缓存过期、 LFU、 LRU 和 ARC 的缓存库
* [geocache](https://github.com/melihmucuk/geocache) - 基于内存存储的缓存，适用于分布式部署的应用
* [Go-cache](https://github.com/pmylund/Go-cache) - 内存键值存储/缓存库，适用于单机程序
* [Goleveldb](https://github.com/syndtr/Goleveldb) - 使用 Go 语言实现的 [LevelDB](https://github.com/Google/leveldb)
* [groupcache](https://github.com/Golang/groupcache) - Groupcache 是一个缓存及缓存填充库，在很多情况下用于替代 memcached.
* [influxdb](https://github.com/influxdb/influxdb) - 用于计量、事件及实时分析的、可扩展的数据库
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb 是一个高性能 NoSQL 数据库，类似 Redi
* [leviGo](https://github.com/jmhodges/leviGo) - LeviGo 是 LevelDB的 Go 语言封装
* [moss](https://github.com/couchbase/moss) - Moss 是一个简单的 LSM 键值存储引擎，100% Go 语言实现
* [piladb](https://github.com/fern4lvarez/piladb) - 轻量级 RESTful 数据库引擎，基于堆栈结构
* [prometheus](https://github.com/prometheus/prometheus) - 监控系统及时间序列数据库
* [rqlite](https://github.com/rqlite/rqlite) - 基于 SQLite 的轻量级的、分布式的关系型数据库
* [Scribble](https://github.com/nanobox-io/Golang-scribble) - 小巧的 JSON 文件存储
* [tempdb](https://github.com/rafaeljesus/tempdb) - 临时数据的键值对存储
* [tidb](https://github.com/pingcap/tidb) - TiDB 是一个分布式的 SQL 数据库。受到了 Google F1的启发
* [tiedot](https://github.com/HouzuoGuo/tiedot) - 基于 Go 语言的 NoSQL 数据库
* [Tile38](https://github.com/tidwall/tile38) - 地理位置数据库及实时地理围栏

_数据库迁移_

* [darwin](https://github.com/GuiaBolso/darwin) - 数据库模式进化库
* [Go-fixtures](https://github.com/RichardKnop/Go-fixtures) - 类似 DjanGo fixtures，用于 Golang 的內建数据库/sql 库
* [Goose](https://github.com/steinbacher/Goose) - 数据库迁移工具。你可以通过编写增量 SQL 或 Go 语言脚本来管理你的数据库
* [Gormigrate](https://github.com/Go-Gormigrate/Gormigrate) - 数据库模式迁移帮助工具，用于 Gorm ORM.
* [migrate](https://github.com/mattes/migrate) - 数据库迁移。命令行及 Go 语言库
* [pravasan](https://github.com/pravasan/pravasan) - 简单的迁移，目前支持 MySQL 但是近期打算支持 Postgres, SQLite, MonGoDB 等等
* [soda](https://github.com/markbates/pop/tree/master/soda) - 数据库迁移、创建、 ORM等等，用于 MySQL, PostgreSQL, 以及 SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - 数据库迁移工具，允许利用 Go-bindata 将数据库迁移嵌入应用程序

_数据库工具_

* [Go-mysql](https://github.com/siddontang/Go-mysql) - 用于处理 MySQL 协议及复制的 Go 语言工具集.
* [Go-mysql-elasticsearch](https://github.com/siddontang/Go-mysql-elasticsearch) - 将你的 MySQL 数据自动同步到 Elasticsearch
* [kingshard](https://github.com/flike/kingshard) - kingshard 是一个Go语言编写的高性能 MySQL 数据库代理
* [myreplication](https://github.com/2tvenom/myreplication) - MySql 二进制 log 复制监听器，支持基于语句和基于行的复制
* [orchestrator](https://github.com/github/orchestrator) - MySQL复制拓扑管理器及可视化工具
* [pgweb](https://github.com/sosedoff/pgweb) - 基于 Web 的 PostgreSQL 数据库浏览工具
* [pREST](https://github.com/nuveo/prest) - 通过任何 PostgreSQL 数据库提供 RESTful API
* [vitess](https://github.com/youtube/vitess) - vitess 提供了能够使大型 web 服务 MySQL 数据库的扩展变得更加容易的服务器及工具

_用于创建和使用SQL的库_

* [dat](https://github.com/mgutz/dat) - Go 语言 Postgres 数据库工具集
* [Dotsql](https://github.com/gchaincl/dotsql) - 一个Go语言库，帮助你将 sql 文件保存在一个地方并且方便的取用
* [Goqu](https://github.com/doug-martin/Goqu) - 地道的 SQL 语句创建器和查询库
* [iGor](https://github.com/galeone/iGor) - PostgreSQL 的抽象层，支持高级功能以及类 Gorm 的语法
* [ozzo-dbx](https://github.com/Go-ozzo/ozzo-dbx) - 提供强大的数据恢复功能以及构建不区分数据库类型的查询的能力
* [scaneo](https://github.com/variadico/scaneo) - 生成用于将数据库行转换为任意结构体的 Go 代码
* [sqrl](https://github.com/elgris/sqrl) - SQL 查询创建器，是 Squirrel 的一个分叉版本，进行了性能方面的优化
* [Squirrel](https://github.com/Masterminds/squirrel) - 一个帮助你构建 SQL 查询的库
* [xo](https://github.com/knq/xo) - 基于已知的数据库表或自定义查询生成地道的 Go 语言代码，支持 PostgreSQL, MySQL, SQLite, Oracle, 以及 Microsoft SQL Server.

## 数据库驱动

_用于连接和操作数据库的库_

* 关系型数据库  
    * [avatica](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica SQL 驱动
    * [bgc](https://github.com/viant/bgc) - 数据库连接工具包，用于通过 Go 语言访问 BigQuery
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL 驱动
    * [Go-adodb](https://github.com/mattn/Go-adodb) - Microsoft ActiveX 对象数据库驱动
    * [Go-bqstreamer](https://github.com/rounds/Go-bqstreamer) - BigQuery fast and concurrent stream insert.
    * [Go-mssqldb](https://github.com/denisenkom/Go-mssqldb) - Go 语言Microsoft MSSQL 驱动
    * [Go-oci8](https://github.com/mattn/Go-oci8) - Oracle 驱动
    * [Go-sql-driver/mysql](https://github.com/Go-sql-driver/mysql) - Go 语言 MySQ L驱动
    * [Go-sqlite3](https://github.com/mattn/Go-sqlite3) - Go 语言的 SQLite3 驱动
    * [Gofreetds](https://github.com/minus5/Gofreetds) Microsoft MSSQL 驱动。 [FreeTDS](http://www.freetds.org)的go语言封装
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL 驱动，支持比 database/sql 更多的特性
    * [pq](https://github.com/lib/pq) - 纯 Go 语言编写的 Postgres 驱动
*   NoSQL 数据库
    * [aerospike-client-Go](https://github.com/aerospike/aerospike-client-Go) - Aerospike 客户端
    * [aranGolite](https://github.com/solher/aranGolite) - AranGoDB 的轻量级 Go 语言驱动
    * [asc](https://github.com/viant/asc) - 用于go语言连接 Aerospike
    * [cayley](https://github.com/Google/cayley) - 支持多种后端的图数据库
    * [dsc](https://github.com/viant/dsc) - 数据库连接工具包，支持 SQL, NoSQL 及结构化文件
    * [dynaGo](https://github.com/underarmour/dynaGo) - DynaGo 是一个符合最小惊奇原则（principle of least surprise）的 DynamoDB 客户端
    * [Go-couchbase](https://github.com/couchbase/Go-couchbase) - Go 语言 Couchbase 客户的
    * [Go-couchdb](https://github.com/fjl/Go-couchdb) - 另一个 CouchDB HTTP API 的 Go 语言封装
    * [Gocb](https://github.com/couchbase/Gocb) - 官方 Couchbase 的 Go 语言 SDK
    * [Gocql](http://Gocql.github.io) - Apache Cassandra 的 Go 语言驱动
    * [Gomemcache](https://github.com/bradfitz/Gomemcache/) - memcache 客户端库
    * [Gorethink](https://github.com/dancannon/Gorethink) - RethinkDB 的 Go 语言驱动
    * [Goriak](https://github.com/zegl/Goriak) - Riak KV 的 Go 语言驱动
    * [mGo](https://Godoc.org/labix.org/v2/mGo) - MonGoDB 驱动，通过简单的 API 实现了丰富的、经过测试的特性，这些 API 遵循 Go 语言的习惯
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API 的 Go 语言接口
    * [Neo4j-Go](https://github.com/davemeehan/Neo4j-Go) - Go 语言实现的 Neo4j REST 客户端
    * [neoism](https://github.com/jmcvetta/neoism) - Go 语言 Neo4j 客户端
    * [rediGo](https://github.com/garyburd/rediGo) - RediGo 是 Redis 数据库的 Go 语言客户端.
    * [redis](https://github.com/Go-redis/redis) - Redis 的 Go 语言客户端
    * [redis](https://github.com/hoisie/redis) - 简单、强大的 Redis 客户端
    * [redis](https://github.com/bsm/redeo) - 兼容Redis协议的 TCP 服务器/服务.
    * [xredis](https://github.com/shomali11/xredis) - 类型安全的、可定制的、简洁易用的 Redis 客户端
*   搜索及分析数据库
    * [bleve](https://github.com/blevesearch/bleve) - 现代文本索引库
    * [elastic](https://github.com/olivere/elastic) - Go 语言的 Elasticsearch 客户端
    * [elasticsql](https://github.com/cch123/elasticsql) - 将 sql 转换为 elasticsearch dsl
    * [elastiGo](https://github.com/mattbaird/elastiGo) - Elasticsearch 客户端库
    * [Goes](https://github.com/belogik/Goes) - 用于和 Elasticsearch 交互的库
    * [skizze](https://github.com/seiflotfy/skizze) - 概率相关数据结构服务和存储

## 日期和时间

_处理日期和时间的库_

* [carbon](https://github.com/uniplaces/carbon) - 简单的时间扩展程序，有很多有用的方法，是 PHP Carbon 库的接口
* [durafmt](https://github.com/hako/durafmt) - 持续时间格式化
* [feiertage](https://github.com/wlbr/feiertage) - 一组计算德国公共假期的函数，比如复活节、感恩节等
* [Go-persian-calendar](https://github.com/yaa110/Go-persian-calendar) - 太阳历
* [Goweek](https://github.com/grsmv/Goweek) - 处理星期的库
* [now](https://github.com/jinzhu/now) - Now 是一个 Go 语言的时间工具集
* [NullTime](https://github.com/kirillDanshin/nulltime) -时间可以是 NULL 的库
* [timeutil](https://github.com/leekchan/timeutil) - 为 Go 语言时间包扩展了有用的功能，例如时间间隔和格式化

## 分布式系统

_用于构建分布式系统的库_

* [celeriac](https://github.com/svcavallar/celeriac.v1) - 利用 Go 语言对Celery 的 worker，任务，事件进行交互和监控的库
* [drmaa](https://github.com/dgruber/drmaa) -集群调度工具的任务提交库，基于标准 DRMAA 
* [flowgraph](https://github.com/vectaport/flowgraph) - MPI 风格的读取，发送协同层
* [gleam](https://github.com/chrislusf/gleam) - 快速、可扩展的分布式 map/reduce 系统，使用纯 Go 语言和 Luajit 编写，融合了 Go 语言的高并发能力和 Luajit 的高性能，可以独立或分布式部署运行。
* [glow](https://github.com/chrislusf/glow) - 简单易用、可扩展的大数据处理能力，Map-Reduce 以及执行 DAG(Database Availability Group），所有功能均由Go语言编写.
* [Go-jump](https://github.com/dgryski/Go-jump) - Google "Jump" 一致性哈希函数的借口
* [Go-kit](https://github.com/Go-kit/kit) - 为服务工具吧，支持服务发现、负载均衡 、可插拔传输以及请求追踪等
* [Gorpc](https://github.com/valyala/Gorpc) - 简单、快速、可扩展的 RPC 库，针对高负载场景
* [grpc-Go](https://github.com/grpc/grpc-Go) - Go 语言实现的 gRPC. HTTP/2 基于 RPC.
* [hprose](https://github.com/hprose/hprose-Golang) - 非常牛逼的 RPC 库，当前支持 25+ 语言。
* [jsonrpc](https://github.com/osaminGo/jsonrpc) - jsonrpc 包实现了 JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP 客户端实现
* [KrakenD](https://github.com/devopsfaith/krakend) - 带有中间件的，高性能 API 网关框架
* [micro](https://github.com/micro/micro) - 微服务工具套件和分布式系统平台
* [NATS](https://github.com/nats-io/gnatsd) - 轻量级、高性能微服务系统，用于微服务、物联网以及云
* [raft](https://github.com/hashicorp/raft) - Raft 一致性协议的 Go 语言实现, 作者是 HashiCorp.
* [raft](https://github.com/coreos/etcd/tree/master/raft#readme) - Raft 一致性协议的 Go 语言实现, 作者是 CoreOS.
* [ringpop-Go](https://github.com/uber/ringpop-Go) - 可扩展、容错的应用层分片库
* [rpcx](https://github.com/smallnest/rpcx) - rpcx是一个类似阿里巴巴 Dubbo 和微博 Motan 的分布式的 RPC 服务框架
* [sleuth](https://github.com/ursiform/sleuth) - 在 HTTP 服务之间进行无主 p2p 自动发现和 RPC通信(使用 [ZeroMQ](https://github.com/zeromq/libzmq)).
* [tendermint](https://github.com/tendermint/tendermint) - 一个高性能的中间件，用于将任何语言编写的状态机转换为一个拜占庭容错状态机，使用Tendermint 一致性及区块链协议
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent 客户端
* [dht](https://Godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT 的实现.
* [Go-peerflix](https://github.com/Sioro-Neoku/Go-peerflix) - 视频流 torrent 客户端

## 电子邮件

_用于创建和发送电子邮件的库_

* [douceur](https://github.com/aymerick/douceur) - HTML 邮件中的内联 CSS
* [email](https://github.com/jordan-wright/email) - 一个健壮的、灵活的 email 库
* [Go-dkim](https://github.com/toorop/Go-dkim) - DKIM 库，用于对 email 进行签名和验证
* [Go-imap](https://github.com/emersion/Go-imap) - IMAP 库，用于客户端和服务器
* [Go-message](https://github.com/emersion/Go-message) - 用于触雷互联网消息格式和邮件的库
* [Gomail](https://github.com/Go-Gomail/Gomail/) - Gomail 是一个非常简单且强大的库，用于发送电子邮件
* [Hectane](https://github.com/hectane/hectane) - 轻量级 SMTP 客户端，提供 HTTP API
* [hermes](https://github.com/matcornic/hermes) - 一个用于生成干净、响应式 HTML e-mail 的包
* [MailHog](https://github.com/mailhog/MailHog) - Email 及 SMTP 测试工具，具有 web 及 API 接口
* [SendGrid](https://github.com/sendgrid/sendgrid-Go) - SendGrid 的 Go 语言库，用于发送电子邮件
* [smtp](https://github.com/mailhog/smtp) - SMTP 服务器协议状态机

## 嵌入式脚本语言

_在你的 Go 代码中嵌入其他语言._

* [aGora](https://github.com/PuerkitoBio/aGora) - 一种动态类型的可以嵌入 Go 中的编程语言
* [anko](https://github.com/mattn/anko) - Go 语言编写的解释器
* [binder](https://github.com/alexeyco/binder) - Lua 接口, 基于 [Gopher-lua](https://github.com/yuin/Gopher-lua)
* [gisp](https://github.com/jcla1/gisp) - Simple LISP
* [Go-duktape](https://github.com/olebedev/Go-duktape) - Duktape JavaScript 引擎的 Go 语言接口
* [Go-lua](https://github.com/Shopify/Go-lua) - Lua 5.2 虚拟机的纯 Go 语言接口
* [Go-php](https://github.com/deuill/Go-php) - PHP 的 Go 语言接口
* [Go-python](https://github.com/sbinet/Go-python) - CPython C-API 的 Go 语言接口
* [Golua](https://github.com/aarzilli/Golua) - Lua C API。的 Go 语言接口
* [Gopher-lua](https://github.com/yuin/Gopher-lua) - Go 语言编写的 Lua 5.1 虚拟机和编译器
* [ngaro](https://github.com/db47h/ngaro) - 可嵌入的 Ngaro 虚拟机实现，支持在 Retro 中使用脚步
* [otto](https://github.com/robertkrimen/otto) - Go 编写的 Javascrip 解释器
* [purl](https://github.com/ian-kent/purl) - 嵌入 Go 语言的 Perl 5.18.2

## 文件

_用于处理文件和文件系统的库_

* [afero](https://github.com/spf13/afero) - 一个文件系统的抽象系统
* [Go-csv-tag](https://github.com/artonge/Go-csv-tag) - 使用 tag 导入 csv
* [Go-gtfs](https://github.com/artonge/Go-gtfs) - 加载 gtfs 文件
* [notify](https://github.com/rjeczalik/notify) - 文件系统提示库，具有简单的 API ，类似 os/signal.
* [skywalker](https://github.com/dixonwille/skywalker) - 允许你简单方便的并发浏览文件系统
* [tarfs](https://github.com/posener/tarfs) - 为 tar 文件实现的 [`FileSystem` 接口](https://Godoc.org/github.com/kr/fs#FileSystem)

## 财经

_会计及财务库_

* [accounting](https://github.com/leekchan/accounting) - 金钱及货币格式
* [decimal](https://github.com/shopspring/decimal) - 任意精度、固定点十进制数
* [Go-finance](https://github.com/FlashBoys/Go-finance) - 使用 Go 语言来理解财务市场数据
* [Go-money](https://github.com/rhymond/Go-money) - [Fowler 金钱模型](https://martinfowler.com/eaaCatalog/money.html)的实现
* [ofxGo](https://github.com/aclindsa/ofxGo) - 查询 OFX 服务器并解析其响应 (有一个示例的命令行客户端)
* [vat](https://github.com/dannyvankooten/vat) - VAT 验证及欧洲增值税率工具

## 表单

_操作表单的库_

* [bind](https://github.com/robfig/bind) - 将表单数据绑定到任意的 Go 变量上
* [binding](https://github.com/mholt/binding) - 将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体
* [conform](https://github.com/leebenson/conform) - 检查用户输入并基于结构标签来清理数据
* [form](https://github.com/Go-playground/form) - 解码 url 中的数据到 Go 语言变量中以及将 Go 语言变量编码进 url 支持Dual Array 及 Full map
* [formam](https://github.com/monoculum/formam) - 将表单数据解码到结构体
* [forms](https://github.com/albrow/forms) - 框架无关的表单/JSON数据解析验证库，支持多部分表单及文件
* [Gorilla/csrf](https://github.com/Gorilla/csrf) - 为 Go 语言 web 应用提供 CSRF 防御
* [nosurf](https://github.com/justinas/nosurf) - CSRF 防御中间件

## 游戏开发

_超赞的游戏开发库_

* [Azul3D](https://github.com/azul3d/engine) - Go 语言编写的 3D 游戏引擎
* [Ebiten](https://github.com/hajimehoshi/ebiten) - Go 语言编写的简单的 2D 游戏库
* [enGo](https://github.com/EnGoEngine/enGo) - EnGo 是一个开源的 2D 游戏引擎，遵循实体-组件-系统范式
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d 游戏引擎，利用 OpenGL 工作
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) 是一个很简单的跨平台游戏库
* [Go-astar](https://github.com/beefsack/Go-astar) - Go 语言实现的 A* 寻路算法
* [Go-collada](https://github.com/GlenKelley/Go-collada) - 操作 Collada 文件格式的 Go 语言库
* [Go-sdl2](https://github.com/veandco/Go-sdl2) - [Simple DirectMedia Layer](https://www.libsdl.org/)的 Go 语言接口
* [Go3d](https://github.com/ungerik/Go3d) - 专注性能的 2D/3D 数学库
* [Gonet](https://github.com/xtaci/Gonet) - Go 语言实现的游戏服务器框架
* [Leaf](https://github.com/name5566/leaf) - 轻量级游戏服务器框架
* [Pixel](https://github.com/faiface/pixel) - 手工 2D 游戏引擎库
* [raylib-Go](https://github.com/gen2brain/raylib-Go) - [raylib](http://www.raylib.com/)的 Go 语言接口，简单、易用的用于学习游戏编程的库
* [termloop](https://github.com/JoelOtter/termloop) - 终端游戏引擎，基于 Termbox

## 代码生成与泛型

_一些增强语言的功能的工具例如通过代码生成支持泛型_

* [efaceconv](https://github.com/t0pep0/efaceconv) - 代码生成工具，用于高效的将 interface{} 转换为不可变类型，不需要进行任何内存分配
* [gen](https://github.com/clipperhouse/gen) - 代码生成工具,用于提供类似泛型的功能
* [Go-linq](https://github.com/ahmetalpbalkan/Go-linq) - 类似 .NET LINQ 的查询方法
* [interfaces](https://github.com/rjeczalik/interfaces) - 命令行工具，用于生成接口定义
* [jennifer](https://github.com/dave/jennifer) - 不适用模板生成任意 Go 语言代码
* [pkgreflect](https://github.com/ungerik/pkgreflect) - 用于包作用域反射的 Go 语言预处理器

## Go 编译器

_用于把 Go 语言编译为其他语言的工具_

* [Gopherjs](https://github.com/Gopherjs/Gopherjs) - 把 Go 编译为 JavaScript.
* [llGo](https://github.com/Go-llvm/llGo) - 基于 LLVM 的 Go 语言编译器
* [tardisGo](https://github.com/tardisGo/tardisGo) - Golang 转换为 Haxe 进而转换为 CPP/CSharp/Java/JavaScript 的编译器.

## 协程

_用于管理和处理Go 语言协程的工具_

* [Go-floc](https://github.com/workanator/Go-floc) - 轻松编排 Go 语言协程
* [Go-flow](https://github.com/kamildrazkiewicz/Go-flow) - 控制 Go 语言协程的执行顺序
* [Goworker](https://github.com/benmanns/Goworker) - Goworker 是一个基于 Go 语言的后台worker
* [grpool](https://github.com/ivpusic/grpool) - 轻量级 Go 语言协程池
* [pool](https://github.com/Go-playground/pool) - 有限消费者协程或无限协程池，用于简单的处理协程和取消协程
* [semaphore](https://github.com/kamilsk/semaphore) - 实现了信号量模式，提供了超时锁定、解锁操作，基于通道和上下文。
* [tunny](https://github.com/Jeffail/tunny) - Go 语言协程池

## GUI

_用于构建 GUI 程序的库_

_工具包_

* [app](https://github.com/murlokswarm/app) - 使用Go, HTML 和 CSS 进行应用程序开发的库 支持 MacOS, Windows in progress.
* [Go-astilectron](https://github.com/asticode/Go-astilectron) - 使用 Go 以及 HTML/JS/CSS 构建应用程序. (基于Electron)
* [Go-gtk](http://mattn.github.io/Go-gtk/) - GTK 的 Go 语言接口
* [Go-qml](https://github.com/Go-qml/qml) - QML 对 Go 语言的支持
* [Go-sciter](https://github.com/sciter-sdk/Go-sciter) - Sciter 的 Go 语言接口 : 支持现代 GUI 程序开发的、嵌入式 HTML/CSS/脚本 引擎。跨平台。
* [Goqt](https://github.com/visualfc/Goqt) - Qt的 Go 语言接口
* [Gotk3](https://github.com/Gotk3/Gotk3) - GTK3 的 Go 语言接口
* [Gowd](https://github.com/dtylman/Gowd) - 使用 Go, HTML, CSS 和 NW.js 语言进行快速、简单的桌面 UI 开发。跨平台
* [qt](https://github.com/therecipe/qt) - Qt 的 Go 语言接口 (支持 Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)
* [ui](https://github.com/andlabs/ui) - 平台原生 GUI 库。跨平台
* [walk](https://github.com/lxn/walk) - windows 应用程序开发工具包

_交互_

* [Gosx-notifier](https://github.com/deckarep/Gosx-notifier) - OSX 桌面提醒库
* [robotGo](https://github.com/Go-vGo/robotGo) - 跨平台 GUI 自动化；控制鼠标、键盘及其他设备
* [systray](https://github.com/getlantern/systray) - 一个跨平台的 Go 语言库，用于在桌面提醒区域放置按钮及菜单
* [trayhost](https://github.com/shurcooL/trayhost) - 一个跨平台的 Go 语言库，用于在主机系统任务条区域放置按钮及菜单

## 硬件

_库、工具以及教程，讲解如何操控硬件_

参见 [Go-hardware](https://github.com/rakyll/Go-hardware) 获取更加全面的信息

## 图像

_用于操作图像的库_

* [bild](https://github.com/anthonynsimon/bild) - 汇集了使用 Go 语言编写的图像处理算法
* [bimg](https://github.com/h2non/bimg) - 利用 libvips 进行快速高效的图像处理
* [geopattern](https://github.com/pravj/geopattern) - 从字符串创建优美的图样
* [gg](https://github.com/fogleman/gg) - 使用 Go 编写的 2D 渲染程序
* [gift](https://github.com/disintegration/gift) - 一组图像处理滤波器
* [Go-cairo](https://github.com/ungerik/Go-cairo) - cairo 图形库的 Go 语言接口
* [Go-gd](https://github.com/bolknote/Go-gd) - GD 库的 Go 语言接口
* [Go-nude](https://github.com/koyachi/Go-nude) - 使用 Go 语言进行裸替检测
* [Go-opencv](https://github.com/lazywei/Go-opencv) - OpenCV 的 Go 语言接口
* [Go-webcolors](https://github.com/jyotiska/Go-webcolors) - webcolors 库的 Go 语言接口
* [imagick](https://github.com/Gographics/imagick) - ImageMagick 的 MagickWand C 语言 API 的 Go 语言接口
* [imaginary](https://github.com/h2non/imaginary) - 快速且简单的 HTTP 微服务，用于图像缩放
* [imaging](https://github.com/disintegration/imaging) - 简单的 Go 语言图像处理包
* [img](https://github.com/hawx/img) - 图像操作工具精选集
* [ln](https://github.com/fogleman/ln) - 3D 图线艺术渲染
* [mpo](https://github.com/donatj/mpo) - MPO 3D 照片解码与转换工具.
* [picfit](https://github.com/thoas/picfit) - 一个使用 Go 语言编写的图片缩放服务器
* [pt](https://github.com/fogleman/pt) - 光线追踪引擎
* [resize](https://github.com/nfnt/resize) - 使用 Go 语言编写的具有常见差值功能的图片缩放工具
* [rez](https://github.com/bamiaux/rez) - 纯 Go 及 SIMD 实现的图像缩放库
* [smartcrop](https://github.com/muesli/smartcrop) - 为任意图片进行剪裁的工具
* [svGo](https://github.com/ajstarks/svGo) - 用于生成 SVG 的 Go 语言库
* [tga](https://github.com/ftrvxmtrx/tga) - tga 是一个 TARGA 图像格式解码/编码器

## 物联网

_用于为物联网设备编程的库._

* [connectordb](https://github.com/connectordb/connectordb) - 开源个人数据及物联网平台
* [devices](https://github.com/Goiot/devices) - 物联网设备套件库
* [eywa](https://github.com/xcodersun/eywa) - Eywa 是一个持续追踪所有连接设备的连接管理器
* [floGo](https://github.com/tibcosoftware/floGo) - FloGo 是一个用于物联网 Edge App 及集成的开源框架
* [gatt](https://github.com/paypal/gatt) - Gatt 是一个用于创建低功耗蓝牙外设的库
* [Gobot](https://github.com/hybridgroup/Gobot/) - Gobot 是一个用于机器人，物理计算以及物联网的库
* [mainflux](https://github.com/Mainflux/mainflux) - 工业网物联网消息及设备管理服务器
* [sensorbee](https://github.com/sensorbee/sensorbee) - 轻量级物联网流处理引擎

## 日志

_用于生成和操作日志文件的库._

* [glg](https://github.com/kpanGo/glg) - glg 是一个简单、快速、分级的日志库
* [glog](https://github.com/Golang/glog) - 分级记录日志的库
* [Go-cronowriter](https://github.com/utahta/Go-cronowriter) 对日志文件进行自动循环写入的库基于当前日期和时间，类似 cronolog.
* [Go-log](https://github.com/siddontang/Go-log) - 支持多处理器及日志分级的库
* [Go-log](https://github.com/ian-kent/Go-log) - Go 语言实现的 Log4j
* [Go-logger](https://github.com/apsdehal/Go-logger) - 支持日志分级的简单的日志工具
* [Gologger](https://github.com/sadlil/Gologger) - 简单易用的日志库，可以在彩色控制台、简易控制的、文件或 Elasticsearch 中记录
* [Gomol](https://github.com/aphistic/Gomol) - 支持多种输出，结构化的日志模块，可以扩展它的输出
* [Gone/log](https://github.com/One-com/Gone/tree/master/log#readme) - 快速、可扩展、全功能、兼容标准库的日志库
* [log](https://github.com/apex/log) - 结构化日志库
* [log](https://github.com/Go-playground/log) - 简单、可配置、可扩展的结构化日志库
* [log-voyage](https://github.com/firstrow/logvoyage) - 全功能日志saas 使用 Go 语言编写
* [log15](https://github.com/inconshreveable/log15) - 简单强大的日志库
* [logdump](https://github.com/ewwwwwqm/logdump) - 支持分级的日志库
* [logex](https://github.com/chzyer/logex) - Go 语言日志库，支持追踪和分级，基于标准库进行了封装
* [logger](https://github.com/azer/logger) - 一个极简的日志库
* [logrus](https://github.com/Sirupsen/logrus) - 支持结构化的日志工具.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) 的插件，用于将错误发送到 [Loggly](https://www.loggly.com/).
* [logutils](https://github.com/hashicorp/logutils) - 对 Go 语言标准日志工具进行了扩展，使其更好用
* [logxi](https://github.com/mgutz/logxi) - 十二要素 app 日志工具，非常快速，令你开心
* [lumberjack](https://github.com/natefinch/lumberjack) - 简单的循环日志工具，实现了 io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - 一个简单的日志模块，可以分5级并有一个可选的循环日志文件记录功能，支持 stdout/stderr 输出.
* [ozzo-log](https://github.com/Go-ozzo/ozzo-log) - 高性能日志库，支持日志严重级别、分类及过滤。可以将过滤后的信息发送到不同的目的地(例如： 控制台、网络、邮箱).
* [seelog](https://github.com/cihub/seelog) - 一个灵活的、解耦的、格式化的日志库
* [slf](https://github.com/ventu-io/slf) - 简单日志门面（The Structured Logging Facade (SLF) ） (类似 SLF4J，但是它是结构化的，并且专为 Go 语言设计)
* [slog](https://github.com/ventu-io/slog) - 为 Go 语言实现的结构化日志门面（Structured Logging Facade (SLF) ）
* [spew](https://github.com/davecgh/Go-spew) - 为 Go 语言的数据结构实现了一个整洁的打印功能，有助于调试
* [stdlog](https://github.com/alexcesaro/log) - Stdlog 是一个面向对象的库，提供了分级日志功能，对于定时任务很有用.
* [tail](https://github.com/hpcloud/tail) - 这个 Go 语言软件包力争模拟 BSD tail 的功能
* [xlog](https://github.com/xfxdev/xlog) - 插件架构以及灵活的日志系统，具有日志等级控制，多日志目标以及自定义日志格式功能
* [xlog](https://github.com/rs/xlog) - 结构化日志 for `net/context` aware HTTP handlers ，可以灵活的分发
* [zap](https://github.com/uber-Go/zap) - 快速的、结构化的、分级的日志库
* [zerolog](https://github.com/rs/zerolog) - 零分配 JSON 日志.

## 机器学习

_机器学习库_

* [bayesian](https://github.com/jbrukh/bayesian) - 贝叶斯分类器
* [CloudForest](https://github.com/ryanbressler/CloudForest) - 纯 Go 语言编写的快速、灵活、多线程决策树
* [gaGo](https://github.com/MaxHalford/gaGo) - 多种群，灵活的，并行的遗传算法
* [Go-fann](https://github.com/white-pony/Go-fann) - 快速人工神经网络库(FANN)的 Go 语言借口.
* [Go-galib](https://github.com/thoj/Go-galib) - Go 语言编写的遗传算法库
* [Go-pr](https://github.com/daviddengcn/Go-pr) -  Go 语言模式识别库
* [Gobrain](https://github.com/Goml/Gobrain) -  Go 语言编写的神经网络
* [Godist](https://github.com/e-dard/Godist) - 多种概率分布及相关方法
* [Goga](https://github.com/tomcraven/Goga) -  Go 语言遗传算法库
* [GoLearn](https://github.com/sjwhitworth/Golearn) -  Go 语言通用机器学习库
* [Golinear](https://github.com/danieldk/Golinear) - liblinear 库的 Go 语言接口
* [Goml](https://github.com/cdipaolo/Goml) - 即时go语言机器学习库
* [GoRecommend](https://github.com/timkaye11/GoRecommend) - Go 语言推荐算法库
* [GorGonia](https://github.com/chewxy/GorGonia) - 基于图的计算库，类似于 Theano。提供了一些原型用于构建各种个样的机器学习和神经网络算法
* [libsvm](https://github.com/datastream/libsvm) - libsvm 的 Go 语言版本，基于 LIBSVM 3.14.
* [mlGo](https://github.com/NullHypothesis/mlGo) - 这个项目点目标是在 Go 语言中提供极简的机器学习算法
* [neat](https://github.com/jinyeom/neat) - 即插即用的并行 Go 语言框架，用于增强拓扑神经网络 (NEAT).
* [neural-Go](https://github.com/schuyler/neural-Go) - Go 语言实现的多层感知神经网络，通过反向传播算法进行训练.
* [probab](https://github.com/ThePaw/probab) -概率分布函数、贝叶斯推理。使用纯 Go 语言编写
* [reGommend](https://github.com/muesli/reGommend) - 推荐系统及协同过滤引擎
* [shield](https://github.com/eaigner/shield) - 贝叶斯文吧分类器，包含灵活的分词器和存储后端

## 消息

_实现了消息系统的库_

* [CentrifuGo](https://github.com/centrifugal/centrifuGo) - 实时消息服务器
* [dbus](https://github.com/Godbus/dbus) - D-Bus的 Go 语言接口
* [drone-line](https://github.com/appleboy/drone-line) - 通过软件包，docker 或是 Drone CI来发送 [Line](https://business.line.me/en/services/bot) 通知
* [emitter](https://github.com/olebedev/emitter) - 通过Go语言的方式发送事件消息，可以使用通配符，断言，取消发送等优秀特性
* [EventBus](https://github.com/asaskevich/EventBus) - 轻量级事件库，支持异步
* [gaurun-client](https://github.com/osaminGo/gaurun-client) - Go 语言编写的 Gaurun 客户端
* [Glue](https://github.com/desertbit/glue) - 健壮的 Go 和 Javascript Socket 库 (可以用来替代 Socket.io).
* [Go-longpoll](https://github.com/ventu-io/Go-longpoll) -  支持长轮询的发布与订阅
* [Go-notify](https://github.com/TheCreeper/Go-notify) - 原生实现的桌面通知规范
* [Go-nsq](https://github.com/nsqio/Go-nsq) - NSQ 官方 Go 语言库
* [Go-socket.io](https://github.com/GooGollee/Go-socket.io) - Go 语言的 socket.io库 ,一个实时应用框架.
* [Go-vitotrol](https://github.com/maxatome/Go-vitotrol) - Viessmann Vitotrol 服务的 Go 语言客户端
* [Gollum](https://github.com/trivaGo/Gollum) - 一个 n:m 的多路复用器，从不同的源汇聚消息并向目标进行广播
* [Golongpoll](https://github.com/jcuga/Golongpoll) - HTTP 长轮询服务器库，让 web 发布与订阅变的更简单.
* [Goose](https://github.com/ian-kent/Goose) - Go 语言实现的服务器端事件发送
* [Gopush-cluster](https://github.com/Terry-Mao/Gopush-cluster) - Gopush-cluster 是一个 Go 语言实现的支持集群的comet服务（支持 websocket，和tcp协议）
* [Gorush](https://github.com/appleboy/Gorush) - 通知推送服务器，使用 [APNs2](https://github.com/sideshow/apns2) 和 Google [GCM](https://github.com/Google/Go-gcm).
* [guble](https://github.com/smancke/guble) - 一个使用通知推送(Google Firebase Cloud Messaging, Apple Push Notification services, SMS)、websockets 、REST API 的消息服务器。提供了分布式操作和消息持久化特性
* [machinery](https://github.com/RichardKnop/machinery) - 异步任务队列，基于分布式消息处理
* [manGos](https://github.com/Go-manGos/manGos) - 纯 Go 语言实现的 Nanomsg ("Scalable Protocols") 
* [melody](https://github.com/olahol/melody) - 用于处理 websocket 会话的一个极简框架，包括广播和自动 ping/pong 处理
* [NATS Go Client](https://github.com/nats-io/nats) - 轻量级高性能发布订阅(publish-subscribe) 以及分布式消息队列系统，这个一个Go语言库.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - 针对 NSQ 的主题和频道进行了简单的封装
* [oplog](https://github.com/dailymotion/oplog) - 原生的 oplog/replication 系统，用于 REST APIs
* [pubsub](https://github.com/tuxychandru/pubsub) - 一个简单的 pubsub 软件包
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ 是一个轻量级，可靠的本地消息队列管理库
* [sarama](https://github.com/Shopify/sarama) - 用于 Apache Kafka 的库
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - 基于 Redis 的统一推服务，用于服务器端向移动客户端推送消息
* [zmq4](https://github.com/pebbe/zmq4) - ZeroMQ version 4的 GO 语言接口。也有适用于[version 3](https://github.com/pebbe/zmq3) 及 [version 2](https://github.com/pebbe/zmq2)的

## 杂项

_一些暂时无法归类的库_

* [alice](https://github.com/magic003/alice) -  GO 语言依赖注入容器
* [archiver](https://github.com/mholt/archiver) - 用于制作和解压 .zip 和 .tar.gz 文件的库和命令
* [autoflags](https://github.com/artyom/autoflags) - 通过结构体自动定义命令行标记的go语言软件包
* [avgRating](https://github.com/kirillDanshin/avgRating) - 利用 Wilson Score 方程计算平均分及评级
* [banner](https://github.com/dimiro1/banner) - 在你的go语言应用中添加炫酷的横幅
* [battery](https://github.com/distatus/battery) - 跨平台电源信息库
* [bitio](https://github.com/icza/bitio) - 高度优化的比特级读写
* [browscap_Go](https://github.com/digitalcrab/browscap_Go) - [Browser Capabilities Project](http://browscap.org/)的 GO 语言库
* [conv](https://github.com/cstockton/Go-conv) - conv 提供了一种快速且符合直觉的 GO 语言类型转换
* [datacounter](https://github.com/miolini/datacounter) - Greaders/writer/HTTP.ResponseWriter 计数器
* [errors](https://github.com/pkg/errors) - 提供简单的错误处理
* [Go-chat-bot](https://github.com/Go-chat-bot/bot) - IRC、Slack、Telegram 聊天机器人
* [Go-commons-pool](https://github.com/jolestar/Go-commons-pool) - 通用对象池
* [Go-multierror](https://github.com/hashicorp/Go-multierror) - 这个 Go 语言库用于将一系列的错误作为一个整体来显示
* [Go-openapi](https://github.com/Go-openapi) - 一些用于处理和利用 open-api 的库集合
* [Go-resiliency](https://github.com/eapache/Go-resiliency) - GO 语言弹性模式
* [Go-sarah](https://github.com/oklahomer/Go-sarah) - 用于构建聊天机器人的框架，支持 LINE, Slack, Gitter等等
* [Go-shortid](https://github.com/ventu-io/Go-shortid) - 超短的、唯一的、非序列的、对 url 友好的 id
* [Go-unarr](https://github.com/gen2brain/Go-unarr) - 解压缩库，可用于 RAR, TAR, ZIP 以及 7z 归档文件.
* [Go.uuid](https://github.com/satori/Go.uuid) - 全球唯一标示符的实现(UUID)，同时支持生成和解析
* [Gofakeit](https://github.com/brianvoe/Gofakeit) - Go 语言编写的随机数据生成器
* [Goid](https://github.com/jakehl/Goid) - 生成和解析符合 RFC4122 规定的 V4 UUIDs.
* [Gopsutil](https://github.com/shirou/Gopsutil) - 用于获取进程和系统资源利用率（cpu，内存，磁盘）的库，跨平台
* [Gosms](https://github.com/haxpax/Gosms) - 你本地的SMS 网关，可以用来发送 SMS
* [Gountries](https://github.com/pariz/Gountries) - 一个用来展示国家及其行政区划数据的库
* [hanu](https://github.com/sbstjn/hanu) - 用于编写 Slack 聊天机器人的库
* [health](https://github.com/dimiro1/health) - 简单易用、可扩展的健康检查库
* [indiGo](https://github.com/osaminGo/indiGo) - 唯一id生成器，使用 Sonyflake 并通过Base58进行编码
* [jobs](https://github.com/albrow/jobs) - 持久化且灵活的后台任务库
* [margelet](https://github.com/zhulik/margelet) - 用于创建 Telegram 聊天机器人的库
* [secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload alGorithm ported to Go to secure download urls.
* [slacker](https://github.com/shomali11/slacker) - 用于编写 Slack 聊天机器人的库，非常易用
* [stats](https://github.com/Go-playground/stats) - 监控 Go 内存状态及系统状态，通过UDP将数据发送到任何地方
* [uuid](https://github.com/agext/uuid) - 生成，编解码 UUIDs v1 ，具有快速的或或密钥级随机节点标识
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate HTTP input and ouput handling.
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
* [xkg](https://github.com/Go-xkg/xkg) - X Keyboard Grabber
* [xstrings](https://github.com/huandu/xstrings) - 一些有用的字符串函数的集合

## 自然语言处理

_用于处理人类语言的库_

* [dpar](https://github.com/danieldk/dpar/) - 基于变换的统计依赖关系解析器
* [Go-eco](https://github.com/ThePaw/Go-eco) - 相似性，相异性及距离度量；差异性，均匀度和不均匀度测量；物种多样性估计；群落线模型
* [Go-i18n](https://github.com/nicksnyder/Go-i18n/) - 软件包及相关工具，用于处理本地化文本
* [Go-mystem](https://github.com/dveselov/mystem) - Yandex.Mystem 的  CGo 接口， Yandex.Mystem 是一个俄语词汇形态学分析器
* [Go-nlp](https://github.com/nuance/Go-nlp) - 在进行自然语言工作时用于处理离散概率分布一些工具，以及其他的一些有用的工具
* [Go-stem](https://github.com/aGonopol/Go-stem) - 波特词干算法的一个实现
* [Go-unidecode](https://github.com/mozillazg/Go-unidecode) - Unicode 文本音译为 ASCII 文本
* [Go2vec](https://github.com/danieldk/Go2vec) - 利用 Go 语言读取和处理 word2vec 
* [Gojieba](https://github.com/yanyiwu/Gojieba) - 结巴分词的 Go 语言实现的 [jieba](https://github.com/fxsjy/jieba) ，结巴分词是一个用于中文的分词算法
* [Golibstemmer](https://github.com/rjohnsondev/Golibstemmer) -  snowball libstemmer 库的 Go 语言接口，包括了对 porter 2 的支持
* [Gounidecode](https://github.com/fiam/Gounidecode) - Go 语言的 Unicode 直译器 (通常称之为 unidecode) 
* [icu](https://github.com/Goodsign/icu) - icu4c C 库的 CGo 接口，包括了检测和转换函数。保证了 version 50.1 版本的兼容性
* [libtextcat](https://github.com/Goodsign/libtextcat) - libtextcat C 库的 CGo 接口。保证了version 2.2 版本的兼容性
* [MMSEGo](https://github.com/awsong/MMSEGo) -  Go 语言实现的 [MMSEG](http://technology.chtsai.org/mmseg/) （一个中文分词算法）
* [nlp](https://github.com/Shixzie/nlp) - 从字符串中提取特定的值并填充结构体
* [paicehusk](https://github.com/rookii/paicehusk) - Go 语言实现的  Paice/Husk 词干算法
* [porter](https://github.com/a2800276/porter) - Martin Porter 实现的 C 语言版本的 Porter 词干算法的 Go 语言接口，非常直观
* [porter2](https://github.com/zhenjl/porter2) - 非常快速的 Porter 2 stemmer.
* [prose](https://github.com/jdkato/prose) - 文本处理库，支持词语切分、词性标记、命名实体提取等功能
* [RAKE.Go](https://github.com/Obaied/RAKE.Go) -  快速自动关键字提取算法(Rapid Automatic Keyword Extraction：RAKE)的 Go 语言接口
* [segment](https://github.com/blevesearch/segment) - 一个用于进行 Unicode 文本分割的库，实现了 [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)中描述的功能
* [sentences](https://github.com/neurosnap/sentences) - 语句标记器：将文字段落转换为语句列表
* [shamoji](https://github.com/osaminGo/shamoji) -  shamoji 是一个Go语言编写的词过滤软件包
* [snowball](https://github.com/Goodsign/snowball) - Snowball 分词器的Go语言接口，提供了分词提取的功能 [Snowball native](http://snowball.tartarus.org/).
* [stemmer](https://github.com/dchest/stemmer) -  Go 语言分词器软件包，包括了英语和德语分词器
* [textcat](https://github.com/pebbe/textcat) - 基于 n-gram 的 Go 语言文本分类软件包，支持utf-8 和 raw 文本
* [whatlangGo](https://github.com/abadojack/whatlangGo) - Go 语言的自然语言检测包。支持84种语言和24种书写 (如拉丁，西里尔等书写系统)。
* [when](https://github.com/olebedev/when) - 英语、俄语的自然语言日期、时间表达解析器，可以插入规则


## 网络

_用于在不同网络层工作的库_

* [arp](https://github.com/mdlayher/arp) - 实现了 ARP 协议，遵循 RFC 826.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - 简单易用的 protocolbuffer 数据流，基于 TCP
* [canopus](https://github.com/zubairhamed/canopus) - CoAP 客户端/服务器实现 (RFC 7252)
* [dhcp6](https://github.com/mdlayher/dhcp6) - dhcp6 实现了一个DHCPv6 服务器，遵循RFC 3315.
* [dns](https://github.com/miekg/dns) - 用于处理 DNS 的 Go 语言库
* [ether](https://github.com/songgao/ether) - 跨平台 Go 语言库，用于发送和接收以太帧
* [ethernet](https://github.com/mdlayher/ethernet) - ethernet 实现了IEEE 802.3 Ethernet II 帧以及IEEE 802.1Q VLAN 标签的组装和剥离.
* [fasthttp](https://github.com/valyala/fasthttp) - fasthttp 是一个快速的 HTTP 实现，是 net/http的10倍性能
* [ftp](https://github.com/jlaffaye/ftp) - ftp 实现了一个 FTP 客户端，遵循 [RFC 959](http://tools.ietf.org/html/rfc959).
* [Go-getter](https://github.com/hashicorp/Go-getter) - 一个用于通过 URL 从多种源下载文件或目录的 Go 语言库
* [Go-stun](https://github.com/ccding/Go-stun) - Go 语言实现的 STUN 客户端 (RFC 3489 及 RFC 5389).
* [Gobgp](https://github.com/osrg/Gobgp) - Go 语言实现的BGP
* [Golibwireshark](https://github.com/sunwxg/Golibwireshark) - Golibwireshark 使用 libwireshark 库来解析 pcap 文件并且分析数据
* [Gopacket](https://github.com/Google/Gopacket) - 用于报文处理的库
* [Gopcap](https://github.com/akrennmair/Gopcap) - libpcap的 Go 语言封装
* [Goshark](https://github.com/sunwxg/Goshark) - Goshark 使用 tshark 来对 IP 报文进行解码并创建数据结构用于分析报文
* [Gosnmp](https://github.com/soniah/Gosnmp) -用于执行 SNMP 操作的库
* [Gotcp](https://github.com/gansidui/Gotcp) - 用于快速编写 tcp 应用的库
* [grab](https://github.com/cavaliercoder/grab) - 管理文件下载的 Go 语言库
* [graval](https://github.com/koofr/graval) - 试验性的 FTP 服务器框架
* [jaziGo](https://github.com/udhos/jaziGo) - JaziGo 是一个 Go 语言编写的工具，用于获取多种网络设备的配置.
* [kcp-Go](https://github.com/xtaci/kcp-Go) - KCP - 快速可靠的 ARQ 协议.
* [kcptun](https://github.com/xtaci/kcptun) - 超级简单、快速的 udp 通道，基于KCP 协议
* [lhttp](https://github.com/fanux/lhttp) - 强大的 websocket 框架，可以更简单的构建你自己的 IM 服务器*
* [linkio](https://github.com/ian-kent/linkio) - 接口读写速度模拟器
* [llb](https://github.com/kirillDanshin/llb) - 一个非常简单但快速的后端代理服务器。对于快速重定向到预定义域名很有用，无内存分配，响应速度快
* [mdns](https://github.com/hashicorp/mdns) - 简单的 mDNS (组播 DNS) 客户端/服务器库
* [mqttPaho](https://eclipse.org/paho/clients/Golang/) - Paho 客户端提供了一个 MQTT 客户端库，用于通过TCP, TLS 或 WebSockets 和 MQTT broker 建立连接
* [portproxy](https://github.com/aybabtme/portproxy) - 简单的 TCP 代理，加入了对CORS 的支持
* [publicip](https://github.com/polera/publicip) - publicip 库会返回你的公网 ip 地址 (互联网出口).
* [raw](https://github.com/mdlayher/raw) - raw 允许你在设备驱动层读写网络接口的数据
* [sftp](https://github.com/pkg/sftp) - sftp 实现了https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.中描述的 SSH 文件传输协议
* [ssh](https://github.com/gliderlabs/ssh) - 用于创建 SSH 服务器的高级 API (封装crypto/ssh).
* [sslb](https://github.com/eduardonunesp/sslb) - 一个超简单的负载均衡库，仅仅是一个为了获取一些性能目标的小项目
* [tcp_server](https://github.com/firstrow/tcp_server) - 一个用于快速创建 tcp 服务器的库
* [utp](https://github.com/anacrolix/utp) - Go uTP 微传输协议的实现
* [water](https://github.com/songgao/water) - 简单的 TUN/TAP 库
* [winrm](https://github.com/masterzen/winrm) - Go WinRM 客户端，用于在 Windows 设备上远程执行命令
* [xtcp](https://github.com/xfxdev/xtcp) - TCP 服务器框架，支持同时全双工通信。可以优雅的关闭，自定义协议

## OpenGL

_用于操作OpenGL的库._

* [gl](https://github.com/Go-gl/gl) - OpenGL的 Go 语言接口
* [glfw](https://github.com/Go-gl/glfw) - GLFW 3 的 Go 语言接口
* [Goxjs/gl](https://github.com/Goxjs/gl) - Go 语言跨平台 OpenGL 接口(OS X, Linux, Windows, browsers, iOS, Android).
* [Goxjs/glfw](https://github.com/Goxjs/glfw) - Go 语言跨平台 glfw 库，用于创建 OpenGL 上下文并接收事件
* [mathgl](https://github.com/Go-gl/mathgl) - Go 语言 3D 数学库，专注于3D，受到 GLM 启发

## ORM

_实现对象关系映射或数据映射技术的库_

* [beeGo orm](https://github.com/astaxie/beeGo/tree/master/orm) - 一个强大的 Go 语言 orm 框架，支持 pq/mysql/sqlite3.
* [Go-pg](https://github.com/Go-pg/pg) - PostgreSQL ORM ，专注PostgreSQL 特定功能及性能
* [Go-store](https://github.com/Gosuri/Go-store) - 简单快速的基于Redis 的键值对存储库
* [Gomodel](https://github.com/cosiner/Gomodel) - 轻量级、快速的、类 orm 库，帮助你和数据库进行交互
* [GoRM](https://github.com/jinzhu/Gorm) - 超棒的 Go 语言 ORM 库，对开发者非常友好
* [Gorp](https://github.com/Go-Gorp/Gorp) - 关系持久的、类 orm 的 Go 语言库
* [pop/soda](https://github.com/markbates/pop) - 数据库迁移、创建、ORM 等等，支持 MySQL, PostgreSQL, 以及 SQLite.
* [QBS](https://github.com/coocood/qbs) - 利用结构体进行标准查询，是一个 Go 语言 ORM
* [reform](https://github.com/Go-reform/reform) - 一个更优秀的 ORM，基于非空接口和代码生成
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM 生成器。为你的数据库表单生成一个功能全面、快速的 ORM
* [upper.io/db](https://github.com/upper/db) - 通过使用封装了成熟的数据库驱动的适配器，来使用单一接口与不同的数据源进行交互
* [Xorm](https://github.com/Go-xorm/xorm) - 简单、强大的 Go 语言 orm
* [Zoom](https://github.com/albrow/zoom) - 超快的数据存储于查询引擎，基于 Redis 构建

## 包管理

_用于进行包和依赖管理的库_

* [dep](https://github.com/Golang/dep) - Go 语言依赖工具.
* [giGo](https://github.com/LyricalSecurity/giGo) - 类似 PIP 的依赖管理工具。支持私有仓库和哈希
* [glide](https://github.com/Masterminds/glide) - 轻松管理你的 GO 语言包发布者以及发布包。 受到类似 Maven, Bundler, 和 Pip 这些工具的的启发
* [Godep](https://github.com/tools/Godep) - Go 语言依赖工具，Godep 可以帮助开发者修复库的依赖关系
* [Gom](https://github.com/mattn/Gom) - Go Manager
* [Goop](https://github.com/nitrous-io/Goop) - 简单的依赖管理工具，手到 Bundler 的启发
* [Gopm](https://github.com/gpmGo/Gopm) - Go 包管理器
* [Govendor](https://github.com/kardianos/Govendor) - Go 包管理器。 Go 语言 vendor 工具，兼容标准 vendor 文件
* [gpm](https://github.com/pote/gpm) -  Go 语言包管理工具
* [gvt](https://github.com/FiloSottile/gvt) - `gvt` 是一个简单的发布管理工具(aka Go15VENDOREXPERIMENT), 基于 gb-vendor.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - 极简的依赖版本管理工具，使用 git
* [nut](https://github.com/jingweno/nut) - Go 语言依赖管理
* [VenGo](https://github.com/DamnWidget/VenGo) - 创建并管理可以导出的，隔离的 Go 语言虚拟环境

## 查询语言

* [graphql](https://github.com/tmc/graphql) - graphql 解析器 + 实用工具
* [graphql](https://github.com/sevki/graphql) - Go 语言实现的 GraphQL
* [graphql](https://github.com/neelance/graphql-Go) - 专注于易用性的 GraphQL 服务器
* [graphql-Go](https://github.com/graphql-Go/graphql) - 为 Go 语言实现的 GraphQL
* [jsonql](https://github.com/elgs/jsonql) - JSON 查询表达式库

## 资源嵌入

* [esc](https://github.com/mjibson/esc) - 在 Go 语言程序中嵌入文件并为其提供 HTTP.FileSystem 接口
* [fileb0x](https://github.com/UnnoTed/fileb0x) - 一个用于在 Go 语言程序中嵌入文件的工具，专注于可定制化和易用性
* [Go-bindata](https://github.com/jteeuwen/Go-bindata) - 一个用于将文件转换为可管理的 Go 语言代码的工具
* [Go-embed](https://github.com/pyros2097/Go-embed) - 生成用于嵌入资源文件到库或可执行文件的 Go 语言代码
* [Go-resources](https://github.com/omeid/Go-resources) - 一个简洁的 Go 语言资源嵌入工具
* [Go.rice](https://github.com/GeertJohan/Go.rice) - Go.rice 是一个让你轻松使用 html,js,css,图片以及模板这类资源的库
* [statics](https://github.com/Go-playground/statics) - 将静态资源嵌入到 Go 文件中，用于单独二进制编译+使用http.FileSystem + symlinks.
* [statik](https://github.com/rakyll/statik) - 将静态文件嵌入到 Go 语言可执行文件中
* [templify](https://github.com/wlbr/templify) - 将外部目标文件嵌入到 Go 代码中来创建单独的二进制文件
* [vfsgen](https://github.com/shurcooL/vfsgen) - 生成一个 vfsdata.Go 文件，静态实现了一个虚拟文件系统

## 科学及数据分析

_用于科学计算和数据分析的库_

* [blas](https://github.com/ziutek/blas) - BLAS (基础线性代数子程序 Linear Algebra Subprograms)的 Go 语言实现
* [chart](https://github.com/vdobler/chart) - 简单的图表绘图库。支持多种图表类型
* [evaler](https://github.com/soniah/evaler) - 简单浮点算数表达式求值器
* [ewma](https://github.com/VividCortex/ewma) - 指数移动加权平均值
* [geom](https://github.com/skelterjohn/geom) - 2D 几何
* [Go-dsp](https://github.com/mjibson/Go-dsp) - 数字信号处理
* [Go-fn](https://github.com/ematvey/Go-fn) - 一些没有包含在 math pkg 中的数学函数
* [Go-gt](https://github.com/ThePaw/Go-gt) - 图论算法
* [Go.matrix](https://github.com/skelterjohn/Go.matrix) - 线性代数
* [Gocomplex](https://github.com/varver/Gocomplex) - 复数库
* [Gofrac](https://github.com/anschelsc/Gofrac) - Go 语言分数库，支持基本算术
* [Gohistogram](https://github.com/VividCortex/Gohistogram) - 数据流的近似直方图
* [Gonum/mat64](https://github.com/Gonum/matrix) - 矩阵计算通用包。 mat64 提供了用于进行64位浮点基础线性代数操作的功能
* [Gonum/plot](https://github.com/Gonum/plot) - Gonum/plot 提供了用于创建和绘制图表的 API
* [Goraph](https://github.com/gyuho/Goraph) - 纯 Go 语言编写的图论库（数据结构，算法可视化）
* [Gostat](https://github.com/ematvey/Gostat) - 统计库
* [graph](https://github.com/yourbasic/graph) - 包含基础图算法的库
* [ode](https://github.com/ChristopherRabotin/ode) - 普通微分方程 (ODE) 求解器。支持扩展状态及基于通道的迭代算法终止条件
* [pagerank](https://github.com/alixaxel/pagerank) - Go 语言实现的加权网页排名（ PageRank）算法
* [PiHex](https://github.com/clayGod/PiHex) - 贝利-波尔温-普劳夫公式（"Bailey-Borwein-Plouffe"）算法的实现，用于计算十六进制π
* [stats](https://github.com/montanaflynn/stats) - 统计库，包含一些 Go 语言标准库中漏掉的常用函数
* [streamtools](https://github.com/nytlabs/streamtools) - 通用图形化工具，用于处理流数据
* [vectormath](https://github.com/spate/vectormath) - 给 Go 语言用的 Vectormath , 是对索尼的矢量数学库中 C 语言函数的改写,可以在 Bullet-2.79 源码中找到 (当前不活跃)

## 安全

_可以帮助你增强应用程序安全性的库_

* [acmetool](https://github.com/hlandau/acme) — ACME (Let's Encrypt) 客户端工具，有自动延长功能.
* [BadActor](https://github.com/jaredfolkins/badactor) - 一个驻留在内存中的，应用驱动的监控程序，受 fail2ban 的启发
* [Go-yara](https://github.com/hillu/Go-yara) - [YARA](https://github.com/plusvic/yara)的 Go 语言接口，号称是 "对于恶意软件研究者（以及其他人）来说是模式匹配的瑞士军刀
* [leGo](https://github.com/xenolf/leGo) - 纯 Go ACME 客户端库及命令行工具
* [memguard](https://github.com/awnumar/memguard) - 一个用于处理内存中敏感数据的 Go 语言库
* [passlib](https://github.com/hlandau/passlib) - 不过时的密码哈希库
* [secure](https://github.com/unrolled/secure) - Go 语言 HTTP 中间件，为 Go 提供了一些安全功能
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt 库，具有简单、易懂的 API，同时具有内置的自动校准功能
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - 利用 ssh 秘钥加解密

## 序列化

_用于进行二进制序列化的库和工具_

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER 及 DER 编码库
* [colfer](https://github.com/pascaldekloe/colfer) - 用于生成 Colfer 二进制格式代码
* [Go-capnproto](https://github.com/glycerine/Go-capnproto) - Go 语言用的 Cap'n Proto 库及解析器 
* [bambam](https://github.com/glycerine/bambam) - 用于 Go 语言生成 Cap'n Proto schemas 的生成器
* [Go-codec](https://github.com/uGorji/Go) - 高性能、多功能、规范化编码解码以及 rpc 库， 用于 msgpack, cbor 和 json，支持基于运行时的 OR 码生成
* [GoGoprotobuf](https://github.com/GoGo/protobuf) - Go 语言的 Protocol Buffer 库
* [Goprotobuf](https://github.com/Golang/protobuf) - 通过库和协议编译器插件使 Go 语言支持 Google的 protocol buffers.
* [jsoniter](https://github.com/json-iterator/Go) -高性能，100% 兼容的"encoding/json" 替代品
* [mapstructure](https://github.com/mitchellh/mapstructure) - 用于对原生键值对进行解码生成 Go 语言结构体
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - 用于协同 PHP session 格式数据和 PHP 序列化／反序列化函数工作的go语言库
* [structomap](https://github.com/tuvistavie/structomap) - 用于从静态结构体简单、动态的生成键值对的库

## 服务器程序

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web 服务器，支持 Lua、Markdown、GCSS 和 Amber.
* [Caddy](https://github.com/mholt/caddy) - Caddy 是一个备选的 HTTP/2 web 服务器，配置简单，使用方便。
* [consul](https://www.consul.io/) - Consul 是一个用于服务发现、监控和配置的工具
* [devd](https://github.com/cortesi/devd) - 开发者使用的本地 web 服务器
* [etcd](https://github.com/coreos/etcd) - 高可用性的键值存储，用于分享配置和服务发现
* [minio](https://github.com/minio/minio) - Minio 是一个分布式对象存储服务器
* [nsq](http://nsq.io/) - 一个实时的分布式消息平台
* [yakvs](https://github.com/sci4me/yakvs) - 小型化、网络化、基于内存的键值存储

## 模板引擎

_模板库及工具_

* [ace](https://github.com/yosssi/ace) - Ace 是一个 Go 语言的 HTML 模板引擎，受到了 Slim 和 Jade 的启发。 Ace 是对Gold的一种改进。
* [amber](https://github.com/eknkc/amber) - Amber 是一个优雅的模板引擎，受到 HAML 和 Jade的启发
* [damsel](https://github.com/dskinner/damsel) - 标记语言，通过css选择器实现了 html 框架 ，并可以通过 pkg html/template 等进行扩展
* [eGo](https://github.com/benbjohnson/eGo) - 轻量级模板语言，让你可以使用 Go 语言来创建模板。模板会被转化为 Go 语言并编译
* [fasttemplate](https://github.com/valyala/fasttemplate) - 简单快速的模板引擎。进行模板元素替换时，速度是[text/template](http://Golang.org/pkg/text/template/)的十倍
* [Gofpdf](https://github.com/jung-kurt/Gofpdf) - PDF 文档生成器，支持文本，绘图和图片
* [grender](https://github.com/dannyvankooten/grender) - 对 html/template 进行了简单的封装，支持基于文件的模板可以利用其他模板文件进行扩展
* [hero](https://github.com/shiyanhui/hero) Hero 是一个趁手的、快速的、强大的 Go 语言模板引擎
* [jet](https://github.com/CloudyKit/jet) - Jet 模板引擎
* [kasia.Go](https://github.com/ziutek/kasia.Go) - 一个用于HTML 和其他文本文件的模板系统，使用go语言实现
* [liquid](https://github.com/osteele/liquid) - Go 语言实现的 Shopify Liquid 模板.
* [mustache](https://github.com/hoisie/mustache) - Go 语言实现的 Mustache 模板语言
* [ponGo2](https://github.com/flosch/ponGo2) - 类似 DjanGo 的模板引擎
* [quicktemplate](https://github.com/valyala/quicktemplate) - 快速、强大且易用的模板引擎。将模板转化为 Go 语言并进行编译
* [raymond](https://github.com/aymerick/raymond) - 使用 Go 语言实现的完整的 handlebars
* [GoRazor](https://github.com/sipin/Gorazor) - Go 语言的 Razor 视图引擎
* [Soy](https://github.com/robfig/soy) -  Go 语言实现的谷歌闭包模板(也就是 Soy templates) , 参见[official spec](https://developers.Google.com/closure/templates/)
* [velvet](https://github.com/Gobuffalo/velvet) - 使用 Go 语言实现的完整的 handlebars

## 测试

_测试及用于生成测试数据的库._

* 测试框架
    * [assert](https://github.com/Go-playground/assert) - 基础断言库，用于对 Go 语言程序进行测试，提供了一些用于自定义断言的代码块
    * [badio](https://github.com/cavaliercoder/badio) - Go 语言 `testing/iotest` 包的扩展
    * [baloo](https://github.com/h2non/baloo) - 表达性强、多功能的、端到端的HTTP API 测试工具
    * [bro](https://github.com/marioidival/bro) - 监控目录中的文件并对其进行测试
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - 清空数据库用于测试，受到`database_cleaner` 的启发
    * [dsunit](https://github.com/viant/dsunit) - 数据库测试，针对 SQL、 NoSQL、 结构化文件.
    * [frisby](https://github.com/verdverm/frisby) - REST API 测试框架
    * [ginkGo](http://onsi.github.io/ginkGo/) - BDD 测试框架
    * [Go-carpet](https://github.com/msoap/Go-carpet) - 用于在终端中查看测试覆盖率的工具
    * [Go-mutesting](https://github.com/zimmski/Go-mutesting) - Go 语言源代码突变测试（Mutation testing ）
    * [Go-vcr](https://github.com/dnaeon/Go-vcr) - 记录并重放 HTTP 交互，用于快速的、确定性的、准确的测试
    * [Goblin](https://github.com/franela/Goblin) - 类似 Mocha 的测试框架
    * [Gocheck](http://labix.org/Gocheck) - 更加高级的测试框架，用于替换 Gotest.
    * [GoConvey](https://github.com/smartystreets/Goconvey/) - BDD 风格的测试框架，具有 web 界面和计时刷新功能
    * [Godog](https://github.com/DATA-DOG/Godog) - 类似 Cucumber 或 Behat 的 BDD 框架
    * [Gofight](https://github.com/appleboy/Gofight) - 对 Go 语言的路由框架进行 API 测试
    * [Gomega](http://onsi.github.io/Gomega/) - 类似 Rspec 的 matcher/assertion 库
    * [GoSpec](https://github.com/orfjackal/Gospec) - BDD 风格的测试框架
    * [Gospecify](https://github.com/stesla/Gospecify) - 支持 BDD 语法 。对于任何使用过 rspec 等库的人来说应该非常熟悉
    * [Gosuite](https://github.com/pavlo/Gosuite) - 轻量级测试套，为 Go1.7's Subtests 带来了setup/teardown 功能
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect](https://github.com/gavv/httpexpect) - 简洁的、声明式的、易用的端到端HTTP 及 REST API 测试
    * [restit](https://github.com/yookoala/restit) - 帮助编写 RESTful API 集成测试的 Go 语言微型框架.
    * [testfixtures](https://github.com/Go-testfixtures/testfixtures) - 类似 Rails 的测试工具，用于测试数据库应用
    * [Testify](https://github.com/stretchr/testify) - 对标准测试包的扩展
    * [wstest](https://github.com/posener/wstest) - Websocket 客户端，用于对于 websocket HTTP.Handler 进行单元测试
* Mock  
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - 用于生成自包含 mock 对象的工具
    * [Go-sqlmock](https://github.com/DATA-DOG/Go-sqlmock) - Mock SQL ，用于测试数据库交互
    * [Go-txdb](https://github.com/DATA-DOG/Go-txdb) - 基于单事物的数据库驱动，主要用于测试目的
    * [Gock](https://github.com/h2non/Gock) - 多功能、易用 HTTP mock
    * [Gomock](https://github.com/Golang/mock) - 给 Go 语言用的 Mock框架
    * [Govcr](https://github.com/seborama/Govcr) - HTTP mock : 离线测试时记录和重放浏览器的动作
    * [minimock](https://github.com/Gojuno/minimock) - Mock 生成器
    * [mockhttp](https://github.com/tv42/mockhttp) - Go HTTP.ResponseWriter 使用的 Mock 对象
* Fuzzing and delta-debugging/reducing/shrinking
    * [Go-fuzz](https://github.com/dvyukov/Go-fuzz) - 随机化测试系统
    * [Gofuzz](https://github.com/Google/Gofuzz) - 用于生成随机值来初始化 Go 语言对象的库
    * [Tavor](https://github.com/zimmski/tavor) - 通用模糊测试框架
* Selenium 及浏览器控制工具  
    * [cdp](https://github.com/mafredri/cdp) - 类型安全的 Chrome debug协议的 Go 语言接口，可以用于浏览器或任何实现了该协议的其他待调试对象
    * [chromedp](https://github.com/knq/chromedp) - 用于驱动和测试 Chrome, Safari, Edge, Android Webviews, 以及其他支持 Chrome 调试协议的产品
    * [ggr](https://github.com/aandryashin/ggr) - 一个轻量级服务器，可以将 Selenium Wedriver 的请求路由或代理到多个 Selenium hubs.
    * [selenoid](https://github.com/aandryashin/selenoid) - Selenium hub 服务器的替代品，在容器中启动浏览器

## 文本处理

_解析和操作文本的库_

*   特殊格式

    * [allot](https://github.com/sbstjn/allot) - 占位符及通配符文本解析
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - 将 bbCode 转换为 HTML
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown 解析器
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML 清理工具
    * [editorconfig-core-Go](https://github.com/editorconfig/editorconfig-core-Go) - Go 语言用的Editorconfig 文件解析和操作库
    * [enca](https://github.com/endeveit/enca) - [libenca](http://cihar.com/software/enca/)的极简的 cGo 接口
    * [genex](https://github.com/alixaxel/genex) - 计算并展开正则表达式为所有匹配的字符串
    * [github_flavored_markdown](https://Godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub 风格的 Markdown 渲染器 (使用 blackfriday) ，支持代码块高亮以及可点击的锚点
    * [Go-humanize](https://github.com/dustin/Go-humanize) - 时间、数字及内存大小格式化工具
    * [Go-nmea](https://github.com/adrianmo/Go-nmea) - NMEA 解析库
    * [Go-pkg-rss](https://github.com/jteeuwen/Go-pkg-rss) - 这个库可以读取 RSS 以及 Atom feeds，并且提供了一种缓存机制，遵守 feed 标准。
    * [Go-runewidth](https://github.com/mattn/Go-runewidth) - 用于获取字符或字符串固定宽度的函数
    * [Go-slugify](https://github.com/mozillazg/Go-slugify) - 生成漂亮的固定链接地址（slug），支持多种语言
    * [Go-vcard](https://github.com/emersion/Go-vcard) - 解析并且格式化vCard
    * [Gofeed](https://github.com/mmcdole/Gofeed) - 使用 Go 语言解析RSS 和 Atom
    * [Gographviz](https://github.com/awalterschulze/Gographviz) - 用以解析 Graphviz DOT 语言
    * [Gommon/bytes](https://github.com/labstack/Gommon/tree/master/bytes) - 格式化二进制为字符串
    * [Gonameparts](https://github.com/polera/Gonameparts) - 将人名解析为几个独立的部分
    * [Goq](https://github.com/andrewstuart/Goq) - 声明式 HTML 编组，使用结构标签和 jQuery 语法 (使用 GoQuery).
    * [GoQuery](https://github.com/PuerkitoBio/Goquery) - GoQuery 为 Go 语言带来了一组类似 jQuery 的语法和功能
    * [Goregen](https://github.com/zach-klippenstein/Goregen) - 根据正则表达式生成随机字符串
    * [Gotext](https://github.com/leonelquinteros/Gotext) - GNU gettext 工具
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - 通过一个 unicode 文本来猜测该文本使用的语言
    * [inject](https://github.com/facebookGo/inject) - inject 提供来一个基于反射对注入器
    * [mxj](https://github.com/clbanning/mxj) - 将 XML 编解码为 JSON 或 map[string]interface{}; 通过点分路径和通配符来提取值。用于替代Replaces x2j 和 j2x 包.
    * [sh](https://github.com/mvdan/sh) - Shell 解析器及格式化工具
    * [slug](https://github.com/Gosimple/slug) - URL 友好的 slug 化工具，支持多种语言
    * [Slugify](https://github.com/avelino/slugify) - Go 语言静态地址生成器，可以处理字符串
    * [toml](https://github.com/BurntSushi/toml) - TOML 配置格式 format (encoder/decoder with reflection).
*   工具

    * [Gotabulate](https://github.com/bndr/Gotabulate) - 使用 Go 语言简单、美观的打印表格数据
    * [kace](https://github.com/codemodus/kace) - 通用大小写转换工具
    * [parseargs-Go](https://github.com/nproc/parseargs-Go) - 字符串参数解析器，能够理解引用及反斜杠
    * [parth](https://github.com/codemodus/parth) - URL 路径分割解析
    * [radix](https://github.com/yourbasic/radix) - 快速的字符串排序算法
    * [xurls](https://github.com/mvdan/xurls) - 从文本中提取 URL

## 第三方 APIs

_用于访问第三方 APIs 的库_

* [amazon-product-advertising-api](https://github.com/ngs/Go-amazon-product-advertising-api) - [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html) 的 go 语言客户端
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Twitter 1.1 API 的 go 语言客户端
* [aws-sdk-Go](https://github.com/aws/aws-sdk-Go) - AWS 提供的官方go语言 SDK
* [brewerydb](https://github.com/naegelejd/brewerydb) - 用于访问 BreweryDB API的 Go 语言库
* [cachet](https://github.com/andygrunwald/cachet) - [Cachet (open source status page system)](https://cachethq.io/)的 Go 语言客户端
* [circleci](https://github.com/jszwedko/Go-circleci) - 用于和 with CircleCI's API 进行交互的 Go 语言客户端
* [clarifai](https://github.com/samuelcouch/clarifai) - 用语和 Clarifai API 交互的 Go 语言库
* [discordGo](https://github.com/bwmarrin/discordGo) - Discord Chat API 的 Go 语言接口
* [facebook](https://github.com/huandu/facebook) - 支持 Facebook Graph API 的库
* [fcm](https://github.com/maddevsio/fcm) - Firebase Cloud Messaging 的 Go 语言库
* [gads](https://github.com/emiddleton/gads) - Google Adwords 非官方 API
* [gami](https://github.com/bit4bit/gami) - Asterisk Manager Interface 的 Go 语言库
* [gcm](https://github.com/Aorioli/gcm) - Google Cloud Messaging 库
* [geo-Golang](https://github.com/codingsince1985/geo-Golang) - 用于与 [Google Maps](https://developers.Google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), 及 [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) 地理编码 / 反编码 APIs 交互的库
* [ghost](https://github.com/neuegram/ghost) - 用于和 Snapchat API 交互的库
* [github](https://github.com/Google/Go-github) - 用于和 GitHub REST API v3 交互的库
* [githubql](https://github.com/shurcooL/githubql) - 用于和GitHub GraphQL API v4 交互的库
* [Go-imgur](https://github.com/koffeinsource/Go-imgur) - [imgur](https://imgur.com) 的 Go 语言客户端
* [Go-jira](https://github.com/andygrunwald/Go-jira) - [Atlassian JIRA](https://www.atlassian.com/software/jira) 的 Go 语言客户端
* [Go-marathon](https://github.com/gambol99/Go-marathon) - 用于和 Mesosphere's Marathon PAAS 交互的 Go 语言库
* [Go-myanimelist](https://github.com/nstratos/Go-myanimelist) - 用于和 [MyAnimeList API](http://myanimelist.net/modules.php?Go=api)交互的库
* [Go-telegraph](https://github.com/toby3d/Go-telegraph) - Telegraph 发布平台 API 客户端
* [Go-tgbot](https://github.com/olebedev/Go-tgbot) - 纯 Go 语言的Telegram 机器人 API 封装，通过 swagger 文件，基会话的路由和中间件
* [Go-trending](https://github.com/andygrunwald/Go-trending) - 用于获取 Github 上面 [当前流行的代码库](https://github.com/trending) 及 [开发者](https://github.com/trending/developers)
* [Go-twitch](https://github.com/knspriggs/Go-twitch) - 用于和推特v3 API 进行交互的 Go 语言客户端
* [Go-twitter](https://github.com/dghubble/Go-twitter) - 用于和推特v1.1 API 进行交互的 Go 语言客户端
* [Go-unsplash](https://github.com/hbagdi/Go-unsplash) - [Unsplash.com](https://unsplash.com) API 的 Go 语言客户端
* [Go-xkcd](https://github.com/nishanths/Go-xkcd) - xkcd API 的 Go 语言客户端
* [Goamz](https://github.com/mitchellh/Goamz) - [Goamz](https://launchpad.net/Goamz) 的一个fork分支，添加了一些缺失的 API，用于调用特定的软件包。
* [Golyrics](https://github.com/mamal72/Golyrics) - Golyrics 是一个 Go 语言库，用于从 Wikia 上获取歌词
* [GoMusicBrainz](https://github.com/michiwend/Gomusicbrainz) - Go MusicBrainz WS2 客户端
* [Google](https://github.com/Google/Google-api-Go-client) - 为go语言自动生成 Google api
* [Google-analytics](https://github.com/chonthu/Go-Google-analytics) - Google 分析报告的一个简单的封装
* [Google-cloud](https://github.com/GoogleCloudPlatform/gcloud-Golang) - Google Cloud APIs Go 语言客户端库
* [Google-email-audit-api](https://github.com/ngs/Go-Google-email-audit-api) - [Google G Suite Email Audit API](https://developers.Google.com/admin-sdk/email-audit/)的 Go 语言客户端库
* [Gostorm](https://github.com/jsgilmore/Gostorm) - GoStorm 是一个 Go 语言库，实现了在 Go 语言里面编写 Spout 和 Bolt 的协议，用于和 Storm  shells 进行通信
* [Govkbot](https://github.com/nikepan/Govkbot) - 简单的 Go [VK](https://vk.com) 机器人库
* [hipchat](https://github.com/andybons/hipchat) - 这个项目实行了Hipchat API 的 Go 语言客户端
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - 通过使用 XMPP 与 HipChat 进行通信的库
* [Medium](https://github.com/Medium/medium-sdk-Go) - Medium OAuth2 API 的 sdk
* [meGos](https://github.com/andygrunwald/meGos) - 用于访问 [Apache Mesos](http://mesos.apache.org/) 集群的客户端
* [micha](https://github.com/onrik/micha) - 用于[Telegram bot api](https://core.telegram.org/bots/api)的go语言库
* [minio-Go](https://github.com/minio/minio-Go) - go 语言 Minio 客户端，用于 Amazon S3 兼容的云存储
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel 是一个用于追踪事件并发送 Mixpanel profile 的更新到 Mixpanel 的库
* [patreon-Go](https://github.com/mxpv/patreon-Go) - Patreon API.
* [paypal](https://github.com/logpacker/paypalsdk) - PayPal 支付 API
* [playlyfe](https://github.com/playlyfe/playlyfe-Go-sdk) - Playlyfe Rest API 的 Go 语言 SDK
* [pushover](https://github.com/gregdel/pushover) - Pushover API 的 Go 语言封装
* [rrdaclient](https://github.com/Omie/rrdaclient) - 用于接入 statdns.com API 的库——RRDA API。通过HTTP协议进行 DNS查询
* [shopify](https://github.com/rapito/Go-shopify) - 一个用于通过 Shopify API 进行增删改查的 Go 语言库
* [slack](https://github.com/nlopes/slack) - Slack API
* [smite](https://github.com/sergiotapia/smiteGo) - 对 Smite game API 的封装
* [spotify](https://github.com/rapito/Go-spotify) - 用于接入 Spotify WEB API 的 Go 语言库
* [steam](https://github.com/sostronk/Go-steam) - 用于与Steam服务器进行交互的库
* [stripe](https://github.com/stripe/stripe-Go) - Stripe API 的 Go 语言客户端
* [tbot](https://github.com/yanzay/tbot) - Telegram bot 服务器，有类似 net/http 的 api
* [telebot](https://github.com/tucnak/telebot) - go语言编写的 Telegram bot 框架
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - 简洁的 Telegram bot 客户端.
* [textbelt](https://github.com/dietsche/textbelt) - textbelt.com txt messaging API 的go语言客户端
* [TheMovieDb](https://github.com/jbrodriguez/Go-tmdb) - 用于和 [themoviedb.org](https://themoviedb.org) 通信的一个简单的 Go 语言软件包
* [translate](https://github.com/poorny/translate) - Go 在线翻译包
* [Trello](https://github.com/adlio/trello) - Trello API的 Go 语言封装
* [tumblr](https://github.com/mattcunningham/gumblr) - Tumblr v2 API 的 Go 语言封装
* [webhooks](https://github.com/Go-playground/webhooks) - GitHub 和 Bitbucket 的Webhook接收器
* [zooz](https://github.com/Gojuno/Go-zooz) - Zooz API 的 Go 语言客户端

## 实用工具

_可以让你的生活变得更简单的实用工具._
* [abutil](https://github.com/bahlo/abutil) - 常用 Go 语言工具的集合
* [apm](https://github.com/topfreegames/apm) - Go 语言进程管理工具具有HTTP API.
* [boilr](https://github.com/tmrts/boilr) - 一个超快的命令行工具，用于从模板文件生成项目
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Go 语言断路器模式
* [clockwerk](http://github.com/onatm/clockwerk) - 使用简单、流畅的语法来调度周期性任务
* [command](https://github.com/txgruppi/command) - 命令模式，支持线程安全的串行、并行调度
* [coop](https://github.com/rakyll/coop) - Go 语言中常见的并发流程速查表
* [copy-pasta](https://github.com/jutkko/copy-pasta) - 通用多工作站剪切板，使用类似 S3 的后端作为存储
* [ctop](https://github.com/bcicen/ctop) - [类似Top](http://ctop.sh)的接口 (例如 htop) ，用于容器数据收集
* [Death](https://github.com/vrecan/death) - 利用信号管理应用程序的关闭
* [Deepcopier](https://github.com/ulule/deepcopier) - 结构体拷贝
* [delve](https://github.com/derekparker/delve) - Go 语言调试器
* [dlog](https://github.com/kirillDanshin/dlog) - 编译时控制的日志，让你的 release 包变得更小而不需移除 debug 调用
* [excelize](https://github.com/Luxurioust/excelize) - 用于读写 Microsoft Excel (XLSX) 文件的库
* [fastlz](https://github.com/digitalcrab/fastlz) - [FastLz](http://fastlz.org/) (免费，开源，可移植实时压缩库) 的一个封装
* [filetype](https://github.com/h2non/filetype) - 通过数字签名来推测文件类型
* [filler](https://github.com/yaronsumel/filler) - 使用 "fill" 标记来填充结构体的小工具
* [fzf](https://github.com/junegunn/fzf) - 命令行模糊查找工具
* [generate](https://github.com/Go-playground/generate) - 针对一个路径或环境变量，递归的执行 Go generate，可以通过正则表达式来进行过滤
* [gentleman](https://github.com/h2non/gentleman) - 全功能、插件驱动的 HTTP 客户端库
* [git-time-metric](https://github.com/git-time-metric/gtm) - 简单、无缝、轻量级的 Git 时间追踪工具
* [GJSON](https://github.com/tidwall/gjson) - 一行代码获取 JSON
* [Go-astitodo](https://github.com/asticode/Go-astitodo) - 解析你 Go 语言代码中的 TODOs（待办事项） 
* [Go-bind-plugin](https://github.com/wendiGo/Go-bind-plugin) - Go:generate 工具，用于构建 Go 语言插件(1.8 only)，并对导出的符号进行包装
* [Go-cron](https://github.com/rk/Go-cron) - 简单的 Go 语言 Cron 库，可以以不同的时间间隔来执行闭包或函数，从一秒到某年某月某日都可以。主要针对的是 Web 应用或者长期运行的守护进程
* [Go-debug](https://github.com/tj/Go-debug) - 条件调试日志，用于 Go 语言库和应用程序
* [Go-dry](https://github.com/ungerik/Go-dry) - DRY (don't repeat yourself)
* [Go-funk](https://github.com/thoas/Go-funk) - 现代 Go 语言工具库，提供了很多有用的工具 (map, find, contains, filter, chunk, reverse, ...)
* [Go-httpheader](https://github.com/mozillazg/Go-httpheader) - 用于将结构体编码进 http 头的 Go 语言库
* [Go-rate](https://github.com/beefsack/Go-rate) - Go 语言版本的限速器
* [Go-respond](https://github.com/nicklaw5/Go-respond) - 用于处理常见 HTTP JSON 响应的库.
* [Go-sitemap-generator](https://github.com/ikeikeikeike/Go-sitemap-generator) - XML 网站地图生成器
* [Go-torch](https://github.com/uber/Go-torch) - 为 Go 语言程序生成火焰图
* [Go-trigger](https://github.com/sadlil/Go-trigger) - Go 语言全局事件触发器，通过 id 和触发器，在程序的任何地方注册事件
* [Go-underscore](https://github.com/tobyhede/Go-underscore) - 一些有用的 Go 语言工具的集合
* [Goback](https://github.com/carlescere/Goback) - 一个 Go 语言的简单的指数补偿包
* [Godaemon](https://github.com/VividCortex/Godaemon) - 用于编写守护进程的工具
* [Godropbox](https://github.com/dropbox/Godropbox) - 用于编写 Go 语言服务／应用的库，来自 Dropbox.
* [Gohper](https://github.com/cosiner/Gohper) - 多种能够帮助你进行软件开发的工具和模块
* [Gojq](https://github.com/elgs/Gojq) - 通过 Go 语言进行 JSON 查询
* [Gojson](https://github.com/ChimeraCoder/Gojson) - 通过 JSON 自动生成 Go 语言结构体
* [Golarm](https://github.com/msempere/Golarm) - 告警（支持系统事件）
* [Golog](https://github.com/mlimaloureiro/Golog) - 简单、轻量级的命令后工具，用于对你的计划任务进行跟踪
* [Gopencils](https://github.com/bndr/Gopencils) - 简单小巧的 Go 语言库，能够很容易的使用各种 REST APIs.
* [Goplaceholder](https://github.com/michiwend/Goplaceholder) - 一个小巧的 Go 语言库用于生成占位图片
* [Goreleaser](https://github.com/Goreleaser/Goreleaser) - 尽可能快速的发布 Go 语言二进制文件
* [Goreporter](https://github.com/wgliang/Goreporter) - 进行代码静态分析，单元测试，代码检视并生成代码质量报告的工具
* [Goreq](https://github.com/franela/Goreq) - 简洁的 Go 语言 http 请求库
* [Goreq](https://github.com/smallnest/Goreq) - 更加简化的 http客户端，基于 Gorequest.
* [Gorequest](https://github.com/parnurzeal/Gorequest) - 简化的 http 客户端，具有丰富的特性
* [Goseaweedfs](https://github.com/linxGnu/Goseaweedfs) - conseilSeaweedFS 客户端，几乎具有全部的特性
* [Gotenv](https://github.com/subosito/Gotenv) - 从 `.env` 或者任何 `io.Reader`中加载环境变量
* [Goxlsxwriter](https://github.com/fterrag/Goxlsxwriter) - 用于操作 XLSX (Microsoft Excel) 文件的 libxlsxwriter 库的 Go 语言接口
* [gpath](https://github.com/tenntenn/gpath) - 用于简化结构体域访问的库
* [grequests](https://github.com/levigross/grequests) - 简单优雅的 `net/HTTP` 封装，紧随 Python 的 requests 的步伐
* [gron](https://github.com/roylee0704/gron) - 使用简单的 Go 语言 API 和 Gron 调度器创建定时任务
* [htcat](https://github.com/htcat/htcat) - 并行及流水线的 HTTP GET 工具
* [httpcontrol](https://github.com/facebookGo/httpcontrol) - httpcontrol 包，运行进行 HTTP 传输层超时和重传控制
* [hub](https://github.com/github/hub) - 封装了 git 命令，提供了额外的功能用于在终端中和 Github 进行交互
* [hystrix-Go](https://github.com/afex/hystrix-Go) - 实现 Hystrix 风格的、程序员预定义的 fallback 机制（熔断）
* [immortal](https://github.com/immortal/immortal) - \*nix 跨平台 (与操作系统无关的)监控程序
* [intrinsic](https://github.com/mengzhuo/intrinsic) - 不需要编写任何汇编代码就能使用 x86 SIMD
* [JobRunner](https://github.com/bamzi/jobrunner) - 智能的、多功能的定时任务调度器，具有任务队列和实时监控功能
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) -  JSON API errors 的 Go 语言接口.
* [jsonf](https://github.com/miolini/jsonf) - 控制台工具，用于高亮及 JSON 查询功能
* [jsonGo](https://github.com/ricardolonga/jsonGo) - 用于更加方便的构建 JSON 对象的 API
* [jsonhal](https://github.com/RichardKnop/jsonhal) - 一个简单的 Go 语言软件包，用于将自定义结构体转换为 HAL 兼容的 JSON 响应
* [kazaam](https://github.com/Qntfy/kazaam) - 用于传输任意 JSON 文件的 API
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload 服务器
* [mc](https://github.com/minio/mc) - Minio Client 提供了一组工具，用于操作 Amazon S3 兼容云存储和文件系统
* [merGo](https://github.com/imdario/merGo) - 用于将结构体和map合并进 Go 语言的工具。对于配置默认值，避免杂乱的if语句很有帮助
* [minify](https://github.com/tdewolff/minify) - 快速压缩 HTML, CSS, JS, XML, JSON 以及 SVG 文件格式
* [mmake](https://github.com/tj/mmake) - 现代 Make 工具
* [moldova](https://github.com/StabbyCutyou/moldova) - 基于输入目标生成随机数据的工具
* [mp](https://github.com/sanbornm/mp) - 简单的命令行邮件解析器，当前支持标准输入并输出JSON.
* [mssqlx](https://github.com/linxGnu/mssqlx) - HA 客户端，用于主-从 (或主-主) 数据库，集成了简单的、轻量级的轮询调度负载均衡。基于 sqlx.
* [multitick](https://github.com/VividCortex/multitick) - 用于 aligned tickers 的多路复用
* [netbug](https://github.com/e-dard/netbug) - 远程对你的服务进行性能分析
* [ngrok](https://github.com/inconshreveable/ngrok) - 创建到 localhost 的隧道
* [okrun](https://github.com/xta/okrun) - 当 Go 文件运行报错时尝试修复并运行
* [onecache](https://github.com/adelowo/onecache) - 支持多种后端存储的缓存库(Redis, Memcached, 文件系统等)
* [panicparse](https://github.com/maruel/panicparse) - 将类似的协程分组并对调用栈进行着色
* [peco](https://github.com/peco/peco) - 简单的交互式过滤工具
* [pester](https://github.com/sethgrid/pester) - Go HTTP 客户端，具有重传，补偿和并发功能
* [pm](https://github.com/VividCortex/pm) - 基于 HTTP API 的进程管理 (i.e. Goroutine) 
* [profile](https://github.com/pkg/profile) - 一个简单的性能分析软件包
* [rclient](https://github.com/zpatrick/rclient) - 可读性良好、灵活、易用的 REST APIs 客户端
* [realize](https://github.com/tockins/realize) - Go 语言构建系统，可以监控文件变化并重新加载。运行，构建，监控文件并支持自定义路径
* [request](https://github.com/mozillazg/request) - Go 语言版的 HTTP Requests for Humans™.
* [rerate](https://github.com/abo/rerate) - 基于 Redis 的速率计数器和限速器
* [rerun](https://github.com/ivpusic/rerun) - 当源码变化时，重新编译并重新运行 Go 语言编写的 app
* [resty](https://github.com/Go-resty/resty) - 简单的 HTTP 和 REST 客户端，受到 Ruby rest-client 的启发
* [retry](https://github.com/kamilsk/retry) - 基于上下文的功能机制，反复执行命令直到成功
* [robustly](https://github.com/VividCortex/robustly) - 有弹性的执行函数，遇到错误时捕获并重新运行
* [scheduler](https://github.com/carlescere/scheduler) - 从容的进行 Cronjobs 任务调度
* [sling](https://github.com/dghubble/sling) - Go HTTP 请求构造器，用于 API 客户端
* [spinner](https://github.com/briandowns/spinner) - 一个 Go 语言软件包，提供多种选项，方便在终端中创建加载动画
* [sqlx](https://github.com/jmoiron/sqlx) - 为内建的数据库/sql 软件包提供一组扩展
* [Storm](https://github.com/asdine/storm) - 一个用于 BoltDB 的简单又强大的工具
* [Task](https://github.com/Go-task/task) - 简单来讲就是 "Make" 的替代品
* [toolbox](https://github.com/viant/toolbox) - 切片, map, multimap, 结构体, 函数,数据转换工具。服务路由，宏求值和标记器
* [uGo](https://github.com/alxrm/uGo) - uGo 是一个切片工具箱，有着和 Go 语言一致的语法
* [UNIS](https://github.com/esemplastic/unis) - Go 语言字符串处理函数的通用架构
* [usql](https://github.com/knq/usql) - usql 是一个通用的命令行接口，用于操作 sql 数据库
* [util](https://github.com/shomali11/util) - 收集了很多有用的函数
* [wuzz](https://github.com/asciimoo/wuzz) - 交互式命令行程序，用于进行 HTTP 检查
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy 提供了二进制对比功能以及 Go 语言补丁库
* [xlsx](https://github.com/tealeg/xlsx) - 简化了在 Go 语言程序中读取 xml 格式文件的操作

## 验证

_用于验证的库_

* [Govalidator](https://github.com/asaskevich/Govalidator) - 数据验证及清晰工具，用于字符串，数字， 数组切片及结构体
* [ozzo-validation](https://github.com/Go-ozzo/ozzo-validation) - 支持多种数据类型的验证 (结构体，字符串，键值对，数组切片等等)，具有可配置、可扩展的验证规则——使用常用代码结构定义，而非结构体标签
* [validate](https://github.com/markbates/validate) - 提供了一个用于为 Go 语言英语程序编写验证工具的框架
* [validator](https://github.com/Go-playground/validator) - Go 结构体及域验证，包括：跨域、跨结构体, Map, 切片和数组

## 版本控制

_用于版本控制的库_

* [gh](https://github.com/rjeczalik/gh) - 用于 GitHub Webhooks 的可编程服务器以及 net/HTTP 中间件
* [git2Go](https://github.com/libgit2/git2Go) - libgit2 的 Go 语言接口
* [Go-vcs](https://github.com/sourcegraph/Go-vcs) - 通过 Go 语言来操作和检视 VCS 代码仓库
* [hGo](https://github.com/beyang/hGo) - HGo 是一个 Go 语言软件包集合，提供了对本地 Mercurial 仓库的读取能力.

## 视频

_用于操作视频的库_

* [gmf](https://github.com/3d0c/gmf) - FFmpeg av* 库的 Go 语言接口.
* [Go-astisub](https://github.com/asticode/Go-astisub) - 使用 Go 语言操作字幕(.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [Goav](https://github.com/giorgisio/Goav) - 易用的 FFmpeg Go 语言接口
* [gst](https://github.com/ziutek/gst) - GStreamer 的 Go 语言接口
* [v4l](https://github.com/korandiz/v4l) - Linux 下使用的视频截图库，Go 语言编写

## Web 框架

_全栈 web 框架_

* [aah](https://aahframework.org) - 可扩展、高性能、快速发布的 Go 语言 web 框架
* [Air](https://github.com/sheng/air) - 理想的 RESTful web 框架
* [BeeGo](https://github.com/astaxie/beeGo) - beeGo 是一个开源的、高性能的 Go 语言 web 框架
* [Buffalo](http://Gobuffalo.io) - 为 Go 语言带来堪比 Rails 的高生产效率
* [Echo](https://github.com/labstack/echo) - 高性能、极简的 Go 语言 web 框架
* [Fireball](https://github.com/zpatrick/fireball) - 感觉更加自然的 web 框架
* [Florest](https://github.com/jabong/florest-core) - 高性能的、基于工作流的 REST API 框架
* [Gem](https://github.com/Go-gem/gem) - 简单快速的 web 框架，对 REST API 很友好
* [Gin](https://github.com/gin-Gonic/gin) - Gin 是一个 Go 语言编写的 web 框架！提供了一组类似 martini 的 API ，具有更好的性能（40倍）。如果你需要高性能和高生产率，这个框架很适合你
* [Gizmo](https://github.com/NYTimes/gizmo) - 纽约时报正在使用对微服务工具集
* [Go-json-rest](https://github.com/ant0ine/Go-json-rest) - 快速、简单的创建 RESTful JSON API.
* [Go-relax](https://github.com/codehack/Go-relax) - 具有可插拔组建的框架，用于构建 RESTful API's.
* [Go-rest](https://github.com/ungerik/Go-rest) - Go 语言 REST 框架中的小恶魔
* [Goa](https://github.com/raphael/Goa) - 用于开发微服务的框架，基于 Ruby 的 Praxis 的设计
* [Goat](https://github.com/bahlo/Goat) - 极简的 REST API 服务器
* [Golf](https://github.com/dinever/Golf) - Golf 是一个快速、简单、轻量级的 Go 语言微型 web 框架。具有强大的功能且没有标准库以外的依赖
* [Gondola](https://github.com/rainycape/Gondola) - 用于快速编写高性能网站的框架
* [Gongular](https://github.com/mustafaakin/Gongular) - 快速 Go web 框架，支持输入映射／验证以及依赖注入
* [Macaron](https://github.com/Go-macaron/macaron) - Macaron 是一个高效的模块化设计的web框架
* [manGo](https://github.com/paulbellamy/manGo) - ManGo 是一个模块化 web 应用框架，受到 Rack 和 PEP333 的启发
* [Microservice](https://github.com/clayGod/microservice) - 用于创建微服务的框架，使用 Go 语言编写
* [neo](https://github.com/ivpusic/neo) - 是一个极小且快速的 Go 语言 web 框架，具有及其简单的 API
* [Resoursea](https://github.com/resoursea/api) - 用于快速编写基于资源对服务的 REST 框架
* [REST Layer](http://rest-layer.io) - 用于构建在数据库之上构建 REST/GraphQL API 且大多数配置都可以通过代码完成
* [Revel](https://github.com/revel/revel) - go语言高生产率框架
* [rex](https://github.com/Goanywhere/rex) - Rex 是一个用于进行模块化开发的库，基于Gorilla/mux 完全兼容大多数的 `net/HTTP`.
* [sawsij](https://github.com/jaybill/sawsij) - 轻量级、开源的 web 框架，用于构建高性能、数据驱动的web应用
* [tanGo](https://github.com/lunny/tanGo) - 微型的、支持插件的 web 框架
* [tigertonic](https://github.com/rcrowley/Go-tigertonic) - 用于构建 JSON web 服务的 Go 语言框架，受到 Dropwizard 的启发
* [traffic](https://github.com/pilu/traffic) - 受到 Sinatra 启发的 Go 语言 web 框架
* [utron](https://github.com/gernest/utron) - 轻量级的go语言 MVC 框架
* [violetear](https://github.com/nbari/violetear) - Go HTTP 路由库
* [YARF](https://github.com/yarf-framework/yarf) - 快速的微型框架，用于快速、简单地构建 REST APIs 以及 web 服务
* [Zerver](https://github.com/cosiner/zerver) - Zerver 是一个富有表达力的、模块化的、全功能的 RESTful 框架.

## Windows

* [d3d9](https://github.com/Gonutz/d3d9) - Direct3D9 的 Go 语言接口
* [Go-ole](https://github.com/Go-ole/Go-ole) - 为 Go 语言实现的 Win32 OLE

## XML

_Libraries and tools for manipulating XML._

* [Go-pkg-xmlx](https://github.com/jteeuwen/Go-pkg-xmlx) - 对 Go 语言 XML 标准库的扩展。维护来一个节点树，允许前进和后退浏览以及一些简单的单／多节点搜索函数
* [XML-Comp](https://github.com/xml-comp/xml-comp) - 简单的命令行 XML 比较工具，可以生成关于目录、文件和标签对差异信息
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML 生成 API 基于 libxml2 的 xmlwriter 模块.
* [xpath](https://github.com/antchfx/xpath) - XPath 库
* [xquery](https://github.com/antchfx/xquery) - XQuery 使你可以从 HTML/XML文档中抽取数据和求值，使用 XPath 表达式

### 中间件

#### 中间件

* [CORS](https://github.com/rs/cors) - 非常方便地向你的 api 中添加 CORS 功能
* [formjson](https://github.com/rs/formjson) - 将 JSON 输入看作说一个标准的表单 POST 来处理
* [Limiter](https://github.com/ulule/limiter) - 超级简单的限速中间件
* [Tollbooth](https://github.com/didip/tollbooth) - HTTP 请求限速中间件
* [XFF](https://github.com/sebest/xff) - 处理 `X-Forwarded-For` 头的中间件

#### 用于创建 HTTP 中间件的库

* [alice](https://github.com/justinas/alice) - 用于连接中间件的库，简单无痛苦
* [catena](https://github.com/codemodus/catena) - HTTP.Handler wrapper catenation (和chain具有相同的 API ).
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [Go-wrap](https://github.com/Go-on/wrap) - 小型中间件库，用于net/HTTP.
* [Gores](https://github.com/alioygur/Gores) - 用于处理 HTML, JSON, XML 等。对于 RESTful APIs 很有用。
* [interpose](https://github.com/carbocation/interpose) - 极简的 net/HTTP 中间件
* [muxchain](https://github.com/stephens2424/muxchain) - 用于net/HTTP的轻量级中间件
* [negroni](https://github.com/urfave/negroni) - 符合语言习惯的 HTTP 中间件库
* [render](https://github.com/unrolled/render) - 用于轻松渲染 JSON, XML, 及 HTML 模板响应的库
* [rye](https://github.com/InVisionApp/rye) - 小型 Go 语言中间件库 ，支持 JWT, CORS, Statsd, 及 Go 1.7 context
* [stats](https://github.com/thoas/stats) - Go 语言中间件，用于存储web应用的多种信息
* [Volatile](https://github.com/volatile/core) - 极简的go语言中间件技术栈，强调灵活性、优秀实践及简洁代码

### 路由

* [alien](https://github.com/gernest/alien) - 轻量级、超快速的 HTTP 路由，来自外星科技
* [Bone](https://github.com/Go-zoo/bone) - 轻量级快速 Fast HTTP Multiplexer.
* [Bxog](https://github.com/clayGod/Bxog) - 为go语言编写的简单快速点 HTTP 路由。能够配合多种不同复杂度、长度和嵌套的路由工作。同时它能够根据接收到的参数创建 URL
* [chi](https://github.com/Go-chi/chi) - 小巧、快速、具有丰富表达力的 HTTP 路由，基于net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - 从`httprouter` fork出来的高性能路由，是第一个适配 `fasthttp`的路由
* [Gocraft/web](https://github.com/Gocraft/web) - Mux 及中间件包
* [Goji](https://github.com/Goji/Goji) - Goji 是一个极简的、灵活的HTTP 请求数据分选器，支持 `net/context`.
* [GoRouter](https://github.com/vardius/Gorouter) - GoRouter 是一个服务器/API 微型框架、HTTP 请求路由 router, 数据分选器，提供了支持`net/context`的中间件
* [Gowww/router](https://github.com/Gowww/router) - 超快的HTTP 路由，完全兼容 net/HTTP.Handler 接口.
* [httprouter](https://github.com/julienschmidt/httprouter) - 高性能路由。使用这个库和标准http处理工具可以构建一个非常高性能大web框架
* [httptreemux](https://github.com/dimfeld/httptreemux) - 高速，灵活，基于树的 HTTP 路由。受到了 httprouter 的启发
* [lars](https://github.com/Go-playground/lars) - 树一个轻量级、快速、可扩展、零分配的HTTP路由，用于创建定制化的框架
* [medeina](https://github.com/imdario/medeina) - Medeina是一个HTTP路由树，基于 HttpRouter 。基于 Roda 和 Cuba.
* [mux](https://github.com/Gorilla/mux) - 强大的 URL 路由和分发库
* [ozzo-routing](https://github.com/Go-ozzo/ozzo-routing) - 一个极快的go语言http路由，支持正则路由匹配。完全支持创建 RESTful APIs.
* [pat](https://github.com/bmizerany/pat) - Sinatra 风格的模式 muxer ，用于go语言 net/http库，由 Sinatra的作者编写。
* [pure](https://github.com/Go-playground/pure) - 是一个轻量级http路由，严格符合标准"net/HTTP"实现
* [Siesta](https://github.com/VividCortex/siesta) - 具有可组合性的框架，用于编写中间件和 handlers
* [vestiGo](https://github.com/husobee/vestiGo) - 高性能、独立的、符合 HTTP 标准的 URL 路由，用于构建go语言web应用
* [xmux](https://github.com/rs/xmux) - 高性能 muxer，基于 `httprouter` ，支持 `net/context`
* [zeus](https://github.com/daryl/zeus) - 非常简单快速的http路由

# 工具

_Go语言软件及插件_

## 代码分析

* [apicompat](https://github.com/bradleyfalzon/apicompat) - 检测一个go语言项目最近的变化，用于监测不能向后兼容的改动
* [dupl](https://github.com/mibk/dupl) - 用于检测重复代码的工具
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck 是一个用于检测go语言程序中未处理错误的程序
* [gcvis](https://github.com/davecheney/gcvis) - 实时地将 Go 语言垃圾回收进行可视化
* [Go Metalinter](https://github.com/alecthomas/Gometalinter) - Metalinter 会自动应用全部的静态分析工具，并生成形式一致的分析报告
* [Go-checkstyle](https://github.com/qiniu/checkstyle) checkstyle是一个代码风格检查工具，类似 java checkstyle 。这个工具就是受到 java checkstyle 和 Golint 的启发
* [Go-cleanarch](https://github.com/roblaszczak/Go-cleanarch) - Go-cleanarch 用于检查代码是否符合简洁架构的相关法则，比如依赖法则以及你的Go语言项目中各个库的交互情况
* [Go-outdated](https://github.com/firstrow/Go-outdated) - 这是一个命令行程序，用于显示过时的库
* [Goast-viewer](https://github.com/yuroyoro/Goast-viewer) - 基于 Web 的 Golang AST 可视化工具.
* [GoCover.io](http://Gocover.io/) - GoCover.io 可以查看任何go语言软件包的代码覆盖率
* [Goimports](https://Godoc.org/Golang.org/x/tools/cmd/Goimports) - 用于自动修复，添加，删除你的 Go 语言项目的 import
* [GoLint](https://github.com/Golang/lint) - Golint 是一个针对 Go 语言源码的 lint 工具
* [Golint online](http://Go-lint.appspot.com/) - 使用golint对GitHub, Bitbucket 以及 Google Project Hosting上面的 Go 语言源文件进行静态分析
* [Goreturns](https://sourcegraph.com/github.com/sqs/Goreturns) - 添加零值 return 语句以符合函数返回值类型
* [Gosimple](https://github.com/dominikh/Go-tools/tree/master/cmd/Gosimple) - Gosimple 是一个针对 Go 语言的lint工具，专注于简化代码
* [Gostatus](https://github.com/shurcooL/Gostatus) - 命令行工具，查看当前 Go 语言软件包仓库的状态
* [interfacer](https://github.com/mvdan/interfacer) - 可以提供接口类型建议的 Lint 工具
* [lint](https://github.com/surullabs/lint) - 将lint作为go语言测试的一部分来执行
* [staticcheck](https://github.com/dominikh/Go-tools/tree/master/cmd/staticcheck) - staticcheck is `Go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [unconvert](https://github.com/mdempsky/unconvert) - 从go语言代码中移除不必要的类型转换
* [unused](https://github.com/dominikh/Go-tools/tree/master/cmd/unused) - unused 会检查 Go 语言代码中没有用到的常量，变量，函数和类型
* [validate](https://github.com/mccoyst/validate) - 自动验证结构体类型

## 编辑器插件

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-Go) - JetBrains IDEs 使用的 Go 语言插件
* [Go-lang-idea-plugin](https://github.com/Go-lang-plugin-org/Go-lang-idea-plugin) (废弃) - IntelliJ (JetBrains) IDEA 之前使用的插件，现在已经被上面的官方插件所取代
* [Go-mode](https://github.com/dominikh/Go-mode.el) - GNU/Emacs的 Go 语言模式
* [Go-plus](https://github.com/joefitzgerald/Go-plus) - 供Atom 使用的自动补全、格式化、语法检查、lint 及 Vetting 的软件包
* [Goclipse](https://github.com/GoClipse/Goclipse) - Eclipse 的 Go 语言插件
* [Gocode](https://github.com/nsf/Gocode) - go语言自动补全
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - SublimeText 2 使用的 Go 语言插件，支持代码补全以及一些类似 IDE 的特性
* [velour](https://github.com/velour/velour) - acme 编辑器使用的 IRC 客户端
* [vim-compiler-Go](https://github.com/rjohnsondev/vim-compiler-Go) - Vim插件，在保存时高亮语法错误
* [vim-Go](https://github.com/fatih/vim-Go) - Vim 使用的 Go 语言开发插件
* [vscode-Go](https://github.com/Microsoft/vscode-Go) - Visual Studio Code (VS Code) 使用的一个扩展，为 Go 语言提供了支持
* [Watch](https://github.com/eaburns/Watch) - 当文件变动时，在 acme 窗口中执行命令

## Go 语言工具

* [colorGo](https://github.com/songgao/colorGo) - 对 `Go` 命令进行了封装，用于为`Go build`的输出结果添加颜色
* [depth](https://github.com/KyleBanks/depth) - 通过分析导入的库，将某个包的依赖关系用树状结构进行显示
* [gb](https://getgb.io/) - 一个简单易用的基于项目的构建工具，用于 Go 语言
* [Go-callvis](https://github.com/TrueFurby/Go-callvis) - 使用 dot 语言将你的 Go 语言程序函数调用关系可视化
* [Go-pkg-complete](https://github.com/skelterjohn/Go-pkg-complete) - Bash 代码补全，用于Go 和 wGo.
* [Go-swagger](https://github.com/Go-swagger/Go-swagger) - 为 Go 语言实现的Swagger 2.0， Swagger 是一个简单但强大的工具，用于展示你的 RESTful API.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用 github 的浏览器插件 OctoLinker 高效浏览 Go 语言文件
* [rts](https://github.com/galeone/rts) - RTS（是response to struct的缩写）用于根据服务器的响应生成 Go 语言结构体

## 软件包

_使用 Go 语言编写的软件_

### DevOps 工具

* [aptly](https://github.com/smira/aptly) - aptly 是一个 Debian 库管理工具
* [aurora](https://github.com/Luxurioust/aurora) - 跨平台、基于web的 Beanstalkd 队列服务器控制台
* [awsenv](https://github.com/soniah/awsenv) - 加载 Amazon (AWS) 环境变量作为 profile 文件
* [Banshee](https://github.com/eleme/banshee) - 异常检测系统，用于周期性数据测量
* [bombardier](https://github.com/codesenberg/bombardier) - 快速的、跨平台的HTTP 基准工具.
* [bosun](https://github.com/bosun-monitor/bosun) - 时间序列告警框架
* [doGo](https://github.com/liudng/doGo) - 监控源文件中的变化并自动编译和执行
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - 触发下游 Jenkins 任务， 可以通过二进制文件、 docker 或者 Drone CI来使用
* [drone-scp](https://github.com/appleboy/drone-scp) - 通过 SSH 拷贝文件及可执行程序,可以通过二进制文件、 docker 或者 Drone CI来使用
* [Dropship](https://github.com/chrismckenzie/dropship) - 通过 cdn 部署代码的工具
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - 一个用于通过 ssh 远程执行命令以及通过`ProxyCommand` 来进行 SCP 下载
* [Gitea](https://github.com/Go-gitea/gitea) - Gogs的fork，完全社区驱动
* [Go Metrics](https://github.com/rcrowley/Go-metrics) - Coda Hale 的 Metrics library的 Go 语言接口: https://github.com/codahale/metrics.
* [Go-selfupdate](https://github.com/sanbornm/Go-selfupdate) - 让你的 Go 语言程序可以自我更新
* [Gobrew](https://github.com/cryptojuice/Gobrew) - Gobrew 让你可以在不同版本的 Go 语言之间轻松切换
* [Godbg](https://github.com/sirnewton01/Godbg) - 基于 Web 的前端 gdb 应用程序
* [Gogs](https://Gogs.io/) - 自我托管的Git服务
* [Gonative](https://github.com/inconshreveable/Gonative) - 为 Go 语言创建可以在多平台进行交叉编译的工具，使用 CGo-enabled 标准库
* [Govvv](https://github.com/ahmetalpbalkan/Govvv) - 对“Go build”进行了封装，用于轻松的向 Go 语言二进制文件中添加版本信息
* [Gox](https://github.com/mitchellh/Gox) - 非常简单的 Go 语言交叉编译工具
* [Goxc](https://github.com/laher/Goxc) - Go 语言构建工具，专注于交叉编译和打包
* [grapes](https://github.com/yaronsumel/grapes) - 一款轻量级工具，用于通过 ssh 发送命令
* [GVM](https://github.com/moovweb/gvm) - GVM 提供了用于管理 Go 语言版本的接口
* [Hey](https://github.com/rakyll/hey) - Hey 是一个微型程序，用于向 web 应用发送一些載荷
* [kala](https://github.com/ajvb/kala) - 极简、现代的、高效的任务调度
* [kubernetes](https://github.com/kubernetes/kubernetes) - 来自 Google 的容器集群管理器
* [Moby](https://github.com/moby/moby) - 为容器生态系统创建的一个合作项目，用于构建基于容器的系统
* [Mora](https://github.com/emicklei/mora) - REST 服务器，用于获取 MonGoDB 文件和元数据
* [ostent](https://github.com/ostrost/ostent) - 收集并显示系统数据，可以作 Graphite 和／或 InfluxDB 的中继
* [Packer](https://github.com/mitchellh/packer) - Packer 通过单一的配置文件，为不同的平台创建独立机器镜像
* [Pewpew](https://github.com/bengadbois/pewpew) - 灵活的 HTTP 命令行压力测试 工具
* [Rodent](https://github.com/alouche/rodent) - Rodent 帮助你管理 Go 语言版本，项目病追踪依赖
* [s3Gof3r](https://github.com/rlmcpherson/s3Gof3r) - 为了从 Amazon S3中高速存取大型对象而特别优化的库
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - 通过命令行来管理 BareMetal 服务器 (和使用 Docker 一样容易).
* [sg](https://github.com/ChristopherRabotin/sg) - 对一组 HTTP 端点 (比如 ab)进行了基准测试， with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [StatusOK](https://github.com/sanathp/statusok) - 监控你的网站和 REST APIs。如果你的服务器挂了或是响应时间超过预期，则会通过 Slack, E-mail 来通知你
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP 加载测试工具和库
* [webhook](https://github.com/adnanh/webhook) - 允许用户创建 HTTP 端点，在服务器上执行命令
* [Wide](https://wide.b3log.org/login) - 基于 Web 的 IDE，为使用 Go 语言的团队设计
* [winrm-cli](https://github.com/masterzen/winrm-cli) - 命令行工具，可以远程在 windows 机器上执行命令

### 其他软件

* [borg](https://github.com/crufter/borg) - 基于终端的搜索引擎，用于搜索 bash 代码 片段
* [boxed](https://github.com/tejo/boxed) - 基于Dropbox 的博客引擎
* [Cherry](https://github.com/rafael-santiaGo/cherry) - Go 语言实现的一个微型网络聊天服务器
* [Circuit](https://github.com/Gocircuit/circuit) - Circuit 是一个可编程的 PaaS 以及 IaaS,用于管理、发现以及编排各种云端应用的服务及主机
* [Comcast](https://github.com/tylertreat/Comcast) - 模拟不佳的网络连接
* [confd](https://github.com/kelseyhightower/confd) - 使用 etcd 或 consul 的模板及数据管理本地应用的配置文件
* [DDNS](https://github.com/skibish/ddns) - 个人 DDNS 客户端，使用 Digital Ocean DNS 作为后端
* [Docker](http://www.docker.com/) - 一个为开发者和系统管理员提供的分布式应用开放平台
* [Documize](https://github.com/documize/community) - 现代维基百科软件，可以继承 SaaS 工具提供的数据
* [fleet](https://github.com/coreos/fleet) - 分布式初始化系统
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store#Go-package-store-) - 一个可以显示你的 GoPATH 路径下 Go 软件包的更新的应用
* [Gocc](https://github.com/Goccmack/Gocc) - Gocc 是一个用 Go 语言编写的 Go 语言编辑器工具集
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - 一个Chrome 浏览器扩展，可以在浏览 Go 语言文档时以工具提示的方式显示函数的描述信息
* [Gogland](https://jetbrains.com/Go) - 跨平台、全功能 Go 语言集成开发环境
* [Gor](https://github.com/buger/Gor) - Http 流量复制工具，用于将生产环境的流量在开发环境实施重现
* [hsync](http://ambrevar.bitbucket.org/hsync/) - 文件系统同步工具
* [huGo](http://GohuGo.io/) - 快速、现代的静态 web 引擎
* [ipe](https://github.com/dimiro1/ipe) - 开源 Pusher 服务器，Go 语言编写，兼容 Pusher 客户端，由 Go 语言编写
* [JayDiff](https://github.com/yazgazan/jaydiff) - Go 语言编写的JSON对比工具
* [Juju](https://jujucharms.com/) - 服务部署及编排工具，，支持 EC2, Azure, Openstack, MAAS 等等
* [Leaps](https://github.com/jeffail/leaps) - 结对编程服务，使用操作变换来避免冲突。
* [limetext](http://limetext.org/) Lime Text 是一个强大又优雅的编辑器，主要使用 Go 语言开发，意在成为 Sublime Text的继承者。
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE 是一个简单、开源、跨平台的 Go 语言 IDE
* [mockingjay](https://github.com/quii/mockingjay-server) - 伪 HTTP 服务器，通过单一配置文件创建消费驱动。同时你还可以让服务器搞点事情，以进行更加符合现实情况的性能测试
* [myLG](https://github.com/mehrdadrad/mylg) - Go 语言编写的命令行网络诊断工具
* [naclpipe](https://github.com/unix4fun/naclpipe) - 简单的基于NaCL EC25519 的加密管道工具
* [nes](https://github.com/fogleman/nes) - Go 语言编写的任天堂娱乐系统(NES)模拟器
* [orange-cat](https://github.com/noraesae/orange-cat) - Go 语言编写的 Markdown 预览工具
* [peg](https://github.com/pointlander/peg) - Peg（Parsing Expression Grammar）是一个 Packrat parser generator 的实现
* [Postman](https://github.com/zachlatta/postman) - 一个批量发送邮件的命令行工具
* [restic](https://github.com/restic/restic) - 解耦备份程序
* [rkt](https://github.com/coreos/rkt) - App 容器运行时，集成了初始化系统，和其他容器兼容，比如 Docker，并且支持其他执行引擎，例如 KVM
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - 快速、简单、可扩展的分布式文件系统，具有O(1)的磁盘查找效率
* [shell2http](https://github.com/msoap/shell2http) - 通过 HTTP 服务器执行 shell 命令行(用于原型验证或远程控制).
* [snap](https://github.com/intelsdi-x/snap) - 强大的遥测框架
* [Stack Up](https://github.com/pressly/sup) - Stack Up 是一个超级简单的开发工具，就好比是服务器网络的 ‘make’ 工具
* [syncthing](https://syncthing.net/) - 开源、去中心化的文件同步工具和协议
* [Tenyks](https://github.com/kyleterry/tenyks) - 面向服务的 IRC 机器人，使用 Redis 和 JSON 来发送消息
* [toto](https://github.com/blogcin/ToTo) - Go 语言编写的简单代理服务器，可以和浏览器一起使用
* [toxiproxy](https://github.com/shopify/toxiproxy) - 模拟网络和系统状态的代理，用于自动化测试
* [tsuru](https://tsuru.io/) - 可扩展的、开源的 SAAS 软件
* [vFlow](https://github.com/VerizonDigital/vflow) - 高性能、可扩展、可靠的 IPFIX, sFlow 和 Netflow 集合.
* [websysd](https://github.com/ian-kent/websysd) - 基于 web 的进程管理工具(类似 Marathon 或 Upstart).
* [wellington](https://github.com/wellington/wellington) - Sass 项目管理工具， 通过支持一些功能（例如Compass）扩展了这门语言

# 资源

_可以找到新的 Go 语言库和软件的地方_

## 基准测试

* [autobench](https://github.com/davecheney/autobench) - 用于比较各个不同版本 Go 语言之间的性能的框架
* [Go-benchmark-app](https://github.com/mrLSD/Go-benchmark-app) - 强大的 HTTP 基准测试工具，集成来 Аb, Wrk, Siege 工具。收集来统计数据以及多种参数用于基准测试和结果比较
* [Go-benchmarks](https://github.com/tylertreat/Go-benchmarks) - 一些基准程序的大杂烩。用于比较一些语言特性以及它们的替代方法.
* [Go-HTTP-routing-benchmark](https://github.com/julienschmidt/Go-HTTP-routing-benchmark) - Go HTTP 请求路由基准和比较
* [Go-type-assertion-benchmark](https://github.com/hgfischer/Go-type-assertion-benchmark) - 对在 Go 语言中使用断言的两种方法进行了性能测试
* [Go-web-framework-benchmark](https://github.com/smallnest/Go-web-framework-benchmark) - Go web 框架基准
* [Go_serialization_benchmarks](https://github.com/alecthomas/Go_serialization_benchmarks) - Go 语言序列化方法基准测试
* [Gocostmodel](https://github.com/PuerkitoBio/Gocostmodel) - Go 语言基础操作基准测试
* [Golang-micro-benchmarks](https://github.com/amscanne/Golang-micro-benchmarks) - 一些go语言微基准测试的集合，目的是比较各种语言特性。
* [Golang-sql-benchmark](https://github.com/tyler-smith/Golang-sql-benchmark) - 对一些流行的 Go database/SQL 工具进行基准测试
* [Gospeed](https://github.com/feyeleanor/GoSpeed) - Go 语言微型基准测试工具，用于测试语言结构的速度
* [kvbench](https://github.com/jimrobinson/kvbench) - 键值数据库基准测试
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M 线程微基准
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - 比较了 Go 语言的多种图片缩放算法

## 会议

* [Capital Go](http://www.capitalGolang.com) - 美国华盛顿
* [dotGo](http://www.dotGo.eu) - 法国巴黎
* [GoCon](http://Gocon.connpass.com/) - 日本东京
* [GolangUK](http://Golanguk.com/) - 英国伦敦
* [GopherChina](http://Gopherchina.org) - 中国上海
* [GopherCon](http://www.Gophercon.com/) - 美国丹佛
* [GopherCon Brazil](https://Gopherconbr.org) - 巴西弗洛里亚诺波利斯
* [GopherCon Dubai](http://www.Gophercon.ae/) - 迪拜
* [GopherCon India](http://www.Gophercon.in/) - 印度普纳
* [GopherCon Singapore](https://Gophercon.sg) - 新加坡丰树商业城
* [GothamGo](http://GothamGo.com/) - 美国纽约

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.Golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-Golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-Go/details)
* [Go Bootcamp](http://Golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - Go 语言书籍列表
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/Go/)
* [The Go Programming Language](http://www.Gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-Golang-anti-textbook/)

## Twitter

* [@Golang](https://twitter.com/Golang)
* [@Golang_news](https://twitter.com/Golang_news)
* [@Golangflow](https://twitter.com/Golangflow)
* [@Golangweekly](https://twitter.com/Golangweekly)

## 网站

* [Awesome Go @LibHunt](https://Go.libhunt.com) - Your Go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - 一个发布远程工作的列表。上面有很多人都在寻找 Go 语言程序员
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - 汇集了其他 Awesome 系列列表的聚合列表
* [Flipboard - Go Magazine](https://flipboard.com/section/the-Golang-magazine-bVP7nS) - 汇集了 Go 语言的教程和文章
* [Go Blog](http://blog.Golang.org) - Go 语言官方博客
* [Go Challenge](http://Golang-challenge.org/) - 通过解题来学习 Go 语言，同时获得专家们的反馈
* [Go Forum](https://forum.Golangbridge.org) - 讨论 Go 的论坛.
* [Go In 5 Minutes](https://www.Goin5minutes.com/) - 5 分钟分享如何做好一件事
* [Go Projects](https://github.com/Golang/Go/wiki/Projects) - Go 语言社区 wiki 列表中的项目
* [Gocryforhelp](https://github.com/ninedraft/Gocryforhelp) - 汇集了一些需要帮助的 Go 语言项目。一个开始你的开源之路的好地方
* [Godoc.org](https://Godoc.org/) - 开源 Go 语言软件包的文档库.
* [Golang Flow](http://Golangflow.io) - 不断更新的博客、新闻、软件等等
* [Golang News](https://Golangnews.com) - 关于 Go 语言编程的一些链接.
* [Golang-graphics](https://github.com/mholt/Golang-graphics) - 关于 Go 语言的图片及艺术作品
* [Golang-nuts](https://groups.Google.com/forum/#!forum/Golang-nuts) - Go 邮件列表
* [Google Plus Community](https://plus.Google.com/communities/114112804251407510571) - Go 语言爱好者的 Google+ 社区
* [Gowalker.org](https://Gowalker.org) - Go 语言项目 API 文档
* [r/Golang](https://www.reddit.com/r/Golang) - Go 语言新闻
* [Trending Go repositories on GitHub today](https://github.com/trending?l=Go) - 一个寻找 Go 语言新库和软件的好地方

### 教程

* [A Tour of Go](http://tour.Golang.org/) - 一个交互式的 Go 语言教程
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-Golang) - Go 语言电子书，讲解如何编写一个 web 应用
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-Go-web-applications-and-microservices-using-gin) - 学习 Gin 以及了解如何使用 Gin 帮你减少模板代码并建立一个请求处理流水线
* [Go By Example](https://Gobyexample.com/) - 通过带注解的例程帮助你动手实践学习 Go 语言
* [Go Cheat Sheet](https://github.com/a8m/Go-lang-cheat-sheet) - Go 参考手册
* [Go database/sql tutorial](http://Go-database-sql.org/) - 介绍数据库及 sql
* [Golangbot](https://Golangbot.com/learn-Golang-series/) - Go 语言初学者教程
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-Godog-for-behavior-driven-development-in-Go) - 学习使用 Godog — 一个行为驱动型开发框架，用于构建和测试 Go 语言应用
* [Working with Go](https://github.com/mkaz/working-with-Go) - 为有经验的程序员提供的 Go 语言教程
