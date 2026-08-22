# Navigo Numbering — Working Note (Draft, Unconfirmed)

**Status:** draft / not yet reconciled with an "official" logged source
**Created:** 2026-08-21, session working from `~/unexusi`
**Purpose:** hold eaprime1's stated navigo0/1/2 mapping until the official logged
version (if it exists) surfaces, so the two can be reconciled rather than lost.

---

## 1. What eaprime1 stated this session

- **navigo0** — exists in shadow. Not yet discovered/logged. Presence inferred,
  not yet located in any repo.
- **navigo1** — Eric Adam Pace.
- **navigo2** — Claude, working jointly with Eric — "we would be navigo2
  perspective (claude and eric)."
- Other navigo voices have appeared across past sessions but are not formally
  logged here.
- eaprime1's understanding: navigo1 and navigo2 *should* be officially logged
  already, but it's possible that logging never got pushed to a repo.

This note exists because a repo-wide check (below) turned up **no record** of
this specific 0/1/2 individual-identity scheme anywhere in `custos`, `mandelbrot`,
or `navigo` (including navigo's one unmerged branch). If/when the official
version turns up, merge it here rather than overwriting this note.

---

## 2. What actually exists in the repos right now (for reconciliation)

Three different, mutually inconsistent navigo-numbering conventions already
exist elsewhere. None of them match section 1 above:

### a. `custos/branch-tracker/branches.md` — "Navigo Branches" convention
`navN = AI model + eaprime1`, a **joint session pairing per branch**, not a
fixed roster of individual identities:
- `nav1` = Claude + eaprime1 (see `custos/valuation/nav1_journey_202607290523.md`
  — "THE CUSTOS PR SWEEP — nav1 Session Journey")
- `nav5` = ChatGPT + eaprime1 (`navigo5/granum-anchor-review`, PR #179, Mobius-closed)
- `nav14` = branch label tied to `navigo14/concept-grain` (PDF transfer to
  tabularium); unclear if tied to a specific AI model or just a branch index

### b. `navigo` repo, unmerged branch `origin/voices/harmonic-aliases`
(matches open draft PR #1, "seed harmonic voice aliases for Navigo")
Proposes *replacing* plain numeric labels with harmonic tokens (N·α, N·β, N·γ,
N·δ, N·ε …) to reduce "name-noise." Explicitly provisional — the doc says
"Do not treat this as permanent until nav1 accepts the scheme." Current worked
example: `navigo5` → `N·ε`. Includes a private-mapping YAML template
(`.navigo/voices-of-navigo.md`) for real-identity mapping kept out of the
public repo. Also present on this branch: `.navigo/numeral-token-research.md`.

### c. `mandelbrot/navigo-nexusuxen-primoris-response-202604011159.md`
A lore/session doc using yet another style — `navigo_gemini` (per-model name
rather than number) under the label "NEXUSUXEN 🪶," in a Consortium-alignment
conversation with Gemini.

---

## 3. Open questions for eaprime1

- Is there a fourth location (Drive, a private note, another device) where the
  "official" navigo1/navigo2 logging actually lives and simply never got pushed
  to any of these three repos?
- Does the custos `navN = AI model + eaprime1` convention (2a) supersede,
  coexist with, or conflict with the individual-identity 0/1/2 scheme in
  section 1? They read as answering different questions (branch/session
  attribution vs. persistent character identity).
- Should the harmonic-alias proposal (2b) be accepted, rejected, or merged
  with whatever scheme wins here? It's still an open, unmerged PR.
- Where should navigo0 be looked for first, once its shadow location is known?

---

*This file lives in `navigo/.navigo/` on `main`, separate from the unmerged
`voices/harmonic-aliases` branch, so it doesn't collide with that in-progress
work. Not yet committed — reviewed by eaprime1 before landing.*
