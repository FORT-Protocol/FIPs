---
fip: 1
title: Replace trading pairs and dealing with the assets in DAO
description: swap 70 million NEST into ETH with NEST-DAO, then swap ETH to USDT; replace the trading pairs DCU/NEST on BSC with DCU/USDT.
author: James
discussions-to: ---
created: Feb-08-2022 06:30 AM +UTC
---

## Abstract
- Removing the swap function on Ethereum
- Replace the trading pairs DCU/NEST with DCU/USDT on BSC 
- Replace 70 million NEST in DAO with USDT and put in DCU/USDT pairs

## Motivation
Considering the expansion of FORT community, we decide to cancel the DCU/NEST trading.
Since the swap on ETH has high transaction fees and few traders, the swap function on ETH will be suspended. 
70 million NEST will be swap to ETH with NEST-DAO and then swap for USDT with uniswap or pancake.
The trading pairs DCU/NEST on BSC will be replaced with DCU/USDT.


## Specification

Identifying the assets in FORT-DAO as follows:

- ETH Swap: 74,238,152.22NEST + 3,030,786.64DCU
- BSC Swap: 72,209,579.20NEST + 3,115,915.08DCU
- DAO Assets: 10,000,000DCU
- NEST Oracle Incentive: 2,600,000,000DCU
- Operational Consumption: 250,000DCU + 20,000DCU + 5,000DCU * 10

Total: 146,447,731.42NEST + 41,826,701.72DCU
