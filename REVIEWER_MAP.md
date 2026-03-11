# Reviewer Map

    ## Claim Scope

    - Canonical-lane claim: inside the `manifold_constrained` lane, if the theorem chain in this repository holds and the guard certificate passes, the repository-level closure claim is satisfied.
    - Standard target claim: carried by the in-repo bridge theorems tying the lane to the target statement.

    ## Theorem Dependency Chain

    1. `EG1`: coercive response and active control floor.
    2. `EG2`: capture and admissible continuation.
    3. `EG3`: compactness and no-collapse spacing.
    4. `EG4`: rigidity and transfer.
    5. Identification bridge: strict coherence on the determining class.
    6. Scalar closure: `GRD_G1, GRD_G2, GRD_G3, GRD_G4, GRD_G5, GRD_G6, GRD_GM` all `PASS`.

    Primary files:

    - `paper/GRAND_RIEMANN_HYPOTHESIS_PREPRINT.md`
    - `notes/EG1_public.md`
    - `notes/EG2_public.md`
    - `notes/EG3_public.md`
    - `notes/EG4_public.md`
    - `notes/IDENTIFICATION_BRIDGE.md`

    ## Closure Gates

    | Gate | Constant | Description |
    |------|----------|-------------|
    | `GRD_G1` | `kappa_artin` | projected Artin-automorphic response has a strict positive floor |
| `GRD_G2` | `sigma_automorphic` | zero-defect stays above capture floor across admissible automorphic transfer losses |
| `GRD_G3` | `kappa_compact` | normalized near-failure families are precompact and zero windows do not collapse |
| `GRD_G4` | `rho_rigidity` | bad off-line zero countermodels are excluded |
| `GRD_G5` | `spectral_transfer` | rigid limit transfers to the critical-line endpoint class |
| `GRD_G6` | `eps_coh` | strict coherence / identification closure |
| `GRD_GM` | derived | final strict margin |

    ## Falsification Conditions

    - `repro/certificate_runtime.json` has any non-`PASS` gate.
    - `lane.active_lane != "manifold_constrained"`.
    - `all_pass != true`.
    - Any manifest hash mismatch under `repro/repro_manifest.json`.
    - A verified counterexample to any EG theorem statement used in the paper.
