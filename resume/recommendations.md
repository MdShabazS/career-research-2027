# Resume — Recommendations for Mohammed Shabaz S

Applies the benchmarks/frameworks to the candidate's actual verified facts (reference repo). These feed [`../synthesis/resume-blueprint.md`](../synthesis/resume-blueprint.md). No assets are built here (brief §22).

## 1. Positioning line (resolve the contradiction first)
`[REC, High]` Lead with **one** specialization line. Evidence supports **embedded-primary**: e.g. *"Embedded Software Engineer — microcontroller firmware (ESP32/STM32, Embedded C) with on-device computer vision."* This is truthful, specific, ECE-aligned, and uses existing projects. Avoid "Automotive Embedded Systems" as the headline until a CAN/AUTOSAR build exists (currently absent). Full argument: [`../executive/career-positioning-analysis.md`](../executive/career-positioning-analysis.md).

## 2. Skills block (fix the audit finding)
`[REC, High]` Group into ≤4 categories, every token backed by a bullet. Resolve the reference-repo contradiction: the canonical `current-skills.md` forbids listing I2C/GPIO/ADC/Cortex-M4/boards *as skills*, yet the resume does. Pick one policy — recommended: add a **"Demonstrated in projects"** sub-line so those tokens are honestly framed as project-proven, not claimed proficiencies. Do **not** list RTOS/CAN/AUTOSAR/REST as skills (not held).

## 3. Projects (top 3 for the embedded master)
`[REC, High]` Automotive BCM (ESP32, FSM, non-blocking) → Smart Wellness (STM32 Cortex-M4, I2C/ADC/timers, **team**) → VisionPay (Python/TFLite/MobileNetV2, ~93% *reported*). MITRA stays under Experience; Skin Disease under IEEE EMBS. AEGIS **omitted** (PLANNED, no code) — or shown only on a software variant, labeled in-progress.

## 4. Experience honesty
`[REC, High]` Show Nokia at its **true lifecycle state**. Per the reference-repo audit, as of 2026-09 the 16 Sep 2026 start is future — present it as *incoming/UPCOMING* until it starts, not "currently working." iHelp: app-side software contribution, MITRA as project name, backend/model attributed to another team. IEEE EMBS: 3-member demo-level.

## 5. Metrics — use only these real ones
`[FACT, High]` 2 video sources; 6+ app-side improvements; 5-minute loop fix; 3-state FSM / 6+ functions; 30 ms debounce; 10 Hz I2C refresh; ~400 images / 6 classes; ~93% **reported** validation accuracy; 2 sensor types; 3-member team. Nothing beyond these.

## 6. Certifications
`[REC, High]` List the 3 evidenced certs normally (Embedded Systems–Internshala, Python–EISystems, Google Cloud GenAI–SmartInternz). Certs 1–2 (SQL/C&C++ "with AI") are `TO_VERIFY` (no issuer/date/PDF) — either omit or list without asserting them strongly until artifacts exist.

## 7. PII / repo safety
`[REC, High]` Never commit a resume file with a plaintext phone into a public repo. Keep the phone only in employer-submitted copies. (Directly addresses the reference-repo leak.)

## 8. First actions
1. Lock the positioning line. 2. Rebuild the skills block with the demonstrated-in-projects tier. 3. Correct Nokia lifecycle wording. 4. Regenerate one-page embedded master + one software variant. 5. Grade with [`scoring-framework.md`](scoring-framework.md); fix the 3 lowest dimensions.
