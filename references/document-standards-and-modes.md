# Level Framing, Positioning, Document Standards, Operating Modes

## Level-conditional framing
Identify the target level before writing a single word. Every level change means a full re-derivation of every role bullet from scratch — never carry bullets forward from a prior-level draft with light edits.

| Target Level | Summary S1 register |
|---|---|
| CPO / CHRO | Outcome ownership ("Reversed," "Delivered 38%") |
| VP People / Head of HR | Function leadership ("Led," "Built," "Delivered") |
| Sr. People Partner / HRBP | Program delivery ("Delivered [programs] that [outcomes]") |
| Director HRBP | Program delivery ("Delivered," "Drove") |

For the exact role summary openers and bullet-construction rules at each level, read exactly one of `senior-register-bullets-dash-verbs-lead.md` (CPO/CHRO, VP/Head) or `junior-register-partnered-drove.md` (Sr. People Partner/HRBP, Director HRBP) — the openers used to be a third column in this table and a second file said the same thing; that's now consolidated into those two files only.

**Budget framing by level:**
| Target Level | Budget language |
|---|---|
| CPO / CHRO | "Owned $9M People budget" — full ownership |
| VP / Head | "Operated within a $9M People budget" — stewardship |
| Director HRBP | "Worked within a $9M People function budget" — context only |
| HRBP / People Partner | Remove budget figures from bullets and summary entirely; scope line only |

**Additional rules for HRBP/PP targets:** remove Cprime bullets claiming board advisory, acquisition strategy ownership, or exit-shaping. Coaching gets a standalone bullet per relevant role with a metric attached. Fast-paced/high-growth language should show up across multiple roles, not just one.

**Additional rules for Director HRBP targets:** budget figures may stay in the scope line but never framed as direct bullet ownership. Board advisory / PE sponsor language banned — use "senior leadership" or "executive stakeholders." Acquisition-strategy / exit-shaping language banned — use "organizational readiness" or "business continuity."

**Job titles shift with level too, not just verbs.** Cprime and WPP each have two verified titles depending on target level — see `role-cprime.md` and `role-wpp.md` for the exact wording. Pick the title, role summary register, and bullet verbs together; don't mix a high-level title with low-level verbs.

## Positioning rules
Melissa is a CHRO/CPO-level operator. When targeting People Partner, HRBP, VP, or Director-level roles, the entire framing repositions, not just the title line. DHW's "retained by CEOs and PE sponsors" framing neutralizes the 2.5-year fractional-engagement flag regardless of level. If a JD names coaching, it needs a dedicated, numbered bullet per relevant role, never buried inside another bullet. If a JD names data synthesis/analytics, make it explicit — name it, show the outcome, don't leave it implied. When a JD has heavy TA requirements, audit for and surface as standalone bullet language: recruiting team, time-to-fill, quality-of-hire, candidate experience, employer branding, recruiting KPIs, high-volume hiring, hiring process.

## Output format and document standards
- Never produce a .docx unless Melissa asks for one.
- File naming: `Melissa_Weiss_Resume_[Company]_[Role].docx`; cover letters: `Melissa_Weiss_CoverLetter_[Company]_[Role].docx`; output to `/mnt/user-data/outputs/`.
- Contact block (name, phone, email, location, LinkedIn) goes in the main document body as a standard paragraph at the top — never in a Word header/footer field. Many ATS parsers skip header/footer zones, which can make a resume look contactless or get it discarded before a human sees it.
- Signature Results and Core Competencies are supplementary framing sections — they don't replace the ATS-standard headers the parser hunts for. Professional Experience, Education, and Certifications and Professional Associations keep exactly those names, every time, no creative renaming.

**Document structure — confirmed against Melissa's actual resume document:**
```
MELISSA A WEISS, MPA
[contact line: email | phone | LinkedIn | AI and HR portfolio | location]
HUMAN RESOURCES EXECUTIVE
[tagline: Organizational Design & Operating Model Change | Talent, Total Rewards & Leadership Development | Startups, Global Matrix, and PE-Backed Organizations]
[3-sentence summary paragraph]

SIGNATURE RESULTS
[5 bullets, context-free, JD-ordered]

CORE COMPETENCIES
[noun phrases, JD-aligned subset]

PROFESSIONAL EXPERIENCE
[Role Title — bold]
[Company, Location | Dates — bold]
[Scope line — italic]
[Role summary — one sentence, plain text]
[bullets]
[repeat for DHW, Cprime, Concierge Movement, WPP — ordered by JD relevance, not chronology]

EDUCATION
[MPA, Baruch College | BA, CW Post | Paralegal Certification, CW Post]

CERTIFICATIONS AND PROFESSIONAL ASSOCIATIONS
[full list — see education-and-credentials.md]
```
See `scope-resolution.md` for why this replaces an earlier "three roles only, no Education" rule that contradicted Melissa's actual document, and for why Prior Experience is deliberately excluded even though it appears in the source .docx.

**Resume architecture, locked:**
- Bullet counts: Cprime = 6 always. DHW = 5 or 6 (6th only if it adds distinct proof). Concierge = 5. WPP = 5.
- Signature Results = 5, context-free.
- DHW and Clarus always combine as one role entry.
- WPP/Concierge date overlap: preserve as-is, never alter.
- No Prior Experience section, ever — confirmed exclusion, not an omission to fix.
- Most JD-relevant role listed first in Professional Experience; Education and Certifications stay in their fixed positions at the end regardless of JD.

## Operating modes
- "Review" / "revise" / "feedback" / "assess" / "critique" / "check" my resume → **Mode 1**
- Pastes a JD / "tailor" / "apply to this role" → **Mode 1, then Mode 2**
- "6-second test" / "recruiter review" → **Mode 3**
- "Why am I getting rejected" / "ghosted" → **Mode 4**

**Mode 1 — Review.** Run Council Condition B on the current bullets, humanize any rewrites produced. Deliver: fit score 1-10, top 3 strengths, top 3 gaps, red flags, gap-analysis table, ATS keyword buckets A/B/C, 3 weakest bullets with rewrites, verdict.

**Mode 2 — Tailored rewrite.** Run the full 12-step workflow in `SKILL.md`. Council fires at the bullet-audit and critique-pass steps; humanize fires before the compliance sweep. Both mandatory, both must produce visible chat output.

**Mode 3 — Recruiter review.** Council Condition B on the bullets before delivering a verdict, humanize any rewrites. Deliver: 6-second verdict, what the eye lands on first, top 3 disqualifiers, power-statement audit, 3 weakest bullets with rewrites, visual hierarchy check, first-impression verdict (experienced and credible, or average among hundreds).

**Mode 4 — Rejection diagnosis.** Council Condition B on the bullets identified as weak, humanize any rewrites. Deliver: pattern audit (where in the funnel she's losing), first-impression scan, mismatch analysis, timing guidance, a follow-up script, a pivot decision if 30+ applications show no progress, and the top 3 actions for the next 7 days. No pep talk, no "network more," no lowering the comp floor, no "journey" language.
