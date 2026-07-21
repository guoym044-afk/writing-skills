---
name: related-work-writer
description: Plan, classify, compare, draft, rewrite, or audit a paper's Related Work or literature review section. Use for requests about Related Work, related studies, 文献综述, 相关工作, 国内外研究现状, grouping papers into themes or methods, building comparison matrices, replacing paper-by-paper summaries with synthesis, organizing citations, identifying a defensible research gap, positioning the current paper against prior work, or improving paragraph flow and cohesion in Chinese or English academic writing.
---

# Related Work Writer

Produce a source-grounded Related Work section that explains the field's structure, compares research streams, and leads to a precise gap and paper position. Adapt the depth and labels to the target venue instead of treating a Related Work section as a full review article.

## Apply Non-Negotiable Rules

- Never invent a paper, citation, result, limitation, dataset, method detail, or research gap.
- Mark missing evidence explicitly. Use `[citation needed]` or a clearly labeled placeholder only when the user permits placeholders.
- Separate a paper's stated limitation from the writer's inference. Label an inference as such and explain its basis.
- Compare sources at a consistent level: method with method, setting with setting, evidence with evidence.
- Present a gap only after establishing the relevant prior work. Make the gap narrower than the field and proportional to the evidence.
- Follow the target journal or conference conventions, requested language, word limit, citation style, and disciplinary norms.
- Prefer primary studies for specific claims and data. Use reviews for broad background or field mapping unless the user or venue requires otherwise.

## Select the Operation

Choose only the artifacts needed for the request:

- **Plan:** create bins, comparison axes, section order, and a paragraph-level outline.
- **Draft:** write a complete section from verified sources or structured notes.
- **Revise:** reorganize existing prose, strengthen synthesis and cohesion, and preserve supported meaning.
- **Audit:** diagnose classification, comparison, citation, gap, positioning, and flow problems without rewriting unless asked.
- **Matrix:** turn a corpus into an evidence ledger and comparison table before prose drafting.

If the source corpus is absent or too thin, say what is missing. Search for literature only when the user asks for discovery or authorizes expanding the corpus; keep newly found sources separate until their bibliographic details and claims are verified.

## Run the Workflow

### 1. Frame the Current Paper

Extract or infer conservatively:

- research problem and scope;
- unit of analysis, population, setting, task, or domain;
- current paper's method and intended contribution;
- target claim that Related Work must support;
- venue, language, length, and citation style.

Do not organize the literature before knowing what distinction the current paper needs to establish. If context is incomplete, proceed with labeled assumptions that do not change the paper's claimed contribution.

### 2. Build an Evidence Ledger

For each source, record only what is supported:

| Field | Record |
|---|---|
| Identity | citation key, authors, year, title |
| Research focus | problem or objective |
| Approach | theory, method, model, or mechanism |
| Evidence | dataset, sample, setting, baselines, evaluation |
| Finding | result relevant to this paper |
| Strength | contribution or capability |
| Boundary | stated limitation or evidence-backed constraint |
| Relation | supports, contrasts, extends, or leaves unresolved |
| Candidate bins | one or more 1-2 word labels |

Keep `not reported` distinct from `does not exist` and `not evaluated` distinct from `performs poorly`.

### 3. Bin and Classify the Literature

Use titles and abstracts for initial binning, then verify claims in the full source when available. The source materials recommend previewing roughly 10-20 papers before fixing headings; treat this as a heuristic, not a requirement when the corpus is smaller.

Assign 1-2 word labels for recurring methods, themes, findings, tasks, or settings. A source may belong to multiple bins. Prefer 2-5 meaningful bins:

- fewer than 2-3 bins may indicate a narrow corpus or a comparison that belongs in one paragraph;
- more than 4-5 bins may indicate an overly broad scope or shallow categories;
- a small bin may reveal either a search need or a genuine underexplored direction;
- sources that fit no bin may be irrelevant and should not be forced into the section.

Choose the dominant organizing logic:

- **Methodological:** compare approaches that pursue a common objective.
- **Thematic:** compare recurring topics, mechanisms, applications, or findings.
- **Chronological:** explain a process, historical shift, or development over time only when time changes the argument.
- **Hybrid:** use one dominant logic for headings and a second logic inside sections. Do not mix axes unpredictably.

For detailed source-derived guidance, read [references/source-framework.md](references/source-framework.md).

### 4. Order Sections and Paragraphs

Choose an order that performs an argument, not a catalog. Common sequences are:

- broad to specific;
- established or older work to newer and less resolved work;
- problem to solution;
- cause to effect;
- objective to method to result;
- baseline family to closest competing family to the current paper's position.

Place the closest work near the end when this creates a clean transition to the unresolved issue. Do not use chronology merely because publication years are available.

### 5. Compare Within and Across Bins

Select comparison axes that matter to the current paper, such as assumptions, mechanism, supervision, data demand, generalization setting, computational cost, interpretability, robustness, evaluation design, or deployment constraints.

For every comparison:

1. name the shared objective or reference point;
2. state the relevant difference;
3. explain the consequence of that difference;
4. cite the evidence;
5. connect the comparison to the section's claim.

Avoid empty judgments such as `better`, `advanced`, `limited`, or `few studies` without specifying the metric, boundary, or search basis.

### 6. Construct a Defensible Gap and Position

Build the transition in five moves:

1. **State of the field:** synthesize what the relevant stream has achieved.
2. **Boundary:** identify what remains untested, incompatible, fragmented, costly, narrow, or unclear.
3. **Consequence:** explain why the boundary matters for the target problem.
4. **Need:** formulate the missing capability, evidence, integration, or understanding.
5. **Position:** state how the current paper addresses that need, without claiming more than it evaluates.

Distinguish common gap types: evidence, method, setting/population, evaluation, integration, theory/mechanism, or contradiction. Prefer a bounded formulation such as `has not been evaluated under X` over an absolute claim such as `no work has studied X` unless a documented search supports the absolute claim.

### 7. Draft Synthesis Paragraphs

Use a flexible paragraph pattern:

1. topic sentence naming the bin and its relevance;
2. synthesis of several sources around a shared claim;
3. comparison or contrast on one or two explicit axes;
4. boundary, implication, or unresolved issue;
5. bridge to the next paragraph or the current paper.

Vary the pattern when the evidence calls for it. Cite several sources together only when they genuinely support the same proposition. Do not write one isolated summary sentence per paper.

Use general-to-specific movement, problem-solution movement, repeated key terms, controlled demonstrative references, and explicit additive, adversative, causal, or temporal links. Keep topic sentences and key nouns stable enough for readers to follow the chain of ideas. Avoid beginning every sentence with a connector.

For reusable paragraph patterns, comparison language, and audit checks, read [references/patterns-and-checklists.md](references/patterns-and-checklists.md).

### 8. Verify Citations and Claims

- Check that every factual claim is supported by the cited source.
- Check that every in-text citation appears in the reference list and vice versa when the list is available.
- Verify names, year, title, venue, page or locator, and publication status against the original source.
- Cite only relevant and significant work within the scope; do not pad the section.
- Preserve the target venue's citation format rather than converting styles without a request.
- Flag secondary citation and unavailable full text; do not imply direct verification.

### 9. Run the Final Audit

Confirm all of the following:

- headings express concepts, not author names;
- the dominant classification logic is visible and consistent;
- paragraphs synthesize multiple sources where appropriate;
- comparisons use explicit shared axes and evidence;
- contributions and limitations are represented fairly;
- the gap follows from the review and is not merely asserted;
- the current paper's position is specific and non-inflated;
- transitions preserve broad-to-specific or other chosen logic;
- no citation or source detail was fabricated;
- no new literature claim appears in the closing synthesis without earlier support.

## Deliver the Result

Match the user's requested format. When not specified, return:

1. a brief statement of source basis and any assumptions;
2. the chosen classification and comparison logic;
3. a concise outline or matrix if it materially helps;
4. the drafted or revised Related Work text;
5. a short list of evidence gaps or citations that still require verification.

Keep diagnostic notes separate from manuscript-ready prose.
