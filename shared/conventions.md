# 项目约定

## 命名规范
- 名人目录使用拼音全拼、连字符分隔（如 `she-shiman/`）
- 文件使用小写英文 + 连字符（如 `decision-framework.md`）

## 蒸馏流程
1. 收集原始资料 → `sources/`
2. 分析提炼 → `notes.md`
3. 编写迭代 prompt → `prompts.md`
4. 定稿 skill → `skill.md`
5. 评估验证 → 使用 `shared/evaluation/` 中的标准

## 目录结构
```
figures/<pinyin-name>/
├── sources/       # 原始资料
├── notes.md       # 分析笔记
├── prompts.md     # Prompt 迭代记录
└── skill.md       # 最终蒸馏 skill
```
