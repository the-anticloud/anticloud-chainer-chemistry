# Students — CHAINER_CHEMISTRY

**Project:** CHAINER_CHEMISTRY  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/pfnet-research/chainer-chemistry  
**Pinned commit:** `efe323aa21f63a815130d673781e7cca1ccb72d2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fb9a6a5bd985fbd5e165443c1b1813681301769ba07d61c8d123481b8ff052fa`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `efe323aa21f63a815130d673781e7cca1ccb72d2`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `fb9a6a5bd985fbd5e165443c1b1813681301769ba07d61c8d123481b8ff052fa`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
