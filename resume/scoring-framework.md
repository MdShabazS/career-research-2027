# Resume Scoring Framework

A reproducible, honest rubric to grade any resume draft. Deliberately **not** a claimed commercial "ATS score" — no universal ATS score exists (platforms weight differently). This measures how well the *true* profile is surfaced.

## Dimensions (sum 100)

| # | Dimension | Weight | What it tests |
|---|---|---|---|
| 1 | Parseability | 15 | One page, single column, selectable text, ≥3 working links, standard headings |
| 2 | Positioning clarity | 12 | One specific specialization line; consistent with LinkedIn/GitHub/portfolio |
| 3 | Skills–evidence coupling | 15 | Every skill token also appears in a bullet; no orphan buzzwords |
| 4 | Project quality | 18 | 3–5 projects, real builds, honest ownership, GitHub links live |
| 5 | Bullet craft | 12 | Distinct action verbs; action+build+tech+outcome shape; no duty lists |
| 6 | Honest quantification | 10 | Real numbers only; fraction of bullets with a genuine metric |
| 7 | Keyword alignment | 10 | Supportable JD keywords present (not stuffed with gaps) |
| 8 | Truthfulness/hygiene | 8 | No invented metrics, no team-as-solo, correct dates/lifecycle, no PII leak |

## Scoring bands
- **90–100 Elite-for-a-fresher:** clear positioning, live evidence, honest metrics, zero contradictions.
- **75–89 Strong:** solid but one or two weak spots (thin metrics, minor drift).
- **60–74 Acceptable:** parses and reads, but generic positioning or weak project evidence.
- **<60 Rework:** buzzwords, unbacked skills, contradictions, or truthfulness problems.

## Guardrail (overrides score)
`[REC, High]` Any invented metric, team-as-solo claim, planned-as-completed project, or a resume file containing a plaintext phone number committed to a public repo → **automatic fail**, regardless of other dimensions. Truthfulness and PII-safety gate the score.

## How to use
Grade a draft on each dimension, list the three lowest, fix those first. Re-grade. The point is to find the weakest signal, not to chase a number.
