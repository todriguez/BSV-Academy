# Chapter 1 - Assessment 3

_Students must receive a score of 25/27 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers._&#x53;tudents must receive a score of 25/27 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers.

1. When a node finds a proof-of-work, what must it immediately do?

Broadcast the block to all nodes.  ✓

Have it verified by the Pool Miner.&#x20;

Claim the block reward.&#x20;

Add the block to the chain and begin working on the next block.&#x20;

1. Why should a node propagate it’s proof-of-work solution to every other node as quickly as possible?

To prevent any attempts by a competing node to start working on a new block before it.&#x20;

To minimize the chance that another node propagates a competing block to the network.  ✓

To prove it is a node.&#x20;

All of the above&#x20;

1. What is it called when two competing blocks, both with valid proof-of-work solutions are propagated to the network?

An orphan race.  ✓

A 51% attack.&#x20;

A hard fork.&#x20;

An orphan block.&#x20;

1. What does a block consist of?

The complete list of transactions, the transaction fees, and the block reward.&#x20;

All of the transactions in the Merkle Tree plus the block header.  ✓

The complete history of all the transactions contained within.&#x20;

A Merkle Tree and a difficulty puzzle.&#x20;

1. What do valid blocks represent?

An incorruptible record of valid transactions.&#x20;

A proof of existence for all the transactions contained within them.&#x20;

A timestamp.&#x20;

All of the above.  ✓

1. Which is a correct description of a chain of blocks?

A set of chronologically ordered timestamps.  ✓

A ledger.&#x20;

A set of chained transactions leading back to the genesis block.&#x20;

The Blockchain.&#x20;

1. Which of these is true?

Proof of work gives the network an ideal method to control block timing.  ✓

Proof-of-work offers a superior method for nodes to identify each other.  ✓

Proof-of-work requires an investment in network infrastructure.  ✓

Proof-of-work can be wasted.  ✓

1. Why is it that the network trend towards having nodes that are exceptionally well connected?

Such nodes have the most hashpower available to solve the difficulty puzzle quickly.&#x20;

Such nodes are able to identify new transactions and add them to their block allowing them to build bigger blocks more consistently.&#x20;

Better connected nodes are more quickly able to both distribute and receive newly found blocks.   ✓

All of the above. &#x20;

1. What can nodes share that will improve their and the network's performance?

Their computed block and other transaction lists.  ✓

Their Pool Miner and mining hardware.&#x20;

Their knowledge of transactions that are occurring in real time. &#x20;

All of the above.&#x20;

**10. How does sharing information between nodes result in a ‘small world network’?**

It results in the ability to easily process large amounts of transactions by reducing the amount of bandwidth needed to distribute blocks back and forth between nodes.&#x20;

It results in a high density network, allowing for almost instantaneous transactions.  ✓

It results in a high security network where it is almost impossible for any single node to accumulate 51%.&#x20;

It results in an increased revenue for nodes as they are able to share work on blocks and receive a portion from any winnings.&#x20;

**11. Who benefits most from increased connectivity and information sharing between nodes?**

The user.&#x20;

The block winning node.&#x20;

The network.&#x20;

All of the above.  ✓

**12. Nodes will accept a block only if?**

All of the transactions within it are valid and unspent.  ✓

All of the transactions are valid and already spent.&#x20;

It matches with the block they are producing.&#x20;

All of the above.&#x20;

**13. Choose all that apply: Why is it important that nodes only accept valid blocks?**

So users don’t need to wait for official confirmation.  ✓

So nodes don’t end up working on the wrong chain.  ✓

So nodes can earn part of the block reward.&#x20;

All of the above&#x20;

**14. How does nodes validating the contents of blocks against its own ledger and the protocol rules, benefit the network?**

It enables validation of transactions almost instantly.  ✓

It prevents wasting proof-of-work on orphan blocks.&#x20;

It creates an environment in which there is a minimal chance of an orphan race occurring.&#x20;

It helps ensure the block timing maintains an average rate of approximately one block per ten minutes. &#x20;

**15. If a node receives a block that contains a transaction that is invalid, or a transaction that spends an already used output, what must the node do?**

It should retain that block for its own ledger.&#x20;

It should check to see if any other nodes have a valid version of it, before discarding it..&#x20;

It must immediately propagate that block to the rest of the nodes in the network.&#x20;

It shouldn't accept the block as valid.   ✓

**16. If a transaction’s input that is already used, is attempted to be used again, what will a receiving node indicate to the user?**

That the user has been the victim of a hack.&#x20;

That the network is already processing that transaction and to wait until the next block.&#x20;

That the newly introduced transaction was rejected as a double spend.  ✓

To reattempt to use that input with a new key.&#x20;

**17. What might cause a double spend?**

User error.&#x20;

Incorrect platform design.&#x20;

Malicious activity.&#x20;

All of the above.  ✓

**18. How might nodes prevent ongoing attempts to double spend on the network?**

Nodes cannot prevent ongoing double spend attempts and have to handle each attempt individually.&#x20;

By disconnecting those who attempt repeated double spends.  ✓

Nodes are able to provide the authorities with information pertaining to the source of repeated double spend attempts.&#x20;

Both (b) and (c).&#x20;

**19. How do nodes express their acceptance of a block?**

By working on a new block, using the accepted block’s hash.  ✓

By recording it in their ledger.&#x20;

By propagating it to the rest of the nodes on the ledger.&#x20;

All of the above.&#x20;

**20. How are nodes incentivized to accept it’s competitors' blocks quickly?**

Too long of a delay in validating competitors’ blocks could result in the node being disconnected from the network.&#x20;

Nodes that accept competitors’ blocks quickly are seen as competent nodes that are worthwhile for other nodes to share information with.&#x20;

The sooner it receives and validates a block from a competitor, the sooner it can begin building a new block with its hash.  ✓

All of the above.&#x20;

**21. What is the consequence of a node not immediately accepting a valid competitor block?**

Any work on a superseded block is a waste of time and money.  ✓

The node will be disconnected from the network.&#x20;

The node may not be provided information by other nodes quickly and will have a delayed block effort.&#x20;

All of the above.&#x20;

**22. Once a node accepts a competitor’s block as valid what should a node begin doing?**

Organizing incoming transactions into the mempool for preparation for the next block.&#x20;

Clearing transactions out of the mempool and forming the next block’s Merkle tree.  ✓

Begin finding a proof-of-work that meets the difficulty target of the network.&#x20;

Searching for the next block being proposed by a competitor.&#x20;

**23. What is a mempool?**

It retains transactions that are valid according to the network rules but not to the node’s local policy settings.&#x20;

It is the early stages of a block that the node is in the midst of creating.&#x20;

It is a security screening system that protects the node from accidentally incorporating an invalid transaction into a block or accepting an invalid block.&#x20;

It contains valid transactions that the node has accepted but which have not been timestamped into a block.  ✓

**24. What benefits are there to the network when nodes are hyper aware of other nodes activities? (select all correct answers)**

It reduces the potential of orphan races.   ✓

It reduces wasted energy spent producing valid yet unacceptable blocks.  ✓

It reduces the possibilities of a double spend.&#x20;

It reduces the amount of time it takes to settle a transaction.&#x20;

**25. What freedom does a node have regarding competitor’s blocks?**

They can reject blocks on any basis.  ✓

They can only reject empty blocks.&#x20;

They cannot deny valid blocks.&#x20;

They cannot accept invalid blocks.&#x20;

**26. What kind of outcome does Bitcoin’s traceability and incentive structure produce?**

One in which government financial regulations will be made unnecessary. &#x20;

An environment where pseudo anonymity and anonymity cannot exist.&#x20;

One in which there will be no criminal activity on the network.&#x20;

One in which honest and lawful action is the most profitable.  ✓

**27. How do nodes set and enforce the rules?**

By competing in finding proof-of-work.&#x20;

By validating transactions based upon what each node thinks is best for the network.&#x20;

Through following Nakamoto Consensus.  ✓

All of the above.&#x20;
