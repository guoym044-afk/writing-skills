# Patterns and Checklists

Use this reference when drafting, revising, or auditing manuscript prose. Treat every pattern as a scaffold; replace bracketed text with verified content and adapt it to the target discipline.

## Contents

- Evidence matrix
- Section and paragraph patterns
- Comparison language
- Gap and positioning patterns
- Cohesion toolkit
- Anti-patterns
- Final checklist

## Evidence Matrix

| Source | Shared objective | Method/mechanism | Evidence/setting | Relevant finding | Strength | Boundary | Relation to this paper | Bin |
|---|---|---|---|---|---|---|---|---|
| [key] | [objective] | [method] | [data/context] | [supported result] | [capability] | [stated or inferred, labeled] | [support/contrast/extend/unresolved] | [label] |

Add columns only when they drive the paper's argument. Common additions are assumptions, supervision, compute, robustness, interpretability, and evaluation protocol.

## Section and Paragraph Patterns

### Research-stream paragraph

`[Stream] approaches address [shared objective] by [common principle]. [Sources] use [variant A], whereas [sources] rely on [variant B]. The former [evidence-backed consequence], while the latter [evidence-backed consequence]. Despite [collective contribution], both lines remain [bounded unresolved issue], which is important for [target context].`

### General-to-specific paragraph

`Research on [broad area] has established [supported field-level point]. Within this area, [substream] focuses on [narrower objective]. Recent studies further examine [closest topic], showing [supported synthesis]. However, their evidence is concentrated in [boundary], leaving [specific need] unresolved.`

### Problem-solution paragraph

`[Situation] creates [problem]. Early work addressed it through [solution family A], achieving [supported contribution] but requiring [constraint]. Later studies introduced [solution family B] to reduce that constraint. These methods improve [dimension], yet [evaluation or setting boundary] remains unclear.`

### Closest-work paragraph

`The studies most closely related to ours are [sources], which share [objective or mechanism]. They differ from the present work in [explicit axis]: [specific comparison]. This distinction matters because [consequence]. Our study therefore evaluates/proposes [precise position], rather than claiming to replace the broader class of [methods].`

## Comparison Language

Use language that states both the axis and consequence:

- `Both A and B target [objective], but they differ in [axis].`
- `Whereas A assumes [condition], B is evaluated under [condition].`
- `A reduces [cost] at the expense of [tradeoff]; B instead prioritizes [dimension].`
- `These findings are consistent on [point] but diverge under [setting].`
- `Direct comparison is not possible because the studies use [different evidence/protocols].`
- `The available evidence supports [bounded conclusion], not [stronger conclusion].`

Avoid ranking methods across incomparable datasets, metrics, populations, or tasks.

## Gap and Positioning Patterns

### Evidence gap

`Although prior studies demonstrate [capability] in [tested settings], they do not report evaluation under [target condition]. It therefore remains unclear whether [specific question]. We address this evidence gap by [evaluation contribution].`

### Method gap

`Existing approaches separately provide [capability A] and [capability B], but the reviewed studies do not establish a method that combines them under [constraint]. This motivates [current method], designed to [bounded capability].`

### Setting or population gap

`Evidence is concentrated in [setting/population]. Because [relevant difference], those findings may not transfer to [target setting]. The present study examines [target] while holding [important comparison condition] explicit.`

### Evaluation gap

`Prior work reports gains on [metric/protocol], but comparisons use heterogeneous [datasets/baselines/metrics]. The relative performance under a common protocol is therefore unresolved. We provide [standardized evaluation], limited to [scope].`

### Integration gap

`Research streams on [A] and [B] have developed largely independently. Their combination could address [need], but the reviewed literature does not test [specific integration]. We investigate [integration] and evaluate [outcomes].`

### Cautious absolute-claim replacements

- Replace `No study has...` with `Among the reviewed studies, we found no evaluation of...`.
- Replace `Few studies...` with `Only [verified number] of the [verified corpus size] reviewed studies examine...`.
- Replace `Existing methods fail...` with `Existing evaluations do not establish performance under...`.
- Replace `Our method is the first...` with `To our knowledge, and within [documented search scope], this is the first...` only when the search supports it.

## Cohesion Toolkit

### Stable lexical chain

Repeat the exact technical noun when a synonym could create ambiguity. Use pronouns or demonstratives only when the antecedent is unmistakable.

### Reference expressions

- `this limitation` must follow one clearly stated limitation;
- `these approaches` must refer to an explicit, nearby group;
- `the former/latter` works only for exactly two unambiguous items;
- `such methods` should not silently expand or narrow the category.

### Logical links

- Additive: `in addition`, `further`, `also`.
- Contrastive: `however`, `whereas`, `by contrast`.
- Causal: `therefore`, `consequently`, `because`.
- Temporal or developmental: `initially`, `subsequently`, `more recently`.

Use connectors when they reveal a real relationship. Do not stack them or place one mechanically at every sentence opening.

## Anti-Patterns

- **Annotated bibliography:** one paper per sentence with no cross-paper claim.
- **Citation dump:** a long citation cluster attached to a claim not shared by all sources.
- **Taxonomy without purpose:** categories that do not clarify the current paper's contribution.
- **Axis switching:** comparing method, then year, then dataset without signaling why.
- **Unsupported limitation:** treating missing discussion as proof of failure.
- **Gap leap:** moving from `work exists` directly to `our method is needed` without a boundary and consequence.
- **Novelty inflation:** `first`, `only`, `comprehensive`, or `state of the art` without a documented basis.
- **Chronology as organization:** listing years when the intellectual change is thematic or methodological.
- **Connector overload:** fluent-looking prose whose causal or contrastive relation is not evidence-backed.
- **New closing claim:** introducing a source or limitation only in the final synthesis.

## Final Checklist

- [ ] The section has one dominant organizing logic.
- [ ] Every heading names a research concept or stream.
- [ ] Each paragraph begins with a claim or organizing idea.
- [ ] Multiple sources are synthesized where the evidence permits.
- [ ] Every comparison names a shared axis.
- [ ] Contributions appear before or alongside limitations.
- [ ] Inferences are distinguished from source-stated facts.
- [ ] The gap is specific, consequential, and evidence-derived.
- [ ] The paper's position answers the gap without overstating novelty.
- [ ] Key terms and references create a traceable lexical chain.
- [ ] Citations and bibliography entries are mutually consistent.
- [ ] The final synthesis adds no unsupported information.
