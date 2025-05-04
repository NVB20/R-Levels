# R-Levels 🔫📈

**R-Levels** is a Pine Script project designed for TradingView that allows traders to visually plan trades based on any candle of their choice. By selecting a specific candle using its `bar_index` .

This is a great tool for **risk-reward visualization**, and **strategy refinement**.

---

## ✨ Features

- Simple, lightweight Pine Script (v6)
- Automatically plots:
  - ✅ Entry level
  - 🛑 Stop loss level
  - 🎯 3R and 6R target lines
- Labels each line for clarity
- Fully customizable via script input

---

## 📷 Quick Start
* Load the script onto your chart.
* Identify the bar index where you want to enter the trade.
![Alt text](images/load-script.png)

* Open the indicator settings by clicking the gear icon on the indicator name.
![Alt text](images/settings.png)

* In the settings popup:
  - Enter your selected value into the “Select Bar Index” input field.
  - (Optional) Disable “Show Bar Index Label” for a cleaner chart view.
  - (Optional) Enable “Use Custom High/Low” and manually enter your desired high and low values.

Click OK to apply the settings and view the calculated R-levels.

![Alt text](images/new-custom-high-low.png)

* The indicator now will show your:
  - Entry level, Stop loss
  - 3R and 6R targets
  
![Alt text](images/TTWO.png)

---

## 🛠️ How to Use
1. In Tradingview, Open the Pine Script Editor.
2. Copy the contents of candle_r_levels.pine into the editor.
3. Click Add to Chart.
4. In the settings (gear icon), input the bar_index of the candle you want to analyze.
5. You can find this by hovering over the candle and checking the Data Window.

6. The script will draw the following levels based on that candle:
    - ✅ Entry
    - 🛑 Stop Loss
    - 🎯 3R and 6R target levels
7. 🔔 You can also create TradingView alerts on the 3R and 6R lines:
    - Right-click on the 3R or 6R line drawn by the script.
    - Choose "Add Alert on Horizontal Line" or "Create Alert".
    - Customize your alert (e.g. crossing, once per bar close, etc.)
    - This lets you receive a notification when price hits your target!

---

