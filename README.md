# OM Prototype Corpus

## Overview
Corpus repository for the Governed Intelligence Production 
System — OM Prototype deployment.

## Repository Role
This repository is the intelligence layer. It contains the 
operator's structured governing language, domain knowledge, 
ethical guidelines, and session artifacts.

The corpus is operator-owned, operator-edited, and 
operator-versioned. The substrate receives only what the 
orchestrator delivers per session. It does not have standing 
access to this corpus.

## Corpus Version Index
| Version | Status | Declared |
|---------|--------|----------|
| corpus-v1.0 | Active | 2026-03-15 |

## Shadow Corpus Version Index
| Version | Status | Declared |
|---------|--------|----------|
| shadow-v1.0 | Placeholder | 2026-03-15 |

## Structure
```
/corpus
    corpus-v1.0.md
    validation-domain-map.md
    operator-profiles.md
/shadow-corpus
    shadow-v1.0.md
README.md
```

## Governance
Every change to this repository is a governed event.
Commit messages follow the standardised schema:
[EVENT:TYPE] description timestamp
