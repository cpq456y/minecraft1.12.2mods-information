![[OF丨高清修复丨OptiFine.jpg]]
- 前置：
 [[MC丨我的世界原版丨Minecraft]]

**注：本模组任何问题反馈应在** **https://github.com/sp614x/optifine/issues** **进行提交。**

概述

增加更多更精细的画质以及效果设置，改善原版画质和流畅度，并且增加高清纹理和自定义模型支持的模组。

同时也是低配玩家的福音，部分版本（1.12.2 及以前）能够显著改善 FPS。

一些增强画质类的模组，和自定义实体或物品模型和纹理的资源包也要求先安装此基础模组才能正常使用。

功能特性

- 让你使用高分辨率的纹理包（Minecraft 1.5.2 及更早的版本，远古版本不支持，后来支持了但有 bug，在 1.6 纹理文件拆分之后就不再存在这种问题了）；
    
- 光影支持（具体到 2015 年 8 月 29 日起发布的后续版本，基于 Karyonix 的 [ShadersMod](https://www.mcmod.cn/class/2321.html) ）；  
    
- 抗锯齿优化（Mipmap）；
    
- 可选平滑光照程度；
    
- 为中低配设备优化 FPS；
    
- 随机生物（有些纹理包中内置同一生物的不同贴图）；
    
- 开启/关闭动画与粒子效果；
    
- 连接纹理（比如无缝玻璃，不同方块之间的衔接）；
    
- 在视距为 2 区块时也显示天体（太阳、月亮等）；
    
- 自定义云、草地、雪地的效果；
    
- 最高渲染距离调整为 64 区块（原版最高渲染距离根据设备性能而变化）；
    
- 动态光源，可以进入_视频设置_里设置为启用（具体到 2016 年 6 月 6 日起发布的版本的新增功能）；
    
- 更多效果可以在_视频设置_中找到；  
    
- 披风原来是Optifine特有功能，后来mojang官方也开始用了可以在高清修复官网购买“OptiFine”披风；
    
- 每年 4 月 8 日使主菜单的闪烁标语会变成“Happy birthday, OptiFine!”或“Happy birthday, sp614x”。
![[OF丨高清修复丨OptiFine.webp]]
兼容性

由于 OptiFine 对核心渲染器的修改较大，在使用其它视觉效果和渲染优化的模组时请提前查询。

  

原版

光影功能和 1.16 新增加的“极佳”画质不兼容，且“快速渲染”功能在开启后会影响一定的视觉体验，如拥有发光效果的实体可能会显示为一片纯白（整个实体呈现为全白而不是描边）；

如果使用超出 3 级的水下呼吸且安装了高清修复，那么有可能会不停报错 OpenGL Error: 1821。

模组

高清修复的光影会导致 [模拟殖民地](https://www.mcmod.cn/class/682.html "模拟殖民地") 的部分方块渲染错误，但不影响游玩；

部分光影会导致 [WorldEdit CUI](https://www.mcmod.cn/class/612.html) 和 [Litematica](https://www.mcmod.cn/class/2261.html) 的选区渲染出现错误或失效；

[维克的现代战争](https://www.mcmod.cn/class/595.html) 的枪械会在光影的渲染下发生各种恶性 Bug，例如枪口火焰故障、换弹动作故障等等，极大的影响了手感及体验，但是维克的现代战争的绝大多数物品渲染需要高清修复；

同时使用 [星辉魔法](https://www.mcmod.cn/class/639.html "星辉魔法") 与光影会导致图形问题。星辉魔法会使用自己的天空渲染器，使得晚上的星星能够闪烁，玩家发现的星座也会出现在天上。它的天空渲染会与光影冲突。处理方法请前往[星辉魔法](https://www.mcmod.cn/class/639.html "星辉魔法")页面查看；

和 [Cracker 的凋灵风暴](https://www.mcmod.cn/class/6410.html "Cracker的凋灵风暴") 一起使用会导致第四阶段前的凋灵风暴在距离玩家过远（此距离会随能见度正相关变化，16 能见度时距离约为 1000格）时不被渲染且无法进化，第四阶段及之后的凋灵风暴无影响。这个特性曾坑了我半年

  

  

各版本的额外问题

在 1.7.10 中，与 Forge 同时安装可能会导致存档无法保存计分板命令（/scoreboard）相关数据。来源于此 MCBBS 帖子 (已失效) 和 此MinecraftForum 帖子，具体模组版本和 Forge 版本不明，可能与其它模组有冲突，或为旧版 Forge 本身的 Bug。  

在 1.16.X 中，高清修复与版本相对低的 [Xaero 的小地图](https://www.mcmod.cn/class/1701.html "Xaero的小地图") 存在严重冲突，即任何 GUI 包括其中的物品都无法显示，解决方法是提升 Xaero 的小地图的版本（推荐最新）。

在 1.16.X 中，如果同时安装[暮色森林](https://www.mcmod.cn/class/61.html "暮色森林")与高清修复，将导致渲染错误，如娜迦只有头部会被渲染，身体会凭空消失大号战利品，好耶！，但不影响碰撞箱，因而仍然可以攻击到。

在 1.17.1 及以上版本，暮色森林放弃兼容高清修复，检测到高清修复后会警告，但可能无法点击继续进入到游戏画面。唯一解决方法是点击继续后按下ESC键。

在 1.18.2 中，如果同时安装 Forge 40.1.68～40.1.59 创建世界时发生崩溃，请使用 Forge 40.1.57 及以下版本或 Forge 40.1.73，或升级 OptiFine 至 H9 pre1 版本。

  

版本支持

高清修复自身可以以库的形式被载入 Minecraft 启动，基本上从该模组诞生起就没有间断过 Minecraft 版本的支持，但仅有主流的大版本高清修复会持续更新下去。

高清修复本身不支持快照版和愚人节版，但可以在快照版和愚人节版安装特殊版本：[OptiKai](https://www.mcmod.cn/class/15226.html "OptiKai")。

Forge

1.12.2 及之前版本一般与任意 Forge 版本兼容。如果遇到问题请尝试单独安装在模组文件夹，而不是在启动器内同时选中 Forge 一键安装。

[Minecraft Forge](https://www.mcmod.cn/class/30.html) 在 1.13 时期的变动致使 Forge 不兼容高清修复，直到 1.14.4 开始 Forge 和高清修复冲突的问题才被解决。在这期间 [Rift](https://www.mcmod.cn/class/1262.html "Rift - MC百科_最大的Minecraft中文MOD百科") 可以与高清修复互相并存并兼容。

1.14.4 之后高清修复建议使用特定 Forge 版本，具体兼容版本请在官网查看。

1.18 Forge 版本中安装高清修复需要双击打开进行安装，直接放入 mods 文件夹无法加载。

高清修复与任何 钠 的 Forge 移植版（如 [Embeddium](https://www.mcmod.cn/class/12028.html "Embeddium")、铷等）冲突。若使用此类模组请使用 [Oculus](https://www.mcmod.cn/class/5741.html "Oculus") 加载光影。

Fabric

如果想在 [Fabric](https://www.mcmod.cn/class/1411.html "Fabric - MC百科_最大的Minecraft中文MOD百科") 环境下使用高清修复，需要安装 [OptiFabric](https://www.mcmod.cn/class/1703.html "OptiFabric - MC百科_最大的Minecraft中文MOD百科") 作为前置。  

在 [Legacy Fabric](https://www.mcmod.cn/class/3391.html) 环境下与高清修复并存需要 [OptiLegacy](https://www.mcmod.cn/class/3390.html) (1.7.2-1.12.2，已停更) 或 [OptiFabric Legacy](https://www.mcmod.cn/class/13069.html "OptiFabric Legacy") (1.3.2-1.13.2) 作为前置。  

在远古版本 Beta 1.7.3 的 [Babric](https://www.mcmod.cn/class/6367.html "Babric") 环境下需要使用 [OptiBabric](https://www.mcmod.cn/class/17058.html "OptiBabric")。

高清修复与 [锂（Lithium）](https://www.mcmod.cn/class/2292.html) 、[钠（Sodium）](https://www.mcmod.cn/class/2785.html) 及 [Canvas 渲染器](https://www.mcmod.cn/class/2862.html "Canvas渲染器") 冲突。若使用钠请使用 [Iris Shaders](https://www.mcmod.cn/class/3697.html) 加载光影。

下载

获取最新的版本信息及下载适用于各游戏版本的高清修复，请至官网下载 https://www.optifine.net/downloads 。