# te-controfase — The Technology of Controfase

**Home of the *Tecnologia di Controfase* series** (Ordinative Sciences Press · Fabio Ghioni). Part of the Ordinative Sciences programme — the Technology of Expressions.

> *Controfase* (Italian; the term is canonical and has no adequate English equivalent — literally, counter-phase) is a universal ordinative phase-shift operator: applied to a system locked in reactive repetition, it introduces a phase displacement into the automatic stimulus-response sequence, interrupts its inertia, and reopens the field in which choice becomes possible.

## Contents

| Path | What it is |
|---|---|
| `Controfase_Vol1_UNIFIED.md` | **Volume 1: Fondamenti** (Italian, native composition) — the complete foundational treatise in one AI-parsing-friendly Markdown file: YAML front matter, bilingual IT/EN abstracts, Prologue, Introduction, 23 chapters in 6 parts, Glossary, Appendices A–D. ~51,000 words, v1.2 |
| `Controfase_Vol1_EN_AI.md` | **Volume 1: Foundations** (English, native composition) — the same treatise composed natively in English, in the AI-optimised deposit form: YAML front matter with ORCID, title page, table of contents, the 11 diagrams of the print edition rendered as readable ASCII with their captions, and a closing colophon. ~54,500 words, v1.0 |
| `dataset/controfase_vol1_instruct.jsonl` | **Bilingual instruction dataset** (80 examples, 40 IT + 40 EN) distilled from Volume 1 for LoRA fine-tuning — chat format aligned with [`te-ordinative-lora`](https://github.com/anckhalion/te-ordinative-lora). Bilingual pairs are Axiom 0 embedded in training data: what survives translation is structure |
| `dataset/README_DATASET.md` | Dataset documentation: format, coverage, validation, extension guidelines |

## Volume 1 — what it establishes

- The **formal definition** of the operator at two levels: the deliberate act `C(s_t)` and the embedded structure `C[f]`, joined by the promotion proposition (iterated acts rewrite the transition law).
- The **energetic accounting**: stimulus energy is received by the relational field, and the inverted configuration is financed by the source itself.
- The **topology of applicability** (SHACK states), the **four-state execution algorithm**, and **five falsifiability criteria** (F1–F5).
- The **phenomenological signature** (PSC): three markers by which an observer's own reactions diagnose an encounter with Controfase — anchored to a peer-reviewed fluid-dynamics experiment (Singh et al., *Communications Physics* 9:123, 2026, DOI [10.1038/s42005-026-02603-w](https://doi.org/10.1038/s42005-026-02603-w)).
- Controfase traced across **seven domains** — physical, cognitive-relational, artificial, civilizational, the physical frontiers, time, and biological systems.
- **Intrinsic Controfase** (Proposition 20.1): in a field structured by an attractor, every emission evokes from the field its own structural complement; the annulment of what is incoherent with the attractor is a law of the field, of which the operator's two forms are local incarnations.
- Explicit **confidence grades** (S0–S3) throughout, and five open limits declared as a research programme.

The volume underwent independent external review (September 2026); the review's 13 patches are incorporated in v1.1.

## Language editions

Two editions, **each a native composition in its own language** — neither is a translation of the other, and each carries its own identifiers. Ontology, structure and equations are identical; the expression is original in each language.

| | Italian | English |
|---|---|---|
| Title | *La Tecnologia di Controfase — Volume 1: Fondamenti* | *The Technology of Controfase — Volume 1: Foundations* |
| Print ISBN | 979-12-82603-20-1 | 979-12-82603-22-5 |
| Zenodo DOI | [10.5281/zenodo.22542621](https://doi.org/10.5281/zenodo.22542621) (concept) | 10.5281/zenodo.23020283 |
| Pages | 237 | 237 |

**A note on the operator's name.** *Controfase* stays Italian across the whole programme and is never translated as a term of its own; "counter-phase" is its gloss on first occurrence, and on its own names the wave phenomenon. This repository's older text used "counter-phase" as the name; the volumes and metadata follow the canonical rule, and the remaining occurrences in `dataset/` are being brought in line.

## The series

1. **Volume 1: Fondamenti** — the foundational treatise (this repository).
2. **Volume 2** (in preparation) — the operational manual: Controfase applied to individual life (conflict, anxiety, approval-seeking, decision, the shortcut).

## The Ordinative Sciences ecosystem

- [`te-ordinative-algebras-en`](https://github.com/anckhalion/te-ordinative-algebras-en) — Semantic Algebra & Proportional Algebra (DOI: 10.5281/zenodo.20059540)
- [`te-oct`](https://github.com/anckhalion/te-oct) — Ordinative Category Theory (DOI: 10.5281/zenodo.20059532)
- [`te-ordinative-lora`](https://github.com/anckhalion/te-ordinative-lora) — LoRA infrastructure & TE instruction dataset (DOI: 10.5281/zenodo.19337864)
- Foundation: [ordinativescience.foundation](https://ordinativescience.foundation) · Academy: [ordinativescience.academy](https://ordinativescience.academy)

## Citing

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22542621.svg)](https://doi.org/10.5281/zenodo.22542621)

See `CITATION.cff`, which declares both editions. Italian edition — Zenodo concept DOI **10.5281/zenodo.22542621** (always resolves to the latest version). English edition — DOI **10.5281/zenodo.23020283**.

## License

[CC BY-NC-SA 4.0](LICENSE) — Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. © 2026 Fabio Ghioni.

---

### Nota in italiano

Questo repository è la casa della serie *Tecnologia di Controfase*, in due edizioni. `Controfase_Vol1_UNIFIED.md` contiene il **Volume 1: Fondamenti** integrale (composizione nativa italiana, v1.2, ~51.000 parole): frontespizio YAML, abstract bilingue, Prologo, Introduzione, 23 capitoli in sei parti, Glossario e quattro Appendici. `Controfase_Vol1_EN_AI.md` contiene **Volume 1: Foundations**, la stessa opera composta nativamente in inglese (~54.500 parole), nella forma di deposito ottimizzata per l'IA: indice, gli undici diagrammi dell'edizione a stampa resi in ASCII leggibile con le loro didascalie, colophon. Nessuna delle due è traduzione dell'altra: ciascuna ha ISBN e DOI propri. La cartella `dataset/` contiene il dataset bilingue di istruzioni per il fine-tuning LoRA. Licenza CC BY-NC-SA 4.0.
