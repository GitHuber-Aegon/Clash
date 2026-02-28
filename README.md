<div align="center">

# 🛠️ Aegon's Clash Configuration

[![Clash](https://img.shields.io/badge/Clash-Premium-blue.svg)](https://github.com/Dreamacro/clash)
[![Rules](https://img.shields.io/badge/Rules-Comprehensive-green.svg)](https://github.com/GitHuber-Aegon/Clash)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](LICENSE)

**一个高度定制化、专业且美观的 Clash 配置文件体系。**
*针对 Windows 及移动端深度优化，内置多项 AI 助手与生产力工具加速规则。*

[快速开始](#-传送门) • [特性介绍](#-主要特性) • [目录结构](#-项目结构) • [鸣谢](#-致谢)

</div>

---

## 🚀 传送门

点击下方链接可跳转至 RAW 文件，或使用右侧代码块一键复制订阅地址：

| 平台版本 | 订阅文件 (点击跳转) | 订阅链接 (手动复制/右键复制) |
| :--- | :--- | :--- |
| **💻 Windows** | [WinSubStoreModel.yaml](https://raw.githubusercontent.com/GitHuber-Aegon/Clash/refs/heads/main/config/WinSubStoreModel.yaml) | `https://raw.githubusercon...` |
| **📱 移动端** | [mSubStoreModel.yaml](https://raw.githubusercontent.com/GitHuber-Aegon/Clash/refs/heads/main/config/mSubStoreModel.yaml) | `https://raw.githubusercon...` |

### 📋 快速复制订阅地址
*点击下方代码块右上角的图标即可一键复制：*

**Windows 版：**
```text
https://raw.githubusercontent.com/GitHuber-Aegon/Clash/refs/heads/main/config/WinSubStoreModel.yaml
```

**移动版：**
```text
https://raw.githubusercontent.com/GitHuber-Aegon/Clash/refs/heads/main/config/mSubStoreModel.yaml
```

---

## ✨ 主要特性

- **🤖 AI 助手优化支持**：内置专为主流 AI 助手优化的规则集，支持进程级拦截与核心域名加速，确保稳定不掉线。
- **🛡️ 模块化规则**：基于 `rule-providers` 划分，包括 AI、社交、游戏（LOL/League）、流媒体等多个专属维度。
- **📊 智能分流**：支持 `url-test` 自动测速、`select` 手动切换，确保延迟最低。
- **🍎 全面覆盖**：深度优化 Apple、Microsoft、GitHub 等生产力工具的网络连接。

---

## 📂 项目结构

```text
.
├── config/                # 核心配置文件 (SubStore 模板)
│   ├── WinSubStoreModel.yaml
│   └── mSubStoreModel.yaml
├── ruleslist/             # 自定义规则集 (.list)
│   ├── Antigravity.list   # AI 增强规则
│   ├── TMS.list
│   └── ...
└── icon/                  # 策略组专用图标
```

---

## 🛠️ 使用说明

1. **获取模板**：下载或直接引用 `WinSubStoreModel.yaml` 作为配置文件模板。
2. **配置订阅**：在 `proxy-providers` 部分，将 `url` 字段替换为您自己的机场或自建节点订阅地址。
3. **加载配置**：在 Clash 客户端中刷新或重新加载配置文件，即可体验预设的自动化分流策略。

---

## 🤝 致谢

感谢以下项目的规则支持：
- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
- [Blackmatrix7](https://github.com/blackmatrix7/ios_rule_script)
- [Qure IconSet](https://github.com/Koolson/Qure)

---

<div align="center">
Made with ❤️ by Aegon
</div>