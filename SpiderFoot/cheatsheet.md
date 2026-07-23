# SpiderFoot Cheat Sheet

A quick reference for the commands used during the Digital Shadow Assessment.

---

## Launch SpiderFoot

```bash
spiderfoot -l 127.0.0.1:5001
```

or

```bash
python3 sf.py -l 127.0.0.1:5001
```

---

## Access the Web Interface

Open your browser and visit:

```text
http://127.0.0.1:5001
```

---

## View Running Process

```bash
ps aux | grep spiderfoot
```

or

```bash
ps aux | grep python
```

---

## Stop SpiderFoot

```bash
kill <PID>
```

Force stop if necessary:

```bash
kill -9 <PID>
```

---

## Workflow Used

1. Launch SpiderFoot.
2. Open the web interface.
3. Create a new scan.
4. Set the target to `owasp.org`.
5. Select the **All** scan profile.
6. Start the assessment.
7. Export the results (CSV, GEXF, PNG).
8. Analyse and document the findings.

---

## Notes

- SpiderFoot is primarily managed through its web interface.
- Large scan profiles may take several hours to complete.
- Export results for further analysis and documentation.
