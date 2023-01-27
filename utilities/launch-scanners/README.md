---
description: Stay on top of all newly listed contracts
---

# Launch Scanners

{% hint style="success" %}
**Get access:**

Follow the generated links from the **Dapp** as outlined in [Access Bots via Dapp](../../about/getting-started/2.-access-bots-via-dapp.md).
{% endhint %}

## Live and dynamic listing channels of newly deployed contracts

The most impressive part of DeFi-Robot are the live and dynamic launch scanners that list and filter all contract deployments on the **Ethereum**, **Binance Smart Chain** and **Arbitrum** blockchains.

### There are four launch scanners

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><strong>Contracts</strong></td><td>Scans all newly deployed contracts on the blockchain with no filters or blacklists</td><td></td><td><a href="contracts.md">contracts.md</a></td></tr><tr><td><strong>Deployer</strong></td><td>Scans for contracts where the developer achieved a previous moonshot >50k</td><td></td><td><a href="deployer.md">deployer.md</a></td></tr><tr><td><strong>Awake</strong></td><td>Lists previously sleeping contracts which have awoken because of recent dev activity</td><td></td><td><a href="awake.md">awake.md</a></td></tr><tr><td><strong>Alpha Deployer</strong></td><td>Checks past deployer projects inc. connected wallets from 5 jumps away</td><td></td><td><a href="alpha-deployer.md">alpha-deployer.md</a></td></tr></tbody></table>

### Information presented via telegram can some or all of the following

<img src="../../.gitbook/assets/file.drawing.svg" alt="" class="gitbook-drawing">

## More information regarding certain sections:

<details>

<summary>List functions</summary>

Click **`functions`** and then **`/start`** on the next page to list all available functions. This works even with unverified contracts on the blockchain.

</details>

<details>

<summary>Search Hashes</summary>

Select each Hashcode to cross-reference previous launches for matching hashes within Telegram.

This is useful to see which past projects with matching hashes were scams and which ones were not.

**Bytecode Hash**

Where the bytecode of the contract is hashed.

#### Functions Hash

Where the contract functions list and callable functions are hashed.

#### Functions + Funding Hash

Where the contract functions and the funding source of developer's wallet (Binance, Coinbase, ...) are hashed together.&#x20;

Usually a dev use same DEX so could be useful to find all other contracts, with same hash, from same DEX.

</details>

<details>

<summary>Suspicious &#x26; Rare Functions</summary>

Alerts on suspicious or rare functions within the launch scanner to give more details on important functions that are usually only accessed with the list functions tool within [Contract Simulator](../analysis-tools/contract-simulator/) bot.&#x20;

See a percentage of rugs there are where contracts have used specific functions. Also notifies users if the functions are completely new to the DeFi-Robot launch scanners indicating new code in the space.

</details>

<details>

<summary>Contract Simulation</summary>

Select the dynamic **`Re-Launch`** button to double check taxes or other changes.

The initial contract simulation results are provided so it's easy for you to set up your sniper bot including some or all of:

* **Buy/sell/transfer tax**
* **Deadblocks**
* **Honeypot status**
* **Enable trading method**

Also shown is the detected l**aunch scenario**

* **Adding LP**
* **Enable trade method**
* **Both**



</details>

<details>

<summary> Dev's Previous Launches</summary>

Split into three sections:

#### Dev's previous Best Token

* Total volume (swaps)
* Name | Ticker
* Launch date
* Links

#### Last Tokens summary

Lists and summary of last tokens

* Buys | Sells
* Links

#### **Keywords**

Quickly get an idea of what to expect with keywords such as:

* DIDN'T SCAM
* 400K
* RUGGED

</details>

<details>

<summary>Potential Telegrams</summary>

This sections provides a list of Telegram groups which could correspond to the token launch.&#x20;

Our bot scrapes Telegram automatically to provide this information so you can investigate a project before any socials come through via the Source Code when verified.

</details>

<details>

<summary>Source Code Verified - Socials</summary>

This sections automatically parses any social media links or websites found within the contract when it becomes publicly verified by the deveoper.

It can also include a **⚠️ \[Hidden Mint] at \_mint"** warning; If you see this it's recommended to check the contract. Most of the time it's used to create the initial supply (which is not the official way to do it ...), but could also be used by another function to actually mint after launch.

Most of the time it's used to create a rug pull, even if liquidity is locked.



</details>

<details>

<summary>Live Updates</summary>

Live updates occur for the token listing for up to 12 hours or up until it rugs. Notifications are useful to see:

* **Liquidity added**
* **How many pre-approvals**&#x20;
* **When token is live for trading**
* **How many swaps occurred**
* **If or when it rugs**

</details>

## How the Contract Simulator works with Launch Scanner

{% hint style="info" %}
There are numerous ways in which the Contract Simulator is embedded within each live listing of contract deployments.
{% endhint %}

Upon each listing being generated, the Contract Simulator already determines the functions, runs a quick simulation and performs a liquidity check.&#x20;

The DeFi-Robot channel then uses this information to present the initial listing information.

### Dynamic List functions and Re-Lunch button

What's more, the user can interact with the Simulator Bot within each listing to dynamically generate new information.

Within each contract listing the user can list the functions of a contract as well as re-launch the quick contract simulator.

<figure><img src="../../.gitbook/assets/list-functions-and-re-launch-simulation.gif" alt=""><figcaption></figcaption></figure>
