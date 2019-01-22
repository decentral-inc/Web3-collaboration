# Parallel

## Grant Application

This application is (select one):
- [ ] Speculative (use this by default)
- [ ] an RFP response


###

This application is (select one):
- [ ] Public (fully)
- [ ] Public with private finances


### Abstract

Develop JSON-RPC API for mobile client use and wallet related usecases. Our focus will be on mobile api, payments api, send and sign api, account management. Add significantly to the developer documentation. Wallet will be made to showcase our works.

## Checklist
- [ ] The [grants](https://github.com/w3f/Web3-collaboration/blob/master/grants/grants.md) document has been read and understood.
- [ ] The [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfMfjiRmDQDRk-4OhNASM6BAKii7rz_B1jWtbCPkUh6N7M2ww/viewform) will be completed accurately. Note that the Google Form requires the pull request URL.
- [ ] Abstract (above) is succinct and complete.
- [ ] The application is being included into the correct directory: either '[targeted](https://github.com/w3f/Web3-collaboration/tree/master/grants/targeted)' or '[speculative](https://github.com/w3f/Web3-collaboration/tree/master/grants/speculative)'.
- [ ] The application includes a project description.
- [ ] The application includes all names of team members.
- [ ] The application includes a description of the team's experience.
- [ ] The application includes all necessary GitHub and LinkedIn links.
- [ ] The application specifies the development language and the reason for choosing it.
- [ ] The "Development Roadmap" section in the application has a timeline of development.
- [ ] The "Development Roadmap" section in the application has an estimate of funds required.
- [ ] The "Development Roadmap" section gives an indication of the team's long term plans.





## Project Description

Parallel is a mobile substrate client with Point of Sale(PoS) to interact with Parity blockchains. 
Parallel's team contributes to substrate by developing JSON-RPC clients(like web3.js in ethereum) and mobile integration. We want to improve Substrate client library so that developing DApps for Substrate is as easy as developing DApps on Ethereum. Our project needs
- better account management API
- APIs for account backup and recovery for soverign mobile wallets
- Significantly improved developer documentation on how to install client library using Cocoapods or Yarn


## Problem

There is a general client for Substrate(oo7.js), but is not as flexible to be adopted in other platforms and languages. In addition, JSON-RPC API is lacking features related to extrinsics, runtime, and etc. This would make barriers for some developers to enter. Therefore, immediate development for adoption is needed.

The reason why JSON-RPC api client has to be developed is that:
1. oo7 is developed as UI library only in javascript, giving a narrow option for client implementation with limited performance.
2. Developing JSON-RPC api was the key for multi-language implementation.
3. It enables division of labour. Employer does not need to hire a blockchain developer who is also good at front-end javascript development.


## Solution

Parallel will solve the problems by contributing to client-side of the blockchain so that the Parity team can focus on its blockchain development.    

We solve the problem by providing:
- JSON-RPC API development/documentation for dapp development
- General client for end-users to use Substrate which accepts the newest implementation of the client updates
- Improvement on adoption on client for monitoring and interacting with runtime api endpoints in Substrate

There are JSON-RPC endpoints that are not documented yet [here](https://github.com/paritytech/substrate/tree/bf86ff0bd55d7512513838301e589d8ca68a5abf/core/rpc/src) in [offical documentation](https://substrate.readme.io/reference-link/system_name-1). We will focus on revealing what the rest of endpoints do. 

As we develop and adopt mobile client in beta stage, we will be able to able to provide a much faster rate of contribution to future updates such as parachain development, interacting with participant roles, staking mechanism. In addition, we will have our own client app so that the adoptions can be delivered to the users from beta stage to future.   

We will improve current Substrate api to provide more information on Substrate runtime. Current api system does not support looking up the runtime api endpoints and inputs. We will make another endpoints in Substrate which retrieves an interface that DApp and Substrate can communicate like ABI in ethereum. 



## Team members
Ling Qing Meng  
Nick Hyungsuk Kang  
Dillon Settle  
Rico Chen  
Nagu Thogiti  


## Team Website
https://decentral.solutions

## Legal Structure

### C Corporation, Incorporated in Delaware

Decentral, Inc.
119 Michael Way   
Santa Clara, CA   
95051  
  

## Team’s experience

### Ling Qing Meng

Ling Qing Meng is a software engineer specializing in ground-up development of blockchain applications and infrastructure. He has helped companies from Korea to New York and Silicon Valley as a developer, advisor, security auditor, investor, and whitepaper writer. His thought leadership on Zero-Knowledge Proofs and cryptographic data obfuscation has empowered a new generation of permissionless end-to-end value exchange.   
  
Prior to Decentral, Ling led a team at Branch Metrics in Palo Alto building the first market solution to deeplink AMP-html articles to specific mobile app views. His implementation of a dynamic AMP HTML template gave customers unrivaled SEO rankings while retaining SDK integration. This allowed market segmentation analysis and greatly increased profits through upselling. Additionally, he has industry specific experience contracting in the supply chain space as well as performing source code audits in IP litigation. Ling is motivated by blockchain's ability to finally allow a direct connection between the creation of value and the engineer who facilitates it, and wants to empower anyone who ventures into this new world.  
   
Ling recently spoke at the Global Blockchain Forum where he was a panelist on the topic of Trust in the Token Economy, which you can watch here: youtube: https://youtu.be/FwKMiKK68_Y. He was also one of the primary speakers at ETH San Francisco and with his position at Decentral, has become one of the most influential speakers in the blockchain space.  


### Nagu Thogiti


Nagu is a mathematician and CS with Cryptography and AI backgrounds. He was a security auditor, blockchain technical consultant/technical Advisor for many blockchain startups and helped in the design/architecture of their blockchain protocols and security engineering.  
  
Outside of Blockchain, Nagu advised National Taiwan Hospitals for their AI in Healthcare implementations and mentoring and helping 100+ computer scientists and medical professionals implementing AI Healthcare projects.  
  
Nagu also has a long track record of building successful data science teams and digital transformation for the enterprises.  
  
Nagu is a MIT certified professional in Cybersecurity, FinTech, IOT and BigData and AI. Nagu is also a Consensys certified Developer.  

## Nick Hyungsuk Kang
  
Nick Hyungsuk Kang is a software engineer with versatile experiences. He has been a hardware programmer, blockchain technical consultant, IoT researcher, machine learning engineer, and blockchain engineer. He has contributed to 6 Ethereum projects and received Global Accesibility Scholarship from Ethereum foundation. He has consulting/development experience with companies in Korea and the U.S to adopt blockchain in their business. He is one of early adoptor of Substrate and he is active in the riot chat for the update.

Other than blockchain, Nick researched on Secure DNS name autoconfiguration for IPv6 internet-of-things devices(SDNSNA), using NFC to manage user identification for IoT devices in the network. 

Nick is also one of the organizers of the official Korean developer group of Keras framework and lead Korean open source communities. 

Nick is a buidler who wants to bring blockchain to people by building open source projects with real working demo.


## Team Code Repos
www.github.com/hskang9  
www.github.com/ricochen 
www.github.com/lingqingmeng 


## Team LinkedIn Profiles
[Ling Qing](https://www.linkedin.com/in/ling-qing-meng-90a35552/)     
[Nagu](https://www.linkedin.com/in/naguthogiti/)    
[Rico](https://www.linkedin.com/in/ricochenx/)  
[Nick](https://www.linkedin.com/in/nick-kang-5217a7103/)


## Current Development Plan


## Background

A robust, more extensive substrate client API development library will lead to increased developer activity and contribution. The sooner we do it, the more long term benefit we have to gain. To give an analogy 

> Here is a simple description for what web3 in ethereum does

> 1) on web3 library, developer executes function like register_account()
>
> 2) the web3 formatter makes JSON-RPC2.0 payload corresponding to the function
>
> 3) the payload is sent from the rpc client provided by the web3 library
>
> 4) web3 receives the response and shows the result

As such, this is how web3.js functions as a client API development library for Ethereum. Because Substrate is architected differently, the ideal solution will incorporate Substrate/Polkadot specific nuances and adhere specifically to the problems that Substrate/Polkadot aims to solve as a whole.  

### Core Tasks of our Development Plan
1. Develop Substrate RPC client for account management, mobile key generation, encryption/decryption (1 month)    
2. NFC and Bluetooth module in Substrate to listen and authenticate payments (1.5 months)  
3. Document rest of JSON-RPC api endpoints in Substrate (1.5 months)  
4. Design and document interface for client to interact with Substrate runtime module (1.2 months)  
5. Develop interface between client and the runtime module with wallet onboarding (3 montha)  
6. Build wallet app for multiple substrate assets(e.g. [ERC721 runtime](https://github.com/shawntabrizi/substrate-erc721), default currencies on each substrate network) (3 months)     
7. Runtime API for building interface betweeb substrate and client(1.2 months)  

### Key Takeaway: We will build for Substrate, a formatter and rpc-client in multiple languages(javascript, python, go, rust) for developers so that they do not need to rebuild the client for the network.

![Parallel Overview](./parallel_overview.png)


## Further Development
IF we are selected for the grant, here are the development tasks we can work on.

* Point of Sale(PoS) with NFC to make polkadot network’s asset can be transferred in real life 
  Current research is [here](./pos.pdf)
  Point of Sale has become a trend in cryptospace and it is one of the most effective use cases for a blockchain. 
  If we make polkadot network supported PoS, this would expand polkadot ecosystem with robust real-life use cases.
  


## Development Roadmap
  

[10k] 1. Develop Substrate RPC client for account management, mobile key generation, encryption/decryption (1 month)    
[15k] 2. NFC and Bluetooth module in Substrate to listen and authenticate payments (1.5 months)  
[3k]  3. Document rest of JSON-RPC api endpoints in Substrate (1.5 months)  
[4k]  4. Design and document interface for client to interact with Substrate runtime module (1.2 months)  
[4k]  5. Develop interface between client and the runtime module with wallet onboarding (3 montha)  
[11k] 6. Build wallet app for multiple substrate assets(e.g. [ERC721 runtime](https://github.com/shawntabrizi/substrate-erc721), default currencies on each substrate network) (3 months)     
[12k] 7. Runtime API for building interface betweeb substrate and client(1.2 months)  

---

`[59k] Total Apple Watch App Development + Apple End to End Integration Software`


  


[12k] Showcase with an react app(e.g. block explorer)    
[20k] Develop mobile polkadot OS in React Native  
[10k] Travel budget 

---

`[42k] Total Blockchain software development for Point of Sale system`

  
## Intended language of development

We plan to implement JSON-RPC api in javascript, and we will choose javascript in order to implement this on react native first.

