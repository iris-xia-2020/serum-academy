---
date: 2020-08-30T00:0:00+00:00
title: Add a market on Serum
weight: 6
---

## Add a market on Serum

If you want to add a new market to Serum follow the steps below:

- The first step is to use [Sollet.io](https://sollet.io) to convert between ERC20 and SPL

- Create a new market see [Github](https://github.com/project-serum/serum-dex/blob/master/dex/src/instruction.rs)

- Run cranks see [Github](https://github.com/project-serum/serum-dex/blob/master/crank/src/main.rs#L297)

- Add the market to [your GUI](https://github.com/project-serum/serum-dex-ui)

- After creating a new market you will have to think about liquidity on this market
