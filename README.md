<div align="center">

# BetterAddon

### 面向 Zotero 的模型配置、插件与 CSL 引用样式工作流工具集

[![Release](https://img.shields.io/github/v/release/bobstpeeters177-spec/betteraddon?color=success&label=release)](https://github.com/bobstpeeters177-spec/betteraddon/releases/latest)
[![Zotero](https://img.shields.io/badge/Zotero-7--10-CC2936?logo=zotero&logoColor=white)](https://www.zotero.org/)
[![Download](https://img.shields.io/badge/下载-XPI-2563eb)](https://github.com/bobstpeeters177-spec/betteraddon/releases/latest)

</div>

---

## 关于 BetterAddon

BetterAddon 是一款 Zotero 扩展，用于集中管理常用科研工作流。当前版本提供模型配置、Zotero 插件目录与 CSL 引用样式管理等能力，并以独立的 BetterAddon 安装和更新身份发布。

## 主要功能

| 功能 | 说明 |
|---|---|
| 模型配置 | 浏览、比较并管理模型及服务配置 |
| 插件管理 | 浏览 Zotero 插件目录，查看安装与更新状态 |
| CSL 样式 | 搜索、预览并安装 CSL 引用样式 |
| 数据集工作流 | 管理工作区中的数据集与相关操作 |
| 通知与记录 | 集中查看通知、用量和订单记录 |

> 部分在线功能需要连接对应服务；实际可用范围以插件界面显示为准。

## 安装

1. 前往 [Releases](https://github.com/bobstpeeters177-spec/betteraddon/releases/latest) 下载最新版 `better-addon-*-release.xpi`。
2. 打开 Zotero，进入 **工具 → 插件**。
3. 点击右上角齿轮，选择 **Install Add-on From File / 从文件安装插件**。
4. 选择下载的 XPI 文件，并按提示完成安装。

兼容范围：Zotero 7–10。

## 自动更新

正式版通过本仓库的 GitHub Release 检查更新：

```text
https://github.com/bobstpeeters177-spec/betteraddon/releases/latest/download/update.json
```

`update.json` 包含固定版本下载地址和 SHA-256 校验值。请只从本仓库 Release 页面下载正式包，不要安装来源不明的重打包版本。

## 发布安全

- Release XPI 使用项目的正式发布构建与 WASM 身份校验。
- 发布前执行类型检查、单元测试、scaffold 验证和 package smoke 测试。
- 客户端插件无法做到绝对不可解包或不可逆向；发布保护的目标是校验官方身份、降低篡改风险并提高分析成本。

## 问题反馈

如果遇到安装、启动或更新问题，请在 [Issues](https://github.com/bobstpeeters177-spec/betteraddon/issues) 提交反馈，并附上：

- Zotero 版本与操作系统
- BetterAddon 版本
- 可复现步骤
- 错误信息或截图（请先移除账号、令牌等敏感信息）

## 下载

前往 [Latest Release](https://github.com/bobstpeeters177-spec/betteraddon/releases/latest) 获取最新版 BetterAddon。

---

Copyright © 2026 BetterAddon. All rights reserved.
