---
order: 100
icon: checklist
tags: [decentralization, security, Testability, Transparency, Standard]
---

# Decentralization Gold Standard

Security
1. All Dapp must strive to rely only on the interface from wallet e.g. RPC, API

2. The wallet should have the ability to stub (replace) mainnet with fork mainnet enabling users to interact Dapp as if they were always on mainnet

3. Dapp should not know nor care if it is connected to fork mainnet or live mainnet

4. Wallet should have the ability to simulate transactions on fork mainnet before submitting transaction And have the UI compare and highlight the delta between the state of the wallet before and after submitting transaction e.g. Wallet balance and Token Ownership.

5. Dapp and Smart-contract should strive to use the same dependency for readability and consolidate testing and auditing efforts e.g. Use the same version of Ether.js v6.13.2 use the same ERC 721 standard

6. Dapp must not show nor rely on stale data
Testability

7. Wallet should have intuitive UI to [impersonate as other account](https://yos.io/2021/09/11/real-world-contract-development-forking-mainnet/#impersonating-as-other-accounts)

8. Dapp testing should limit the use of testnet as much as possible since they are not representative of the actual mainnet e.g. Compound Ethereum Sepolia Testnet doesn't have LINK contract deployed like Ethereum Mainnet

Transparency
9. Dapp must clearly disclose all contract addresses that Dapp interacts with on the current chain

10. Dapp must clearly disclose all API URLs that Dapp is relying on

11. Dapp must not be compressed minified, or uglified by the client

12. Dapp must clearly disclose links to all code repositories, assets, and artifact

Even though some of these are impractical at the moment we should try hard to live up to the decentralize promise

Co-author: Callum