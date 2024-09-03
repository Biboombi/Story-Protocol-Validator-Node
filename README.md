# Story Protocol Validator Node Setup Guide

## Introduction

This guide will walk you through the process of setting up a Story Protocol validator node. Story Protocol is revolutionizing the way narrative worlds are created in the Web3 space. It provides a simplified framework to manage the entire lifecycle of IP development, including origin tracking, frictionless licensing, and revenue sharing. Built for all media creators—writers, artists, and more—Story Protocol allows for the creation, contribution, and remixing of content, while capturing the value of those contributions.

## Key Events

- **August 2024:** Story Protocol raised $80 million in its Series B funding round.
- **September 2023:** Story Protocol completed a $25 million Series A funding round.
- **May 2023:** Story Protocol raised $29.3 million in funding.

## Prerequisites

Before you start, ensure you have the following:

- **Operating System:** Ubuntu native device, Ubuntu VM, or Mac device.
- **ETH Wallet:** Required for staking.
- **Hardware Requirements:**
  - **CPU:** 4-core processor
  - **RAM:** 8 GB
  - **Storage:** 200 GB
  - **Network:** 10 Mbps

It’s recommended to run the node on a VPS (Virtual Private Server) to ensure 24/7 uptime. You can use providers like Contabo, which offers affordable options. Consider selecting the Cloud 2 configuration for better performance, especially with their current promotion offering free storage upgrades.

## Setup Instructions

### 1. Install the Node

To install the Story Protocol node, run the following command in your terminal:

```bash
wget -O story.sh https://raw.githubusercontent.com/a3165458/story/main/story.sh && chmod +x story.sh && ./story.sh

2. Obtain Testnet Tokens and Create a Validator
To participate as a validator, you need to obtain testnet tokens from the Story Protocol faucet:
https://faucet-app-pi.vercel.app/

3. Create a Validator
After obtaining tokens, you can create your validator:

Minimum Stake: You need to stake at least 1 token to create a validator.
Validator Address: You can export the validator key to retrieve your validator address.

4. Monitor Your Node
Once your node is up and running, monitor its status to ensure everything is functioning correctly. Below is an example of what a normally running node looks like:


Conclusion
This guide has provided the steps necessary to install, configure, and run a Story Protocol validator node. Staking and running a node will help secure the network and potentially earn rewards in the future. Make sure to monitor your node regularly and stay updated with any announcements from the Story Protocol team.

For additional resources and updates, keep an eye on official communication channels and community forums.


