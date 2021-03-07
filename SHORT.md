![RaspiBlitz](pictures/raspilogo_400px.png)

*Build your own Lightning Node on a RaspberryPi with a nice Display.*

`Version 1.6.3 with lnd 0.11.1 and bitcoin 0.20.0 (or litecoin 0.18.1)`

![RaspiBlitz](pictures/raspiblitz.jpg)

**The RaspiBlitz is a do-it-yourself Lightning Node based on LND running together with a Bitcoin-Fullnode on a RaspberryPi 3/4 - with an HDD/SSD and a nice display for easy setup & monitoring.**

RaspiBlitz is mainly targeted for learning how to run your own node decentralized from home - because: Not your Node, Not your Rules. Discover & develop the growing ecosystem of the Lightning Network by becoming a full part of it. Build it as part of a [workshop](WORKSHOP.md) or as a weekend project yourself.

## Feature Overview

This is a quick look at the SSH main menu (once RaspiBlitz is SetUp):

![MainMenu-A](pictures/mainmenu.png)

As an alternative to the SSH menu, the "Ride the Lightning" (RTL) WebUI is available:

![RTL-preview](pictures/RTL-dashboard.png)

There are further Services that can be switched on:

* **Tor** (Run as Hidden Service) [details](https://en.wikipedia.org/wiki/Tor_(anonymity_network)#Onion_services)
* **ElectRS** (Electrum Server in Rust) [details](https://github.com/romanz/electrs)
* **BTCPayServer** (Cryptocurrency Payment Processor) [details](https://btcpayserver.org)
* **BTC-RPC-Explorer** (Bitcoin Blockchain Explorer) [details](https://github.com/janoside/btc-rpc-explorer)
* **LNbits** (Lightning wallet/accounts System) [details](https://twitter.com/lnbits/status/1253700293440741377?s=20)
* **SpecterDesktop** (Multisig Trezor, Ledger, COLDCARDwallet & Specter-DIY) [details](https://twitter.com/CryptoAdvance/status/1233833767283941376?s=20)
* **LNDmanage** (Advanced Channel Management CLI) [details](https://github.com/bitromortac/lndmanage)
* **Loop** (Submarine Swaps Service) [details](https://github.com/lightninglabs/loop/blob/master/README.md)
* **Pool** (Inbound Liquidity Marketplace) [details](https://github.com/lightninglabs/pool/blob/master/README.md)
* **JoinMarket** (CoinJoin Service) [details](https://github.com/JoinMarket-Org/joinmarket-clientserver)
* **ThunderHub** (Lightning Node Manager WebUI) [details](https://www.thunderhub.io/)
* **Faraday** (Channel Analysis & Recommendations CLI) [details](https://github.com/lightninglabs/faraday/blob/master/README.md)
* **Balance Of Satoshis** (Commands for working with LND balances) [details](https://github.com/alexbosworth/balanceofsatoshis/blob/master/README.md)
* **Kindle Display** (Bitcoin Status Display made with a jailbroken Kindle) [details](https://github.com/dennisreimann/kindle-display)
* **Stacking Sats Kraken** (Auto-DCA script) [details](https://github.com/dennisreimann/stacking-sats-kraken)
* **Circuit Breaker** (Lighthing Channel Firewall) [details](https://github.com/lightningequipment/circuitbreaker/blob/master/README.md)
* **PyBlock**  (Python Util & Fun Scripts) [details](https://github.com/curly60e/pyblock/blob/master/README.md)
* **Mempool Explorer** [details](https://github.com/mempool/mempool)
* **Sphinx Relay Server** [details](https://github.com/stakwork/sphinx-relay/blob/master/README.md)

You can connect the following Wallet-Apps to your RaspiBlitz:

* **Zap** (Android, iOS & Desktop) [details](https://zap.jackmallers.com/)
* **Zeus** (Android & iOS-TestFlight) [details](https://zeusln.app)
* **Fully Noded** (iOS) [details](https://apps.apple.com/us/app/fully-noded/id1436425586)
* **SendMany** (Android) [details](https://github.com/fusion44/sendmany/blob/master/README.md)
* **Sphinx Chat App** (Android & iOS) [details](https://sphinx.chat)


Also many more features like Touchscreen, Channels Autopilot, DynDNS, SSH-Tunneling, UPS Support, ...

## DeepDive Video (July 2020)

<a href="https://www.youtube.com/watch?v=QXUGg45CWLo" target="_blank"><img src="pictures/raspiblitz-deepdive.png" alt="Video Tutorial" width="400"></a><br>--watch--> https://www.youtube.com/watch?v=QXUGg45CWLo

## Time Estimate to Set Up a RaspiBlitz

The RaspiBlitz is optimized for being setup during a workshop at a hackday or conference (see [detailed workshop tutorial](WORKSHOP.md)). When it comes fully assembled with an up-to-date synced blockchain, it's possible to have it ready in about 2 to 3 hours - most of it is waiting time.

If you start at home ordering the parts from Amazon (see shopping list below) then it's a weekend project with a lot of downloading and syncing time where you can do other stuff while checking on the progress from time to time.

## Hardware Needed

All parts together cost around 180-250 USD - based on shops and location.

### Buy a ready-2-go RaspiBlitz (Germany, EU and International)

If you like to support the RaspiBlitz project you can order a ready-2-go RaspiBlitz or an all-you-need-hardware set for yourself or for your RaspiBlitz workshop from [raspiblitz.com](https://raspiblitz.com)

Find a list of other shops selling a Ready-2-Go RaspiBlitz in your area on [raspiblitz.org](https://raspiblitz.org/).

### Amazon Shopping List (buy parts & build it yourself)

The cheapest way is to buy and assemble the single parts yourself. There are two packages.

*Please try to use the exact hardware models that are recommended in the shopping lists. We have had multiple reports where, for example, other SSD or SSD cases/controllers lead to problems. The idea of the shopping lists is to provide you the best tested hardware components that work together - improvement recommendations are always welcome.*

#### Package: Standard (around 250 USD)

*The "Standard Package" is the most tested and recommended option if you can afford it. It aims to give you the best economic value to run all the RaspiBlitz features with good performance and even allows you to self-validate your blockchain in under 3 days.* 

* RaspberryPi 4 4GB (or 8GB) [amazon referral link](https://geni.us/raspiblitz-4gb-new)
* Power Supply - USB-C, 5V, >=3A [amazon referral link](https://geni.us/raspiblitz-ps)
* 1TB SSD - SanDisk SSD Plus 1TB 2.5" : [amazon referral link](https://geni.us/raspiblitz-1000gb-san) *other 1TB SSD models might cause power issues*
* SSD-case - UGREEN 2.5" External USB 3.0 Hard Disk Case with UASP support : [amazon referral link](https://geni.us/raspiblitz-ssd-case)
* MicroSDCard 32GB - Samsung PRO Endurance 32 GB microSDHC UHS-I U1: [amazon referral link](https://geni.us/raspiblitz-sc-card)
* LCD - 3.5" RPi Display, GPIO connection, XPT2046 Touch Controller: [amazon referral link](https://geni.us/raspiblitz-touchscreen)
* Heatsink Case for RPi4 : [amazon referral link](https://geni.us/heatsink-raspi4)

*You can even pay for your RaspiBlitz Amazon Shopping with Bitcoin & Lightning through [Bitrefill](https://blog.bitrefill.com/its-here-buy-amazon-vouchers-with-bitcoin-on-bitrefill-bb2a4449724a).*

#### Package: Minimal (around 180 USD)

*The minimal package aims for the cheapest price and allows you to use old hardware. It will always be possible to run all the basic features of a Bitcoin- & Lightning-Fullnode, but the system might be too slow to validate the blockchain history by itself and run some resource intensive extended services.*

Basic Parts:
* 1TB Hard Drive: [amazon referral link](https://geni.us/raspiblitz-hdd)
* Micro SD-Card 16GB: [amazon referral link](https://geni.us/raspiblitz-sd-card16gb)
* LCD - 3.5" RPi Display, GPIO connection, XPT2046 Touch Controller: [amazon referral link](https://geni.us/raspiblitz-touchscreen)

When RaspberryPi 3 --> add following parts:
* RaspberryPi 3B+ : [amazon referral link](https://geni.us/raspiblitz-rpi3)
* Heatsink-Case for RPi3: [amazon referral link](https://geni.us/raspiblitz-heatsink)
* Powersupply microUSB, 5V, >=3A: [amazon referral link](https://geni.us/raspiblitz-3A-power)

When RaspberryPi 4 2GB --> add following parts:
* RaspberryPi 4 2GB [amazon referral link](https://geni.us/raspiblitz-4-2gb)
* Power Supply - USB-C, 5V, >=3A [amazon referral link](https://geni.us/raspiblitz-ps)
* Heatsink Case for RPi4: [amazon referral link](https://geni.us/heatsink-raspi4)

[What other case options do I have?](FAQ.md#what-other-case-options-do-i-have)

## Support

If you run into a problem or you have still a question, follow the steps below to get support. Also check the [setup documentation](#setup-process-detailed-documentation) for details.

1. Look up the [FAQ](FAQ.md) if you can't find an answer to this question/problem.

2. If you have a hardware problem, please check that your hardware parts are exactly the parts recommended in the shopping list above. Different screens or even SSD-casings can cause problems.

3. There is a Telegram Group of RaspiBlitz users helping each other: https://t.me/raspiblitz

4. Please determine if your problem/question is about RaspiBlitz or for example with LND. For example if you can't route a payment or get an error when opening a channel that is an LND question/problem and is best answered by the LND dev community: https://dev.lightning.community

5. Go to the GitHub issues of the RaspiBlitz: https://github.com/rootzoll/raspiblitz/issues Do a search there. Also check closed issues by removing 'is:open' from the filter/search-box.

6. If you haven't found an answer yet, open a new issue on the RaspiBlitz GitHub. You may have to register an account with GitHub for this. If it's a bug with the RaspiBlitz, please add (copy+paste) a Debug Report to your issue (see [FAQ](FAQ.md) for how to generate them) and/or add some screenshots/photos so the community gets more insight into your problem.

## FAQ

Here is a short selection of the very frequently asked questions:

* [How to backup my Lightning Node?](FAQ.md#how-to-backup-my-lightning-node)
* [How can I recover my coins from a failing RaspiBlitz?](FAQ.md#how-can-i-recover-my-coins-from-a-failing-raspiblitz)
* [Are those "Under-Voltage detected" warnings a problem?](FAQ.md#are-those-under-voltage-detected-warnings-a-problem)
* [Can I run RaspiBlitz on computer boards other than RaspberryPi?](FAQ.md#can-i-run-raspiblitz-on-other-computers-than-raspberrypi)

Do you still have more questions? Check the [RaspiBlitz-FAQ-Archive](FAQ.md).

## Community Development

Everybody is welcome to join, improve, and extend the RaspiBlitz - it's a work in progress. [Check the issues](https://github.com/rootzoll/raspiblitz/issues) if you wanna help out or add new ideas. You find the scripts used for RaspiBlitz interactions on the device at `/home/admin` or in this Git repo's subfolder `home.admin`.

To start your Deep Dive into the RaspiBlitz project, the following YouTube video (July 2020) is recommended: [https://www.youtube.com/watch?v=QXUGg45CWLo](https://www.youtube.com/watch?v=QXUGg45CWLo)

Get all details on "How to contribute to RaspiBlitz Development" on this video:

<a href="https://www.youtube.com/watch?v=ZVtZepV3OfM" target="_blank"><img src="pictures/video-contrib.png" alt="Video Tutorial" width="400"></a><br>--watch--> https://www.youtube.com/watch?v=ZVtZepV3OfM

Also get inspired for a deep-dive with the original "[RaspiBolt](https://stadicus.github.io/RaspiBolt/)" tutorial on how to build a lightning node on the RaspberryPi, the base work on which the RaspiBlitz was developed - so much thx to Stadicus :)

Join me on twitter [@rootzoll](https://twitter.com/rootzoll), visit us at an upcoming [#lightninghackday](https://twitter.com/hashtag/LightningHackday?src=hash) or check by one of our bitcoin meetups in Berlin ... every 1st Thursday evening a month at the room77 bar - feel free to buy me a beer with lightning there :)

* [How can I get further help/support?](#support)
