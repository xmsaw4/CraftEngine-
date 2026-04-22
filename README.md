# Slimefun IA → CE 配置迁移包

将 InfinityExpansion、无尽贪婪等主流 Slimefun 附属的 **2400+ 等物品** 从 ItemsAdder 完整迁移至 CraftEngine 的配置文件与资源包。

## ✨ 关于本包

1. 本材质包的模型文件以及纹理文件完全匹配items.yml里的路径。
2. 本材质包的物品配置文件的custom-model-data完全匹配slimefun粘液插件配置的item-models
3. 粘液的所有材质CE物品菜单配置文件路径 CraftEngine\resources\slimefun\configuration\slimefun\categories.yml (可根据需求删除或添加 一般不建议改动)
4. 部分冗余纹理或未使用的模型文件进行了清理，减少材质包大小的占用。
5. 修复了少部分材质的路径和模型问题。

**基本无需再手动处理路径错误、缺失纹理或模型引用问题，放入对应CE目录即可**

## ⚠️ 重要

- 本包**仅包含配置文件和资源包**，不包含 InfinityExpansion 等附属插件本身。。
- 本包假设你已安装 **CraftEngine** 并已在resources配置好命名空间。如果你使用的命名空间不是 `slimefun` 否则请手动更改。
- 本包中的配置是基于 **Minecraft 1.21.4** 游戏版本 和 **CraftEngine 0.0.67+** 版本的插件编写的 理论上兼容1.20.1至最新游戏版本。

## 📦 下载

你可以在 [Releases](https://github.com/你的用户名/仓库名/releases) 页面下载最新的打包文件。

## 🚀 使用方式

1. 将压缩包解压后将slimefun文件夹(包含configuration、resourcepack、pack.yml) 复制到 plugins\CraftEngine\resources 文件夹下即可。
2. 先执行 `/ce clean-cache all` 清理未使用的custom-model-data的物品，建议输入，避免和粘液材质的custom-model-data值冲突。
4. 在游戏内执行 `/ce reload all` 即可自动发包给玩家加载材质 若未自动发送材质包请前往CE的WIKI查看修改config配置。

## 📋 需求

- **Minecraft**：1.21.4（推荐） 或1.20.x-最新游戏版本
- **CraftEngine**：0.0.67 或更高版本 插件传送门：https://modrinth.com/plugin/craftengine 插件wiki：https://ce.gtemc.cn/zh-Hans/
- **Slimefun**：粘液本体 前置库等最新附属插件
- 对应的 **Slimefun 附属插件**（如 InfinityExpansion 等）需要可前往鬼斩构建站下载粘液插件附属(https://builds.guizhanss.com/)

## 🙋 作者

**msaw4**
熊猫
目前在 缘落之梦 服务器担任技术 主流玩法粘液空岛
欢迎大家前来游玩 Q群：859957646
---

*本包中的所有原始物品设计及模型版权归其各自作者所有。本包仅提供配置文件与资源包的迁移整理工作。*
