# GitHub 恶意代码与安全扫描器（Agent Skills）

Detect malware, suspicious scripts, cookie stealing, and sensitive data leaks in agent skill packages and GitHub repositories.

用于检测 **Agent Skills / GitHub 仓库中的潜在恶意行为与安全风险**，在运行前快速分析不可信代码。

---

## 🔄 Language

* [English](#github-malware--security-scanner-for-agent-skills)
* [中文](#github-恶意代码与安全扫描器agent-skills)

---

## 🚀 功能特性

* 🔍 检测可疑脚本（JavaScript / Python / Shell）
* 🍪 识别 Cookie / Token 窃取行为
* 📦 扫描压缩包（.zip）与混合文件结构
* 🕵️ 检测隐藏命令与持久化机制
* ⚠️ 标记高风险操作（系统访问 / 环境变量泄露 / 网络请求）
* 🧠 专为 **Agent Skills / AI 工作流安全** 设计

---

## ⚡ 为什么要做这个

很多人把 Agent Skills 当作“无害组件”：

> 复制 → 粘贴 → 运行

但实际上它们是**可执行代码**，可能访问：

* 本地文件
* 环境变量（API Key / Token）
* 系统信息
* 外部网络

这会带来真实风险：

* 数据泄露（Cookie / Token / 用户信息）
* 工作流中的隐蔽后门
* 静默执行恶意代码

本项目的目标是：

👉 在运行之前，**快速发现潜在风险**

---

## 📦 支持扫描内容

* 单文件脚本（`.js` / `.py` / `.sh` 等）
* 压缩包（`.zip`）
* GitHub 仓库
* Agent Skill 包

---

## 🛠️ 使用方法

```bash
git clone https://github.com/szyszy070524/detection
cd detection

# 示例
# python main.py <path>
```

---

## 🧪 示例检测能力

* 可疑网络请求（数据外传）
* 读取 Cookie / 本地存储
* 访问系统 / 环境信息
* 隐藏 shell 执行
* 混淆或编码后的恶意逻辑

---

## 🤝 参与贡献

这是一个早期项目，欢迎一起完善：

* 增加检测规则
* 分享恶意模式
* 提高检测准确率
* 扩展语言支持

---

## 🌍 愿景

我们认为：

> 安全应该是 Agent 生态的一部分，而不是事后补救

随着 AI 工作流增长：

👉 **盲目信任代码会成为巨大风险**

本项目希望推动：

* 更安全的 skill 共享
* 更透明的代码行为分析
* 社区驱动的安全标准

---

## ⭐ 支持一下

如果你觉得这个项目有帮助，欢迎点个 Star ⭐
这会帮助更多人发现它。

---

## 📜 License

MIT

---

# GitHub Malware & Security Scanner for Agent Skills

Detect malware, suspicious scripts, cookie stealing, and sensitive data leaks in agent skill packages and GitHub repositories.

A lightweight tool to analyze untrusted code before you run it.

---

## 🚀 Features

* 🔍 Detect suspicious scripts (JavaScript, Python, Shell)
* 🍪 Identify cookie / token exfiltration
* 📦 Scan zip packages and mixed file structures
* 🕵️ Detect hidden commands and persistence behavior
* ⚠️ Flag risky operations (system access, env leaks, network calls)
* 🧠 Built for **Agent Skills / AI workflow security**

---

## ⚡ Why this exists

Agent skills are often treated as harmless building blocks:

> Copy. Paste. Run.

But in reality, they are **executable logic** with access to:

* local files
* environment variables
* API keys
* system commands

This creates real risks:

* Data exfiltration
* Hidden backdoors
* Silent malicious execution

This project helps you:

👉 **Detect risks before trusting code**

---

## 📦 What it scans

* Script files (`.js`, `.py`, `.sh`)
* Compressed packages (`.zip`)
* GitHub repositories
* Agent skill bundles

---

## 🛠️ Usage

```bash
git clone https://github.com/szyszy070524/detection
cd detection

# example
# python main.py <path>
```

---

## 🧪 Example detections

* Suspicious network activity
* Cookie / token access
* System / environment data access
* Hidden shell execution
* Obfuscated payloads

---

## 🤝 Contributing

This is an early-stage project.

You can help by:

* Adding detection rules
* Sharing suspicious patterns
* Improving accuracy
* Expanding language support

---

## 🌍 Vision

Security should be part of the **agent ecosystem**, not an afterthought.

As AI workflows grow:

👉 Trusting code blindly will become a major risk.

---

## ⭐ Support

If you find this useful, give it a star ⭐

---

## 📜 License

MIT
