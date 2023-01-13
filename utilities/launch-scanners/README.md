---
description: Stay on top of all newly listed contracts
---

# Launch Scanners

## Live and dynamic listing channels of newly deployed contracts

The most impressive part of the DeFi-Robot are the live and dynamic live contract listings that come through Telegram channels for **Ethereum**, **Binance** and **Arbitrum** blockchains; commonly known in the space as _**launch scanners**_.

Read more about our three main launch scanners and check below for a diagram of what to expect.

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><strong>Contracts</strong></td><td>Lists all newly deployed contracts with no filters or blacklists.</td><td></td><td><a href="contracts.md">contracts.md</a></td></tr><tr><td><strong>Deployer</strong></td><td>Lists all new contracts where the developer achieved a previous moonshot >50k</td><td></td><td><a href="deployer.md">deployer.md</a></td></tr><tr><td><strong>Awake</strong></td><td>Lists previously sleeping contracts which have awoken because of recent developer activity</td><td></td><td><a href="awake.md">awake.md</a></td></tr></tbody></table>

<img src="../../.gitbook/assets/file.drawing (6).svg" alt="" class="gitbook-drawing">

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
