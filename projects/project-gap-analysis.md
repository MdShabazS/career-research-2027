# Project Gap Analysis — the candidate's existing projects

Each project from the reference repo assessed against [`project-quality-framework.md`](project-quality-framework.md). Status labels from the reference repo are preserved (no `PLANNED`→`COMPLETED`).

## Assessment table

| Project | Ownership | Status | Tier now | On-identity? | Verdict |
|---|---|---|---|---|---|
| **Automotive BCM (ESP32)** | Individual | COMPLETED | **Strong portfolio** | ★★★★★ embedded/automotive | **Feature — lead artifact** |
| **VisionPay** | Individual | COMPLETED | **Strong portfolio** | ★★★★☆ on-device CV | **Feature — differentiator** |
| **Smart Wellness (STM32)** | College **team** | COMPLETED | **Demonstration → Strong** | ★★★★☆ embedded | **Feature — labeled team** |
| **MITRA (iHelp)** | Company product; app-side contribution | COMPLETED | **Industry-credible (context)** | ★★★★☆ software/Android | **Under Experience, not standalone** |
| **Skin Disease Classification** | IEEE EMBS **team**, 1-month | COMPLETED (demo) | **Demonstration** | ★★★☆☆ healthcare/AI | **Under Experience; portfolio-secondary** |
| **AEGIS** | Team; candidate lead | **PLANNED** (empty repo) | **Not creditable yet** | ★★★☆☆ AI platform | **Design-stage only; do not present as built** |

Excluded (reference repo): NIDAR, undocumented hackathon, NexCast Pro (removed), Pega (removed) — keep excluded.

## Per-project notes

### Automotive BCM — strongest asset
`[FACT, High]` ESP32, OFF/ACC/ON FSM, 6+ functions, non-blocking `millis()` scheduler, 30 ms debounce, 10 Hz I2C OLED, real breadboard photo. `[INFER, High]` The single most on-identity artifact (embedded + automotive theme + real hardware + defensible design). **Lead everywhere.** Lift to Industry-credible with tests + a wiring/architecture diagram + demo video.

### VisionPay — the differentiator
`[FACT, High]` Python, MobileNetV2→TFLite, ~400 imgs/6 classes, offline CPU, confidence-gating + temporal smoothing, ~93% **reported**. `[INFER, High]` Real, useful (assistive), on-device — the edge-AI half of the throughline. Lift by fixing the notebook-language optics (`.py` modules), adding a demo video, and keeping ~93% labeled reported.

### Smart Wellness — solid team proof
`[FACT, High]` STM32 Cortex-M4, ultrasonic + ADC temp, I2C OLED, timers, HAL, STM32CubeIDE; candidate did sensor interfacing, wiring, testing. `[REC, High]` Keep, **always labeled a team project**; his contribution stated. Second embedded proof (adds STM32/Cortex-M4 + protocol breadth to the story).

### MITRA — real but bounded
`[FACT, High]` Company product; app-side stream-reliability/voice/testing work; backend/model another team; confidential; no public repo. `[REC, High]` Present under Experience only, high-level. It is genuine industry context but not a personal showcase repo.

### Skin Disease — demonstration, keep honest
`[FACT, High]` 3-member, 1-month, demo-level, model unrecorded. `[REC, High]` Under IEEE EMBS experience; portfolio-secondary; never "productized/clinical."

### AEGIS — the risk
`[FACT, High]` `PLANNED`, design stage, and its public repo is a ~40-folder empty scaffold. `[REC, High]` **Do not** present as built anywhere; do not pin/feature the empty repo (reads as abandoned). Keep it as a clearly-labeled *design-stage* concept, ideally private until real code exists. High upside **only if actually built**.

## The project-portfolio gap (what's missing)
`[INFER, High]` The candidate has **two Strong embedded/CV artifacts + team proof**, which is already a credible fresher base. The gaps that would most raise the portfolio:
1. **Protocol/RTOS breadth** — no UART/SPI-interrupt or FreeRTOS project (the top market differentiators). One FreeRTOS port + one UART/SPI multi-sensor build would materially strengthen the set.
2. **Demo media** — no demo videos/GIFs (the strongest "I build" signal).
3. **Reproducibility signals** — no tests/CI on any repo.
4. *(Conditional on automotive goal)* a **CAN demo** — the one automotive unlock.

`[REC, High]` Recommended next builds, ranked by asset-leverage: (1) FreeRTOS port of BCM or Smart Wellness; (2) UART/SPI interrupt-driven multi-sensor; (3) demo videos + README upgrades on existing repos; (4) CAN demo if automotive is chosen. All align with the reference repo's own roadmap; here they are prioritized by market evidence.
