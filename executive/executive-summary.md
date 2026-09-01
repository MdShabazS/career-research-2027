# Executive Summary

Evidence-based research to inform four career assets — Resume, LinkedIn, GitHub, and a premium 3D/immersive portfolio — for Mohammed Shabaz S, a final-year B.E. ECE student (BITM, graduating 2027). Read [`../METHODOLOGY.md`](../METHODOLOGY.md) for how claims are labeled and what could/couldn't be sampled.

## What was researched
- **Market (India/Bangalore, 2026):** Software, AI/ML, GCP/Cloud, and the four embedded role families — fresher accessibility, skills, salary bands, gates, growth drivers.
- **Asset best-practice (2025–2026):** resume (ATS, bullets, structure), LinkedIn (headline/About/Featured), GitHub (pins, README, recruiter scan), portfolio (premium 3D, Three.js performance/accessibility).
- **The candidate's actual profile** from the reference repo, and his live GitHub repos (direct API checks).
- **Frameworks + scoring ladders** for each asset, a project quality ladder, a skill-demand/ROI model, and cross-referenced evidence.

## Major findings
1. **The candidate's demonstrable evidence is densest in embedded** (2 real hardware projects), thinner in software/AI, near-absent in cloud. Positioning should follow that. `[INFER, High]`
2. **GCP/Cloud is not a truthful 2027 fresher positioning** — it needs a Python/Linux/Docker/K8s/Terraform stack + a real cloud project he doesn't have. Defer it. `[FACT, High]`
3. **Automotive embedded is aspirational, not a headline** — gated by CAN/AUTOSAR/ISO 26262 (all absent). `[FACT, High]`
4. **Software is a secondary door, DSA-gated** — his Basic DSA is the binding constraint; embedding-primary routes around it. `[FACT, High]`
5. **His rare differentiator is embedded firmware + on-device computer vision** — few freshers pair real MCU firmware with real edge-AI. `[INFER, High]`
6. **Presentation, not substance, is the biggest near-term gap:** empty repo descriptions, no demo media, no tests/CI, an empty public "flagship" (AEGIS), and a positioning that contradicts itself across channels. `[FACT/INFER, High]`
7. **Best-practice convergence:** evidence beats claims everywhere; recruiters read 2–4 pinned repos in ~11–30s and ignore contribution graphs/badges; premium 3D means restraint + performance (WebGPU+fallback, <100 draw calls, defer the 3D bundle), not maximum animation. `[FACT, High]`

## Strongest positioning discovered
`[REC, High]` **Embedded Software Engineer, with on-device intelligence as the differentiator** — software as a secondary door, automotive as an earned aspiration, cloud/RAG deferred. Evidence-led, truthful, and (deliberately) not identical to either positioning currently in the reference repo. Argument: [`career-positioning-analysis.md`](career-positioning-analysis.md).

## Biggest gaps (ranked)
- **Critical:** resolve to one identity; fix integrity leaks (Nokia tense, plaintext phone in a public repo, empty AEGIS repo); upgrade the 3 public repos (descriptions/READMEs/media).
- **High:** protocol/RTOS evidence (UART/SPI + FreeRTOS builds); demo videos; tests/CI; stronger C.
- **Medium:** DBMS/OS/CN depth; VisionPay deployment; a LinkedIn recommendation; resolve the two `TO_VERIFY` certs.
- **Defer:** cloud stack, RAG, automotive stack (unless that branch is chosen).

## Most important recommendations
See [`strategic-recommendations.md`](strategic-recommendations.md) and [`../synthesis/final-profile-strategy.md`](../synthesis/final-profile-strategy.md). In one line: **pick one evidenced identity, fix the truthfulness/consistency leaks, surface the work he already has, then close the top embedded gaps with real artifacts — in that order.**

## Honest limitations
Individual LinkedIn profiles were not scrapeable; LinkedIn findings rest on official + reputable-analysis guidance. Most sources are strong-secondary recruiter/career publications cross-checked for agreement, not official primary docs. Salary bands are corroborated ranges, not precise figures. All flagged in [`../METHODOLOGY.md`](../METHODOLOGY.md) and [`../sources/`](../sources/).

## Repository map
`executive/` conclusions · `market/` role & skill demand · `resume/ linkedin/ github/ portfolio/` benchmarks+frameworks+recommendations · `projects/ skills/ certifications/` candidate evaluation · `database/` matrices · `sources/` evidence index · `synthesis/` gap analysis, scorecard, blueprints, final strategy.
