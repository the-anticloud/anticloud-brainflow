# Students — BRAINFLOW

**Project:** BRAINFLOW  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/brainflow-dev/brainflow.git  
**Pinned commit:** `bd3789193a6941783ebe89c97602af2496c7310a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0b42200421ac8e63e8b486286489f842c5de81ec964f9d63f68b96b619d3a18b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `bd3789193a6941783ebe89c97602af2496c7310a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `0b42200421ac8e63e8b486286489f842c5de81ec964f9d63f68b96b619d3a18b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
