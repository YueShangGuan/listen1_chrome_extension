Listen 1 (Chrome Extension) V2.12.0
==========
（最后更新于2020年08月241日）

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

[English Version](https://github.com/listen1/listen1_chrome_extension/blob/master/README_EN.md)

重要
----
Listen1的用户，有个坏消息希望和大家分享。Listen1最近收到了[QQ音乐的DMCA Takedown Notice](https://github.com/github/dmca/blob/master/2017/2017-11-17-Listen1.md), 主要代码库已经因为此原因而临时关闭。悲观一点看，Listen1项目可能会在今年内彻底消失。

Listen1诞生的初衷从不是和大公司的争夺版权利益，而是为了给予热爱音乐的人更好的收听体验，所以，Listen1是开源，免费的，并且不接受任何形式的捐助。正是因为有热爱音乐的Listen1的你们，Listen1才发展到今天这一步。不管结果如何，Listen1团队感谢所有支持过这个项目的人们。

在这个关系项目生死存亡的时刻，我寻求项目因为DMCA被github关闭的援助。如果有对这个比较了解如何解决的人，或者你想对这个事情发表看法和建议，可以在[issue](https://github.com/listen1/listen1_chrome_extension/issues/113)留言，或者发送邮件到 githublisten1@gmail.com。我们会尽最大努力，来守护Listen1，即使可能它即将成为历史。

缘起
----
当我发现找个想听的歌因为版权听不了，需要打开好几个网站开始搜索，来回切换让我抓狂的时候，我知道是时候该做点什么了。

妈妈再也不用担心我找不到我想听的歌了。

支持音乐平台
* 网易云音乐
* 虾米
* QQ音乐
* 酷狗音乐
* 酷我音乐
* bilibili
* 咪咕音乐

搜歌，听歌，就用 `Listen1`。

[![imgur](https://i.imgur.com/dIVFtor.gif)]()

V2.9.0 新特性：自动切换播放源(Beta)

当一首歌的播放源不可用时，会自动搜索其他平台，获得可用的播放源。避免了用户手动搜索的麻烦。

还有精选歌单哦。

Chrome安装
----
1. 下载项目的zip文件，在右上方有个 `Download ZIP`, 解压到本地

2. chrome右上角的设置按钮下找到更多工具，打开`扩展程序`

3. 选择 `加载已解压的扩展程序`(如果没有显示先选中`开发者模式`)，选中解压后的文件夹，完成！

Firefox打包安装
-----------
### 打包xpi文件（或在release页面下载已经打包好的xpi文件）
1. 将根目录下manifest_firefox.json替换manifest.json
2. `cd listen1_chrome_extension`
3. `zip -r ../listen1.xpi *`

### 安装
1. 打开Firefox，加载xpi文件，完成安装

更新日志
-------
`2020-08-24`
* 修复虾米歌单歌曲只显示部分歌曲的bug (感谢@RecluseWind的提交)
* 修复歌单图片和标题显示问题 (感谢@RecluseWind的提交)
* 支持桌面版点击链接打开系统默认浏览器

`2020-08-04`
* 增加正在播放窗口和播放列表弹窗的动画效果
* 修复虾米艺人封面图片无法显示的问题 （感谢@RecluseWind的提交）
* 优化打开歌单功能，支持网易云排行榜单，艺人页面，专辑页面网址（感谢@whtiehack的提交）
* 优化专辑图片显示，避免图片被压缩 （感谢@RecluseWind的提交）

`2020-07-10`
* 修复咪咕音乐无法播放的问题
* 支持顶部搜索栏回车触发 （感谢@kangbb的提交）
* 支持歌单歌曲数显示，支持播放/暂停全局快捷键（桌面版）（感谢@x2009again的提交）
* 支持返回时回到滚动条历史位置（感谢@x2009again参与完成）
* 优化firefox滑动条，修改qq音乐图标网址，解决firefox上架jquery代码问题 （感谢@RecluseWind的提交）

`2020-06-29`
* 支持播放失败时自动切换播放源(Beta)

`2020-06-28`
* 修复网易歌单仅显示10首歌曲的问题

`2020-04-30`
* 修复咪咕音质较差的问题

`2020-04-27`
* 增加收藏歌单功能，特别感谢 @zhenyiLiang
* 修复咪咕音乐无法播放的bug
* 一些细节优化

`2019-11-27`
* 加入法语支持, 特别感谢 @Leoche

`2019-09-07`
* 修复migu无法播放的bug

`2019-08-09`
* 增加深色主题

`2019-07-03`
* 修复咪咕音乐无法播放的bug

`2019-06-24`
* 增加咪咕音乐
* 修复网易音乐无法播放的bug
* 修复酷狗音乐无法播放的bug

`2019-06-23`
* 修复无法连接到github的bug

`2019-05-26`
* 修复酷狗音乐无法播放的bug

`2019-04-26`
* 修复虾米音乐无法播放的bug
* 修复播放器未在页面底端显示的bug

`2019-03-03`
* 修复删除单个歌曲导致歌单所有歌曲消失的bug
* 修复删除单个歌单导致所有歌单消失的bug

`2019-02-26`
* 修复qq音乐歌单无法显示的bug

`2018-12-30`
* 修复酷我音乐歌单缺失歌曲的问题
* 自动检测客户端语言

`2018-12-29`
* 修复虾米音乐搜索失败的问题
* 修复部分QQ音乐歌曲无法播放的问题
* 修复使用插件时QQ官方网站无法使用的问题

`2018-12-24`
* 多语言支持，支持英文
* 新添加到歌单的歌曲将出现在歌单头部
* 修复版权通知占满屏幕的bug

`2018-12-22`
* 全新版本2.0发布，更新界面(特别感谢@iparanoid提供主题设计)
* 升级jquery和angular版本

`2018-12-21`
* 修复虾米音乐歌单访问的问题
* 修复网易云音乐歌单只有一首歌的问题
* 修复bilibili滚动时加载重复歌单的问题
* 修复酷狗部分音乐无法播放的问题
* 修复Github Gist备份无法导入的问题
* 升级soundmanager2库到最新版本

`2018-12-05`
* 完全修复虾米音乐歌单访问的问题

`2018-08-25`
* 修复虾米音乐无法播放的bug

`2018-06-15`
* 增加酷我音乐的支持（特别感谢@WinterXMQ的提交) 

`2018-06-10`
* 修复酷狗音乐收藏歌单后可能显示空歌单的bug

`2018-06-10`
* 修复虾米音乐无法显示歌词的bug

`2018-06-05`
* 增加酷狗音乐的支持（感谢@WinterXMQ ) 

`2018-05-30`
* 修复QQ音乐无法播放的问题（感谢@noschoollee 提供修复方案）

`2018-04-23`
* 修复虾米音乐无法播放的问题

`2018-02-18`

* 修复无法创建歌单的bug
* 修复点击关闭歌单按钮后无法再打开歌单的bug
* 增加歌曲主页，点击封面可进入（特别感谢@iparanoid提供歌曲页面UI设计）

`2018-02-15`

* 修复随机播放在播放列表播放结束后自动停止的问题，开启无限洗脑循环（感谢@sunjie21的提交）
* 增加将当前播放列表全部添加到歌单的功能 (感谢@sunjie21的提交)
* 修复标题播放状态不实时更新的bug (感谢@sibojia的提交)

`2018-02-14`

* 修复主页在加载更多数据时出现双重滚动条的bug，并修改了滚动条样式（感谢@zhuzhuyule的提交)
* 修复打开歌单时，网易云音乐个人歌单地址无法解析的bug（感谢@zhuzhuyule的提交)


`2017-12-26`

* 增加同步歌单到Github Gist功能。(特别感谢@ConstLhq提供创意和部分代码实现）


`2017-12-20`

* 增加搜索翻页功能，你可以看到更多的搜索结果了。(感谢@ConstLhq的提交）
* 增加合并歌单功能。可以快速的把其它你创建的歌曲合并到当前的歌单中了。(感谢@Dumeng的提交）

`2017-11-27`

* 修复网易云音乐歌单只显示第一首歌的Bug（感谢[@Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)提供接口实现）

`2017-11-18`

* 修复版权原因无法播放歌曲时自动暂停的问题

`2017-11-17`

* 在我的歌单页面增加“打开歌单”功能，可打开支持网页的歌单链接地址。这样就可以导入你喜欢的歌单了。
* HTTP请求头部的Origin字段设置为正常网址

`2017-10-16`

* 修复QQ音乐歌单翻页显示重复的问题(感谢@Moobusy的提交)

`2017-10-03`

* 修复网易云音乐歌单无法显示的问题(感谢@Moobusy的提交)

`2017-09-14`

* 修复QQ音乐无法播放的bug

`2016-05-27`

* 增加快捷键功能（输入?查看快捷键设置）
* 支持同步播放记录到last.fm
* 增加搜索loading时的图标(感谢@richdho的提交）
* 页面标题增加显示当前播放信息
* 修复了在收藏对话框点击取消出现新建歌单的bug
* 重新组织代码文件夹结构

`2016-05-21`

* 增加歌单分页加载功能(感谢@wild-flame的提交)
* 修复关闭按钮随网页滚动的bug
* 修复点击暂停按钮会重置进度条和歌词的bug
* 修复点击歌单名称不跳转的bug
* 调整歌单水平位置居中

`2016-05-14`

* 增加firefox插件支持（感谢fulesdle的提交）

`2016-05-13`

* 增加我的歌单功能，可以收藏现有歌单，并创建自己的歌单
* 点击Listen 1和图标可以回到首页
* 标记了部分因版权无法播放的歌曲,增加版权提示
* 重构了音乐平台代码，使用统一的接口规范
* 重构了歌单接口，合并歌手，专辑和歌单接口
* 修复了阿里云歌手链接点击错误的bug


`2016-05-08`

* 增加歌词显示
* 精选歌单：添加歌单到当前播放列表，可点击跳转到原始链接
* 修复了搜索qq音乐时的乱码问题
* 修复了循环播放网易歌曲一段时间后暂停的bug
* 修复了可能导致微信公众号无法登录的bug
* 优化性能，删除了不必要的事件消息触发

`2016-05-02`

* 增加音量控制


License
--------
MIT
