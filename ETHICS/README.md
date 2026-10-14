# Ethics — SELF_DRIVING_CAR

**Project:** SELF_DRIVING_CAR  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/udacity/self-driving-car  
**Pinned commit:** `aa7fe7a77d397de27bf8d2ce0e48576337b162f0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `575598bc651a05e430c8fcff5d872c081eccf157c44c60660ed5fcff89e69a9e`  
**Date:** October 2026

## Position

SELF_DRIVING_CAR is packaged for offline deployment with a verifiable audit trail. The
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
