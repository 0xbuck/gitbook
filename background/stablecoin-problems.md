# Stablecoin Problems

DAI is an <mark style="color:purple;">**over-collateralized**</mark> stablecoin that requires an issuer to post 150% collateral. In other words, if a user wanted to mint 100 DAI, they would have to send $150 in Ethereum to the protocol. If the value of the collateral were to fall below a certain threshold, this position could be liquidated. The value of this collateral is what maintains the value of DAI pegged.



In case of other stablecoins like USDC, USDT, BUSD are more capital efficient than DAI as it only requires $1 collateral to mint 1 stablecoin. But these types of stablecoins are <mark style="color:purple;">**centralized and controlled**</mark> by issuing companies such as Centre/Coinbase for USDC, Bitfinex/Tether (USDT) and Binance (BUSD). These companies <mark style="color:purple;">**can**</mark>**  **<mark style="color:purple;">**freeze your fund!**</mark>

****

The fully algorithmic stablecoin with rebase system, used by coins like Ampleforth and Based, is built on periodic expansions and contractions of the entire supply. The mechanism does not care about the history of rebases up to that point — if it has already rebased 10 times prior, it will add 5% of the current supply anyway. The process is reversed when the coin trades below $1.

The result is that the token’s supply can grow and shrink at a staggering pace, putting immense pressure on the nominal price. This supply change is distributed evenly between all wallets holding the token, meaning that a user’s total portfolio value does not change if the price shifts exactly by the percentage of new tokens minted. The fact that every single wallet follows the rebase means that the nominal price is just one small part of the picture.

Non-collateralized stablecoins require continual growth to be successful. In the event of a price crash, <mark style="color:purple;">**there is no collateral to liquidate the coin back into, and the holder’s money would be lost**</mark>, as seen with many past projects trying to utilize such design.

Gauging whether the coin is actually “stable” requires taking the supply changes into consideration as well, as every wallet is affected by them. When analyzing the total market capitalization to account for both supply and price, it becomes clear that this kind of stablecoin is <mark style="color:purple;">**extremely volatile.**</mark>

****
