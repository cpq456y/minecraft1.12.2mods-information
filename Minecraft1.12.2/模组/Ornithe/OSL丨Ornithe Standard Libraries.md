![[OSL丨Ornithe Standard Libraries.jpg]]
- 前置：
 [[Ornithe]]

概述

Ornithe Standard Libraries（简称 OSL）提供了用于开发的 Ornithe 工具：  

- **Core API：**提供了其他模块使用的通用实用程序，如事件系统和注册表；
    
- **Branding Patch：**利用 16w05a 及以下版本中的 Mod 加载程序信息修改标题屏幕以模拟您在 16w05b 及以上版本中看到的内容。这是通过解析 option.versionType 的运行参数来完成的；
    
- **Config API：**提供了一个用于构建和存储 Mod 配置的框架；
    
- **Entrypoints API：**允许 Mod 开发者提交在游戏初始化之前调用入口点；
    
- **Lifecycle Events API：**跟踪 MC 客户端和服务器（生物）生命周期的事件；
    
- **Networking API：**为客户端 & 服务器通信提供了一个框架；
    
- **Resource Loader API：**允许 Mod 将自己的资源加载到游戏中。