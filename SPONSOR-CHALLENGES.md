### Blizzard Finance

Note : We are not requesting front-end development work. All submissions, including those that do not win, will be considered for additional prizes. Exceptional entries that go above and beyond may receive bonuses. Winners are expected to integrate Blizzard Finance deeply at their core in their final product. Please keep in mind that additional rewards are not guaranteed and will be determined at our discretion.

- FlashFreeze Loans: A flash loans contract on Blizzard Finance. Feel free to get creative in how it would work, or ask any questions, but we are intentionally leaving this open ended.
- PermaFrost Perpetuals: Develop a perpetuals contract for seamless long and short trading on the Blizzard Finance. Feel free to get creative in how it would work, or ask any questions, but we are intentionally leaving this open ended.
- Subzero Lending: Build a lending contract that deposits LP tokens into the Blizzard vault and allows users to borrow against it. Funds should be locked for the loan term. Should have dynamic interest rates based on collateral LP value. The rate starts at the lender's set amount and adjusts as collateral value changes, with a set floor. 
- IceBound Options: Create an options contract on Blizzard Finance, enabling users to hedge risks or speculate on asset prices. Use pricing directly from Blizzard Vault. Feel free to get creative in how it would work, or ask any questions, but we are intentionally leaving this open ended.

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

### White Whale

#### Migaloo Chain
- Build a convenience tool suite that allows users to, for example, airdrop to the Migaloo community or create tokens using the token factory.
- Build a self-repaying-loan protocol that allows users to leverage against the future yield of any yield-bearing asset.
- Build a decentralized name service for Migaloo.
- Build a project incubator with a launchpad, crowdfunding, ICO, and liquidity bootstrapping.
- Build a FUN game on Migaloo.
- Build a stable coin native to the Migaloo ecosystem. The stablecoin could be overcollaterized by Whale or be algorithmically secured by its own token.
- Build an index token protocol for the Alliance assets on Migaloo.
- Build a a project funding service that allows users to lock their yield bearing assets to finance projects, teams, and effors using their staking rewads.

#### White Whale Protocol
- Modify our Smart Contracts to be compatible with SecretWasm.
- Modify our Smart Contracts to be compatible with the EVM.
- Modify our Frontend to be mobile compatible.
- Build a general-purpose DCA Tool that allows users to trade in or out any token listed on any White Whale satellite market by directly integrating with the White Whale DEX Router on every given chain.
- Build a market-making bot for pools on all White Whale satellite markets.

#### MEV
- Build a liquidtation bot for the Comdex Lending Market utilizing White Whale flashloans & pools.
- Build a liquidtation bot for the Comdex Stablecoin Market utilizing White Whale flashloans & pools.
- Build a arbitrage bot for the Comdex Orderbook utilizing White Whale flashloans & pools.
- Build a interchain arbitrage bot that stabilizes ampWhale & boneWhale prices across all satellite markets.
