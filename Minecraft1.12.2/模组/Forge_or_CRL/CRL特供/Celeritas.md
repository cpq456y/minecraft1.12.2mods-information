![[Celeritas.jpg]]
- 前置：
 [[Cleanroom]]

- 概述
    
    Celeritas 是一款自由且开源的 Minecraft 客户端性能与光影模组。
    
    它基于 [Embeddium](https://www.mcmod.cn/class/12028.html "Embeddium")（源自 [Sodium](https://www.mcmod.cn/class/2785.html "Sodium") 最后一个采用自由且开源许可证的版本）与 [Oculus](https://www.mcmod.cn/class/5741.html "Oculus") 1.7 分叉而来。
    
    作者出于个人使用与实验目的维护这个模组，并将源代码开放给那些可能对此感兴趣的项目及它们的开发者。
    
    注意事项
    
    - 作者无法保证持续维护，包括漏洞修复或移植到更新的 Minecraft 版本；
        
    - 源代码仍采用 LGPL-3.0 许可，因此任何兼容项目（包括 Embeddium）均可自由采纳其中的修复与功能；
        
    - **由于测试有限，预计兼容性较差，且可能存在诸多 Bug**；
        
    - 没有官方二进制 Release，如果你从任何第三方渠道下载预编译的 JAR 文件，作者将无法提供支持，风险自负；
        
    - 唯一官方发布渠道为官方源代码仓库：TauMC 。
        
    
    项目结构
    
    Celeritas 采用 Stonecutter 工具链，以减轻对每个游戏版本的单独支持工作量。
    
    此外，尽可能多的核心渲染代码被完全抽象到 :common 项目中，与 Minecraft 核心解耦。
    
    该通用模块已发布至 Maven，下游项目可直接引用，无需重新完整构建源码。但正式的模组 JAR 文件并未上传到 Maven。
    
    如何构建
    
    详见此处：TauMC。
    
    如何使用
    
    在较旧版的 Minecraft（1.12 及更早）上，Celeritas 需要一个“现代化”的运行环境，**无法直接在默认的整合包中开箱即用**。
    
    较新版的 Minecraft（1.13+）已自带所需依赖，无需额外配置。
    
    旧版（1.13 版本以下）
    
    游戏实例必须提供 LWJGL 3，部分情况还需 Java 21。
    
    目前仅有以下两种整合环境可直接满足要求：
    
    - Forge 1.7.10（配合 [LWJGL3ify](https://www.mcmod.cn/class/9103.html "lwjgl3ify")）；
        
    - Forge 1.12.2（配合 LWJGL3ify 或 [Cleanroom Loader](https://www.mcmod.cn/class/9689.html "Cleanroom Loader")）；
        
    
    其余版本暂无现成的启动器模板。
    
    Ornithe 版本（1.7 版本以下）
    
    [Ornithe](https://www.mcmod.cn/class/17451.html "Ornithe") 版本为早期实验性测试版，仅在开发环境测试过，生产环境未验证。
    
    现代版（1.13+）
    
    直接把编译好的模组 JAR 文件放入对应版本的标准实例即可运行。通常不需要 Java 17/21，除非该版本 Minecraft 本身强制要求。
    
    许可证
    
    Celeritas 采用 GNU Lesser General Public License v3 开源，因仅使用了 [Oculus](https://www.mcmod.cn/class/5741.html "Oculus") 1.7、[Sodium](https://www.mcmod.cn/class/2785.html "Sodium") 0.5.11 及更早版本以及其他自由且开源项目的源代码。
    
    部分选项界面代码基于 [FlashyReese](https://www.mcmod.cn/author/24108.html "FlashyReese") 的 [Reese's Sodium Options](https://www.mcmod.cn/class/4905.html "Reese's Sodium Options") 项目，使用 MIT 许可证，详见  src/main/resources/licenses/rso.txt。
    
    本项目不包含也不计划包含 Sodium 0.6+ 或 0.5.12+ 的任何代码，因这些版本不再以自由且开源的许可证发布。
    
    如对代码许可有疑问，请在 Discord 联系 @embeddedt。
    
    致谢
    
    - [CaffeineMC](https://www.mcmod.cn/author/26827.html "CaffeineMC") 团队：开发并开源 Sodium 0.5.11 及更早版本；
        
    - CelestialAbyss：设计 Embeddium 图标（本项目仅重新配色），input-Here 提供视觉优化；
        
    - [Ven（@basdxz）](https://www.mcmod.cn/author/28955.html)、[XFactHD](https://www.mcmod.cn/author/26434.html "XFactHD")、[Pepper](https://www.mcmod.cn/author/24384.html "Pepper") 以及任何作者的朋友：提供代码见解或提供宝贵的建议；
        
    - ...
        
    
    关于非官方构建版
    
    - 从 Release 中下载；
        
    - **未基于标签构建，风险较高，使用后果自负**；
        
    - 严禁使用文件名为 -dev-dev.jar  与  -dev-remapped-thin.jar 的版本。