# Skill Demand & Classification (2026)

Skills classified by market demand and by **ROI for this candidate's four assets**, not by trendiness (brief §12/§24). Depth model: Awareness → Working → Strong → Advanced.

Labels: `[FACT]` cited · `[INFER]` reasoned · `[REC]`. Confidence in each row.

## 1. Demand tiers (embedded-primary lens, with software/AI adjacency)

| Skill | Tier | Demand evidence | Candidate now | Target depth | ROI |
|---|---|---|---|---|---|
| **C / Embedded C** | Must-have | #1 embedded filter (piestsystems, ziprecruiter) | Basic | Strong | ★★★★★ |
| **MCU peripherals** (GPIO/timers/interrupts/ADC/PWM) | Must-have | named in every embedded JD | Working (project) | Strong | ★★★★★ |
| **UART / SPI / I2C** | Must-have | baseline protocols (piestsystems) | I2C only | Working across all 3 | ★★★★★ |
| **RTOS / FreeRTOS** | Strongly preferred | differentiator; mandatory in automotive/robotics | None | Working | ★★★★★ |
| **Debugging (serial→JTAG/SWD)** | Strongly preferred | maturity signal | Serial only | Working | ★★★★☆ |
| **Git / version control** | Must-have | universal | Basic | Working | ★★★★★ |
| **Testing / verification** | Strongly preferred | most effort-intensive in safety work | Basic (project) | Working | ★★★★☆ |
| **Python** | Strongly preferred | tooling, tests, ML, cloud automation | Basic | Working | ★★★★☆ |
| **DSA + problem-solving** | Must-have (for SWE screens) | Amazon/Flipkart OA gate | Basic | Interview-ready if SWE | ★★★★☆ |
| **CAN / LIN** | Preferred (Must-have for automotive) | automotive gate (piestsystems) | None | Working (if automotive) | ★★★★☆ *conditional* |
| **AUTOSAR / MISRA / ISO 26262** | Automotive-only | Tier-1 gate | None | Awareness | ★★★☆☆ *conditional* |
| **On-device CV** (OpenCV, TFLite, MobileNet) | Preferred/Emerging | edge-AI growth; his differentiator | Basic (VisionPay) | Working | ★★★★☆ |
| **RAG / vector databases** | Emerging (AI) | +67% AI roles, heavy RAG demand (NASSCOM-BCG via taggd) | None | Awareness | ★★★☆☆ |
| **Docker / K8s / Terraform** | Preferred (cloud/DevOps) | cloud fresher asks (futurense) | None | Awareness | ★★☆☆☆ *deferred* |
| **SQL / DBMS** | Preferred | broad | Basic | Working | ★★★☆☆ |
| **OS / Computer Networks fundamentals** | Preferred | CS-fundamentals rounds | Basic | Working | ★★★☆☆ |
| **Embedded Linux / Yocto / drivers** | Preferred (role-dependent) | Linux-class roles | None | Awareness | ★★★☆☆ |
| **VLSI / Verilog / SystemVerilog** | Adjacent (different track) | semiconductor boom (dqindia) | None | — | ★★☆☆☆ (off-path) |

## 2. Low-ROI / avoid for this candidate now
`[REC, Medium]` **Do not** spread into: full DevOps/IaC stack, VLSI/RTL (a different ECE track), heavy web-framework depth, or a long tail of "familiar with X" tools. Breadth without depth is the exact anti-pattern recruiters discount (brief §24). Each added skill must be **demonstrable in a project or dropped**.

## 3. The highest-ROI moves (ranked)
`[REC, High]`
1. **Strong C + interrupt-driven UART/SPI** — converts "exposure" into interview-safe embedded depth. Highest leverage.
2. **FreeRTOS port** — single most valuable *keyword-with-evidence* unlock.
3. **Git fluency + clean READMEs/tests on existing repos** — cheap, visible on GitHub immediately.
4. **On-device CV framing** (VisionPay) — the differentiator that separates him from generic embedded freshers.
5. *(Conditional on automotive goal)* **CAN demo** — the one automotive unlock worth the cost.

## 4. Depth honesty rule
`[FACT, High]` The reference repo already enforces "Learn → Practise → Verify → Add." This research adds only the **market weighting** of what to learn first. No skill in this file may appear on the resume/LinkedIn/GitHub above its true depth. RAG, Docker/K8s, CAN, AUTOSAR are **targets**, not current claims.

## Sources
- piestsystems.com, ziprecruiter.com, careers360.com (embedded skill demand)
- taggd.in, acciojob.com, masaischool.com (AI skills incl. RAG/vector DB, NASSCOM-BCG figure)
- futurense.com, cloudsoftsol.com (cloud/DevOps skill asks)
- glassdoor.co.in, apna.co (SWE fresher DSA/stack demand)
- dqindia.com (semiconductor/VLSI adjacency)
