---
name: rapid-gender-analysis
description: Produce a Rapid Gender Analysis (RGA) for a humanitarian emergency or crisis in two gated phases. Phase 1 builds a verified, cited evidence base from background documents, situation reports, and primary sources. Phase 2 turns that evidence into a standard RGA document that meets the TGLF RGA rubric and decolonial feminist (dRGA) criteria. Use this skill whenever the user asks for a rapid gender analysis, RGA, dRGA, gender brief, gender in emergencies analysis, or gendered impact assessment of an outbreak, conflict, disaster, displacement, or other crisis.
---

# Rapid Gender Analysis (RGA)

This skill automates the research and assembly work of an RGA so that the human operator can spend more time with women-led organisations, youth-led organisations, and the groups most affected by the crisis. The AI collects, verifies, and structures the evidence. The operator engages people, corrects the analysis, and moves resources and decision power toward local actors.

## When to use

- The user asks for an RGA, dRGA, gender brief, or gender analysis of an emergency.
- The user supplies sitreps, background documents, or earlier RGAs and asks what they mean for women, men, girls, and boys.
- The user asks to update an existing RGA with new evidence.

## Workflow

1. Collect the input fields. See [references/input-template.md](references/input-template.md). If a field is missing, ask once, then proceed with stated assumptions.
2. Read the governing rules. See [references/governing-rules.md](references/governing-rules.md). They apply to both phases without exception.
3. Run Phase 1: research the emergency. See [references/phase-1-research.md](references/phase-1-research.md). Save the evidence base as a separate file with full citations.
4. Pass the Phase 1 verification gate. Do not start Phase 2 until it is complete and the operator has had the chance to correct it.
5. Run Phase 2: write the RGA. See [references/phase-2-document.md](references/phase-2-document.md).
6. Apply the quality criteria and failure-mode check. See [references/quality-criteria.md](references/quality-criteria.md).
7. Apply the self-check. See [references/self-check.md](references/self-check.md). Revise until every answer is yes. Remove the self-check from the deliverable.
8. Deslop the prose. See [references/deslop-integration.md](references/deslop-integration.md).
9. Deliver the RGA as a downloadable file, together with the Phase 1 evidence file.

## Outputs

- Phase 1: `evidence-base-[emergency]-[date].md` with a source list, claim verification table, and the three biggest gaps.
- Phase 2: `rga-[emergency]-[date].md` (or DOCX or PDF on request) in the required structure.

## Hard limits

- Never fabricate data, quotations, names, dates, or methods.
- Never place a paraphrase inside quotation marks.
- Never mix inline hyperlinks and numbered references in one document.
- Never drop the four mandatory recommendations: unrestricted funding to named local women-led organisations, a formal decision-making seat, sex and age disaggregation, and a co-authored follow-up RGA.
- Never present the AI output as consultation with affected communities. It is a secondary data review until local actors co-author it.

## Operator guidance

Humans running this skill should read [references/operator-manual.md](references/operator-manual.md).
