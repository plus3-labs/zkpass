## Intro To ZKPass
`ZKPass` is a cryptographic authenticator based on Mina’s Zero Knowledge Proof and acts as a user’s pass to the cryptographic world. Distinguish features are as below:
1) `ZKPass` transforms wallet addresses into friendly, readable and easy-to-remember identifiers similar to the Ethereum ENS, and gives you full control over your encrypted identity without the fear of losing your private key through an unmanaged email social recovery solution.
2) Through Mina Protocol’s the unique ZK Oracle zero-knowledge proof solution, `ZKPass` can bring in real-world attributes such as the user’s real and valid identity tag according to the user’s wishes, while maintaining privacy, allowing users to bind multiple chain addresses and verify their social accounts to make their encrypted identity more valuable. At the same time, through these real and valid off-chain data and users’ on-chain behaviour data to form the users verifiable reputation, the users’ encrypted identity formed based on ZKPass can ensure the uniqueness of the user and be integrated by all Snapps in the ecosystem through SSO services, which can be used to avoid Bots (e.g NFT or airdrop campaign) and achieve more valuable voting governance to maintain fairness users will also get more potential airdrop opportunities and additional incentives from the Dapp.
3) Users can use ZKPass without revealing their external wallet address, which will better protect their privacy through the separation of authorisation and asset control identity keys. We also plan to introduce a contract wallet feature to support a certain level of privacy for transactions.

As you can see, ZKPass is such a big project with several features. Thus we seperate it into multiple modules: Wallet Based on Smart Contract, DID module ([MNS](https://github.com/plus3-labs/mns-frontend) (under development yet)), Shielded Transfer module ([Shadow](https://github.com/plus3-labs/shadow) (under development yet)) and so on.

## High level user view
![image](https://user-images.githubusercontent.com/92623877/174844091-8868b5d1-fac2-4f0f-bc4a-66ebfbe49ef3.png)

## Integration
Based on the features above, zkpass is able to be integrated into all snapps as their ID component. You know, ID is really important for some activities of snapps, like avoiding bots in token airdrop or NFT application for a DAO.
![image](https://user-images.githubusercontent.com/92623877/174844358-0347e8aa-cbe3-4a7d-958c-023a6468704e.png)
