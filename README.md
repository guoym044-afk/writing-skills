# Writing Skills

面向 Codex 的可复用写作 Skill 集合。仓库按写作领域分类，每个 Skill 都是可以独立安装和调用的子模块。

## 目录结构

```text
writing-skills/
└── skills/
    └── academic-writing/
        └── map-imrad-paper-structure/
            ├── SKILL.md
            ├── agents/
            │   └── openai.yaml
            └── references/
                └── imrad-logic.md
```

## Skill 目录

| 类别 | Skill | 功能 |
|---|---|---|
| 学术写作 | `map-imrad-paper-structure` | 规划、诊断和重构科研论文的 IMRaD/AIMRaD 全文脉络，检查研究缺口、目标、方法、结果、讨论与贡献是否对齐。 |

## 安装单个 Skill

将目标 Skill 文件夹复制到个人 Codex Skill 目录：

```text
~/.codex/skills/
```

例如，安装后应形成：

```text
~/.codex/skills/map-imrad-paper-structure/SKILL.md
```

之后可以显式调用：

```text
使用 $map-imrad-paper-structure 帮我敲定这篇论文的全文脉络。
```

## 新增 Skill 约定

1. 将新 Skill 放在 `skills/<category>/<skill-name>/` 下。
2. 使用小写字母、数字和连字符命名 Skill。
3. 每个 Skill 必须包含带 `name` 和 `description` YAML frontmatter 的 `SKILL.md`。
4. 推荐提供 `agents/openai.yaml`；仅在需要时添加 `references/`、`scripts/` 或 `assets/`。
5. 详细知识放入 `references/`，把 `SKILL.md` 保持为精炼、可执行的工作流。
6. 提交前运行 Codex Skill 校验，并用真实或模拟任务做前向测试。

## 分类规划

- `academic-writing`：论文、学位论文、学术报告及投稿写作。
- 后续可按需要增加 `professional-writing`、`technical-writing`、`creative-writing` 等分类。
