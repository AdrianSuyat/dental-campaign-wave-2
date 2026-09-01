# EOD format (house style)

Adrian's end-of-day note. Use this shape every day, no exceptions, unless he says
otherwise.

## Rules

1. **Title line:** `EOD — <Weekday>, <D Month YYYY>` (em dash, day name, no leading
   zero on the date). Example: `EOD — Tuesday, 1 September 2026`.
2. **One flat bulleted list.** No section headers, no sub-bullets, no tables, no
   bold inside bullets, no closing recommendation block.
3. **Every bullet is a complete sentence in past tense, opening with a verb.**
   Typical verbs: Re-checked, Worked on, Resolved, Corrected, Recorded, Fixed,
   Created, Installed, Carried forward.
4. **Bullet order:**
   - Verification bullet first — every re-checked figure in one sentence.
   - In-progress work.
   - Resolved items and corrections to earlier notes.
   - Admin, memory notes, installs.
   - Any other work done that day.
   - Carry-forward open items — always the last bullet, one sentence,
     comma-separated.
5. **Numbers as digits:** `9 emails plus 3 conditional alternates`, not "nine".
6. **Backticks for anything machine-named:** fields (`business_name`,
   `solv_line`), files (`HOW-TO-IMPORT.md`), datasets (`DENTAL-FINAL-612`).
7. **Title case for verticals and systems:** PIM, Chiro, Opto, Dental Wave 3,
   Sprint 1 Round 2, Optometry Attempt 3.
8. **Figures are quoted, never estimated.** Only include a number that has been
   checked against source. If it hasn't been checked, say so or leave it out.
9. **Corrections to earlier notes get their own bullet**, stating what was wrong,
   the scope it was wrong in, and the consequence.

## Canonical example — 1 September 2026

EOD — Tuesday, 1 September 2026

* Re-checked every figure in the output against source: 128 bodies, 55 bare booking links, 16 asset placeholders, 5 Google Meet promises, 91 handlers with 73 empty trigger phrases, `business_name` present in all three PIM imports and absent from both Chiro/Opto finals, backup present, and the enforcement hook wired at lines 229 and 287.
* Worked on Wave 3, drafted and awaiting a ruling: 9 emails plus 3 conditional alternates, with the gate table.
* Resolved Friday's `business_name` blocker at the source level. The field is present in all three PIM import files, and `HOW-TO-IMPORT.md` says to map it. Importing from there avoids any body changes. The field remains absent from the Chiro and Opto finals, so the failure is real but avoidable.
* Corrected Friday's note: the swap-to-name option is not a provable no-op on `DENTAL-FINAL-612`. The two fields differ on 156 of 612 rows, and neither is clean, so a find-and-replace would be wrong 156 times.
* Recorded the 128-body read, merge-field audit, skill installation, and standup as seven memory notes.
* Worked with Lem on setting up the Optometry Attempt 3 automation.
* Created new drafts for the Dental Wave 3 email sequences.
* Fixed and installed Claude Terminal.
* Carried forward Friday's open items plus today's additions: 91 missing handler subjects, Coty's audit-calendar link across 55 bodies, the stale 18 August export, Google Meet promise, `solv_line`, three changed-address contacts, and Sprint 1 Round 2 now two weeks unanswered.
