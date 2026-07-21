---
name: write-methods-results
description: Draft, revise, diagnose, translate, and finalize research-paper Methods and Results sections in Chinese or English. Use when Codex needs to turn protocols, study designs, experiment notes, statistical plans, figures, tables, or raw findings into publication-ready Methods or Results; check reproducibility and reporting completeness; distinguish Results from Discussion; align prose with research questions and figure order; or resolve wording, tense, voice, quantitative reporting, and journal-style issues in these sections.
---

# Write Methods and Results

## Core rules

- Preserve truthfulness. Never invent sample sizes, settings, equipment, software versions, statistical tests, effect sizes, uncertainty, p-values, ethics approvals, exclusions, or results.
- Mark missing information as `[NEEDED: ...]`. Ask only the questions that materially affect validity or reproducibility.
- Follow the target journal and discipline when supplied. If current journal instructions must be checked, verify the official author guide before applying it.
- Separate evidence from interpretation. Report observations and supported comparisons in Results; reserve mechanisms, broad explanations, implications, and recommendations for Discussion unless the journal combines the sections.
- Maintain traceability: every Methods claim must map to an actual study action, and every Results claim must map to a figure, table, analysis output, or supplied observation.
- Prefer a complete, usable draft plus a concise gap list over stopping at the first missing detail.

## Choose the task mode

1. **Draft**: build a section from notes, protocols, tables, or figures.
2. **Revise**: preserve scientific meaning while improving structure, precision, flow, and language.
3. **Audit**: diagnose omissions, unsupported claims, Methods/Results mixing, and reporting weaknesses before rewriting.
4. **Translate**: translate scientifically rather than literally; preserve quantities, units, terminology, and claim strength.
5. **Finalize**: conform headings, tense, voice, terminology, cross-references, and level of detail to the target journal.

## Build an evidence brief

Collect or infer only what the user supplied:

- field, study type, research questions or hypotheses, and target journal;
- materials, participants, samples, inclusion/exclusion rules, ethics, equipment, conditions, and software;
- chronological procedures, controls, randomization/blinding if applicable, and deviations from established methods;
- data-processing steps, variables, statistical tests, uncertainty, significance criteria, and replicate definitions;
- each figure/table's purpose, comparison, key numeric result, unit, variability, and statistical evidence.

When source files are available, inspect them before drafting. Create a compact internal map:

`research question -> method/procedure -> analysis -> figure/table -> supported result`

Do not silently repair contradictions. Flag inconsistent sample counts, labels, units, statistics, or figure references.

## Draft or revise Methods

Read [references/methods-guide.md](references/methods-guide.md) whenever the request includes Methods, Materials and Methods, Methodology, Experimental Procedures, simulations, data collection, or statistical analysis.

Use the default order unless disciplinary or journal conventions require another structure:

1. study overview and design rationale;
2. materials, participants, samples, or data sources;
3. procedures, interventions, measurements, or computational workflow;
4. data processing and analysis.

Write enough detail for a qualified reader to judge appropriateness and reproduce the work. Cite established procedures concisely; describe modifications and new methods in full. Explain choices when the rationale is not obvious. Use subheadings for distinct experiments or designs.

## Draft or revise Results

Read [references/results-guide.md](references/results-guide.md) whenever the request includes Results, findings, tables, figures, quantitative comparisons, unexpected findings, or a combined Results and Discussion section.

Organize by research question, experiment, or figure/table order - not by the order in which the data happened to be analyzed. Use this paragraph pattern flexibly:

1. objective or brief methodological cue;
2. figure/table location;
3. key quantitative finding and comparison;
4. restrained, evidence-near comment or transition.

State the result first when it matters more than the location sentence. Report only representative values needed to establish the pattern. Do not narrate every cell of a table or repeat captions.

## Control language and claim strength

Read [references/language-patterns.md](references/language-patterns.md) when drafting English, translating, repairing tense/voice, or improving transitions and quantitative descriptions.

- Use past tense for actions performed and results observed in the present study.
- Use present tense for general truths, equations or algorithms treated as current facts, and what a figure/table shows as a document artifact when appropriate.
- Choose active or passive voice for clarity and journal fit. Avoid mechanical passive voice.
- Match claim strength to evidence. Do not convert association into causation or statistical significance into practical importance.
- Keep terminology, abbreviations, units, decimal precision, group names, and statistical notation consistent.

## Audit before delivery

Read [references/final-checklist.md](references/final-checklist.md) for audits, finalization, or high-stakes submission work.

Verify separately:

- **Methods**: reproducibility, design rationale, materials/subjects, conditions, sequence, controls, ethics, data processing, statistics, and external citations.
- **Results**: alignment with aims, figure/table order, numerical fidelity, uncertainty/statistics, representative rather than exhaustive reporting, and absence of unsupported interpretation.
- **Cross-section**: every reported result has a described method; every important method has a corresponding result or a clear reason for inclusion.

## Deliver the result

Unless the user requests another format, provide:

1. a publication-ready Methods and/or Results draft;
2. a short `[NEEDED]` list for unresolved scientific details;
3. a concise audit note only for material issues, such as contradictions, unsupported claims, or journal-dependent choices.

Preserve the user's citation style and figure/table numbering. Explain revisions in the user's language while drafting the paper section in the requested manuscript language.
