# Results writing and quantitative comparisons

## Four-component Results model

Use components selectively according to discipline and journal:

1. **Opening orientation**: revisit the aim, relevant method, overview, or visual location.
2. **Specific/key results**: report representative evidence, optionally with a local explanation.
3. **Comparisons**: compare groups, conditions, model predictions, or prior research when appropriate.
4. **Problems or limitations**: acknowledge material irregularities and give a bounded cause, consequence, or remedy.

Not every subsection needs all four. Specific, claim-relevant results are indispensable.

## The evidence sentence

A strong quantitative report combines three information functions:

1. **Location**: where the evidence appears.
2. **Technical description**: direction, magnitude, pattern, uncertainty, and test.
3. **Comment**: the restrained meaning of that result.

Example structure:

`Treatment increased the response from 12.4 to 18.1 units relative to control (absolute difference, 5.7 units; Fig. 3B), supporting a positive treatment effect under the tested condition.`

If the statistical evidence is unavailable, remove the inferential claim or mark it as descriptive.

## Comparison math

Let `A` be the reference/baseline and `B` the comparison.

| Quantity | Formula | Wording |
|---|---|---|
| Absolute difference | `B - A` | `5.7 units higher` |
| Relative change | `(B - A) / A x 100%` | `46% higher than baseline` |
| Percentage-point change | `B% - A%` | `8 percentage points higher` |
| Ratio | `B / A` | `1.46 times the baseline value` |

Rules:

- Name the reference group explicitly.
- Do not calculate relative change from a zero baseline.
- Distinguish `increased by 20%` from `increased to 20%`.
- Distinguish percent from percentage points.
- When both direction and exact values matter, report values first and derived comparison second.
- Avoid "times higher" when it could be read ambiguously; use "times as high as" or a ratio.

## Trend description

Describe only visible or modeled features that matter to the claim:

- direction: increased, decreased, remained stable;
- shape: linear, nonlinear, exponential, U-shaped, biphasic;
- timing: early, delayed, peaked at, plateaued after;
- variability: narrow/wide dispersion, outliers, subgroup separation;
- relationship: positive/negative association, threshold, saturation;
- uncertainty: overlapping intervals, imprecise estimate, wide confidence interval.

Avoid value-by-value narration. Select endpoints, extrema, inflection points, thresholds, and comparisons that answer the research question.

## Statistical reporting

- Give the estimate or descriptive values before or alongside the p-value.
- Include units, effect size, and confidence interval when supplied and relevant.
- State the comparison that a p-value belongs to.
- Preserve the source's exact p-value or threshold convention; never infer a p-value from asterisks unless the legend defines them.
- Do not equate `p > 0.05` with equivalence or no effect. Write `did not reach statistical significance` and report the estimate/interval.
- Do not claim groups differ merely because one is significant and the other is not; require a direct between-group comparison.
- Identify whether `n` refers to participants, biological replicates, technical replicates, images, cells, or measurements.

## Interpretation strength

Use a verb aligned with the design:

- direct description: `shows`, `was`, `increased`, `correlated`;
- cautious inference: `suggests`, `supports`, `is consistent with`;
- association: `was associated with`, `covaried with`;
- strong causal language: use only for designs and analyses that justify it.

In separate Results, keep the comment local to the experiment. In combined Results and Discussion, connect to mechanisms or literature but label alternatives and uncertainty.

## Problems and irregularities

Acknowledge a material problem when it affects interpretation. Use this order:

1. state the observed issue precisely;
2. identify the evidence-bounded source or condition;
3. state the consequence for interpretation;
4. give a robustness check, remedy, or future test when available.

Avoid hiding weaknesses or using vague euphemisms. Also avoid magnifying a localized technical constraint into a failure of the entire study. If similar issues are documented in prior work, cite them without using them as an excuse.

## Paragraph logic

- Use one central finding per paragraph.
- Start with the question or headline result, not a list of procedures.
- Present comparisons in a stable order: control before treatment, low before high dose, or chronological order.
- Use subheadings when substantial information answers distinct aims.
- End with a bounded takeaway or a transition to the next experiment.
