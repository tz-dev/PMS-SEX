# PMS–SEX

**From Impulse to Self-Binding: A Praxeological Grammar of Sexuality (Δ–Ψ)**

**PMS–SEX is a formal application profile of the [Praxeological Meta-Structure (PMS)](https://github.com/tz-dev/Praxeological-Meta-Structure-Theory)** — a generative operator framework (Δ–Ψ) for modelling praxis, frames, non-events, stabilization, asymmetry, temporality, distance, integration, and self-binding.

Where many approaches to sexuality default to psychology, morality, diagnosis, taxonomy, or advice, **PMS–SEX stays strictly praxeological**: it reconstructs **what sexual configurations produce over time** — especially **cost layouts**, **drift chains**, **outer legibility**, and **viability corridors** — without person-typing, moral ranking, clinical interpretation, or instructional content.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19787200.svg)](https://doi.org/10.5281/zenodo.19787200)

---

## What PMS–SEX Is

PMS–SEX is:

* a **scene grammar** for explicit sexual practice: enactments, roles, frames, and non-events
* a **consequence model** for how repetition stabilizes (Α), how costs distribute (Ω), and how time makes effects durable (Θ)
* a framework that treats **absence / withdrawal / non-occurrence (Λ)** as structurally active under expectation
* a **viability-and-drift lens**: when configurations remain governable, and when drift becomes likely
* a way to discuss “risk” as **praxeological structure**, not as moral verdict or psychological diagnosis
* an overlay that distinguishes **internal framing**, **outer legibility**, **publicness**, and **temporal carryover** without collapsing them

**Guiding formula:**

> **Non-clinical in stance /  
> Structural in mechanism /  
> Guardrailed in application**

---

## What PMS–SEX Is *Not*

PMS–SEX is not:

* a therapy framework or clinical model
* a moral doctrine, purity narrative, or normative sex ethics
* a typology of people, desires, orientations, or “kinds of sexuality”
* a how-to manual, optimization method, or risk-management procedure
* a tool for sanctioning, humiliation, public accusation, or person-worth judgments

PMS–SEX evaluates **configurations**, not persons.  
Critique targets **structures, trajectories, and cost handling**, not identities.

---

## Core Thesis

PMS–SEX argues that sexual practice becomes structurally readable because:

* **Λ (non-event)** is active: absence, withdrawal, hesitation, and delay can steer under expectation.
* **Α (attractor)** stabilizes: repetition consolidates scripts and narrows options.
* **Ω (asymmetry)** distributes costs: access, exposure, obligation, exit margin, and repair load rarely remain symmetric.
* **Θ (temporality)** accumulates: consequences persist and reshape exit realism over time.
* **Φ (recontextualization)** can reframe a scene, but does not rewind accumulated structure.
* **Χ (distance)** is the decisive limiter: without practical stop-capability and meta-position, drift becomes hard to intercept.
* **Σ (integration)** is required where contradictory demands must be held without denial or coercive simplification.
* **Ψ (self-binding)** is a threshold: local events and non-events can become biography-relevant, binding-relevant, or identity-relevant under time.

> Sexuality does not “cost” because it is immoral.  
> It costs because it happens under bodies, frames, asymmetry, repetition, and time.

---

## Relation to PMS

PMS–SEX is built directly on the canonical PMS operator grammar (Δ–Ψ), as defined in [`PMS.yaml`](https://raw.githubusercontent.com/tz-dev/Praxeological-Meta-Structure-Theory/refs/heads/main/model/PMS.yaml).

Current dependency:

```text
PMS.yaml      schema_version: PMS_1.3
PMS-SEX.yaml  schema_version: PMS-SEX_1.1
````

PMS–SEX:

* introduces no new PMS operators
* redefines no operators
* rewrites no dependencies
* modifies no derived PMS axes
* treats reduced signatures as shorthand only
* treats publicness, outer legibility, body remainder, and path-cost as overlay concepts, not operators

Canonical spine:

```text
Δ → ∇ → □ → Λ → Α → Ω → Θ → Φ → Χ → Σ → Ψ
```

---

## Method Guards

PMS–SEX is valid as a PMS application only under the standard gate:

* **Χ — Distance preserved:** analysis maintains meta-position and stop-capability; no fusion into urgency, accusation, enforcement, or role-perspective.
* **Reversibility preserved:** claims remain scene-bound, revisable, and configuration-specific; no global person labels.
* **D — Dignity-in-Practice preserved:** critique avoids shaming, humiliation, diagnosis, orientation taxonomy, and person-ranking.

Two central guard sentences:

> **Internal framing does not erase outer form.**
> **Naming outer legibility does not rank persons.**

PMS–SEX may describe **path-cost**, **stabilization burden**, **disturbance**, or **configuration-level deviation**, but only as structural language. These terms do not diagnose persons, rank identities, lower dignity, or imply moral pathology.

---

## Inner / Outer / Public Layer Discipline

PMS–SEX distinguishes four layers that may overlap but must not be collapsed:

| Layer                  | Question                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------- |
| **Internal framing**   | How is the scene inhabited, narrated, or lived from within?                                       |
| **Outer legibility**   | What action-form is structurally readable under asymmetry, exposure, repetition, and consequence? |
| **Publicness**         | Does visibility, documentation, reputation, or circulation amplify consequences?                  |
| **Temporal carryover** | How does the scene continue across Θ?                                                             |

Publicness is treated as a **□ extension**: it may distribute, amplify, document, repeat, or sedimentize consequences, but it does not necessarily generate the primary action-form.

---

## Repository Layout

This repository ships the PMS–SEX paper, model profile, model specification, shared CSS, and worked examples.

```text
PMS-SEX/
├── README.md
├── LICENSE
├── PMS-SEX.md
├── PMS-SEX.html
├── PMS-SEX.pdf
├── css/
│   └── main.css
└── examples/
    ├── Example 1 - Desire as Self-Punishment (Minimal Psychology Trigger).yaml
    ├── Example 1 - Desire as Self-Punishment (Minimal Psychology Trigger).html
    ├── Example 2 - Suspended Binding That Quietly Becomes Possession.yaml
    ├── Example 2 - Suspended Binding That Quietly Becomes Possession.html
    ├── Example 3 - High Intensity + Narrative Safety.yaml
    ├── Example 3 - High Intensity + Narrative Safety.html
    ├── Example 4 - Dignity Collapse without Rule Violation.yaml
    ├── Example 4 - Dignity Collapse without Rule Violation.html
    ├── Example 5 - Pseudo-Symmetry under Real Cost Asymmetry.yaml
    └── Example 5 - Pseudo-Symmetry under Real Cost Asymmetry.html
```

The canonical paper source is `PMS-SEX.md`.
The canonical model source is `PMS-SEX.yaml`.
HTML and PDF are render targets for reading and citation.

---

## Example Suite

The `examples/` directory contains uniform PMS–SEX-conform worked cases.
They are **structural stress tests**, not guides, advice, or case diagnoses.

The examples test:

* drift preparation under Λ→Α→Ω→Θ
* formal consent versus structural cost distribution
* Ψ leak under suspended or limited frames
* Χ erosion under repetition, intensity, or narrative stability
* Dignity-in-Practice as an enactment constraint
* publicness, body remainder, and path-cost as guarded overlays

Included cases:

1. **Consent That Remains Procedurally Valid but Fails Structurally**
   *Formal consent remains intact while Ω, Θ, and Χ drift.*

2. **Desire as Self-Undercutting Configuration**
   *Repetition continues despite known Θ damage and D-in-Practice stress.*

3. **Suspended Binding That Quietly Becomes Possession**
   *Ψ suspension fails through Λ steering, Ω gradients, and Θ solidification.*

4. **High Intensity + Narrative Safety**
   *Narrative safety remains stable while operational containment weakens.*

5. **Dignity Collapse without Rule Violation**
   *Nothing is formally forbidden, yet degradation-form readability emerges through repeated enactment mode.*

---

## Structural Contributions

### 1. Sexuality as Consequence System

PMS–SEX reconstructs sexuality as praxis that produces:

* scripts and attractors (Α)
* cost gradients (Ω)
* trajectory effects (Θ)
* recontextualization pressure (Φ)
* distance or stop-capability stress (Χ)
* binding relevance (Ψ)

### 2. Non-Event Seriousness

Withdrawal, silence, delay, hesitation, and absence are treated as structurally active under expectation — not as “nothing happened.”

### 3. Viability Without Moralizing

Functional practice is defined by **governability**, not normality:

```text
□ explicit
+ Ω nameable
+ Θ realistic
+ Χ operative
+ Λ tolerable
+ Ψ handled
(+ Σ reachable)
= structurally governable configuration
```

### 4. Outer Legibility Without Person-Ranking

PMS–SEX can name externally readable action-forms — such as asymmetry-form, exposure-form, humiliation-form, or degradation-form — without converting that analysis into moral verdict, identity judgment, diagnosis, or person-worth claim.

### 5. Path-Cost Without Pathology

PMS–SEX may describe higher stabilization burden, disturbance, or path-cost only at the level of configuration dynamics.

> Disturbance names structural stabilization burden, not human worth.

### 6. Optional Docking to MIP

Where public critique or system-level evaluation is required, PMS–SEX may dock to **MIP** without merging layers:

* PMS–SEX maps structure.
* MIP evaluates critique legitimacy.
* Outer legibility alone does not automatically authorize public accusation.

---

## Intended Use

PMS–SEX is intended for:

* structural theorists analysing sexuality without diagnosis or moral ranking
* discourse contexts where critique must be hard but non-degrading
* modelling drift, cost distribution, exit realism, and viability under time
* analysing explicit frames without reducing them to intent, identity, or pathology
* maintaining consequence realism without prescriptive or instructional content

It is not intended for giving instructions, escalating risk, optimizing sexual practice, diagnosing persons, or ranking identities.

---

## Links & Resources

*PMS-SEX* is situated within a broader **praxeological ecosystem** that connects formal operator theory, applied anthropology, structural ethics, and domain-specific analyses.
The resources below provide **canonical references, adjacent applications, and tooling** for working with PMS-SEX **without mixing layers**.

| Category        | Resource                                                                                                                           | Description                                                                                      |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Model website   | [PMS Theory Site](https://pms-theory.netlify.app)                                                                                  | Canonical PMS theory reference                                                                   |
| Book websites   | [Maturity in Practice (EN)](https://maturity-in-practice.netlify.app)                                                              | *Maturity in Practice* — English edition (praxeological anthropology)                            |
|                 | [Reife im Vollzug (DE)](https://reife-im-vollzug.netlify.app)                                                                      | *Reife im Vollzug* — Deutsche Ausgabe                                                            |
|                 | [PMS Stack](https://pms-stack.netlify.app)                                                                                         | PMS-STACK reference architecture                                                                 |
| Amazon          | [Maturity in Practice (EN)](https://www.amazon.com/dp/B0G4XBKNNR)                                                                  | *Maturity in Practice: A Praxeological Anthropology* — English edition                           |
|                 | [Reife im Vollzug (DE)](https://www.amazon.de/dp/B0G4SPBDQD)                                                                       | *Reife im Vollzug: Eine praxeologische Anthropologie* — Deutsche Ausgabe                         |
|                 | [PMS-STACK](https://www.amazon.com/dp/B0G6G7V38P)                                                                                  | *PMS-STACK — A Praxeological Operating System Architecture*                                      |
| GitHub (papers) | [PMS Theory / Repo](https://github.com/tz-dev/Praxeological-Meta-Structure-Theory)                                                 | Canonical PMS grammar, theory & YAML definitions                                                 |
|                 | [Maturity-in-Practice](https://github.com/tz-dev/Maturity-in-Practice)                                                             | Book sources & applied praxeological anthropology                                                |
|                 | [PMS-QC](https://github.com/tz-dev/PMS-QC)                                                                                         | PMS-QC — Praxeological Meta-Structure for Quantum Computing                                      |
|                 | [PMS-LOGIC](https://github.com/tz-dev/PMS-LOGIC)                                                                                   | PMS-LOGIC — Structural Responsibility, Logical Limits, and Post-Moral Effects                    |
|                 | [PMS-ANTICIPATION](https://github.com/tz-dev/PMS-ANTICIPATION)                                                                     | PMS-ANTICIPATION — Structural Conditions, Risks, and Viability of Anticipatory Praxis            |
|                 | [PMS-CRITIQUE](https://github.com/tz-dev/PMS-CRITIQUE)                                                                             | PMS-CRITIQUE — From Irritation to Correction: A Praxeological Grammar of Critique                |
|                 | [PMS-EDEN](https://github.com/tz-dev/PMS-EDEN)                                                                                     | PMS-EDEN — Structural Drift from Praxis to Comparison and Reciprocity Loss                       |
|                 | [PMS-SEX](https://github.com/tz-dev/PMS-SEX)                                                                                       | PMS-SEX — From Impulse to Self-Binding: A Praxeological Grammar of Sexuality                     |
|                 | [PMS-CONFLICT](https://github.com/tz-dev/PMS-CONFLICT)                                                                             | PMS-CONFLICT — Conflict as Stabilized Incompatibility: Cost, Binding, and Tragic Non-Integration |
|                 | **[PMS-AXIOM](https://github.com/tz-dev/PMS-AXIOM)**                                                                               | PMS-AXIOM — Cartography of Classical Closure-Demands Across the PMS Stack                        |
| Custom GPTs     | [PMS Model Assistant](https://chatgpt.com/g/g-69358a2a4980819183da6a97893389cf-pms-model-assistant)                                | Interactive PMS.yaml exploration & validation                                                    |
|                 | [Maturity in Action](https://chat.openai.com/g/g-693460d3def48191ad08647301645a2e-maturity-in-action-a-praxeological-anthropology) | Applied praxeological anthropology assistant                                                     |

Raw model references:

* PMS.yaml:
  [https://raw.githubusercontent.com/tz-dev/Praxeological-Meta-Structure-Theory/refs/heads/main/model/PMS.yaml](https://raw.githubusercontent.com/tz-dev/Praxeological-Meta-Structure-Theory/refs/heads/main/model/PMS.yaml)

* MIP YAML:
  [https://raw.githubusercontent.com/tz-dev/Maturity-in-Practice/refs/heads/main/MIPractice_case_v2.0_full_with_model_reference.yaml](https://raw.githubusercontent.com/tz-dev/Maturity-in-Practice/refs/heads/main/MIPractice_case_v2.0_full_with_model_reference.yaml)

---

## Citation

When referencing PMS–SEX, please cite both PMS–SEX and PMS:

**PMS–SEX**

> T. Zöller (2026): *PMS–SEX — From Impulse to Self-Binding: A Praxeological Grammar of Sexuality (Δ–Ψ).*
> `PMS-SEX.yaml`, schema_version `PMS-SEX_1.1`.

**PMS Framework**

> T. Zöller (2025): *Towards a Praxeological Meta-Structure Theory.*
> `PMS.yaml`, schema_version `PMS_1.3`.

---

## License

Unless otherwise stated, all documentation in this repository is licensed under:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

---

## Final Note

PMS–SEX does not tell you what sex *should* be.

It makes visible what sexual configurations **produce** — especially where costs emerge, how drift becomes prepared, how inner framing and outer form can diverge, and why many conflicts arise not from malice but from structural opacity under time, asymmetry, non-event, and repetition.

PMS–SEX remains valid by staying within configuration-language:

> not what persons are,
> but what configurations do over time.
