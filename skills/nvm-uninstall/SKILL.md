---
name: nvm-uninstall
description: Remove nvm cleanly, including NVM_DIR cleanup, profile edits, and PATH restoration.
license: Complete terms in LICENSE.txt
---

## When to use this skill

**ALWAYS use this skill when the user mentions:**
- Uninstalling or removing nvm
- Cleaning NVM_DIR or profile entries
- Restoring system node priority

**Trigger phrases include:**
- "uninstall nvm", "移除 nvm", "cleanup"
- "restore PATH", "恢复系统 Node"

## How to use this skill

**CRITICAL: This skill is for removal and cleanup only.** Installation or usage belongs to other nvm-* skills.

1. Remove NVM_DIR and delete nvm profile entries.
2. Restore PATH to prioritize the system Node.
3. Validate that nvm commands are no longer available.

### Example file map

- examples/uninstall.md
- examples/restore-path.md
- examples/system-node.md

## Keywords

nvm uninstall, remove, cleanup, PATH restore, system node, 卸载

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
