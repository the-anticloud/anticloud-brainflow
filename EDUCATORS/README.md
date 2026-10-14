# Educators — BRAINFLOW

**Project:** BRAINFLOW  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/brainflow-dev/brainflow.git  
**Pinned commit:** `bd3789193a6941783ebe89c97602af2496c7310a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0b42200421ac8e63e8b486286489f842c5de81ec964f9d63f68b96b619d3a18b`  
**Date:** October 2026

## Teaching with BRAINFLOW

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `0b42200421ac8e63e8b486286489f842c5de81ec964f9d63f68b96b619d3a18b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
