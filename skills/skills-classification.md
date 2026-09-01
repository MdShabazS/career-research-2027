# Skills — Classification & Development Plan (candidate-specific)

Companion to [`../market/skill-demand.md`](../market/skill-demand.md) (which holds the market demand tiers). This file is the **prioritized learning plan** mapped to which asset each skill unlocks. Depth model: Awareness → Working → Strong → Advanced.

## 1. Current honest baseline (reference repo, VERIFIED)
`[FACT, High]` C, C++, Python, Java, SQL — **Basic**. DSA, DBMS, OS, CN — **Basic**. Embedded C, Microcontrollers; Android Studio, OpenCV, Firebase, Git/GitHub. Hands-on (project-level): ESP32, STM32 (Cortex-M4), I2C, ADC, timers, sensor interfacing, TensorFlow Lite, MobileNetV2. **Not held:** RTOS, UART/SPI (interrupt-driven), CAN/LIN, AUTOSAR, JTAG/SWD, Docker/K8s, REST (as a competency).

## 2. Prioritized development plan (what to learn, in order, and why)

| Priority | Skill | To depth | Unlocks | Asset impact |
|---|---|---|---|---|
| **P0** | Strong **C** (pointers, memory, bit-ops) | Strong | every embedded role | Resume/GitHub credibility |
| **P0** | **UART/SPI interrupt-driven** | Working | protocol breadth (currently I2C-only) | Resume skills + a project |
| **P0** | **Git** fluency (branches, clean history) | Working | GitHub signal | GitHub tier ↑ |
| **P1** | **FreeRTOS** (tasks, sync) | Working | RTOS keyword-with-evidence | Resume + portfolio project |
| **P1** | **Debugging JTAG/SWD** | Working | maturity signal | Resume + GitHub |
| **P1** | **Testing + CI** (unit tests, GitHub Actions) | Working | reproducibility signal | GitHub Strong→Elite |
| **P1** | **On-device CV depth** (OpenCV/TFLite) | Working | the differentiator | Portfolio throughline |
| **P2** | **DSA** (if keeping software door open) | Interview-ready | SWE screens | Software-track resume |
| **P2** | **DBMS/OS/CN** Basic→Working | Working | CS-fundamentals rounds | Resume depth |
| **P2 (cond.)** | **CAN/LIN** | Working | automotive unlock | Automotive positioning |
| **P3 (cond.)** | AUTOSAR/MISRA/ISO 26262 | Awareness | automotive vocabulary | Cover-letter only |
| **Deferred** | Docker/K8s/Terraform, RAG/vector DB | Awareness | cloud/AI pivots | year-2 |

## 3. The learn→apply pairing (never learn without shipping)
`[REC, High]` Each P0/P1 skill is paired with a concrete artifact so it becomes evidence, not a claim:
- UART/SPI → interrupt-driven multi-sensor project.
- FreeRTOS → port BCM/Smart Wellness to tasks.
- Testing/CI → add to one existing repo.
- CV depth → extend VisionPay (deployment/video).

## 4. Honesty rule (unchanged)
`[FACT, High]` No skill appears on any asset above its true depth. Deferred/Conditional skills are **targets**, never current claims. This preserves the reference repo's "Learn → Practise → Verify → Add" gate.

## 5. Anti-breadth guardrail
`[REC, High]` Resist adding a long tail of "familiar-with" tools. Depth in the P0/P1 embedded core + the CV differentiator beats a wide shallow list (brief §24; recruiters discount breadth-without-depth).
