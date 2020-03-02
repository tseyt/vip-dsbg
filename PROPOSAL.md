# A Scalable Solution for Cross-Blockchain Interoperability

## 1. Introduction


## 2. Problem Statement
- Every blockchain platform today is unique with its own set of operations, rules for governance, and technical requirements. As a result, the development of decentralized applications (dApps) tend to be siloed to a single, or select few, blockchain(s), which invariably have significant negative impact on the volume of users a dApp can handle. This puts developers through a Sisyphus-ean burden, tasked with rolling a boulder up a hill only to see it roll back down and start over again. Developers must rewrite their applications for every additional blockchain platform they want to integrate with, getting in their way of reaching their total addressable market as well as preventing the viability of Facebook-sized dApps to exist on top of current blockchain(s). With growing support for the philosophy of "write once, deploy anywhere", the necessary groundwork must be set into place so that dApp developers may enjoy the same right. This research project will provide an overview of state-of-the-art inter-blockchain commmunication mechanisms. In addition, it will propose a conceptual framework for cross-blockchain interoperability.

## 3. Objectives
-	Explore the Ethereum yellow paper, EOS white paper, and any additional resources with the purpose of understanding key steps that need to be taken in order to build this "bridge" between blockchain platforms.
Immediate Plan:
- Use EOSIO and Ethereum development platforms to create transactions and push code on the EOS and Ethereum blockchains. This way we get a hands-on look at how the blockchain environment in both platforms behaves.
- Push Ethereum contracts from the EOS blockchain through an Ethereum Virtual Machine.

## 4. Preliminary Literature Review

As of right now, the popular method of linking blockchains is through the Ethereum Virtual Machine. This allows existing blockchains to connect and push transitions to only the Ethereum blockchain. A good example of this is the work done by IBM with their Hyper Ledger Fabric. The method produces tremendous results, however, it is not scalable to other blockchains yet. Another company, LiquidLink has developed a solution to connect EOS and Ethereum, but claim for future support for the connection of Bitcoin chains as well. A general solution to connect all the major blockchains seems to be impossible, but handling each major connection seems to be a feasable solution. The reason to connect certain blockchains like EOS to Ethereum is to get efficiency of EOS to be used with Ethereum and allow for general dApp solutions that can push to multiple blockchains. The question of efficiency of the bridging process becomes extremely important as if implemented wrong can defeat its own purpose. This paper will take a look at the existing models and analyze which are more efficient and what truly is the best way to make these connections. This area is hotly researched which is evident by various bounties on connecting the chains. For instance a challenge to connect EOS and Ethereum has been issued and many are attempting to solve the problem.

## 5. Methodology
