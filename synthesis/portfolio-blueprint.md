# Portfolio Blueprint (spec, build later)

Derived from [`../portfolio/`](../portfolio/). Not built now (brief §22).

## Concept
A premium, restrained **"interactive engineering product"** on one throughline: **embedded firmware + on-device intelligence**. One signature 3D interaction tied to real work (interactive OFF/ACC/ON state machine, or a rotatable annotated ESP32/STM32 board) — not a generic particle hero.

## Stack & performance budget
React + React Three Fiber + Drei + GSAP; WebGPU-with-WebGL fallback; content-first loading (HTML before 3D bundle). Budget: <100 draw calls, Draco/KTX2 assets, LOD, dispose-on-unmount, `prefers-reduced-motion` honored, full light/dark, fully responsive, graceful low-power degradation.

## IA
Hero → Featured projects (cards→case pages) → Experience → Skills → About → Education/Leadership/Certs → Contact (form only, no plaintext phone; LinkedIn+GitHub only).

## Case-page story shape
Problem → architecture diagram → key decisions/trade-offs → what I built (honest ownership) → status + evidence (repo/demo/media) → what's next. Statuses truthful (AEGIS design-stage; Smart Wellness team; ~93% reported).

## Media
Real only: BCM breadboard photo, Smart Wellness wiring diagram, VisionPay frames, IEEE SPACE 2026 photos + **new demo videos/GIFs** (currently missing — capture before/at build).

## Build order
1. Fast content-first **v1** (HTML + media + working links).
2. One signature 3D interaction.
3. Case-page diagrams + demo videos.
4. Polish (scroll sequencing, WebGPU) within the perf budget.

## Prerequisite
Positioning resolved + demo media captured **before** building. The portfolio renders a decided identity; it is not where the identity is decided.
