# Portfolio — Recommendations for Mohammed Shabaz S

Feeds [`../synthesis/portfolio-blueprint.md`](../synthesis/portfolio-blueprint.md). Site is **not** built here (brief §22); this is the spec.

## 1. Concept
`[REC, High]` A premium, restrained **"interactive engineering product"** built around one throughline: **embedded firmware + on-device intelligence**. One signature 3D interaction tied to real work (interactive BCM state machine or a rotatable annotated board), not a generic particle hero.

## 2. Stack
`[REC, High]` React + **React Three Fiber + Drei + GSAP**, WebGPU-with-WebGL-fallback, content-first loading (HTML before 3D bundle). Deploy on a fast static host. Targets: <100 draw calls, Draco/KTX2 assets, LOD, dispose-on-unmount, `prefers-reduced-motion` honored, full light/dark, fully responsive.

## 3. Projects to feature (in order)
`[REC, High]` Automotive BCM → Smart Wellness (team) → VisionPay → (AEGIS as *design-stage*, clearly labeled, only if it has real content by build time). MITRA appears under Experience (company-confidential; high-level, no repo). Skin Disease under IEEE EMBS.

## 4. Media plan (real only)
`[REC, High]` Reuse the reference repo's real assets: BCM breadboard photo, Smart Wellness wiring diagram, VisionPay frames, IEEE SPACE 2026 photos. Capture a short **demo video/GIF** of each project working — the single strongest "I build things" signal and currently missing.

## 5. Contact & privacy
`[REC, High]` Contact form only; **no plaintext phone** on the public site; LinkedIn + GitHub only (no other socials). Location: Ballari.

## 6. Consistency
`[REC, High]` Hero specialization line = the exact same identity as resume/LinkedIn/GitHub. Nokia shown at true lifecycle state. This is what makes the four assets reinforce one story.

## 7. Sequencing (build later, in this order)
1. Ship a **fast, content-first v1** (HTML + real media + working links) even before heavy 3D — a live, honest portfolio beats a perfect unshipped one.
2. Add the **one signature 3D interaction**.
3. Add case-page **architecture diagrams** + demo videos.
4. Layer polish (scroll sequencing, WebGPU) last, within the perf budget.

## 8. Prerequisite
`[REC, High]` Capture demo media and finalize positioning **before** building — the portfolio is a rendering of a resolved identity, not the place to decide it.
