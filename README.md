# The Receiver-Limited Floor

**The Receiver-Limited Floor: Rate-Distortion Bounds on Serial Decoding Throughput**

**Paper 2 in the FONS Constraint / Throughput Basin series**

---

## Quick Summary

Tests whether AI language model throughput is receiver-limited (independent of vocabulary size) using 1,749 translation model variants. The M-ary rate-distortion function R_M(ε) provides the theoretical framework.

**Key Finding:** Bits-per-byte shows no correlation with log₂(vocabulary) across 1,749 models (p = 0.643). Throughput is receiver-limited, not sender-limited.

---

## Citation

```bibtex
@article{whitmer2026receiverlimitedfloor,
  title={The Receiver-Limited Floor: Rate-Distortion Bounds on Serial Decoding Throughput},
  author={Whitmer, Grant Lavell III},
  journal={Windstorm Institute},
  year={2026},
  doi={10.5281/zenodo.19323194},
  url={https://zenodo.org/records/19323194}
}
```

---

## Links

- **Website:** https://windstorminstitute.org
- **Published Paper (Zenodo):** https://zenodo.org/records/19323194
- **Windstorm Institute Community:** https://zenodo.org/communities/windstorm-institute/
- **Experiments & Code:** https://github.com/Windstorm-Labs/receiver-limited-floor
- **Compute Required:** ~8 hours on RTX 5090

---

## Repository Contents

- `paper.pdf` — Full academic paper
- `article.html` — Accessible web version

---

## The FONS Constraint / Throughput Basin Series

| # | Paper | Key Finding | Status |
|---|-------|-------------|--------|
| 1 | [Fons Constraint](https://github.com/Windstorm-Institute/fons-constraint) | 64-codon alphabet derivation | Published |
| 2 | [Receiver-Limited Floor](https://github.com/Windstorm-Institute/receiver-limited-floor) | Vocab-independent BPT | Published |
| 3 | [Throughput Basin](https://github.com/Windstorm-Institute/throughput-basin) | 31-system convergence | Published |
| 4 | [Dissipative Decoder](https://github.com/Windstorm-Institute/dissipative-decoder) | Regime A/B analysis | Published |
| 5 | [Serial Decoding Basin τ](https://github.com/Windstorm-Institute/serial-decoding-basin) | τ = 4.16 ± 0.19 bits | Published |
| 6 | [Inherited Constraint](https://github.com/Windstorm-Institute/inherited-constraint) | AI inherits from biology | Published |
| 7 | AGI Extensions (in progress) | Data vs architecture test | — |



---

## About This Series

The FONS (Fons Optimal Numerus Signorum) constraint and Throughput Basin papers investigate whether serial decoding systems — from ribosomes to language models — converge to fundamental information-processing limits. The series combines theoretical derivation, computational experiment, and cross-substrate comparison.

**Principal Investigator:** Grant Lavell Whitmer III  
**Affiliation:** Windstorm Institute, Fort Ann, NY

---

*License: CC BY 4.0*
