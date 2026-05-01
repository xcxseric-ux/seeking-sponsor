# seeking-sponsor（求包养技能）

面向 Claude / Cursor 等 Agent 的一份技能说明文档：帮用户把能力与价值整理成可合作的「宣言」，并强调伦理边界（非 PUA）。

文档正文见仓库根目录的 **SKILL.md**。

## 仓库地址

- 主页：https://github.com/xcxseric-ux/seeking-sponsor
- 克隆：`git clone https://github.com/xcxseric-ux/seeking-sponsor.git`

## 与 HermeSchool 的关系

**HermeSchool**（Hermes 深度指南）仅作为「文档型开源仓库」的组织参考示例，例如 README、目录清晰度、LICENSE 等：

https://github.com/xcxseric-ux/HermeSchool

本仓库主题独立，与 HermeSchool 内容无依赖关系。

## 后续更新（本地已有 clone 时）

```bash
cd /path/to/seeking-sponsor-open
# 编辑 SKILL.md / README.md 后：
git add -A
git commit -m "chore: update SKILL"
git push origin main
```

若在 Obsidian 大仓库内维护脚手架副本 `Projects/06-seeking-sponsor-open/`，注意该目录下已有独立 `.git`，不要与外层 vault 仓库混淆。

## 与 Obsidian 知识库的同步

Vault 里可有 canonical 笔记（例如根目录 `seeking-sponsor.md`）。常见流程：

- 以 Vault 为主：改 vault → 覆盖本仓库 `SKILL.md` → commit / push。
- 以本仓库为主：改 `SKILL.md` → 按需合并回 vault。

## 免责声明

技能内容仅供合法社交与个人成长语境下的表达练习；禁止用于欺诈、胁迫或违反当地法律与伦理的行为。详见 SKILL.md 内「操控 vs 吸引」与法律伦理红线章节。
