![[LL丨LiteLoader.jpg]]
- 前置：
 [[MC丨我的世界原版丨Minecraft]]

介绍

**本项目已停更。**

专门针对客户端的轻量 Mod API。

  

使用 LiteLoader 加载模组，既能享受各种模组的方便快捷，又保留了原版 Minecraft **极快**的启动速度。（注：LiteLoader 会重新加载一遍资源，导致和大型整合包一起运行时游戏很慢）适合于小地图、[聊天泡泡](https://www.mcmod.cn/class/976.html "聊天泡泡")、HUD 等各种辅助模组。（LiteLoader 作者及著名地图模组 [VoxelMap](https://www.mcmod.cn/class/981.html "VoxelMap") 作者原话）

既可以直接安装于原版之上，像 [Forge](https://www.mcmod.cn/class/30.html "Forge") 那样独立加载模组，也可以作为 Mod 在 Forge 下工作， 基本与 Forge 完美兼容。

  

LiteLoader 源码可见，但是根据许可它并不是开源软件，也不允许他人贡献代码。  

注意

1. 稳定的 LiteLoader 绝对不会和稳定的 Forge 有冲突，除非将 Forge 比较新的版本和 LiteLoader 比较老的版本（本段来源未知，如果出问题请将两个模组加载器均升级到最新版本）放在一起（1.12 有段时间 Forge 改动弄坏了 LiteLoader 兼容）；
    
2. LiteLoader 只能加载文件后缀为 litemod 的模组，Forge 的模组的文件修改后缀后 LiteLoader 无法检测，机制不同；
    
3. LiteLoader 不是不可以做大型模组，只是常用来做辅助模组，因为接口比较少；同时一般不会有什么大型模组专门针对客户端；
    
4. LiteLoader 绝对无毒，除非你不是从官网下；
    
5. LiteLoader 一般更新比 Forge 更快，但是最近 Mumfrey 潜水，所以可能 LiteLoader 1.13 会出得晚点；
    
6. LiteLoader 有中文翻译；
    
7. LiteLoader 有的模组会跟 Forge 有的模组联动；
    
8. LiteLoader 已停止更新，终结于 1.12.2，在更高版本请采用其他 ModLoader 和 API（[Rift](https://www.mcmod.cn/class/1262.html) 1.13 ~ 1.13.2（已停更)，[Forge](https://www.mcmod.cn/class/30.html)，[Fabric](https://www.mcmod.cn/class/1411.html) 1.14+，[Quilt](https://www.mcmod.cn/class/3901.html) 1.14+，[NeoForge](https://www.mcmod.cn/class/11433.html "NeoForge") 1.20.1+）。
    

模组兼容

1.8.9 及以上的 LiteLoader 使用 Mixin，但 LiteLoader 自带的 Mixin 版本过旧，会导致其它使用 Mixin 的模组失效或游戏崩溃。

有一些方法可以在 1.8.9 及以上 Forge 且拥有多个使用 Mixin 的模组的环境下（如 1.12.2 的贪婪整合包）正常使用 Liteloader：

1. **确认 LiteLoader 单独安装在 mods 文件夹，而不是在启动器内同时选中 Forge 一键安装。**
    
2. **不要使用** [**MixinBootstrap**](https://www.mcmod.cn/class/2364.html) 模组，它所包含的 Mixin 可能导致兼容问题。
    
3. 有时**可以尝试下载使用** [**兼容 Mixin 0.7-0.8 (Mixin 0.7-0.8 Compatibility)**](https://www.mcmod.cn/class/3951.html "兼容Mixin0.7-0.8 (Mixin 0.7-0.8 Compatibility)") **模组。**
    
4. 如不使用 ESSENTIAL，**可尝试下载使用** [**MixinBooter**](https://www.mcmod.cn/class/4010.html) **模组。它的名字前面有“!”，能保证新版本的 Mixin 被 Forge 优先加载。**  
    
5. 如果同时使用 ESSENTIAL 时游戏启动失败，1.8.9 请尝试编辑 版本.json 文件里 "name": "org.ow2.asm:asm-all:5.0.3" 这一行把 5.0.3 改成 5.2 并补全文件；1.12.2 则不需要 MixinBooter，直接在 ESSENTIAl 的文件名前面添加“!”，以确保被 Forge 优先加载。  
    
6. 1.12.2 不兼容 Forge 版的 [体素地图 (VoxelMap)](https://www.mcmod.cn/class/981.html)，请使用 litemod 版的体素地图。
    
7. 1.12.2 使用 [LiteLoader 修复（Extra Foam For LiteLoader）](https://www.mcmod.cn/class/1780.html)可解决与 [JEI 物品管理器](https://www.mcmod.cn/class/459.html) 等模组冲突崩溃问题。  
    
8. 将需要的 litemod 文件放入 mods 文件夹，即可开始正常游戏愉快的玩耍啦！