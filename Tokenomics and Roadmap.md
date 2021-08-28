## Tokenomics

### How does the MASAMOON token smart contract transfer function work?
  
MASAMOON is a BEP-20 token on the Binance Smart Chain. It works like all other BEP-20 tokens, but also includes some additional features in its transfer function. These features are Reflection and Liquidity Pool (LP) Acquisition:

  - Reflection: Holders earn passive rewards through static reflection as their balance of MASAMOON grows.

  - Liquidity Pool (LP) Acquisition: A percentage of all transfer transactions is added to the PancakeSwap liquidity pool.
			
Every token transfer incurs a 10% fee.

### Fee breakdown

  - Reflection: 5% of the fee is distributed to all token holders in proportion to their token holdings. MASAMOON token balances have two different calculations: The first balance calculation is based on the traditional fixed number of tokens associated with a user’s address; The second balance calculation represents a user’s balance as a proportion of the total supply of the token:

	- This second calculation works similarly to how dynamic rebasing mechanisms work (example – Ampleforth token). When a taxed transaction occurs, the % re-distributed to token holders is deducted from the total “proportional” supply. As a result, the users' percentage of the total supply increases.

  - Liquidity Pool Acquisition: 5% of the fee is to provide liquidity on PancakeSwap. To keep the liquidity pool balanced, 2.5% is added to BNB token and 2.5% is added to MASAMOON token.

### Incentives

  - Reflection: Holding the token long-term will result in redistribution rewards automatically added to a holder's wallet.

  - LP acquisition: Selling results in a 10% transfer fee that helps support and stabilize the price of the token.

**IMPORTANT: Because of this special transaction function, it is recommended that traders set their slippage tolerance to 12%+ to prevent unnecessary loss.**
	
### 'SwapAndLiquify' function explained
	
  - After each transaction, a fee is charged and sent to the contract balance. When the contract balance reaches the 'numTokensSellToAddToLiquidity' amount, the following transaction will call the function 'SwapAndLiquify' which divides the contract balance in half; one part is swapped for WBNB and the second half remain in MASAMOON tokens. These two halves are then paired together and added to liquidity on PancakeSwap.

-----

## Roadmap

### PLANNING & DEVELOPMENT
- ~~Create token name~~
- ~~Create token logo~~
- ~~Create GitHub profile~~
- ~~Create diff of SafeMoon & MASA code~~
- ~~Write Solidity code (mirrored from SafeMoon with adjustments)~~
- ~~Create Discord server & configure~~
- ~~Create Telegram group (Admin: Katsuo クリエイター)~~
- ~~Create Twitter~~
- Create linktr.ee (update as needed)
- Advertising templates (w/link, w/o links, etc)

### PRE-LAUNCH
- ~~QA code~~
- ~~Deploy contract~~
- ~~Verify contract source code on BscScan~~
- ~~Send 5% to publicly announced developer wallet~~

### LAUNCH
- ~~Create WBNB-MASAMOON LP~~
- ~~Lock LP (Team.finance quote: 0.1 BNB)~~
- Renounce ownership (?)

### POST-LAUNCH
- Gather & distribute important links
- Create Medium profile
- Create Facebook page
- Create Instagram
- Create sub Reddit (?)
- Update website
- Domain email address
- TechRate quick audit
- PooCoin rug check
- Rugscreen check
- Submit BscScan info update request

### FUTURE
- CoinGecko listing
- CoinMarketCap listing
- CertiK or other audit (tentative)
- More...
