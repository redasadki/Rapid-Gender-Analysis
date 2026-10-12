# Deslop integration

Run the deslop skill on the Phase 2 draft after the self-check passes, and again on any executive summary rewritten by the operator.

## Order

1. Run `clean_ai.py` (from `redasadki/ai-text-cleaner`) for encoding, list, and table cleanup.
2. Apply the deslop editorial rules: cut filler, break formulaic structures, remove AI tropes, active voice with human subjects, specifics, varied rhythm, no em dashes, no bold-first bullets.
3. Score directness, rhythm, trust, authenticity, and density out of 10 each. Revise below 35 of 50.

## Rules that must not be deslopped away

- Argument-carrying sentence headings stay.
- The four labelled recommendation sub-items stay as bullets.
- Exact quotations stay exact, even if the source wording is clumsy.
- Hedges that express real uncertainty about data stay. Deslop removes decorative hedging, not honest uncertainty.
- Numbered references or inline links stay in the chosen format.
