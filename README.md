<h1 align="center">gadamer.skill</h1>

<p align="center">伽达默尔 · Hans-Georg Gadamer</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“能够被理解的存在，就是语言。”<br>— 伽达默尔 · <a href="https://www.uni-heidelberg.de/fakultaeten/philosophie/philsem/gadamerprofessur/gadamer_nachruf.html">《真理与方法》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将前理解、开放提问与实践判断整理为思想分析 Skill，让 AI 在阅读和对话中暴露自己的预设，允许文本与他人的回答改变原来的问题。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 读历史文本，是不是只要放下偏见就能理解？

> 理解并非从没有预设开始。先写下自己的期待，再看哪些细节迫使它改变；历史处境既会限制理解，也提供进入文本的线索，不能用“各有视角”免除事实核查。

### 2. 我已经让对方解释，为什么对话还是毫无进展？

> 检查你的问题是否只接受预定答案，对方能否指出题设本身有问题。开放不是保证最后同意，而是让回答有机会改变你接下来问什么。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 前理解修订 | 记录初读预期，再用文本中的反向证据修正。 |
| 开放提问 | 检查问题是否允许意外答案或拒绝题设。 |
| 实践尺度 | 同时考虑可测量条件与处境中的合宜理由。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/gadamer-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `gadamer-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/gadamer-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用伽达默尔的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《真理与方法》前理解、视域与谈话选段；访谈、讲演及实践判断相关材料。

- [原作来源、版本与实际阅读范围](source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.uni-heidelberg.de/fakultaeten/philosophie/philsem/gadamerprofessur/gadamer_nachruf.html">《真理与方法》</a>，海德堡大学纪念文章引述。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
