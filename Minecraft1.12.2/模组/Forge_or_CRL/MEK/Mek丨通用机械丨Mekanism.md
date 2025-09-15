![[Mek丨通用机械丨Mekanism.jpg]]
- 前置：
 [[Forge丨Minecraft Forge]]

![[Mek丨通用机械丨Mekanism.webp]]
_“Mekanism 是一个独立的科技 mod，它为 Minecraft 带来了低级、中级、高级的机械。当你看到 Mekanism 所有的随机的（随意的）项目（从喷气背包到气球），你会觉得这个模组并没有实际的目标。不过，我可以保证，当你将所有的内容混合在一起，你就会更了解这个模组！”_

_——aidancbrady（作者）_

概述

**通用机械（Mekanism）**是独立的科技模组，提供了基础、高级、精英等不同层次的机器添加到 Minecraft 中。模组内添加了矿石处理系统和化学品储运系统，以及一系列的发电设备和各种实用工具，采用 Joule（J，焦耳）为能量单位（在 V10 版本中默认使用 [FE](https://www.mcmod.cn/item/334421.html "Forge Energy") 显示电量）。

注意

**Mek V10** 对应原版 **1.16.X** 及以上的游戏版本；**1.15.2** 及以下对应最新模组版本均为 **Mek V9**。

现 **Mek V10** 已全面更换贴图及 GUI。

**Mek V10** 相比 **Mek V9** 更改了众多物品名称，使用时望请注意。

相关

通用机械在 **1.7.10** 的版本需要 [ForgeMultiPart](https://www.mcmod.cn/class/627.html) 模组作为前置；在 **1.9.4 ~ 1.12.2** 的版本需要 [MCMultiPart](https://www.mcmod.cn/class/685.html) 模组作为前置；在 **1.12.2** 以上的版本不需要前置。

此模组兼容 [[AE2] 应用能源2](https://www.mcmod.cn/class/260.html "Applied Energistics 2")、[[TE] 热力膨胀](https://www.mcmod.cn/class/576.html "Thermal Expansion")、[[IC2] 工业时代2](https://www.mcmod.cn/class/2.html "Industrial Craft 2")，且在游戏后期提供强大的 5 倍产矿能力。

多数物品处理机器都有对应的[工厂](https://www.mcmod.cn/item/447588.html "Factory")方块，工厂分基础、高级、精英、终极（仅限 MC1.15+）四级，分别可以同时处理 3、5、7、9 种物品，而气液处理机器则没有。

曾有一个名为 [通用机械：DZ版](https://www.mcmod.cn/class/1600.html "Mekanica") 的项目，改进了当时已知存在的大部分性能问题。在 **Mekanism 1.12.2-9.7.0.369** 并入官方版本。

能量单位换算

1 [EU](https://www.mcmod.cn/item/303102.html "Energy Unit") = 2 [AE](https://www.mcmod.cn/item/366571.html "AE能量") = 4 [RF](https://www.mcmod.cn/item/311488.html "Redstone Flux") = 10 J = 4 [FE](https://www.mcmod.cn/item/334421.html "Forge Energy")。

有关 GJ、MJ、KJ 等单位属于 Mek 的更高的能量单位如下面的表格：

|             |                          |
| ----------- | ------------------------ |
| 103J = 1kJ  | 10<sup>3</sup>FE = 1kFE  |
| 103kJ = 1MJ | 10<sup>3</sup>kFE = 1MFE |
| 103MJ = 1GJ | 10<sup>3</sup>MFE = 1GFE |
| 103GJ = 1TJ | 10<sup>3</sup>GFE = 1TFE |
| 103TJ = 1PJ | 10<sup>3</sup>TFE = 1PFE |

注：Mek 的 MJ 是 Million Joule，也就是百万焦耳，而 [[BC] 建筑](https://www.mcmod.cn/class/4.html "BuildCraft") 使用的 [MJ](https://www.mcmod.cn/item/673458.html "Minecraft Joule") 是 Minecraft Joule（Minecraft 焦耳），注意不要混淆。

此模组分为四部分

- **[Mek] 通用机械 (Mekanism)** - 本体，即本模组。包含管道、除反应堆和工业涡轮的所有多方块结构、用电机械、蓄电设备、观赏性方块、产生热量的机械。
    
- [[MekG] 通用机械发电机 (Mekanism Generators)](https://www.mcmod.cn/class/1323.html "[MekG] 通用机械发电机 (Mekanism Generators)") - 包含了反应堆和发电机。  
    
- [[MekT] 通用机械工具 (Mekanism Tools)](https://www.mcmod.cn/class/1615.html "[MekT] 通用机械工具 (Mekanism Tools)") - 包含了各种材料的工具、武器、装备。
    
- [[MekA] 通用机械附加 (Mekanism Additions)](https://www.mcmod.cn/class/2437.html "[MekA] 通用机械附加 (Mekanism Additions)") - 在通用机械 1.15+ 版本中，Mek 本体不再带有小型怪物、塑料方块、黑曜石TNT、气球等，而是被转移到这个模组中。
    

MekG ，MekT 与 MekA 为 Mek 官方附属。

部分问题解答

**Mek V9 版本部分物品纹理渲染异常的问题：**  

安装 Mek 后，你会发现有部分物品的纹理不能正常渲染，现已经有人在 GitHub 上汇报了这个漏洞。

**解决方法：**  

在“.minecraft”根目录中打开“config/forge.cfg”文件，把“allowEmissiveItems”选项设为“false”。

也可以在游戏中的主菜单上依次点击“Mods -> Minecraft Forge -> Config-> 客户端设置”，找到“允许物品渲染发光效果”选项，将其设为“false”。

**Mek V10 版本纹理不连接的问题：**

需安装[连接纹理](https://www.mcmod.cn/class/837.html "ConnectedTexturesMod")模组，各种方块才会出现连接纹理。

1.20.1版本可使用 [Fusion (Connected Textures)](https://www.mcmod.cn/class/11194.html "Fusion (Connected Textures)") 与该资源包达成连接纹理的效果。