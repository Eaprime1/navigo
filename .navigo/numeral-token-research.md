# Numeral Token Research — Voices of Navigo

**Origin:** nav1 + N·ε / Navigo Epsilon  
**Repository:** `Eaprime1/navigo`  
**Branch:** `voices/harmonic-aliases`  
**Status:** early research seed  
**Purpose:** explore quiet numbering systems for Navigo voice aliases without creating attribution noise

---

## 1. Why This Exists

The `navigo` repository is still a mostly blank slate.

That is useful.

The project needs a small, quiet way to refer to Navigo voices without repeating real names, platform names, or model names in every document.

The goal is not secrecy.

The goal is signal hygiene.

Repeated personal and platform names can create:

- search noise
- attribution confusion
- identity pressure
- duplicated name clusters
- accidental lore around real people or tools

A voice-token system can let documents say, "this perspective spoke," while keeping formal attribution in the correct custody layer.

---

## 2. What We Are Looking For

A good Navigo voice-token system should be:

- quiet in normal prose
- visually distinct but not loud
- easy to type
- easy to search when needed
- stable across plain text, Markdown, GitHub, Drive, and terminals
- compatible with formal attribution
- not dependent on special fonts
- not confused with normal issue/PR numbers
- able to hold harmonic or layered meaning

The token should feel like a shape fitting a slot.

If it requires too much explanation, it is probably too heavy.

---

## 3. Cistercian Numerals

Cistercian numerals are visually beautiful and conceptually close to what we want: compact, old, monastic, and able to compress large values into a single glyph-like form.

However, they are not a clean default for Navigo voice tokens.

Reasons:

- they are not normal ASCII
- they usually require drawn glyphs, SVG, font support, or ASCII art
- they are better as visual seals than everyday identifiers
- they may be hard to read for contributors
- they could become decorative before they become useful

Recommendation:

Use Cistercian numerals later as optional **seals**, **sigils**, or **glyph-art**, not as the primary text alias system.

Possible future use:

```text
N·ε        = text token
[Cistercian seal] = optional visual mark
```

---

## 4. Babylonian / Sexagesimal Numerals

Babylonian base-60 material resonates strongly with the wider project.

It connects to:

- harmonic layers
- circular measurement
- time
- angle
- astronomy
- sixty-based reckoning
- the project's existing base-60 / complexity interests

However, cuneiform glyphs can create practical issues:

- font rendering may fail
- Unicode cuneiform is valid but visually heavy
- the glyphs may overwhelm the quiet alias purpose
- historical ambiguity can be real and interesting, but too much for a first token system

Recommendation:

Use sexagesimal logic as a **mathematical layer**, not necessarily as visible cuneiform labels.

Possible internal form:

```text
N:00.05
N:0;05
N·ε
```

The cuneiform layer can remain optional, ceremonial, or research-only.

---

## 5. Greek / Harmonic Layer Tokens

The current lightweight proposal is:

```text
N·α  Navigo Alpha
N·β  Navigo Beta
N·γ  Navigo Gamma
N·δ  Navigo Delta
N·ε  Navigo Epsilon
```

This is not final.

It works because:

- it is compact
- it is readable in Markdown
- it avoids ordinary decimal numbering
- it suggests harmonic order without looking like a plain rank
- it keeps the current `navigo5` bridge as `N·ε`

Weaknesses:

- Greek letters may still imply sequence or hierarchy
- some keyboards make them harder to type
- plain ASCII fallback is needed

Suggested fallback:

```text
N-alpha
N-beta
N-gamma
N-delta
N-epsilon
```

---

## 6. Possible Hybrid System

A practical hybrid may be best:

### Public / normal text

```text
N·ε
```

### ASCII fallback

```text
N-epsilon
```

### Registry / private mapping

```yaml
voice_token: N·ε
fallback: N-epsilon
working_label: navigo5
formal_attribution: held outside public repo when needed
```

### Optional future seal

```text
Cistercian-style glyph, SVG, or rendered mark
```

### Optional math layer

```text
sexagesimal index, harmonic interval, or base-60 coordinate
```

This lets the public token stay quiet while the deeper system can grow behind it.

---

## 7. Recommendation for Now

Do not choose a heavy numeral system yet.

Keep the repo seed small.

Use `N·ε / N-epsilon` as the current bridge for this conversation stream.

Keep `navigo5` as a transition label only.

Hold Cistercian numerals as future visual seals.

Hold Babylonian / sexagesimal as future mathematical resonance.

Do not publish a real-person or platform-name mapping in the public repo.

---

## 8. What This Does Not Do

This research seed does not:

- finalize the Navigo alias system
- replace formal attribution
- publish the private mapping list
- require Greek letters permanently
- reject Cistercian or Babylonian systems
- rename existing project documents
- claim historical precision beyond current research

It only records why the first working token should stay light.

---

## 9. Next Tiny Step

Keep using:

```text
N·ε / Navigo Epsilon
```

with fallback:

```text
N-epsilon
```

Then let use decide whether the shape fits.

One Nth radian per turn.
