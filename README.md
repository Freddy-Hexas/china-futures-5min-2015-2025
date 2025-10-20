# China Futures 5-Minute Interval Data (2015-2025)

This repository contains high-frequency futures data for various contracts in China's futures market, spanning from April 16, 2015, to June 30, 2025, at 5-minute intervals. The dataset is organized by different futures exchanges, including:

- **CFFEX** (China Financial Futures Exchange)
- **CZCE** (Zhengzhou Commodity Exchange)
- **DCE** (Dalian Commodity Exchange)
- **GFEX** (Guangzhou Futures Exchange)
- **INE** (Shanghai International Energy Exchange)
- **SHFE** (Shanghai Futures Exchange)

Each exchange is further organized by the different futures contracts (e.g., IC, IF, IH, etc.), with data for each contract provided in separate CSV files, organized by year and month. The dataset includes contract data such as open, high, low, close, and volume at 5-minute intervals.

### **Data Structure**
- The data is organized by futures exchanges, with each exchange folder containing multiple subfolders for different contracts (e.g., **IC**, **IF**, **IH**, etc.).
- Each contract folder contains CSV files, each corresponding to a specific month and year (e.g., `IC1505.csv` for May 2015 contract data of the IC contract).

### **Example Data Files**
- `CFFEX/IC/IC1505.csv` (May 2015 contract for IC)
- `CZCE/AP/AP1805.csv` (May 2018 contract for AP)

### **Data Usage**
- This data is ideal for researchers, analysts, and traders who wish to analyze historical market trends and conduct high-frequency trading strategies or other types of financial research.

### **License**
This dataset is licensed under the **CC0** (Public Domain Dedication) License, meaning you can freely use, modify, and distribute it.

