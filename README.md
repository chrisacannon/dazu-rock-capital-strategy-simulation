# Dazu Rock Capital — Strategy Simulation

A simulation-based demonstration of a tiered portfolio strategy with actively managed options positions, tested across two historically distinct market environments.

**Live site:** [chrisacannon.github.io/dazu-rock-capital-strategy-simulation](https://chrisacannon.github.io/dazu-rock-capital-strategy-simulation)

---

## What This Is

This project models a three-tier investment framework — core index participation, directional equity and options positions, and a speculative tier — applied to 2022 (bear market) and 2024 (bull market) conditions. The central analytical question: how does active options management, specifically profit-taking on puts during large down moves rather than passive hold-to-expiration, affect portfolio outcomes across different regimes?

All performance data is simulated and illustrative of investment approach only. No actual trades, client assets, actual portfolio returns, or proprietary records are represented.

---

## Framework Overview

| Tier | Description | Allocation |
|------|-------------|------------|
| I | Core index exposure (SPY/QQQ) with actively managed put overlay | 65–75% |
| II | Directional equity positions + targeted long calls on researched names | 10–18% |
| III | Speculative — small caps, short-dated options, crypto | 1–4% |
| Cash | Strategic buffer — funds options premium, supports rebalancing | 8–15% |

Academic grounding: core-satellite theory (Leibowitz & Bova, 2005), tactical asset allocation (Faber, 2007), momentum factor (Jegadeesh & Titman, 1993), barbell strategy (Taleb, 2012), Kelly Criterion (Kelly, 1956).

---

## Simulations

**2022 — Bear Market:** S&P 500 −19.4%. Four identifiable bear market legs with intervening rallies. Simulated strategy return: **+5.5%** (+24.9pp vs. benchmark).

**2024 — Bull Market:** S&P 500 +24.2%. Low volatility, AI-driven Mag 7 concentration. Simulated strategy return: **+27.4%** (+3.2pp vs. benchmark), with outperformance driven primarily by the April put trade.

---

## Files

- `index.html` — Strategy overview, tier construction, risk framework
- `simulation-2022.html` — Bear market simulation with interactive charts
- `simulation-2024.html` — Bull market simulation with cross-regime comparison

---

*Simulation disclosure: All figures are modeled outputs and do not represent actual investment results, actual trading history, or the performance of any real account. Dazu Rock Capital is a private investment vehicle. This is not investment advice.*
