# NEXIA (Networked Expertise and Contextual Intelligent Assistant)

## Use Case: A portfolio rebalancer in Uniswap based on research RAG and agent built in Galadriel

### Problem Statement:

LLMs and other SLMs have created workable models for natural language processing, trained on public domain data. These models have undergone sufficient testing and established baselines for latencies and AI inference costs, making them appear compelling.
However, enterprises and private companies are hesitant to utilize public domain data due to concerns about proprietary information. They prefer private databases and knowledge bases.
To leverage the strengths of both public and private data, a solution is needed to query private data without incurring full training costs and to supply context-specific research to public systems, such as networking smart contracts for private research on public digital asset prices.

## Solution - Retrieval Augmented Generation:

A private research RAG can be employed, combining LLMs with a context-defined, privately indexed knowledge base. This enables a rebalancing agent to research curated, LLM-trained content within a domain-specific context using RAG and Galadriel agents.
The solution involves retrieval augmented generation, spliced and indexed private knowledge bases, and contextualizing LLM models. This optimizes AI training costs while preserving the benefits of public data training.
Private domain data can be integrated into network systems, including permissionless ones, through oracles, allowing for the injection of query responses from private research data.

## Use Case:

Implementation in Galadriel Web3 AI involves creating a knowledge base integrated into the Galadriel Network via an oracle. This enables private research data to be linked to smart contracts, facilitating on-chain LLM fund management and voting systems for domain arbitration.
The Retrieval-Augmented Generation is built with [Changelly](https://changelly.com/) reports to understand the digital asset class, the investment outlook for 2024, and specific price predictions for July 2024. The query process moves from specific to generic.

## Video
The video is available at: https://youtu.be/y-GOJWzqANs

## Presentation deck
https://prezi.com/view/884EVai4o3vI8WgCd7HX/

## How to Run NEXIA (Devnet)

### Installation and Setup
* Follow the steps to install Galadriel.
* Set up the on-chain contracts and agents.

### Deployment
* **Agent Deployment:**
  * Agent deployed to 0x6F78f66ad057C4d429F153E33FeDF80b829A3b5b
* **ChatGPT with Knowledge Base Deployment:**
  * Knowledge base: QmRW646Zabid4gJC5YmwpgF3q9iTCsUqymuXpp9iphQcis
  * ChatGPT deployed to 0x1F8505B459B71920Da60fd625A629fE08a0e4399

### Smart Contract
* The smart contract can be found at the following address in the Galadriel devnet: [Smart Contract Address]

### Running the Chat and Agent Interface
* Navigate to the `\Galadriel\contracts\contracts` directory.
* Run the following commands:
  * `npm run chat`
  * `npm run agent`

### Rebalancer Functionality
* The rebalancer adjusts the ETH/DAI portfolio based on LLM agent predictions.
* **Example:**
  * Initial WETH balance: 1 ETH
  * Final WETH balance: 0.99 ETH
  * Initial DAI balance: 0 DAI
  * Final DAI balance: 342.4783756098569 DAI

### Next Steps
* Incorporate cross-chain capabilities.
* Implement webhooks for integration.


