---
name: nvm-usage-basics
description: Cover everyday nvm usage for installing, switching, and listing Node versions, including LTS and system node.
license: Complete terms in LICENSE.txt
---

## When to use this skill

**ALWAYS use this skill when the user mentions:**
- Installing a Node version with nvm
- Switching active Node versions
- Listing installed or remote versions
- Using LTS or system node

**Trigger phrases include:**
- "nvm install", "nvm use", "nvm ls", "ls-remote"
- "LTS", "长期支持", "system node", "io.js"

## How to use this skill

**CRITICAL: This skill focuses on basic version management commands.** For default version or .nvmrc, use the defaults skill.

1. Select the required command: install, use, ls, or ls-remote.
2. Choose LTS or specific versions based on stability needs.
3. Confirm available versions before switching.
4. Use system node only when required by the OS.

**Important notes:**
- LTS is recommended for production stability.

### Example file map

- examples/usage.md
- examples/install-version.md
- examples/use-version.md
- examples/list-versions.md
- examples/long-term-support.md
- examples/system-node.md
- examples/iojs.md

## Keywords

nvm use, nvm install, nvm ls, ls-remote, LTS, system node, node versions, 日常使用

## 能力边界

### ✅ 适用场景
- 当你需要使用此技能对应的技术栈时
- 当项目需要遵循最佳实践时
- 当需要快速上手或深入理解核心概念时

### ⚠️ 需要注意
- 复杂业务逻辑需要结合具体场景调整
- 性能优化需要根据实际数据量评估

### ❌ 不适用场景
- 不相关的技术栈或框架
- 需要完全自定义的特殊场景

## 常见陷阱 (Gotchas)

1. **版本兼容性**：注意框架版本与依赖库的兼容性，不同版本 API 可能有差异
2. **配置文件格式**：配置文件格式错误是最常见的问题，建议使用编辑器的语法检查
3. **环境变量**：确保所有必要的环境变量已正确设置，敏感信息不要硬编码
4. **依赖冲突**：多版本共存时注意依赖冲突，使用 lock 文件锁定版本
5. **性能陷阱**：大数据量场景下注意性能优化，避免 N+1 查询等常见问题

## 使用流程

### Step 1: 环境准备
确保开发环境已安装必要的依赖和工具。

### Step 2: 配置初始化
根据项目需求进行基础配置。

### Step 3: 核心功能使用
按照示例代码实现核心功能。

### Step 4: 测试验证
运行测试确保功能正常。

### Step 5: 部署上线
完成开发后进行部署和监控。
