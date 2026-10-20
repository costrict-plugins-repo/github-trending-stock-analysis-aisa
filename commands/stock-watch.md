---
description: Manage watchlist with price alerts (e.g., /stock-analysis-aisa:stock-watch add AAPL --target 220 --stop 160)
---

Manage the watchlist using the stock-watchlist skill.

```bash
python3 "${CLAUDE_PLUGIN_ROOT}/skills/stock-watchlist/scripts/watchlist.py" $ARGUMENTS
```

Available actions: `add TICKER [--target N] [--stop N] [--alert-on signal]`, `remove TICKER`, `list`, `check [--notify]`. If no arguments are provided, show the current watchlist with `list`.
