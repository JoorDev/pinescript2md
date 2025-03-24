# pinescript2md
**pinescript2md** is a Pine Script tool that converts key technical analysis data into a neatly formatted Markdown report. It simplifies tracking essential market metrics like moving averages, RSI, support/resistance levels, and volume trends.

This repository hosts a Pine Script indicator that performs technical analysis by calculating:
- **Current Price**: The last closing price.
- **50-day Moving Average (MA)**: A simple moving average over 50 days.
- **Relative Strength Index (RSI)**: Computed over a 14-day period.
- **Support Level**: The lowest low in the past 20 bars.
- **Resistance Level**: The highest high in the past 20 bars.
- **Volume Trend**: A comparison of the current volume to the average volume over the last 7 bars to indicate if the trend is increasing or decreasing.

## Script Overview

The script uses TradingView's Pine Script (version 6) to calculate the above metrics. It generates a Markdown formatted text block summarizing the indicator’s values and logs this output.

## How to Use

### Copy the Script:

Copy the Pine Script code from the repository into your TradingView Pine Script editor.

### Apply the Script:

Add the indicator to your chart by saving and applying the script on TradingView.

### Interpret the Output:
    The script logs a Markdown table in the console (or logs) that summarizes the key technical metrics:

        Current Price

        50-day MA

        RSI

        Support

        Resistance

        Volume Trend

## Customization

Feel free to modify parameters such as lengthMA, lengthRSI, supportBars, and volumeLookback to suit your trading strategy or market conditions.
Contributing

Contributions, improvements, or suggestions are welcome. 

## License

This project is licensed under the MIT License.
