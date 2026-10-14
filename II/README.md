# Independent Insurance — SELF_DRIVING_CAR

**Project:** SELF_DRIVING_CAR  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/udacity/self-driving-car  
**Pinned commit:** `aa7fe7a77d397de27bf8d2ce0e48576337b162f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | SELF_DRIVING_CAR with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
