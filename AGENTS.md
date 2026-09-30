# AGENTS.md — qualcomm-on-device-budget-futures

**Company:** Qualcomm
**Domain:** Cloud AI Platform Engineering

## Quick Rules
- **Test command:** `PYTHONPATH=src pytest tests/ -v`
- **Lint:** `ruff check src/ tests/`
- **No drive-by edits** — load the skill first.

## Architecture
- `src/qualcomm_on_device_budget_futures/core.py` — Domain logic (Cloud AI Platform Engineering)
- `tests/` — Verified test suite
- `.github/workflows/ci.yml` — Enforced CI pipeline
