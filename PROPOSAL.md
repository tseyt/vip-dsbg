# A Conceptual Framework for Cross-Blockchain Interoperability

## 1. Introduction

Every blockchain platform today is unique with its own set of operations, rules for governance, and technical requirements. As a result, the development of decentralized applications (dApps) tend to be siloed into a single, or a select few, blockchain(s), which has a significant negative impact on the volume of users a single application can host. This puts developers through a Sisyphus-ean burden, tasked with rolling a boulder up a hill only to see it roll back down and start over again. Developers must rewrite their applications for every additional blockchain platform they want to integrate with, getting in the way of reaching their total addressable market as well as preventing the viability of Facebook-sized dApps to exist on top of current blockchain(s). With growing support for the philosophy of "write once, deploy anywhere", the necessary groundwork must be set into place so that dApp developers may enjoy the same right. This research project will investigate the current state of inter-blockchain communication (IBC) mechanisms. In addition, it will attempt to propose a conceptual framework for cross-blockchain interoperability.

## 2. Problem Statement

Developing a robust, scalable solution to bridge the millions of operational blockchains in the future is necessary if million-user dApps are to exist. This has long been recognized by the industry, but the necessary infrastructure for building something like this successfully is only just beginning to be realized. Numerous blockchain projects are still plagued by illiquidity of data and platform tribalism, which can frequently be accredited to ineffective communication systems and dysfunctional ecosystems. Especially today, as projects become more technically complex and increase in technical debt, user data becomes more vulnerable with an over-reliance on a single platform with a higher risk of attack. Linking multiple chains together is not only a hardier method of preserving user data, but it also ensures the maintenance of a single source of truth among these chains. In summary, there is a need for a better understanding of constraints within differing blockchains and a structured approach in identifying opportunities to connect isolated developer ecosystems to ensure the potential for large-scale applications built on blockchain. More specifically, the following research questions need to be addressed:
1)	What are the typical constraints found in various blockchain protocols?
2)	How to classify these constraints to find similarities between different platforms?
3)	What are currenty industry best practices as well as advances in research on cross-blockchain interoperability?

How do we unify this knowledge on how different blockchains operate and their governance models into a single framework for a functional IBC protocol?

## 3. Objectives
1.	Explore the Ethereum yellow paper<sup>[4]</sup>, EOS white paper<sup>[1]</sup>, and any additional resources with the purpose of understanding key steps that need to be taken in order to interface between the EOS and Ethereum protocols, with the goal of extending to more protocols in the future.
2.	Developing an SDK for deploying, executing and querying of various contracts. 
3.	Enabling developers in the EOSIO, Ethereum, and wider blockchain communities to use their preferred development platforms while leveraging the benefits of IBC.


## 4. Preliminary Literature Review

A preliminary literature review shows that the established method in past studies/products of linking blockchains is through the virtual machine (VM). For instance, using the Ethereum VM allows existing blockchains to connect and push transactions to the Ethereum blockchain. A good example of this is Hyper Ledger Fabric<sup>[2]</sup> from IBM and the Linux Foundation, which acts as an enterprise version of Ethereum. Building on top of existing VM's produces tremendous results, however, it is not easily scalable to additional blockchains quite yet. A similar product, LiquidLink has developed a second-layer solution connecting the public blockchains/smart contract platforms of EOS and Ethereum, claiming support in the future for greater blockchain connectivity, such as to Bitcoin<sup>[3]</sup>. A general solution to connect all the major blockchains seems to be impossible, but handling each major connection seems to be a feasible solution. The reason to connect certain blockchains like EOS to Ethereum is to get the efficiency of EOS to be used with Ethereum and allow for general-purpose dApp solutions that can push to multiple blockchains. The question of efficiency of the bridging process becomes extremely important as if implemented wrong can defeat its own purpose. This paper will take a look at the existing models and analyze which are more efficient and what truly is the best way to make these connections. This type of emerging research is growing rapidly which is evident by various bounties available for solutions to bridge the gap between various blockchains. The initial inspiration for this research project was the EOSIO smart contracts challenge issued by Block.One to find bridge EOS and Ethereum.

## 5. Methodology

The primary research method for this study is application and literature review. This study will be a step by step process starting off with mini-objectives. The first mini-objective would be to implement simple Smart Contracts for both the EOS.IO blockchain and the Ethereum blockchain. Next we must review the current processes of pushing transactions with the Ethereum Virtual Machine. From here, we can find ways to implement the EVM into an EOSIO C++ smart contract to invoke transactions on Ethereum that contains what we have outlined in our contract. Between each step and implementation, multiple tests must incurr to steer the code towards success. This project aims to be a multi-semester project.

## 6. References

1.	 “EOS.IO White Paper.” GitHub, Block.one, 
github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md. Accessed on 2 March 2020.
2.	 “Hyperledger Burrow.” Hyperledger, www.hyperledger.org/projects/hyperledger-burrow. Accessed on 2 March 2020.
3.	LiquidApps, liquidapps.io/liquid-link. Accessed on 2 March 2020.
4.	Wood, Gavin. ETHEREUM: A SECURE DECENTRALISED GENERALISED TRANSACTION LEDGER. ethereum.github.io. Accessed on 2 March 2020.
