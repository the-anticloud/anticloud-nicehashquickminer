# Ethics — NICEHASHQUICKMINER

**Project:** NICEHASHQUICKMINER  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `fea94d384103118be0d8c2675ad263060d6fb45f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8298341a6892cb0686a864eb5f5a52952a9f7c5bdcd36834935afaeecaf217d5`  
**Date:** October 2026

## Position

NICEHASHQUICKMINER is packaged for offline deployment with a verifiable audit trail. The
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
