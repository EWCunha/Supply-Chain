# Supply Chain Simplified Dapp
This Dapp was developed with the Truffle framework. Two Smart Contracts were programmed: one for managing the items and another for creating those items. When an item is created, a cost value is assigned to it and an independent Smart Contract is created for each item. This means that each item has its own independent address, which facilitates the payment from the customers. I used the Truffle React box and I programmed event triggers to warn the users about states of the items in the supply chain (Created, Paid, Delivered) for automated dispatch.

## Real World Use Cases
- Can be part of a supply-chain solution
- Automated Dispatch upon payment
- Payment collection without middlemen

## Functionality
The supply chain project fucntionalities are depicted in the following flowchart.


## What I Learned
- Showcase event triggers
- The low-level function `address.call.value()()`
- The Workflow with Truffle
- Unit Testing with Truffle
- Events in HTML
