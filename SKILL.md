---
name: resume-jd-aligner
description: Tailors Melissa Weiss's HR-executive resume (DHW, Cprime, Concierge Movement, and WPP roles, plus Prior Experience, Education, and Certifications) to a specific job description. Runs a gap analysis, ATS keyword scan, full XYZ-formula rewrite, LLM Council review, and a humanize pass. Triggers on "tailor my resume for this job", "here's a JD", "apply to this role", "resume review", "ATS score", "6-second test", "why am I getting rejected", or any pasted job posting Melissa wants to target.
---

# Resume to Job Description Aligner

Read the child files in `references/` at the step that calls for them. Do not load all of them upfront — read each one when its step arrives, so context stays focused on the step in front of you.

## Step 0 — Load facts
Read `references/facts-and-banned-words.md` and `references/scope-resolution.md`. These never change between JDs. `scope-resolution.md` explains why Professional Experience has four roles plus Education and Certifications, and why Prior Experience is deliberately excluded — don't apply an older three-role assumption, and don't add Prior Experience back based on the source resume.

## Step 1 — Think before writing
Identify: target level (CPO/CHRO, VP/Head, Sr. People Partner/HRBP, Director HRBP), the JD's 3 primary hiring outcomes, which of Melissa's four roles maps to each, and the biggest framing risk for this specific application.

## Step 2 — Gap analysis
Four-column table: JD Requires | Resume Has | Status | Action. Add ATS keyword buckets A/B/C, the 3 weakest bullets with rewrites, and an overall fit verdict. Read `references/keyword-and-ats-workflow.md` for the extraction and grep passes.

## Step 3 — Blind spot audit
State assumptions about keyword coverage and level fit. Name how this resume could fail at the 6-second stage even if Step 2 looks clean.

## Step 4 — Council, round 1
Read `references/council-protocol.md`. Run the full 6-step protocol in chat before writing a single bullet. Label every bullet by role code (SR for Signature Results, plus one prefix per role: DH, CP, CO, WP) even before they're drafted, so the council and the final compliance sweep use the same codes throughout.

## Step 5 — Confirm level and framing
Read `references/document-standards-and-modes.md` for the level-conditional framing table (budget language by level). Then read exactly one of these two files, based on the confirmed level, and only that one:
- CPO/CHRO or VP People/Head of HR → `references/senior-register-bullets-dash-verbs-lead.md`
- Sr. People Partner/HRBP or Director HRBP → `references/junior-register-partnered-drove.md`

Re-derive every role summary and bullet from scratch at the confirmed level. Never carry bullets forward from a prior-level draft.

## Step 6 — Write the roles, one at a time, in this order
1. Read `references/role-cprime.md`, write Cprime (6 bullets).
2. Read `references/role-dhw.md`, write DHW (5-6 bullets).
3. Read `references/role-concierge.md`, write Concierge Movement (5 bullets).
4. Read `references/role-wpp.md`, write WPP (5 bullets).
5. Read `references/education-and-credentials.md`, write Education and Certifications and Professional Associations. Do not write a Prior Experience section.

Order the four Professional Experience roles in the delivered resume by JD relevance, not by this writing order. Education and Certifications stay in their fixed positions at the end regardless of JD. Read `references/bullet-formula-and-verbs.md` before writing any bullet — every bullet needs an explicit X, Y, and named Z, and every claim must trace to a verified accomplishment in the relevant role file. Never invent a fact, metric, or outcome not already in a role file — ask Melissa if a JD needs something the role files don't support.

## Step 7 — Signature Results and Core Competencies
5 context-free bullets, JD-ordered, drawing from all four roles without restating any role bullet's wording or angle (see the anti-redundancy rules in `references/bullet-formula-and-verbs.md`). Before moving to Step 8, run that file's Signature Results redundancy table in chat — this is a required mechanism check with a Pass/Fail per bullet, not an assumption that Step 7's instructions were followed.

## Step 8 — Mandatory section checklist
Before anything else, confirm the draft contains all of: Summary, Signature Results (5 bullets), Core Competencies, Professional Experience → DHW, → Cprime, → Concierge Movement, → WPP, Education, Certifications and Professional Associations. Confirm there is no Prior Experience section. Anything missing gets written now. This step exists because a role has been silently dropped before — treat it as non-negotiable, not a formality.

## Step 9 — Critique pass + Council, round 2
Flag every bullet that describes a task instead of an outcome, has a weak/circular Z-clause, or could be written by 500 other HR executives. Re-run `references/council-protocol.md` Condition B against the flagged bullets. Apply every chairman fix.

## Step 10 — Humanize
Read `references/humanize-protocol.md`. Run all 6 passes. Must produce visible output in chat.

## Step 11 — Compliance sweep
Read `references/compliance-checklist.md`. Run every grep and every checklist item, including the Step 8 section checklist again. Any failure gets fixed and re-checked before delivery, not noted as a caveat.

## Step 12 — Deliver
Present the resume, the keyword change log (four columns: Added | Already Covered | Honest Gaps | Asked and Confirmed), and a brief summary of what changed. No soft asks, no closing pitch.

## Operating modes
Not every request needs all 12 steps. Read `references/document-standards-and-modes.md` for Mode 1 (review only), Mode 2 (full tailored rewrite — all 12 steps), Mode 3 (recruiter 6-second review), Mode 4 (rejection diagnosis). Match the request to a mode before starting Step 0.
