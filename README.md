# KaseiCoin

The crowdsale contract that you create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. Your contract will mint the tokens automatically and distribute them to buyers in one transaction.
</br></br></br>

**Complier using 0.5.5+

**KaseCoin complier

![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/KaseiCoin.png)

**KaseiCoinCrowdsale complier

![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/KaseiCoinCrowdsale.png)

**KaseiCoinCrowdsaleDeployer complier

![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/KaseiCoinCrowdsaleDeployer.png)

**User Guide
1.	link Ganache, Metamask, and Remix.
</br></br>
2.
	- Choose "KaseiCoinCrowdsaleDeplayer - KaseiCoinCrowdsale.sol" in CONTRACT.
	- Type in Name, symbol, and wallet. Wallet would be the address type.
	- Click transact and Metamast would pop-up the confirmation of contract, and click confirm.

![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/KaseiCoinCrowdsaleDeployer_transact.png)
</br></br>

3.	Call kasei_token_address and kasei_crowdsale_address, and copy kasei_token_address result.

![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/KaseiCoinCrowdsaleDeployer_address.png)
</br></br>

4.	
	- Change CONTRACT to "KaseiCoinCrowdsale - KaseiCoinCrowdsale.sol".
	- Fill kasei_token_address to "At Address" blank, and click "At Address".
	- System would deploy Kaseicoincrowdsale in "Deployed Contracts".

![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/AtAddress.png)
</br></br>

5.	
	- Call all function rate, token, wallet, weiRaised, and check if the info is correct.
	- Fill in the amount of Ether or wei for transfer.
	- Fill the beneficiary into buyToken blank, and click "buyTokens".
	- The Metamask confirmation would pop-up and click confirm.
![alt text](https://github.com/wf880180/KaseiCoin/blob/main/Evaluation_Evidence/BuyToken_confirm.png)

</br></br>
