![[光影前向兼容丨AdvancedShader.jpg]]
- 前置
 [[Forge丨Minecraft Forge]]
 [[OF丨高清修复丨OptiFine]]

光影前向兼容AdvancedShader

模组作者：一只猫。  

“有欲望而无行动者滋生瘟疫。”作者引用这句话的意思是他为了能在 1.12.2 用上光影自学了做 Mod 哦。希望大家向他学习呢x

这是一个很简单的模组，只是让你能在这里使用 Minecraft 1.16.5+ 光影，仅此而已。

**由于作者身体原因，本模组不再进行维护与更新。如有BUG，凑合用吧~**

使用方法

- 在 1.12.2 安装 Forge 和 OptiFineG5 版本，再往 mods 文件夹添加本模组；  
    
- 在光影选择界面右侧自由切换 1.12.2 或 1.16.5 的**渲染机制**、**方块 ID**、**氛围值机制；**
    
- 选择你想使用的 1.16.5+ 光影。  
    

功能

支持特性

- 计算着色器与 colorimg、 shadowcolorimg；
    
- RenderTargets 注释和 colortex8-15；
    
- Prepare 预处理着色器和 ShadowComp 阴影后处理着色器；
    
- RenderStage 渲染阶段 Uniform 变量；
    
- 1.17+ 的 Core Profile（不支持alphaTestRef）；
    
- at_midBlock 顶点属性；
    
- gbuffers_line 线段着色器；
    
- 8 bits 与 16 bits 的整数型纹理格式；
    
- 100 个后处理着色器（#6530，嗯……无力吐槽）；
    
- 阴影阶段渲染地形、实体、实体方块配置；
    
- size.buffer.<buffer> 配置和 blend.<program>.<buffer> 配置。
    

不支持特性

- at_velocity 顶点属性；
    
- 阴影视裁框剔除。
    

其它修改

- 增加渲染机制、方块 ID、氛围值机制选项用以模拟高版本特性；
    
- 支持识别 in 顶点属性；
    
- 支持同时开启光影与各向异性过滤；
    
- shaders.properties 增加对光影选项宏的支持；
    
- 修复 block.properties 无法正常匹配方块状态问题；
    
- 增加 biome_category 与 biome_precipitation 用于自定义 Uniform；
    
- cameraPosition 更改为实际相机位置；
    
- 兼容 Aperture 模组；  
    
- 修复宏状态机的 bug。  
    

注意事项

如果有奇奇怪怪的渲染问题请尝试将渲染机制在 1.12.2 和 1.16.5 之间反复横跳

如果草方块像摇曳鳗一样晃起来了的话请将方块 ID 设为 1.16.5

如果你想知道什么时候会被游戏的惊悚声音吓一跳的话请将氛围值机制设为 1.16.5并打开F3

致谢

在作者最孤单时陪伴作者的朋友：ネムロイ、阳炘（没有他们就没有这个模组）。  

内测参与者： Surisen（内测的神，几乎所有严重Bug都是这位发现的）、ExDragine（宣发支持）、GeForceLegend（Bug提交者）、villa_qi（Bug提交者）、EpsilonSatoshi、少修、奥维利亚two。