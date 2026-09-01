# Methodology, Labeling & Limitations

This file governs how every other file in this repository is written and read. It exists so that a future reader (or the subject) can tell exactly how much weight each statement deserves.

## 1. Claim labels

Every non-trivial statement is one of:

- **OBSERVED FACT** — directly supported by a cited source that was actually retrieved, or by the reference repository. What the evidence literally shows.
- **INFERENCE** — a reasonable conclusion drawn from combining multiple observations. Not directly stated by any single source.
- **RECOMMENDATION** — a suggested action derived from the evidence. A judgment call, owned as such.

These are never blurred. Where a section is dense, claims are tagged inline as `[FACT]`, `[INFER]`, `[REC]`.

## 2. Evidence hierarchy

| Tier | Sources | How it is used |
|---|---|---|
| **Primary** | Official company career pages, official job descriptions, official documentation (Google Cloud, ARM, AUTOSAR), university/institution pages, official platform guidance (LinkedIn, GitHub) | Strongest; can anchor an `OBSERVED FACT`. |
| **Strong secondary** | Reputable recruiting/labor-market sources, established career/industry publications, recognized technical organizations | Can support a fact when cross-confirmed; otherwise supports an `INFERENCE`. |
| **Supporting** | Credible community discussion, public profile examples, practitioner blogs | Directional only; supports `INFERENCE`, never a lone `FACT`. |
| **Unverified** | Anonymous claims, unsourced assertions, marketing copy | Flagged and not relied upon. |

## 3. Confidence levels

Each material finding carries a confidence: **High** (multiple independent, recent, credible sources agree), **Medium** (credible but thinner or partly dated), **Low** (single source, older, or contested). Volatile market facts favor 2025–2026 sources.

## 4. Finding record format

Important findings use:

> **Claim** → **Source(s)** → **Evidence (what the source shows)** → **Interpretation** → **Confidence**

## 5. Honest limitations of this research (read this)

The brief asked for "large representative samples" of real profiles. The following constraints are stated plainly rather than papered over:

- **LinkedIn profiles are not directly retrievable.** LinkedIn serves a login/anti-scraping wall to automated fetching. This research therefore does **not** claim to have parsed N individual LinkedIn profiles. LinkedIn findings are built from: LinkedIn's own official guidance, reputable recruiter/career analyses of what strong profiles do, and publicly summarized profile patterns. Treated as `INFERENCE` unless a primary source is cited.
- **GitHub profiles are retrievable** and a small number of real, well-known engineer profiles were examined directly; these are named where used. This is an illustrative sample, **not** a statistical one — patterns are cross-checked against published GitHub/recruiter guidance rather than asserted from a handful of profiles.
- **Job descriptions:** aggregate skill-demand is taken from labor-market/job-board analyses and a sample of real postings that were retrievable. Individual JD counts are illustrative, not exhaustive.
- **Recency vs. cutoff:** where web sources were retrieved, they are cited and dated. Where general domain knowledge is used (e.g. what UART/SPI are), it is background, not a market claim. Any forward-looking market statement is anchored to a retrieved 2025–2026 source or marked `INFERENCE`.
- **No fabricated sampling numbers.** This document will never say "analyzed 200 profiles" unless 200 profiles were actually analyzed. They were not.

## 6. Reference-repo handling

The subject's facts come from [`shabaz-career-profile`](https://github.com/MdShabazS/shabaz-career-profile). Its status labels are authoritative and preserved:

- `VERIFIED` facts are used as-is.
- `TO_VERIFY` items are used only with hedging and flagged for the subject to confirm.
- `PLANNED` work (e.g. AEGIS) is treated as not-yet-built.
- `EXCLUDED` items stay out of recommendations.
- `CONFIDENTIAL` items (Nokia domain, MITRA internals) are never inferred or exposed.

A known open issue in the reference repo (documented separately): the subject's **positioning is currently contradictory** across channels and Nokia is represented as current before its start date. This research treats positioning as an **open question to be answered by evidence**, which is the correct posture regardless of that inconsistency.
