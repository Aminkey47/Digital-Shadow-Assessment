# Notes

## Goal

The goal of using theHarvester was to perform passive reconnaissance against **OWASP (owasp.org)** and gather publicly available information from multiple OSINT sources. The focus was on understanding how different data providers contribute to an organisation's digital footprint.

---

## Installation

Unlike older versions of theHarvester, the latest release uses a modern Python project structure with a `pyproject.toml` file instead of the traditional `requirements/base.txt`.

To avoid affecting the system Python installation, I created and activated a Python virtual environment before installing the required dependencies.

After the installation was complete, I confirmed that theHarvester was working correctly by displaying its help menu and checking the installed version.

---

## First Impressions

Compared to Recon-ng, theHarvester was straightforward to install and use. The command-line interface was simple, and the documentation made it easy to understand the available options.

The tool required very little configuration before reconnaissance could begin, allowing me to focus on collecting information rather than troubleshooting installation issues.

---

## Reconnaissance Process

I began by querying individual OSINT sources to understand the type of information each one could provide.

The sources explored during this assessment included:

- crt.sh
- RapidDNS
- HackerTarget
- CertSpotter

After analysing the results from each source individually, I performed a comprehensive scan using all available sources to compare the overall coverage.

This approach made it easier to identify which providers returned the most useful information and demonstrated that every source contributes different pieces of intelligence.

---

## Observations

One of the most interesting discoveries during the assessment was that different OSINT sources produced significantly different results.

Some sources returned only certificate-related information, while others revealed many subdomains, IP addresses, and additional infrastructure details.

Running a scan against all available sources produced a much broader view of OWASP's publicly exposed assets than relying on any single provider.

---

## Challenges

Unlike the other tools used during this project, theHarvester presented very few technical challenges.

The installation process completed successfully, and the reconnaissance commands executed without significant issues.

This allowed me to spend more time analysing the results rather than troubleshooting the environment.

---

## Lessons Learned

Working with theHarvester reinforced several important lessons:

- Different OSINT providers contain different datasets.
- No single source provides a complete picture of an organisation's digital footprint.
- Combining multiple passive intelligence sources produces richer and more reliable reconnaissance results.
- Passive reconnaissance can reveal a surprising amount of publicly available information without interacting directly with the target's systems.

Overall, theHarvester was one of the most enjoyable tools to use during this assessment because it was reliable, easy to operate, and produced valuable results with minimal setup.


## Timeline

1. Installed theHarvester in a Python virtual environment.
2. Verified the installation and version.
3. Tested individual OSINT data sources.
4. Compared the results from each source.
5. Performed a comprehensive scan using all available sources.
6. Documented the findings.

---

## Next Step

With the reconnaissance process complete, the next stage was to analyse the collected data and document the findings.

➡️ Continue to **findings.md**
