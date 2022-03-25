# BSC-Mempool-Telegram-Sniper-Via-Solidity-Contract

Telegram: https://t.me/PotatoSniperBot
contact @poormanmentality for free trail.

**Mempool Mode (PCS/PINK-SALE/DX-SALE):**<br>	
	✔️ Anti Blacklist, Revert Transaction<br>
	✔️ Anti High Tax > = 58%, Revert Transaction<br>
	✔️ Buy From Dedicated Solidity Smart Contract<br>
  ✔️ PancakeSwap NON-BNB<br>
  ✔️ PancakeSwap BNB<br>
  ✔️ Pink-Sale<br>
  ✔️ Dx-Sale<br>
  ✔️ HoneyPot Checker<br>
  ✔️ Efficient Code<br>
  
**Do not turn off bot if first purchase transaction fails, it might be due to trading is disabled. The bot will continue to scan mempool for owner&contract interactions.**
  
Telegram Mode (LINK/ID):
  ✔️ Scrape Contract Address Only From Admin
  ✔️ Reconstruct To Valid Contract Address
  ✔️ Public & Private Group/Channel
  ✔️ Filter Greeting Messages
  ✔️ Buy From Dedicated Solidity Smart Contract
  ✔️ HoneyPot Checker
⚠️**Telegram ID mode should only be used in private groups. Make sure to only turn it on when the chat is muted, otherwise it will capture all messages from MEMBERS and ADMINS except for greeting messages.** ⚠️
  
  
**Config.json File Setup:**

⚠️⚠️⚠️⚠️ **DO NOT CHANGE NAME OF PARAMETERS** ⚠️⚠️⚠️⚠️

  apiID:   Get your telegram api id at https://my.telegram.org/auth
  
  apiHash: Get your telegram api hash at https://my.telegram.org/auth
  
  my_contract:  Buy Contract Address Here After You Deploy It From Contract Deployer.exe
  
  hp_contract:  HoneyPot Contract Address Here After You Deploy It From Contract Deployer.exe
  
  contract_owner_addr: Wallet Address You Want To Deploy The Contracts
  
  contract_owner_key:  Secret Key Of Wallet Address You Used To Deploy The Contracts 
  sell_account_addr:   Wallet Address You Want To Use For Selling 
  sell_account_key:    Secret Key Of Wallet Address You Want To Use For Selling 

  "url": " BSC ENDPOINT HERE HTTP or WS (WS is better for mempool) ",

  "auto_sell": false,      
  "auto_sell_interval": "3",
  "auto_sell_amount": "25",
  "auto_sell_all_target": "15",

  "Telegram_Honeypot": true,
  "target_buytax": "25",
  "target_selltax": "35",

  "buy_amount": "0.01",
  "test_buy_amount":"0.001",
  "buy_delay_timer": null,
  "gas": "7",
  "gaslimit": "2000000",
  "intermediate_token": null,
  "sell_slippage":"35",

  "target_owner": "",
  "router":"0x10ED43C718714eb63d5aA57B78B54704E256024E",
  "factory":"0xcA143Ce32Fe78f1f7019d7d551a6402fC5350c73",
  "bnb_busd_pair":"0x58F876857a02D6762E0101bb5C46A8c1ED44Dc16",
  "wbnb":"0xbb4CdB9CBd36B01bD1cBaEBF2De08d9173bc095c",
  "busd":"0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56",
  "usdt":"0x55d398326f99059fF775485246999027B3197955",
  "usdc":"0x8AC76a51cc950d9822D68b83fE1Ad97B32Cd580d"


}




