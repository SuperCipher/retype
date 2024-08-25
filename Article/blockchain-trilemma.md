---
order: 100
icon: checklist
tags: [decentralization, security, Testability, Transparency, Standard]
---

# DAPP Gold Standard

## Security

1. Main net fork-ability
  1. feature to simulate future transaction on Main net without test net 
	 2. application shouldn't know if they're connect to Main net live or Main net fork
	 3. Single point of connectivity (application should strive to only require rpc form user wallet) maybe create a specific browser that block all conectivity and only expose rpc API
	 4. impersonate wallet (change to some one else address and interact with the contract on their behalf)
  5. Put common functionality in the wallet as much as possible. E.g. swap coin instead of each swap implement the same functional over and over in a slight difference way just call a wallet API for it or currency API

## Testability

1. No TESTNET!!! (Why ? dependency of the contract might not deploy)

## Transparency

1. Developer mode/ Audit mode/ transparency mode
2. On chain smart contract traceability to code base verification and discovery (smartcontract hash that link to a build artifact on GitHub)
3. Where the contract deploy (address)
4. Uncompressed unminified deuglified frontend (Solved commercialization first)
5. API transparency show what API front end is connected to and  ability to connect to self host opensource API serve
	1. e.g. opensource indexer
6. Standardization single source of dependency reuse dependency as much as possible to consolidate security resource to common share library and decrease variant between different application make it easier to vet the source code since most DAPP using the same library user only need to check the implementation of the library instead of the the library it self
7. Standardization of interface
8. Ability to change API endpoint or RPC endpoint
9. display compatibility status on different data base on different chain on different 
10. contractwallet detect different chain on different contract
start with problem
