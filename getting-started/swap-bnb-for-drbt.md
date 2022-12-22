---
description: Swap Binance Coin for our native token DRBT.
---

# Swap BNB for DRBT

<img src="../.gitbook/assets/file.drawing (12).svg" alt="" class="gitbook-drawing">

## 1. Go to Pancake Swap

Visit [Pancake Swap,](https://pancakeswap.finance/swap?outputCurrency=0x1a0ffdb73dd942f999fcdc4ecddcadb4c7e0b592\&chainId=56) import DRBT token when prompted and then select '**Connect Wallet**'.

Choose your wallet provider and connect your specified wallet to Pancake Swap.&#x20;

## 2. Add the BNB Smart Chain network

> _**If you already have the BNB Smart Chain network connected skip this step.**_

When prompted, simply '**Approve**' and  '**Switch network**' to the BNB Smart Chain network within your wallet interface so you can connect your wallet to Pancake Swap.

<figure><img src="../.gitbook/assets/Screenshot 2022-11-29 at 13.13.02.png" alt=""><figcaption></figcaption></figure>

## 3. Swap BNB for DRBT

**$DRBT** should be prefilled within the swap criteria when following the link from Step 1.&#x20;

Double check to make sure the contract address matches the one below:

{% code title="Contract Address" %}
```solidity
0x1A0ffDB73dD942F999fcDc4eCdDcadb4c7e0b592
```
{% endcode %}

If not simply copy and paste it into the swap.

Using the example of swapping **BNB** for **DRBT** to access Tier 3.

7,000,000 **DRBT** are required for Tier 3, however with the buy tax of **12%** we'll need to swap a little  more.

{% hint style="info" %}
Buy & Sell tax: **9%** (team) + **3%** (liquidity pool)
{% endhint %}

$$7000000 / 0.88 = 7955000$$

Therefore, type **7840000** into the swap and in the settings panel change the slippage to between **15-20%** which should be enough to include buy tax as well as price variability.

Select '**Swap**' and '**Confirm Swap**'.

> ### _**Voilà! Proceed to the next step to connect your Telegram account with the DeFi-Robot dapp.**_
