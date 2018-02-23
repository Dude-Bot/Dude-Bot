# Dude-Bot

This is a closed source BOT for gitter.im and is still in BETA phase; some portions in DEVELOPMENT. There will be a slimmed down version of the bot with most of the core functionality available [here](https://github.com/Dude-WTF/simple-gitter.im-bot).

To have this bot available in your gitter.im chat simply share your room with Dude-Bot and he'll activate in roughly 1 minute after being added. This also works in private 1 on 1 chats with the bot.

---

Will be adding in hooks to FaceBook messenger and slack in near future.

---

## Designated commands/operations

* !mimic (@who)
  * !clearmimic
* !ask (some ?)
* !imageSearch (search phrase)

---

## Cryptocurrency Specific - In Development

* $ *Price lookup*
  * $(coin name/symbol) [convert to fiat]
  * $bitcoin USD
  * $btc GBP

* !tradeBot
  * !tradeBot (from coin amount) (from coin) (to coin)
  * !tradeBot (with who @name) (from coin amount) (from coin) (to coin amount) (to coin)
  * !tradeBot status
  * !tradeBot cancel (orderId)
    * Method Aliases: swap, trade, exchange

* !market
  * !market (from coin amount) (from coin) (to coin amount) (to coin)
  * !market status 
  * !market cancel (orderId)


---

### Bot Client Specific (Rig/Wallet Interface) - In Development
* !rigStatus [rigAlias]
* !rigSwapPool (Pool Alias) [Coin]
* !rigNotify (true/false)
* !wallet (method) (coin) [actions]
* !wallet getbalance (coin)
* !wallet send (coin) (to address) (amount)

---

## z-nomp mining pools

Easy to add other z-nomp pools - Just open a issue and provide the pool details and it will be added.

### LuckPool
* !luckpool [coin symbol]
* !luckpool minerstats (walletAddress)
  * Operation Aliases: workerstats, minterstats
* !luckpool mystats *use the following operations to configure 'mystats'*
* !luckpool addWallet (address) *Can add multiple at once, use commas to seperate them!*
* !luckpool listWallets 
* !luckpool removeWallet (address) *Can remove multiple at once, use commas to seperate them!*

Custom Operations - specific to luckpool
* !luckpool fixWebsite
* !luckpool wiki (page) (bookmark/anchor) 
* !luckpool status *custom monitoring for site and stratum servers*
* !luckpool status (coin)

### Fastblocks
* !fastblocks [coin symbol]
* !fastblocks minerstats (walletAddress)
  * Operation Alises: workerstats, minterstats
* !fastblocks mystats *use the following operations to configure 'mystats'*
* !fastblocks addWallet (address) *Can add multiple at once, use commas to seperate them!*
* !fastblocks listWallets 
* !fastblocks removeWallet (address) *Can remove multiple at once, use commas to seperate them!*

### Generic Z-NOMP - 0 Config
* !znomp get (domain:port) minerstats (walletAddress)

---

Donations are Accepted :smile:
---

Komodo: RWx5tdLyrDe5gNDwynwLN6im4HoEY**DUdE**7

BTC: 1EWVaH8jQccdQtpFx3y5L4rXRLAuubCk58

LTC: LPvqRzkYh5T6qnq1HU4ZfwXxoWmJ8dbs2w

zCash: t1N4HUoWy42KM4m7a6p9mHiDTerWSfeWCNx

ZEN: znaWz3CnN2Y1Vzx5YG8Amx1gQ5GR84pfwDn

ETH: 0xc9620D885c0966f9A6514a1c3c3CAA490bB0c018

BCH: qqn5ykk3g69hzmm6ulr94g0xw3jrfq4ffq9fnn074t
