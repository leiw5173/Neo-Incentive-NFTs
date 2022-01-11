# Neo Incentive NFTs

This project shows the whole structure of Neo NFT incentive system. We utilize a Demo to develop to MVP to validate the feasibility of this system. This proposal includes several terms:

- Tutorial example
- Tasks based on tutorial
- NFT series based on Tasks
- Claim method
- Incentive system
- Feedback and improvement ways

## Tutorial example

We will use [A Demo of Neo N3 Core Components dApp](https://github.com/leiw5173/A-Demo-of-Neo-N3-Core-Components-dApp) as tutorial example. The dApp built in it is designed for the following usage scenario:

_Oliver_ is looking for an accommodation. To make the reservation, the dApp requires Oliver to identify himself as an individual. Fortunately for Oliver, his Government has recently decided to implement a digital version of the national ID with the help of the Neo blockchain. Oliver needs to apply for a digital ID by presenting his physical ID to a local authority. At the moment of booking, Oliver can identify himself to the dApp with his digital Passport. Once the identity is verified, the dApp issues an access key credential to Oliver. Among the other things, the access key contains a code that gives access to an automatic door to enter the accommodation. When Oliver arrives at his accommodation, he displays the booking confirmation to the Door Lock, an automatic door with a IoT device capable to verify Oliver's claim. Once the booking is verified, Oliver is finally able to enter the accommodation.

In this tutorial, it describes an interactive demo to demonstrate the functionality and usage of NeoID (Neo Identity) as well as Neo Oracle and NeoFS (Neo File Storage) with an example use case.

In this tutorial, the structure is shown as below:

- Environment setting
- Smart contract writing
  - Basic smart contract knowledge
  - Oracle integration
- Smart contract compiling, deployment, Invokation, and testing
- Neo dApp and smart contract interaction
- NeoID integration
- NeoFS integration
- Demo operation

According to this structure, we will seperate the tutorial into 8 courses. For each course, it will last around 60 minutes.

## Tasks based on tutorial

The tasks are designed according to the structure of tutorial. 7 serieses of tasks will be set to test the first 7 learning processes. The last one demonstrate the whole procedure of this dapp. The serieses of tasks are shown as below:

- Set environment to fetch the data of Neo testnet
- Deploy a smart contract on N3 testnet
- Update the smart contract with Oracle integration
- Invoke and debug a smart contract with [NeoExpress and NeoTrace](https://github.com/neo-project/neo-express)
- Develop a frontend page to interact with smart contract
- Update the smart contract and frontend page to integrate with NeoID
- Update the smart contract and frontend page to integrate with NeoFS

After the tasks finished by learners, we need methods to check their degrees of different tasks' completion. The method can be set as below:

- Submit the screenshot of the fetched data
- Submit the contract hash
- Submit the contract hash after update
- Submit the NeoExpress file and NeoTrace file
- Submit the website address
- Submit the contract hash and frontend page after update
- Submit the contract hash and frontend page after update

In this segment, we set up the tasks and checking point and make sure the learners get familiar with the whole development process of Neo N3.

## NFT series based on tasks

There are two kinds of Incentive NFTs in this system. One is for contributors of this repo. Another is for learners who complete the tasks.

- `Contributor NFT`: We will deploy a Non-tradable NFT smart contract to reward the contributors who make their efforts on this system.
- `Learners NFT`: We will deploy four Non-tradable NFT smart contract to reward learners who complete the different levels of tasks.
  - `Junior Learner`: The learners who are able to deploy smart contract on testnet can get this NFT
  - `Middle Learner`: The learners who are able to create website and interact with smart contract can get this NFT.
  - `Senior Learner`: The learners who are able to integrate NeoID, NeoFS, and Oracle into the smart contract can get this NFT.
  - `Leader`: The developers who run their own projects on Neo N3 mainnet can get this NFT.

The whole NFT serieses are shown above. All the NFTs are distributed on the Neo N3 mainnet and will be endowed certain incentive according to the NFT series.

## Claim method

The claim method is shown as below.

- If you have committed any changes that were merged into this repo, you have a `Contributor NFT` waiting!
- If you have completed certain tasks and submitted the related proofs, you have one of `Learners NFT`series waiting!
- You can claim your NFTs in the [![Discord](https://img.shields.io/discord/382937847893590016?label=Neo%20Smart%20Economy)](https://discord.gg/xqAXAECWsT)
- A member of our team will verify the request and DM you with a personalized link to claim your own fresh minted NFTs.
- To help with verification we request all the applicants connect their GitHub account with their Discord account (Discord > settings > Connections > GitHub).
- If you haven't learned yet and would like to earn a `Learners NFT` to show your enthusiasm to the Neo N3 space, head over to [Developer Portal](https://kind-meadow-0e3193d1e.azurestaticapps.net/) to start learning!
- If you haven't contribute yet and would lke to earn a `Contributor NFT` to show your loyalty to the Neo N3 space, head over to [Issue](https://github.com/leiw5173/Neo-Incentive-NFTs/issues) tab to get start.

## Incentive system

The incentive is the key to motivating the developers and contributors to build the whole page of this developer ecosystem. And we need two different incentive systems to award developers and contributors.

The people with different NFTs can get some privileges:

- Exclusive role and badge on Discord
- Exclusive access to channels on Discord
- Exclusive new perks in the future

## Feedback and improvement ways
