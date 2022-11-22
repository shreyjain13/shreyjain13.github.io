---
title:  "Social Applied ZK Projects on Ethereum "
mathjax: true
author: shrey
category: coffee
---

The work being done with zero-knowledge proofs (ZKPs) in the Ethereum ecosystem for improving privacy and scalability is quite promising. 

There is still a small community of people who are specifically working on social applications of ZKP technology on Ethereum that I wanted to try to highlight here. I define "social applications" as pretty much anything that is not oriented on scaling solutions or financial solutions (yes, transferring money is social, but I think you can get a flavor for what I am trying to do). 

I recently tried to crowdsource the key projects working in this space [on Twitter](https://twitter.com/shreyjaineth/status/1590310990876659712?s=20&t=3CHekKSyDClGxAIsrChMQA) and was quite happy with the response that it felt approprite to try and aggregate the comments and DMs into a blog for people. 

Some of the things I am interested in working on in this space include: signed messages, [designated verifier proofs](https://www.youtube.com/results?search_query=working+towards+a+plural+public+via+common+knowledge+and+designated+verifier+proofs), zero-knowledge machine learning for healthcare applicaitons, and how we can build [common knowledge](https://en.wikipedia.org/wiki/Common_knowledge_(logic)) in communication protocols. If this is also of interest to you, DM me on [Twitter](https://twitter.com/shreyjaineth). 

I break down the projects in social applied zk into three key categories: 

- Identity 
- Governance
- Messaging 

Disclaimer: I am not invovled (financially or as a collaborator) with any of the projects below other than the zkSBT and designated verifier work which I was a co-author on. Orderded alphabetically to not give preference to any specific project. 

## Identity
- [Interep](https://interep.link/): Private reputation and identity system allowing services to verify that users belong to a certain group or meet certain reputation criteria without revealing their identities. Users can anonymously export reputation from platforms such as Twitter and Github.
- [Relic Protocol](https://relicprotocol.com/#certificates): Relic Protocol uses ZKPs to prove facts about arbitrary historical Ethereum state, allowing users to prove their reputation based on their historical on-chain activity and minted as SBTs. 
- [Sismo](https://www.sismo.io/): Sismo is a modular protocol issuing ZK Badges for reputation portability and aggregation
- [Sealcred](https://sealcred.xyz/): SealCred allows you to experience the world pseudonymously with ZK badges. This means you can prove ownership of an NFT without it tracing back to you.
- [Unirep](https://unirep.social/)): Unirep allows anonymous members of a group to give, receive, and prove reputation without revealing their identity. Applications or people can act as attesters and build their own reputation tokens on top of a shared Unirep contract.
- [Worldcoin](https://worldcoin.org/): Worldcoin has built a [Privacy-Preserving Proof-of Personhood Protocol](https://worldcoin.org/the-worldcoin-protocol)
- [zkPortal](https://zkportal.io/):Bringing personal data to web3 in a trust-minimised and private way: preventing sybil attacks, enabling 1P1V and helping DeFi to stay compliant.
- [zkSBTs](https://github.com/enricobottazzi/ZK-SBT): ZK SBTs allows for the creation of a composable network of trust. The token is always visible on chain making impossible for a user to hide the existance of an information when requested. The information contained in the claim is obscured using ZK in order to guarantee privacy. The only thing stored on chain is the hash of a signed message.


## Governance 
- [Devfolio](https://devfolio.co/projects/anonymous-voting-system-c15d): An anonymous voting system full on-chain. 
- [Nouns DAO heyanoun](https://nouns.wtf/vote/150): A way for snapshotted nouners at a given proposal to pseudonymously submit messages about the proposal.
- [MACI](https://github.com/privacy-scaling-explorations/maci): Minimum Anti-Collusion Infrastructure (MACI) is a base layer for bribery-resistant, secure, and private digital voting.
- [zkPIN](https://github.com/zk-pin/pin): Creating commitment pools to sign or endorse an idea in a trust minimized way. 



## Messaging 
- [designated-verifier-proofs](https://github.com/enricobottazzi/designated-verifier-proof/blob/main/README.md): Cryptographic scheme that is compatible with Ethereum to ensure that only a designated verifier is persuaded of information being communicated to them and any 3rd party is unsure whether the designated verifier is telling the truth or not
- [heyanon](https://twitter.com/heyanonxyz): heyanon, by [personae labs](https://twitter.com/personae_labs) is a way for people who are in cool groups or did cool stuff on Ethereum to broadcast messages anonymously on Twitter.
- [Sealcaster](https://blog.bigwhalelabs.com/applied-zk-part-3-or-how-we-made-anonymous-casts-on-farcaster-possible/): Anyonymous messaging on Farcaster. 
- [Semaphore](https://semaphore.appliedzkp.org/): Semaphore is a protocol, designed to be a simple and generic privacy layer for Ethereum DApps. Using zero knowledge, Ethereum users can prove their membership of a group and send signals such as votes or endorsements without revealing their original identity.
- [zkEmail](https://zkemail.xyz/): Trusless email verification on-chain. The [talk from DevCon](https://www.youtube.com/watch?v=sPCHiUT3TmA) is more informative. 
- [zknullifier](https://github.com/zk-nullifier-sig/zk-nullifier-sig/): Creates anonymous identifiers via verifiably deterministic signatures on Ethereum, leading to unique pseudonymity. 

I will keep this blog live, so DM me on Twitter if I missed your project and if you think it fits in one of the above buckets. 

Thanks Vivek B for feedback. 

<script defer data-domain="shreyj.com" src="https://plausible.io/js/script.js"></script>
