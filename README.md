# solidity_homework

## Please refer to `My_AssociateProfitSplitter.sol` , `My_TieredProfitSplitter.sol` and `My_DeferredEquityPlan.sol` solidity files for my homework submission. 
#

# Background
Our new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic.

These contracts will do several things:

* Pay our associate-level employees quickly and easily using `My_AssociateProfitSplitter.sol`

* Distribute profits to different tiers of employees using `My_TieredProfitSplitter.sol`

* Distribute company shares for employees in a "deferred equity incentive plan" automatically using `My_DeferredEquityPlan.sol`

More explanations and instructions below:
* **The `My_AssociateProfitSplitter` contract** that will accept ether into the contract, and divide it evenly among associate-level employees. This will allow the human resources department to pay employees quickly and efficiently.

* **The `My_TieredProfitSplitter` contract** that will distribute different percentages of incoming ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* **The `My_DeferredEquityPlan` contract** that models traditional company stock plans. This contract will automatically manage 1000 shares, with an annual distribution of 250 shares over four years for a single employee.