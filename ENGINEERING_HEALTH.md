# LR Lab — Engineering Health Matrix

This page tracks engineering evidence across the public LR Lab repositories.

> A green CI badge or a benchmark artifact means the repository exercises a defined check. It does **not** by itself prove production suitability or scientific validity.

| Project | Automated tests | Labeled / repeated evaluation | CI artifact | Provenance / integrity | Explicit limitations |
|---|---|---|---|---|---|
| [LR-Agent](https://github.com/LLR6/LR-agent) | ✅ Python 3.11/3.12 | 🧪 research manifests / mechanism tests | ✅ CI + showcase artifacts | ✅ experiment artifact SHA-256 bundle | ✅ Claim Ledger + research notes |
| [NightWatch](https://github.com/LLR6/Cybersecurity-Detection-Engineering-Android-Automation-Learning-by-Building) | ✅ pytest | ✅ positive + benign regression corpora | ✅ detection / evaluation reports | ✅ suppression audit | ✅ tuning notes / non-goals |
| [Detection Threshold Lab](https://github.com/LLR6/lr-detection-lab) | ✅ unittest | ✅ multi-seed replicate / Pareto analysis | ✅ replicate JSON | ✅ seeded experiment parameters | ✅ synthetic-data caveat |
| [LR-SOC-Copilot](https://github.com/LLR6/LR-SOC-Copilot) | ✅ unittest | ✅ labeled runbook retrieval benchmark | ✅ benchmark JSON | ✅ source-line evidence refs | ✅ Evidence Model |
| [LR-PayloadLab](https://github.com/LLR6/LR-PayloadLab) | ✅ unittest | ✅ bounded scenario checks | ✅ manifest inspection artifact | ✅ Manifest / receipt SHA-256 | ✅ capability boundary |
| [Detector Resilience Lab](https://github.com/LLR6/LR-Detector-Resilience-Lab) | ✅ unittest | ✅ threshold + drift-strength sweeps | ✅ resilience report | ✅ seeded deterministic experiments | ✅ non-executable feature-space boundary |
| [Android CI Doctor](https://github.com/LLR6/lr-android-ci-doctor) | ✅ unittest | ✅ labeled synthetic build-log benchmark | ✅ benchmark JSON | ✅ line-level evidence + redaction | ✅ triage model / non-goals |
| [CTF Tracebook](https://github.com/LLR6/lr-ctf-tracebook) | ✅ unittest | ✅ transcript parser benchmark | ✅ benchmark JSON | ✅ source SHA-256 + redaction summary | ✅ trace model |
| [LR-Tablet](https://github.com/LLR6/LR-Tablet) | ✅ data / backup self-tests | ✅ question-bank integrity gates | ✅ Android APK workflow | ✅ backup SHA-256 envelope | ✅ local-first data contract |

## What “good” means here

For LR Lab, a project is moving in the right direction when it can answer:

1. **What problem is being solved?**
2. **What exact input produced this result?**
3. **What automated check would catch a regression?**
4. **What evidence supports the output?**
5. **What does the project explicitly *not* claim?**
6. **Can another person reproduce the same experiment or build?**

## Current cross-project quality targets

- Keep default-branch CI green.
- Prefer deterministic fixtures over screenshot-only demos.
- Save machine-readable benchmark outputs as CI artifacts.
- Keep synthetic / toy / production claims clearly separated.
- Version data schemas that are persisted or exchanged.
- Preserve provenance with source refs, hashes or fixed seeds where useful.
- Document safety boundaries for security-related repositories.
- Keep Roadmap and CHANGELOG aligned with actual code.
