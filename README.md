# Basketball Stats Dashboard

A Flask dashboard for loading basketball game data and viewing team, player, and trend summaries.

## What it does

- Shows season totals, games, player summaries, and leaderboards
- Calculates advanced stats and trends from imported game data
- Includes optional AI analysis when an API key is configured
- Runs locally with your own data files

## Run it locally

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

Copy `.env.example` to `.env` if you want to use optional services. Add your own non-sensitive data files under `data/`; this repository intentionally ships without a real roster or game history.

## License

This code is provided as-is for personal or educational use.
