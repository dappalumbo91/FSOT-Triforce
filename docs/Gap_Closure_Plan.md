# FSOT Triforce – Gap Closure Plan

**Goal**: Systematically close the main gaps in the model before expanding further, so that comparisons with real observational data become more quantitative and credible.

## Identified Gaps (Prioritized)

| Priority | Gap | Impact | Current State |
|----------|-----|--------|---------------|
| 1 | Physical mapping of "structure density" and "trinary coherence" to real astrophysical quantities | High | Schematic / hand-tuned |
| 2 | Absolute scale calibration for BAO (Mpc) and NANOGrav strain | High | Normalized or relative only |
| 3 | Frequency spectrum modeling for NANOGrav | Medium | Basic power-law |
| 4 | Survey geometry / redshift-space distortion effects for BAO | Medium | Not included |
| 5 | Source vs propagation modeling (especially NANOGrav) | Medium | Mostly propagation only |

## Stage 1 Plan (Immediate Focus)

### 1.1 Improved Parameter Mapping
- Define clearer physical meaning for "structure density" (e.g. map to local overdensity δ or large-scale structure contrast).
- Define "trinary coherence" as a measure of vibrational order / coupling strength in the fluid spacetime.
- Create conversion functions between abstract parameters and physical quantities.

### 1.2 Absolute Scale Calibration
- Calibrate BAO output to physical Mpc scale (target ~150 Mpc sound horizon).
- Calibrate NANOGrav strain to physical units (target ~2.4 × 10^{-15} characteristic strain).
- Update unified simulator with these calibrations.

### 1.3 Targeted Calibration Sweeps
- Run sweeps focused on realistic density/redshift ranges relevant to current observations.
- Generate updated summary statistics and comparison tables.

## Stage 2 (Next)

- Add realistic frequency-dependent spectral shape for NANOGrav.
- Include basic redshift-space distortion and survey geometry effects for BAO.
- Begin distinguishing source vs propagation contributions where relevant.

## Success Criteria

- Model outputs for BAO and NANOGrav are in physical units and within ~20-30% of observed central values (or clearly explainable deviations).
- Parameter mapping is documented and reproducible.
- Updated comparison tables show improved quantitative agreement.

## Timeline

Stage 1 work begins immediately. Stage 2 will follow once Stage 1 outputs are stable.

---

*This plan ensures we build on a solid, well-calibrated foundation before expanding into new observables or deeper phases.*