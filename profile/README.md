# Artemis AI

*Unlock the Value of Your Generative AI Prompts—Create, Share, Earn*

## Overview

**Artemys AI** is an AI-powered social platform built for the **Chain Abstraction Hackathon**. It enables users to generate, share, and monetize high-quality generative AI prompts, and their generated Image output across multiple EVM chains.

---

## Problem Statement
When it comes to existing AI art platforms, there are quite a few issues:

- **Lack of Community Focus on Art and Prompt Creation**: Existing platforms tend to focus mainly on the end product - the AI-generated artwork - but often overlook the importance of the creative process, particularly the crafting of prompts which is crucial in the generation of quality AI Art.

- **Requirement for Detailed Prompts in Advanced AI Models**: Advanced AI models like Stable Diffusion Ultra and Midjourney demand intricately detailed prompts for high-quality outputs, a skill not all users possess due to varying levels of experience.

- **Absence of Incentive and Structured Improvement Methods**: Many platforms lack mechanisms that actively engage users in improving their AI art creation skills in a structured, rewarding, and enjoyable manner.

- **Limited Monetization Opportunities for Prompt Creators**: there's a noticeable lack of platforms that offer talented prompt creators the opportunity to monetize their skills. Despite the crucial role they play in the AI art creation process, these creators often have limited avenues to gain financial rewards for their expertise in crafting effective and intricate prompts.

---

## Key Features
- **Multichain AI-Powered Prompt Generation**

  - Transform basic ideas into high-quality prompts using our finetuned GPT-4o assistant based on **SEDA** network and **interacted with using smart contracts on any chain**, enabling even complete beginners to achieve optimal results with AI image models.

- **Seamless Experience**

  - **Gasless Transactions**: Enjoy a fee-free experience powered by **Particle Network**. Get started creating quality AI prompts and images without manually paying for gas.
  - **Social Logins**: Our project leverages **Particle Connect SDK** to deliver a **frictionless onboarding experience with cross-chain compatibility**. By implementing Particle's authentication infrastructure, we've enabled users to seamlessly interact with multiple blockchains through a single, secure smart account - supporting both Web3-native and traditional social login methods.
    
- **AI Image Creation**: 

  - Generate stunning images using advanced models like Stable Diffusion, Stable Image Core, and Stable Image Ultra, leveraging either your own prompts or those crafted by the Prompt Generator to create artwork with excellent typography, complex compositions, dynamic lighting, and vibrant hues.

- **Generative AI Prompt Monetization**

   - Share AI image prompts for free in the community collection or monetize your creativity by selling protected premium NFT prompts with multi-layered security. Prompt Creations marked premium are locked, AES encrypted, and require **tx-gated access**. When users buy a prompt nft on any chain, the transaction hash is verified on chain using **Etherscan data proxies on** **SEDA**. If it was successful, our consumer smart contract returns a transactions successful response. Then, the AI prompt is unlocked, the key is regenerated and the prompt is decrypted and accessible to buyer.
   - **Transaction verification is also Chain abstracted, so a transaction hash created from buying a prompt on arbitrum sepolia can be verified using a smart contract on base sepolia**. 

- **Automated Price Feeds** - 
  - We created an automated price feed contract so users can price their premium prompts in USD and get paid directly in ETH. This is built using **SEDA**, and automated with **Chainlink Automation**

- **Social Engagement** 
  - Engage with a vibrant community by sharing AI-generated images and prompts, curating a personalized feed based on interests, following favorite creators, and interacting with others' creations through likes and remixes.

- **Community Powered AI Prompt Challenges**

   - Engage in or host theme-based challenges with USDC prizes held in escrow, where participants can submit prompt creations, vote for favorites, and win rewards. Our system ensures fair winner selection, while a chainlink automation finalizes challenges and distributes prizes.
      
---

## Getting Started
 This codebase has four main parts - Each repository has a very detailed Readme, enabling you to understand, test and interact with our project
  - [Frontend](https://github.com/Artemis-Multichain/frontend) - The UI, also shows how we use SEDA & Particle Connect on the client side
  - [Python Backend](https://github.com/Artemis-Multichain/backend): Stores all of the indexed data from the smart contracts, hosts our blockchain automation service that periodically finalizes community challenges and extra computation for social streaks, leaderboard, and social feed curation
  - [Seda Oracle](https://github.com/Artemis-Multichain/seda-oracle): contains the SEDA network integration components for providing decentralized oracle services for AI-driven prompts with GPT4o, pricing data, and transaction verification across chains
  - [Smart Contracts](https://github.com/Artemis-Multichain/evm-contracts): Smart contracts for the Generative AI Prompt Marketplace / Community Run Challenges / Automated Price Feed

*Empower your creativity. Join us today!*
