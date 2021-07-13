# Supply Chain Simplified Dapp
This Dapp was developed with the Truffle framework. Two Smart Contracts were programmed: one for managing the items and another for creating those items. When an item is created, a cost value is assigned to it and an independent Smart Contract is created for each item. This means that each item has its own independent address, which facilitates the payment from the customers. I used the Truffle React box and I programmed event triggers to warn the users about states of the items in the supply chain (Created, Paid, Delivered) for automated dispatch.

## Real World Use Cases
- Can be part of a supply chain solution.
- Automated dispatch upon payment.
- Payment collection without middlemen.

## Functionality
The supply chain project fucntionalities are depicted in the following flowchart.
![Supply Chain Functionality](https://github.com/EWCunha/Supply-Chain/blob/main/Supply%20Chain%20Structure.png)

As a new item is created, it is tracked via the blockchain with its own Smart Contract, which means that this created item has its own address. When a customer pays the requested item, it triggers events to the warehouse to dispatch the item and to the owner to allow withdrawal of the paid amount. The state from "Paid" to "Delivered" of the items can be changed only by the owner of the Smart Contract.

## What I Learned
- Showcase event triggers
- The low-level function `address.call.value()()`
- The Workflow with Truffle
- Unit Testing with Truffle
- Events in HTML
