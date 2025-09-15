![[Forge.jpg]]
- 前置：
 [[MC丨我的世界原版丨Minecraft]]

下一个 Forge?

现在出现了一个 Forge 的分支项目 [NeoForge](https://www.mcmod.cn/class/11433.html "NeoForge") ，原 Forge 开发组几乎所有成员都加入了持有该项目的组织 [NeoForged](https://www.mcmod.cn/author/30165.html "NeoForged") 。

而原 Forge，也就是本资料对应的 Minecraft Forge 的开发也随即放缓。

鉴于 NeoForge 的开发人员基本就是 Forge 开发组的原班人马，而 NeoForge 的一次会议记录也表示其会在 1.20.1 保持与 Forge 的兼容性。但 1.20.2 及以上 NeoForge 完全独立，不与 Forge 兼容。所以基本可以认为 NeoForge 就是 Forge 的下一个形态。

Minecraft Forge

目前 Minecraft 的主流 API，目前有半数以上的模组都在使用 Forge，以易于与 Minecraft Java Edition 的驳接。

一般情况下 Forge 的更新速度很快，一般在 Minecraft 正式版本发布后的一天内更新，偶尔有出现因为一些测试需求在 Minecraft 快照发布后更新的（出现过适用于特定快照版本的 FML）。

Forge 是一个版本支持度极高的 API，从远古版本到最新版本均有支持。

运行任何带有 Forge 的 Minecraft 时，在主界面点击“Mods...”按钮均可显示正在运行的模组，其中 Minecraft、Minecraft Forge、Forge Mod Loader（FML）和 Mod Code Pack（MCP）都是 Forge 的核心模组（旧版没有 Minecraft，新版没有 FML 和 MCP），必定默认出现在模组列表。

功能

为开发模组提供 API

ModLoader 的基本要求，理所当然。

目前，在各大模组加载器中，就体量而言，Forge 提供了最为完整，最为全面的 API 。

矿物/液体辞典

Forge 允许使用了同一个辞典的不同物品/流体互相通用，比如各大科技模组提供的锡锭。

不过，随着 Mojang 在 Minecraft 1.13 引入了[标签（Tag）](https://www.mcmod.cn/item/492042.html "标签 (Tag)")，Forge 放弃了矿物辞典，改为使用原版的标签提供同样的功能。

跨版本兼容

Forge 允许版本较旧的模组兼容版本更新的 Minecraft 及 Forge ，但是，通常仅限于小版本，比如 1.8.8 与 1.8.9。

这不是新功能，而是在 Minecraft 1.5 的 Forge 就出现的功能。

在 Minecraft 和 Forge 的新旧区别不大时，Forge 会对较旧版本模组进行兼容。

此功能有许多较典型例子，如[建筑（BuildCraft）](https://www.mcmod.cn/class/4.html)模组的 Minecraft 1.5 版本可通过 Forge 兼容功能使其可在 Minecraft 1.5.2 版本上运行。

更多功能

更详细的功能介绍和说明可以访问其官方网站查询。

备注

Minecraft Forge 对 Java 的兼容性由于其开发时长非常久远和甲骨文对新版本所做出的改动导致了 Java 8 成为了 1.16.5 及之前最合适 Minecraft Forge 的万金油版本，又因为 Java 8 去除了 PermGen 的存在的缘故，更适合一些没有自定义启动代码的老启动器用 Java 8 来启动老版本的大型整合避免出现 PermGen 分配内存不足所导致的崩溃。

后来 Minecraft 在 1.13 等版本经历多次底层代码大改后， Forge 开发团队决定重写 Forge，一是为了摆脱旧代码的各种历史遗留问题，二是确保对新版 Java 的兼容性；又随着最新版 Minecraft 需求新版本 Java 的缘故，现在的最新版 Forge 已经兼容 Java 17+ 。  

在 Forge 官网点击 Installer 由于国内无法流畅观看广告而无法下载，可以点击 Show all Versions 然后在对应版本下点击 Installer 后面带“i”字眼的小圆点，点击“(Direct Download)”来进行下载。

1.7.10 及之前，客户端**必须安装** Forge 才能加入 Forge 服务端。由于 [SpongeForge](https://www.mcmod.cn/class/1459.html "SpongeForge") 的出现，Forge 在 1.8 取消了此限制，原版客户端也可以连接没有客户端需装模组的 Forge 服务端。