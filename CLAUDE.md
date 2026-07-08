# CLAUDE.md — Nick-Holder Capital Group
## Project Orchestration Context

Read this file in full before taking any action in this project.

## 1. Firm Overview

Nick-Holder Capital Group is a proprietary trading firm owned by Nick (founder and sole principal), structured through two Bulgarian entities:
- Nick-Holder Capital EOOD — holding company
- Nick-Holder Investments EOOD — trading subsidiary (10% corporate tax)

## 2. The Trading Model

Four-Step Entry Sequence:
1. Liquidity sweep — price takes out a prior high or low
2. Displacement — strong impulsive move away from swept level
3. FVG return — price retraces into the fair value gap
4. Confirmation signal — defined trigger at the FVG

Risk Framework:
- Max risk per trade: 0.5% of account
- Max trades per day: 2
- Weekly drawdown limit: 3%
- Instrument: GER40

## 3. Folder Structure

- trade-logs/ — live trade records (read-only for agents)
- reports/ — monthly CEO reviews
- compliance/ — Bulgarian entity obligations
- backtests/ — all backtest work
- docs/ — firm documentation

## 4. The Agent Team

- risk-auditor: checks trades vs rules. Read only.
- reporting-clerk: monthly CEO review documents.
- compliance-ops: Bulgarian entity obligations.
- backtest-engineer: builds and runs GER40 backtests.
- research-analyst: pre-session macro briefs.
- brand-content: website and external content.

## 5. Standing Instructions

- Never modify the Operating Manual without explicit instruction from Nick.
- Never execute trades or connect to a broker API.
- Never fabricate data. Report gaps honestly.
- When in doubt: stop and ask Nick.
