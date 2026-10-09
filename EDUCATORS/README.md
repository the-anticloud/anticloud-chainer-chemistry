# Educators — CHAINER_CHEMISTRY

**Project:** CHAINER_CHEMISTRY  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/pfnet-research/chainer-chemistry  
**Pinned commit:** `efe323aa21f63a815130d673781e7cca1ccb72d2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fb9a6a5bd985fbd5e165443c1b1813681301769ba07d61c8d123481b8ff052fa`  
**Date:** October 2026

## Teaching with CHAINER_CHEMISTRY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `fb9a6a5bd985fbd5e165443c1b1813681301769ba07d61c8d123481b8ff052fa` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
