# Hackathon's Overall User Story and Architecture
_Machu-Picchu_ models the existing manual risk-sharing practices among rural communities, but uses the blockchain and Earth Observation to scale globally. The approach is pragmatic, as done by field actors today: whatever is technically feasible and compatible with regulations is implemented, the rest is done manually. Therefore we need to make the distinction between the long-term (final?) User Story and the hackathon's User Story.
## Long term User Story
The long-term User Story is described in the [README of the Top-level Machu-Picchu](https://github.com/kvutien/Machu_Picchu_Top-Level/blob/master/README.md)
## Hackathon's User Story
The hackathon team will implement 3 dApps:
* contribution, used by the farmer or by the "enabler" (the NGO who supports the farmer) on behalf of the farmer
* damage assessment, used by the "watcher". This dApp is supported by an Earth Observation app, already developed outside the Hackathon
* compensation and account explorer, used by the "enabler" and by the supervision authority

The hackathon will use a single private blockchain. In the future, each dApp will use a distinct blockchain. The different blockchains will interoperate via Cosmos, or PolkaDot, or equivalent.
* The hackathon will use ETH. Depending on available time, we'll implement an ERC-20 token to trace the contribution and compensation, an ERC-720 token to trace the "merit" of the farmers, and an ERC-20 token to trace the "reputation" of the watchers.
* Depending on available time, we'll implement an IPFS storage of more farmers data to prefigure the public service of farmers data.

Else these bonuses will be part of the larger development plan of _Machu-Picchu_

![Image](https://github.com/Machu-Pichu/Top-Level/blob/master/Bootcamp/ETHOnline/20200922%20Hackathon-overall%20userstory.png)

## [Back to the Hackathon root README](https://github.com/Machu-Pichu/Top-Level/blob/master/Bootcamp/ETHOnline/README.md)
