---
sidebar_position: 1
---

# Creators 

Creators are holders of **HonestWork Genesis NFT** that unlocks access to HonestWork features and benefits. 

HonestWork Genesis NFTs also record your revenue on the blockchain, enabling you to earn future airdrops based on your performance.

Visit [honestwork.app/mint](https://honestwork.app/mint) to mint a new one or upgrade existing 😎

## Platform utilities

Genesis tiers provide different levels of utility on the platform. Frequent users or polymaths will prefer higher tiers to display more variety of skills.

In the table below, you can see the limits of each tier. In short words;
* `Total Skills` is the number of skills member can display,
* `Applications/day` is the number of job applications a member can make in a span of 24hrs,
* `Total referrals` is the amount of referrals you get by purchasing a genesis NFT.

| Genesis Tier   | Total Skills         | Applications/day  | Total Referrals     |
| -------------- | -------------------- | ----------------- | ------------------- |
| `Tier I`       | 3                    | 2                 | 2                   |
| `Tier II`      | 6                    | 3                 | 3                   |
| `Tier III`     | 8                    | 5                 | 4                   |


## Revenue accumulation

HonestWork indexer tracks all revenue generation via contracts. Aggregated values are reflected on NFT metadata. This
mechanic exists to **_capture value created on the platform_** and correlate it with an **_on-chain asset_** and help us design an airdrop campaign on our way to complete decentralization.

Example metadata of a tier 3 member who made total of $5000 on HonestWork;
```json title="honestwork-genesis-nft/metadata"
{
 ...
 "attributes": [
  {
   "trait_type": "Tier",
   "value": 3,
   "max_value": 3
  },
  {
   "trait_type": "Gross Revenue",
   "value": 5000
  },
  {
   "trait_type": "Revenue Tier",
   "value": "$1000 - $10000"
  }
 ]
}
```


## AI generated visuals
Genesis NFT is the first on-chain asset of HonestWork. It's deployed on Ethereum Mainnet and verified. 

NFT visuals are generated with same exact prompt but different seeds on MidJourney. 
Only 1000 unique visuals are generated so far since it's not clear if we will introduce a new membership model in the future and hardcap this collection.

Below is a selection of NFT's that are not yet minted. See the genesis collection on [opensea.io/honestwork-genesis](https://opensea.io/collection/honestwork-genesis "Genesis Collection").

![](https://honestwork-userfiles.fra1.cdn.digitaloceanspaces.com/docs_nft.png)

