# Ethics — BRAINFLOW

**Project:** BRAINFLOW  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/brainflow-dev/brainflow.git  
**Pinned commit:** `bd3789193a6941783ebe89c97602af2496c7310a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0b42200421ac8e63e8b486286489f842c5de81ec964f9d63f68b96b619d3a18b`  
**Date:** October 2026

## Position

BRAINFLOW is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
