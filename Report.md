# ASSIGNMENT15--10-16
# MODULE 21 - Martian Token Crowdsale

![alt=""](Images/application-image.png)


# Challenge_21 Report
## Analysis Overview:
Our objective in this analysis is to design and execute a cryptocurrency project called KaseiCoin, along with launching a crowdsale for prospective Mars settlers who wish to exchange their Earth currency for KaseiCoin. The entire project is coded in Solidity and leverages OpenZeppelin libraries to facilitate ERC-20 token creation and crowdsale operations.

### Methods Employed and Supporting Evidence:

### KaseiCoin Contract:
The KaseiCoin contract is meticulously crafted, inheriting crucial functionality from OpenZeppelin's ERC20, ERC20Detailed, and ERC20Mintable contracts. These foundation contracts lay the groundwork for establishing an ERC-20 compliant token. The constructor is responsible for initializing the token's particulars. Below is a snapshot demonstrating the successful compilation of the KaseiCoin contract:
![KaseiCoin contract](https://github.com/Narimanhx/ASSIGNMENT15--10-16/assets/132794052/1e93e2f8-d607-4fca-ae6f-14ffabdd9e41)

### KaseiCoinCrowdsale Contract:
The KaseiCoinCrowdsale contract, an offspring of OpenZeppelin's Crowdsale and MintedCrowdsale, manages the sale of KaseiCoin during the crowdsale phase. It plays a pivotal role in the distribution of tokens. The screenshot below confirms the successful compilation of the KaseiCoinCrowdsale contract:
![KaseiCoinCrowdsale](https://github.com/Narimanhx/ASSIGNMENT15--10-16/assets/132794052/e5780acb-76a8-450f-95f9-46ac4242b437)

### KaseiCoinCrowdsaleDeployer Contract:
The KaseiCoinCrowdsaleDeployer contract is the deployment mastermind behind both the KaseiCoin and KaseiCoinCrowdsale contracts. This contract orchestrates the instantiation of the token and crowdsale, binds them together, and mints tokens for the crowdsale. Importantly, it relinquishes its minter role to safeguard the integrity of the token. The screenshot below validates the successful compilation of the KaseiCoinCrowdsaleDeployer contract:
![KaseiCoinCrowdsaleDeployer](https://github.com/Narimanhx/ASSIGNMENT15--10-16/assets/132794052/9f7a18ee-eb0c-480f-9787-76910f21f00d)

### KaseiCoin Contract Demo
To demonstrate the functionality of the KaseiCoin contract, you can refer to the following link:

https://github.com/Narimanhx/ASSIGNMENT15--10-16/assets/132794052/051f8c9e-96ab-4308-ba15-25a2f4cb1bb5


### Summary:
This project establishes the groundwork for creating KaseiCoin, a cryptocurrency, and facilitating its distribution via a crowdsale. Utilizing OpenZeppelin libraries ensures that KaseiCoin adheres to the ERC-20 standard and that the crowdsale functions smoothly. The process involves the initial setup of the token and crowdsale contracts, as well as the deployment of these contracts. The smart contracts also handle the minter role for the crowdsale, ultimately securing the token's integrity.
