---
sidebar_position: 2
---

# Job Listing
### Who can enlist jobs?
Although it is possible to enlist job posts without having the membership, as a member you can also accumulate any generated revenue through our smart contracts.

HonestWork is committed to decentralization and it's quite possible we will have a token airdrop in the future that will be based on revenue and activity. Further, we plan on bringing features like `Projects` to serve multi-role users.

### Job listings & agreements

Job listing and on-chain agreements are detached systems. Anyone can link a their job id to the deal. This is important because it enables the freelancer to show this job on their `Job History`. 

```javascript
function createDeal(
        ...
        uint256 _recruiterNFTId,
        uint256 _jobId,
        bytes memory _signature
    ) external returns (uint256)
```

Once a job post has been attached to a deal. It is consumed by the indexer and gets `Taken` status on the platform.
