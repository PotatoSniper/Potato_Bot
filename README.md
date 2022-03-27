# BSC-Mempool-Telegram-Sniper-Via-Solidity-Contract
**Demo : https://www.youtube.com/watch?v=3t74O6JmtNI&t=24s**
**Telegram: https://t.me/PotatoSniperBot**<br>
**Discord:** **https://discord.gg/nrghTp9H5p**<br>
**contact @poormanmentality on telegram or @Anonymous101#5251 on discord for free trail**<br>

_**PancakeSwap, ApeSwap, BabySwap, KnightSwap, MDEXSwap**_

**ContractDeployer.exe**<br>
![image](https://user-images.githubusercontent.com/102332910/160053710-00143c1a-40ae-4afd-a987-7bb0c1ff1a85.png)<br>

**PotatoBot.exe**<br>
![image](https://user-images.githubusercontent.com/102332910/160054132-b3eb1914-78a5-4e6b-a54e-f38805be28ec.png)

**YOU WILL NEED TO TRANSFER BNB TO YOUR BUY CONTRACT INORDER TO BUY, ONLY SEND A SMALL AMOUNT AND TEST WITHDRAW FUNCTION TO ENSURE YOU CAN WITHDRAW. ALL CONTRACTS DEPLOYED ARE DEDICATED CONTRACT, MEANING ONLY CONTRACT OWNER CAN INTERACT WITH IT**


**Mempool Mode (_PCS/PINK-SALE/DX-SALE_):**<br>	
  ✔️ Anti Blacklist, Revert Transaction<br>
  ✔️ Anti High Tax > = 58%, Revert Transaction<br>
  ✔️ Buy From Dedicated Solidity Smart Contract<br>
  ✔️ PancakeSwap NON-BNB<br>
  ✔️ PancakeSwap BNB<br>
  ✔️ Pink-Sale<br>
  ✔️ Dx-Sale<br>
  ✔️ Efficient Code<br>
  
**⚠️Warning: Do not turn off bot if first purchase transaction fails, it might be due to trading is disabled. The bot will continue to scan mempool for owner&contract interactions.⚠️**<br>
  <br>
  <br>
**Telegram Mode (_LINK/ID_):**<br>
  ✔️ Scrape Contract Address Only From Admin<br>
  ✔️ Reconstruct To Valid Contract Address<br>
  ✔️ Public & Private Group/Channel<br>
  ✔️ Filter Greeting Messages<br>
  ✔️ Buy From Dedicated Solidity Smart Contract<br>
  ✔️ HoneyPot Checker<br>
  
⚠️**Telegram ID mode should only be used in private groups. Make sure to only turn it on when the chat is muted, otherwise it will capture all messages from MEMBERS and ADMINS except greeting messages.** ⚠️<br>
  <br>
  <br>
**Config.json File Setup:** <br>
**⚠️ Do Not Change Parameter Name⚠️** 

  **apiID**:   Get your telegram api id at https://my.telegram.org/auth
  
  **apiHash**: Get your telegram api hash at https://my.telegram.org/auth
  
  **my_contract**:  Buy Contract Address Here After You Deploy It From Contract Deployer.exe
  
  **hp_contract**:  HoneyPot Contract Address Here After You Deploy It From Contract Deployer.exe
  
  **contract_owner_addr**: Wallet Address You Want To Deploy The Contracts
  
  **contract_owner_key**:  Secret Key Of Wallet Address You Used To Deploy The Contracts 
  
  **sell_account_addr**:   Wallet Address You Want To Use For Selling 
  
  **sell_account_key**:    Secret Key Of Wallet Address You Want To Use For Selling 
  
  **url**: " BSC EndPoint Here HTTP/WSS (WS/WSS is better for mempool) "
  
  **reconnect**: **true/false**, only use it when your endpoint have timeout configured

  **auto_sell**: Put **true**/**false** Here
  
  **auto_sell_interval**: Sell interval at every x pure profit. PureProfit = CurrentBalance - InvestmentAmount.
  
  **auto_sell_amount**: Sell x % at every sell interval.
  
  **auto_sell_all_target**: Sell all balance at x pure profit.

  **Telegram_Honeypot**: Enable honeypot checking **true**/**false**, only applies for telegram mode
  
  **target_buytax**: Buy Tax, Only Buy If Tax is <= x, only applies for telegram mode
  
  **target_selltax**: Sell Tax, Only Buy If Tax is <= x, only applies for telegram mode

  **buy_amount**: Amount Of BNB To Buy, Actual Buy
  
  **test_buy_amount**: Amount Of BNB To Buy, Sample Buy
  
  **buy_delay_timer**: Buy Delay, If not using leave it as **null**
  
  **gas**: gas
  
  **gaslimit**: maximum gaslimit
  
  **intermediate_token**: Only applies to telegram mode, if target token is paired with non-bnb. For example safemoon-busd, you would enter busd address here.
  
  **sell_slippage**: Sell slippage

  **target_owner**: Leave It as is, bot will automatically fetch this. If bot failed to fetch owner address then you need to manually enter it here. Only For Mempool Mode.
  





