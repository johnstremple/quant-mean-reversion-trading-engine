# Quant Mean Reversion Trading Engine

A Python-based algorithmic trading research system designed to analyze institutional market behavior and mean reversion signals using SPY as a market sentiment and liquidity indicator.

Instead of trading SPY directly, this model identifies potential market reversal zones and uses those signals to confirm bullish or bearish breakout entries in individual equities. The objective is to improve trade timing, reduce false breakout signals, and align individual stock momentum with broader market conditions.

---

## Strategy Overview

The model evaluates institutional flow and liquidity behavior within SPY to identify potential mean reversion opportunities and market turning points. These signals act as confirmation tools when trading breakout setups across correlated equities.

By combining index-level market sentiment with individual stock momentum, the system aims to improve probability-based trade entry decisions.

---

## Features

- Institutional flow signal detection  
- Mean reversion analysis using SPY market behavior  
- Breakout trade confirmation framework  
- Custom backtesting engine  
- Performance tracking and trade analytics  
- Modular architecture designed for strategy expansion  

---

## Development History

The initial version of this model was created in 2024 and used during live swing trading as a decision-support tool to confirm breakout entries.

The current version represents a refactored and expanded rebuild focused on improved modular architecture, cleaner code structure, and a dedicated backtesting engine for systematic strategy evaluation.

---

## Example Use Case

The model is designed to support discretionary or systematic swing trading strategies by:

- Confirming overall market direction  
- Identifying potential reversal zones  
- Filtering false breakout trades  
- Improving entry timing using index-level liquidity signals  

---

## Project Structure

```
quant-mean-reversion-trading-engine/

strategies/     → Trading signal logic  
backtesting/    → Backtesting engine and simulation tools  
results/        → Performance output and trade logs  
```

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- JSON data processing  
- Quantitative trading research methods  

---

## Example Results

The strategy was evaluated using historical SPY data to identify reversal zones and breakout confirmation signals. The system was also applied during live swing trading as a decision-support research tool.

Backtesting performance results and trade logs are available in the `results/` directory.

---

## How To Run

### 1. Clone Repository

```
git clone https://github.com/johnstremple/quant-mean-reversion-trading-engine.git
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run Backtesting Engine

```
python backtesting/backtest_engine.py
```

---

## Future Improvements

- Machine learning signal optimization  
- Real-time data pipeline integration  
- Automated trade execution framework  
- Multi-index confirmation models  
- Enhanced visualization and analytics dashboard  

---

## Motivation

This project was developed to explore systematic trading strategies, institutional liquidity behavior, and quantitative market analysis while strengthening Python development and financial modeling skills.

---
