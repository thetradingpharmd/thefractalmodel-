# Fractal Model Pro [TheTradingPharmD]

Fractal Model Pro is a multi-timeframe market structure indicator designed to bring key fractal concepts into one streamlined workflow for NinjaTrader 8.

## Features

- Multi-timeframe HTF candle display
- Live Candle 2 (C2) tracking
- Confirmed Candle 3 (C3) progression
- SMT divergence detection
- Liquidity sweep detection
- PSP (Precision Swing Point) identification
- T-Spot fractal zones
- HTF 50% equilibrium levels
- Configurable time ranges
- Customizable chart visuals
- Built-in alert options
- Multiple HTF display support
- Optimized drawing management for improved chart performance

## Fractal Model Logic

The indicator follows a Candle 1, Candle 2, and Candle 3 framework.

A Candle 2 forms when price sweeps the previous HTF candle's high or low and trades back through the swept level.

Bullish C2:
Price trades below Candle 1's low and returns back above or equal to that low.

Bearish C2:
Price trades above Candle 1's high and returns back below or equal to that high.

Candle 3 is the expansion candle that follows a valid Candle 2 and is used to evaluate continuation from the fractal reversal.

## Higher-Timeframe Candles

Fractal Model Pro can display higher-timeframe candles directly alongside price action, allowing traders to monitor the active HTF structure without constantly switching charts.

The indicator supports primary HTF pairing along with additional optional HTF groups.

## SMT and Liquidity Sweeps

The SMT engine compares correlated markets and identifies divergence between their respective highs and lows.

Liquidity sweep logic highlights when price trades through prior liquidity before reversing or continuing.

These tools are intended to provide additional context around developing C2 and C3 structures.

## PSP — Precision Swing Point

PSP highlights important fractal swing relationships that can help identify meaningful liquidity events and potential reversal areas.

## T-Spot

T-Spot projects a fractal zone derived from the qualifying HTF candle into the following candle.

These zones can be used as an additional reference for retracement, continuation, and reaction areas within the C2/C3 sequence.

## 50% Equilibrium Levels

Optional 50% equilibrium lines can be displayed on HTF candles to provide a quick visual reference for the midpoint of the candle range.

## Time Ranges

Configurable time-range separators and boxes can be displayed to help visually organize price action according to the selected timeframe structure.

## Alerts

Fractal Model Pro includes customizable alerts for supported fractal events so traders can monitor the market without continuously watching the chart.

Available alert behavior depends on the enabled modules and indicator settings.

## Performance

The NinjaTrader version is designed with performance in mind.

Drawing objects use stable tags so existing objects can be updated instead of continuously creating new ones. Expensive correlation-based features are isolated so users can disable them when they are not needed.

## Installation

1. Download the Fractal Model Pro NinjaScript file.
2. Open NinjaTrader 8.
3. Go to New > NinjaScript Editor.
4. Open the Indicators folder.
5. Import or create the indicator file.
6. Compile NinjaScript.
7. Open a chart.
8. Right-click the chart and select Indicators.
9. Add Fractal Model [TheTradingPharmD].
10. Configure the settings as desired.

If NinjaTrader reports a compile error during installation, review the error list for the affected file and line number.

## Important

This indicator is a technical analysis tool only. It does not guarantee profitable trades and should not be treated as financial advice.

Always apply proper risk management and independently evaluate any trading setup before entering a position.

## Author

TheTradingPharmD
