# The Receiver-Limited Floor

**Paper 2 Experiments & Code**

✅ Complete

**Paper Publication:** https://github.com/Windstorm-Institute/receiver-limited-floor  
**Windstorm Institute:** https://windstorminstitute.org

---

## Quick Start

```bash
# Clone and setup
git clone https://github.com/Windstorm-Labs/receiver-limited-floor.git
cd receiver-limited-floor
pip install torch transformers datasets pandas matplotlib scipy

# Run full experiment (8 hours, 1,749 models)
python run_full_experiment.py

# Or analyze existing results
python analyze_full.py
```

---

## Reproducibility Info

**Verified:** 2026-03-29 on RTX 5090
- Python 3.11.6
- PyTorch 2.2.0
- Transformers 4.38.0
- CUDA 12.1

**Runtime:** ~8 hours for full 1,749 model sweep

---

## Results Preview

**Key Result:** BPT independent of vocabulary size (p = 0.643)

| Metric | Value |
|--------|-------|
| Models evaluated | 1,749 |
| Mean BPB | 0.50 |
| Spearman ρ (BPB vs log₂V) | 0.042 |
| p-value | 0.643 |

See `results/statistical_summary.txt` for full analysis.

---

## Series Index

| # | Paper | Status | Key Result |
|---|-------|--------|------------|
| 1 | [Fons Constraint](https://github.com/Windstorm-Labs/fons-constraint) | ✅ Published | 64-codon alphabet |
| 2 | [Receiver-Limited Floor](https://github.com/Windstorm-Labs/receiver-limited-floor) | ✅ Complete | Vocab-independent BPT |
| 3 | [Throughput Basin](https://github.com/Windstorm-Labs/throughput-basin) | ✅ Published | 31-system convergence |
| 4 | [Dissipative Decoder](https://github.com/Windstorm-Labs/dissipative-decoder) | ✅ Published | Regime A/B analysis |
| 5 | [Serial Decoding Basin τ](https://github.com/Windstorm-Labs/serial-decoding-basin) | ✅ Published | τ = 4.16 ± 0.19 bits |
| 6 | [Inherited Constraint](https://github.com/Windstorm-Labs/inherited-constraint) | ✅ Published | AI inherits biology |
| 7 | [AGI Extensions](https://github.com/Windstorm-Labs/agi-extensions) | 🚧 In Progress | Data vs architecture |

Legend: ✅ Complete (paper + code) | ✅ Published (paper on Zenodo) | 🚧 In Progress



---

## About Windstorm-Labs

This organization contains the experimental code, data, and analysis supporting the Windstorm Institute paper series. Each repository is designed for reproducibility and extension.

**Questions?** Open an issue.  
**Want to contribute?** Fork and PR.  
**Found a bug?** Let us know.

---

*License: MIT for code, CC BY 4.0 for data*
