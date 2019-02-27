# IndexRiskOn
## General strategy assumptions
1. Market (index) is always growing due to economic growth with average annual total return ~ 7%
1. Market is fluctating: it has upturns and downturns due to:
    1. investor emotions and sentiment
    1. economic changes (crisises)
    1. gaps between buyers and sellers in specific moment
1. Market over the time returns to average growth rate of 7%
1. Broker commission may be included as part of each limit order (buy or sell)

## Strategy principles
1. Buy low, sell high
1. Have less risk (equity) when market grows
1. Have more risk (equity) when market drops
1. Rebalance on market fluctuations (selling volatility)

## Strategy assets
1. Index funds, broad diversification is important, because one company may become bankrupt ("A rising tide lifts all boats except those that sink")

## Strategy rules
1. Strategy should sell out to minimum (MinP) when market reaches new all time high (NATH) (+7% including dividends from old time high (OTAH))
1. Strategy should max out equity (MaxP) when market is down 50%+ from expected all time high
1. Minimal profit per lot/contract is required, f.e. 0.5% + 7% APR
1. For current market price value (from 0% to 50%+ (CurP)) optimal portfolio value between MinP and MaxP is calculated OptP and strategy tried to rebalance portfolio to new OptP, but taking into account minimal profit per lot/contract

# Terms

# Input parameters
1. OTAH
    1. Price
    1. Date max was reached
    1. Dividends history

# Output parameters
