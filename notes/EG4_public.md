# EG4 Public Note (Rigidity and Endpoint Transfer)

Canonical wording: `bad-limit exclusion / endpoint transfer`.

In-paper anchor: `paper/GRAND_RIEMANN_HYPOTHESIS_PREPRINT.md` (`GRD_G4`, `GRD_G5`).

## Goal
Separate the rigidity job from the endpoint-transfer job for `proving critical-line zero localization for admissible Artin and automorphic `L`-function families through an admissible spectral-transfer closure architecture`.
The older wording `rigidity and endpoint-transfer` corresponds to bad-limit exclusion plus the bridge into the intended endpoint object.

## Objects

- bad-limit class: candidates extracted by the compactness gate but incompatible with closure.
- rigidity floor: `rho_rigidity`.
- endpoint-transfer lock: `spectral_transfer`.
- coherence interface: `eps_coh` remains available to the bridge and final margin.

## Closure Criterion

`GRD_G4` closes when `rho_rigidity` excludes bad endpoint alternatives: bad off-line zero countermodels are excluded.
`GRD_G5` closes when `spectral_transfer` transfers the surviving endpoint to the intended target class: rigid limit transfers to the critical-line endpoint class.
Together they feed the strict margin `M_GRD`.

## Lemma Chain and Proof Payload

### Lemma EG4.1 (bad-limit exclusion)
Every extracted bad limit contradicts a declared rigidity constraint or leaves the admissible class.

Payload: check `rho_rigidity` in the registry and certificate surfaces.

### Lemma EG4.2 (endpoint transfer)
The surviving rigid representative is locked to the standard problem-side endpoint by `spectral_transfer`.

Payload: read this note together with `notes/IDENTIFICATION_BRIDGE.md`.

### Theorem EG4.3 (rigidity/transfer gate closure)
If bad limits are excluded and the endpoint lock is active, then `GRD_G4` and `GRD_G5` deliver the boundary object needed by the final margin.

## Current Instantiation

- rigidity gate: `GRD_G4`
- rigidity artifact key: `rho_rigidity`
- transfer gate: `GRD_G5`
- transfer artifact key: `spectral_transfer`
- canonical equivalent: `bad-limit exclusion / endpoint identification`
- audit surface: `notes/IDENTIFICATION_BRIDGE.md` and `repro/certificate_runtime.json`
