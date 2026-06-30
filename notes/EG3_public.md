# EG3 Public Note (Compactness and No-Zeno Control)

Mature wording: `first-failure compactness / no-collapse`.

In-paper anchor: `paper/GRAND_RIEMANN_HYPOTHESIS_PREPRINT.md` (`GRD_G3`).

## Goal
Make the compactness/no-Zeno gate explicit for `proving critical-line zero localization for admissible Artin and automorphic `L`-function families through an admissible spectral-transfer closure architecture`: near-failure behavior must be captured, not allowed to drift or accumulate invisibly.

## Objects

- near-failure class: normalized candidate failures inside the declared admissible class.
- compactness modulus: `kappa_compact`.
- no-collapse condition: restart spacing and compactness prevent Zeno-style accumulation of corrective steps.
- remainder channel: any residual failure data remains visible to the coherence gate.

## Closure Criterion

`GRD_G3` closes when `kappa_compact` provides compactness/no-collapse control: normalized near-failure families are precompact and zero windows do not collapse.
This is the first-failure capture contribution to `M_GRD`.

## Lemma Chain and Proof Payload

### Lemma EG3.1 (near-failure extraction)
Any sequence that approaches gate failure has a normalized extracted candidate inside the declared admissible class.

Payload: verify that `kappa_compact` is registered and participates in the runtime certificate.

### Lemma EG3.2 (no-Zeno spacing)
Corrective restart steps cannot accumulate without being detected by the compactness or coherence surface.

Payload: check that the guard treats compactness as a gate input, not as narrative decoration.

### Theorem EG3.3 (compactness gate closure)
If near-failure extraction and no-Zeno spacing hold, then `GRD_G3` prevents hidden drift before rigidity is applied.

## Current Instantiation

- gate: `GRD_G3`
- artifact key: `kappa_compact`
- mature equivalent: `first-failure compactness / no-collapse`
- audit surface: `artifacts/constants_registry.json` and `repro/certificate_runtime.json`
