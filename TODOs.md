## What are we going to do? 

#### Cleanup APIs - @georgeartem 
  - [ ] Refresh old PR and apply to private endpoints #17
  - [ ] Add appropriate JSON (connect) output to invoice api
  - [ ] Add invoice reading endpoint with QRcode 
  - [ ] Move to a sub-package `webapi.go` getting big

  
#### Auto-reconciliation feature - @georgeartem
  - [ ] Add account 'settings' to DB
  - [ ] Add reconciliation setting per account (where/when to auto send Doge payments)
  - [ ] Add reconciliation setting per invoice (overrides account setting)
  - [ ] Write an Accountant service to manage automatic payments etc.
  
#### Message broker - TBD
  - [ ] Build AMQP connector for external event integration
  - [ ] Build logger connector for debugging msg bus
  - [ ] Build message bus system

#### Transaction Broker - TBD
  - [ ] Detect tip reorgs (what happens?) 
  - [ ] Connect to core ZMQ channels and recieve blocks

#### Wallet logic - TBD
  - [ ] Implement balance querying API (total vs available?)
  - [ ] Implement unspent UTXO tracking for payments

#### Write New Implementation Documentation 
