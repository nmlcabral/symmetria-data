# symmetria-data

Schemas, tiny sample datasets, and data policies for Project Symmetria.  
This repo **never** stores large or private datasets.  
It defines what data looks like and provides minimal, synthetic examples.

## Structure
- `schemas/` — JSON/CSV/YAML schemas describing fields, types, and semantics  
- `samples/` — tiny synthetic samples that pass the schemas  
- `docs/` — data policy, conventions, and notes

## Boundaries
- No large files; keep samples < 100 KB each.  
- No secrets or PII.  
- Production code → `symmetria-core`  ·  Exploration → `symmetria-research`