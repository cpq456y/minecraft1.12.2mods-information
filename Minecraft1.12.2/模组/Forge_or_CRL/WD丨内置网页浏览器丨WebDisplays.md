![[WD丨内置网页浏览器丨WebDisplays.jpg]]
- 前置：
 [[MCEF丨Minecraft Chromium丨嵌入式框架]]

简介

一个功能非常惊艳的内置的网页浏览器模组。  

使用方法

1. 将网页显示屏方块摆放为 2x2 - 16x16 的墙以组成显示屏。
    
2. Shift + 右击输入 URL 链接，显示屏便会显示对应的网页。
    
3. 用手来代替鼠标来点击网页用激光笔进行精准定位。
    
4. 使用键盘上来输入文字吧~玩家行走于键盘上时还有十分逼真的音效
    

WebDisplays 1.0（支持 1.10.2、1.12.2）可在官网下载，而支持 1.10.2 以前版本游戏的 WebDisplays 需前往 MinecraftForum （下载链接已失效）下载。

安装需求

|**游戏版本**|[**Forge版本**](https://www.mcmod.cn/class/592.html)|[**Minecraft Chromium Embedded Framework[MCEF]**](https://www.mcmod.cn/class/592.html "Minecraft Chromium Embedded Framework") **版本（必须）**|
|---|---|---|
|1.12.2|14.23.2.2611 及以上|0.9 或更新版本|
|1.10.2|12.18.3.2185 及以上|0.9 或更新版本|
|1.7.10|-|0.6|
|1.7.2|-|0.2|
|1.6.4|-|0.2|
|1.6.2|-|-|

对于非 Windows 系统用户

目前非 Windows 系统并不支持网页显示功能。但是安装该模组可以让玩家加入安装了此模组的服务器。

只需要将 JAR 格式的模组文件丢进 mods 文件夹即可，无需安装 MCEF。

针对服务器

只需要将 JAR 格式的模组文件丢进服务器 mods 文件夹即可，无需安装 MCEF。

关于不能使用 Flash 的问题

**Flash 有严重的安全问题！**

目前 1.12.2 关闭了 Flash 但仍可以通过修改配置文件启用。

操作方法

1. 从这里（链接已失效）下载干净的老版本 Flash；
    
2. **（** **注：29 版本开始 Flash 被国内流氓公司从 Adobe 手里买走，他们没有优化源代码的能力，只掺杂恶心人的私货**连证书都懒得改**）；**
    
3. 完全断网运行安装包，**安装完毕后去服务禁用 Flash Helper Service**，然后恢复网络；
    
4. 在 .minecraft 目录下找到 config 文件夹，打开 mcef.cfg；
    
5. 将 S:cefArgs=--disable-gpu 替换为 S:cefArgs=--disable-gpu -enable-system-flash；
    
6. 保存 mcef.cfg，启动游戏，Mod 会自动调用本机 Flash。
    

WebDisplays分支传送门

|                                                                                     |                                       |          |          |
| ----------------------------------------------------------------------------------- | ------------------------------------- | -------- | -------- |
| **名称**                                                                              | **支持的(Neo)Forge版本**                   | **维护状态** | **类型**   |
| **[WD]内置网页浏览器 WebDisplays（本模组）**                                                    | **Forge1.12.2~1.6.2**                 | **停更**   | **官方**   |
| [**[WD]内置网页浏览器 WebDisplays**](https://www.mcmod.cn/class/8643.html)**（推荐，不需要额外配置）** | **Forge1.20.2~1.18.2，NeoForge1.20.1** | **半弃坑**  | **授权分支** |
| [**DBlockbusterDisplays**](https://www.mcmod.cn/class/15811.html)**(作者已删库跑路)**      | **Forge1.20.1**                       |          |          |