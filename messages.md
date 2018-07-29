# Message Templates

## 1. Membership

Confirmation:
````
{
    type: 'association/membership-confirmation',
    version: VERSION-NB,
    association: SSB-MSG-ID, 
    member: SSB-ID,
    amount: Number,
    currency: String,
    confirmation-date: Date,
    expiration-date: Date 
}
````

Termination:
````
{
    type: 'association/membership-termination',
    version: VERSION-NB,
    confirmation-message: SSB-MSG-ID,
    termination-date: Date
}
````

## 2. Finances

### 2.1 Assocoin

#### Creation Schema

#### Transfer Schema

## 4. Governance

### Role Proposal Schema

Role: Treasurer or President

### Decision Schema

### Constitution Change Schema

### Dissolution Proposal Schema

