# Operator manual: running the Rapid Gender Analysis skill

## What the skill does and what you do

The skill does the desk work: it finds sources, checks dates, sorts evidence into the RGA structure, flags gaps, and writes a first draft that meets the TGLF RGA rubric and decolonial (dRGA) criteria. You do the work that a machine cannot do: you talk to women-led organisations, youth-led organisations, and affected groups, you judge what matters, and you move money, seats, and credit to local actors.

Treat every AI output as a draft for your correction. The skill is fast and thorough, but it only knows what is written down and online. The people living the crisis know more.

## Time budget

| Task | Without the skill | With the skill |
|---|---|---|
| Source search and reading | 1 to 2 days | 1 to 2 hours of review |
| Structuring and drafting | 1 to 2 days | 1 to 2 hours of correction |
| Engagement with local organisations | Often squeezed out | The main use of your freed time |

These figures are planning estimates, not measured results. Record your own times to improve them.

## Before you start

1. Install the skill folder in your AI tool (for example the skills directory of Claude, or a project knowledge folder in another assistant). The folder must contain `SKILL.md` and the `references` folder.
2. Gather documents: sitreps, cluster updates, earlier RGAs, government statements, and anything local partners have shared.
3. Ask local partners for consent before you upload anything they shared. Agree how they want to be credited.
4. Fill in the input template in `references/input-template.md`.

## Step 1: start Phase 1

Paste the filled template and attach documents. Say: "Run Phase 1 of the rapid-gender-analysis skill."

Expect an evidence file with sections 1.1 to 1.7, a claim verification table, a source list, and the three biggest gaps.

## Step 2: check the verification gate

Spend your review time on these checks:

- Open five sources at random. Does each say what the evidence file claims, on the stated date?
- Look at every "single-source" and "unverified" claim. Drop it, confirm it, or keep it with its label.
- Check section 1.5. Are the local and women-led organisations named correctly? Who is missing?
- Read the three gaps. These are your questions for local partners.

## Step 3: engage local actors with the gaps

Take the gaps to women-led organisations and other local groups by the channels they already use: WhatsApp, voice notes, phone calls. Ask what they see. Do not run an extractive survey. Record their answers with consent and their preferred credit. Ask whether they want to be named authors.

Where possible, move resources at the same time. The dRGA approach puts unrestricted funding to pre-identified partners ahead of assessment.

## Step 4: correct and run Phase 2

Give the skill your corrections in plain language, for example:

- "Drop claim 14. The source is a repost."
- "Add these notes from [organisation], credited as co-authors, with their consent."
- "The audience is the Health Cluster. Distribution is PDF."

Then say: "Run Phase 2 of the rapid-gender-analysis skill using the corrected evidence file."

## Step 5: review the draft

| Check | What good looks like |
|---|---|
| Opening | One institutional statement, then the executive summary |
| First sentence | The finding that should change a decision |
| Headings | Sentences that carry the argument |
| Figures | Dated, sourced, sex and age split or gap stated |
| Women and girls | Shown as responders and analysts, not only as victims |
| Recommendations | Four labelled sub-items each, four mandatory items present |
| Limitations | After recommendations, all six points covered |
| References | Complete, visible URLs, one citation format only |

Ask the skill to rerun the self-check if anything fails.

## Step 6: disseminate and iterate

- Share the international version through coordination channels.
- Support local organisations to produce the community version in the local language. Pay for that work.
- Schedule the co-authored follow-up RGA named in the recommendations.

## Troubleshooting

| Problem | Fix |
|---|---|
| The skill invents a figure or quotation | Point to it, ask for the source, and remove it if none exists. Report it as a failure |
| Sources are old | Give a date window, for example "sources published since [date]" |
| Recommendations are generic | Name the organisations and coordination bodies, then rerun Phase 2 |
| Culture is blamed | Ask the skill to apply the structural analysis criterion to that section |
| Draft is too long | Give a word count in CONSTRAINTS |
| The tool ignores the skill | Name the skill explicitly in your prompt and confirm the references folder uploaded |

## What the skill cannot do

- It cannot consult affected people. Only you and local partners can.
- It cannot verify what is not published.
- It cannot transfer resources. Its recommendations only matter if someone acts on them.
