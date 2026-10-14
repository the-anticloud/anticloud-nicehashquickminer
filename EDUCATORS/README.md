# Educators — NICEHASHQUICKMINER

**Project:** NICEHASHQUICKMINER  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `fea94d384103118be0d8c2675ad263060d6fb45f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8298341a6892cb0686a864eb5f5a52952a9f7c5bdcd36834935afaeecaf217d5`  
**Date:** October 2026

## Teaching with NICEHASHQUICKMINER

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `8298341a6892cb0686a864eb5f5a52952a9f7c5bdcd36834935afaeecaf217d5` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
