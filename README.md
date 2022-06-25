# **Disclaimer**<br>
**Mr. Potato holds no responsible or reliable for any error or losses, if you persist on using this tool then you agree to hold full responsibility and liability for all consequences. If you are uncomfortable or disagree with any of the terms of this policy, please discontinue use of Potato Sniper Bot/Products.**

# **Warning**<br>
**⚠ Only use test wallet and never use main wallet ⚠**

# **Set Up**<br>

**Telegram Chat: https://t.me/PotatoSniperBot**<br>
**Dev-Telegram: @poormanmentality**<br>
**Dev-Discord: Anonymous101#5251**<br>

**Refer To PDF Manual**<br>

**IMPORTANT**<br>
Some Examples for dead block setup for those that doesn't understand comparison.<br>

**Example 1.**<br>
>uint launch_time = block.timestamp;<br>
>uint deadblock = 5;<br>
>if(block.timestamp <= launch_time + deadblock){<br>
>  blacklist[msg.sender] = true;<br>
>}<br>

**dead block set up will be 6.**<br>

**Example 2.**<br>
>uint launch_time = block.timestamp;<br>
>uint deadblock = 5;<br>
>if(block.timestamp < launch_time+deadblock){<br>
>  blacklist[msg.sender] = true;<br>
>}<br>

**dead block set up will be 5.**<br>

**Example 3.**<br>
>uint launch_time = block.timestamp;<br>
>uint deadblock = 5;<br>
>if( launch_time + deadblock > block.timestamp){<br>
>  blacklist[msg.sender] = true;<br>
>}<br>

**dead block set up will be 5.**<br>

**Example 4.**<br>
>uint launch_time = block.timestamp;<br>
>uint deadblock = 5;<br>
>if( launch_time + deadblock >= block.timestamp){<br>
>  blacklist[msg.sender] = true;<br>
>}<br>

**dead block set up  will be 6.**<br>


    
# **Supported Dex & Chains**<br>
**Mempool Snipe, Telegram Snipe, Presale Snipe, Limit-Trade, Monitor-Remove-LP** <br>
**-BSC [_PancakeSwap, ApeSwap, BabySwap, KnightSwap, MDEXSwap_]**<br>
**-ETH [UniSwapV2, SushiSwap, ShibaSwap]**<br>
**-Chronos [_MeerakatSwap_]**<br>
**-Polygon [_QuickSwap, PolycatSwap_]**<br>
**-Fanton [_SpookySwap, SpiritSwap_]**<br>
**-Avalanche [_TraderJoe, Pangolin_]**<br>
**-Metis  [_TethySwap_]**<br>
**-MILKOMEDA [_MilkySwap, OsccamxSwap, MuesliSwap_]**<br>


