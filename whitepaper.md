# TNTOO Whitepaper

Fair, open, reserves can not be diverted transaction network.

Version 1.0


## Introduction

TNTOO named from Transaction Network, TNTOO transaction network access address is tntoo.com, Chinese name is "tantu".

The enthusiasm for probability has existed since ancient times, TNTOO can guarantee is fair and equitable, so that good money to expel bad money. The time has come to use blockchain TNTOO, not just people's Long-time idea. TNTOO Mall only circulation of the TOKEN, does not involve the legal tender, which also filters part of the irrational participants.

TNTOO released the corresponding transaction network smart contract and TNTOO TOKEN, at the same time have the mall applications. TNTOO contract code completely open, post trade, decision and other methods are pre-set by contract, can not be modified, anyone can verify.


## TOKEN

TNTOO is based on Ethereum ERC20 TOKEN, TNTOO as a unit. The TNTOO supply is designed to be dynamically related to the participating ETH. The initial TNTOO total supply is 0, and the contract owner and TNTOO team are no exception. The contract limits the TNTOO team to only benefit from the mall transaction fee.

TNTOO is the only credential to use TNTOO's trading network, TNTOO is used to buy goods and settlements on TNTOO's trading network. The reason why TNTOO is issued is to realize some special agreement with TNTOO contract. For example, the quota variable is introduced to limit the capacity of the contract owner, so that the contract owner can not withdraw ETH freely even if it can transfer TNTOO TOKEN, so as to ensure 100% preparation currency system implementation.

### Appreciation

TNTOO and ETH can be converted bidirectionally. When the contract is first released, the exchange relationship is 1ETH = 10000TNTOO. As the 1% of the transaction amount in each transaction is directly destroyed by the contract, it can be confirmed that the same amount of TNTOO must be able to receive more ETH in the future. The contract set to allow the ratio of TNTOO Redeem ETH to be updated every 15 days will be tried at each decision.

### Recharge

The purpose of recharge is to reduce the waste of processing fees for a large number of small transactions, to lower the threshold for participation and to increase participation. Transfer TNTOO or ETH to TNTOO mall application to increase the account balance used to purchase the item. Mall for each user provides a recharge unique address, used to determine the changes in funding for each user, applications will immediately turn to the TNTOO contract owner for unified management.

### Quota and withdraw

TNTOO can be extracted as the corresponding ETH only with the quota, according to the ratio of the extraction will convert ETH to the specified address. The only way to get a quota is to participate in the decision except the contract owner. The decision process is executed by the contract and can not be interfered by others.

When a user applies to withdraw ETH, the contract owner performs the method on behalf of the recipient, and subtracts the corresponding ETH withdraw quota from the withdraw address from the contract and transfer out. There is an assumption that if the owner of the contract uses TNTOO to go to an address and then purchases the goods at that address in full, he will be able to immediately have the outgoing ETH. However, the reality is that such behavior is abnormal and will be permanently recorded. Anyone can view TNTOO flow on the contract at any time and will be clearly identified anyway. The TNTOO team has promised that this will not happen at all, and the benefits of doing so are insignificant compared to TNTOO's reputation.

### Transfer

TNTOO is ERC20 TOKEN, user can use Ethereum wallet to transfer. If you compare TNTOO to shopping gold, you can either transfer assets through gift or over-the-counter transactions achieve circulation, but the transfer does not transfer the ETH withdrawal quota. TNTOO's biggest purpose is not to transfer, but rather appreciation design and trading settlement on the TNTOO transaction network to provide support.

## Transaction

### Post trade

Need to invoke the contract when the method of publishing goods information written to the chain in advance, including the price of goods, optional seller address, as the default value of the index. The preset value has a corresponding unique preset value, the original text is a string of 40 hexadecimal characters, and the string encrypted by sha256 is a preset value. The original text of the preset value will be disclosed after the decision. Since the preset value is set in advance, the participant can verify the correspondence between the preset value and the original text to prove the authenticity of the original text of the preset value.

### Purchase

Participate in the purchase need to use the account balance has been recharged, the mall application will record the participate in the purchase of goods. TNTOO contract according to the participation of participants of the corresponding probability, to determine which participants successfully obtained goods. The final decision will be made public at the mall, and the result is also publicly available on the chain and can not be modified.

### Decision

The first thing that needs to be explained is the parameters involved in the decision:
1. Each participating address is added and converted to a number as parameter 1.
2. TNTOO contract generated random number as parameter 2.
3. The original text of the trade released preset converted to a number as parameter 3.

Get the above three parameters and do the following steps:
1. Summation of the three parameters, taking the remainder of the product amount to obtain a decision result.
2. According to the number of TNTOO submissions, divide the interval, find the interval where the result of the decision is located, find out the corresponding address of the recipient and complete the decision process.

The reason why the above method of determining trustworthiness is because the three parameters mutually restraint. First of all, each person's participation affects the final decision, TNTOO team can not interfere. Second, since the contract code is public, it can be assumed that the node cheating can not benefit from the random value. Finally, the original text of the preset value controlled by TNTOO is not published before the decision, and can not be revised again when judging. It is almost impossible for the three parameters to be controlled at the same time. Therefore, the decision of TNTOO design can guarantee random and uncontrolled results.

### Settle

There are two ways to settle. One is the use of TNTOO direct settlement, the quota and TNTOO are directly transferred to buyer who obtain the decision good. The other is by TNTOO Mall save TNTOO, sellers in the decision phase to obtain the quota but without TNTOO, buyer click to confirm the receipt then TNTOO to the seller. TNTOO mall join in, transaction process can be longer period and more flexible.

## Income Distribution

The user gotten the trade decision will eventually receive 98% of the total amount. Aside them, 1% of the total amount of the transaction fee for the transaction, initially divided into three parts: inviting rebates, platform revenue, investors dividends. The other 1% of the TNTOO that determines the total amount will be directly destroyed, which will benefit every user who already has TNTOO.

### Window period and investment

TNTOO records window period within 180 days from the date of its release. During the window period, the first 5 wallet address trasfer to TNTOO contract not less than 500ETH will be entitled to a permanent 5% fee income share. Contract restrictions Investment quota can not be increased, beyond the limit number address can not be written into the contract investment address list. The contract will automatically read the list of investment addresses each time TNTOO charges a fee, and distributes the corresponding TNTOO amount and ETH withdrawal amount proportionately. Investment address owner simply invoke the contract on the extraction method, you can at any time transfer ETH to the wallet.


## Contract upgrade

TNTOO data storage and logic are in a smart contract, do not call any external contracts, which makes verification easier. Unfortunately, nothing can be eternal, TNTOO will make an announcement in advance when the old contract can not meet the update requirement or there are some unavoidable problems, so as to completely relocate the TNTOO contract's TOKEN balance and other data to the new Contract or TNTOO main blockchain. The whole process will not lose the interests of the holder, will not result in the loss of the user's assets.


## Conclusion

TNTOO contract through the above design, creating a win-win cooperation opportunities. With the development of TNTOO, the value of money holders and investors will increase, and TNTOO will get better and better with a substantial return. TNTOO will always be a value-based trading network, but also strive to contribute to the development of the blockchain ecosystem.

