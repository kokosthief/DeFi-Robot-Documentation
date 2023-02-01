---
description: A simple overview of DeFi-Robot ecosystem and what to expect.
---

# 👀 Overview

The DeFi-Robot ecosystem is made up of advanced and dynamic interconnected [Launch Scanners](../utilities/launch-scanners/), [Analysis Tools](../utilities/analysis-tools/) and [Group](../utilities/group-chats/) [Chats](../utilities/group-chats/).

```mermaid
graph TD
Z[Arbitrum] --> E
A[ETH / BSC] --> B(Launch Scanners)
     B --> E(Contracts)
     B --> F(Deployer)
     B --> G(Awake)
     B --> H(Alpha Deployer)
       B --> I(Decompiler)
       I(Decompiler) --> B
       I(Decompiler) --> J(Contract Simulator)
       J --> B
    A --> C(Analysis Tools)
     C --> B
     B --> C
     C --> J
     C --> K(Wallet & Token Check)

    A --> D(Group Chats)
     D --> L(General)
     D --> M(Private)
     D --> N(Exclusive)





```

<img src="../.gitbook/assets/file.drawing (1) (2).svg" alt="" class="gitbook-drawing">

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td> <strong>Launch Scanner</strong></td><td>Get alerts on all contract deployments via our various launch scanners.</td><td></td><td><a href="../utilities/launch-scanners/">launch-scanners</a></td></tr><tr><td><strong>Analysis</strong> <strong>Tools</strong></td><td>Discover what functions and utilities lie within the our advanced bots.</td><td></td><td><a href="../utilities/analysis-tools/">analysis-tools</a></td></tr><tr><td><strong>Group Chats</strong></td><td>See what group chats are within the DeFi-Robot ecosystem.</td><td></td><td><a href="../utilities/group-chats/">group-chats</a></td></tr></tbody></table>

