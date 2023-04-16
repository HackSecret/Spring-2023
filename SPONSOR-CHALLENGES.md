### Shade Protocol

##### Tier 1: Attract developers to Secret Network as potential hires; incentivize developers to build full products for Shade Protocol

- Build a Yearn-style product that allows users to deposit SILK, and allow the creation of arbitrary strategies that can be plugged into the contract that utilize deposited funds to generate yield.
- Implement Trader Joe’s Liquidity Book as a Secret Network contract that works with the ShadeSwap pool factory
- Implement Pendle-style interest rate derivatives on Secret Network

##### Tier 2: Attract power users to conduct off-chain arbitrage activity on Secret Network

- Build an arbitrage bot that utilizes ShadeSwap’s liquidity pools to execute arbitrage trades on Osmosis using IBC.
- Build an arbitrage bot that utilizes ShadeSwap’s derivative pools to execute staking derivative arbitrage using Stride’s derivatives and IBC.
- Build an arbitrage bot that utilizes ShadeSwap’s derivative pools to execute staking derivative arbitrage using Shade Protocol’s stkd-SCRT derivative.
- Build a liquidation bot that executes liquidations on Shade Lend
- Build an arbitrage bot that executes arbitrage across ShadeSwap’s stablecoin pools
- BONUS: Build a contract that allows users to deposit SILK, and have the arbitrage bot utilize the deposited SILK for arbitrage, returning profits to the pool, and guaranteeing the arbitrage is profitable (LUNA’s White Whale style)
- Build an arbitrage bot that executes arbitrage between ShadeSwap’s stablecoin pools and higher liquidity ETH pools (e.g. Curve, Uniswap V3)
- This involves a Secret Network contract, solidity contract, IBC integration, and Axelar GMP integration.
- BONUS: Build a contract that allows users to deposit SILK, and have the arbitrage bot utilize the deposited SILK for arbitrage, returning profits to the pool, and guaranteeing the arbitrage is profitable (LUNA’s White Whale style)

### SecretSwap 2.0

- Build vaults for yearn like vaults on top of secretSwap 2.0 contracts that only take one asset and produce the yield in that asset only. One vault could be to deposit SCRT and will earn yield either from liquid staking, LPing into bSCRT/SCRT or seSCRT/SCRT pools or buying liquid staked assets bSCRT, seSCRT as discount from open market and unstaking to get profit in SCRT. Another vault could be to deposit in stables like axlUSDC and depositing into pools and getting yield in stables only.

- Build arbitrage bots for anyone to do arbitrage b/w secretSwap pairs or even b/w pairs of multiple DEXs on Secret Network or even with IBC connected DEXs like Osmosis and Wynd.

- Build an analytics dashboard for SecretSwap 2.0 contracts with proper indexing to showcase price, volume and yield history for individual pairs and for the overall DEX. Can be further extended to show user specific data such as assets value held over time, impermanent loss calculator etc.

- A convex like protocol for ve gauges of secretSwap 2.0. Convex allows users to deposit their CRV token and get boosted rewards while having the option to withdraw anytime sacrificing on higher % of CRV emissions.

### Sienna Protocol

##### TBD

### Blizzard.Finance

##### TBD

### White Whale

##### TBD
