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

## 按功能选择 Skill

| 类别 | Skill | 功能 |
|---|---|---|
| 全文结构规划 | `map-imrad-paper-structure` | 规划、诊断和重构科研论文的 IMRaD/AIMRaD 全文脉络，检查研究缺口、目标、方法、结果、讨论与贡献是否对齐。 |
| 全文修订与润色 | `polish-full-academic-manuscript` | 基于两份全文修订与科学写作风格专家 PDF，从研究目的、论点证据和整体结构，到段落衔接、句子表达、术语与语法一致性，系统润色完整论文。 |
| 核心章节写作 | `write-research-introduction` | 基于专家写作材料与证据约束，规划、起草、翻译、审查并定稿论文 Introduction，完成研究背景、文献综合、研究缺口与本文目标的由宽到窄衔接。 |
| 核心章节写作 | `academic-abstract-writing` | 基于三份摘要写作专家 PDF，起草、诊断、翻译、压缩并定稿期刊、综述、结构式、会议及扩展摘要，同时检查修辞 move、证据边界、语言选择和投稿限制。 |
| 核心章节写作 | `related-work-writer` | 基于 Related Work 专家材料，对文献进行分箱、分类、比较与综合，建立证据矩阵，组织研究流派并将评述准确导向研究缺口和本文定位。 |
| 核心章节写作 | `write-methods-results` | 基于实验方案、研究设计、统计计划、图表和结果证据，起草、审查、翻译并定稿论文的 Methods 与 Results，同时检查可复现性、定量表达和 Results/Discussion 边界。 |
| 图表与结果表达 | `write-experimental-figures-tables` | 基于实验图表写作专家材料，选择和审查图表，撰写图题、图注、表注、正文引用、数据比较与图表驱动的 Results，并约束统计显著性、因果关系和缺失信息的表达。 |
| 引用与学术规范 | `audit-academic-citations` | 基于引用与文献归因专家材料，核查引用必要性与位置、论断—来源支持关系、第一手与第二手来源归因、直接引用、概括、转述及正文—参考文献一致性。 |

推荐的一般使用顺序是：先规划全文结构，再完成各章节和图表结果表达，随后审计引用，最后进行全文语言与结构润色。实际使用时可以只安装需要的 Skill。

## 安装

### 1. 克隆仓库

```powershell
git clone https://github.com/guoym044-afk/writing-skills.git
cd writing-skills
```

如果已经克隆过仓库，可在仓库目录执行 `git pull --ff-only` 获取最新版本。

### 2. 安装单个 Skill

Windows PowerShell 示例：

```powershell
$SkillName = "map-imrad-paper-structure"
$TargetRoot = Join-Path $env:USERPROFILE ".codex\skills"
New-Item -ItemType Directory -Force -Path $TargetRoot | Out-Null
Copy-Item -Recurse -Force "skills\academic-writing\$SkillName" $TargetRoot
```

macOS 或 Linux 示例：

```bash
SKILL_NAME="map-imrad-paper-structure"
mkdir -p "$HOME/.codex/skills"
cp -R "skills/academic-writing/$SKILL_NAME" "$HOME/.codex/skills/"
```

安装后应形成：

```text
~/.codex/skills/map-imrad-paper-structure/SKILL.md
```

将示例中的 Skill 名称替换为下表中的任意名称，即可安装对应 Skill。若目标目录中已有同名 Skill，上述命令会更新其中的同名文件；重要的本地自定义内容应提前备份。

### 3. 批量安装全部学术写作 Skill

Windows PowerShell：

```powershell
$TargetRoot = Join-Path $env:USERPROFILE ".codex\skills"
New-Item -ItemType Directory -Force -Path $TargetRoot | Out-Null
Get-ChildItem "skills\academic-writing" -Directory | ForEach-Object {
    Copy-Item -Recurse -Force $_.FullName $TargetRoot
}
```

macOS 或 Linux：

```bash
mkdir -p "$HOME/.codex/skills"
cp -R skills/academic-writing/* "$HOME/.codex/skills/"
```

完成安装或更新后，建议新建一个 Codex 任务，使 Skill 列表重新加载。

### 4. 检查安装结果

Windows PowerShell：

```powershell
Get-ChildItem "$env:USERPROFILE\.codex\skills" -Directory | Select-Object Name
```

macOS 或 Linux：

```bash
ls -1 "$HOME/.codex/skills"
```

## 每个 Skill 的调用示例

显式写出 `$skill-name` 最稳定，也可以用相应的自然语言请求触发。

| Skill | 示例提示词 |
|---|---|
| `map-imrad-paper-structure` | `使用 $map-imrad-paper-structure 读取这篇论文，建立 IMRaD 结构图，检查研究问题、方法、结果、讨论和贡献是否一致，并给出需要重排的部分。` |
| `polish-full-academic-manuscript` | `使用 $polish-full-academic-manuscript 对这篇论文进行全文语言、衔接、段落和整体结构润色；保留数据、公式、引用和技术含义，并列出需要作者确认的问题。` |
| `write-research-introduction` | `使用 $write-research-introduction 根据我提供的文献和研究贡献重写 Introduction，按背景—研究现状—缺口—本文目标组织，不添加未提供的引用。` |
| `academic-abstract-writing` | `使用 $academic-abstract-writing 将这篇论文压缩为不超过 250 词的英文期刊摘要，保留研究目的、方法、主要定量结果和有证据支持的结论。` |
| `related-work-writer` | `使用 $related-work-writer 将这些文献按技术路线分类，比较各类方法的共同点、差异和局限，并写成能够自然导向本文研究缺口的 Related Work。` |
| `write-methods-results` | `使用 $write-methods-results 根据实验方案和结果表分别起草 Methods 与 Results，检查可复现性、统计表达和 Results/Discussion 边界，不补造缺失数据。` |
| `write-experimental-figures-tables` | `使用 $write-experimental-figures-tables 根据这些图表和统计结果撰写图题、图注、正文引用及 Results 段落，准确比较趋势、效应量和显著性。` |
| `audit-academic-citations` | `使用 $audit-academic-citations 审计这篇论文的引用必要性、引用位置、论断—来源支持关系和正文—参考文献一致性，并区分必须修正与建议改进的问题。` |

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
