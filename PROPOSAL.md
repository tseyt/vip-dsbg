# A Conceptual Framework for Cross-Blockchain Interoperability

## 1. Introduction
- Every blockchain platform today is unique with its own set of operations, rules for governance, and technical requirements. As a result, the development of decentralized applications (dApps) tend to be siloed to a single, or select few, blockchain(s), which invariably have significant negative impact on the volume of users a dApp can handle. This puts developers through a Sisyphus-ean burden, tasked with rolling a boulder up a hill only to see it roll back down and start over again. Developers must rewrite their applications for every additional blockchain platform they want to integrate with, getting in their way of reaching their total addressable market as well as preventing the viability of Facebook-sized dApps to exist on top of current blockchain(s). With growing support for the philosophy of "write once, deploy anywhere", the necessary groundwork must be set into place so that dApp developers may enjoy the same right. This research project will provide an overview of state-of-the-art inter-blockchain commmunication mechanisms. In addition, it will propose a conceptual framework for cross-blockchain interoperability.

## 2. Problem Statement
- 

## 3. Objectives
-	Explore the Ethereum yellow paper, EOS white paper, and any additional resources with the purpose of understanding key steps that need to be taken in order to build this "bridge" between blockchain platforms.
Immediate Plan:
- Use EOSIO and Ethereum development platforms to create transactions and push code on the EOS and Ethereum blockchains. This way we get a hands-on look at how the blockchain environment in both platforms behaves.
- Push Ethereum contracts from the EOS blockchain through an Ethereum Virtual Machine.

## 4. Preliminary Literature Review

- A preliminary literature review shows that the established method in past studies/products of linking blockchains is through the virtual machine (VM). For instance, using the Ethereum VM allows existing blockchains to connect and push transitions to the Ethereum blockchain. A good example of this is Hyper Ledger Fabric from IBM and the Linux Foundation, which acts as an enterprise version of Ethereum. Building on top of existing VM's produces tremendous results, however, it is not easily scalable to additional blockchains quite yet. A similar product, LiquidLink has developed a second-layer solution connecting the public blockchains/smart contract platforms of EOS and Ethereum, claiming support in the future for greater blockchain connectivity, such as to Bitcoin. A general solution to connect all the major blockchains seems to be impossible, but handling each major connection seems to be a feasable solution. The reason to connect certain blockchains like EOS to Ethereum is to get efficiency of EOS to be used with Ethereum and allow for general-purpose dApp solutions that can push to multiple blockchains. The question of efficiency of the bridging process becomes extremely important as if implemented wrong can defeat its own purpose. This paper will take a look at the existing models and analyze which are more efficient and what truly is the best way to make these connections. This type of emerging reserach is growing rapidly which is evident by various bounties available for solutions to bridge the gap between various blockchains. The initial inspiration for this research project was the EOSIO smart contracts challenge issued by Block.One to find bridge EOS and Ethereum. 

## 5. Methodology

The primary research method for this study is application and literature review. This study will be a step by step process starting off with mini-objectives. The first mini-object would be to implement simple Smart Contracts for both the EOS.IO blockchain and the Ethereum blockchain. Next we must review the current processes of pushing transactions with the Ethereum Virtual Machine. From here, we can implement ways to translate an EOS.IO smart contract to the EVM and invoke a contract on the Ethereum blockchain that does what our EOS.IO contract intended to do. Between each step and implementation, multiple tests must incurr to steer the code towards success. This project aims to be a multi-semester project.

## 6. References

“EOS.IO White Paper.” GitHub, Block.one, github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md. Accessed on 2 March 2020.

“Hyperledger Burrow.” Hyperledger, www.hyperledger.org/projects/hyperledger-burrow. Accessed on 2 March 2020.

LiquidApps, liquidapps.io/liquid-link. Accessed on 2 March 2020.

Wood, Gavin. ETHEREUM: A SECURE DECENTRALISED GENERALISED TRANSACTION LEDGER. ethereum.github.io. Accessed on 2 March 2020.
