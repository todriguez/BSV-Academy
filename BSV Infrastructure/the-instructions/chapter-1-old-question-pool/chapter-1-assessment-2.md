# Chapter 1 - Assessment 2

_Students must receive a score of 26/28 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers._&#x53;tudents must receive a score of 26/28 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers.

1. T/F A node can append transactions to a block in any order.

True  ✓

False&#x20;

1. What is the most efficient method for nodes to add transactions to a block?

Adding them wherever a node sees fit. This process makes it unnecessary for a node to recalculate the Merkle tree.&#x20;

Appending them to the end of the block and recalculating to find a new Merkle root.  ✓

Randomly, this allows for the block to automatically form a new Merkle tree.&#x20;

The only way possible for nodes to add transactions into a block is by appending them to the end of the list of transactions in the block. &#x20;

1. What does appending transactions to the end of a block achieve at scale?

Increases the speed by which nodes are able to collect transactions as they appear on the network.&#x20;

Maximizes the amount of transactions that can be contained within a block further increasing the transaction throughput of the network.&#x20;

Minimizes redundancies in the management of the Merkle tree allowing for greater efficiency.  ✓

All of the above.&#x20;

1. What is a Merkle tree?

The complete transaction history of every single input contained within the block back to the moment they were distributed in the form of a block reward.&#x20;

A Hierarchical data structure that enables secure and fast verification of data.  ✓

The process by which control over the funds being spent on the network is verified.&#x20;

Hash based proof-of-work that links together the blocks to form an immutable record leading back to the Genesis block.&#x20;

1. How is a Merkle tree formed?

By nodes as they form the blockheader for their new block.&#x20;

By ASICs as they work on finding a solution to the proof of work puzzle that meets the difficulty target formed by network consensus.&#x20;

Through network consensus as to the order of events as they occurred on the network.&#x20;

By nodes recording the order of transactions as they receive them.  ✓

1. What happens once a node successfully wins a block?

Other nodes on the network verify that the successful block is valid.&#x20;

The block's Merkle tree is recognized as the correct order of events on the ledger.  ✓

The block winnings are immediately distributed to the winning node to freely spend.&#x20;

All of the above. &#x20;

1. What level of investment in infrastructure is necessary for a node to manage its task effectively?

Minimal&#x20;

Significant  ✓

Moderate&#x20;

None&#x20;

1. When a transaction is spent, the spending party must attach a valid \_\_\_\_\_ to the outputs from the UTXO set?

scriptSig  ✓

Input&#x20;

Private key&#x20;

Public address&#x20;

1. Once a node obtains a transaction it initiates which of the following tests to determine the validity of the transaction? (select all valid answers)

The scriptSig for each input validly solves the locking script / scriptPubkey.  ✓

This is the first time these inputs have been spent.  ✓

The outputs being generated are valid.  ✓

None of the above.&#x20;

**10. What does the full data of a block consist of?**

The transaction inputs, scriptSig, and public address of all the transactions being submitted.&#x20;

The ordered list of transactions plus the block header.  ✓

The nonce of the completed hash puzzle along with the transactions being submitted.&#x20;

The inputs, outputs, and scriptSig of all the transactions contained within the block.&#x20;

**11. What must a node do each time a new version of the Merkle tree is created?**

Begin creating a new block.&#x20;

Nothing.&#x20;

Renew its block template.  ✓

Both (a) and (c).&#x20;

**12. What does the acronym ASIC represent?**

Application Specific Integrated Circuit  ✓

Application Singular Integrated Computer&#x20;

Application Specific Integral Circuit&#x20;

None of the above&#x20;

**13. What process is carried out by ASIC or Hashing machines?**

The process of discovering new transactions being propagated onto the network.&#x20;

The process of finding a proof-of-work.  ✓

The process of transaction validation.&#x20;

All of the above.&#x20;

**14.  How do ASICs or Hashers find a proof-of-work?**

By continuously updating the Merkle root. &#x20;

By checking each transaction's scriptSig for validity.&#x20;

By iterating the value of the block header's nonce and hashing the result.  ✓

By consolidating the transaction hashes to form a new Merkle root.&#x20;

**15. What is a Pool Miner?**

It governs ASICs and manages the hashing process.  ✓

A node operator that owns multiple nodes.&#x20;

A group of ASICs all working together.&#x20;

When multiple nodes join together to build blocks.&#x20;

**16. How is a Pool Miner integral in the block building process?**

Pool Miners search for new transactions to enter into the incomplete block and distribute information about those transactions to a node which updates the block template for the hashers to work on.&#x20;

Once a valid proof-of-work is found by hashers, it is distributed to nodes which send it to Pool Miners in order to be proposed to the network as the valid record of events having occurred on the ledger.&#x20;

Pool Miners operate nodes as a for profit service allowing those with ASICs to connect directly to a pool which automatically directs the block creation effort.&#x20;

Nodes distribute information about the incomplete block to the pool miners which coordinate ASICs in the search for a valid proof-of-work.  ✓

**17. How do ASICs or Hashers find a valid proof-of-work?**

By determining that all the transactions within the block are valid.&#x20;

By finding a block header that hashes to less than the difficulty target.  ✓

By finding a Merkle tree which matches the block’s hash puzzle.&#x20;

By finding the next block in the chain with the most difficult proof of work.&#x20;

**18. Which best describes the nature of the difficulty puzzle?**

It’s difficulty is determined by the amount of nodes on the network at any given time, the more active nodes working to build blocks the more difficult the puzzle becomes.&#x20;

It’s difficulty is proportional to the amount of transactions contained within the block. As the amount of transactions contained within blocks grows, the difficulty of the puzzle increases, requiring more and more hashpower to maintain an average of 10 minutes per block.&#x20;

It has a pseudo random solution which is tuned to maintain a block discovery rate of approximately 10 minutes.  ✓

It has a single unknown solution that needs to be found approximately every 10 minutes in order to maintain the networks block frequency.&#x20;

**19. What is the significance of the block discovery rate?**

It is timed to balance the benefits of a low orphan block rate, and still provide an enticing opportunity for nodes to be rewarded.  ✓

It enforces the network’s hard limit of approximately twenty one-million Bitcoins.&#x20;

It ensures that any attempts by a node to double spend can be beaten by honest nodes in an orphan race.&#x20;

All of the above.&#x20;

**20. Which Block templates have the highest probability of becoming a valid block?**

They all have equal probability of being valid.&#x20;

The block templates with the most recent Merkle root.&#x20;

The block templates with the most transactions.&#x20;

The block templates which have the most hash applied.  ✓

**21. What does a valid hash puzzle represent?**

That the transactions contained within the block are also valid.&#x20;

The key to unlock the block reward which consists of the subsidy and the transaction fees contained within the block.&#x20;

A signal that is impossible to form without access to hashers in order to generate valid block proposals.  ✓

An unbreakable encryption scheme that protects the ledger's immutability. &#x20;

**22. What does a valid hash puzzle provide nodes?**

A simple and inimitable means for nodes to determine if they are talking to another node.  ✓

A way for nodes to show the amount of work they had to exert in order to generate a block.&#x20;

A means to identify themselves in order to receive their reward for successfully generating a block.&#x20;

All of the above.&#x20;

**23. Why is it important for nodes to know who the other nodes are in the network?**

In order to try to out compete each other at producing valid blocks.&#x20;

To watch each other for attempts to double spend on the network.&#x20;

To prevent each other from attempting a 51% attack.&#x20;

To share transactions and block announcements with each other.  ✓

**24. What does the act of winning a block signify for the victorious node?**

That it is a valid competitor.  ✓

That it controls the most hashpower.&#x20;

That it was able to accumulate the most transactions.&#x20;

That it is the most connected node.&#x20;

**25. What is proof-of-work designed to ensure?**

That everyone has a fair chance to win a block.&#x20;

Nodes with the greatest investment have the opportunity to win the most blocks in order to incentivize additional infrastructure investment.&#x20;

Only those who have invested in the infrastructure of the network can participate in block building.  ✓

(b) and (c).&#x20;

**26. How does proof-of-work legitimize the network legally?**

It prevents nodes being considered legally as money transmitters and instead creates a new class of business with which there are minimal legacy regulatory controls.&#x20;

By ensuring that node operators are identifiable enterprises engaged in transaction processing as a regulated business activity.  ✓

It allows for the transactions contained within the blocks to be both transparent in their activity yet private in their identity.&#x20;

All of the above.&#x20;

**27. Which answer best describes the Bitcoin network's energy consumption regarding proof-of-work and transaction processing?**

The energy consumed by proof-of-work is directly proportional to the amount of transactions on the network.&#x20;

Bitcoin’s energy consumption will become increasingly less as more energy efficient hashing machinery and more effective means of harnessing renewable energy are used.&#x20;

The energy expended to find a valid solution for a hash puzzle is independent from that which is needed to gather and validate the transactions in each block.  ✓

(a) and (b).&#x20;

**28. How does the energy for solving hash puzzles being independent from that needed to process transactions benefit Bitcoin?**

It provides a degree of energy anti-fragility which allows Bitcoin to operate in austere and hostile conditions.&#x20;

As Bitcoin scales, its per-transaction efficiency increases.  ✓

The energy used for solving hash puzzles is not independent from transaction processing.&#x20;

It makes it difficult for those with cheap energy to spam the network with blocks.&#x20;
