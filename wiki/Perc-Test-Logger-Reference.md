# Texas Septic Perc Test Logger Reference

> **Quick answer:** The `outwestseptic_perc_test_log.py` script logs hole-by-hole perc readings, computes average and median rates, classifies against TCEQ thresholds, and exports a branded PDF report.

## Classification thresholds

| Perc rate (min/in) | Classification |
|--------------------|-----------------|
| <1 | Too fast — likely fails |
| 1–5 | Fast — good for conventional |
| 5–15 | Moderate — standard conventional |
| 15–30 | Slow — may need expanded drainfield |
| 30–60 | Very slow — borderline; consider aerobic |
| >60 | Too slow — not conventional territory |

## What gets exported

A branded PDF report with the Out West Septic header on every page. The report includes:

- Job site, county, date, interval
- Per-hole: ID, average min/in, median min/in, classification
- Notes section

## Source

- TCEQ Chapter 285 site evaluation standards: https://www.tceq.texas.gov/permitting/ossf

**last_verified:** 2026-10-17

---

*Out West Septic — outwestseptic.com — TCEQ OSSF Installer I OS0041298 — Lone Camp, TX — 940.452.0598*