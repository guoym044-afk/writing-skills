# Citation and attribution audit rubric

Use this rubric to make findings reproducible and appropriately cautious.

## Contents

1. Status and severity
2. Finding codes
3. Claim-support test
4. Language-independence test
5. Required report structure
6. Correction patterns

## 1. Status and severity

Assign one status to each audited unit:

- `PASS`: inspected evidence supports the unit and no material citation or attribution problem was found.
- `PARTIAL`: evidence supports only part of the unit or supports a narrower/weaker version.
- `FAIL`: inspected evidence contradicts, fails to support, or is incorrectly credited.
- `WARN`: likely problem or style/clarity risk that does not establish failure.
- `UNVERIFIABLE`: required original source, page, figure, table, or metadata was unavailable or unreadable.
- `N/A`: the check does not apply.

Assign severity by consequence:

- `Critical`: fabricated or nonexistent source; materially false quotation; pervasive unmarked copying; attribution that reverses or seriously changes scientific meaning.
- `Major`: unsupported central claim; wrong evidence producer; primary/secondary source misuse for key data; material overstatement; missing citation for a central borrowed claim.
- `Moderate`: ambiguous citation scope; partial support; patchwriting; incorrect locator; citation attached to the wrong clause; substantial reference mismatch.
- `Minor`: outlet-style inconsistency, punctuation, ordering, or metadata detail that does not change evidentiary meaning.

Do not inflate severity solely because a sentence is important. Base severity on the error and its effect on traceability, credit, or scientific meaning.

## 2. Finding codes

### Citation necessity and placement

- `CIT-01` Missing citation for a source-dependent claim
- `CIT-02` Citation placed too late, too early, or outside the supported claim boundary
- `CIT-03` One citation ambiguously scopes multiple sentences or clauses
- `CIT-04` Citation cluster does not show which source supports which claim
- `CIT-05` Unnecessary or irrelevant citation padding

### Claim support

- `SUP-01` Cited source does not support the claim
- `SUP-02` Source supports only part of the claim
- `SUP-03` Claim overstates scope, population, conditions, direction, magnitude, or certainty
- `SUP-04` Claim conflicts with source evidence
- `SUP-05` Evidence cannot be verified from the available material

### Attribution

- `ATT-01` Wrong source or researchers credited
- `ATT-02` Information relayed from another citation is attributed to the current paper
- `ATT-03` Secondary source presented as producer of specific primary evidence
- `ATT-04` Primary article cited for background it attributes elsewhere
- `ATT-05` Writer's inference is presented as the source's conclusion, or vice versa
- `ATT-06` Reporting verb misstates the source's action or certainty

### Source language

- `LAN-01` Unmarked verbatim or near-verbatim copying
- `LAN-02` Patchwriting: syntax/order retained with superficial word changes
- `LAN-03` Sentence-mining: isolated source sentence rewritten without synthesis
- `LAN-04` Direct quotation missing quotation treatment, citation, or locator
- `LAN-05` Summary/paraphrase materially changes source meaning
- `LAN-06` Acceptable technical overlap but citation or explanation should clarify necessity

### Reference integrity and style

- `REF-01` In-text citation missing from reference list
- `REF-02` Reference-list entry never cited in text
- `REF-03` Bibliographic metadata disagrees with original record
- `REF-04` Duplicate references or inconsistent author/year labels
- `REF-05` Mixed or incorrect citation system for the target outlet
- `REF-06` Page, table, figure, DOI, URL, or publication-status error

## 3. Claim-support test

For each claim, compare:

| Dimension | Question |
|---|---|
| Proposition | Does the source state or demonstrate the same core relationship? |
| Evidence owner | Did this source generate the evidence or cite another work? |
| Population/object | Does the claim concern the same participants, material, system, dataset, or setting? |
| Conditions | Are time, place, dose, method, model, and experimental constraints preserved? |
| Direction | Is increase/decrease, association/no association, benefit/harm, or causality preserved? |
| Magnitude | Are numbers, units, comparisons, and effect sizes accurate? |
| Certainty | Does wording preserve uncertainty and limitations? |
| Generalization | Has a specific result been expanded into a universal or field-wide claim? |
| Location | Can the supporting page, section, figure, table, or passage be identified? |

Use `PARTIAL` if any material dimension is supported only after narrowing. Use `FAIL` when the difference changes meaning.

## 4. Language-independence test

Compare manuscript and source across four dimensions:

1. distinctive phrase overlap;
2. grammatical structure;
3. order of ideas or details;
4. selection of one isolated sentence versus synthesis of a meaningful source unit.

Interpretation:

- High overlap in all four: likely `LAN-01` or `LAN-02`.
- Different words but same syntax/order: `LAN-02`.
- One sentence minimally reworked without larger understanding: `LAN-03`.
- Independent structure and selective synthesis with preserved meaning: acceptable paraphrase/summary.
- Exact necessary terminology or data alone: normally acceptable, but keep citation and verify accuracy.

Never report an automated similarity percentage as proof of plagiarism. Identify the observable overlap and the required correction.

## 5. Required report structure

### Overall verdict

State audit depth, manuscript coverage, source availability, and the largest risks in two to five sentences.

### Finding table

Use these columns unless the user asks for another format:

| ID | Manuscript location | Claim/cited wording | Citation/source | Status | Severity | Code | Evidence and source location | Recommended fix |
|---|---|---|---|---|---|---|---|---|

Quote only the minimum text needed to identify the issue. If the source is copyrighted, prefer a short excerpt plus paraphrased evidence.

### Coverage summary

Report:

- claim units checked;
- in-text citations checked;
- original sources inspected;
- sources missing or limited to abstracts/snippets;
- reference-list entries checked;
- counts by status and severity;
- remaining `UNVERIFIABLE` items.

### Corrected text

When requested, give a clean revision plus a brief mapping from changes to finding IDs. Preserve the user's terminology and voice where scientifically valid.

## 6. Correction patterns

### Overbroad citation scope

Split the sentence or paragraph so each citation immediately follows the supported proposition.

### Partial support

Narrow the population, condition, effect, or certainty to the verified evidence. Do not solve partial support by adding an unverified citation.

### Relay citation

Locate and cite the original source. If it is unavailable and indirect citation is permitted, name both relationships transparently according to the target style.

### Patchwriting or sentence-mining

Return to a larger source unit, take concept notes, hide the original wording, and write a concise synthesis from understanding. Reopen the source to verify meaning and necessary terminology.

### Review used for exact data

Replace it with the primary study for exact findings, or reframe the sentence as a review-level synthesis if that is what the review actually supports.

### Unverifiable source

Retain a visible `UNVERIFIABLE` marker in the audit. Request the full source or reduce the conclusion to checks that do not require content access.
