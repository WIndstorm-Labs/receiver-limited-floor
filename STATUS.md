# Windstorm-Labs Status Dashboard

**Last Updated:** 2026-04-08

---

## Overview

| Metric | Value |
|--------|-------|
| Total Papers in Series | 7 |
| Experiments Complete | 1 (Paper 2) |
| Experiments In Progress | 1 (Paper 7) |
| Models Evaluated | 1,749 (Paper 2) |
| GPU Hours Logged | ~12 (Paper 2) |
| GPU Hours Planned | ~100 (Papers 1-7) |

---

## Detailed Status

### Paper 1: Fons Constraint
- **Status:** 📋 Planned
- **Type:** Theoretical derivation
- **Experiments:** N/A (pure theory)
- **Deliverable:** Numerical validation scripts
- **ETA:** —

### Paper 2: Receiver-Limited Floor ✅
- **Status:** ✅ **COMPLETE**
- **Experiments:** 1,749 model vocabulary sweep
- **Hardware:** RTX 5090, ~8 hours
- **Key Result:** BPT independent of vocab (p = 0.643)
- **Data:** 237KB CSV, 5 charts, statistical summary
- **Reproducible:** Yes, verified 2026-03-29

### Paper 3: Throughput Basin
- **Status:** 📋 Planned
- **Type:** Meta-analysis
- **Experiments:** Data compilation from 31 systems
- **Deliverable:** Cross-substrate analysis scripts
- **ETA:** —

### Paper 4: Dissipative Decoder
- **Status:** 📋 Planned
- **Experiments:** 27-model energy benchmark
- **Hardware:** RTX 5090, ~6 hours
- **Key Result:** α_capacity = 0.937 (Regime B)
- **Deliverable:** Power profiling + analysis
- **ETA:** —

### Paper 5: Serial Decoding Basin τ
- **Status:** 📋 Planned
- **Type:** Computational simulation
- **Experiments:** 5 convergence experiments
- **Hardware:** CPU-based simulations
- **Key Result:** τ₂₁ = 4.157 bits
- **Deliverable:** Simulation suite (5 scripts)
- **ETA:** —

### Paper 6: Inherited Constraint
- **Status:** 📋 Planned
- **Experiments:** 7-corpus shuffling cascade
- **Hardware:** RTX 5090, ~4 hours
- **Key Result:** Structural bonus = 6.74 bits
- **Deliverable:** Evaluation harness + shuffling utils
- **ETA:** —

### Paper 7: AGI Extensions 🚧
- **Status:** 🚧 **IN PROGRESS**
- **Experiments:** 6 new experiments
- **Hardware:** RTX 5090, 32-56 hours total
- **Priority:** Exp 3 (Recurrent vs Transformer) first
- **Key Question:** Data-driven vs architectural constraint?
- **Deliverable:** 6 runnable experiment protocols
- **ETA:** Experiments ready, awaiting execution

---

## Resource Requirements

| Paper | GPU Hours | Storage | Priority |
|-------|-----------|---------|----------|
| 2 | 8 | 250MB | Done ✅ |
| 4 | 6 | 100MB | Medium |
| 6 | 4 | 50MB | Medium |
| 7 | 32-56 | 500MB | **High** |
| **Total** | **~100** | **~1GB** | — |

---

## Blockers

None currently.

---

## Next Actions

1. **Execute Exp 3** (Recurrent vs Transformer) — 4-8 hrs, lowest risk
2. **Execute Exp 2** (Quantization Cliff) — 6-10 hrs
3. **Develop Exp 1** (Synthetic Training) — requires training infrastructure

---

*This dashboard is maintained in the Windstorm-Labs org. Update frequency: per experiment.*
