<div align="center">

# nvm-skills

**Node Version Manager (nvm) skills — install, setup, CI, troubleshooting**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Fnvm-skills-green.svg)](https://github.com/full-statck-skills/nvm-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) ·
[Install](#-install) ·
[Skills](#-skills) ·
[Supported Agents](#-supported-agents) ·
[Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**nvm Skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) ecosystem maintained by [PartMe.AI](https://github.com/partme-ai).

This package includes **15 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-statck-skills/nvm-skills
```

Or install specific skills:

```bash
npx skills add full-statck-skills/nvm-skills --skill <skill-name>
```

## 🎯 Skills (15)

| Skill | Description |
|-------|-------------|
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

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **All Skill Groups** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
