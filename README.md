# Dude-Bot

This is a closed source BOT for gitter.im - there will be a slimmed down version of the bot with most of the core functionality available [here](https://github.com/Dude-WTF/simple-gitter.im-bot).

To have this bot available in your gitter.im chat simply share your room with Dude-Bot and he'll activate in roughly 1 minute after being added. This also working in private 1 on 1 chats with the bot.

---

Will be adding in hooks to FaceBook messenger and slack in near future.

---

## Designated commands/operations

* !mimic (@who)
* !ask (some ?)
* !imageSearch (search phrase)

---

## Cryptocurrency Specific - In Developement
* !tradeBot (from coin amount) (from coin) (to coin)
* !tradeBot (with who @name) (from coin amount) (from coin) (to coin amount) (to coin)
* !tradeBot status
* !tradeBot cancel (orderId)
  * Method Aliases: swap, trade, exchange

* !market (from coin amount) (from coin) (to coin amount) (to coin)
* !market status 
* !market cancel (orderId)

---

### Bot Client Specific (Rig/Wallet Interface) - In Developement
* !rigStatus [rigAlias]
* !rigSwapPool (Pool Alias) [Coin]
* !rigNotify (true/false)
* !wallet (method) (coin) [actions]
* !wallet getbalance (coin)
* !wallet send (coin) (to address) (amount)

---

## z-nomp mining pools

Easy to add other z-nomp pools, in the method configuration add the following options for your custom command. If you would like to have your pool added but don't want to configue, open a issue and provide the pool details.

```
znomp: {
  znompDomain: "www.yourPoolURL.com",
  znomp: port#
}
```

### LuckPool
* !luckpool [coin symbol]
* !luckpool minerstats (walletAddress)
  * Operation Aliases: workerstats, minterstats
* !luckpool fixWebsite
* !luckpool wiki (page) (bookmark/anchor)

### Fastblocks
* !fastblocks [coin symbol]
* !fastblocks minerstats (walletAddress)
  * Operation Alises: workerstats, minterstats

