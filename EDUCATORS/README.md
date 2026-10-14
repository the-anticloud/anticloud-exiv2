# Educators — EXIV2

**Project:** EXIV2  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e407f94bc4a2514d4ec38e90281db20a9a9f44e8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8`  
**Date:** October 2026

## Teaching with EXIV2

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `0681a8289feff840e7ec9dbc2ce0f31ae9ff144fc1932d8458546da1d03b96d8` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
