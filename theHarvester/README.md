# theHarvester

## Overview

theHarvester is an Open Source Intelligence (OSINT) tool designed to collect publicly available information from search engines, certificate transparency logs, DNS databases, and other online sources. It helps security professionals understand an organisation's public exposure by gathering information such as subdomains, IP addresses, email addresses, URLs, and Autonomous System Numbers (ASNs).

For this assessment, theHarvester was used to perform passive reconnaissance against **OWASP (owasp.org)**. The tool proved to be one of the most effective during the project, successfully discovering a significant number of publicly available assets from multiple OSINT sources.

---

## Objectives

The objectives of using theHarvester were to:

- Install and configure theHarvester.
- Perform passive reconnaissance against OWASP.
- Collect publicly available subdomains, IP addresses, URLs, and ASNs.
- Compare information gathered from different OSINT sources.
- Understand the strengths and limitations of each data source.

---

## Data Sources Used

During this assessment, information was collected from the following sources:

- crt.sh
- RapidDNS
- HackerTarget
- CertSpotter
- All Available Sources

Each source returned different results, demonstrating that no single OSINT provider contains a complete view of an organisation's digital footprint.

---

## What This Folder Contains

- **notes.md** – Installation process, workflow, observations, and lessons learned.
- **cheatsheet.md** – Commands used throughout the assessment for quick reference.
- **findings.md** – Summary of the reconnaissance results collected from each data source.
- **images/** – Screenshots captured during installation and reconnaissance.

---

## Key Takeaway

theHarvester demonstrated the importance of combining multiple OSINT sources during reconnaissance. While individual data sources provided only partial information, using them together produced a much broader view of OWASP's publicly exposed infrastructure.

---

> This folder documents my first experience using theHarvester and serves as a reference for future passive reconnaissance and OSINT investigations.
