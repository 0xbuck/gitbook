# Crash Resistance

### <mark style="color:purple;">TWAP to Spot Oracle Switch</mark>

Calculation of TCR is completely dependent on price information from Oracle. One of the main problems in the case of Iron-Titan's bank-run was that their Time Weighted Average Price (TWAP) based Oracle was not responsive enough to handle price drops during massive selling pressure. TWAP oracle gave stale price where the price was still much higher than the actual price.&#x20;

Buck is equipped with <mark style="color:purple;">**Rapid Oracle Switch**</mark> which can change Oracle Mode from TWAP to Spot immediately in the event of massive selling pressure.&#x20;

By getting more real-time price information from Spot Oracle, the TCR can be updated with more precision, the mint/redeem function finally works properly so the stablecoin (BUCK) can recover its peg price.

### <mark style="color:purple;">**Options Liquidity Mining (OLM)**</mark>

Referring to the case of massive selling pressure of the TITAN value accrual token (in this project the token is BEVY) due to over-circulation in the market as a result of TITAN's massive farming bonus, we made several modifications by changing the Farming method to <mark style="color:purple;">Options Liquidity Mining (OLM)</mark> as discovered by Sushiswap Team and described [here](https://andrecronje.medium.com/liquidity-mining-rewards-v2-50896e44f259).
