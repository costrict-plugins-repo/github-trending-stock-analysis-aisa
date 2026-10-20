# Stock Analysis — AIsa Edition (Claude Plugin)

AI-powered stock and crypto analysis plugin for **Claude Code**, powered by the [AIsa API](https://aisa.one).

## Features

This plugin provides 6 skills and 7 slash commands for comprehensive market analysis:

| Skill | Command | Description |
|-------|---------|-------------|
| `stock-analysis` | `/stock-analysis-aisa:stock AAPL` | 8-dimension scoring with BUY/HOLD/SELL signals |
| `stock-analysis` | `/stock-analysis-aisa:stock-compare AAPL MSFT` | Side-by-side ticker comparison |
| `stock-dividend` | `/stock-analysis-aisa:stock-dividend JNJ` | Dividend metrics, safety score, income rating |
| `stock-hot` | `/stock-analysis-aisa:stock-hot` | Hot Scanner — trending stocks and crypto |
| `stock-rumors` | `/stock-analysis-aisa:stock-rumors` | Rumor Scanner — M&A, insider, analyst signals |
| `stock-watchlist` | `/stock-analysis-aisa:stock-watch add AAPL` | Watchlist with price alerts |
| `stock-portfolio` | `/stock-analysis-aisa:portfolio show` | Portfolio management with live P&L |

## Installation

### From Claude Plugin Marketplace

Search for "stock-analysis-aisa" in the Claude Code plugin manager, or install directly:

```bash
claude plugin install stock-analysis-aisa
```

### Local Development

```bash
claude --plugin-dir ./stock-analysis-aisa-claude
```

## Configuration

When you enable the plugin, Claude Code will prompt you for:

| Variable | Required | Description |
|----------|----------|-------------|
| `AISA_API_KEY` | Yes | Your AIsa API key from [aisa.one](https://aisa.one) |
| `AISA_BASE_URL` | No | API base URL (default: `https://api.aisa.one/v1`) |
| `AISA_MODEL` | No | AI model (default: `gpt-4o`) |

## Requirements

Python 3.8 or later with the `openai` package installed:

```bash
pip install openai
```

## Disclaimer

**NOT FINANCIAL ADVICE.** All analysis is for informational purposes only.

## License

MIT
