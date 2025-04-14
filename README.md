# pine-script-indicators
A showcase of advanced Pine Script indicators built for TradingView.
# Short Term Mean Reversion Indicator

## Description
The **Short Term Mean Reversion** indicator identifies potential **counter-trend trading opportunities** based on price behavior around Bollinger Bands. It detects short-term price reversals when the price deviates significantly from its recent average. This indicator can be used for **scalping** or **range-bound market strategies**.

### **Screenshot of Indicator in Action:**
![Short Term Mean Reversion Indicator](screenshots/short_term_mean_reversion.png)

## Pine Script Code:
The full Pine Script code for the indicator is available in the (https://github.com/Pa1Tiwari/pine-script-indicators/blob/e745dcbc42eb49999c93e375d80ce66d9fe27c40/src/short_term_mean_reversion.pine)

### **Core Features:**
- **Long signal** (Green): When the price opens below the lower Bollinger Band and closes higher (bullish reversal).
- **Short signal** (Red): When the price opens above the upper Bollinger Band and closes lower (bearish reversal).
- Customizable **Bollinger Band settings** (length and standard deviation).
- Displays visual **signals** on the chart with arrows and labels.
- Background color highlights for long and short signals.

### **Inputs:**
- **Length**: Period for Bollinger Band moving average.
- **Source**: The price source to be used for the calculation.
- **Std Dev Multiplier**: Standard deviation multiplier for the band width.

### **Visual Features:**
- **Green background** for Long signals.
- **Red background** for Short signals.
- **Long/Short labels** at the entry point.
  


### **Usage:**
This indicator works best in **range-bound markets** or for **short-term scalping** strategies. It is recommended to use it in conjunction with other indicators or price action analysis for better accuracy.



## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

