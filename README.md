
```markdown
# Systematic Trading Journal Assist

A CLI-based trading decision support and journaling tool designed to help traders follow a **systematic, rule-based trading process**.

This project focuses on **discipline, consistency, and review**, not automation or live trading.

---

## What This Project Does

- Displays mandatory **pre-trade rules** at startup
- Evaluates trade setups using **YES / NO strategy questions**
- Calculates trade probability based on rule confluence
- Suggests whether to **Take Trade / Wait / Don’t Trade**
- Enforces a **maximum of 3 trades per day**
- Records executed trades
- Allows adding **Profit & Loss (P&L)** later
- Shows a simple **performance dashboard**

> This is NOT a trading bot  
> No live data, no indicators, no automation

---

## Core Idea

Most trading losses come from:
- Breaking rules
- Overtrading
- Emotional decisions
- Poor journaling

This tool helps reduce those mistakes by enforcing **process before execution**.

---

## Features

### Pre-Trade Discipline
- Displays fixed trading rules and reminders
- No interaction or scoring
- Acts as a mental reset before analysis

### Strategy Evaluation
- Separate logic for **BUY (Bullish)** and **SELL (Bearish)**
- Rule-based questions answered with YES / NO
- Probability calculated from confirmations

Example:

Score: 11 / 13
Probability: 84.6%
Suggestion: TAKE TRADE


### Trade Journal
- Records:
  - Date
  - Symbol
  - Side (BUY / SELL)
  - Strategy score
  - Probability
  - Lots
  - P&L (added later)

### Dashboard
- Total trades
- Winning vs losing trades
- Win rate
- Total P&L
- Average P&L per trade

---

## How It Works (Flow)

1. Show pre-trade rules
2. Choose BUY or SELL
3. Answer strategy questions
4. Calculate probability
5. Get trade suggestion
6. Confirm if trade was taken
7. Save trade
8. Update P&L later
9. View dashboard

---

## Tech Stack

- Python
- Command Line Interface (CLI)
- Uses:
  - Classes & objects
  - Lists & dictionaries
  - Functions

No external libraries required.

---

## Project Goals

- Improve trading discipline
- Reduce emotional decisions
- Maintain a clean trading journal
- Practice real-world Python design

---

## Disclaimer

This tool does not provide financial advice.  
All trading decisions are made by the user.

---

## Author

Personal project built to combine **systematic trading discipline** with **Python fundamentals**.
```
