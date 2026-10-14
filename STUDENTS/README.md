# Students — NICEHASHQUICKMINER

**Project:** NICEHASHQUICKMINER  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `fea94d384103118be0d8c2675ad263060d6fb45f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8298341a6892cb0686a864eb5f5a52952a9f7c5bdcd36834935afaeecaf217d5`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `fea94d384103118be0d8c2675ad263060d6fb45f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `8298341a6892cb0686a864eb5f5a52952a9f7c5bdcd36834935afaeecaf217d5`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
