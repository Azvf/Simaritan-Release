# Simaritan

> 把《模拟人生 4》的 Mods、家庭、地段和穿搭整理成自己看得懂、随时能切换的内容方案。

[下载 Windows 版](https://github.com/Azvf/Simaritan-Release/releases) · [5 分钟快速开始](docs/UserGuide/快速开始.md) · [完整使用流程](docs/UserGuide/完整关键链路.md) · [全部模块教程](docs/UserGuide/README.md)

![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)

如果你的 Mods 文件夹已经大到“知道自己下载过，但完全找不到”，Simaritan 就是用来解决这件事的。它会读取你真实拥有的游戏内容，帮你预览、搜索、分类和组合；你可以为不同存档、审美或玩法准备不同的 **蓝图**，需要时一键切换。

## 下载时选哪个文件

1. 打开 [Releases](https://github.com/Azvf/Simaritan-Release/releases)，选择要安装的版本。
2. 展开 **Assets**，下载文件名以 `_x64-setup.exe` 结尾的 Windows 安装包。
3. `.sig`、`latest.json`、`SHA256SUMS.txt` 和 artifact identity 是自动更新与发布校验使用的文件，普通安装不需要手动下载。
4. Alpha/Beta 是测试版本，可能出现功能不完整或更新不稳定；想要更省心时请选择 Stable。

不要下载 GitHub 自动生成的 **Source code (zip/tar.gz)**，它不是可安装的软件。

## 第一次用，选一条最适合你的路线

| 你现在想做什么 | 从这里开始 |
|---|---|
| 我刚下载安装，不知道先点哪里 | [5 分钟快速开始](docs/UserGuide/快速开始.md) |
| 我想从导入资源一直做到进游戏 | [完整关键链路](docs/UserGuide/完整关键链路.md) |
| 我只想学 Tray、Mods 或衣橱 | [按模块学习](docs/UserGuide/README.md#按模块学习) |
| 我遇到路径、权限或加载问题 | [设置教程](docs/UserGuide/modules/设置.md) |

## 它能帮你做什么

- **蓝图：**把一套家庭、地段、穿搭、家具和常驻模组组合成一次游戏方案。
- **Tray：**用预览图浏览家庭、地段和房间，导出时自动带上已解析的依赖 Mod。
- **Mods：**按发型、服装、妆容、家具、灯具等分类搜索，不再盲翻文件夹。
- **衣橱：**把 CAS 内容整理成 Capsule，例如“秋日咖啡店店员”或“复古千禧辣妹”。
- **地段：**把建造/购买内容整理成 Set，例如“奶油风卧室”或“海边小屋家具”。
- **系统模组：**让脚本和玩法模组在所有蓝图中保持启用。
- **导入与暂存区：**先预览别人分享的 Tray/Mod 资源，再决定哪些正式收入资料库。
- **任务：**导出、导入和优化在后台运行，不用盯着界面等。

## 开始前请记住 4 件事

1. 切换或激活蓝图前，先退出《模拟人生 4》。
2. 第一次启用蓝图时，确认 **设置** 中显示的是你真正使用的 Sims 4 用户数据文件夹。
3. 蓝图需要 Windows 开发者模式或管理员权限来创建文件夹链接；看到系统授权窗口时按提示确认。
4. 启用蓝图后，不要手动搬动 Simaritan 管理的 Library 或 `VirtualWorkspaces` 文件夹。

## 更新、问题与源代码

- Stable、Beta 和 Alpha 的自动更新清单保存在 [`channels/`](channels/)；普通用户不需要手动修改。
- 遇到问题时，在 Simaritan 中打开 **设置 → 应用 → 导出调试日志**，生成经过脱敏的诊断 ZIP。
- 问题反馈与源代码位于 [Azvf/SimsToolkit](https://github.com/Azvf/SimsToolkit)。
