# Automated-Paper-Trading-Execution-Workflow
Automated paper trading system that simulates live trade execution with risk controls, PnL tracking, and performance analytics using real market data.

Project 6: Automated Paper Trading & Execution Workflow

This project implements a fully automated paper trading system that simulates realistic trade execution, portfolio accounting, and risk management using historical market data. The goal is to bridge the gap between backtesting and live trading by modeling execution timing, transaction costs, and capital constraints.

The system downloads market data, generates trading signals, executes trades under predefined rules, and continuously tracks portfolio performance and risk metrics.

Key Features:-

Market Data Integration

Downloads historical equity price data using yfinance

Robust handling of real-world data issues (missing values, column formats)

Signal Generation

Simple momentum-based strategy using moving average (SMA)

Binary long / flat positioning based on trend signals

Execution Simulation

Trade execution at next-day open or same-day close

Transaction costs modeled via commissions and slippage

Position sizing with leverage constraints

Risk Management

Maximum daily loss protection

Maximum portfolio drawdown halt

Automatic position flattening during risk breaches

Portfolio Accounting

Cash balance and position tracking

Mark-to-market valuation

Daily PnL and cumulative equity curve

Performance Analytics

Total return and annualized return

Annualized volatility and Sharpe ratio

Maximum drawdown

Trade-level execution logs

Outputs & Visualization

Equity curve and drawdown plots

CSV exports of portfolio ledger, trades, and performance statistics
