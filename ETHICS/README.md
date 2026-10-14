# Ethics — EXIV2

**Project:** EXIV2  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e407f94bc4a2514d4ec38e90281db20a9a9f44e8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8`  
**Date:** October 2026

## Position

EXIV2 is packaged for offline deployment with a verifiable audit trail. The
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
