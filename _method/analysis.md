---
title: "Analysis"
slug: analysis
description: "Analytical tradecraft, source reliability grading, and how AI-assisted collection is used, with mandatory analyst verification on every output."
crumbs:
  - title: "Method"
    url: /method/
  - title: "Analysis"
    url: /method/analysis/
---
### Raw findings are not a report.

Every source Greyline uses is graded for reliability before a finding built on it is written up. A single anonymous forum post is treated differently from a corroborated public record, and the report says so explicitly rather than presenting both with equal confidence.

This is not a stylistic choice. It is a structural discipline.

<hr class="gold-rule">

### Source Reliability Grading

Greyline applies a modified version of the **NATO Admiralty Code** to every source used in an engagement. Each source is scored on two axes:

| Axis | Question | Grades |
|---|---|---|
| **Reliability** | How trustworthy is the source itself? | A: Completely reliable. B: Usually reliable. C: Fairly reliable. D: Not usually reliable. E: Unreliable. F: Reliability cannot be judged. |
| **Credibility** | How likely is the information to be true? | 1: Confirmed. 2: Probably true. 3: Possibly true. 4: Doubtful. 5: Improbable. 6: Truth cannot be judged. |

A source graded **B2** (usually reliable, probably true) is treated differently in the report from a source graded **D3** (not usually reliable, possibly true). The grade is recorded in the analyst's working notes and, where material to the conclusion, disclosed in the report itself.

This means a client can read a Greyline report and see not just *what* we found, but *how confident we are in the foundation we built it on*.

<hr class="gold-rule">

### The Analyst as Gatekeeper

Where AI-assisted tools are used, for pattern-matching across large datasets, flagging candidate matches in a named-entity search, or surfacing connections in network data, **every output is verified by a named analyst before it enters a report.**

Tooling accelerates collection. It does not sign off a finding.

This distinction matters most in the **AI & Synthetic Intelligence** capability, where detection tooling is probabilistic by nature. Findings there are worded as *consistent with*, not *proof of*, a given pattern. The analyst's judgement, trained, contextual, accountable, sits between the tool and the client.

<hr class="gold-rule">

### Finding Classification: Three Categories, Not Two

Your report will contain findings at one of three classification levels:

**Corroborated Finding**
Sourced, dated, and cross-referenced against at least one independent source wherever the underlying material allows. Stated as fact in the report, with full source citation and reliability grading.

**Unverified Lead**
Single-source, flagged, dated, not yet corroborated. Presented in an appendix or working-notes section, never as a concluded fact. Included only where it may assist onward investigation or where the client has specifically instructed us to report leads as well as findings.

**Analyst Assessment**
The analyst's reasoned judgement, based on corroborated findings, as to what the picture means. Clearly labelled as assessment, with the underlying evidence referenced. The client can see the line between what we know and what we infer.

We do not present the three as equivalent.

<hr class="gold-rule">

### Analytical Tradecraft in Practice

Beyond source grading, Greyline analysts apply the following disciplines as standard:

- **Chronological reconstruction**: Events are mapped in time order before causal inference is attempted. Cause and effect are not assumed.
- **Competing hypothesis testing**: The analyst is required to generate and test at least one alternative explanation for any significant finding before it is reported.
- **Source triangulation**: No significant finding rests on a single source type. Where possible, open-source material is cross-checked against documentary, technical, or behavioural evidence.
- **Red team review**: For litigation-aligned and high-stakes engagements, a second analyst reviews the work product before delivery, specifically tasked with finding weaknesses in the reasoning or evidence base.

<hr class="gold-rule">

### What This Means for the Client

You receive a report where:
- Every significant finding is traceable to a source you can inspect.
- The reliability of that source is disclosed.
- Inference is separated from fact.
- A named individual has taken personal accountability for the analytical judgements within.

This is the standard against which we measure our own work. It is not negotiable, and it does not vary by engagement size.
