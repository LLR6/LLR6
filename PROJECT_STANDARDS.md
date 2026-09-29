# LR Lab Project Standards

This document is the default engineering baseline for public LR Lab repositories.

## 1. Repository basics

Every maintained public project should have:

- README
- LICENSE
- SECURITY.md
- SUPPORT.md
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md
- CHANGELOG.md
- CITATION.cff when the project may be referenced academically
- Roadmap
- Compatibility policy
- Release checklist

## 2. CI baseline

A maintained project should validate as much of the following as applies:

- install / dependency resolution;
- package compile or build;
- CLI / app smoke start;
- automated tests;
- malformed-input robustness;
- benchmark / fixture regression;
- release metadata consistency;
- CodeQL;
- supported runtime-version matrix.

## 3. Evidence before claims

Prefer artifacts that can be independently inspected:

- source refs;
- hashes;
- fixed seeds;
- labeled fixtures;
- benchmark JSON;
- reproducible commands;
- CI artifacts.

Avoid claims based only on screenshots or one successful run.

## 4. Benchmarks

A benchmark should state:

- what input it uses;
- what metric it measures;
- what counts as regression;
- what it does **not** prove.

Synthetic benchmarks must not be presented as production measurements.

## 5. Versioned data

Persisted or exchanged data should have a schema/version when practical.

Schema changes should answer:

- can old data still be read?
- is migration required?
- can migration fail safely?
- does the change invalidate old benchmark comparisons?

## 6. Change risk

Classify changes conceptually as:

- Low: docs / additive examples
- Medium: additive public behavior
- High: persisted data, metric semantics, security boundary, correlation/ranking logic, restore/migration behavior

High-risk changes need stronger evidence than low-risk changes.

## 7. Security-related projects

Security tooling should clearly state:

- intended defensive / authorized scope;
- non-goals;
- threat model or safety boundary;
- data handling;
- dangerous capabilities intentionally excluded.

Do not weaken a project boundary just to make a demo more impressive.

## 8. Performance

Performance measurements in shared CI are normally trend signals, not universal benchmarks.

Hard performance gates require:

- stable hardware/runtime;
- fixed fixture;
- documented measurement method;
- enough repetitions;
- clear reason for the threshold.

## 9. Failure modes

Every serious project should document known failure modes and how to detect them.

A good project explains not only how it works, but how it fails.

## 10. Release discipline

Before a release:

1. CI green.
2. Version metadata consistent.
3. CHANGELOG updated.
4. Citation metadata updated when present.
5. Benchmarks reviewed.
6. Compatibility and migration impact reviewed.
7. Known limitations still accurate.
8. Safety boundary rechecked for security projects.

## 11. Research projects

Keep these statements separate:

- “implemented”
- “tested”
- “benchmark improved”
- “research hypothesis supported”
- “general claim established”

Do not promote one into another without evidence.

## 12. Maintenance principle

The goal is not the largest repository.

The goal is a repository where another technical reader can answer:

> What does this do, why should I trust this output, how can I reproduce it, and where will it fail?
