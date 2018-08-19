# contracts
Smart Contracts (Solidity) providing marketplace functionality

This repository contains an early version of the contract(s) Sample is in the process of writing in order to build a data marketplace. The basic structure, as of this writing, is one script (mvp.sol) which contains a wrapper contract (SampleTypes), and three contracts:

1) Entity: Entities are the individual users on the platform. The Entity contract establishes different classes of users, and establishes their permissions.
2) Datablock: Datablocks are blockchain analogs to data stored in on a storage platform. Each piece of data for sale in the marketplace has its own Datablock on the blockchain. The Datablock contract allows consumers to purchase access to the data, and has lockup and disputation features.
3) Partnership: Research is done in groups and funded by groups, not individuals. Partnerships are the representation of collaboration, which allows recvenue from monetization to be distributed among all contributing and funding members by weight.
