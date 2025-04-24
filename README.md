# CandleSniper 🔫📈

**CandleSniper** is a Pine Script project designed for TradingView that allows traders to visually plan trades based on any candle of their choice. By selecting a specific candle using its `bar_index`, the script automatically draws the following levels on the chart:

- **Entry**: High of the candle + 0.01
- **Stop Loss**: Low of the candle - 0.01
- **3R Target**: Entry + (Candle Range × 3)
- **6R Target**: Entry + (Candle Range × 6)

This is a great tool for **manual backtesting**, **risk-reward visualization**, and **strategy refinement**.

---

## ✨ Features

- Simple, lightweight Pine Script (v5)
- Automatically plots:
  - ✅ Entry level
  - 🛑 Stop loss level
  - 🎯 3R and 6R target lines
- Labels each line for clarity
- Fully customizable via script input

---

## 📷 Preview

_(Add a screenshot here of the chart showing the lines and labels)_

---

## 🚀 How to Use

1. Open [TradingView](https://www.tradingview.com/).
2. Open the Pine Script Editor.
3. Copy the contents of `candle_sniper.pine` into the editor.
4. Add to chart.
5. In the settings (gear icon), input the `bar_index` of the candle you want to analyze.
   - You can find this by hovering over the candle and checking the Data Window.
6. The script will draw Entry, Stop Loss, 3R, and 6R levels based on that candle.

---

## 🛠 Development

### File Structure

