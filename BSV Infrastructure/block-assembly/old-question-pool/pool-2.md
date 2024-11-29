# Pool 2

_Students must receive a score of 23/25 to successfully pass the course._&#x53;tudents must receive a score of 23/25 to successfully pass the course.

1. Each node typically broadcasts \_\_\_\_\_ transactions to all other nodes, even \_\_\_\_\_.

valid, if they do not plan to place them in a block.  ✓

invalid, they won’t be included in a block.&#x20;

low fee, though some low fee transactions may be retained for a block if there aren't enough high fee transactions.&#x20;

complex, with large fees as it's faster to process simple transactions.&#x20;

1. When a node detects that another node does not have transactions it has validated, there is an incentive to do what?

Not to connect with that node.&#x20;

Request a fee for them from that node.&#x20;

Provide them to that node.  ✓

Add them to its block.&#x20;

1. How is it that transactions are typically able to be propagated to the vast majority of nodes within a few hundred milliseconds?

The highly connected nature of nodes.  ✓

Bitcoin’s transaction design.&#x20;

Nodes are watching for transactions in real time.&#x20;

Because they haven't been timestamped into blocks.&#x20;

1. What does the First Seen Rule dictate?

That the node that first sees a UTXO must broadcast it to the rest of the nodes on the network.&#x20;

That whichever node first sees a transaction it gets to place it into its block.&#x20;

That each input contained within the UTXO of a transaction must be seen simultaneously by a node.&#x20;

That a UTXO can only be spent in the first seen valid transaction that spends it.  ✓

1. What does the First Seen Rule protect against?

Nodes withholding transactions from the rest of the network.&#x20;

Double spends by users.  ✓

Double spends by nodes.&#x20;

All of the above.&#x20;

1. How does a node attempt to double spend?

By propagating an invalid transaction to the rest of the network.&#x20;

By attempting to spend the same inputs to different outputs.&#x20;

By generating enough proof-of-work to override network consensus.  ✓

By placing an already spent input into a new block.&#x20;

1. What can the network do to a double spending node?

Nothing.&#x20;

It can reject its blocks.  ✓

&#x20;

It can fork it off onto a separate chain.

&#x20;

It can shut down the node.&#x20;

1. How is the TXID hash part of the node’s block template?

It is used to form the block header.&#x20;

Valid transactions are appended to the Merkle tree.  ✓

It is used in the creation of the Merkle Root.  ✓

It is not a part of the block template.&#x20;

1. What part/s of the Merkle tree is constructed with unconfirmed transactions?

The previous block’s hash.&#x20;

The root.  ✓

The leaf nodes.  ✓

The block template.&#x20;

**10. How many transactions are capable of being included into a block’s Merkle tree structure?**

Unlimited.&#x20;

It depends on the block size limit.&#x20;

Only what fits in it’s fixed-length byte string.&#x20;

Theoretically unbounded.  ✓

**11. After the \_\_\_\_\_\_ has been hashed twice using the SHA256 algorithm, the output value, known as the \_\_\_\_\_\_\_, is converted to little endian and appended to the Merkle tree data structure.**

serialized binary string is, Transaction ID.  ✓

TXID is, Merkle root.&#x20;

Transaction ID is, serialized binary string.&#x20;

UTXOs are Merkle tree’s leaves.&#x20;

**12. What must occur each time a transaction is added to the Merkle tree?**

A new TXID forms the Merkle tree’s leaves.&#x20;

The Merkle root must be re-calculated.  ✓

A new block template is created.  ✓

A new double hash must be formed.&#x20;

**13. How could a node parallelize Merkle tree generation?**

By combining the Merkle trees of transaction subsets contained within a candidate block to form a larger tree.  ✓

By generating multiple possible Merkle trees providing ready made possibilities that can be automatically applied to the candidate block.&#x20;

By connecting with other nodes to compare Merkle trees.&#x20;

By building multiple block headers and combining them with the different Merkle roots.&#x20;

**14. What kind of information is contained within the Block Header?**

Proof-of-work provenance.  ✓

The Merkle tree provenance.&#x20;

Block contents provenance.  ✓

All of the above.&#x20;

**15. The linked block headers combined form a structure known as what?**

The longest chain of proof-of-work.&#x20;

The ledger.&#x20;

A Directed Acyclic Graph.  ✓

A working blockchain.&#x20;

**16. Which blocks does the directed acyclic graph consist of?**

Only blocks that contain UTXO’s that are spendable on the network.&#x20;

The blocks since the node first connected to the network.&#x20;

The blocks which a node has successfully added to the longest proof-of-work chain.&#x20;

The genesis block to the current tip of the longest proof-of-work chain.  ✓

**17. Match the item with its description: This 32 byte little endian field represents the part of the Merkle tree that contains the transactions which are time stamped in a block.**

hashPrevBlock.&#x20;

Time.&#x20;

Nonce.&#x20;

hashMerkleRoot.  ✓

**18. Match the item with its description: This is a 4 byte little endian field indicating the Bitcoin protocol under which a node is publishing a block.**

Nonce.&#x20;

Version.  ✓

hashMerkleRoot.&#x20;

Bits.&#x20;

**19. Match the item with its description: This is a 4 byte field indicating the difficulty required of the solution to the proof-of-work puzzle.**

hashPrevBlock.&#x20;

Nonce.&#x20;

Version.&#x20;

Bits.  ✓

**20. Match the item with its description: This is a 4 byte field which is cycled through values to modulate the block header. The hash of the header is then checked against the difficulty target.**

hashPrevBlock.&#x20;

Time.&#x20;

Nonce.  ✓

Bits.&#x20;

**21. Match the item with its description: This is a 32 byte little endian field which is the double SHA256 hash of the prior block’s header.**

hashPrevBlock.  ✓

Nonce&#x20;

Version.&#x20;

hashMerkleRoot.&#x20;

**22. Match the item with its description: This is a 4 byte field for a Unix epoch stamp that is applied to all transactions in the block.**

Time.  ✓

Nonce.&#x20;

Version.&#x20;

Bits.&#x20;

**23. Which forms the edge to the previous block that joins new blocks to the blockchain DAG?**

hashMerkleRoot.&#x20;

hashPrevBlock.  ✓

Version.&#x20;

Time.&#x20;

**24. How many unique nonce combinations are possible?**

Unlimited.&#x20;

Unbounded.&#x20;

4.3 billion values.  ✓

8.6 billion values.&#x20;

**25. How is a nonce used to generate proof-of-work?**

By finding a nonce that once incorporated into the hash puzzle, the subsequent value must equal the difficulty target to be considered successful.&#x20;

By cycling hash puzzles against the nonce until a hash puzzle is unlocked that meets the difficulty target of the network.&#x20;

By passing single use values through the nonce field modulating the block header to form an output value less than or equal to the difficulty target.  ✓

By searching for a nonce that when combined with the hash puzzle forms a number that matches the difficulty criteria.&#x20;
