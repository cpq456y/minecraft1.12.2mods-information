![[BC丨建筑丨BuildCraft.jpg]]
- 前置：
 [[Forge丨Minecraft Forge]]

![[BC丨建筑丨BuildCraft.webp]]
概述

**建筑（BuildCraft****）**是一个历史悠久的物流向模组。它添加了大量自动化相关的机器，可以帮助玩家搭建自动化工厂；同时它还拥有一系列管道，配合加入的逻辑门控制系统，可用于运输物品、液体和能量；此外还有一套自动建筑建造系统，方便玩家根据蓝图快速搭建各种建筑；在 6.1.1 版本中它引入了全新的机器人系统，可胜任更为复杂的自动化任务。

*本段内容仅限 1.7.10，1.12.2 缺失部分内容将在之后不断完善。

分包内容简介

**模组文件名中包含“all”字样的为组合版即含有全部模块，若只需特定功能则可单独下载指定模块****，以下为不同模块的介绍：**

- Core 核心模块，包括[扳手](https://www.mcmod.cn/item/526.html)，[齿轮](https://www.mcmod.cn/item/521.html)和引擎，以及其它模块所需要的基础性物品。游玩时总是需要此模块；
    
- Builders 建筑师模块，包括[建筑工作台](https://www.mcmod.cn/item/37504.html)，[建筑机](https://www.mcmod.cn/item/512.html)，[填充机](https://www.mcmod.cn/item/511.html)和其它一些建筑有关的物品；
    
- Energy 能源模块，包括了原油和各种燃料，以及[斯特林引擎](https://www.mcmod.cn/item/501.html)和[燃油引擎](https://www.mcmod.cn/item/502.html)；
    
- Factory 工厂模块，包括[液泵](https://www.mcmod.cn/item/30719.html)，[储罐](https://www.mcmod.cn/item/504.html)，[矿井](https://www.mcmod.cn/item/506.html)，[自动合成台](https://www.mcmod.cn/item/30718.html)等自动化设备；
    
- Transport 运输模块，包括了各类管道；
    
- Silicon 模块，包括[逻辑门](https://www.mcmod.cn/item/540.html)，[镭射](https://www.mcmod.cn/item/517.html)系统和镭射装置，以制作更高级的物品；
    
- Robotics 模块，包括[机器人](https://www.mcmod.cn/item/8577.html)；
    
- Compact 模块（[建筑兼容 Mod](https://www.mcmod.cn/class/496.html)），添加了包括[养蜂员管道](https://www.mcmod.cn/item/36223.html)，[装配台](https://www.mcmod.cn/item/516.html "装配台")合成表配方*以及与其他模组的兼容性。
    
- Lib 模块，支持库可作为其他模组的依赖，其包含于 Core 模块重复添加会导致冲突**。  
    

* 在 7.99.20 之前其未包含在组合版中需要单独安装，若未安装则会缺失部分装配台合成表配方。

** API 模块虽然也在 Core 模块中，但重复添加并不会导致冲突。

  

历史沿革与社区影响

能量系统

建筑模组是最初引入能量单位“Minecraft 焦耳”（_Minec__raft Joule_ 即  "MJ"）的模组，当时它所有的机器和管道都以 MJ 作为能量单位。但由于历史原因，自 6.1.2（MC 1.7.10）起，建筑模组换用时下流行的[红石通量](https://www.mcmod.cn/item/311488.html "红石通量")（_Redstone Flux_  即 "RF"）作为其能量单位。在 7.99.x（MC 1.11.2 & 1.12.2）后，建筑模组经历大规模改动，绝大多数代码被重写并以 MPLv2 开源许可证重新授权，在此过程中 MJ-API 也在重写后被重新启用，MJ 再次成为建筑模组所使用的能量单位。

物流系统

在流体方面，建筑模组率先引入“毫桶”（_m__illiBucket_ 即 "mB"）的流体单位，并由各类模组 API 沿用至今，使几乎所有模组均支持该流体系统。物流方面，建筑模组率先引入“管道”作为物流模式，这种模式在后来的社区中不断被推广，逐渐形成如今以管道为主的各类物流模组。

  

活跃情况

在 8.0.0 更新公告中对未来 BC 的版本号做出了新的安排，原 7.99.x 版本（MC1.12.2） 全部划归 8.0.x，1.19.4 将使用 9.x 作为版本号，而 1.16.5 1.18.2 和 1.20.1版本对应 BC 的版本号则会是 8.1.x、8.2.x 和 8.3.x。建筑模组在 8.0.x 后已经重新使用 MJ-API，并新增 BC 手册、水凝胶等物品。此外，模组还大改了炼油系统、门控操作系统以及引擎工作逻辑，大大提升玩家生活质量与游戏趣味。虽然机器人（即 Robotics 模块）内容与自动建筑（即 Builders 模块）至今仍未重置完成，且其它游戏内容或多或少存在 Bug，但是这仍不能阻挡这一远古模组重新焕发的生机。MJ-API  正在不断地修正改进，目前仅有少量模组支持直接使用 MJ。林业（[Forestry](https://www.mcmod.cn/class/5.html "FR站内链接。")）自 5.8.2.311 起兼容。而铁路模组（[Railcraft](https://www.mcmod.cn/class/6.html "RC站内链接。")）12.1.0（12.1.0-BETA）也重新加入了产生 MJ 的蒸汽引擎。

推荐版本  

目前 8.0.x 版本虽然还有部分 Bug 与缺失功能*，但其是正在开发的活跃版本。若想要游玩缺失的内容（如机器人等），可以使用 7.1（MC 1.7.10）版本。自 7.99.20 起组合版 BC 已包含 Compact 模块（[建筑兼容 Mod](https://www.mcmod.cn/class/496.html)）无需单独下载。

*Builders 模块中，蓝图相关机器未移植完整，存在各种未知 Bug，因此合成表被移除。如果急需使用，可通过 CraftTweaker 一类的模组自行添加配方。而 Robotics 模块则完全没有完成。

非官方版本

- [BC Remastered](https://www.mcmod.cn/class/15763.html)， 将 BC 7.1（对应 1.7.10）移植到 1.12.2（不包含 8.0.x 的新增内容），添加了部分不同于官方版的内容；但机器人模块以及[建筑机](https://www.mcmod.cn/item/512.html "建筑机")和[填充机](https://www.mcmod.cn/item/511.html "填充机")一类的功能仍未完成。
    
- CalenXwX/BuildCraft，将 BC 8.0.x（对应 1.12.2）移植到 1.16.5、1.18.2 和 1.20.1。**包含完整的机器人模块**，其是从 BC 7.2.x（对应 1.8.9）移植而来的。
    
- CurativeTree/BuildCraft，将 BC 8.0.x（对应 1.12.2）移植到 1.19.2。
    

官方路线图

***_此部分内容最后更新于 2023 年 6 月 14 日，部分信息已经失去时效性_**。

在官网上的 路线图（Roadmap）中，BC 在 1.12.2 以上版本的维护者 AlexIIL 指出 BC8[原文如此，但在 2025 年 4 月版本号规则更新后则是 BC9，本段后将都采用新的命名规则] 将伴随第一个 MJ 更新测试版发布于 1.20+ Quilt 环境。他还指出，将来的第一个测试版将包括 Core，Energy，Factory，Transport， Silicon 模块和 "搬运"，"储罐" 机器人（Robotics 模块并不完善，且 Builders 不在这个测试版本涵括的范围内）。在 2022 年的 8 月 1 日，AlexIIL 表示 Core 和 Silicon 模块基本都已移植完，Energy，Transport，Factory 模块还有部分内容需要移植；在 2023 年的 6 月 14 日，AlexIIL 表示他需要找到一种能在不剧透的前提下展示他已完成的进展的方式。因此，可以推断 BC9 的主体结构已经成型，相信在不久的将来 BC9 就能在 Quilt 上与诸位玩家见面。

AlexIIL称 BC9 将不会出现在任何早于 1.20 的版本上，1.20 前的 BC9 开发版本已经被跳过且不被支持。

值得注意的是，BC9 将使用一套较为独立的流体处理与物品处理API，由同作者的 [LibBlockAttributes](https://www.mcmod.cn/class/3744.html) 提供。此外，小方块（Multipart）功能将由同作者的另一个模组 LibMultiPart 提供。使用这两个 API 的模组将与 BC9 取得完美兼容，但是使用其它 API 乃至 Fabric 自身的物流 API 的模组将无法与 BC 机器进行直接交互。当然，BC 管道仍然可以与这些模组的机器进行连接用以提取或输入物品，进而实现与 BC 机器的交互。