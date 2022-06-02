---
description: Simple Collateral+Algorithmic Stablecoin on Arbitrum
---

# BUCK Stablecoin

## <mark style="color:purple;">**What is BUCK?**</mark>

<mark style="color:purple;"></mark>[<mark style="color:purple;">**BUCK**</mark>](https://app.sushi.com/) <mark style="color:purple;"></mark> <mark style="color:purple;"></mark><mark style="color:purple;">**is a partial-collateralized and algorithmic stablecoin with stability mechanism and soft pegged to the U.S. Dollar.**</mark>

BUCK employs a partial-collateralized model, which means part of BUCK supply is backed by DAI collateral (DAI is more decentralized compared to USDC / USDT) and another part of the supply is algorithmically controlled by using BEVY token. This makes BUCK capital efficient (no over-collateralization), truly stable, and fully decentralized.

BUCK protocol is a two token system: BUCK stablecoin and the governance token BEVY. The Stablecoin design is based on Frax and we built the Buck protocol by increasing the speed and efficiency of gas without compromising the security and stability of the Ethereum blockchain. We therefore chose to run the new layer 2 technology; <mark style="color:purple;">**ARBITRUM.**</mark>

As one of our mission to broaden the visibility of BUCKnBEVY and for wider adoption by various blockchain use cases, we decided to go multi-chain.\
The other chains we chose are:

**1. Ethereum for**\
👍 best security\
👍 most erc-20 wallet support\
👍 most cex/dex support (easiest liquidity for hodlers)

**2. Polygon/Matic Network for**\
👍 lower fees and faster execution\
👍 most defi app partners from various use cases\
👍 support from the largest NFT marketplace; **OpenSea**\
👍 have plans to use ethereum security via Hermes L2

Once it ready, your BUCK n BEVY tokens will be bridge-able between three chains: Arbitrum-Ethereum-Polygon

## <mark style="color:purple;">BUCK Features</mark>

#### <mark style="color:purple;">1. Dynamic collateral ratio based on BUCK market price</mark> <a href="#192d" id="192d"></a>

The collateral and algorithmic ratios depend on the market price of the BUCK stablecoin. If the BUCK trades above $1, the protocol lowers the collateral ratio. If the BUCK trades below $1, the protocol increases the collateral ratio.

The collateral is used for redemption, helping to maintain price stability. The collateral ratio starts at 100% which means that the user must enter 100% of the DAI as collateral which is equivalent to the amount of BUCK they wish to mint. This collateral ratio will be updated hourly in 0.25% steps.

Users mint BUCK by transferring DAI and BEVY to a time-locked smartcontract as collateral pool, where the ratio between the DAI and BUCK is determined by the current Target Collateral Ratio (TCR)\
_e.g. if current TCR is 85% then to mint 1000 BUCK, user has to put $850 worth of DAI and $150 worth of BEVY into the collateral pool, BEVY is burned during the minting process._

Users can also withdraw their DAI and BEVY by burning BUCK and get their DAI and BEVY back.

#### <mark style="color:purple;">2. High Speed & Low Gas Fee with Layer 2 Technology</mark> <a href="#0e60" id="0e60"></a>

All transactions are carried out on Arbitrum Layer 2 Technology with high speed execution and lower gas fees. Unlike other Ethereum Virtual Machine (EVM) based protocols such as Binance Smart Chain, Polygon, Fantom and xDai, Arbitrum as Layer 2 still relies on its Layer 1 Security (Ethereum).&#x20;

#### <mark style="color:purple;">3. BEVY Minter (Re-collateralize)</mark> <a href="#7ebb" id="7ebb"></a>

BEVY is the governance token which accrues fees, seigniorage revenue and excess collateral value. Users can mint BEVY by adding DAI (only) into the collateral pool and get additional 1% BEVY as minting bonus.

Attractive bonus is applied to get more DAI added to the collateral pool. This supply of DAI is very important to facilitate redemption and helping to maintain price stability.&#x20;

#### <mark style="color:purple;">4. Automated Collateral Treasury</mark> <a href="#7ebb" id="7ebb"></a>

Buck protocol can handle excess and deficit of DAI collateral automatically, without users intervention.&#x20;

When the Effective Collateral Ratio (ECR) is <mark style="color:purple;">**above**</mark> the Target Collateral Ratio (TCR), the excess DAI will be transferred from collateral pool to another smartcontract as treasury.&#x20;

When the ECR is <mark style="color:purple;">**below**</mark> the TCR, DAI from treasury will be added automatically to collateral pool, without user intervention.

#### <mark style="color:purple;">5.</mark> <mark style="color:purple;"></mark><mark style="color:purple;">**Crash Resistance**</mark> <a href="#68ed" id="68ed"></a>

Learning from the mistakes of other stablecoins, BUCK has several features and strategies to avoid bank-run. The most important features for dealing with this are:

<mark style="color:purple;">Rapid Oracle Switch</mark> and Liquidity Mining V.2 or also known as <mark style="color:purple;">Options Liquidity Mining (OLM)</mark>.&#x20;

[_(click here for more information)_](background/crash-resistance.md)__

#### <mark style="color:purple;">6. DAI (Only) Collateral Pool</mark> <a href="#68ed" id="68ed"></a>

For simplicity and ensuring decentralization, BUCK only uses DAI as collateral. DAI is a self-sovereign money generation of stablecoin with complete financial independence.

The collateral pool is the heart of the fractional protocol, therefore BUCK ensures that it is completely decentralized and cannot be frozen by anyone, anytime and for any reason.

<mark style="color:purple;">****</mark>

<mark style="color:purple;">**7. Personalized Farming Bonus Multiplier**</mark>

Buck combines DeFi and NFT in a very innovative way. Our community will be able to mint BuckLoot NFT for free. Inspired by Loot NFT Project, BuckLoot is randomized hunting gear items generated on-chain. Each BuckLoot 'bag' contains three items. During certain promo periods, there will be a BuckLoot Challenge where we display single hunting gear item as keyword on our website. BuckLoot holders who have the keyword item in their bags will get Special Multiplier for BEVY Farming Bonus and earn higher yield in return.&#x20;

<mark style="color:purple;">****</mark>

<mark style="color:purple;">**8. Single-sided exposure**</mark>

BUCK allows users to mint BUCK using only DAI or only BEVY. The system will automatically swap half of the given token to its pairing token then trigger the minting of BUCK.

<mark style="color:purple;">****</mark>

<mark style="color:purple;">**9. Enhanced User Experience**</mark> <mark style="color:purple;"></mark><mark style="color:purple;"></mark>&#x20;

BUCK improves the User Experience to be simpler and more user friendly. We avoid overly technical terminology and UI components in order to make it easier for users to operate the protocol.

## <mark style="color:purple;">Future Plan</mark> <a href="#965e" id="965e"></a>

To increase the use of BUCK by fostering its adoption in the DeFi ecosystem, the team will <mark style="color:purple;">**collaborate with dApp projects**</mark> that require cross-border payments in their applications.

When the protocol is stable enough, we will give <mark style="color:purple;">**control to community members**</mark> so that they can govern through voting mechanisms.

