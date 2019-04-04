# Request funding app

UX prototype: [https://www.figma.com/proto/dT9yEXPkPNT1WiwLG5gVayRm/The-Commons-Stack?node-id=9%3A2&scaling=scale-down](https://www.figma.com/proto/dT9yEXPkPNT1WiwLG5gVayRm/The-Commons-Stack?node-id=9%3A2&scaling=scale-down)

## User Stories / Fund Requester \(Farmer\)

### Sign in or create a Ethereum account on Metamask/Frame/Mobile

… this should be glossed over in the narrative... but its needed by every user in the system

### Use Giveth to Request Donations

* Create a Campaign on Giveth (Done)
  * Pic
  * Title, description \(e.g. Plant trees in Indonesia\)
  * Reviewer
  * Sign a transaction submitting the Campaign data to IPFS and putting the Hashes on chain
  * The signer of this tx is the Campaign Manager 
  * The Campaign can receive crypto donations from any person, DAO, Commons, etc

* Create Milestone on Giveth (Done)
  * Pic
  * Title, description \(e.g. Plant 10 Oaks by 01.06.19\)
  * Amount requested \(Fixed amount, e.g. 150 xDAI\)
  * Reviewer
  * Sign a transaction submitting the Milestone data to IPFS and putting the Hashes on chain
  * If the Milestone was created by the Campaign manager, it shows up right away
  * If the Milestone came from the community, it must be approved by the Campaign Manager
  * The Milestone can receive crypto donations from any person, DAO, Commons, etc


### Nominate Milestone for Funding by the Commons 

* Choose a Giveth Milestone to Nominate and copy the URL
  * Note: The milestone must be raising funds in xDAI and have a cap
* Go to the conviction voting interface and click the Nominate button
* Paste the URL into the input box, and make a comment if you want
* X number of tokens are required to stake behind a milestone to nominate it 
* As long as at least that number of tokens is staked by the nominator or someone else, the milestone will remain visible, other wise it will be removed
* The total amount of xDAI requested by the milestone and the amount of xDAI that the allocated conviction power represents is displayed to the Commons (by team 2) 
* If somebody donates to the Milestone directly, the total amount of xDAI requested from the Commons is reduced

### Track progress of a Milestone (not done yet)

* Have a Giveth profile  
* Go to the Milestone's URL in Giveth
* Request to follow the Milestone
* Get email notification when my Milestone got funded
* See funds before the transfer
  * 50 xDAI from external donors
  * 100 xDAI from the Commons (tho this will turn into tokens)

### Redeem funds after approval

* If it triggers I get 50 xDAI and some # of Commons token \(the equivalent of 100 xDAI\)
* The user gets directed to Team 1 UI for bonding curve, so he can burn tokens for xDAI.
* If the user chooses to burn their tokens, they would get 98 xDAI and 2 xDAI would go to the Commons to be donated to other causes.
* The only way xDAI exits the system is through the token bonding curve (Team 1)



