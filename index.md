# Masamoon Token ($MASAMOON)

![MASAMOON Logo 400x400](https://user-images.githubusercontent.com/89506800/131245140-08e98430-870f-4e5d-855b-9fb46f6e6e2c.jpg)

## Basic Information

_Masamoon Token's name was inspired by Masamune (正宗), also known as Gorō Nyūdō Masamune (五郎入道正宗). He was widely recognized as Japan's greatest swordsmith; he created swords and daggers, known in Japanese as tachi and tantō respectively, in the Sōshū tradition. As no exact dates are known for Masamune's life, he has reached an almost legendary status._

- Name: Masamoon
- Symbol: MASAMOON
- Type: BSC/BEP-20
- Contract: [0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF](https://bscscan.com/address/0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF)
- Decimals: 18
- Total Supply: 10,000,000
- MaxTxAmount: 25,000 (0.25% of total)
- SwapAndLiquify Amount: 5,000 (0.05% of total)

500K tokens (5% of total supply) were [sent](https://bscscan.com/tx/0x2b96cf4c1f8fafbe13d863bed56e75fa75467030bf661dd91d8ae5aa51583f47) to the [developer wallet](https://bscscan.com/address/0x4daf1e9df7955699A5cB090aa3406Dd9D97b4720)*

**[Start trading on PancakeSwap!](https://pancakeswap.info/pool/0xf71f572a175a4efb5786f139a1d2e5bcb815779f)**

**[Step-by-step instructions for purchasing MASAMOON tokens](#step-by-step-instructions-for-purchasing-masamoon-tokens)**

**_MUST READ: The max transaction amount is 25,000 tokens! Anything more than that will fail. Also, set slippage to around 12%+ since there is a 10% wallet redistribution/liquidity fee!_**

-----

## Tokenomics

### How does the Masamoon token smart contract transfer function work?
  
MASAMOON is a BEP-20 token on the Binance Smart Chain. It works like all other BEP-20 tokens, but also includes some additional features in its transfer function. These features are Reflection and Liquidity Pool (LP) Acquisition:

  - Reflection: Holders earn passive rewards through static reflection as their balance of MASAMOON grows.

  - Liquidity Pool (LP) Acquisition: A percentage of all transfer transactions is added to the PancakeSwap liquidity pool.
			
**_Every token transfer incurs a 10% fee._**

### Fee breakdown

  - Reflection: 5% of the fee is distributed to all token holders in proportion to their token holdings. MASAMOON token balances have two different calculations: The first balance calculation is based on the traditional fixed number of tokens associated with a user’s address; The second balance calculation represents a user’s balance as a proportion of the total supply of the token:

	- This second calculation works similarly to how dynamic rebasing mechanisms work (example – Ampleforth token). When a taxed transaction occurs, the % re-distributed to token holders is deducted from the total “proportional” supply. As a result, the users' percentage of the total supply increases.

  - Liquidity Pool Acquisition: 5% of the fee is to provide liquidity on PancakeSwap. To keep the liquidity pool balanced, 2.5% is added to BNB token and 2.5% is added to MASAMOON token.

### Incentives

  - Reflection: Holding the token long-term will result in redistribution rewards automatically added to a holder's wallet.

  - LP acquisition: Selling results in a transfer fee that helps support and stabilize the price of the token.

_IMPORTANT: Because of this special transaction function, it is recommended that traders set their slippage tolerance to 12%+ to prevent unnecessary loss._
	
### 'SwapAndLiquify' function explained
	
  - After each transaction, a fee is charged and sent to the contract balance. When the contract balance reaches the 'numTokensSellToAddToLiquidity' amount, the following transaction will call the function 'SwapAndLiquify' which divides the contract balance in half; one part is swapped for WBNB and the second half remain in MASAMOON tokens. These two halves are then paired together and added to liquidity on PancakeSwap.

-----

## Step-by-step instructions for purchasing MASAMOON tokens

1. First, obtain some Binance Coin (BNB):
    
    _-Buy BNB directly from Binance here: https://www.binance.com/en/buy-sell-crypto_
    
    _-Or, purchase it from other centralized exchanges_
    
2. Download and install a MetaMask wallet on your computer or phone (and be sure to backup your password, private key(s) and secret recovery phrase): https://metamask.io:
    
    _-Also make sure you add and switch to the Binance Smart Chain (Mainnet) within your wallet. Review these instructions to learn how: https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain_
    
3. Go back to the site or app where you purchased BNB and send it to your MetaMask wallet address (it is located near the top and looks something like '0xC444...3CBA' ~ it is highly recommended that you copy and paste it directly, rather than inputting each character manually to avoid mistakes and financial loss)
4. Go to PancakeSwap: https://pancakeswap.finance/swap#/swap
5. Connect your MetaMask wallet
6. Your BNB balance should show up as the 'From' currency in their Exchange/Swap
7. Click 'Select a currency' in the 'To' box and input the MASAMOON contract address: **0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF**
8. Click 'MASAMOON' and verify it is the correct token
9. Input the amount of BNB you want to spend or tokens you would like to acquire (make sure you leave enough BNB in your wallet for tx/gas fees):

    _-Important: The max transaction amount is **25,000 MASAMOON**! Anything more than that will fail. Also, **set slippage to around 12%+** since there is a 10% wallet redistribution/liquidity fee!_

10. After purchasing MASAMOON, open your MetaMask wallet, make sure you are connected to the Binance Smart Chain network (drop down near the top right, next to your account icon), click the 'Assets' tab and then 'Add Token'
11. Copy and paste the MASAMOON contract address: **0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF**:

    _-The fields should self-populate_
    
12. After you have added MASAMOON to your wallet, you will be able to see the balance, as well as send and receive tokens:

    _-These instructions can be applied to any BEP-20, or even ERC-20, token_
    
    _-Remember, you can always see more detailed information about your wallet, and other wallets, on BscScan: https://bscscan.com_
    
-----

## Roadmap

**Planning & Development**
- ~~Create token name~~
- ~~Create token logo~~
- ~~Create GitHub profile~~
- ~~Write Solidity code (mirrored from SafeMoon with adjustments)~~
- ~~Create diff of SafeMoon & MASA code~~
- ~~Create Discord server & configure~~
- ~~Create Telegram group (Admin: Katsuo クリエイター)~~
- ~~Create Twitter~~
- ~~Advertising templates (w/link, w/o links, etc)~~

**Pre-Launch**
- ~~QA code~~
- ~~Deploy contract~~
- ~~Verify contract source code on BscScan~~
- ~~Send 5% to publicly announced developer wallet~~

**Launch**
- ~~Create WBNB-MASAMOON LP~~
- ~~Lock LP (Team.finance quote: 0.1 BNB)~~
- ~~Renounce ownership~~

**Post-Launch**
- ~~Gather & distribute important links~~
- Create Medium profile
- Create Facebook page
- Create Instagram
- Create sub Reddit (?)
- Update website
- Domain email address
- TechRate quick audit
- ~~PooCoin rug check~~
- ~~Rugscreen check~~
- Submit BscScan info update request

**Future**
- CoinGecko listing
- CoinMarketCap listing
- CertiK or other audit (tentative)
- More...

-----

## Building Trust - Audits, Checks, Scans & More

**Proof of LP lock through TrustSwap:**

[Team.finance link](https://team.finance/view-coin/0xEdefd156430a2c43dC9A4c6c2C31DB254DABf8AF?name=Masamoon&symbol=MASAMOON)

[BscScan transaction link](https://bscscan.com/tx/0xc61fe3ab4d1867be33b7d605b2e459154d28fb2064bfa5d65dade3df0e2bb424)

**Ownership Renounced:**

[BscScan transaction link](https://bscscan.com/tx/0x38a1bd54e3654996b0e56b49aa643a3dbccc8316919af757748c2c780233e41c)

[Transaction event log](https://bscscan.com/tx/0x38a1bd54e3654996b0e56b49aa643a3dbccc8316919af757748c2c780233e41c#eventlog)

**PooCoin Rug Check:**

[Link](https://poocoin.app/rugcheck/0xedefd156430a2c43dc9a4c6c2c31db254dabf8af/dev-activity)

**Token Sniffer:**

[Link](https://tokensniffer.com/token/0xedefd156430a2c43dc9a4c6c2c31db254dabf8af)

**Rugscreen:**

Coming soon!

**TechRate Quick Audit:**

Coming soon!

**CertiK Audit:**

Tentative.

-----

## Social Media

- [Telegram](https://t.me/masamoontkn)
- [Discord](https://discord.gg/g9nJtE3qae)
- [Twitter](https://twitter.com/masamoontkn)
- [Medium](https://tatsuhirodev.medium.com)
- [GitHub](https://github.com/katsuokurieita)
- Facebook (coming soon)
- Instagram (coming soon)

_*The owner(s) of the developer wallet have full discretion in deciding on how, where and when the allotted funds are spent._
