# SpiderFoot

## Overview

SpiderFoot is an automated Open Source Intelligence (OSINT) and reconnaissance tool designed to collect, analyse, and correlate publicly available information from hundreds of different data sources. Unlike many traditional OSINT tools that return isolated results, SpiderFoot builds relationships between discovered entities, providing a broader view of an organisation's digital footprint.

For this assessment, SpiderFoot was used to perform a comprehensive reconnaissance of **OWASP (owasp.org)**. The goal was to correlate publicly available information gathered from multiple sources and gain a deeper understanding of the organisation's publicly exposed infrastructure.

---

## Objectives

The objectives of using SpiderFoot were to:

- Learn how automated OSINT correlation works.
- Perform a comprehensive passive reconnaissance assessment.
- Identify publicly available assets associated with OWASP.
- Analyse relationships between discovered entities.
- Export and document the collected intelligence.

---

## Assessment Summary

A full SpiderFoot scan was performed using the **All** scan profile.

The assessment generated a large dataset containing publicly available information related to OWASP, including domains, subdomains, IP addresses, DNS records, URLs, network information, and other correlated entities.

The collected data was exported for further analysis and documentation.

---

## What This Folder Contains

- **notes.md** – Installation journey, troubleshooting, observations, and lessons learned.
- **cheatsheet.md** – Frequently used SpiderFoot commands.
- **findings.md** – Summary of the intelligence collected during the assessment.
- **exports/** – CSV, GEXF, and other exported artefacts generated during the scan.
- **images/** – Screenshots captured throughout the assessment.

---

## Key Takeaway

SpiderFoot demonstrated the value of automated OSINT correlation. Rather than collecting information from a single source, it connected data from numerous public sources to build a much richer picture of OWASP's digital footprint.

This assessment also highlighted the importance of patience when performing large-scale reconnaissance, as comprehensive scans can require significant time to complete and produce very large datasets for analysis.

---
## Project Statistics

| Metric | Result |
|---------|--------|
| Target | OWASP |
| Scan Profile | All |
| Duration | Approximately 7 hours |
| Total Events | 80,274 |
| Unique Entities | 31,088 |
| Export Formats | CSV, GEXF, PNG |



> This folder documents my first experience using SpiderFoot and serves as a reference for future OSINT investigations and digital footprint assessments.
