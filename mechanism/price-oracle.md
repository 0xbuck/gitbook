# Price Oracle

### <mark style="color:purple;">**Oracle**</mark>

To ensure the integrity of BUCK peg, the BUCK Stablecoin gathers necessary data, such as market price and liquidity pool information, from external locations or "Oracle". BUCK Stablecoin currently makes use Sushiswap on Arbitrum **** Oracle. The integrity of the system relies on an accurate price of BUCK and BEVY. To achieve this the U.S. Dollar price of DAI is one time retrieved from Chainlink**.** This gives the protocol a consistent and up to date reading of the USD price of BUCK and BEVY**,** used **** in calculating the TCR. BUCK's peg value is backed by a consistent price of USD and not a basket of on-chain stablecoins, the prices of which can deviate significantly.

### <mark style="color:purple;">Chainlink</mark>

Chainlink's Price data provide an on-chain, untampered feed of market prices. Using the Chainlink "oracle" eliminates the risk of inaccuracies in the liquidity pool data of an active Automated Market Maker(AMM) on a Decentralized Exchange(DEX) .
