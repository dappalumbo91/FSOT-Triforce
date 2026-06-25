# Stage 2 Progress – NANOGrav Frequency Spectrum + BAO Survey Effects

## NANOGrav Frequency Spectrum Shaping

Prototype now includes a more realistic frequency-dependent strain:

```python
def nanograv_spectrum(density, frequency):
    coherence = 0.7 + (density * 0.4)
    trinary = coherence * (1 + (density-1)*0.25)
    coupling = 1.0 / (1.0 + (density-1)**2 * 0.82)
    
    # Broken power-law like spectrum (example)
    if frequency < 3e-8:
        exponent = -0.25
    else:
        exponent = -0.35
    
    freq_factor = (frequency / 1e-8) ** exponent
    return 2.38e-15 * trinary * coupling * freq_factor
```

## BAO Survey Geometry Effects (Prototype)

Basic redshift-space distortion factor added:

```python
def bao_with_rsd(density, redshift, mu=0.5):
    # mu = cosine of angle to line of sight
    bao_base = 149 * ...  # from previous calibration
    rsd_factor = 1 + 0.4 * mu**2 * (1 + redshift*0.3)
    return bao_base * rsd_factor
```

## Status

Stage 2 work initiated. Prototypes added for frequency spectrum and basic survey effects. Ready for integration and testing.