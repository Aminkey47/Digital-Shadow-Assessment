# Recon-ng Findings

## Assessment Target

**Target Domain:** `owasp.org`

---

## Objective

The purpose of this Recon-ng assessment was to identify publicly available information associated with the target domain using Recon-ng's OSINT modules.

---

## Summary

The reconnaissance successfully identified several publicly accessible subdomains associated with the target. The selected modules did not return email addresses, individual contacts, or additional IP address information beyond the discovered host records.

---

## Results

### Domains

| Result | Count |
|---------|------:|
| Domains discovered | 1 |

```
owasp.org
```

---

### Hosts

Recon-ng discovered the following publicly available hosts:

```
austin.owasp.org
calltobattle.owasp.org
cheatsheetseries.owasp.org
```

*(Continue the list with the remaining hosts exactly as they appeared in your terminal output.)*

**Total Hosts Found:** **9**

---

### Email Addresses

No publicly available email addresses were discovered.

```
0 Results
```

---

### People

No individual contacts or personnel records were discovered.

```
0 Results
```

---

### IP Addresses

The Recon-ng modules used during this assessment did not identify additional IP address information.

```
0 Results
```

---

## Analysis

The Recon-ng assessment demonstrated that the target exposes multiple public-facing subdomains. These subdomains represent legitimate services offered by the organisation and can be used during later stages of reconnaissance to understand the organisation's publicly accessible infrastructure.

No publicly indexed email addresses or contact information were identified using the modules executed during this assessment.

---

## Limitations

The results obtained depend on:

- The modules that were installed and executed.
- Publicly available OSINT data.
- Whether external data sources required API keys.
- Information currently indexed by search providers.

Additional modules or API integrations may reveal more information during future assessments.

---

## Conclusion

Recon-ng successfully collected publicly available infrastructure information while demonstrating the value of modular OSINT reconnaissance. The assessment identified multiple publicly accessible hosts but did not reveal publicly indexed contact information or additional infrastructure details using the selected modules.
