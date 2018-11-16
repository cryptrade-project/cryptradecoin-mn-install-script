CrypradeCoin(CRCO) One-Click Automatic Masternode Install Script
=====================================

![CryptradeCoin Banner](https://i.imgur.com/oM1aPBg.png)

Cryptrade is a decentralized cryptocurrency trading platform built on top of bitshares 2.0 which aims to provide traders with a secure and easy way to buy and sell cryptocurrencies and tokens online instantly.

CryptradeCoin(CRCO) is a private and anonymous cryptocurrency which is officially issued by Cryptrade. CRCO uses hybrid PoS+Masternode consensus to secure its blockchain and provides coin holders with full-time private and instant transactions by implementing swiftx and zerocoin protocol. Paying for the listing fees and trading fees in Cryptrade is the main use-case of CRCO coin.

## Installation (Ubuntu 14.04, 16.04 or 18.04)

```shell
wget -q https://raw.githubusercontent.com/cryptrade-project/cryptradecoin-mn-install-script/master/install.sh
chmod u+x install.sh
./install.sh
```
***

## Usage:
```
cryptradecoin-cli getinfo
cryptradecoin-cli mnsync status
cryptradecoin-cli masternode status
```

If you want to check/start/stop **CryptradeCoin** , run one of the following commands as **root**:

**Ubuntu 16.04 or 18.04**:
```
systemctl status CryptradeCoin #To check CryptradeCoin service is running.
systemctl start CryptradeCoin #To start CryptradeCoin service.
systemctl stop CryptradeCoin #To stop CryptradeCoin service.
systemctl is-enabled CryptradeCoin #To check whetether CryptradeCoin service is enabled on boot or not.
```
**Ubuntu 14.04**:  
```
/etc/init.d/CryptradeCoin start #To start CryptradeCoin service
/etc/init.d/CryptradeCoin stop #To stop CryptradeCoin service
/etc/init.d/CryptradeCoin restart #To restart CryptradeCoin service
```
***

## MN Collateral
<table>
<tr><th>Block Height</th><th>MN Collateral</th></tr>
<tr><td>1-450,000</td><td>1,000 CRCO</td></tr>
<tr><td>450,001-90,000</td><td>2,000 CRCO</td></tr>
<tr><td>90,001-135,000</td><td>4,000 CRCO</td></tr>
<tr><td>135,001-270,000</td><td>6,000 CRCO</td></tr>
<tr><td>270,001-540,000</td><td>8,000 CRCO</td></tr>
<tr><td>>=540,001</td><td>10,000 CRCO</td></tr>
</table>

***
