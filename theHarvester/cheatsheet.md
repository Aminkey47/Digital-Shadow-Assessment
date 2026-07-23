# theHarvester Cheat Sheet

A quick reference of the commands used during the Digital Shadow Assessment project.

---

## Display Help

```bash
theHarvester -h
```

---

## Check Version

```bash
theHarvester --version
```

---

## Basic Scan

```bash
theHarvester -d owasp.org -b crtsh
```

### Options

| Option | Description |
|---------|-------------|
| `-d` | Target domain |
| `-b` | Data source |

---

## Scan Using crt.sh

```bash
theHarvester -d owasp.org -b crtsh
```

---

## Scan Using RapidDNS

```bash
theHarvester -d owasp.org -b rapiddns
```

---

## Scan Using HackerTarget

```bash
theHarvester -d owasp.org -b hackertarget
```

---

## Scan Using CertSpotter

```bash
theHarvester -d owasp.org -b certspotter
```

---

## Scan Using All Available Sources

```bash
theHarvester -d owasp.org -b all
```

---

## Save Results to HTML

```bash
theHarvester -d owasp.org -b all -f report
```

---

## Common Data Sources

| Source | Purpose |
|--------|---------|
| `crtsh` | Certificate Transparency logs |
| `rapiddns` | DNS records |
| `hackertarget` | Host and DNS information |
| `certspotter` | Certificate Transparency |
| `all` | Query all supported sources |

---

## Workflow Used

1. Verify installation.
2. Test individual data sources.
3. Compare the results.
4. Run a scan using all sources.
5. Analyse and document the findings.

---

## Notes

- Passive reconnaissance only.
- No direct interaction with the target systems.
- Different data sources produce different results.
- Combining multiple sources provides better coverage.
