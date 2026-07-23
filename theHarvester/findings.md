# Findings

## Target

**Domain:** `owasp.org`

**Assessment Type:** Passive Open Source Intelligence (OSINT)

---

## Data Sources Investigated

The following OSINT sources were queried during this assessment:

- crt.sh
- RapidDNS
- HackerTarget
- CertSpotter
- All Available Sources

Each source returned different information, highlighting the importance of combining multiple data providers during reconnaissance.

---

## crt.sh

### Results

- **Hosts Discovered:** 22
- **IP Addresses:** None
- **Email Addresses:** None

### Observation

crt.sh relies on Certificate Transparency logs. It successfully identified several subdomains associated with OWASP but did not reveal infrastructure details such as IP addresses.

---

## RapidDNS

### Results

- **Hosts Discovered:** 9

RapidDNS also resolved several public IP addresses for the discovered hosts.

### Observation

Compared to crt.sh, RapidDNS provided fewer hosts but included valuable DNS resolution information.

---

## HackerTarget

### Results

- **Hosts Discovered:** 50

Several publicly accessible subdomains and their corresponding IP addresses were identified.

Examples included:

- austin.owasp.org
- cheatsheetseries.owasp.org
- calltobattle.owasp.org
- aghast.owasp.org
- 20thanniversary.owasp.org

### Observation

HackerTarget returned the largest number of subdomains among the individual sources tested, making it one of the most informative data providers during the assessment.

---

## CertSpotter

### Results

- Certificate Transparency information was returned.

The primary result identified was:

- *.owasp.org

### Observation

CertSpotter focuses on certificate transparency records and therefore provides less infrastructure information than DNS-based sources.

---

## All Sources Scan

A final reconnaissance scan was performed using all available data sources.

### Results

- **Hosts:** 143
- **IP Addresses:** 21
- **Interesting URLs:** 23
- **Autonomous System Numbers (ASNs):** 2

This comprehensive scan produced the richest dataset collected during the assessment.

---

## Key Findings

The reconnaissance identified a variety of publicly available assets, including:

- Public subdomains
- Public IP addresses
- Certificate Transparency records
- URLs
- Autonomous System Numbers (ASNs)

No sensitive information or vulnerabilities were identified. All collected information was publicly accessible through passive OSINT sources.

---

## Conclusion

theHarvester demonstrated that different OSINT providers expose different parts of an organisation's digital footprint. While individual sources provided valuable intelligence, combining multiple sources produced a significantly more comprehensive view of OWASP's publicly accessible infrastructure.

---


