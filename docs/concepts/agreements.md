---
sidebar_position: 2
---

# Agreements

## Flexible Payment System
Payments are facilitated through `Escrow` contract. After a conversation has started an agreement can be created following these 3 steps;
1. Recruiter creates an agreement offer
2. Creator accepts and signs the agreement parameters
3. Recruiter takes the signature and executes the agreement on-chain.

During execution; total amount is transferred from the recruiter to the contract but only the downpayment amount is unlocked. 

After the initial transaction, a recruiter can follow with any amount of unlocks until total amount is unlocked. Every time a recruiter unlocks a portion, they also rate the creator. In a similar manner, during every claim a creator rates the recruiter.

Weight averaged aggregating ratings are displayed on the platform and used primarily for reputation.

## Dispute Resolution
Although HonestWork tries to ensure every deal goes smoothly but that's not always the case. That's why we use [XMTP](https://xmtp.org) (Extensible Message Transport Protocol) which is an open protocol, network, and standards for secure, private web3 messaging.

With XMTP we can enable HonestWork DAO to essentially become an official court for the platform to aid dispute resolution. All the agreement history and provable message history from XMTP will provide the proof needed for better judgement from DAO.
