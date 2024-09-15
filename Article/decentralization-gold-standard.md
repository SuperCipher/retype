---
order: 100
icon: checklist
tags: [decentralization, security, Testability, Transparency, Standard]
---

# Decentralization Gold Standard

Security
1. All Dapp must strive to rely only on the interface from wallet e.g. RPC, API

2. The wallet should have the ability to stub (replace) mainnet with fork mainnet  enable users interact to Dapp as if they were always on mainnet

3. Dapp should not know nor care if it is connected to fork mainnet or live mainnet

4. Wallet should have the ability to simulate transaction on fork mainnet before submit transaction And have the UI compare and highlight the delta between state of the wallet before and after submiting transaction e.g. Wallet balance, Token Ownership.

5. Dapp and Smartcontract should strive to use the same dependency for readability and consolidate testing and auditing effort e.g. Use the same version of Ether.js v6.13.2 use the same ERC 721 standard

6. Dapp must not show nor rely on stale data

Testability

6. Wallet should have intuitive UI to [impersonate as other account](https://yos.io/2021/09/11/real-world-contract-development-forking-mainnet/#impersonating-as-other-accounts)

7. Dapp testing should limit the use of testnet as much as possible since they are not representative of the actual mainnet e.g. Compound Ethereum Sepolia Testnet doesn't have LINK contract deployed like Ethereum Mainnet

Transparency

8. Dapp must clearly disclose all contract addresses that Dapp interacts with on the current chain

9. Dapp must clearly disclose all API URL that Dapp is relying on

10. Dapp must not be compressed minified uglified the client

11. Dapp must clearly disclose links to all code repositories, assets and artifact

Event though some of these are impractical at the moment we should try hard to live up to the decentralise promise

Co author: Callum
