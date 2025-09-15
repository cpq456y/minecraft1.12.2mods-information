![[匠魂矿辞缓存丨Tinkers OreDict Cache.jpg]]
- 前置：
 [[TiC2丨匠魂2丨Tinkers' Construct 2]]
 [[MixinBooter]]

匠魂会扫描游戏内所有配方来生成矿辞相关的冶炼炉熔融配方，比如金剑融化成 288 mB 熔融金。然而在大型整合包里，游戏里有成千上万个配方，而匠魂每次游戏加载都要扫描一次，这会消耗大量时间。这个模组缓存了所有矿辞相关的冶炼配方，并阻止匠魂一次次扫描配方。

于大型整合包 e2e-extended 的测试结果
![[匠魂矿辞缓存丨Tinkers OreDict Cache 1.webp]]
![[匠魂矿辞缓存丨Tinkers OreDict Cache 2.webp]]