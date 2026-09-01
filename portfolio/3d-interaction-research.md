# Portfolio — 3D / Interaction / Performance Research

The technical spine of a premium 3D portfolio that stays fast, usable, and accessible. All targets below are from retrieved 2026 Three.js production guidance.

## 1. Stack choice
- `[FACT, High]` **React Three Fiber (R3F)** suits component-driven portfolio sites; **vanilla Three.js** for the most bespoke, hand-tuned scenes. GSAP/Framer Motion for choreography. (utsubo, creativedevjobs.)
- `[REC, High]` For this candidate: **R3F + Drei + GSAP** — component model is maintainable and the scenes are moderate, not bespoke-agency-level.

## 2. Rendering & fallback
- `[FACT, High]` 2026 default: **WebGPURenderer with automatic WebGL2 fallback** (Three r171+); ship one renderer, Three handles compatibility; migrate to WebGPU only when hitting draw-call walls. Provide a **poster/HTML fallback** when WebGL is unavailable. (utsubo, appscale.)

## 3. Hard performance targets
- `[FACT, High]` **Under 100 draw calls** per frame for smooth 60fps; >500 struggles even on strong GPUs. Monitor `renderer.info.render.calls`. (utsubo.)
- `[FACT, High]` **Instancing/batching:** `InstancedMesh` turns 1,000 objects into 1 draw call; share materials to enable batching. (A cited real case cut 9,000→300 draw calls via instancing.) (utsubo.)
- `[FACT, High]` **Asset compression:** Draco geometry (~90–95% smaller), **KTX2** textures (stay compressed on GPU, ~10× VRAM saving). **LOD** via Drei `<Detailed/>` (30–40% FPS gain in big scenes). (utsubo.)
- `[FACT, High]` **Always dispose** geometry/material/texture on unmount; watch `renderer.info.memory` for leaks. (utsubo.)

## 4. Load strategy (Core Web Vitals)
- `[FACT, High]` **Render meaningful HTML first, defer the 3D bundle** (dynamic import / code-split), lazy-load below-the-fold 3D via IntersectionObserver, show placeholder geometry, use R3F `<Suspense>`. This is how a rich scene still passes CWV. (utsubo, appscale.)

## 5. Mobile & thermal
- `[FACT, High]` `mediump` precision on mobile (~2× faster), keep varyings <3, disable MSAA in post, consider half-res render + upscale (~2× FPS); mind fill-rate and thermal throttling. (utsubo.)

## 6. Accessibility
- `[FACT, High]` Honor **`prefers-reduced-motion`** (disable auto-loops/animation); pause the render loop when a project page is open or the tab is hidden; keep raycasting cheap. (utsubo.)

## 7. What to actually build (engineering-meaningful 3D)
`[REC, High]` Prefer interactions that *are* the evidence:
- An interactive **BCM state machine** (OFF/ACC/ON) the user can drive.
- A rotatable **ESP32/STM32 board** with hotspots explaining peripherals used.
- A **VisionPay** live/looped inference panel.
- A scroll-sequenced "how the firmware loop works" build-up.
One or two of these, done well, beats a generic particle hero.

## Sources
- utsubo.com/blog/threejs-best-practices-100-tips · utsubo.com/blog/best-threejs-websites-2026
- appscale.blog/en/blog/threejs-production-3d-web-2026 · creativedevjobs.com
