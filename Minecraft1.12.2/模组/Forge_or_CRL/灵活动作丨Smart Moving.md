![[灵活动作丨Smart Moving.jpg]]
- 前置：
 [[玩家API丨Player API]]

- 概述
    
    灵活动作 Mod 是一种能够让玩家自由做出各种跑酷动作的 Mod。
    
    本 Mod 增加了一系列玩家移动的能力，有了它便可以趴下 (穿过 1 格的洞)、游泳、加速跑、超级跳 (需要蓄力)、攀爬等。
    
    本模组还改进了人物游泳、飞行时的动作，使游戏中的角色动作更加自然真实。
    
    Mod 需求 [Player API](https://www.mcmod.cn/class/35.html "玩家API") 才可以正常运作，还有 [Render Player API Enhancer](https://www.mcmod.cn/class/5964.html "Render Player API Enhancer") 作为增强其它模组兼容的可选项。作者表示使用 Render Player API Enhancer 如果出问题后果自负。
    
    有用于原版的文件覆盖版（只做到 1.6.4），ModLoader版（Modloader 就活到 1.6.2）和 Forge 版三种。
    
    制作历史
    
    原作者在更新了 1.8.9 之后不再更新，以至于因为 Minecraft Forum 的变动导致大多数帖子都没了，只有这一个奇迹般的被保留了下来。这之后 JonnyNova，Tommsy64 和 Elveskevtar 先后将 Mod 移植到了 1.10.2 和 1.12.2 上，doch13_ 继续维护 1.12.2，并发布了 灵活动作：重启 (Smart Moving Reboot)。
    
    **注意：由于新版 Forge 对基本 class 编辑作了限制，故 PlayerAPI 1.6.4 之前的部分版本使用了作者自己修改版本的 Forge，这可能导致一些兼容问题以及无法及时更新其他的模组。**
    
      
    
    1.7.10 非官方维护分支：SmartMoving - makamys 版，添加了对更多模组的兼容；以及其前置 PlayerAPI - makamys 版，同样添加了对更多模组的兼容，但该分支还需要使用一个额外的前置 [SmartRender](https://www.mcmod.cn/class/12841.html)。
    
    兼容性
    
    本模组与下列修改了玩家模型的模组以及 [更多玩家模型 (More Player Models)](https://www.mcmod.cn/class/3417.html) 互不兼容，同时安装会导致崩溃或渲染错误。 
    
    - [动画化玩家](https://www.mcmod.cn/class/11650.html "动画化玩家")（Forge 1.6.2-1.7.10）
        
    - [更多弯曲](https://www.mcmod.cn/class/526.html "更多弯曲")（Forge 1.6.2-1.12.2）
        
    
    相似模组
    
    - [更多动画](https://www.mcmod.cn/class/4378.html "更多动画")（Forge & Fabric 1.16.4+）
        
    - [跑酷！](https://www.mcmod.cn/class/5958.html)（Forge 1.16.5+）
        
    
    严重bug
    
    - 不兼容其他模组的盔甲，表现为穿上盔甲后渲染错误。
        
    - 无法正常使用鞘翅。
        
    - 当在服务器内安装时，触发动作会使饥饿值快速清零。