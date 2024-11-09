# Artemis AI

*Unlock the Value of Your Generative AI Prompts—Create, Share, Earn*

## Overview

**Artemys AI** is an AI-powered social platform built for the **Chain Abstraction Hackathon**. It enables users to generate, share, and monetize high-quality generative AI prompts, and their generated Image output.

---

## Key Features
- **Multichain AI-Powered Prompt Generation**

     Transform basic ideas into high-quality prompts using our finetuned GPT-4o assistant based on **SEDA** network and **interacted with using smart contracts on any chain**, enabling even complete beginners to achieve optimal results with AI image models.

- **Seamless Experience**

  - **Gasless Transactions**: Enjoy a fee-free experience powered by **Particle Network**. Get started creating quality AI prompts and images without manually paying for gas.
  - **Social Logins**: Our project leverages **Particle Connect SDK** to deliver a frictionless onboarding experience with cross-chain compatibility. By implementing Particle's authentication infrastructure, we've enabled users to seamlessly interact with multiple blockchains through a single, secure smart account - supporting both Web3-native and traditional social login methods.
    
- **AI Image Creation**: 

  - Generate stunning images using advanced models like Stable Diffusion, Stable Image Core, and Stable Image Ultra, leveraging either your own prompts or those crafted by the Prompt Generator to create artwork with excellent typography, complex compositions, dynamic lighting, and vibrant hues.

- **Generative AI Prompt Monetization**

   - Share AI image prompts for free in the community collection or monetize your creativity by selling protected premium NFT prompts with multi-layered security. Prompt Creations marked premium are locked, AES encrypted, and require **tx-gated access**. When users buy a prompt nft on any chain, the transaction hash is verified on chain using **Etherscan data proxies on** **SEDA**. If it was successful, our consumer smart contract returns a transactions successful response. Then, the AI prompt is unlocked, the key is regenerated and the prompt is decrypted and accessible to buyer.
      

## Getting Started
 This codebase has four main parts - Each repository has a very detailed Readme, enabling you to understand, test and interact with our project
  - [Frontend](https://github.com/Artemis-Multichain/frontend) - The UI, also shows how we use SEDA & Particle Connect on the client side
  - [Python Backend](https://github.com/Artemis-Multichain/backend): Stores all of the indexed data from the smart contracts, hosts our blockchain automation service that periodically finalizes community challenges and extra computation for social streaks, leaderboard, and social feed curation
  - [Seda Oracle](https://github.com/Artemis-Multichain/seda-oracle): contains the SEDA network integration components for providing decentralized oracle services for AI-driven prompts with GPT4o, pricing data, and transaction verification across chains
  - [Smart Contracts](https://github.com/Artemis-Multichain/evm-contracts): Smart contracts for the Generative AI Prompt Marketplace / Community Run Challenges / Automated Price Feed

*Empower your creativity. Join us today!*
