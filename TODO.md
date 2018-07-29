# TODO

## v0.2 (Core Membership)
### General
- [x] Rework general presentation
- [x] Add a license

### Crypto-donations
- [x] Handle donations through Open Collective
- [ ] Clarify how to mint a new assotoken
- [ ] Clarify how to transfer funds between active members
- [ ] Clarify how to destroy the tokens by using them in an SSB association
- [ ] Clarify that the tokens may ultimately only be used for the purpose of paying membership fees 
- [ ] Clarify the relationship between IASU and ACCESS: handle the donations through ACCESS
- [ ] Think about invariants that need to be maintained to trust the Treasurer confirmation times

### Messaging Protocol
- [ ] Mandate the use of the #iasu channel

### Membership Protocol
- [ ] Add the requirement that the president needs to follow-back an active member and the members need to follow the president
- [ ] Handle a possible sybil attack in which someone may create multiple accounts to obtain more than one vote during decisions processes (we would have one vote per "share" of membership rather than one vote per person). Possible solution:
    - Add two additional requirements for becoming a member:
      - being followed by at least one other active members;
      - having a minimum number of messages in the feed.
      for two reasons:  
      - it reduces the possibility of a Sybil attack, in which a single user creates
      multiple SSB IDs and pays the membership multiple times to have multiple votes,
      because

## v0.3 (Add Governance)
### Voting Protocol
- [ ] Have the president create an explicit message for each possibility for voting

### Funding Protocol
- [ ] Rework to ensure spreading of funds throughout the year
- [ ] Add a time limit after which funds are transferred to the SSBC Open Collective Account

### Governance Protocol
- [ ] Clarify that the president account needs to change every mandate
- [ ] Clarify when elections are made

## v0.4 (Add Bitcoin support)
### Crypto-donations
- [ ] Handle donations through Bitcoins
- [ ] Clarify how membership fees augment
- [ ] Handle reimbursement

#### Bitcoin handling
- [ ] Rework Bitcoin process to use the following:

1. Send treasurer an invoice address request
2. Treasurer sends a unique address for that member
3. Member pays fees to the address
4. Treasurer sends the funds to the association’s address/account
      
- [ ] Clarify that the values of Bitcoin funds may be reach the threshold because Bitcoin's value has appreciated

### Membership Protocol
- [ ] Handle cases of concurrent use of the same transaction


## v1.0 (Release)

### General
- [ ] Add a public http website to advertise the existence of the association to non-SSB users
