# Students — SELF_DRIVING_CAR

**Project:** SELF_DRIVING_CAR  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/udacity/self-driving-car  
**Pinned commit:** `aa7fe7a77d397de27bf8d2ce0e48576337b162f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `aa7fe7a77d397de27bf8d2ce0e48576337b162f0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
