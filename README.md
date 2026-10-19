# mattpocock/skills · 技能收藏

本仓库收录 [mattpocock/skills](https://github.com/mattpocock/skills) **v1.3.1**（2026-10-04 发布）的技能集合，用于备份与离线取用。

- **上游来源**：https://github.com/mattpocock/skills
- **版本**：v1.3.1（`package.json` version = 1.3.1）
- **许可**：MIT（见根目录 `LICENSE`，版权归 Matt Pocock 及贡献者所有）
- **收录日期**：2026-10-19

## 目录结构

```
skills/
├── engineering/   # 工程技能（20）：tdd、to-spec、to-tickets、code-review、diagnosing-bugs、
│                  #   implement/implement-spec、pr、research、retro、triage、wayfinder、wizard、
│                  #   prototype、ask-matt、domain-modeling、codebase-design、
│                  #   improve-codebase-architecture、grill-with-docs、setup-matt-pocock-skills
├── productivity/  # 生产力（7）：grill-me、grilling、handoff、teach、to-questionnaire、wait-what、writing-for-agents
├── misc/          # 杂项（4）：git-guardrails-claude-code、migrate-to-shoehorn、scaffold-exercises、setup-pre-commit
├── in-progress/   # 未稳定（7）：chief-of-staff、claude-handoff、loop-me、setup-ts-deep-modules、writing-beats/fragments/shape
└── deprecated/    # 已废弃（1）
```

> 建议优先使用 `engineering` / `productivity` / `misc` 三类；`in-progress` 未稳定、`deprecated` 已废弃，按需取用。

## 安装到 WorkBuddy

WorkBuddy 只识别用户级技能目录 `~/.workbuddy/skills/` 下的**直接子文件夹**，因此需扁平化复制（按需挑选，勿整目录塞入以免技能过多）：

```bash
# 示例：安装单个技能
cp -r skills/engineering/tdd ~/.workbuddy/skills/tdd
```

技能加入后**可能需要新开一个会话**才会出现在 WorkBuddy 的技能/命令列表中。

## 首次配置

在具体代码仓库中首次使用工程技能前，运行 `/setup-matt-pocock-skills`（位于 `skills/engineering/setup-matt-pocock-skills/`）完成逐仓库的 issue tracker、triage 标签与域文档（GLOSSARY/ADR）配置。
