<div align="center">

# nvm-skills

**Node Version Manager (nvm) skills — install, setup, CI, troubleshooting**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Fnvm-skills-green.svg)](https://github.com/full-statck-skills/nvm-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-兼容-purple.svg)](https://agentskills.io)

[English](./README.md) | 简体中文

[简介](#-简介) ·
[安装](#-安装) ·
[技能列表](#-技能列表) ·
[支持的智能体](#-支持的智能体) ·
[生态](#-生态)

</div>

---

## 📖 简介

**nvm 技能** 是一组 AI 编码智能体技能，属于 [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) 生态，由 [PartMe.AI](https://github.com/partme-ai) 维护。

本包包含 **15 个技能**。每个技能是一个独立的 `SKILL.md` 文件，AI 智能体按需加载。

## 📦 安装

```bash
npx skills add full-statck-skills/nvm-skills
```

或按需安装特定技能：

```bash
npx skills add full-statck-skills/nvm-skills --skill <skill-name>
```

## 🎯 技能列表 (15)

| 技能 | 描述 |
|------|------|
| `nvm-defaults-and-nvmrc` | Define default Node versions and manage project-specific versions with .nvmrc and auto-use flows. |
| `nvm-docker-ci` | Cover nvm installation and usage in Docker images and CI/CD pipelines, including non-interactive shell loading. |
| `nvm-global-packages` | Migrate global packages between Node versions and define a default global packages file for consistency. |
| `nvm-install` | Provide comprehensive guidance for installing and updating nvm from the official README, including install scripts, p... |
| `nvm-mirror-and-auth` | Configure Node.js binary mirrors and authentication headers for restricted or 10、Company Manger network environments. |
| `nvm-misc` | Provide nvm overview, output color customization, tests, and automation examples like Ansible. Use when users ask for... |
| `nvm-project-meta` | Provide nvm project metadata like maintainers, support policy, enterprise support, license, and copyright notice. Use... |
| `nvm-setup` | Configure shell initialization and environment variables so nvm loads correctly across bash, zsh, and fish. |
| `nvm-shell-integration` | Enable deeper shell integration and auto-switching for nvm across bash, zsh, and fish. |
| `nvm-troubleshooting-linux` | Diagnose common nvm issues on Linux and WSL, including distro differences, profiles, and PATH errors. |
| `nvm-troubleshooting-macos` | Diagnose common nvm issues on macOS, including profile loading, PATH priority, and permissions. |
| `nvm-uninstall` | Remove nvm cleanly, including NVM_DIR cleanup, profile edits, and PATH restoration. |
| `nvm-usage-basics` | Cover everyday nvm usage for installing, switching, and listing Node versions, including LTS and system node. |
| `nvm-verify` | Verify nvm installation and diagnose PATH or profile loading issues after setup. |
| `nvm` | Guidance for installing, configuring, and using nvm (Node Version Manager) based on the official README. Use when the... |

## 🤖 支持的智能体

适用于 [Claude Code](https://code.claude.com)、[Codex](https://developers.openai.com/codex)、[Cursor](https://cursor.com)、[OpenCode](https://opencode.ai)、[Gemini CLI](https://geminicli.com)、[GitHub Copilot](https://github.com/features/copilot)、[Windsurf](https://codeium.com/windsurf) 及 [70+ 其他平台](https://agentskills.io/clients)。

### Claude Code 安装

**方式一：npx skills CLI（推荐）**

```bash
npx skills add full-statck-skills/nvm-skills
```

**方式二：手动安装**

```bash
git clone https://github.com/full-statck-skills/nvm-skills.git
cp -r nvm-skills/skills/* .claude/skills/
```

更多详情请参阅 [Claude Code 技能指南](https://code.claude.com/docs/en/skills) 和 [Agent Skills 规范](https://agentskills.io/)。

## 🌐 生态

| 资源 | 链接 |
|------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **全部技能组** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills 规范** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 许可证

Apache 2.0 — 详见 [LICENSE](LICENSE)。
