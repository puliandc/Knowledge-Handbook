# Claude Code 使用技巧

以下内容总结自阅读经验，适合在项目开发中使用 Claude Code 时参考。  
Tags: #AI #ClaudeCode #workflow #tips  

---

## 1. /init
- 作用：初始化项目，生成 `CLAUDE.md` 文件。
- 内容：记录项目背景、目标、风格指南、工具函数。
- 价值：保持上下文一致性，不需要重复说明。

## 2. Plan Mode
- 作用：让 Claude Code 先规划，再执行。
- 使用场景：遇到复杂需求或思路不明确时。
- 快捷键：`Shift + Tab`

## 3. /ide
- 作用：集成 VS Code 或 Cursor，增强交互体验。
- 步骤：
  1. 安装 Claude Code 插件
  2. 运行 `/ide` 选择 IDE

## 4. Custom Command
- 作用：自定义命令，减少重复输入。
- 方法：在 `claude/commands` 文件夹中创建 Markdown 文件（文件名 = 命令名）。

## 5. /cost
- 作用：查看 API 使用费用（仅 API 用户适用）。
- 补充：可用 `/model` 切换模型节省成本。
