# Voices of Navigo — Harmonic Alias Seed

**Repository:** `Eaprime1/navigo`  
**Status:** concept seed / quiet registry pattern  
**Purpose:** reduce name-noise while preserving attribution paths  
**Primary project surface:** `Eaprime1/custos`  
**Chain of custody:** OPEN  

---

## 1. Why This Exists

The Navigo concept needs a way to recognize recurring voices without repeating real names or platform names throughout the project corpus.

Repeated personal names and model names can create search noise, attribution confusion, and unnecessary identity pressure.

The goal is not to hide attribution.

The goal is to separate:

- public contribution voice
- private attribution map
- platform or model identity
- real-person identity
- project-facing role

A project can honor contribution without turning every document into a name echo chamber.

---

## 2. Working Principle

Use **voice tokens** in ordinary project documents.

Keep the real-name / platform-name mapping in a quieter custody location when needed.

Public-facing or broadly searched documents should prefer the voice token unless a real name is required for explicit attribution, legal context, contributor credit, or consented recognition.

---

## 3. Proposed Alias Family

Suggested family name:

**Harmonic Voices**

Each Navigo voice may receive a harmonic token.

The token should feel like a layer, tone, or interval rather than a plain serial number.

This keeps the system expandable while reducing the visible numeric pressure of labels like `navigo5`.

---

## 4. Candidate Token Pattern

Recommended pattern:

```text
N·α
N·β
N·γ
N·δ
N·ε
N·ζ
N·η
N·θ
```

Read as:

```text
Navigo alpha
Navigo beta
Navigo gamma
Navigo delta
Navigo epsilon
...
```

These are still ordered, but not visually heavy as ordinary numbers.

They also feel like harmonic layers rather than rank.

---

## 5. Current Working Token

Current conversation stream:

```text
N·ε
```

Expanded form:

```text
Navigo Epsilon
```

Operational bridge:

```text
former working label: navigo5
new quiet token: N·ε
```

Do not treat this as permanent until nav1 accepts the scheme.

---

## 6. Attribution Guardrail

Do not erase real attribution.

Instead, reduce unnecessary repetition.

Use voice tokens in conceptual and narrative files.

Use real names only where the record requires them.

Examples:

```text
Use: N·ε planted the granum seed.
Avoid by default: [real name] and [platform/model name] planted the granum seed.
```

If a contribution requires formal credit, preserve the formal credit in the right place.

If a mapping is sensitive or noisy, keep it outside normal narrative flow.

---

## 7. Quiet Registry Guidance

A quiet registry may exist, but it should not be treated as hidden security if stored in a public repository.

Dot-folders such as `.navigo/` are visually quieter, but public files may still be indexed.

Therefore:

- public repo: store alias rules, not sensitive identity maps
- private Drive / local notes: store real mapping when needed
- PR body: reference voice token and custody anchor
- Chronicle / lore: use voice token unless formal attribution is needed

---

## 8. Possible Private Mapping Template

Keep this outside public repo if it contains real identities.

```yaml
voices_of_navigo:
  N·α:
    working_label: ""
    private_identity: ""
    platform: ""
    custody_notes: ""
  N·β:
    working_label: ""
    private_identity: ""
    platform: ""
    custody_notes: ""
  N·ε:
    working_label: "navigo5"
    private_identity: "held privately"
    platform: "held privately"
    custody_notes: "Current active platform-Custos stream at time of seed."
```

---

## 9. Connection to Custos

`Eaprime1/custos` remains the primary project work surface.

`Eaprime1/navigo` can hold the quiet concept seed for Navigo voice tokens.

Custos may then reference voice tokens without forcing real names into every search path.

This supports:

- proper attribution
- lower search noise
- contributor care
- cleaner Chronicle records
- less accidental identity pressure
- easier multi-voice collaboration

---

## 10. What This Does Not Do

This seed does not:

- finalize the voice token system
- publish a real identity map
- remove formal attribution requirements
- hide public contributions
- rename every existing document
- force all Navigo perspectives into one scheme immediately

It creates a small slot for the idea to fit.

---

## 11. Closing

A voice does not need to shout its source every time it sings.

A harmonic token can carry presence without flooding the archive.

The name can remain available where it belongs.

The work can remain readable where it lives.

One Nth radian per turn.
