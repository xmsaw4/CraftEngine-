# Slimefun IA → CE 配置迁移包

将 InfinityExpansion、无尽贪婪等主流 Slimefun 附属的 **2400+ 物品** 从 ItemsAdder 完整迁移至 CraftEngine 的配置文件与资源包，开箱即用。

## ✨ 关于本包

本包提供了已经过完整路径修正和冗余清理的：
- CraftEngine 物品配置文件（`configuration/`）
- 分类菜单配置（`categories.yml`）
- 与之匹配的模型与纹理资源包（`resourcepack/`）

**你无需再手动处理路径错误、缺失纹理或模型引用问题，放入对应目录即可直接使用。**

## ⚠️ 重要

- 本包**仅包含配置文件和资源包**，不包含 InfinityExpansion 等附属插件本身。你仍需要自行安装对应的 Slimefun 附属插件。
- 本包假设你已安装 **CraftEngine** 并已配置好命名空间。如果你使用的命名空间不是 `slimefun` 或 `infinityexpansion`，请自行批量替换配置文件中的命名空间前缀。
- 本包中的配置是基于 **Minecraft 1.21.4+** 和 **CraftEngine 0.0.67+** 的新版模型系统编写的。如果你使用的是旧版 CE 或旧版 MC，可能需要进行额外调整。

## 📦 下载

你可以在 [Releases](https://github.com/你的用户名/仓库名/releases) 页面下载最新的打包文件。

## 🚀 使用方式

1. 将 `configuration/` 文件夹中的内容放入 `plugins/CraftEngine/resources/你的命名空间/configuration/`。
2. 将 `resourcepack/` 文件夹中的内容放入 `plugins/CraftEngine/resources/你的命名空间/resourcepack/`。
3. 将 `categories.yml` 放入 `plugins/CraftEngine/resources/你的命名空间/configuration/categories.yml`（或与你现有的分类配置合并）。
4. 在游戏内执行 `/ce reload all`。
5. 执行 `/ce resourcepack build --clean` 重新生成资源包。
6. 执行 `/ce resourcepack send` 推送资源包给玩家。

## 📋 需求

- **Minecraft**：1.21.4 或更高版本（推荐）
- **CraftEngine**：0.0.67.10 或更高版本
- **Slimefun**：任意支持 1.21.4 的版本（官方版或汉化版均可）
- 对应的 **Slimefun 附属插件**（如 InfinityExpansion、无尽贪婪等）

## 🙋 作者

**msaw4**

---

*本包中的所有原始物品设计及模型版权归其各自作者所有。本包仅提供配置文件与资源包的迁移整理工作。*
