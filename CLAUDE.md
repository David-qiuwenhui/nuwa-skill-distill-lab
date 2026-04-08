# Nuwa Skill Distill Lab

## 项目简介
从名人公开资料中蒸馏思维模式和表达风格，编码为可复用的 AI skill。

## 目录约定
- `personalities/<名人>/` — 每位名人的完整蒸馏工作区
  - `00-raw/` — 原始资料（语录、文章、访谈、视频文字稿等）
  - `01-analysis/` — 分析笔记（思维模式、决策框架提取）
  - `02-prompts/` — prompt 草稿和迭代版本
  - `03-skill/` — 最终蒸馏出的 skill，可直接上传 GitHub
  - `README.md` — 名人简介 + 蒸馏进度
- `templates/` — 新增名人时使用的模板
- `shared/` — 跨名人共享的蒸馏方法论

## 工作流程
1. 收集原始资料 → `00-raw/`
2. 分析提炼思维模式 → `01-analysis/`
3. 编写和迭代 prompt → `02-prompts/`
4. 定稿 skill → `03-skill/`

## 命名规范
- 名人目录使用中文全名（如 `佘诗曼/`）
- 文件使用小写英文 + 连字符（如 `decision-framework.md`）
