# TradingView Daytrade Signals

TradingView Pine Script indicator for a 1-hour day-trading workflow.

## Files

- `trend_ema_chikou_daytrade_1h.pine`
  - Latest EMA version.
  - Uses TrendSignal direction, 25 EMA side, Ichimoku Chikou span side, and weekly pivot side.
  - Signal appears when at least 3 of 4 conditions align.

- `trend_vwap_chikou_daytrade_1h_vwap.pine`
  - Restored VWAP version.
  - Uses TrendSignal direction, VWAP side, Ichimoku Chikou span side, and weekly pivot side.
  - Signal appears when at least 3 of 4 conditions align.

## Notes

- Designed for TradingView Pine Script v6.
- The EMA file is the current revised version.
- The VWAP file is kept for comparison and backup.
