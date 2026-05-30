# data/

CSV exports from tagging sessions.

## Naming convention
`GC_5m_Batch[N]_E[start]-E[end]_[YYYY-MM-DD].csv`

Example: `GC_5m_Batch3_E101-E150_2026-05-30.csv`

## Rule
Export after every batch lock.
Do not rely on tagger internal storage as the only copy.
