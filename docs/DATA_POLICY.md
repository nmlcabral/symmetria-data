# DATA POLICY (symmetria-data)

## Purpose
Define data shapes with schemas and provide tiny, synthetic samples for development and testing.

## Principles
- Minimal — samples must be small and generic.  
- Transparent — schemas describe fields, types, units, and assumptions.  
- Safe — no PII, credentials, or vendor-locked exports.

## Allowed
- Synthetic CSV/JSON rows demonstrating expected fields.  
- Public metadata describing fields and units.

## Disallowed
- Real brokerage exports with identifiers.  
- Files > 100 KB each.  
- Anything violating privacy or platform terms.

## Versioning
- Each schema version bump updates filename + changelog here.

## Changelog
- v0.1 — Initial policy and starter schemas.