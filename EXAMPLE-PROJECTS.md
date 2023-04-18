## Layer 2 DeFi / DeFi 3.0 example projects.

--> Presentation about the current defi Landscape by Waffle (from LodeStar finance) -- Here

### (LSD) arbitrage vaults

Make a vault that can execute arbitrage trades over various liquid staking derivatives on Secret DEXs and returns profit as an autocompounding token

Possible design:
- Commit sSCRT, stkd-SCRT, SeSCRT, bSCRt, stSCRT etc. into Vault (imbalanced - Fee is lower if contributing the required assets)
- Disperse Vault LP tokens - represents aggregate of staking derivatives
- Vault executes arbitrage trades between staking derivatives cross-dex
- Arbitrage revenue is compounded by retaining the LSD SCRT revenue
- Vault LP token can be used as collateral in DeFi (looping, borrowing, self repaying loans etc)
- Contract owner or DAO can take a fee for own revenue
- Contract can also arbitrage its own Vault LP token as revenue source

### Margin trading via Money markets

Make a contract and Backend that can create margin positions using user colleteral and available money market solutions like shade/Sienna lend. Start with simple 1.25 or 1.5x long/short but can be expanded with one-click looping to create even 2.5x leverage trades.

### Limit orders that Execute on pools / private orderbook

Leverage existing dexpools to execute limit orders set into a contract by users. Additionally a private orderbook could be added that requires trades to be set on both sides.
Starting code and UI for this exists: https://github.com/btn-group/sn-limit-orders

### One-click UX (for ex: Delta neutral interest arbitrage)

Leverage available money-markets to take out strategies in a simple click - for ex leveraged long, leveraged yield farm, delta neutral interest arbitrage etc. - leveraged yield farming also usable than by other protocols like: https://nolus.io/ or https://www.quasar.fi/

### Flashloans

Create a flashloan vault to be used for arbitrage and other strategies by users on Secret Defi products over a single block.

### Private On-chain Options - Price betting

Create option vaults (either set or fluid prices) for existing liquid tokens. Options could be p2p like for ex: https://www.dopex.io/ with added liquidity for the options itself but one could also make this as a more betting like product.
In that case odds/price gain wouldnt be known in advance and fees wouldnt be split with liquidity providers. Instead Buyers and sellers can deposit liquidity themselves on a strike price being over or under, the winning position takes all or a % of the funds from the losing side.
Additionally one could combine this with a revenue streaming protocol like: https://beta.streamswap.io/ so to disperse revenue more easily during the time the bet is open.
This is cool to build on Secret as you could potentially hide the liquidity entered as buy/sell and thereby hide the execution price/revenue take.

### Stablecoin/Defi insurance


### Yield trading protocol

Emulate https://www.pendle.finance/ but then for SILK, stkd-SCRT or other set revenue tokens on Secret chain.

### undercolleteralised lending leveraging ICA

Integrate your protocol cross-chain with https://nolus.io/ so that borrowers can execute these defi strategies on secret. or even emulate the same functionality here leveraging native Secret liquidity and execution of native straegies.
