![[Scalar.jpg]]
- 前置：
 [[Cleanroom]]（Forge下不会影响启动）

简介

Scalar 是 [Cleanroom](https://www.mcmod.cn/class/9689.html "Cleanroom") 的 Scala 语言提供器程序，它为运行时和编译时提供独立的 Scala 2.11 和 Scala 3 库。

是的，你可以在 1.12.2 中使用 Scala 3.4.x + Java 21 进行开发。  

Scalar 有两个版本：2.11.1 和 3.x：

- 2.11.1 适用于 1.12 Forge 的旧 Scala 开发的 Mod；
    
- 3.x 适用于标记为 Cleanroom 兼容的 Mod。 
    

以及 OpenComputer Scala 3 移植即将推出。

  

常问问题：

- 问：什么是 [Cleanroom](https://www.mcmod.cn/class/9689.html "Cleanroom") ？
    
- 答：Cleanroom 是 1.12.2 Forge 的一个分支，为开发者提供版本更新的工具链以及 API，并同时保有与 Forge 99% 的兼容性。我们的计划是让开发者能够在 1.12.2 版本与使用最新的工具链，并为 Forge 和原版添加更多功能，以此吸引更多开发者回到 1.12.2，让开发者不仅能够享受各种新 API 与特性，还无需再与高版本的“X 个发布版本 * Y 模组 API”的维护问题而头疼。
    
- 问：Cleanroom 如何安装？
    
- 答：请按照[说明](https://www.mcmod.cn/post/3556.html)中的说明进行操作。
    
- 问：我可以将 Scalar 放入我的 Forge 整合包中吗？它会让我的 Forge 包崩溃吗？
    
- 答：可以，并且你无需担心会引发崩溃问题，因为该模组不会在 Forge 环境中加载。
    
- 问：Java 版本？
    
- 答：21 或 22，我们计划支持使用最新的 LTS 版本 Java 进行开发，并使用最新的 Java 运行。
    
- 问：目前状态？
    
- 答：Cleanroom 目前与市面上的整合包兼容性良好，像 Tekkit 2 这样的轻量型整合包可以与 [Fugue](https://www.mcmod.cn/class/13259.html "Fugue") 一起开箱即用，而像 [E2E-E](https://www.mcmod.cn/modpack/428.html "E2EE") 和 Mystics Monstrosity 这样的巨量型整合包在经过一些兼容性调整后也可以运行。但我们缺少人手，如果你愿意提供帮助，请加入我们的 Discord 。
    

注意：模组文件在 CurseForge 上标记为“Forge”平台，因为 CurseForge 尚不支持 Cleanroom。