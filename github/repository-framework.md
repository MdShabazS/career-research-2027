# Repository Framework (per-repo standard)

The standard every pinned repo should meet. A repo that clears this is "Strong"; add the Elite extras to reach Elite.

## Required (Strong)
1. **Descriptive name** — `automotive-bcm-esp32`, not `project2`. (Existing names are already decent.)
2. **Repo description + topics set** — the one-line description and topic tags. `[FACT, High]` Cross-check: the candidate's three public repos currently have **null descriptions** — a free, high-visibility fix.
3. **README** answering, in order: what it does (one line a non-dev understands) → screenshot/GIF → features → tech stack → how to run → design decisions/trade-offs → **honest contribution** (solo vs team).
4. **Runs from the README** — a stranger can reproduce it (`requirements.txt`/build steps). VisionPay already has `requirements.txt` — good.
5. **License** present. (All three already have one.)
6. **Honest ownership** — Smart Wellness labeled a **team** project; VisionPay notes training was AI-assisted and ~93% is *reported*.

## Elite extras
7. **Architecture/wiring diagram** for embedded repos (the BCM state machine; the Smart Wellness wiring) — the reference repo already has real images; put them in-repo.
8. **A screenshot/GIF of it working** — real hardware photo (BCM) beats any badge.
9. **Tests + a GitHub Actions CI** on at least one repo — a genuine engineering signal recruiters cite.
10. **Meaningful commit history** — descriptive messages; small honest commits over one dump.
11. **Releases / issues** where it makes sense.

## Repo-language caveat
`[FACT, Medium]` VisionPay's primary language registers as **Jupyter Notebook** (GitHub top-languages skews to file size). `[REC, Medium]` Move core logic into `.py` modules (already partly done: `realtime.py`, `capture_dataset.py`) and keep the notebook as an experiment record, so the repo reads as Python engineering, not a notebook.

## Anti-patterns (never)
`[REC, High]` No empty scaffold repos linked as flagship work (the `aegis` repo is currently ~40 empty folders — keep it private until it has code, per the reference-repo audit). No fake commits, no forks-as-work, no vanity stat widgets presented as achievement.
