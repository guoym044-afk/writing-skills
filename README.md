# Writing Skills

面向 Codex 的可复用写作 Skill 集合。仓库按写作领域分类，每个 Skill 都是可以独立安装和调用的子模块。

## 目录结构

```text
writing-skills/
└── skills/
    └── academic-writing/
        ├── map-imrad-paper-structure/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       └── imrad-logic.md
        ├── polish-full-academic-manuscript/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       ├── deliverables.md
        │       ├── language-cohesion.md
        │       ├── revision-framework.md
        │       └── source-notes.md
        ├── write-research-introduction/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       ├── framework.md
        │       ├── language-cohesion.md
        │       ├── quality-checklist.md
        │       └── source-notes.md
        ├── academic-abstract-writing/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       ├── abstract-frameworks.md
        │       ├── revision-checklists.md
        │       └── source-notes.md
        ├── related-work-writer/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       ├── patterns-and-checklists.md
        │       └── source-framework.md
        ├── audit-academic-citations/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       ├── audit-rubric.md
        │       └── source-guidance.md
        ├── write-methods-results/
        │   ├── SKILL.md
        │   ├── agents/
        │   │   └── openai.yaml
        │   └── references/
        │       ├── final-checklist.md
        │       ├── language-patterns.md
        │       ├── methods-guide.md
        │       └── results-guide.md
        └── write-experimental-figures-tables/
            ├── SKILL.md
            ├── agents/
            │   └── openai.yaml
            └── references/
                ├── captions-callouts-and-tables.md
                ├── phrasebank.md
                ├── quality-checklist.md
                ├── results-writing-and-comparisons.md
                ├── source-foundation.md
                └── visual-selection-and-design.md
```

## Skill 目录

| 类别 | Skill | 功能 |
|---|---|---|
| 学术写作 | `map-imrad-paper-structure` | 规划、诊断和重构科研论文的 IMRaD/AIMRaD 全文脉络，检查研究缺口、目标、方法、结果、讨论与贡献是否对齐。 |
| 学术写作 | `polish-full-academic-manuscript` | 基于两份全文修订与科学写作风格专家 PDF，从研究目的、论点证据和整体结构，到段落衔接、句子表达、术语与语法一致性，系统润色完整论文。 |
| 学术写作 | `write-research-introduction` | 基于专家写作材料与证据约束，规划、起草、翻译、审查并定稿论文 Introduction，完成研究背景、文献综合、研究缺口与本文目标的由宽到窄衔接。 |
| 学术写作 | `academic-abstract-writing` | 基于三份摘要写作专家 PDF，起草、诊断、翻译、压缩并定稿期刊、综述、结构式、会议及扩展摘要，同时检查修辞 move、证据边界、语言选择和投稿限制。 |
| 学术写作 | `related-work-writer` | 基于 Related Work 专家材料，对文献进行分箱、分类、比较与综合，建立证据矩阵，组织研究流派并将评述准确导向研究缺口和本文定位。 |
| 学术写作 | `write-methods-results` | 基于实验方案、研究设计、统计计划、图表和结果证据，起草、审查、翻译并定稿论文的 Methods 与 Results，同时检查可复现性、定量表达和 Results/Discussion 边界。 |
| 学术写作 | `write-experimental-figures-tables` | 基于实验图表写作专家材料，选择和审查图表，撰写图题、图注、表注、正文引用、数据比较与图表驱动的 Results，并约束统计显著性、因果关系和缺失信息的表达。 |
| 学术写作 | `audit-academic-citations` | 基于引用与文献归因专家材料，核查引用必要性与位置、论断—来源支持关系、第一手与第二手来源归因、直接引用、概括、转述及正文—参考文献一致性。 |

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
