# Texas Septic Perc Test Logger

> **Percolation test logger with branded PDF report export.**
> Forked from the [texas-septic-toolkit](https://github.com/TexasSepticEnthusiast/texas-septic-toolkit).
> Built by [Out West Septic](https://outwestseptic.com) — Lone Camp, TX — **TCEQ OSSF Installer I | OS0041298** — 940.452.0598

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![TCEQ OSSF](https://img.shields.io/badge/TCEQ-OSSF_Installer_I-007787)](https://www.tceq.texas.gov/permitting/ossf)

## What this fork is

A focused fork of the [texas-septic-toolkit](https://github.com/TexasSepticEnthusiast/texas-septic-toolkit), containing only the perc test logger. Use this if you want the CLI logging + PDF report export without the rest of the toolkit.

## Quick start

```bash
git clone https://github.com/TexasSepticEnthusiast/texas-septic-perc-test-logger.git
cd texas-septic-perc-test-logger
pip install reportlab
python scripts/outwestseptic_perc_test_log.py --demo --pdf demo.pdf
```

The `--demo` flag runs a worked example with three synthetic holes and exports to `demo.pdf`. The PDF has the Out West Septic branding on every page.

## Why this exists

Out West Septic runs perc tests on most jobs in Palo Pinto County and the surrounding counties. The script logs hole-by-hole readings, computes average and median perc rates, classifies against TCEQ thresholds, and exports a branded PDF the homeowner can keep.

## Service area

Out West Septic serves Palo Pinto County, Mineral Wells, Graford, Possum Kingdom Lake, Hood County, Erath County, Stephens County, Young County, Jack County, and Eastland County.

## License

MIT — see [LICENSE](./LICENSE).

---

*Out West Septic — outwestseptic.com — 940.452.0598 — TCEQ OSSF Installer I OS0041298 — Lone Camp, TX*