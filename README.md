# 办公效率技能库

> AI Agent Skills for Office Productivity —— 文档格式转换、演示设计、PPT 自动化

## 定位

为独立开发者和小团队提供一套可安装的 AI Agent 办公效率技能，覆盖 Office 文档处理、Markdown 互转、专业演示制作。

## 核心理念

> 让 AI 接管格式工作，你只需专注内容本身。

- **格式互转**——Office ↔ Markdown 双向转换，让文档进入 Git 工作流
- **设计赋能**——无需设计背景，AI 自动应用品牌级排版和配色
- **批量自动化**——Python 脚本批量处理，告别手工重复操作

## 技能清单

| 环节 | 技能 | 描述 | 来源 |
|------|------|------|------|
| 📥 格式转换 | `office-to-md` | Office/PDF 文档转 Markdown，支持 Word/Excel/PPT/图片/音频 | [衍生](https://skills.sh/claude-office-skills/skills/office-to-md) |
| 📤 格式转换 | `md-to-office` | Markdown 转 Word/PPT/PDF，Pandoc 驱动的专业文档生成 | [衍生](https://skills.sh/claude-office-skills/skills/md-to-office) |
| 🎨 演示设计 | `presentation-designer` | 专业演示设计：5 套品牌风格、排版体系、动画指南、一致性验证 | [衍生](https://skills.sh/willem4130/claude-code-skills/elite-powerpoint-designer) |
| 🤖 PPT 自动化 | `ppt-automation` | PowerPoint 编程操作：python-pptx 创建/修改/提取，模板驱动 | [衍生](https://skills.sh/practicalswan/agent-skills/powerpoint-ppt) |

## 快速开始

```bash
npx skills add skills-repo/office-master@office-to-md -g -y
npx skills add skills-repo/office-master@md-to-office -g -y
npx skills add skills-repo/office-master@presentation-designer -g -y
npx skills add skills-repo/office-master@ppt-automation -g -y
```

## 推荐工作流

```
Office 文档 → Markdown → 编辑/版本控制 → 新 Office 文档
office-        (Git)                    md-to-
to-md                                   office

Markdown 内容 → 专业演示设计 → PPT 自动化输出
              presentation-    ppt-
              designer         automation
```

## 许可

MIT