# EMA System Indicator

An optimized EMA system indicator designed for the TradingView platform.

## Features

- Multi-EMA framework (10/20/50/100/200) for multi-horizon trend assessment
- Trend regime filter: background based on the 200 EMA (long-term trend)
- Customizable display: toggle each EMA line and the regime background independently

## Installation

1. Open the "Pine Editor" in TradingView
2. Copy the contents of `indicator.pine`
3. Paste into the editor and save
4. Add the indicator to your chart

## Settings

### EMA Parameters

- 10 EMA (Short-Term): 10-period EMA (default)
- 20 EMA (Short-Term): 20-period EMA (default)
- 50 EMA (Intermediate-Term): 50-period EMA (default)
- 100 EMA (Medium-Term): 100-period EMA (default)
- 200 EMA (Long-Term, Trend Filter): 200-period EMA (baseline)

### Display Options

- Independently toggle visibility for each EMA line
- Toggle the trend regime background on/off

## Usage

- Bullish regime: Price above the 200 EMA; background fills green
- Bearish regime: Price below the 200 EMA; background fills red
- EMA stack alignment: Faster EMAs (10/20) above slower EMAs (50/100/200) supports bullish bias, and vice versa

## Version

- Version: 2.0
- Author: um1ng
- Language: Pine Script v5
