## 1. Membership

The current membership protocol is tailored to the OpenCollective use case.

1. Anyone can become a member, the only requirement is to contribute a Membership Fee, after which a member is considered *active*.
2. Contributions that count towards the Membership Fee can be made from monthly recurring donations. Other possiblities will be added later.
3. For contributions through recurring monthly donations:
   1. After the first donation on OpenCollective, the member will be notified to suggest linking their SSB-ID with their OpenCollective account. Every subsequent donation will receive an automatic [````membership-confirmation````](../messages.md).
4. The member becomes *inactive* after the ````expiration-date```` of the [````membership-confirmation````](../messages.md).
5. The Membership Fee is non-refundable.

## Optional rules for handling possible Sybil attacks

Sybil attack may undermine democratic decision making by enabling physical persons with sufficient money multiple votes. This can be mitigated with the following rules:

1. A member ID must have been present in at least 20 messages from at least 4 distinct active members to be considered for membership.

## Additional Explanations

Assocoins may have been obtained by making a one-time donation or having received them from another member.

An explicit confirmation needs to be made by the Treasurer because we cannot rely on the message time supplied by the member message. The later could have been moved to the future or the past, voluntarily or by accident. We avoid by trusting the Treasurer's confirmation time.

An association is defined by a Message ID to make it independent of the particular members of the association.

Point 3.1 will eventually be automated by allowing the donation to be linked with an SSB-ID on the OpenCollective platform. In the meantime, this will require a manual step from the user.




