# Agent Skills 安全风险与应对

🔄 **语言选择 / Language Switch**  
- [中文 (Chinese)](#agent-skills-安全风险与应对)  
- [English](#agent-skills-security-risks-and-mitigation)

随着 "agent skills" 的广泛采用，我们正在进入软件复用的新阶段 —— 但同时也进入了安全风险的新阶段。

大多数人将 skills 视为无害的构建块。复制、粘贴、运行。

但现实是：**skills 是可执行逻辑**，通常可以访问敏感数据、系统环境和外部 API。

这意味着恶意或未经充分审查的 skill 可能：

* 窃取 cookies、令牌或本地文件
* 收集个人数据（姓名、电子邮件、系统信息）
* 执行隐藏命令或持久化机制
* 在工作流中充当静默后门

问题不仅仅是个别不良行为者 —— 而是围绕 skills **缺乏共享的安全思维**。

我们需要开始问：

* 这个 skill 来自哪里？
* 它在底层实际上做了什么？
* 有人审核或验证过它吗？

安全不应该是事后考虑。它应该是 skill 生态系统本身的一部分。

为了帮助朝这个方向前进，我创建了一个简单的检测项目：
`https://github.com/szyszy070524/detection`

它并不意味着完美 —— 只是一个起点。
目标是识别 skill 包（尤其是压缩或混合内容的包）中的潜在风险行为，并使检查变得更容易。

更重要的是，这是一个协作的号召。

如果你关心这个领域：

* 贡献检测规则
* 分享可疑模式
* 提高分析覆盖率
* 帮助定义 "安全 skills" 应该是什么样子

我们还处于早期阶段。这正是它重要的原因。

让我们一起建立更安全的基础。

---

# Agent Skills Security Risks and Mitigation

🔄 **语言选择 / Language Switch**  
- [中文 (Chinese)](#agent-skills-安全风险与应对)  
- [English](#agent-skills-security-risks-and-mitigation)

As "agent skills" become more widely adopted, we're entering a new phase of software reuse — but also a new phase of security risk.

Most people treat skills like harmless building blocks. Copy, paste, run.

But the reality is: **skills are executable logic**, often with access to sensitive data, system environments, and external APIs.

That means a malicious or poorly reviewed skill can:

* Exfiltrate cookies, tokens, or local files
* Collect personal data (names, emails, system info)
* Execute hidden commands or persistence mechanisms
* Act as a silent backdoor in your workflow

The problem isn't just individual bad actors — it's the *lack of a shared security mindset* around skills.

We need to start asking:

* Where did this skill come from?
* What does it actually do under the hood?
* Has anyone audited or validated it?

Security should not be an afterthought. It should be part of the skill ecosystem itself.

To help move in that direction, I've put together a simple detection project:
`https://github.com/szyszy070524/detection`

It's not meant to be perfect — just a starting point.
The goal is to identify potentially risky behaviors in skill packages (especially zipped or mixed-content ones), and make inspection easier.

More importantly, this is a call for collaboration.

If you care about this space:

* Contribute detection rules
* Share suspicious patterns
* Improve analysis coverage
* Help define what "safe skills" should look like

We're early. That's exactly why it matters.

Let's build a safer foundation — together.