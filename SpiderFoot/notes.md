# Notes

## Goal

The goal of using SpiderFoot was to perform a comprehensive OSINT assessment against **OWASP (owasp.org)** by automatically collecting and correlating publicly available information from multiple data sources.

Unlike the previous tools, SpiderFoot was expected to provide a broader view of the organisation's digital footprint by connecting relationships between discovered entities.

---

## Installation Journey

My initial plan was to install and run SpiderFoot on **Ubuntu**.

During the installation process, I encountered dependency and compatibility issues related to the Python environment. Despite trying several approaches to resolve the problem, the installation was unsuccessful.

Rather than spending more time troubleshooting, I decided to continue the assessment using **Kali Linux**, where SpiderFoot was already available and properly configured.

This decision allowed me to focus on learning the tool instead of fighting installation issues.

---

## Running the Assessment

After successfully launching SpiderFoot on Kali Linux, I created a new scan targeting **owasp.org**.

For the scan profile, I selected **All**, allowing SpiderFoot to execute as many available modules as possible and gather information from numerous public data sources.

I expected this scan to take longer than the previous reconnaissance tools because of the large number of modules involved.

---

## The Seven-Hour Scan

Once the scan started, I allowed it to continue running overnight.

The assessment took approximately **seven hours** to complete.

By the following morning, SpiderFoot had collected a massive amount of publicly available information, generating:

- More than **80,000 events**
- Over **31,000 unique entities**

This was by far the largest dataset collected during the entire Digital Shadow Assessment.

---

## Exporting the Results

After the scan completed, I exported the assessment results for documentation and further analysis.

The exported files included:

- CSV
- GEXF
- Graph images

These exports were saved as evidence of the assessment and are included in this repository.

---

## Challenges

The biggest challenge during this phase was not running SpiderFoot itself—it was getting the environment ready.

The Ubuntu installation highlighted how dependency and compatibility issues can affect security tools. Switching to Kali Linux proved to be the right decision and allowed the assessment to proceed successfully.

Another challenge was the sheer volume of collected data. Instead of manually reviewing every record, I learned the importance of focusing on significant findings and understanding the relationships between entities.

---

## Lessons Learned

SpiderFoot taught me that OSINT is more than collecting information.

The real value comes from correlating information from multiple public sources to build a complete picture of an organisation's digital footprint.

This assessment also reinforced the importance of patience, planning, and documentation when working with large-scale reconnaissance tools.

---

## Timeline

1. Attempted installation on Ubuntu.
2. Encountered dependency and compatibility issues.
3. Switched to Kali Linux.
4. Created a new assessment targeting **owasp.org**.
5. Selected the **All** scan profile.
6. Allowed the scan to run overnight.
7. Exported the collected results.
8. Documented the findings and lessons learned.

---

## Next Step

With the assessment complete, I analysed the collected intelligence and documented the most significant findings.

➡️ **[Continue to Findings](findings.md)**
