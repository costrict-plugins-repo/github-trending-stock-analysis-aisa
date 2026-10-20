---
description: Find early signals, M&A rumors, insider activity (Rumor Scanner)
---

Run the Rumor Scanner to find early market signals using the stock-rumors skill.

```bash
python3 "${CLAUDE_PLUGIN_ROOT}/skills/stock-rumors/scripts/rumor_scanner.py" $ARGUMENTS
```

Present M&A signals, insider activity, analyst actions, social whispers, and top signals ranked by impact. The user can pass `--focus ma`, `--focus insider`, `--focus analyst`, `--focus social`, or `--output json` as arguments.
