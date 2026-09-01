# Portfolio — Elite Benchmark (premium 3D / immersive, 2026)

Real best-in-class Three.js/WebGL sites and what makes them strong. The goal is an **"interactive engineering product,"** not an "animated template."

## 1. Named best-in-class sites (2026) and their one idea
`[FACT, Medium]` From a curated 2026 roundup (utsubo):
- **Oryzo** (Lusion) — single product render, inertial physics, Z-axis depth scroll.
- **IVRESS** (Utsubo) — WebGPU with WebGL fallback via TSL shaders.
- **Shopify Editions** — scroll-sequenced product showcase, choreographed transitions.
- **Hubtown** (Unseen) — a single 3D monolith with mouse-reveal.
- **Sleep Well Creative** — scroll-driven narrative blending hand-drawn art with 3D.
- **Explore Primland** — cinematic aerial flythrough of real terrain.
- **Cartier Watches & Wonders** (Immersive Garden) — six scrollable 3D "museum" alcoves.

## 2. The recurring pattern: restraint
- `[FACT, High]` Standouts use **one focused mechanic**, not layered effects: **single hero objects**, baked lighting, tight asset budgets. Scroll is used as **narrative sequencing**, and camera moves through **Z-depth** rather than 2D parallax. (utsubo.)
- `[INFER, High]` "High-end ≠ maximum animation." The premium feel comes from **one memorable interaction executed flawlessly** + fast load + clarity — exactly the brief's instruction.

## 3. Performance is part of the aesthetic
- `[FACT, High]` 2026 standouts adopt **WebGPU with a WebGL fallback**, and pass Core Web Vitals by **deferring the 3D bundle, rendering meaningful HTML first, and budgeting assets.** (utsubo, appscale.) Details in [`3d-interaction-research.md`](3d-interaction-research.md).

## 4. What separates strong from flashy-but-empty
- `[INFER, High]` A flashy template shows motion with no meaning. A **strong engineering** portfolio uses visuals to explain *the work* — a rotating PCB/board, an interactive state-machine diagram, a live inference demo — so the 3D *is* the evidence, not decoration. This is the differentiator the candidate should chase, given real hardware artifacts to show.

## Sources
- utsubo.com/blog/best-threejs-websites-2026 · utsubo.com/blog/threejs-best-practices-100-tips
- appscale.blog (Three.js in production 2026: WebGPU, perf, fallback)
- creativedevjobs.com (Three.js portfolio examples 2026)
