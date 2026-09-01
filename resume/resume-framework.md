# Resume Framework (four layers)

The brief asks for four frameworks. They are one master with three derivations — never four independent documents. Facts, dates, ownership, and metrics are identical across all; only emphasis changes.

## Layer 1 — Master Resume (source of truth, not submitted)
- Holds every verified fact, every honest metric, all projects, full skill taxonomy.
- Lives alongside the reference repo's canonical files; the submitted versions are **generated** from it.
- Rule: never edit a fact to fit an output; edit the master, regenerate.

## Layer 2 — One-Page Placement Resume
- The default for campus/mass applications. One page, single column, ATS-clean.
- Section order: Summary → Skills → Experience → Projects (top 3) → Education → Leadership → Certifications.
- Content budget: Summary ≤3 lines; Skills grouped into ≤4 categories; each role/project 2–3 bullets.

## Layer 3 — Domain-Specific Resume
- One variant per realistic target domain. For this candidate the honest domains are:
  - **Embedded / Embedded-Software (primary).** Lead projects: Automotive BCM → Smart Wellness → VisionPay. Skills lead with C/Embedded C/MCU/peripherals.
  - **Software / Applied-CV (secondary).** Lead projects: VisionPay → MITRA (via experience). Skills lead with Python/Android/OpenCV/TFLite; move DSA/DBMS/OS/CN up.
- Changes only: summary wording, skill ordering, project selection/ordering, keyword alignment.

## Layer 4 — Company/JD-Tailored Resume
- Per-JD workflow: read JD → extract required keywords → map to **verified** facts → note gaps honestly (never invent coverage) → pick 3–4 best-matching projects → reorder skills → one page → final honesty pass (name, location, dates, Nokia lifecycle correct, ownership honest, no confidential content).

## The bullet template (apply everywhere)
`[REC, High]` **Action verb (distinct each time) + what was built + specific technology + honest quantifier/outcome.**
- Good (real): *"Programmed an ESP32 body-control module with a 3-state (OFF/ACC/ON) ignition FSM driving 6+ vehicle functions."*
- Bad (invented scale): *"...serving 2M+ users"* — the candidate has no such metric; do not borrow the elite example's numbers.

## Header rule
`[REC, High]` Name, one specialization line, location (Ballari), email, clickable LinkedIn + GitHub labels. **Phone:** include only on resumes submitted directly to an employer — never commit a resume containing a plaintext phone number to a public repo (reference-repo audit flagged this exact leak). No portfolio URL until deployed.

## Non-negotiables
- One page. Single column. Named tools only if used. Every skill token appears in a bullet. `TO_VERIFY` certs are not presented as strong claims. Nokia shown at its true lifecycle state (see reference-repo audit). No invented metrics.
