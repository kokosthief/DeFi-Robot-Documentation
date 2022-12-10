---
description: Perform a quick and powerful analysis on any wallet.
---

# Wallet Check

Use **`/walletcheck`** command to run a full wallet check on all of a wallet's transactions.

<figure><img src="../../../.gitbook/assets/wallet-check-GIF.gif" alt=""><figcaption></figcaption></figure>

The wallet check analyzes tokens bought by wallet returning a list of variables and their values.

{% hint style="info" %}
Wallet check includes the analysis of **Multicalls**
{% endhint %}

### Each returned response includes

#### Tokens bought / sold by CA Bot

Amount of different tokens bought /sold by a contract, not a normal wallet.

#### Tokens bought / sold by wallet

Amount of different tokens bought /sold by the wallet.

#### Tokens REKT Ratio

Percentage of tokens bought where the trader could not exit his position.

#### Tokens Holding Ratio

Percentage of tokens still held by wallet and sold.

#### Tokens Profit Ratio

Percentage of trades that made profit over loss.

#### Total PnL

The total Profit of all trades as a value.

#### Avg. PnL / Token

The average of profits made across all trades.
