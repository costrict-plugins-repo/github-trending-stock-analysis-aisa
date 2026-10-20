---
description: Compare multiple stock/crypto tickers side-by-side (e.g., /stock-analysis-aisa:stock-compare AAPL MSFT GOOGL)
---

Compare the tickers "$ARGUMENTS" side-by-side using the stock-analysis skill.

Run the analysis script with all provided tickers:

```bash
python3 "${CLAUDE_PLUGIN_ROOT}/skills/stock-analysis/scripts/analyze_stock.py" $ARGUMENTS
```

Present individual analyses followed by a ranked comparison table. If fewer than 2 tickers are provided, ask the user for more tickers to compare.
