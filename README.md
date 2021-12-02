# BOTDEXDAMAR
combination botsniper and botexploit\
botsniper = buy tokens if tokens already have liquidity or activate swap quickly.\
botexploit = it's so hard to explain but the features in this are frontrun, backrun, arbitrange.\
all botdexdamar features require 1 target token to execute.

# changelog to V8.1.0
1. remove open source :(
2. compile the script to execute so that it is easy and has minimal bugs 
3. added a minimum target amount, delay feature in the sandwich feature 
4. added autoTradeSellToken feature in firstlaunchbuy features 
5. fix bug and tune up performance 
6. etc...

# features sniper
for more details, please check the config/config.js file
```
(SNIPER) all process using SCRIPT
(SNIPER) custom node url.
(SNIPER) custom gwei, gaslimit, slippage.
(SNIPER) auto detect liquidity or enable swap.
(SWAP) anti honeypot.
(SWAP) auto takeprofit and cutlose on autotrade sell token.
(SWAP) swap token with delay / timeout.
(SWAP) spam buy before or after launch with targetBulk. this process using SCRIPT for process send bulk transaction with different blockNumber.
(PRESALE) auto detect unlock presale.
(PRESALE) spam tx before launch presale with targetBulk. this process using SCRIPT for process send bulk transaction with different blockNumber.
```

# features exploit
for more details, please check the config/config.js file
```
(EXPLOIT) custom node url.
(EXPLOIT) custom gwei, gaslimit, slippage.
(EXPLOIT) free mempool premium for filter transaction.
(FIRSTLAUNCHBUY) swap token with in the same blockNumber along with addLiquidity method or enable swap. this process using SCRIPT or CUSTOM ROUTER.
(FIRSTLAUNCHBUY) swap token with custom router. this process using CUSTOM ROUTER for all process bot exploit.
(FIRSTLAUNCHBUY) swap token with custom router and chi gas token for reduce transaction fees. this process using CUSTOM ROUTER for process reduce transaction fees.
(FIRSTLAUNCHBUY) swap token with bulk transactions using custom router. this process using CUSTOM ROUTER for process send bulk transaction with same blockNumber.
(FIRSTLAUNCHBUY) spam buy before launch with targetBulk. this process using SCRIPT for process send bulk transaction with different blockNumber.
(FIRSTLAUNCHBUY) auto takeprofit and cutlose on autotrade sell token.
(SANDWICH) swap token with sandwich and arbitrange method. this process using SCRIPT or CUSTOM ROUTER for process sandwich.
(SANDWICH) swap token with high gwei before target success do transaction. this process using SCRIPT or CUSTOM ROUTER for process sandwich.
(SANDWICH) sell all balance token after buy and after target success do transaction. this process using SCRIPT or CUSTOM ROUTER for process sandwich.
(SANDWICH) delay after execute sandwich
(SANDWICH) filterMinimumAmountTarget
(BUYBULK) spam buy with nonce difference of 1 blockNumber per transaction with targetBulk. this process using SCRIPT for process send bulk transaction with different blockNumber.
```

# screnshot
some screenshots of this bot

1. home\
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/home.png?raw=true)

2. calculate max tx fee\
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/toolsCalculateTxFee.png?raw=true)

# bot sniper
1. home\
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botsniper.png?raw=true)

2. (swap) sniper token\
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botsniperSwap.png?raw=true)

3. (swap) autoTradeSellToken after sniper token
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botsniperSwapAutoTradeSellToken.png?raw=true)

4. (presale) sniper presale address\
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/presale.jpg?raw=true)

# bot exploit
a little information, if you don't have a special node private blockchain as needed by other bot, calm down because this bot already provides a premium node blockchain to filter transactions so you only need node blockchain free or paid to enable sending your transactions\

1. home\
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botexploit.png?raw=true)

2. (firstlaunchbuy) buy token with same blockNumber method addLiquidity or other method token. 
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botexploitFirstlaunchbuy.png?raw=true)

3. (sandwich) buy token before target do success buy and after that sell all the tokens.
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botexploitSandwich.png?raw=true)

- sandwich results with capital $1 amount and profit $0.025 :).
![alt text](https://github.com/damartripamungkas/botdexdamar/blob/main/images/botexploitSandwich2.png?raw=true)
- txhash buy = https://bscscan.com/tx/0x25f7cf89d1b5d7e4c457544be1222ae7908634f40de4611f072ab65313a6b84f
- txhash sell = https://bscscan.com/tx/0xc57572e1c98a10bd4c47df7e99f61d4be31138ab89f1c2736948300280b70d2c
- txhash target = https://bscscan.com/tx/0x85ccdf8c347d9bbc7d08f2ad5f5cd589c5844448206d52a38f0a4462043c6bde

# video
- watch my video example (v6.0.0) : https://youtu.be/FC6_BASNzvg
- watch my video example (v8.0.0) : https://youtu.be/pX-SkcBzRIY
- watch my video example (v8.1.0) : https://youtu.be/b4N4MyZPgYI

# information
- language : javascript
- framework : nodejs
- is open source : no
- is compiled : yes

# question
1. is there a monthly fee? no, you only pay once.
2. does it need a private node to run it? no, our bots can be run using private node or free node.
3. is there an update or repair fee? no, for updates and repairs we provide for free.
4. dex what support in this bot? pancakeswap, uniswap, apeswap, and others dex with structur code UniswapV2.
5. is this bot safe from theft of funds in the wallet? This bot is 100% safe, there is no theft of funds or other suspicious things.

# price
```
botsniper = $100
1 package botdexdamar(botsniper + botexploit) = $2000

note : if you buy it, you can only add 1 whitelist address that you will use and if you want to change your whitelist address we have provided tools to transfer your whitelist
```

# contactus
```
email: damartripamungkas@gmail.com
telegram: https://t.me/damartripamungkas
facebook: https://fb.com/damartripamungkass
```
