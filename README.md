# Voting-DApp

The problem with creating a web based (client - server architecture) voting application is that the votes can be changed in the database because the server,
or we should say one entity has the control over it, as well as the code.

So who ever has access to the server can manipulate the voting outcome.

We want to ensure that every vote is counted and counted only once and that the candidate with most votes will actually be the winner.

How does the blockchain solve these problems?

The data is decentralized, destributed among the nodes operating on the blockchain.

Every node has a copy of all the data that is shared across the blockchain, all this data is devided in blocks, and all the blocks are chained together therefore
crating the blockchain.

So for an action (for example sending my vote to candidate number 1) to be executed on the blockchain network, it needs to be approved by enough different nodes on the
network, just enough to make a consensus about the validity of the action, once the action is approved and a bunch of nodes agree that it is valid, the action is
permanently stored in the data, that every node on the network has a copy of and updates it regularry.

This is how the security and the validity of the votes remains true, because it is not controlled or owned by any single entity, it is not replacable or deletable.

This is why a DApp is a much better solution.


