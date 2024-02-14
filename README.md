# Pinbar Candle Pattern Alert MT5

Pinbar Candle Pattern Alert MT5 is a custom indicator for MetaTrader 5 (MT5) that detects pinbar candlestick patterns and generates alerts. This indicator is developed by Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pinbar-mt5-software-review-optimize-forex-trade-alerts/). Please note that ForexRobotEasy is not the official developer of this product, and this code is provided as a sample that can work as described in the product. For the official developer, please refer to MQL5.

## Indicator Input Parameters

- **ArrowColor**: Color of the arrows displayed on the chart.
- **ArrowSize**: Size of the arrows.
- **RsiPeriod**: Period for RSI (Relative Strength Index) calculation.
- **MinWickLengthPercent**: Minimum percentage of the wick length for a valid pinbar pattern.

## Indicator Buffers

- **PinbarBuffer**: Buffer that stores the detected pinbar pattern values.

## Indicator Constants

- **Pinbar**: Enumeration for the different types of pinbar patterns detected (NONE, PINBAR_BULLISH, PINBAR_BEARISH).

## Custom Indicator Initialization Function

The `OnInit()` function is called during the initialization of the indicator. It performs the following tasks:

- Maps the indicator buffers.
- Sets the properties of the indicator line (arrow).
- Sets the indicator parameters.
- Sets up the RSI filter.

## Custom Indicator Iteration Function

The `OnCalculate()` function is called for each new tick of data. It calculates the pinbar pattern for each bar and generates the corresponding alerts. It follows these steps:

- Checks if there are enough bars available for calculation.
- Calculates the pinbar pattern for each bar.
- Checks for additional conditions such as RSI overbought/oversold levels and minimum wick length.
- Sets the pinbar pattern value in the PinbarBuffer.

## Product Description

Pinbar Candle Pattern Alert MT5 is a powerful indicator that helps traders identify pinbar candlestick patterns on their charts. Pinbars are significant reversal patterns that can provide valuable trading opportunities.

This indicator scans the price data and detects pinbar patterns based on specific criteria, such as the length of the body and wicks. It also includes an RSI filter to further confirm the validity of the detected patterns.

When a valid pinbar pattern is identified, an alert is generated, allowing traders to take timely action. The alerts can be in the form of arrows displayed on the chart, indicating the direction of the pinbar pattern.

With Pinbar Candle Pattern Alert MT5, traders can improve their trading decisions by leveraging the power of pinbar patterns. Whether you are a beginner or an experienced trader, this indicator can be a valuable addition to your trading arsenal.

Please note that this product is developed by Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pinbar-mt5-software-review-optimize-forex-trade-alerts/). ForexRobotEasy is not the official developer of this product and only provides this code as a sample that can work as described in the product. For the official developer, please refer to MQL5. For detailed reviews and trading results of this product, please visit the provided link.
