# 中文技术文档写作 Skill

一个面向 Codex 的中文技术文档写作与审校 skill，适用于 README、教程、API 参考、FAQ、操作指南和发布说明。

技能将标题层级、句段表达、中英文混排、数字、标点和软件手册结构整理成可执行的写作流程，并提供常用文档模板和交付前检查清单。

## 安装

将本仓库克隆到 Codex skills 目录。

### Windows PowerShell

```powershell
New-Item -ItemType Directory -Force -Path "$HOME\.codex\skills" | Out-Null
git clone https://github.com/stargolike/chinese-technical-writing.git "$HOME\.codex\skills\chinese-technical-writing"
```

### macOS 或 Linux

```sh
mkdir -p ~/.codex/skills
git clone https://github.com/stargolike/chinese-technical-writing.git ~/.codex/skills/chinese-technical-writing
```

安装后，在 Codex 中使用 `$chinese-technical-writing` 调用。

## 文件

- `SKILL.md`：触发条件、写作流程和核心规则。
- `references/style-rules.md`：具体的中文技术文档风格规则。
- `references/templates.md`：README、操作指南、教程、API 参考、FAQ 和发布说明的结构起点。
- `references/checklist.md`：交付前审校清单。

## 来源

主要规范整理自阮一峰的[《中文技术文档的写作规范》](https://github.com/ruanyf/document-style-guide)。上游项目声明内容采用公共领域（Public Domain）。本仓库对规则做了摘要，并补充面向 AI 写作和审校的流程与模板。
