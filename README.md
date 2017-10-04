# About Antz
Open Source Blockchain-Enabled B2B Service Procurement Marketplace

Welcome to Antz. We are a Singapore-based project that is seeking to build an open-source, blockchain-enabled B2B marketplace to directly connect buyers and sellers of business services. We believe that by eliminating the use of intermediaries, our solution will help make procurement of services more cost-effective for buyers, will ensuring fair and equitable opportunities for suppliers. 

## What We Hope to Achieve
(1) Provide a direct connection between buyers and sellers of businesses services without a need for intermediaries.

(2) Build a robust and reliable open-source, permissions-free B2B platform for transactions.

(3) Leverage on blockchain technology for data exchange and creation/validation of smart contracts in transactions.

(4) Encourage innovation and collaboration where all participants are engaged in the development of the platform via an open-consensus model.

## Design Overview
Note: Design and architecture of the main Antz platform may be updated in actual development. 

We see the platform as comprising 4 main components or modules:

(1) User Registration: Allows for Buyers and Sellers of BPS to register as users on the platform, and data is written to a backend MySQL database.

(2) Search & Match: Allows for Buyers and Sellers to find each other; includes filters that include relevance, new listings, location, pricing, customer reviews etc.

(3) P2P Funds Transfer: P2P funds transfers facilitated through the exchange of Nectar, our ERC-20 token; Nectar will also allow for easy conversions into fiat currencies for users who do not hold Nectar tokens.

(4) Feedback Mechanism: Communications between Buyers and Sellers via direct messaging functions, chats etc for clarifications; customer ratings and feedback submissions to rate and comment on both buyers and sellers. 

We also plan to incorporate functionalities where buyers can submit customised requests for services not listed on the platform, and for suppliers to bid for these requests using an automated e-bidding system. This feature may be introduced in Version 1, or later on as we develop other functionalities to the platform.


## Built With
Antz is built primarily on Ethereum. As such, we anticipate a lot of work to be done via the Ethereum Virtual Machine (EVM). Ethereum Virtual Machines have been implemented in C++, Go, Haskell, Java, Javascript, Python, Ruby, Rust, and WebAssembly.

Smart Contracts will be based on [Solidity](https://solidity.readthedocs.io/en/develop/), a language library with similarities to C and JavaScript and [Serpent](https://github.com/ethereum/wiki/wiki/Serpent).

## Contributing to the Antz Project
Please read [CONTRIBUTING.md](https://github.com/AntzProject/Platform/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
We use [SemVer](http://semver.org/) for versioning. 

## License
This project is licensed under the Apache 2.0 License - see the [License](https://github.com/AntzProject/B2B-Platform-Build/blob/master/LICENSE) for details.
