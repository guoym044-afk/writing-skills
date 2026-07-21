# Methods guide

## Purpose and default structure

Make the section satisfy three tests:

1. a qualified reader can understand what was done;
2. another researcher can reproduce the work with the stated materials, conditions, and decisions;
3. a reviewer can judge whether the design and analysis support the results.

Use four adaptable components:

1. **Overview/design**: principal activity, setting, methodological approach, and non-obvious rationale.
2. **Materials/subjects/data**: what or who was studied and where each resource came from.
3. **Procedures**: what happened, in what sequence, under which conditions, and with which controls.
4. **Data analysis**: how raw observations became reported outcomes and how validity or uncertainty was assessed.

Split multiple designs or experiments into clearly named subsections. Follow the target journal's title and order when it uses alternatives such as Materials and Methods, Methodology, Experimental Procedures, Models, or Simulations.

## Reproducibility content

Include the details that could change replication or interpretation.

### Human or animal studies

- design, setting, recruitment or sampling frame, dates when relevant;
- eligibility, exclusions, allocation, groups, sample size and its basis when available;
- participant/sample characteristics needed to interpret the study;
- intervention or exposure, timing, dose, administration, controls, randomization, and blinding;
- outcome definitions and measurement instruments;
- ethics approval, consent, registration, and welfare procedures when applicable.

### Laboratory or engineering experiments

- material identity, grade/purity, quantity, source, preparation, and storage when consequential;
- equipment type/model/manufacturer when performance depends on it;
- geometry, calibration, temperature, pressure, humidity, duration, rate, voltage, load, or other critical conditions;
- chronological operations, repetitions, controls, and stopping criteria;
- sample characterization or measurement settings.

Use generic names by default. Add trade names only when needed for reproducibility. Put compact specifications in parentheses and define abbreviations at first mention. Use a table when parameter density would make prose unreadable.

### Computational, simulation, or algorithm studies

- data source and version, preprocessing, splits, leakage controls, and inclusion/exclusion rules;
- algorithm/model definition, assumptions, critical equations, parameters, initialization, and stopping rules;
- baselines, hardware only when relevant, software/library names and versions, random seeds, and repetitions;
- evaluation metrics and how they were calculated.

Explain only equations essential to reproduce or understand the method. Define symbols and assumptions. Use present tense for mathematical relationships treated as general facts; use past tense for the implementation actually executed.

### Surveys and qualitative studies

- population and sampling, instrument development or provenance, administration, response handling;
- interview/observation procedure, recording/transcription, coding framework, coder training, disagreement resolution;
- category derivation, saturation or stopping logic, reflexivity, and trustworthiness checks when applicable.

## Established, modified, and new methods

- **Established and familiar**: name the method and cite the authoritative source; avoid reprinting standard details.
- **Established but modified**: cite the source and describe every modification that could affect the result.
- **New or uncommon**: give a precise, concise account sufficient for replication and validation.

Never use a citation to hide a critical deviation or parameter choice.

## Explain methodological choices

Supply a rationale when a reasonable reviewer could ask "why this choice?" Link the choice to bias control, measurement validity, comparability, feasibility, resolution, robustness, or a study objective. Keep the rationale local to the decision.

Useful logic patterns:

- To reduce `[source of bias]`, we `[action]`.
- We selected `[method]` because it permits `[relevant capability]`.
- We adapted `[source method]` to accommodate `[study-specific constraint]`.
- `[Condition]` was held constant so that `[comparison]` reflected `[target factor]`.

Do not justify a choice with vague claims such as "better" or "more accurate" unless evidence or a concrete criterion follows.

## Data analysis content

Describe:

- preprocessing, quality control, missing data, exclusions, transformations, normalization, and derived variables;
- unit of analysis, independent replicate definition, sample size for each analysis, and aggregation;
- statistical or qualitative method and why an unusual method was appropriate;
- assumptions, multiple-comparison handling, confidence/credible intervals, significance threshold, effect-size calculation;
- software and version when relevant.

Ordinary methods may be named briefly. Cite advanced, unusual, or externally defined methods. Distinguish exploratory from confirmatory analysis if the source information supports that distinction.

## Language and organization

- Use past tense for the study's completed actions.
- Use present perfect for relevant prior practice only when needed to contrast it with the current work.
- Mix active and passive voice deliberately. Use active voice to clarify author responsibility; use passive voice when the procedure or material is the natural focus.
- Make sequence explicit where order affects replication: before, after, subsequently, simultaneously, or upon completion.
- Use numerals, SI units, spacing, and symbols according to the journal. Keep unit and decimal conventions consistent.
- Prefer exact operational verbs over vague verbs such as "did," "handled," or "processed."

## Common failure patterns

Reject or repair Methods prose that:

- omits sample counts, sampling logic, critical conditions, controls, analysis, or replicate definitions;
- provides exhaustive routine detail while omitting consequential decisions;
- reports results or conclusions inside the procedure description;
- confuses biological/technical replicates or participant/sample units;
- changes tense or terminology in a way that obscures what the authors actually did;
- names a method as standard when it was materially altered;
- describes software or equipment without enough information to identify the reproducible configuration.

## Paragraph scaffold

For each subsection, draft in this order when it improves clarity:

1. purpose or overview;
2. materials/subjects and critical settings;
3. chronological procedure;
4. controls and quality checks;
5. analysis or output feeding the next stage.

Avoid forcing this scaffold when a discipline uses a stronger convention.

## Knowledge basis

This guide operationalizes the Methods expert knowledge in the user-supplied PDFs `学习Method和Results（2）.pdf` (Chapter 5, "How to Write the Method") and `学习Method和Results.pdf` (the concise Methods overview). It preserves their four-part model, reproducibility standard, method-selection rationale, material and condition reporting, data-analysis requirements, tense/voice guidance, and reviewer-oriented completeness checks without redistributing the source PDFs.
