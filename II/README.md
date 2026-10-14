# Independent Insurance — EXIV2

**Project:** EXIV2  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e407f94bc4a2514d4ec38e90281db20a9a9f44e8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | EXIV2 with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
