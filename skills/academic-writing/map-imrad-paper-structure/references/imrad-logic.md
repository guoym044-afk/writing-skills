# IMRaD Full-Paper Logic

## Contents

1. Functional model
2. Macro-organization
3. Section moves
4. Cross-section alignment
5. Evidence ordering
6. Micro-organization and cohesion
7. Variations by research design
8. Diagnostic checks
9. Compact worked example

## 1. Functional model

Treat IMRaD as four scientific questions rather than four compulsory labels:

| Function | Governing question | Reader expectation |
|---|---|---|
| Introduction | What problem or question was studied, and why? | Establish context, need, and the present study. |
| Methods | How was the problem studied? | Make the design understandable and, where applicable, reproducible. |
| Results | What was found? | Present the evidence that answers the stated questions. |
| Discussion | What do the findings mean? | Interpret the answer, delimit it, and position its contribution. |

`AIMRaD` adds an Abstract that compresses the same chain. A paper may rename, merge, reorder, or distribute these functions, but primary research normally contains them somewhere.

Use the target journal's structure and heading rules. Evaluate whether required functions exist before evaluating whether familiar labels exist.

## 2. Macro-organization

### Hourglass model

Use an hourglass to control scope and audience level:

1. Begin broadly enough to establish the field-level situation.
2. Narrow the Introduction through the literature to a precise gap, need, or problem.
3. Reach maximum specificity in Methods and Results, where technical detail and expert audience level are highest.
4. Begin the Discussion with the concrete overall findings.
5. Widen toward implications, comparison with the field, limitations, and future work.

An Introduction that never narrows leaves the study unmotivated. A Discussion that never widens leaves the findings unpositioned. A Methods or Results section written at background level lacks the specificity expected at the center of the hourglass.

### Full argument chain

Maintain this chain across the manuscript:

`known situation -> unresolved problem -> justified need -> objective/RQ/hypothesis -> chosen design -> evidence -> answer -> interpretation -> contribution`

Use the same core terms at corresponding links. If the Introduction promises accuracy, the Results must measure accuracy and the Discussion must interpret accuracy rather than silently substituting efficiency or robustness.

### Abstract and title

Make the Abstract a compact mirror of the paper's functional chain. Do not let it introduce a central claim absent from the main text.

Choose a title that reflects either:

- the major result; or
- the objective and method.

Prefer specificity appropriate to an expert audience. Avoid claiming a broader contribution than the Discussion supports.

## 3. Section moves

### Introduction

Move from broad context to the present study:

1. Establish the research territory, relevance, or situation.
2. Review and synthesize the literature needed to understand the problem.
3. Identify a gap, limitation, need, contradiction, or unresolved question.
4. Justify why resolving it matters.
5. State the present study's objective, research question, or hypothesis.
6. Optionally preview the approach, scope, or expected contribution.

Place the gap/need and present-study statement near the end, commonly in the final one or two paragraphs. Make the objective respond directly to the identified gap.

Use review sources for established background when appropriate and primary research for specific findings or data. Keep citation claims proportional to what the sources establish.

### Methods

Supply the information an expert reader needs to understand the design and, where applicable, repeat it. Depending on the field, include:

- study design and sequence;
- samples, participants, cases, datasets, or assumptions;
- materials, instruments, software, models, or computational environment;
- conditions, quantities, time, thresholds, and preprocessing;
- outcome definitions, variables, controls, baselines, and evaluation metrics;
- statistical or analytical procedures;
- ethical approval and inclusion/exclusion rules where applicable.

Organize subsections by study component or experiment. Give each major method an explicit relationship to an objective, question, hypothesis, or claim.

For theoretical work, treat derivations, assumptions, propositions, proofs, models, simulations, and analytical comparisons as methodological functions. Reproducibility may mean reconstructing the reasoning or computation rather than repeating a physical experiment.

### Results

Walk through experiments, analyses, or proofs in the order that best builds the paper's argument. Call out figures and tables in their first-use order.

Use a result packet when applicable:

1. State the local objective or question.
2. Give only the method reminder needed to understand the evidence.
3. Point the reader to the relevant figure, table, model, or test.
4. State the most important observation, including direction and magnitude when available.
5. Give a brief interpretation or transition to the next result.

Report the findings needed to answer the research questions, including material negative, unexpected, or limiting results. Do not narrate every number in a visual.

The boundary between Results and Discussion varies. Some fields allow literature comparison and stronger interpretation in Results; some combine the two sections. Ensure that full interpretation still appears somewhere.

### Discussion

Position the new research within the field:

1. State the overall findings without merely repeating the Results.
2. Answer the objective, question, or hypothesis.
3. Explain how the findings address the original gap or need.
4. Compare, reconcile, or contrast the findings with relevant research.
5. Explain theoretical, methodological, or practical implications.
6. State limitations, boundary conditions, uncertainties, and challenges.
7. Identify remaining unknowns and justified future research.

Reconnect the Discussion to the Introduction. A limitation should qualify the scope of a claim; future work should arise from a limitation or remaining unknown, not from a generic wish list.

### Conclusion

Include a separate Conclusion only when the venue or argument benefits from it. Keep it brief, often one paragraph. Summarize the largest finding and contribution, note the main boundary or future need, and avoid introducing new evidence.

## 4. Cross-section alignment

### Alignment matrix

Create one row per objective, RQ, hypothesis, or major claim:

| ID | Intro promise | Method | Result | Discussion answer | Contribution |
|---|---|---|---|---|---|
| RQ1 | Gap and question | Design that tests/addresses RQ1 | Evidence answering RQ1 | Meaning and limits of that evidence | What becomes newly known or possible |

Apply these invariants:

- Every Introduction promise must be paid off later.
- Every major Method must produce or analyze evidence used in Results.
- Every major Result must serve an objective, question, hypothesis, or necessary validity check.
- Every Discussion claim must trace to reported evidence.
- Every contribution must close, reduce, reframe, or delimit the stated gap.
- Every limitation must qualify a specific method, result, inference, or scope claim.

### Common orphan defects

- **Orphan objective**: announced in the Introduction but never answered.
- **Orphan method**: described in Methods but unused in Results.
- **Orphan result**: reported without a motivating question or later interpretation.
- **Orphan claim**: asserted in Discussion without direct result support.
- **Orphan contribution**: emphasized at the end but unrelated to the initial gap.
- **Terminology drift**: the construct, population, outcome, or comparison changes name or meaning across sections.

## 5. Evidence ordering

Design the figure and table sequence before drafting detailed Results when possible.

Prefer an argumentative order such as:

1. establish setup, data quality, or validity;
2. present the primary result;
3. test robustness, mechanism, boundary conditions, or alternatives;
4. culminate in the broadest or most consequential result.

Do not default to laboratory chronology. Use chronology only when time or causal sequence is itself part of the argument.

For each visual, record:

- the question it answers;
- the comparison or evidence it contains;
- the one result readers must retain;
- the claim it supports;
- the next visual it motivates.

Remove, demote, or move to supplementary material any visual that does not serve the core chain, subject to transparency and venue requirements.

## 6. Micro-organization and cohesion

### General-specific pattern

Use this pattern when introducing a topic or subsection:

1. start with a definition, comparison, generalization, or purpose statement;
2. narrow through increasingly specific information;
3. optionally widen in the final sentence to state significance or connect forward.

### Problem-solution pattern

Use this pattern when motivating a study, method, or interpretation:

1. describe the situation;
2. identify the problem;
3. present the solution or study response;
4. evaluate the solution's result, value, or limitation.

This pattern can structure the final Introduction paragraphs and also smaller units within Methods or Discussion.

### Cohesion and flow

Make semantic relations visible through:

- reference: this, these, the former/latter, or a precise repeated noun;
- comparison: similar, different, higher, lower, or an explicit baseline;
- addition: also, moreover, or a parallel grammatical structure;
- contrast: however, whereas, although, or a stated exception;
- cause and consequence: because, therefore, consequently, or an explicit mechanism;
- sequence: first, next, finally, or a meaningful procedural order;
- lexical cohesion: controlled repetition, synonyms, superordinate terms, and expected collocations.

Choose the device that represents the actual relation. Avoid stacking generic conjunctions, overusing sentence-initial connectors, or replacing precise recurring terms with varied wording that creates ambiguity.

Check paragraph flow with this test: each sentence should either develop the previous sentence's topic, supply evidence, state a logical consequence, introduce a qualified contrast, or set up the next move.

## 7. Variations by research design

- **Quantitative empirical**: align hypotheses, variables, statistical tests, results, and inference limits.
- **Qualitative**: align research questions, sampling, data collection, coding/analysis, themes, evidence excerpts, interpretation, and reflexive limitations.
- **Mixed methods**: show the purpose and integration point of each strand; do not present two parallel studies without explaining their joint inference.
- **Theoretical or mathematical**: align the unresolved theoretical issue, assumptions, formulation, derivation/proof, analytical or computational result, and meaning.
- **Case study or design research**: align the case/design problem, intervention or artifact, evaluation evidence, transfer limits, and contribution.

Do not infer universal reporting conventions from IMRaD alone. Treat disciplinary and journal conventions as constraints on how the functions are packaged.

## 8. Diagnostic checks

### Macro checks

- Can the full paper be summarized as one problem-to-contribution sentence?
- Does the Introduction narrow to one primary gap or a clearly related set of gaps?
- Do Methods and Results answer the exact questions promised?
- Does the Discussion begin from actual findings and widen responsibly?
- Does the Abstract mirror the main text?

### Evidence checks

- Is every major claim tied to a result, figure, table, proof, or analysis?
- Are negative and unexpected findings reported when they affect interpretation?
- Are causal claims supported by a causal design?
- Do limitations change the stated scope of conclusions?

### Sequence checks

- Does every subsection have a clear governing question?
- Does each result motivate the next result?
- Are background, method, result, and interpretation placed where readers need them?
- Could a reader understand the argument from headings, topic sentences, and figure captions alone?

### Cohesion checks

- Are key constructs named consistently?
- Does every pronoun or demonstrative have an unambiguous referent?
- Do transitions specify addition, contrast, cause, sequence, or consequence accurately?
- Does each paragraph have one controlling function and a clear exit into the next paragraph?

## 9. Compact worked example

Suppose a study claims that a new model improves early disease detection.

| Link | Example content |
|---|---|
| Gap | Existing models perform poorly on early-stage cases. |
| Objective | Test whether model X improves early-stage sensitivity without unacceptable specificity loss. |
| Method | Compare model X with prespecified baselines on an appropriate labeled cohort using sensitivity and specificity. |
| Result | Model X increases early-stage sensitivity by the reported amount while specificity remains within the prespecified bound. |
| Discussion | The result addresses the early-stage detection gap under this cohort and evaluation design, with stated generalization limits. |
| Contribution | Provide evidence for a method that improves the targeted detection setting, not a universal diagnostic solution. |

If the Results report only overall accuracy, the objective is not answered. Fix the evidence or narrow the objective; do not repair the mismatch with stronger prose.

## Knowledge basis

This reference synthesizes the user's supplied materials, *先掌握整篇论文的结构IMRD* and *先掌握整篇论文的结构与IMRaD写作逻辑*, into an operational planning and diagnostic framework. It preserves their core ideas: functional IMRaD questions, journal variation, hourglass organization, section moves, general-specific and problem-solution patterns, and cohesion through explicit logical links.
