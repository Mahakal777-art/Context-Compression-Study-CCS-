# Context Compression Study (CCS)

Single-participant feasibility pilot.

## Success Criterion

Determine whether capturing one short statement of investigative intent at task start provides enough later context-recovery benefit to justify its capture cost for a single developer.

---

## Repository Structure

- PROTOCOL.md
- MANIFEST.md
- REPORT.md
- assignment_matrix.json
- context.py
- analyze.py
- trials.csv
- excluded_tasks.csv

---

## Operational Workflow

Capture Phase

Check assignment_matrix.json.

Control
- Use Git normally.

Experimental
- context open
- work normally
- context attach (optional)
- context close

Recovery Phase

After 14–30 days:

- Start stopwatch
- Git only for 5 minutes
- If stuck:
    context show <id>

Record measurements immediately.

---

Only result files should change after baseline freeze.
