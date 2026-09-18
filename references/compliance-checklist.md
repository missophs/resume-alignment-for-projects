# Recruiter Audit, Red Flag Audit, Pre-Delivery Checklist

## Recruiter 10-second audit — run before every delivery
1. What stands out immediately? Role scope, metrics, and company names must be visible without reading closely.
2. What's forgettable? Any bullet that could describe 500 other HR executives gets rewritten.
3. Does it communicate value fast enough? The first 3 bullets of each role are its highest-impact outcomes.
4. Layout check: role headers show scope (employee count, budget, dates) at a glance; metrics are visible in the first scan.
5. First-impression verdict: does this make Melissa look experienced and worth interviewing, or average among hundreds? If "average," rewrite the opening until it isn't.

**7-second test:** scope visible in role headers, metrics visible in the first scan, most relevant role listed first, S1 stops a recruiter cold.

## Red flag audit — run before delivery
- Generic summary that could fit any HR executive → rewrite
- Bullets describing the role instead of proving an outcome → rewrite
- A metric with no business context (what did it mean to the P&L?) → add the consequence
- HR process language that signals operational rather than executive thinking → remove
- The same achievement in two roles → consolidate
- Strongest outcome buried mid-role instead of leading → reorder
- Corporate language in a startup role, or startup language in an enterprise role → recalibrate

Run a self-audit after the first full version is written: find every weakness, rewrite it, then hand Melissa the corrected version as final — not the first draft.

## Pre-delivery checklist

**Process gates**
- Target level confirmed before writing; every summary and bullet re-derived from scratch at that level
- Think-before-answering complete: level identified, 3 JD outcomes named, story mapped to each
- Blind-spot audit run
- Cross-role story audit complete: every role in Professional Experience tells a distinct story
- Cross-role redundancy gate complete (story audit, Sig Results paraphrase check, role-summary echo check)
- JD outcome-mapping audit complete: every primary JD outcome has a bullet with explicit proof
- Mistake-finder and critique passes complete
- Council Condition B complete: all 5 advisors in parallel, peer review run, chairman synthesis with labeled rewrites shown in chat — applies to every mode, not just the full rewrite
- Humanize protocol complete, with visible chat output
- Eval-self scores all 8+ (see below)
- Recruiter and red-flag audits complete
- **Section checklist confirmed** (see Step 8 in `SKILL.md`): Summary, Signature Results, Core Competencies, and every role in Professional Experience are all present in the draft — nothing silently dropped

**Document and font**
- Raw half-point size values (body=20, name=24, subhead=22, contact=18), no pt() multiplier
- Page count 1-3 pages
- Font: Arial throughout

**Level and framing**
- Summary register matches target level
- "Owned"/"Took ownership of" absent from PP/HRBP summaries and role summaries
- Board-advisory bullets removed from Cprime for PP/HRBP
- "Exit timeline," "board confidence," "enabling board" absent below VP
- Budget framing matches the target level's table

**Summary**
- Exactly 3 sentences, one paragraph
- S1 opens with the correct-level verb, no "by [gerund]" construction
- S2 under 20 words, scope statement
- S3: concrete headline outcomes tied to the JD
- S1's verb doesn't repeat as any bullet opener

**XYZ and bullets**
- Every bullet has explicit X, Y, and a named Z (semicolon form)
- All bullet openers unique across the whole resume
- Every bullet under 280 characters, no trailing period
- Zero hits on "by [gerund]" and interior banned words
- No soft tails

**Role summaries**
- Word counts verified, all under 22 words
- No overlap with the scope line or bullet 1
- No banned openers, no "crisis," no fractured construction, no comma-gerund chain

**Facts and metrics**
- Every number traces to the source resume
- 39% not used anywhere
- Cprime always "tech consulting firm"/"tech consulting and SaaS firm," no tech-stack inflation, no PEO claim outside Concierge
- No metric at 3+ appearances; "zero regulatory violations" at 2 max
- No achievement duplicated across roles; the Signature Results redundancy table in `bullet-formula-and-verbs.md` has been run in chat and every row shows Pass — not just eyeballed for near-clones
- Metric cap re-checked after keyword patches

**Keywords**
- Full JD extraction complete, all three grep passes run
- Every missing keyword either integrated or confirmed as a gap with Melissa — no unresolved gaps shipped
- Four-column keyword change log ready

**Document**
- .docx validated (only if one was requested)
- File named per the convention, saved to `/mnt/user-data/outputs/`

## Eval-self gate
Before delivering, rate the draft 1-10 on: accuracy to source, clarity, keyword coverage, verb uniqueness, human voice (Mode 2 adds level-match to JD). Any score below 8 gets fixed and re-scored. Nothing ships below 8 across the board.

## Compliance sweep — run against the built document
Extract text via zipfile/XML from the .docx and strip tags for ground truth, then confirm:
- Em dashes (Unicode + ASCII), en dashes, arrows: zero
- Full banned-word list: zero hits
- `by \w+ing` and `through \w+ing`: zero hits
- "helped," "supported," "contributed" anywhere in bullet text: zero
- All bullet openers unique, confirmed programmatically
- S1's verb doesn't appear among the bullet openers
- Role-summary word counts verified in code, all under 22
- Every bullet under 280 characters, verified programmatically
- No periods at bullet ends
- Metric cap holds; "zero regulatory violations" at 2 max
- Three-pass keyword audit complete, re-checked after patches
- Recruiter and red-flag audits complete
- Page count 1-3 pages
- ATS rescore at 92+ before delivery, when the ATS workflow is in play
