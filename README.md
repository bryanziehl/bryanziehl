# Bryan Ziehl

Building infrastructure for operational verification in complex systems.

---

## Current Work

### Prima Veritas

Reconstructs fragmented system data into a consistent, verifiable operational history.

---

## Demonstration System

**prima-veritas-demo-system**

Public system for reconstructing and verifying operational timelines from structured event data. Upload a dataset to generate a reproducible history and verification bundle.

https://github.com/bryanziehl/prima-veritas-demo-system

## Foundational Systems

**pv-event-ledger**  
Reference implementation of event sequencing and hash-linked ledgers for reconstructing verifiable operational history.
https://github.com/bryanziehl/pv-event-ledger

**pv-reproducible-pipeline**  
Reference implementation of a reproducible data pipeline with cross-machine verification and hash-stable outputs.
https://github.com/bryanziehl/pv-reproducible-pipeline

---

## Developer Tooling

A small suite of Node.js CLI tools for dependency analysis and project diagnostics.

**deptrace**  
Trace dependency lineage in Node.js projects using `package-lock.json`.  
https://github.com/bryanziehl/deptrace

**ghostdep**  
Detect unused dependencies declared in `package.json`.  
https://github.com/bryanziehl/ghostdep

**depmissing**  
Detect imports used in source code but missing from `package.json`.  
https://github.com/bryanziehl/depmissing

**lockdrift**  
Detect drift between `package.json` and `package-lock.json`.  
https://github.com/bryanziehl/lockdrift

---

## Focus Areas

- dependency lineage tracing  
- reproducible data pipelines  
- operational data reconstruction  
- verification workflows  
