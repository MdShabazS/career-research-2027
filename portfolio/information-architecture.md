# Portfolio — Information Architecture

Structure the site so a recruiter (5–10 second scan) and an engineer (deep read) both get what they need. Project-first, evidence-led.

## 1. Page/section order
`[REC, High]`
1. **Hero** — name + one specialization line + one signature 3D/interactive moment tied to the work (not generic particles). A skimmer must grasp "embedded engineer who builds real hardware + on-device intelligence" in seconds.
2. **Featured projects** (3–4) — cards → detailed case pages. Top projects visible without scrolling.
3. **Project case pages** — problem → overview → stack → architecture/workflow diagram → what was built (honest contribution) → status → links (repo/demo) → real media.
4. **Experience** — Nokia (high-level, correct tense), iHelp/MITRA (app-side), IEEE EMBS.
5. **Skills** — grouped, honest, project-backed.
6. **About** — short, human, the one identity.
7. **Education / Leadership / Certifications** — compact.
8. **Contact** — form (no plaintext phone), LinkedIn + GitHub only.

## 2. Navigation
`[REC, High]` Persistent, minimal nav (Projects, Experience, About, Contact). Deep-linkable sections. Keyboard-navigable. A "skip to content" affordance because the hero is heavy.

## 3. Content-first, 3D-second loading
`[REC, High]` Meaningful HTML (name, headline, project titles) renders **before** the 3D bundle. The 3D enhances; it is never a blank screen the recruiter waits on. (See [`3d-interaction-research.md`](3d-interaction-research.md).)

## 4. Evidence traceability
`[REC, High]` Every project card links to its GitHub repo and, where possible, a live demo or a video. Metrics shown are the real ones (reference repo); ~93% labeled *reported*. No dead links (a dead link reads as abandoned work).

## 5. Two audiences, one page
`[INFER, High]` Recruiter path = hero → project cards → contact. Engineer path = case page → architecture diagram → repo. The IA must serve both without forcing either to dig.
