---
title: "fix(perc-logger): footer on multi-page PDFs"
labels: ["bug"]
---

Adds a `onLaterPages` callback to the reportlab document builder so the footer appears on page 2+ of multi-page reports.

**Verified**

Generated a 2-page report from a Palo Pinto County job. Both pages now have the footer.

---

*Out West Septic — TCEQ OSSF Installer I — OS0041298*