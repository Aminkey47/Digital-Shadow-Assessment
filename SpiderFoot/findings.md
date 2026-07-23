# Findings

## Target

**Domain:** `owasp.org`

**Assessment Type:** Passive Open Source Intelligence (OSINT)

---

## Assessment Summary

A full SpiderFoot assessment was performed using the **All** scan profile.

The scan completed successfully after approximately **seven hours**, producing one of the largest datasets collected during this project.

### Assessment Statistics

| Metric | Result |
|---------|--------|
| Target | owasp.org |
| Scan Profile | All |
| Duration | ~7 Hours |
| Total Events | 80,274 |
| Unique Entities | 31,088 |
| Module Errors | 2,485 |

---

## Information Collected

SpiderFoot successfully correlated information from numerous public sources and identified several categories of publicly available information, including:

- Domains
- Subdomains
- IP Addresses
- DNS Records
- URLs
- Network Blocks
- Open TCP Ports
- Affiliate Infrastructure

---

## Examples of Discovered Assets

Some of the publicly available assets identified during the assessment included:

- cheatsheetseries.owasp.org
- training.owasp.org
- videos.owasp.org
- wiki.owasp.org
- contact.owasp.org
- admin.owasp.org
- mail.owasp.org

These assets demonstrate the breadth of publicly accessible infrastructure associated with OWASP.

---

## Entity Types Observed

During analysis of the exported dataset, SpiderFoot identified several different entity types, including:

- IP_ADDRESS
- NETBLOCK_MEMBER
- TCP_PORT_OPEN
- AFFILIATE_IPADDR

These entity relationships provide a deeper understanding of how publicly available infrastructure is connected.

---

## Exported Evidence

The assessment results were exported for further analysis in the following formats:

- CSV
- GEXF
- PNG Graph

These files are available in the **exports/** directory.

---

## Key Findings

The SpiderFoot assessment demonstrated that publicly available information from multiple sources can be automatically correlated into a much richer intelligence dataset than individual OSINT tools provide on their own.

Although the assessment generated more than **80,000 events**, not every event represented a unique asset. SpiderFoot records many relationships between entities, allowing analysts to understand how infrastructure components are connected rather than simply listing discovered hosts.

---

## Conclusion

SpiderFoot produced the most comprehensive dataset collected during the Digital Shadow Assessment.

Its ability to aggregate and correlate information from numerous public sources provided valuable insight into OWASP's publicly exposed infrastructure and demonstrated the effectiveness of automated OSINT correlation during passive reconnaissance.

---

## Next Step

With reconnaissance complete, the final stage of this project was to consolidate the findings and produce the overall Digital Shadow Assessment report.

➡️ **[Continue to the Final Assessment](../assessment/report.md)**
