BWS Core integration/staging repository
=====================================
[![GitHub version](https://badge.fury.io/gh/BWS%2FBWS.svg)](https://badge.fury.io/gh/BWS%2FBWS)


Masternodes are computers that run a BWS wallet and make decisions,
such as locking transactions with SwiftTX, coordinate obfuscation of coins,
and voting on budget funding. Masternodes are required to have 50000 BWS
collateral.

SUPER FAST
60 second block time is already very fast, BWS transactions using SwiftTX
are instant with ZERO confirmation wait time required.

PRIVACY
Already extremely secure and private, BWS is aiming its sights on establishing as one of the leading anonymous crypto-currency.
Zerocoin protocol transactions are fully functional on BWS

SECURE
Built on Bitcoin Core 0.10.x.
with some v0.13.2 updates and Dash / PIVX core v0.12.1
BIP38 Encryption/Decryption of Private Keys.

BWS is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- Anonymized transactions using coin mixing technology, we call it _Xend_.
- Fast transactions featuring guaranteed zero confirmation transactions (_SwiftTX_).
- Current Masternode technology used to secure the network and provide the above features, each Masternode is secured with a collateral of 50000 BWS.

More information at [https://bitcoinwspectrum.com](https://bitcoinwspectrum.om/)

### Coin Specs
| Algo                         | Xevan              |
|------------------------------|--------------------|
| Block Time                   | 60 Seconds         |
| Difficulty Retargeting       | Every Block        |
| Max Coin Supply (All Phases) | 103 M BWS           |
| BWS  swap coins              | 103 M BWS*    |

Wallet Port: 41798, RPC Port: 41799


### Rewards Breakdown

| **Block Height**       | **Masternodes**    | **PoW/PoS**               
|----------------------------|---------------------------|---------------------                 
| 2 - infinite           | 70% ( 5.6 BWS)    | 30% (2.4 BWS)   


HOW TO COMPILE THE SOURCE CODE

sudo apt-get update

sudo apt-get upgrade

sudo reboot

sudo apt-get install build-essential libtool autotools-dev autoconf pkg-config libssl-dev

sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3

sudo apt-get install libboost-all-dev

sudo apt-get install software-properties-common

sudo add-apt-repository ppa:wagerr/wagerr

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev

sudo apt-get install libminiupnpc-dev

sudo apt-get install libzmq3-dev

git clone https://github.com/bitcoinwspectrum/bitcoinwspectrum

cd bitcoinwspectrum

./autogen.sh && ./configure --enable-tests=no --without-gui && make && sudo make install

NODES (wallet has a seednode)

addnode 45.77.213.178 add

addnode 45.76.248.116 add

addnode 144.202.24.153 add
