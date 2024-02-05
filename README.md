# UGenesys MultiTrend Indicator
## Developer: Forex Robot Easy Team
## Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)

This is the code for the UGenesys MultiTrend Indicator developed by the Forex Robot Easy Team. This indicator is designed to enhance forex trading by providing trend insight. It calculates multiple trend oscillators and generates a main buffer value based on these oscillators.

### Indicator Parameters
- oscillatorPeriod: The period used for calculating the trend oscillators. The default value is 14.

### Indicator Buffers
- mainBuffer: The buffer that holds the main indicator values.

### Trend Oscillators
- oscillator1 to oscillator15: Arrays that hold the values of the trend oscillators.

### Initialization Function
The OnInit() function is called when the indicator is initialized. It sets the indicator buffers and resizes the trend oscillators arrays based on the number of bars.

### Deinitialization Function
The OnDeinit() function is called when the indicator is deinitialized. It clears the trend oscillators arrays to free up memory.

### Calculation Function
The OnCalculate() function is called to calculate the indicator values. It calculates the trend oscillators for each bar and then calculates the main buffer value based on these oscillators.

To calculate the trend oscillators, the code iterates through the bars from the last calculated bar to the current bar. For each bar, it calculates the values of oscillator1 to oscillator15 using specific formulas (not shown in the code).

After calculating the trend oscillators, the code iterates through the bars again to calculate the main buffer value. The calculation of the main buffer value is also done using a specific formula (not shown in the code).

The rates_total, prev_calculated, time[], open[], high[], low[], close[], tick_volume[], volume[], and spread[] parameters passed to the OnCalculate() function provide the necessary data for the calculations.

### Product Description
The UGenesys MultiTrend Indicator developed by the Forex Robot Easy Team is a powerful tool designed to enhance forex trading by providing trend insight. It calculates multiple trend oscillators based on the specified period and generates a main buffer value that represents the overall trend.

This indicator can be used to identify trends and potential trend reversals, allowing traders to make informed trading decisions. By analyzing the trend oscillators and the main buffer value, traders can gain valuable insight into market trends and improve their trading strategies.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/ugenesys-multitrend-review-enhance-forex-trading-with-trend-insight/).
