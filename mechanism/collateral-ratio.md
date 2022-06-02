# Collateral Ratio

BUCK Stablecoin uses two ratios to influence the collateral ratio.

### <mark style="color:purple;">Target Collateral Ratio (TCR)</mark> <a href="#target-collateral-ratio-tcr" id="target-collateral-ratio-tcr"></a>

TCR stands for Target Collateral Ratio which is the percentage of DAI collateral that the system targets. TCR is used by the minting function and it is displayed as a percentage. This ratio expresses what percentage of DAI token is required to mint BEVY token. TCR can increase or decrease every hour based on BUCK price:

If the time-weighted average price of BUCK token in the past hour is more than $1.00, then the protocol lowers the TCR. It can be lowered by 0.25% per hour.

If the time-weighted average price of BUCK token in the past hour is less than $1.00, then the protocol increases the TCR.

At the beginning, the lower bound of TCR will be set to be 100%. And after the price of BUCK is stabilized, the conditions for changing TCR can be changed.

Please note that these percentages can change in the future. The BUCK Stablecoin team is continuously focused on improving and optimizing the protocol stability.

### <mark style="color:purple;">**Effective Collateral Ratio (ECR)**</mark> <a href="#effective-collateral-ratio-ecr" id="effective-collateral-ratio-ecr"></a>

ECR stands for Effective Collateral Ratio and it is shown in percentage. This percentage expresses the amount of DAI token stored as collateral for the BUCK token.

If TCR is short is lower than ECR, then the protocol has excess collateral. TCR is usually lower than ECR when the demand for the BUCK token is high and the price stays above the ideal $1.00 peg. If the TCR is higher than the ECR, then the protocol has no excess collateral. TCR is usually higher than the ECR when the price of BUCK token stays around and below the ideal $1.00 peg for an extended period of time.
