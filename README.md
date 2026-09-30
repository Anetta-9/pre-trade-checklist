# Pre-Trade Risk Checklist

A free, single-file tool for forex and gold traders. Enter the trade you are about to place and it:

- works out your **position size** from your balance, risk % and stop distance
- shows your **risk in $**, potential reward, stop distance and **risk:reward**
- checks the trade against **your own limits**: max risk per trade, minimum risk:reward, daily loss limit
- walks you through a short **plan, market and state-of-mind checklist**
- only shows **Ready to place** when every check passes

Everything runs in your browser. No sign-up, no tracking, no data leaves your computer. Your rules (balance, risk %, limits) are remembered in your browser's local storage.

**Live version:** https://anetta-9.github.io/pre-trade-checklist/

## How to use

1. Open the live version above, or download `index.html` and open it in any modern browser (works offline).
2. Set your rules once.
3. Before every trade, enter the instrument, entry, stop loss and take profit, and tick the checklist.
4. Click **Clear for next trade** when you are done.

## Instruments and assumptions

EURUSD, GBPUSD, AUDUSD, NZDUSD, USDJPY, USDCAD, USDCHF, EURGBP, EURJPY, GBPJPY, XAUUSD, XAGUSD.

- Account currency: USD
- Forex: 100,000 units per standard lot, pip = 0.0001 (0.01 for JPY pairs)
- Gold: 100 oz per lot, one point = $0.10 price move ($10 per lot)
- Silver: 5,000 oz per lot, one point = $0.01 price move ($50 per lot)
- Cross pairs (EURGBP, EURJPY, GBPJPY) ask for the current GBP/USD or USD/JPY rate to convert the pip value to USD
- Lot size is rounded down to 0.01, so actual risk is never above your risk budget

Brokers differ, especially for gold and silver. Confirm contract size and pip value on your trading platform.

## Disclaimer

For educational use only. This is not financial advice. Forex and gold trading on margin carries a high level of risk and you can lose money rapidly due to leverage.

## Licence

MIT. Free to use, change and share. Made by [ForexInfo.ai](https://forexinfo.ai).
