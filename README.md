# Mempool & Telegram Sniper<br>
**Demo : https://www.youtube.com/watch?v=3t74O6JmtNI**<br>
**Telegram: https://t.me/PotatoSniperBot**<br>
**Discord:** **https://discord.gg/nrghTp9H5p**<br>
**contact @poormanmentality on telegram or @Anonymous101#5251 on discord for free trail**<br>

**BSC DEX:** _**[PancakeSwap, ApeSwap, BabySwap, KnightSwap, MDEXSwap]**_<br>

**ContractDeployer.exe**<br>
![image](https://user-images.githubusercontent.com/102332910/160053710-00143c1a-40ae-4afd-a987-7bb0c1ff1a85.png)<br>

**PotatoBot.exe**<br>
![image](https://user-images.githubusercontent.com/102332910/160316993-7e568d63-b50d-4a61-a557-7201ccb4b743.png)


**Mempool Mode (_PCS/PINK-SALE/DX-SALE_):**<br>	
  ✔️ Anti Blacklist, Revert Transaction<br>
  ✔️ Anti High Tax > = 58%, Revert Transaction<br>
  ✔️ Buy From Solidity Smart Contract<br>
  ✔️ Multi-Buy within one transaction<br>
  ✔️ PancakeSwap NON-BNB<br>
  ✔️ PancakeSwap BNB<br>
  ✔️ Pink-Sale<br>
  ✔️ Dx-Sale<br>
  ✔️ Auto Sell<br>
  ✔️ Manual Sell<br>
  
**Telegram Mode (_LINK/ID_):**<br>
  ✔️ Scrape Contract Address Only From Admin<br>
  ✔️ Reconstruct To Valid Contract Address<br>
  ✔️ Public & Private Group/Channel<br>
  ✔️ Filter Greeting Messages<br>
  ✔️ Buy From Solidity Smart Contract<br>
  ✔️ HoneyPot Checker For buy/sell tax<br>
  ✔️ Auto Sell<br>
  ✔️ Manual Sell<br>
  
⚠️**Telegram ID mode should only be used in private groups. Make sure to only turn it on when the chat is muted, otherwise it will capture all messages from MEMBERS and ADMINS with the exception of greeting messages.** ⚠️<br>
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
  
   **buy_count**: How many time to buy within one transaction 
  
  **test_buy_amount**: Amount Of BNB To Buy, Sample Buy
  
  **buy_delay_timer**: Buy Delay, If not using leave it as **null**
  
  **gas**: gas
  
  **gaslimit**: maximum gaslimit
  
  **intermediate_token**: Only applies to telegram mode, if target token is paired with non-bnb. For example safemoon-busd, you would enter busd address here.
  
  **sell_slippage**: Sell slippage

  **target_owner**: Leave It as is, bot will automatically fetch this. If bot failed to fetch owner address then you need to manually enter it here. Only For Mempool Mode.
  





