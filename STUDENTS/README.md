# Students — EXIV2

**Project:** EXIV2  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e407f94bc4a2514d4ec38e90281db20a9a9f44e8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e407f94bc4a2514d4ec38e90281db20a9a9f44e8`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
