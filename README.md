# SMC-Trading-Algorithm

## Overview
SMC-Trading-Algorithm is an algorithmic trading system based on **Smart Money Concepts (SMC)**. It leverages liquidity sweeps, break of structure (BOS), and fair value gaps (FVG) to identify high-probability trade setups. 

## Features
- **Liquidity Sweep Detection** – Identifies liquidity grabs before trend reversals.
- **Break of Structure (BOS)** – Recognizes key shifts in market structure to confirm trade bias.
- **Fair Value Gap (FVG) Utilization** – Pinpoints imbalance zones for precision entries.
- **Customizable Parameters** – Adjust risk, trade frequency, and entry conditions.
- **Backtesting Support** – Test strategies on historical data before live execution.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/newoatsoca/SMC-Trading-Algorithm.git
   ```
2. Navigate to the project folder:
   ```bash
   cd SMC-Trading-Algorithm
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
## Technologies Used
- **Language**: Python
- **IDE**: Jetbrains' PyCharm
- **API**: Alpaca Market Data API
- 
## Configuration
Modify `config.py` to customize:
- Trading exchange (e.g., ES, NQ, EUR/USD)
- Timeframe selection (e.g., 1m, 5m, 15m)
- Risk management settings

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
