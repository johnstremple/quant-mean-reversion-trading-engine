# Quant Mean Reversion Trading Engine

## Overview
A Python-based quantitative research project designed to test whether SPY mean reversion signals can improve breakout confirmation in correlated equities. This system focuses on structured research, modular design, and systematic backtesting.

## Problem
Breakout strategies often fail due to poor market timing. This project evaluates whether index-level reversals (SPY) can act as a confirmation filter to reduce false breakout entries.

## What This Project Does
- Detects mean reversion conditions in SPY
- Uses those signals to confirm breakout setups
- Simulates trades using a custom backtesting engine
- Tracks performance metrics (win rate, drawdown, profit factor)
- Stores trade logs and results for analysis

## Project Structure
strategies/ → signal logic  
backtesting/ → trade simulation engine  
results/ → output data and performance logs  

## Performance Evaluation
The system evaluates:
- Win rate
- Profit factor
- Maximum drawdown
- Trade frequency
- Risk-adjusted performance

## Version History
v1 (2024): Initial prototype used for research and discretionary decision support  
v2 (2025): Refactored modular rebuild with structured backtesting engine  

## Limitations
- Uses static parameters
- Historical data only
- No live API integration
- No walk-forward validation yet

## Future Improvements
- Add parameter optimization
- Add walk-forward validation
- Integrate real-time data
- Build visualization dashboard

## Tech Stack
Python  
Pandas  
NumPy  
JSON configuration  

## Motivation
Built to strengthen systematic trading research, risk modeling, and Python engineering skills through structured experimentation and iterative development.

---
