# SPY / QQQ SMT + IFVG Paper Trading Bot

This repository is intended for a paper-trading bot using overnight liquidity sweeps, SPY/QQQ SMT divergence, market structure shifts, inverse fair value gaps, and pullback entries.

## Current deployment status

**Not deployed.** GitHub is source control, not an always-on server. A cloud VPS/container host and Alpaca paper-data credentials are still required.

## Safety

- Paper trading only; do not enable live-money orders.
- Never commit `.env`, API keys, passwords, or brokerage secrets.
- Do not execute trades on stale data or after a restart without reconciling positions and orders.
- Monitor heartbeat, feed latency, trading-session status, and order failures.

## Next steps

1. Upload the application source from the local V4 ZIP.
2. Configure a cloud VPS and deploy Docker Compose.
3. Set Alpaca paper keys as secrets on the VPS.
4. Test historical data, paper execution, restarts, and monitoring.

The repository alone does **not** guarantee continuous monitoring or execution.
