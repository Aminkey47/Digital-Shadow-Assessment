# Final Assessment Report

# Digital Shadow Assessment of OWASP



---

## Executive Summary

This assessment was conducted as part of the **ALX Cybersecurity Programme** to explore how passive Open Source Intelligence (OSINT) techniques can be used to understand an organisation's publicly accessible digital footprint.

The target selected for this assessment was **OWASP (Open Worldwide Application Security Project)**.

Rather than attempting to exploit systems or gain unauthorised access, the objective was to investigate what information is already available to anyone on the Internet.

Three reconnaissance tools were used throughout the assessment:

- Recon-ng
- theHarvester
- SpiderFoot

Together, these tools revealed publicly available infrastructure, domains, subdomains, IP addresses, URLs, certificate information and relationships between digital assets. The assessment demonstrates how information scattered across many public sources can be combined to create a detailed picture of an organisation's online presence.

---

# Background

Every organisation leaves traces of information on the Internet.

DNS records, SSL certificates, search engines, public repositories, infrastructure databases and many other services continuously expose pieces of information.

Individually, these pieces may appear insignificant.

When combined, however, they create what is commonly referred to as a **Digital Shadow**.

Understanding this digital shadow helps organisations:

- Understand their public exposure.
- Identify forgotten assets.
- Reduce unnecessary information leakage.
- Improve their overall security posture.

---

# Scope

## Target

OWASP (owasp.org)

## Assessment Type

Passive Open Source Intelligence (OSINT)

## Techniques

Only passive reconnaissance techniques were used.

No authentication was attempted.

No exploitation was performed.

No vulnerability scanning against live systems was conducted.

---

# Methodology

The assessment followed three major stages.

## Stage One — Recon-ng

Recon-ng was used to understand modular reconnaissance frameworks and API-driven intelligence gathering.

The assessment explored Marketplace modules, API integrations and workspace management.

Although several modules were limited by third-party API restrictions, the framework demonstrated how professional reconnaissance workflows are organised.

---

## Stage Two — theHarvester

theHarvester gathered publicly available information from multiple independent OSINT providers.

Several sources were compared individually before running a complete assessment using all available sources.

The combined scan successfully identified:

- 143 Hosts
- 21 IP Addresses
- 23 Interesting URLs
- 2 Autonomous System Numbers

This demonstrated that combining multiple providers significantly improves reconnaissance coverage.

---

## Stage Three — SpiderFoot

SpiderFoot automated the correlation of information gathered from numerous public intelligence sources.

A full assessment using the **All** scan profile required approximately seven hours to complete.

The completed assessment generated:

- 80,274 Events
- 31,088 Unique Entities

The exported CSV, GEXF and graphical reports illustrated the relationships between publicly accessible infrastructure associated with OWASP.

---

# Key Findings

The assessment demonstrated several important observations.

## 1. Public Information Exists Across Many Sources

No single OSINT provider contained a complete view of OWASP's infrastructure.

Each source contributed unique information.

---

## 2. Correlation Produces Better Intelligence

SpiderFoot demonstrated that correlating information from multiple sources provides significantly greater visibility than analysing isolated datasets.

---

## 3. Public Exposure Does Not Equal Vulnerability

The information discovered during this assessment was publicly available.

Its existence does not indicate that OWASP is vulnerable.

Instead, it illustrates how much infrastructure information organisations naturally expose through normal Internet operations.

---

## 4. Documentation Is Part of Cybersecurity

One of the most valuable lessons from this project was that cybersecurity extends beyond running tools.

Planning, documenting, troubleshooting and interpreting results are essential parts of every assessment.

---

# Challenges Encountered

Several practical challenges were encountered throughout the assessment.

## Recon-ng

- API restrictions
- Shodan free plan limitations
- Censys authentication changes

## SpiderFoot

- Dependency issues on Ubuntu
- Migration to Kali Linux
- Seven-hour assessment runtime
- Large datasets requiring careful analysis

## theHarvester

The installation and assessment proceeded smoothly with no significant technical issues.

---

# Recommendations

Based on this assessment, organisations should consider:

- Periodically reviewing publicly exposed assets.
- Monitoring Certificate Transparency logs.
- Maintaining an accurate inventory of Internet-facing infrastructure.
- Performing regular OSINT assessments.
- Reviewing DNS records and publicly accessible services.

---

# Personal Reflection

This project was my first experience conducting a structured digital shadow assessment.

More importantly, it taught me that cybersecurity is not simply about using tools.

It is about asking questions, solving problems, understanding data and documenting findings in a way that others can understand.

Throughout this project I learned to troubleshoot installation issues, work with multiple Linux environments, compare different reconnaissance tools and interpret large volumes of publicly available information.

This assessment marks the beginning of my journey into Open Source Intelligence and digital reconnaissance.

---

# Conclusion

This Digital Shadow Assessment successfully demonstrated how passive reconnaissance techniques can be used to investigate an organisation's public online presence without interacting directly with its systems.

Using Recon-ng, theHarvester and SpiderFoot provided different perspectives on the same target, while highlighting the strengths and limitations of each tool.

Most importantly, the project reinforced that effective reconnaissance is not about collecting the most data—it is about collecting meaningful information, understanding what it represents and communicating the findings clearly.

---

> *"A journey of a thousand miles starts with one step."* — Lao Tzu
