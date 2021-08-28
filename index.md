# Masamoon Token ($MASAMOON)

![Masamoon Logo 400x400](https://user-images.githubusercontent.com/89506800/131190389-38929928-2ea9-45dc-b669-12c40ec18eb4.jpg)

## Basic information

_Masamoon Token's name was inspired by Masamune (正宗), also known as Gorō Nyūdō Masamune (五郎入道正宗). He was widely recognized as Japan's greatest swordsmith; he created swords and daggers, known in Japanese as tachi and tantō respectively, in the Sōshū tradition. As no exact dates are known for Masamune's life, he has reached an almost legendary status._

- Name: Masamoon
- Symbol: MASAMOON
- Type: BSC/BEP-20
- Contract: [0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF](https://bscscan.com/address/0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF)
- Decimals: 18
- Total Supply: 10,000,000
- MaxTxAmount: 25,000 (0.25% of total)
- SwapAndLiquify Amount: 5,000 (0.05% of total)

500K tokens (5%) were sent to the developer wallet*: [0x4daf1e9df7955699A5cB090aa3406Dd9D97b4720](https://bscscan.com/address/0x4daf1e9df7955699A5cB090aa3406Dd9D97b4720)

**[Start trading now!](https://pancakeswap.finance/swap)**

**[Step-by-step Instructions for Purchasing MASAMOON Tokens](https://github.com/katsuokurieita/Masamoon/blob/main/README.md)**

## Tokenomics

### How does the MASAMOON token smart contract transfer function work?
  
MASAMOON is a BEP-20 token on the Binance Smart Chain. It works like all other BEP-20 tokens, but also includes some additional features in its transfer function. These features are Reflection and Liquidity Pool (LP) Acquisition:

  - Reflection: Holders earn passive rewards through static reflection as their balance of MASAMOON grows.

  - Liquidity Pool (LP) Acquisition: A percentage of all transfer transactions is added to the PancakeSwap liquidity pool.
			
**Every token transfer incurs a 10% fee.**

### Fee breakdown

  - Reflection: 5% of the fee is distributed to all token holders in proportion to their token holdings. MASAMOON token balances have two different calculations: The first balance calculation is based on the traditional fixed number of tokens associated with a user’s address; The second balance calculation represents a user’s balance as a proportion of the total supply of the token:

	- This second calculation works similarly to how dynamic rebasing mechanisms work (example – Ampleforth token). When a taxed transaction occurs, the % re-distributed to token holders is deducted from the total “proportional” supply. As a result, the users' percentage of the total supply increases.

  - Liquidity Pool Acquisition: 5% of the fee is to provide liquidity on PancakeSwap. To keep the liquidity pool balanced, 2.5% is added to BNB token and 2.5% is added to MASAMOON token.

### Incentives

  - Reflection: Holding the token long-term will result in redistribution awards automatically added to a holder's wallet.

  - LP acquisition: Selling results in a 10% transfer fee that helps support and stabilize the price of the token.

**IMPORTANT: Because of this special transaction function, it is recommended that traders set their slippage tolerance to 12%+ to prevent unnecessary loss.**
	
### 'SwapAndLiquify' function explained
	
  - After each transaction, a fee is charged and sent to the contract balance. When the contract balance reaches the 'numTokensSellToAddToLiquidity' amount, the following transaction will call the function 'SwapAndLiquify' which divides the contract balance in half; one part is swapped for WBNB and the second half remain in MASAMOON tokens. These two halves are then paired together and added to liquidity on PancakeSwap.

*The owner(s) of the developer wallet have full discretion in deciding on how, where and when the allotted funds are spent.
