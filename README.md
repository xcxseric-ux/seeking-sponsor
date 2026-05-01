# seeking-sponsor（求包养技能）

面向 Claude / Cursor 等 Agent 的一份技能说明文档：帮用户把能力与价值整理成可合作的「宣言」，并强调伦理边界（非 PUA）。

文档正文见仓库根目录的 **SKILL.md**。

## 与 HermeSchool 的关系

**HermeSchool**（Hermes 深度指南）仅作为「文档型开源仓库」的组织参考示例，例如 README、目录清晰度、是否单独 LICENSE 等：

https://github.com/xcxseric-ux/HermeSchool

本仓库是**独立**主题（赞助 / 合作叙事技能），与 HermeSchool 代码与内容无依赖关系。

## 在 GitHub 上新建本仓库（你需要自己在网页上操作）

我无法替你登录 GitHub 创建远程仓库；按下面做一次即可得到「独立开源仓库地址」。

1. 打开 GitHub，登录账号。
2. 右上角 **New repository**。
3. **Repository name** 自定（例如 `seeking-sponsor`）。
4. **Public**。若本目录已有 `README.md`，建议**不要**勾选 “Add a README”，避免与本地推送冲突。
5. 创建完成后，复制页面上的仓库 URL（形如 `https://github.com/<你的用户名>/<仓库名>.git`）。

## 首次推送（在本机此目录执行）

若当前目录落在 Obsidian 大仓库内部，直接 `git init` 会形成嵌套仓库；更稳妥的做法是：把整个 `06-seeking-sponsor-open` 文件夹复制到磁盘上任意独立路径，再在该副本里执行下列命令（把第一行路径换成你的实际路径）。

```bash
cd /path/to/06-seeking-sponsor-open
git init
git add README.md LICENSE SKILL.md .gitignore
git commit -m "Initial publish: seeking-sponsor skill"
git branch -M main
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main
```

将 `<你的用户名>`、`<仓库名>` 换成你在上一步创建的仓库信息。

## 与 Obsidian 知识库的同步

Obsidian vault 里可能另有 canonical 副本（例如 vault 根目录的 `seeking-sponsor.md`）。更新流程建议：

- 以 vault 为编辑主阵地时：改 vault → 再复制覆盖本目录 `SKILL.md` → commit / push。
- 若以本仓库为主阵地：改 `SKILL.md` → 按需反向合并回 vault。

## 免责声明

技能内容仅供合法社交与个人成长语境下的表达练习；禁止用于欺诈、胁迫或违反当地法律与伦理的行为。详见 SKILL.md 内「操控 vs 吸引」与法律伦理红线章节。
