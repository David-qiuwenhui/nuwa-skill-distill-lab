# Nuwa Skill Distill Lab

## 项目简介
从名人公开资料中蒸馏思维模式和表达风格，编码为可复用的 AI skill。

## 目录结构
```
figures/<pinyin-name>/      # 每位名人的完整蒸馏工作区
├── sources/                # 原始资料（语录、文章、访谈、视频文字稿等）
├── notes.md                # 分析笔记（思维模式、决策框架提取）
├── prompts.md              # Prompt 草稿和迭代版本
└── skill.md                # 最终蒸馏出的 skill

shared/                     # 跨名人共享资源
├── templates/              # 新增名人时使用的模板
├── evaluation/             # 蒸馏质量评估标准
└── conventions.md          # 项目约定

skills/                     # nuwa-skill 框架及参考示例
```

## 工作流程
1. 收集原始资料 → `sources/`
2. 分析提炼 → `notes.md`
3. 编写迭代 prompt → `prompts.md`
4. 定稿 skill → `skill.md`

## 命名规范
- 中文人名使用拼音全拼 + 连字符（如 `she-shiman`）
- 文件使用小写英文 + 连字符（如 `decision-framework.md`）
