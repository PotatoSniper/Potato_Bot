# Mempool & Telegram Sniper<br>
**Demo : https://www.youtube.com/watch?v=3t74O6JmtNI**<br>
**Telegram: https://t.me/PotatoSniperBot**<br>
**Discord:** **https://discord.gg/nrghTp9H5p**<br>

**COMING SOON: ETH**<br>

**BSC DEX:** _**[PancakeSwap, ApeSwap, BabySwap, KnightSwap, MDEXSwap]**_<br>
**CRONOS DEX:** _**[MeerkatSwap]**_<br>

**Mempool Mode**<br>	
&nbsp;&nbsp; &nbsp;✔️ Detect Blacklist and High Tax > Revert Transaction<br>
&nbsp;&nbsp; &nbsp;✔️ Buy From Solidity Smart Contract<br>
&nbsp;&nbsp; &nbsp;✔️ Multi-Buy within one transaction<br>
&nbsp;&nbsp; &nbsp;✔️ Auto Sell<br>
&nbsp;&nbsp; &nbsp;✔️ Manual Sell<br>
  
**Telegram Mode**<br>
&nbsp;&nbsp; &nbsp;✔️ Scrape Contract Address From Only Admin<br>
&nbsp;&nbsp; &nbsp;✔️ Attempt To Reconstruct To Valid Contract Address<br>
&nbsp;&nbsp; &nbsp;✔️ Public & Private Group/Channel<br>
&nbsp;&nbsp; &nbsp;✔️ Filter Greeting Messages<br>
&nbsp;&nbsp; &nbsp;✔️ Buy From Solidity Smart Contract<br>
&nbsp;&nbsp; &nbsp;✔️ HoneyPot Checker For buy tax/sell tax/tradeable/sellable<br>
&nbsp;&nbsp; &nbsp;✔️ Auto Sell<br>
&nbsp;&nbsp; &nbsp;✔️ Manual Sell<br>
  
  <br>
  <br>
  
&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;**⚠️ Do Not Change Parameter Name⚠️** <br>
****Config.json File Setup:**** <br>

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
  





