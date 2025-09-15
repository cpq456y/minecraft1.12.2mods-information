![[MixinBooter.jpg]]
- 前置：
 [[Forge丨Minecraft Forge]]

概述

从 [CensoredASM](https://www.mcmod.cn/class/3848.html) 2.3 开始起，需要 MixinBooter 作为前置。

  

**模组简介：**

使得任何 Mixin 的构建使用在 1.8 - 1.12.2 上也能轻松自如。

目前包括的 Mixin 版本为 UniMix 0.15.3 的 CleanroomMC 分支，基于 (LegacyModdingMC 的 0.8.7 分支)，与 [UniMixins](https://www.mcmod.cn/class/9457.html) 基本相同。

包括的 [MixinExtras](https://www.mcmod.cn/class/12750.html "MixinExtra") 版本是 0.5.0-beta5。

  

**对于开发者：**

你需要添加 [CleanroomMC](https://www.mcmod.cn/author/26409.html "Cleanroom - CleanroomMC / cleanroommc / cleanroom-mc") 的仓库并依赖 MixinBooter。如果使用了这个，则不需要再一次compile Mixin了

- - 从 4.2 开始，API 发生改变，所有使用 Mixin 的模组都推荐使用 MixinBooter，甚至包括那些混入原版 / Forge / 运行库的类的模组，为了避免 Mixin 版本不匹配与尝试实现修改后的 Mixin 的模组发生崩溃（_看看你 [原版修复](https://www.mcmod.cn/class/1223.html "原版修复")_）；
        
    - 从 5.0 开始，包括了 LlamaLad7 的 MixinExtras ，更方便开发者使用；
        
    - 从 8.0 开始，现已支持 1.8 - 1.12.2 的所有版本；
        
    - 从 8.4 开始，试图与 [SpongeForge](https://www.mcmod.cn/class/1459.html "[SF] 海绵端插件支持 Forge 版 (SpongeForge)") 兼容（仅支持 1.12.2）；
        
    - 从 9.2 开始，将 MixinLoader 注解重新启用，以便在 1.8.X 使用（因为 1.8.X Forge 还未收集类实现接口的信息）；
        
    - 从 10.0 开始，开始使用更新的 Mixin 版本 0.8.7；
        
    - 对于原版、Forge 或任何很早传递给 ClassLoader 的类（例如 Guava），请查看 IEarlyMixinLoader 和 IFMLLoadingPlugin；
        
    - 对于第三方模组的 Mixin 使用，请查看 ILateMixinLoader；
        
    - @MixinLoader 注解从的功能与 LateMixinLoader 类似，两者可以同时使用，特别是当模组需要支持 1.8.X 时。
        
    
    实际上你只需要实现MixinBooter的接口并且传递好信息就万事大吉了，比从coremod手动引导方便太多了
    
    注意
    
    该模组可能与以库形式安装的 [LiteLoader](https://www.mcmod.cn/class/610.html "LiteLoader") （**如****部分启动器的一键安装选项**）冲突导致启动失败，请尝试**仅安装 Forge 并将单独下载的 LiteLoader 安装在 mods 文件夹**，更多兼容信息请参考 LiteLoader 词条的模组兼容部分。  
    
    本模组可能与 ESSENTIAL 冲突 （GitHub Issue），**请升级 ESSENTIAL 版本至 1.3.2.6 以上**。
    
    10.0 版本及以上可能与部分使用 Mixin 的模组存在兼容性问题，且仅 10.3 和 10.4 兼容 1.8.X，若更新后无法启动暂时回退到 9.4 版本即可。