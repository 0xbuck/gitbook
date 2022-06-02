# BEVY Minting

Anyone can call the Mint BEVY function which then checks if the ECR is below the current TCR. If it is, then the system allows the caller to add up to the amount needed to reach the TCR in exchange for newly minted BEVY at a bonus rate. The bonus rate is set to `1%` to quickly incentivize arbitragers to close the gap and recollateralize the protocol to the target ratio. The bonus rate can be adjusted or changed through governance. 10% of bonus rate (0.1%) will be sent to BUCK Team's time-locked address for platform sustainability.

#### <mark style="color:purple;">**Example**</mark>

There is 100,000,000 BUCK in circulation at a 80% ECR. The total value of collateral across the DAI pools is 80m USD and the system is balanced. (TCR＝ECR) The price of BUCK drops to $.99 and the protocol increases TCR to 80.25%.

There is now `$250,000` worth of collateral needed to reach TCR. Anyone can call the Mint BEVY function and place up to `$250,000` of collateral into pools to receive an equal value of BEVY plus a bonus rate of `0.9`% (0.1% goes to Team's  time-locked address).
