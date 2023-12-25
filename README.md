# Bollinger Bands Scanner Full

This code implements a Bollinger Bands scanner to identify the number of bars that occurred before the price closed above or below the upper or lower band.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/bollinger-band-scanner-full-review-elevate-your-forex-trading/).

## Terms of Reference for Writing Code

- Version: 1.0
- Developer's site: [Forex Robot Easy Team](https://forexroboteasy.com)

## Global Variables

- `timeframe` (input int): User-defined timeframe.
- `barsCount` (input int): Number of bars to track.
- `upperBand[]` (double): Array to store upper Bollinger Band values.
- `lowerBand[]` (double): Array to store lower Bollinger Band values.
- `barsSinceCloseAboveUpper` (int): Number of bars since the price closed above the upper band.
- `barsSinceCloseBelowLower` (int): Number of bars since the price closed below the lower band.

## Initialization Function

The `OnInit()` function is responsible for setting up the Bollinger Bands and the chart.

## Main Program Execution

The `OnTick()` function is the main program execution. It calculates the Bollinger Bands and checks if the price closed above or below the bands. It then prints the number of bars since the price closed above or below the bands.

## Program Termination Function

The `OnDeinit()` function is responsible for cleaning up the arrays used for the Bollinger Bands.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
