# AutoResearch Skill

一个通用、证据驱动、可累积的科研 Agent Skill。它指导 Agent 理解研究全局、提出可检验假设、设计和评估实验、维护研究知识，并规划下一步研究。

## 仓库结构

```text
autoresearch-skill/
├── README.md
└── skills/
    └── autoresearch/
        └── SKILL.md
```

本仓库只包含通用科研行为规范，不包含特定项目的指标、实验执行代码、数据库或 UI。项目目标和成功标准应由各项目自己的 PLAN 提供。

## 安装

### Codex

个人级安装：

```bash
mkdir -p ~/.agents/skills/autoresearch
cp skills/autoresearch/SKILL.md ~/.agents/skills/autoresearch/SKILL.md
```

项目级安装：

```bash
mkdir -p .agents/skills/autoresearch
cp skills/autoresearch/SKILL.md .agents/skills/autoresearch/SKILL.md
```

### Claude Code

个人级安装：

```bash
mkdir -p ~/.claude/skills/autoresearch
cp skills/autoresearch/SKILL.md ~/.claude/skills/autoresearch/SKILL.md
```

项目级安装：

```bash
mkdir -p .claude/skills/autoresearch
cp skills/autoresearch/SKILL.md .claude/skills/autoresearch/SKILL.md
```

### Claude.ai

将 `skills/autoresearch/` 文件夹压缩为 ZIP，然后进入 **Customize → Skills → Create skill → Upload a skill** 上传 ZIP。

## 使用建议

- 将项目目标、评价标准、基线和约束保存在项目自己的 PLAN 中。
- 将实验执行、数据校验和知识库读写交给相应工具或 Research Framework。
- 本 Skill 负责科研行为规范，不代替实验平台、研究数据库或项目配置。

## 状态

初始草案。正式公开发布前，建议补充版本号、贡献指南和由仓库维护者选择的开源许可证。
