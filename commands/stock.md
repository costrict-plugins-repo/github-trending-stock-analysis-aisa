---
description: Analyze a stock or crypto ticker (e.g., /stock-analysis-aisa:stock AAPL)
---

Analyze the stock or crypto ticker "$ARGUMENTS" using the stock-analysis skill.

Run the analysis script:

```bash
python3 "${CLAUDE_PLUGIN_ROOT}/skills/stock-analysis/scripts/analyze_stock.py" $ARGUMENTS
```

Present the results in a clear, formatted manner. If no ticker is provided, ask the user which stock or crypto they want to analyze.
