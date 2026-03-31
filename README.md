# 🐙 my-openclaw-project

> 我的 OpenClaw 技能仓库

## 📖 项目介绍

本项目用于存储和管理 [OpenClaw](https://github.com/openclaw/openclaw) AI 助手的自定义技能。

OpenClaw 是一个强大的 AI 助手框架，支持通过技能（Skills）扩展功能。

## 📁 目录结构

```
my-openclaw-project/
├── README.md           # 项目说明
├── skills/             # 自定义技能目录
│   └── my-skill/       # 技能文件夹
│       ├── SKILL.md    # 技能定义文件
│       └── scripts/    # 技能脚本
└── docs/               # 文档目录
```

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/zhuchenghuai0717/my-openclaw-project.git
cd my-openclaw-project
```

### 2. 创建技能

参考 [OpenClaw 技能开发文档](https://docs.openclaw.ai) 创建你的第一个技能。

### 3. 测试技能

在 OpenClaw 中加载技能并测试功能。

## 📝 开发指南

### SKILL.md 模板

```markdown
---
name: my-skill
description: "技能描述"
metadata:
  {
    "openclaw": {
      "emoji": "🔧",
      "requires": { "bins": ["command"] },
    }
  }
---

# 技能名称

技能详细说明...
```

## 🔗 相关链接

- [OpenClaw 官方文档](https://docs.openclaw.ai)
- [OpenClaw GitHub](https://github.com/openclaw/openclaw)
- [ClawHub 技能市场](https://clawhub.ai)
- [Discord 社区](https://discord.com/invite/clawd)

## 📄 许可证

MIT License

---

**🙏 由 唐僧 维护**
