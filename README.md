# CrossWa Desktop 跨境出海多开获客工作台

[![GitHub release](https://img.shields.io/github/v/release/zhangxiaohu998321-coder/CrossWa-Desktop?color=brightgreen&label=Latest%20Version)](https://github.com/zhangxiaohu998321-coder/CrossWa-Desktop/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2B-blue.svg)](https://github.com/zhangxiaohu998321-coder/CrossWa-Desktop)
[![License](https://img.shields.io/badge/License-Proprietary-orange.svg)](https://github.com/zhangxiaohu998321-coder/CrossWa-Desktop)
[![Telegram](https://img.shields.io/badge/Telegram-%40crosswa-blue?logo=telegram)](https://t.me/crosswa)

CrossWa 是一款专为外贸 B2B、跨境电商及海外本地化运营打造的高性能桌面多开工作台。集成了**独立指纹浏览器隔离**、**双向即时聊天翻译**、**内置轻量智能接待系统**与 **外贸工作流辅助**，帮助出海团队低成本、高效率管理多个海外沟通账号。

---

## 🚀 核心功能特性

- **🛡️ 硬件级指纹隔离**：每个窗口具备独立的 Canvas、WebGL、AudioContext 及字体指纹，搭配独立代理 IP，保障多账号防关联。
- **🌐 双向实时翻译**：支持输入实时双向翻译（中译英、中译西、中译法、中译阿等多语种切换），消除跨国沟通语言障碍。
- **🤖 内置外贸接待与知识库**：
  - 支持本地配置企业人设（persona.md）、产品阶梯价目表（products.md）与常见问答（aq.md）。
  - 支持接入 DeepSeek / OpenAI / 自建大模型 API，自动根据知识库拟人化接待，非业务闲聊自然温和过渡，杜绝机械式冰冷回复。
- **🔌 MCP 智能体生态协议支持**：内置开放的 MCP (Model Context Protocol) 接口，可无缝对接各类海外获客与自动化工具。
- **⚡ 超低资源占用**：针对后台多开深度优化，支持空闲标签自动休眠，低配置电脑也可稳定流畅运行多环境。

---

## 📥 下载安装

请前往 [GitHub Releases](https://github.com/zhangxiaohu998321-coder/CrossWa-Desktop/releases/latest) 页面获取最新安装包：

| 版本类型 | 文件名 | 适用场景 |
| :--- | :--- | :--- |
| **标准安装版 (推荐)** | CrossWa-Setup-v1.3.11.exe | 适合日常使用，自动创建桌面快捷方式，支持一键无缝更新 |
| **便携免安装版** | CrossWa-portable-v1.3.11.exe | 绿色单文件，解压即用，适合放在 U 盘或临时测试环境 |

> **系统要求**：Windows 10 / Windows 11 (64-bit)，建议 4GB 以上内存。

---

## 📖 小白开箱 3 步上手指南

1. **第一步：下载并启动**
   - 下载并运行 CrossWa-Setup-v1.3.11.exe，安装完成后打开桌面上的 **CrossWa** 图标。
2. **第二步：新建环境并配置代理**
   - 点击主界面顶部「**添加环境**」，输入环境名称（如 *客户接待01*）。
   - 在代理设置中填入你的海外 Socks5 / HTTP 代理 IP 并保存。
3. **第三步：登录与智能接待**
   - 点击「**启动**」打开独立指纹窗口，使用海外沟通 App 扫码登录。
   - 打开「**AI 接待设置**」：填入你的 API Key，并编辑你的产品资料与企业介绍，即可开启高效获客！

---

## 🛠️ 常见问题 (FAQ)

<details>
<summary><b>Q1: 杀毒软件提示报毒或拦截怎么办？</b></summary>
由于本软件采用底层 V8 机器字节码编译保护商业逻辑，未经微软商业证书签名的版本可能会被 Windows Defender 提示“未知的发布者”。点击「更多信息」->「仍要运行」即可放心使用。
</details>

<details>
<summary><b>Q2: 为什么提示连接不上大模型？</b></summary>
请检查填写的 API Key 是否有效，以及所在网络是否能直连对应的大模型服务商。推荐使用国内直接可用的服务商（如 DeepSeek）或配置代理。
</details>

<details>
<summary><b>Q3: 更换电脑后，我的多开环境会丢失吗？</b></summary>
每个环境的指纹数据保存在本地系统目录中，你可以使用软件内的「环境导出/导入」功能随时迁移数据到新设备。
</details>

---

## 💬 官方支持与商务咨询

如需商务合作、大客户定制或使用咨询，欢迎通过以下官方渠道联系我们：

- ✈️ **Telegram 频道 / 官方客服**：[@crosswa](https://t.me/crosswa)
- 📧 **商务咨询与合作邮箱**：[crosswa88@gmail.com](mailto:crosswa88@gmail.com)

---

*Copyright © 2026 CrossWa Team. All rights reserved.*
