# Hide Scale MT4

This code is designed to hide the scale value of price charts on the MetaTrader 4 platform. It provides two functions - `HideScale()` and `CustomizeScaleDisplay()` - that allow users to customize the display of scale values according to their preferences.

## How it Works

1. The `HideScale()` function hides the scale value by setting the `CHART_SHOW_PRICE_SCALE` property to `false` using the `ChartSetInteger()` function.

2. The `CustomizeScaleDisplay()` function allows users to customize the display of scale values. It takes three parameters: `textColor`, `font`, and `anchorPoint`.

   - `textColor` specifies the color of the scale values using the `ChartSetInteger()` function with the `CHART_COLOR_SCALE` property.
   
   - `font` specifies the font of the scale values using the `ChartSetString()` function with the `CHART_FONT_SCALE` property.
   
   - `anchorPoint` specifies the position of the scale values using the `ChartSetInteger()` function with the `CHART_SCALE_Y_ANCHOR` property.

3. The `OnStart()` function is the main function that executes when the script is run. It calls the `HideScale()` function to hide the scale value and then calls the `CustomizeScaleDisplay()` function to customize the display of scale values. In this example, the scale values will be displayed in blue color, using the Arial font, and anchored at the bottom-right corner of the chart.

## Product Description

[Hide Scale MT4](https://forexroboteasy.com/forex-robot-review/hide-scale-mt4-review-unbiased-analysis-of-forex-software/) is a customizable MetaTrader 4 indicator that allows users to hide the scale value of price charts and customize the display of scale values according to their preferences.

This indicator provides two functions - `HideScale()` and `CustomizeScaleDisplay()` - that can be used to modify the appearance of scale values on the chart.

The `HideScale()` function hides the scale value completely, providing a clean and clutter-free chart view.

The `CustomizeScaleDisplay()` function allows users to customize the display of scale values by specifying the color, font, and anchor point. Users can choose from a wide range of colors, fonts, and anchor points to create a personalized chart display.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that demonstrates how this indicator can work as described. To find the official developer of this product, please refer to the MQL5 platform.
