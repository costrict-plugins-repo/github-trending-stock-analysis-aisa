---
description: Analyze dividend metrics for a stock (e.g., /stock-analysis-aisa:stock-dividend JNJ PG KO)
---

Analyze dividend metrics for "$ARGUMENTS" using the stock-dividend skill.

Run the dividend analysis script:

```bash
python3 "${CLAUDE_PLUGIN_ROOT}/skills/stock-dividend/scripts/dividends.py" $ARGUMENTS
```

Present the dividend analysis results. If no ticker is provided, ask the user which dividend stock they want to analyze.
