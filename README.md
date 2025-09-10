# EMA System (TradingView)

Optimized multi-EMA indicator for TradingView (Pine Script v5). It plots five EMAs and an optional trend regime background keyed to the 200 EMA for clean, multi-horizon trend assessment.

## Key Features

- Five EMAs: 10, 20, 50, 100, 200
- Regime background driven by the 200 EMA
- Independent toggles for each EMA and the background
- Lightweight visuals; designed to overlay price

## Quick Start

1. In TradingView, open the Pine Editor.
2. Copy the contents of `indicator.pine` from this repo.
3. Paste into the editor, save, and name it (e.g., "EMA System (Optimized)").
4. Click "Add to chart".
5. Open the indicator Settings to customize inputs and display.

## Inputs

### EMA Parameters

- 10 EMA (Shorter): default 10
- 20 EMA (Short): default 20
- 50 EMA (Long): default 50
- 100 EMA (Longer): default 100
- 200 EMA (Holder): default 200

### Display Options

- Show 10/20/50/100/200 EMA: toggle each line on/off
- Show Trend Regime Background: color the chart background by 200 EMA trend

## How To Read

- Bullish regime: close above 200 EMA (green background)
- Bearish regime: close below 200 EMA (red background)
- Alignment: faster EMAs (10/20) above slower EMAs (50/100/200) supports a bullish bias, and vice versa

## Tips

- Consider higher timeframe confirmation for trend context.
- Adjust background strength via the indicator's Style transparency if needed.
- This is not financial advice; use with a risk-managed plan.

## Version

- Version: 2.0
- File: `indicator.pine`
- Author: um1ng
- Language: Pine Script v5

## Changelog

- 2.0
  - Grouped inputs for clarity (EMA Parameters, Display Options)
  - Independent toggle for trend regime background
  - Color and plotting refinements
