# HODLAO

HODLAO is a 8/13 multisig holding HODL

![HODL](https://ordin-delta.vercel.app/content/890e6644eb08f0c9bfe747c4bd8302734e9f9b9562fa4063681c3a988a89a52ai0)

[Bitcoin Shroom 86 (inscription #722)](https://ordinals.com/inscription/890e6644eb08f0c9bfe747c4bd8302734e9f9b9562fa4063681c3a988a89a52ai0)

## Shroomtoshi's gift

Shroomtoshi graciously left some gifts behind before going full Satoshi. He asked his custodians (dazza9, Kenny, richwake) to deliver Shrooms #85 (Number Go Up) and #86 (HODL) to 25 people he named. He proposed distributing the gifts in multisig wallets. NGU never touched the multisig, the group asked the custodians to list the shroom for sale and distribute the proceeds between members. NGU sold for 1.6 BTC on 30 May 2024. 

The 13 original members of the HODL group voted to honor Shroomtoshi's wish and set up the multisig. 

## Current Holders

- vinimok
- techcapo
- Simo
- pain
- ticklesnarf
- HAALAND
- EO
- DEADPOLAROID
- c0ffeeplease
- Beni
- Bard
- ModifyGalaxy
- OYOGZ

## Buyouts

Each member holds a claim on an equal share of 1/13th of the HODL artifact.

### Can I be part of HODLAO?

Yes! Every HODLAO member has a price point for selling their share of the multisig, you just have to find the lowest one and initiate a buyout.

### How to perform a buyout?

1. The seller and the buyer agrees on a sale price
1. The buyer transfers the sale price +2% transaction fee to the HODLAO multisig. The fee covers on-chain fees + compensates HODLAO members for the following work
1. The buyer shares their public key with HODLAO (master fingerprint, derivation, xpub)
1. HODLAO sets up a new multisig, replacing the seller's slot with the buyer's
1. HODLAO transfers HODL (and other holdings) to the new multisig
1. HODLAO transfers the sale price to the seller

## Liquidation

In case a simple majority of the HODLAO members (7 of 13) decide to list the shroom for sale, HODLAO will transfer HODL to a trusted third party (Kenny has graciously agreed to help HODLAO with this) who will list the shroom for sale and will split the proceeds equally between the 13 holders.

## Technical Considerations

Here are some considerations we have discussed in detail (12 angry men style) while setting up HODLAO.

### Why 8/13?

Partly it's a trade-off between risk of loss vs risk of theft. The higher the threshold, the easier it is to lose access to the shroom. In a 11/13 multisig three people lose their keys and it's game over. With lower thresholds it's easier for an attacker to steal the shroom. In a 4/13 multisig, an attacker only needs to hack 4 members. 

The main consideration, though, is how many people need to agree to make decisions. If the threshold is lower than 50%, a minority of the holders can act against the wishes of the majority, so let's not do that. A simple majority (7/13) can make decisions faster but might leave a relatively large minority unhappy. If we require a super-majority of the group to agree (eg. 10/13), a relatively small minority can block decisions that would make most people happy.

### Collusion

The kind of majority decision that would make minority holders very unhappy, is if a majority of holders collude against the others to lock them out. In a 3/13 multisig it would only take three people to go behind the other's back and send the shroom out to their own 3/3. That's an easy 4x. With an 8/13 multisig, though, you need secret coordination between 8 members which sounds pretty hard. Also the upside is lower because there are more attackers and fewer victims.

### Sybil Protection

Collusion can be pulled off easier if there are sybil signers on the multisig (ie. one person controls multiple signers). To make sure this doesn't happen, HODLAO only accepts members with estabilished identities in the Ordinals ecosystem.


