![[Cleanroom.jpg]]
- 前置：
 [[MC丨我的世界原版丨Minecraft]]

**Cleanroom**

_**由**_ [_**CleanroomMC**_](https://www.mcmod.cn/author/26409.html "CleanroomMC") _**团队基于**_ [_**Minecraft Forge**_](https://www.mcmod.cn/class/30.html "Minecraft Forge") _**1.12.2 制作的模组加载器分支。**_

**Cleanroom** 致力于继续维护 1.12.2 的 Forge 模组社区，类似 GTNH 正在做的那些事情。

**Cleanroom** 的开发将侧重于对 Minecraft 原版以及 Forge 进行漏洞修复与增加功能。

与 Forge 尽量减少 Patch （以便版本迁移）的理念不同，**Cleanroom** 会为了功能而进行大量的覆写与重构。
![[Cleanroom.png]]
📚写在开头

**记得安装** [**Fugue**](https://www.mcmod.cn/class/13259.html "Fugue") **与** [**Scalar**](https://www.mcmod.cn/class/14677.html "Scalar") **！**

若要安装[高清修复](https://www.mcmod.cn/class/36.html "高清修复")_（OptiFine，OF）_请以模组文件形式安装，请勿使用文件覆盖版！

如果遇到了无法解决的疑难杂症请在 GitHub Issues 内上传错误报告或在 Discord 频道中汇报给作者。

关于 [MixinBooter](https://www.mcmod.cn/class/4010.html "MixinBooter") 版本需求问题，可以在 _**config/forge_early.cfg**_ 内 **MIXIN_BOOTER_VERSION** 项修改为需要的版本。

  

📥食用指南

**Cleanroom** 是 Forge 的分支，这意味着你必须将其以加载器（文件覆盖）的方式安装。

更完整的介绍请[点此进入](https://www.mcmod.cn/post/3556.html)。

- 目前建议在 GitHub 的 Releases 页面下载稳定发布版本安装器和MMC 格式包；
    
- 也可以在 Actions 中下载构建版；
    
- 可以使用 [Cleanroom Relauncher](https://www.mcmod.cn/class/18779.html "Cleanroom Relauncher") 模组，将你的 Forge 实例变成 Cleanroom；
    

关于服务端，你可以使用 Installer 快速下载 Forge 端，也可以查看由社区开发者编写的**_实验性_** CatRoom 项目（融合该项目与 Catserver）。

  

🧱项目相关

_**Cleanroom**_ 的开发周期被设置了一个较长的时间阶段，所有开发目标都被分成了三个阶段。

所有内容都被保证在兼容原版 Forge 的情况下进行，但部分修改使得无法 100% 兼容一切第三方模组，请在测试阶段使用 [Fugue](https://www.mcmod.cn/class/13259.html "Fugue") 来保证基本的（当前已发现的不兼容）模组兼容性。

  

🎯项目目标

**CleanroomMC** 认为：  

- Mojang 的新内容已经不值得费力追随；
    
- 1.13+ 的“数据驱动”改动对游戏性能和模组开发弊大于利；
    
- 1.13+ 的游戏底层大改（Blaze3D 渲染库），使得对游戏基础的修改变得困难重重；
    
- Mojang 仍在频繁更新开发工具、破坏性修改底层结构，大大提高了模组移植难度；
    
- Forge 多年来歧视低版本玩家、无视模组移植难度，破坏性修改代码结构；
    
- Forge 多年来不作为，在添加新 API 方面极度保守，以至于开发者人均使用 ASM；
    
- Fabric 盲信 Mixin，在新 API 方面更加保守，造成社群分裂。  
    

**CleanroomMC** 打算：

- 延续早就被社区所遗弃的 1.12.2 Forge；
    
- 使用并兼容新版 Java（Java 21 支持） 、新的前置库；
    
- 对游戏整体进行优化和修补（**CleanroomMC** 成员内有目前 1.12.2 Forge 大部分仍保持活跃开发优化模组的作者）；
    
- 给常见模组内容开发新 API ，降低模组联动难度，并且通过新 API 引导新模组的开发；
    
- 将大部分模组生态吸引到 1.12.2 Forge，新版本有人想为了一个自动合成器便与 Mojang 唇枪舌战，那就随他去。  
    

目前已经实现的特性有：

- 在 Java 21 + LWJGL3 下运行游戏；
    
- 内置 [MixinBooter](https://www.mcmod.cn/class/4010.html "MixinBooter")、[ConfigAnytime](https://www.mcmod.cn/class/11060.html "ConfigAnytime")；
    
- 内置输入法支持（类似 1.13+）与原始输入（类似[Raw Mouse Input](https://www.mcmod.cn/class/8667.html "Raw Mouse Input")）；
    
- 支持多语言排版（即 [WrapFix](https://www.mcmod.cn/class/8443.html "WrapFix")）（注：仍需安装 WrapFix 以修复模组的排版）。
    

未来计划移植高版本[标签](https://www.mcmod.cn/item/492042.html "标签")、Ticket 和世界生成等 1.13+ 特性和部分模组的前置库，详见相关链接中的路线图。

安装器下载位于 GitHub 的 Actions 页面，该页面含有多个分支的安装包，下载前请仔细检查，详细步骤请参阅教程。  

_**Cleanroom**_ 使用了来自 [Lwjgl3ify](https://www.mcmod.cn/class/9103.html "Lwjgl3ify") 的 lwjglx 转换层，并且在开发中得到了其作者 [eigenraven](https://www.mcmod.cn/author/29118.html "eigenraven") 的许多帮助。

更完整的计划表翻译：[发展目标](https://www.mcmod.cn/item/828610.html "发展目标")。

  

🤝关于兼容性

_**Cleanroom**_ 使用 [Fugue](https://www.mcmod.cn/class/13259.html "Fugue") 中的大量兼容 Transformer 以确保与原版 Forge 的兼容性，安装该模组可实现与99%模组的兼容。

对于内置的模组，则无需额外安装，以免与内置部分产生冲突。  

在未来，如果所有冲突的 1.12.2 模组皆得到维护，Fugue将不再需要。  

---

目前 **_foundation_** 分支的兼容性已经足够好，推荐所有用户直接前往 Release 进行下载。

注意，Cleanroom 针对 Scala 运行库进行了**剥离**。如果需要运行 Scala 模组请安装 Scalar。  

  

🆘如何反馈 BUG

1. 首先在常规 Forge 下再运行测试一次，确定问题在 Cleanroom 中才出现；
    
2. 用中文则必须在 Discord 中反馈，用英文则还可使用 GitHub Issue；
    
3. 必须说明复现步骤、附上各种日志、而且要留意是否与现有 Issue 重复；
    
4. 开发者精力有限，不这样做可能会不予理会。  
    

针对部分因特殊原因无法使用 Github 或 Discord 提交问题的，也可通过加入 QQ 群讨论和提交问题。  

_**Cleanroom**_ 1.12.2 的非官方交流 QQ 群：956425376