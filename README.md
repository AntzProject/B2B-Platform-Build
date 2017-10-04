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

The DAPP will thus consist of the following layers:
(1) Server (NodeJS / Web3) that manages communication between the client apps and the blockchain
(2) Smart Contracts (Solidity, compiled into EVM Byte Code, as well as a corresponding Application Binary Interface (ABI) that is derived from the Solidity source code and which tells other languages how to interact with the compiled contracts)
(3) UI (Javascript, as well as, optionally, native languages such as Swift, or Java)


## Built With
Antz is built primarily on Ethereum. As such, we plan to build smart contracts with the following:

(1) GoLang (The Go Programming language is needed to run Geth)

(2) Geth (The Ethereum system implemented in Go)
a local closed testnet (run by invoking Geth), and a shared testnet running on a cheap cloud server
NodeJS, and/or

(3) Python3
(4) Redux / React for the front end

(5) a text editor such as Atom, Sublime, or Textmate 

(6) custom scripts to compile Solidity, generate the Binary files and ABIs as needed, and deploy the compiled contracts to a nominated blockchain (local or shared testnets, or the public blockchain)


## Contributing to the Antz Project
Please read [CONTRIBUTING.md](https://github.com/AntzProject/Platform/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
We use [SemVer](http://semver.org/) for versioning. 

## License
This project is licensed under the Apache 2.0 License - see the [License](https://github.com/AntzProject/B2B-Platform-Build/blob/master/LICENSE) for details.
