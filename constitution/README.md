# Name: International Association of SSB Users (IASU)

Purpose: Democratically fund (some of) the next ssbc-grants. 

version: 0.2 (WIP)

The constitution is organized in separate modules to favor reuse and adaptation
in various contexts:
* [Membership](./membership): This specifies how members join and leave. It ties it to a financial contribution to support the association.
* [Governance](./governance): This specifies how the association is managed.

## 0. Definitions

President: ````SSB-ID````
Treasurer: ````SSB-ID````
Mandate Duration: 12 months or 12 rounds of funding, whichever comes first
SSB-Native Association (SNA): IASU
Channel: #iasu
Membership Fee: $20 USD 
Recognized National Associations (RNA): 
- ACCESS (https://assoaccess.fr)

Throughout the rest of this document the left part of the definitions above are used as place-holders for the values on the right part. Ex: The Channel refers to #iasu.

### Assocoin

An Assocoin is an SSB-native crypto-currency based on donations to associations. 

An Assocoin is minted by making a donation to an SNA using an external crypto-currency, such as Bitcoin, or by making a donation to an RNA using their corresponding national currency. The creation of the Assocoin is recorded on the feed of the current Treasurer of the association and includes:
- a Proof-of-Donation, either in the form of an existing crypto-currency transaction ID or as a promise from the RNA to provide the equivalent funds for pre-defined purposes;
- the amount of the donation;
- the currency of the donation;
- the recipient SSB ID.

The latest recipient of an Assocoin can transfer it to another Active Member by creating a transfer message on their SSB feed including:
- the amount of the transfer;
- the recipient SSB ID.

The latest recipient of an Assocoin may also redeem its underlying value by transferring it back to the original issuing association with a redeeming message on their SSB feed including:
- the amount redeemed;
- a proof-of-redeemability, e.g. the SSB message that indicates an allocation decision including the recipient ID or a previous transfer immediately coming from the Treasurer of the SNA.

