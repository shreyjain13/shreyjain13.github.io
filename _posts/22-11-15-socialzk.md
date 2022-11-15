---
title:  "Social Applied ZK Projects on Ethereum "
mathjax: true
author: shrey
category: coffee
---

The work being done with zero-knowledge proofs (ZKPs) in the Ethereum ecosystem for downstream applications that are trying to improve privacy and scalability is quite promising. 

Attempting to map the entirety of the work being done Ethereum ecosystem with ZKPs is too large of a task to do in a way that felt productive. However, there is still a small community of people who are specifically working on social applications of ZKP technology on Ethereum that I wanted to try to highlight here. I define "social applications" as pretty much anything that is not oriented on scaling solutions or financial solutions (yes, transferring money is social, but I think you can get a flavor for what I am trying to do). 

I recently tried to crowdsource the key projects working in this space [on Twitter](https://twitter.com/shreyjaineth/status/1590310990876659712?s=20&t=3CHekKSyDClGxAIsrChMQA) and was quite happy with the response that it felt approprite to try and aggregate the comments and DMs into a blog for people. 

I break down the projects in social applied zk into a three key categories: 

- Identity 
- Governance
- Messaging 

Disclaimer: I am not invovled (financially or as a collaborated) with any of the projects below other than the zkSBT work which I was a co-author on.

## Identity

- [Sismo](https://www.sismo.io/): Sismo is a modular protocol issuing ZK Badges for reputation portability and aggregation
- [Worldcoin](https://worldcoin.org/): Worldcoin has built a [Privacy-Preserving Proof-of Personhood Protocol](https://worldcoin.org/the-worldcoin-protocol)
- [zkSBTs](https://github.com/enricobottazzi/ZK-SBT): ZK SBTs allows for the creation of a composable network of trust. The token is always visible on chain making impossible for a user to hide the existance of an information when requested. The information contained in the claim is obscured using ZK in order to guarantee privacy. The only thing stored on chain is the hash of a signed message.
- [Interep](https://interep.link/): Private reputation and identity system allowing services to verify that users belong to a certain group or meet certain reputation criteria without revealing their identities. Users can anonymously export reputation from platforms such as Twitter and Github.
- [Relic Protocol](https://relicprotocol.com/#certificates): Relic Protocol uses ZKPs to prove facts about arbitrary historical Ethereum state, allowing users to prove their reputation based on their historical on-chain activity and minted as SBTs. 
- [Sealcred](https://sealcred.xyz/): SealCred allows you to experience the world pseudonymously with ZK badges. This means you can prove ownership of an NFT without it tracing back to you.
- [Unirep](https://unirep.social/)): Unirep allows anonymous members of a group to give, receive, and prove reputation without revealing their identity. Applications or people can act as attesters and build their own reputation tokens on top of a shared Unirep contract.

## Governance 
- [MACI](https://github.com/privacy-scaling-explorations/maci): Minimum Anti-Collusion Infrastructure (MACI) is a base layer for bribery-resistant, secure, and private digital voting.
- [zkPIN](https://github.com/zk-pin/pin): Creating commitment pools to sign or endorse an idea in a trust minimized way. 

## Messaging 
- [heyanon](https://twitter.com/heyanonxyz): heyanon is a way for people who are in cool groups or did cool stuff on Ethereum to broadcast messages anonymously on Twitter.
- [zkEmail](https://zkemail.xyz/): Trusless email verification on-chain. The [talk from DevCon](https://www.youtube.com/watch?v=sPCHiUT3TmA) is more informative. 
- [Semaphore](https://semaphore.appliedzkp.org/): Semaphore is a protocol, designed to be a simple and generic privacy layer for Ethereum DApps. Using zero knowledge, Ethereum users can prove their membership of a group and send signals such as votes or endorsements without revealing their original identity.
- [Sealcred](https://blog.bigwhalelabs.com/applied-zk-part-3-or-how-we-made-anonymous-casts-on-farcaster-possible/): 

I will keep this blog live, so DM me on Twitter if I missed your project and if you think it fits in one of the above buckets. 

<script defer data-domain="shreyj.com" src="https://plausible.io/js/script.js"></script>
