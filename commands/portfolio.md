---
description: Manage investment portfolios with live P&L (e.g., /stock-analysis-aisa:portfolio show)
---

Manage portfolios using the stock-portfolio skill.

```bash
python3 "${CLAUDE_PLUGIN_ROOT}/skills/stock-portfolio/scripts/portfolio.py" $ARGUMENTS
```

Available actions: `create NAME`, `list`, `show [--portfolio NAME]`, `add TICKER --quantity N --cost N [--portfolio NAME]`, `update TICKER [--quantity N] [--cost N]`, `remove TICKER`, `rename OLD NEW`, `delete NAME`. If no arguments are provided, show the portfolio summary with `show`.
