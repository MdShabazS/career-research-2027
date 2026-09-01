# Career Positioning Analysis

The positioning question, worked from evidence — not pre-decided (brief §3). Full market detail in [`../market/`](../market/); this is the argument and the conclusion.

## The question
Which of Software / AI-ML / GCP-Cloud / Embedded / Embedded-Software / Embedded-Firmware / Automotive-Embedded gives this candidate the strongest combination of employability, technical credibility, fresher accessibility, differentiation, growth, background-fit, and **demonstrable** evidence?

## The method
Score each family for *this* candidate's actual starting point (2 embedded HW projects, 1 CV project, Basic DSA/CS-fundamentals, 2 internships, no cloud/RTOS/CAN evidence), using the accessibility scorecard in [`../market/role-analysis.md`](../market/role-analysis.md).

## The evidence, compressed
- **Embedded** ranks highest: ECE-aligned, uses projects that already exist, structurally growing India market, and it **avoids the candidate's weakest gate** (Basic DSA). Entry bar (Embedded C + documented HW projects) is already met; only differentiators (RTOS, protocol breadth) are missing. `[FACT/INFER, High]`
- **Automotive Embedded** has the highest pay but is **gated** by CAN/AUTOSAR/ISO 26262 — none currently truthful. Aspirational, not a headline. `[FACT, High]`
- **Software Engineer** is credible but **DSA-gated** (Amazon/Flipkart OAs) — the candidate's Basic DSA is the binding constraint. Secondary door. `[FACT, High]`
- **AI/ML** has a low barrier *if* you ship 2–3 real projects; the candidate has real CV artifacts but Basic skills and no deployment/RAG. Best used as a **differentiator**, not a standalone headline. `[FACT/INFER, Medium-High]`
- **GCP/Cloud** is the **weakest-evidenced** and least ECE-adjacent — one virtual-internship cert, no cloud project. A year-2 pivot, not a 2027 identity. `[FACT, High]`

## The conclusion
`[REC, High]` **Primary: Embedded Software Engineer. Differentiator: on-device computer vision. Secondary door: Software. Aspirational vector: Automotive (earned via a CAN build). Deferred: GCP/Cloud, RAG-AI.**

This is an evidence-led call, and deliberately not identical to either positioning currently in the reference repo. It is defensible in an interview because every element maps to a real artifact, and it is truthful because it excludes everything the candidate cannot yet demonstrate.

## Why this beats the two existing positionings
- The reference repo's **canonical** files say "Software Developer \| Embedded Engineer" (software-first) — but software is the DSA-gated, less-evidenced door.
- The reference repo's **resume/GitHub** say "Embedded Engineer \| Automotive Embedded Systems" — but automotive is gated by skills he lacks.
- The evidence supports **Embedded Software + on-device CV**: embedded-first (matching his strongest evidence) with the CV differentiator that neither existing version foregrounds, and automotive correctly demoted to aspiration. It also resolves the cross-channel contradiction the audit found.
