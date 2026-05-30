# 🧭 vX Dashboard
*Open this first. Every session. Before anything else.*

---

## ▸ WHERE AM I RIGHT NOW

|| **Batch** | 3 ✅ Locked · Batch 4 next | | |
|---|---|
| **Phase** | C — Validation Dataset |
| **Instrument** | GC 5m |
| **Batch** | 3 (active) |
| **Last event tagged** | ~150 |
| **Next event** | 151 |
| **Batch target** | 151–200 · Feb 2026 wk2 |
| **Ground Truth version** | v1.10 |

---

## ▸ NEXT ACTION

>  **Tag events 146–150 → lock Batch 3 → update Ground Truth to v1.5**
> **Retroactive coding E1–E150 → deploy tagger v4 → Batch 4 · Feb 2026 wk2**
---

## ▸ PRE-SESSION CHECKLIST

- [ ] TradingView Bar Replay loaded — GC 5m
- [ ] Correct week on chart (Batch 3 = Jan 2026 wk2)
- [ ] Tagger v2 open in browser
- [ ] HTF context checked (60m + 240m)
- [ ] Session window active
- [ ] Not in skip window (6 bars after last signal)

---

## ▸ BATCH STATUS

| Batch | Events | Status |
|---|---|---|
| Batch 1 | 1–50 | ✅ Locked |
| Batch 2 | 51–100 | ✅ Locked |
| Batch 3 | 101–150 | 🔄 Active |
| Batch 4 | 151–200 | ⬜ Not started |
| Batch 5 | 201–250 | ⬜ Not started |

---

## ▸ SESSION CLOSE CHECKLIST

- [ ] Export CSV from tagger
- [ ] Save CSV to data/ folder
- [ ] Update this dashboard
- [ ] Update Ground Truth if rules changed
- [ ] Upload Ground Truth to Claude Project
- [ ] Commit + push to GitHub

---

## ▸ SESSION WINDOWS (UTC+9)
- Tokyo: 09:00–15:00 ✅
- Gap: 15:00–16:00 ❌ skip
- London: 16:00–22:00 ✅
- NY: 22:00–05:00 ✅
- Off-session: before 09:00 / after 05:00 ❌ skip
