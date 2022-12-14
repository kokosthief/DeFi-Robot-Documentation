---
description: >-
  Stay on top of all new pairs via live listing channels and their connected
  bots.
---

# Contract Deployment Listing Channels

## Live and dynamic listing channels of new contract deployments

The most impressive part of the DeFi-Robot are the live and dynamic live contract listings that come through Telegram channel for the Ethereum, Binance and Arbitrum blockchains.

### [ETH/BSC Contracts](eth-bsc-contracts.md)&#x20;

{% hint style="success" %}
Lists all new contracts.
{% endhint %}

### [ETH/BSC Deployer](eth-bsc-deployer.md)

{% hint style="success" %}
Lists all new contracts where the developer achieved a previous moonshot >50k.
{% endhint %}

### [ETH/BSC Awake](eth-bsc-awake.md)&#x20;

{% hint style="info" %}
Lists previously sleeping contracts which have awoken because of recent developer activity.
{% endhint %}

### ETH/BSC Alpha Deployer (beta)&#x20;

{% hint style="info" %}
Exclusive Alpha Deployer filtering pure alpha deployments
{% endhint %}

<img src="../../.gitbook/assets/file.drawing.svg" alt="" class="gitbook-drawing">

## Each listing can include the following

<details>

<summary>Token information</summary>

First section of each listing always contains the token name, contract address and the corresponding trading ticker.

</details>

<details>

<summary>Bytecode hashes </summary>

Included are three hashes all clickable so you can quickly cross-reference previous launches for matching hashes.&#x20;

This is useful to see which past projects with matching hashes were scams and which ones were not.

**1. Bytecode Hash**

Where the bytecode of the contract is hashed.

#### 2. Functions Hash

Where the contract functions list and callable functions are hashed.

#### 3. Functions + Funding Hash

Where the contract functions and the funding source of developer's wallet (Binance, Coinbase, ...) are hashed together.&#x20;

Usually a dev use same DEX so could be useful to find all other contracts, with same hash, from same DEX.

</details>

<details>

<summary>List functions</summary>

Click **`functions`** and then **`/start`** on the next page to list all available functions. This works even with unverified contracts on the blockchain.

</details>

<details>

<summary>Developer Wallet</summary>

See the developer wallet and where it's funding came from as well as age of wallet.

</details>

<details>

<summary>Tokenomics and links</summary>

Here available is the total supply, decimals, and all necessary links about the contract.

</details>

<details>

<summary> Dev's Previous Launches</summary>

Split into two sections:

#### Dev's previous Best Token

* Total volume (swaps)
* Name | Ticker
* Launch date
* Links

#### Last Tokens summary

Lists and summary of last tokens

* Buys | Sells
* Links

</details>

<details>

<summary>Keywords</summary>

Quickly get an idea of what to expect with keywords such as:

* DIDN'T SCAM
* 400K
* RUGGED&#x20;

</details>

<details>

<summary>Contract Simulation</summary>

The results of the initial contract simulation are returned here where you can find information on:

* Buy and sell taxes
* Transfer tax
* Deadblocks
* Honeypot status
* Enable trading method

</details>

<details>

<summary>Potential Telegram Groups</summary>

This sections provides a list of Telegram groups which could correspond to the token launch.

</details>

<details>

<summary>Source Code Verified</summary>

This sections automatically parses any social media links or websites found within the contract when it becomes publicly verified by the deveoper.

?????? \[Hidden Mint] at \_mint"

It can also include a Hiddent Mint warning; If you see this it's recommended to check the contract. Most of the time it's used to create the initial supply (which is not the official way to do it ...), but could also be used by another function to actually mint after launch.



</details>

<details>

<summary>Live Updates</summary>

Live updates occur for the token listing for up to 12 hours or up until it rugs. Notifications are useful  to see:

* Liquidity added
* How many pre-approvals&#x20;
* When token is live for trading
* How many swaps occurred
* If or when it rugs

</details>

## How the Simulator Bot works with Channels

{% hint style="info" %}
There are numerous ways in which the Simulator Bot is embedded within each live listing.
{% endhint %}

Upon each listing being generated, the Simulator Bot already determines the functions, runs a quick simulation and performs a liquidity check.&#x20;

The DeFi-Robot channel then uses this information to present the initial listing information.

### Dynamic List functions and Re-Lunch button

What's more, the user can interact with the Simulator Bot within each listing to dynamically generate new information.

Within each contract listing the user can list the functions of a contract as well as re-launch the quick contract simulator.

<figure><img src="../../.gitbook/assets/list-functions-and-re-launch-simulation.gif" alt=""><figcaption></figcaption></figure>

<img src="../../.gitbook/assets/file.drawing (14).svg" alt="" class="gitbook-drawing">
