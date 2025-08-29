# RR Binazir Chart for MetaTrader 4

**Author:** Mohammad Reza Mokhtari Kia  
**Date:** 2025-08-29  

---

## 📈 Overview
**RR Binazir Chart** is an Expert Advisor (EA) for **MetaTrader 4** that visually displays rectangles and calculates **Risk-to-Reward (RR) ratios** for your open trades.  
It draws:
- A **red rectangle** from Entry to Stop-Loss (SL)
- A **green rectangle** from Entry to Take-Profit (TP)
- The **RR ratio** in the top-right corner of the chart with one decimal precision  

Whenever you modify your SL or TP, the rectangles and RR label update automatically. When a trade is closed, the shapes are removed.

---

## 🛠 Installation Instructions

### 1. Download the EA file
Download the `RR binazirchart.mq4` file from the link below:  
[RR binazirchart.mq4 on GitHub](https://github.com/mr-mm12/MT4/blob/main/RR%20binazirchart.mq4)  

You can download it by either:  
- Clicking the **three dots** in the top-right corner of the GitHub page and selecting **Download**, or  
- Using the keyboard shortcut **Ctrl + Shift + S** to save the file.

### 2. Locate your MetaTrader 4 `Experts` folder  
Navigate to your MT4 data folder. Example path:  
C:\Users<YourUserName>\AppData\Roaming\MetaQuotes\Terminal<YourTerminalID>\MQL4\Experts

### 3. Copy the EA file  
Place the downloaded `RR binazirchart.mq4` file into the `Experts` folder.

### 4. Open the EA in MetaTrader 4  
- Restart MetaTrader 4 (or refresh the Navigator).  
- Press **Ctrl + N** to open the Navigator panel.  
- Locate **RR binazirchart** under **Expert Advisors**.  
- Double-click it and click **OK** to attach it to your chart.

### 5. Start Trading  
Open a trade (Buy or Sell).  
You will now see the **entry, SL, TP rectangles** and the **RR ratio** in the **top-right corner** of the chart.

---

## ⚙ Features
- Dynamic rectangles for Entry → SL / TP  
- Real-time **Risk-to-Reward ratio** calculation  
- Auto-update on SL/TP changes  
- Auto-remove visuals when a trade is closed  
- Customizable colors, font size, and rectangle width  

---

## 🖌 Customization
You can change colors, rectangle width, and label font in the EA **input parameters**:
- **SL_Color** → Change Stop-Loss rectangle color
- **TP_Color** → Change Take-Profit rectangle color
- **RR_Label_Color** → Change RR text color
- **Rect_Bars_Ahead** → Adjust rectangle width (in bars)
- **RR_FontSize** / **RR_FontName** → Adjust RR label font

---

## 💡 Notes
- Ensure the EA is attached to the chart **before opening trades** to see the visuals immediately.
- Works only on **the symbol the EA is attached to**.
- RR ratio is rounded to **1 decimal place**.

---

Enjoy monitoring your trades with a clear **Risk-to-Reward visualization**! 🚀
س
