![[Materialis.jpg]]
- 前置：
 [[TiC2丨匠魂2丨Tinkers' Construct 2]]

**Materialis** 为[匠魂](https://www.mcmod.cn/class/683.html "匠魂")添加了更多的材料，一些由它自己添加，还有一些来源于其他模组。

匠魂2中完全兼容[匠魂盔甲](https://www.mcmod.cn/class/1318.html "匠魂兵工厂")，这代表你可以用本模组添加的几乎所有材料来制作护甲。

匠魂3中暂不支持匠魂盔甲，但与[psi](https://www.mcmod.cn/class/470.html)同时安装时，会添加一套匠魂psi金属盔甲。

所有材料都可以在配置文件中单独禁用。

  

**注意：与**[**匠魂进化**](https://www.mcmod.cn/class/2739.html "TConEvo")**存在小冲突，该冲突会导致崩溃**，版本至少涵盖 materialis-1.12.2-1.2.1 与 tconevo-1.12.2-1.0.38。

原因是两个模组都注册了锡（tin），而本模组没有作自动禁用。

以下提供两个解决方案：

1、（匠魂进化作者在 GitHub 上给出的解决方案）对[匠魂进化](https://www.mcmod.cn/class/2739.html "TConEvo")模组文件的名称作修改（如最前面加 1），使其先于本模组加载（原理是 Forge 的模组按名称顺序加载）

2、在本模组的配置文件中禁用锡的注册