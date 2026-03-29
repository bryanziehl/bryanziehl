# Bryan Ziehl

Independent systems builder working on developer tooling, reproducible data pipelines, and operational verification infrastructure.

---

## Current Work

### Prima Veritas

An event-ledger system for reconstructing and verifying operational timelines from raw system data.

Conceptual flow:

Raw System Data → Ingest → Normalize → Atomize → Event Ledger → Timeline Replay → Verified Operational History

---

## Demonstration System

**prima-veritas-demo-system**
Public demonstration system for reconstructing and verifying operational 
timelines from structured event records.
https://github.com/bryanziehl/prima-veritas-demo-system

## Foundational Systems

**prima-veritas-core**  
Core engine for reconstructing verifiable operational timelines.  
https://github.com/bryanziehl/prima-veritas-core

**prima-veritas-demo**  
Reproducible analytics benchmark using the UCI Iris and Wine datasets.  
https://github.com/bryanziehl/prima-veritas-demo

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
