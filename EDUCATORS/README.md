# Educators — SELF_DRIVING_CAR

**Project:** SELF_DRIVING_CAR  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/udacity/self-driving-car  
**Pinned commit:** `aa7fe7a77d397de27bf8d2ce0e48576337b162f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e`  
**Date:** October 2026

## Teaching with SELF_DRIVING_CAR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
