# BUCK Minting and Burning

### <mark style="color:purple;">Minting</mark>

In order to mint 1 BUCK, the system requires TCR worth of DAI and (1 - TCR) worth of BEVY. DAI will be added to Collateral Pool and BEVY will be burned.

`ex) When TCR = 80%, 100 BUCK can be minted with $80 worth of DAI and $20 worth of BEVY`

### <mark style="color:purple;">Burning</mark>

When 1 BUCK is sent to protocol for burning, the system returns ECR worth of DAI and (1 - ECR) worth of BEVY.

`ex) When ECR = 75%, if 100 BUCK is redeemed, the system returns $75 worth of DAI and $25 worth of BEVY`

### <mark style="color:purple;">Zero Fee!</mark>

There are no fees charged for minting and burning, users only need to pay arbitrum gas fees which are very cheap compared to ethereum gas fees.
