# polkazeck_erc20_contract

The total supply of token is 162 million. No mint functions are present.

Upon deployment, the team receives 76.95 million tokens. The remaining 85.05 million tokens are locked in the contract and will be released to the team over time.

The team is able to claim 25% of an additional 32.4 million tokens for the purpose of marketing every 3 months.

The team is able to claim 25% of an additional 16.2 million tokens for the purpose of team rewards every 2 years.

The team is able to claim an additional 8.1 million tokens for the purpose of team reserves after 1 year.

The team is able to claim an additional 28.35 million tokens for the purpose of funding the 'ecosystem' after 1 year.

There is a fee incurred upon transfers of the token. Part of this transfer fee is redistributed to existing token holders instantly and automatically at the time of each transaction; while the other part is burned to reduce the total supply.
The team can set the tax and burn rates to any amount at any time. We recommend limiting what these rates can be set to via a require() statement.
The owner also has the ability to include and exclude accounts from transfer fees.

The contract uses SafeMath libraries along with following the ERC20 standard.
Public functions may be declared external to save a small amount of gas on each transaction. In addition, the team can set the beneficiary claimInterval and claimPercent variables as constant.

######Audit report link
###### Audit report link
https://solidity.finance/audits/Polkazeck/
