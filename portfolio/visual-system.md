# Portfolio — Visual System

A visual identity specific to an **embedded/hardware + on-device-intelligence** engineer, so the site reads as an engineering product, not a generic template. (Final palette/type chosen at build; this sets direction and guardrails.)

## 1. Design direction
`[REC, High]` Lean into the subject's real world: circuit boards, microcontrollers, state machines, signal traces. A restrained, technical-instrument aesthetic — think oscilloscope/PCB, not neon gaming. One accent, disciplined; everything else quiet (this is also the anti-AI-template move).

## 2. Typography
`[REC, Medium]` Pair a characterful display face (used sparingly for the hero + section titles) with a highly readable body face, and a **monospace** for code, specs, and data — the mono is on-theme for firmware work. Set a type scale and hold it; generous spacing.

## 3. Color & theme
`[REC, High]` A picked neutral ground (slightly hue-biased, not pure grey), one engineering accent, and **semantic** colors for status (planned/in-progress/complete) that are distinct from the accent. Full **light and dark** support, both designed (not an inverted afterthought).

## 4. Motion discipline
`[REC, High]` Motion serves meaning: a board rotating to reveal components, a state-machine animating its transitions, a scroll that advances a build sequence. **Respect `prefers-reduced-motion`** — disable auto-loops/heavy motion when set. No motion for motion's sake (it's an AI-template tell and an accessibility cost).

## 5. Imagery
`[REC, High]` Use the candidate's **real** media: the BCM breadboard photo, the Smart Wellness wiring diagram, VisionPay inference frames, IEEE SPACE 2026 photos. Never fabricate screenshots or hardware. Where a real image is missing, use a clean, clearly-labeled designed thumbnail — not a fake screenshot.

## 6. Accessibility & responsiveness (non-negotiable)
`[REC, High]` Semantic HTML, keyboard navigation, visible focus, sufficient contrast in both themes, alt text on all imagery, reduced-motion honored, fully responsive (desktop→mobile), 3D degrades gracefully on low-power devices.

## 7. Anti-template guardrails
`[INFER, High]` Avoid the current AI-portfolio clichés (warm-cream + serif + terracotta; lone acid-green pop on near-black; purple→blue gradient hero; Inter/Space-Grotesk-as-default; emoji section markers; everything centered; rounded-card-with-accent-rail). Ground every choice in the engineering subject instead.
