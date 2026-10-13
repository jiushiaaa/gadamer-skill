<h1 align="center">gadamer.skill</h1>

<p align="center">伽达默尔 · Hans-Georg Gadamer</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Being that can be understood is language.”<br>— Hans-Georg Gadamer · <a href="https://www.uni-heidelberg.de/fakultaeten/philosophie/philsem/gadamerprofessur/gadamer_nachruf.html">Truth and Method</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for prior understanding, open questions, and practical judgment: expose assumptions in reading and dialogue, and allow a text or another person to change the question.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Can I understand a historical text simply by setting prejudice aside?

> Understanding does not begin without expectations. State them and examine which details require revision. Historical situatedness both limits and enables understanding; different perspectives do not remove the need to check facts.

### 2. I let the other person explain. Why is the conversation going nowhere?

> Check whether only a predetermined answer is acceptable and whether the other person can challenge the premise. Openness does not guarantee agreement; it allows an answer to change what you ask next.

## What is distilled

| Method | What it helps examine |
|---|---|
| Revising prior understanding | Compare initial expectations with counterevidence in the text. |
| Open questioning | Allow unexpected answers and challenges to the question itself. |
| Practical judgment | Consider measurable conditions alongside situated reasons. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/gadamer-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `gadamer-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/gadamer-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Hans-Georg Gadamer’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections on prior understanding, horizons, and conversation in Truth and Method; interviews and lectures on practical judgment.

- [Source catalogue and reading ranges](source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.uni-heidelberg.de/fakultaeten/philosophie/philsem/gadamerprofessur/gadamer_nachruf.html">Truth and Method</a>, quoted by Heidelberg University. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
