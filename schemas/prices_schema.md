# prices schema v0.1 (CSV)

| column | type | required | notes |
|--------|------|-----------|-------|
| timestamp | string | yes | ISO8601 UTC e.g. 2025-01-31T14:30:00Z |
| symbol | string | yes | e.g. AAPL |
| open | float | yes |  |
| high | float | yes |  |
| low | float | yes |  |
| close | float | yes |  |
| volume | integer | yes | non-negative |
| source | string | no | free text (e.g. "synthetic") |

**Assumptions**
- No duplicates for (timestamp, symbol).  
- Timestamps monotonic per symbol.  
- Prices ≥ 0; volume ≥ 0.