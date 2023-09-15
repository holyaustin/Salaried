# Salaried :  A Decentralized Pool for Freelancer / Agent Escrow platform

## Introduction

In the world of freelancing and agent-client relationships, trust is paramount. To address the challenges of trust, payment security, and dispute resolution, the concept of a "Decentralized Pool for Freelancer/Agent Escrow Platform" has emerged. This innovative platform harnesses the power of blockchain technology to create a secure, transparent, and efficient ecosystem for freelancers, agents, and clients.

### Key Components and Features

1. Blockchain Technology: At the core of this platform is a blockchain-based infrastructure that ensures transparency and immutability of all transactions and agreements. This technology provides a secure and tamper-proof ledger for tracking payments, milestones, and communication.

2. Smart Contracts: Smart contracts play a pivotal role in automating the escrow process. When a freelancer and a client agree on a project, funds are escrowed into a smart contract. The smart contract is programmed to release funds to the freelancer upon meeting predefined milestones or conditions, providing a trustless mechanism for payment security.

3. Decentralization: Unlike traditional escrow services, this platform operates in a decentralized manner, eliminating the need for intermediaries. This decentralization reduces fees, enhances security, and ensures that funds are controlled by the parties involved rather than a centralized entity.

4. Transparent Reputation System: The platform incorporates a reputation system that allows freelancers and agents to build trust over time. Client reviews, project success rates, and dispute resolution outcomes contribute to a transparent and credible reputation score for all participants.

5. Dispute Resolution Mechanism: In the event of disputes, the platform leverages blockchain's transparency to facilitate fair and efficient dispute resolution. Arbitrators or decentralized autonomous organizations (DAOs) can be involved to make impartial decisions.

6. Currency Agnosticism: The platform supports multiple cryptocurrencies, making it accessible to a global audience while accommodating various digital currencies and tokens.

A new and secure way to get paid for freelancing through an agent escrow contract. Try it out!.

## Web 3.0 technologies Used

Frontend: NextJS, postcss, tailwindcss, Theme
web3 technologies: Web3 Modal, metamask wallet, Bunzz,  XMTP
Backend: Solidity, Node.js, Bunzz EscrowByAgent Module, Bunzz ERC20 Module

Blockchain: Mumbai testnet

Project initiated and created for dApp-A-thon Season 2:  

## Description

This project was made using several technologies. The front-end was designed using a server-side-rendering javascript tech known as NextJS. the latest version of Next was used because of how fast it was to build the project.  
A user can creates a new pool by clicking either of the following

1. Add Pool (Native) MATIC or
2. Add Pool (ERC20) PST Token Mint PST Token.

When you create a pool a pool with the PST token, you have to approve the contarct to spend the PST token on your behalf befeore tramsfering token to the smart contarct.

Once deal is completed, the agent releases token to the reciever and get its percentage.

If you dont have the PaySmart (PST) Token, you can mint it by clicking on Mint PST Token.
The entire project demo was deployed to Vercel

## Live DApp hosted on

Live Dapp on Vercel: - <https://salaried.vercel.app/>

Deployed to Polygon Mumbai Testnet through Bunzz:
EscrowAddress = "0x8204861156bedE45f0aBaaf2bB752D702FCbF23A"
<https://mumbai.polygonscan.com/address/0x8204861156bedE45f0aBaaf2bB752D702FCbF23A>
ERC20 tokenAddress = "0x179c44B91554AD48745f28dd539Ae558d4f1c3b1"
<https://mumbai.polygonscan.com/address/0x179c44B91554AD48745f28dd539Ae558d4f1c3b1>

## Bunz Module template id

https://app.bunzz.dev/module-templates/4be22852-e07a-4ff7-ba24-96fa36599743?version=1.0.1

https://app.bunzz.dev/dapps/23ec574b-4a29-47a4-9edb-aaa3c3808d86/dashboard

### Bunzz deccipher 
https://app.bunzz.dev/decipher/chains/80001/addresses/0x179c44b91554ad48745f28dd539ae558d4f1c3b1

## Getting Started with EscrowByAgent

 1. Deploy this contract. (Anybody can deploy this contract for an escrow
          service and make money from this service)
      2. Create an escrow pool with recipient, agent and amount
          - call depositByETH to deposit ETH
          - call deposit to deposit ERC20 token
              * can't use same address for recipient and agent.
      3. Once you (sender) allow the agent to release the payment
           (this option is outside of blockchain), the agent will release the payment.
          - call release by agent
              * ownerFee will be transferred to smart contract owner
              *agentFee will be transferred to the agent
      4. Approve to cancel the payment when you want to cancel it.
          - call approveCancel
              * sender, recipient and agent will approve for canceling
      5. Cancel the payment
          - call cancel to cancel the payment
              This function works for these cases:
                  1) recipient and sender accepted.
                  2) sender accepted and recipient didn't
                      * need agreement of agent

## Connect with me and send me a mail

E-mail - <holyaustin@yahoo.com>

stay connected on twitter @holyaustin

erc20
<https://mumbai.polygonscan.com/address/0x179c44B91554AD48745f28dd539Ae558d4f1c3b1>

escrow
<https://mumbai.polygonscan.com/address/0x8204861156bedE45f0aBaaf2bB752D702FCbF23A>
