# Pool 4



Students must receive a score of 23/25 to successfully pass the course.Students must receive a score of 23/25 to successfully pass the course.

&#x20;

1. How does the process of proof-of-work begin?
   1. Nodes distribute the mining candidate to one or more pool-miners.  ✓
   2. Nodes distribute the mining candidate to ASIC hashing machines.&#x20;
   3. Pool-miners validate the mining candidate before distributing it to ASICs.&#x20;
   4. The proof-of-work is provided to the pool-miners which then distribute it to the nodes.&#x20;

&#x20;

Pool-miners manage what?

1. ASIC hashing machinery.  ✓
2. Nodes.&#x20;
3. Block creation.&#x20;
4. The proof-of-work process.  ✓

&#x20;

1. How do ASIC mining machines find proof-of-work?
2. By incrementing nonce values through a candidate block header.  ✓
3. By hashing the nonce value and a candidate blockheader.&#x20;
4. By double SHA256 hashing a candidate block header.  ✓
5. By checking the double hashed candidate block header against the difficulty target.  ✓

&#x20;

&#x20;

1. ASIC mining machines \_\_\_\_ values through a supplied \_\_\_\_ and with each value the block header is hashed twice using SHA256. A block header is valid if the double hash is \_\_\_\_\_\_ and can be added to the chain.
2. Adds, block header, more difficult than the difficulty target.&#x20;
3. test, hash function, equal to or less than the difficulty target.&#x20;
4. hash, block, greater than the difficulty target.&#x20;
5. increment nonce, block header, less than the difficulty target.  ✓

&#x20;

&#x20;

1. How are pool-miners able to calculate their profitability?
2. Using the transparency of the block reward and their operating costs.  ✓
3. By calculating the 24 hour market price of the block reward and the price of energy.&#x20;
4. By calculating the reward proportional to each hash operation performed.  ✓
5. By predetermining a sale price.&#x20;

&#x20;

1. What are some of the operating costs of hashing machinery?
2. The cost of energy.  ✓
3. The amount of energy consumed.  ✓
4. Facilities.  ✓
5. Data storage.&#x20;

&#x20;

1. What do pool-miners use their mining candidate for?
2. To generate unique block headers and coinbase transactions which they provide to their ASICs.  ✓
3. Incrementally iterating a nonce as an input to the candidate header before hashing with the ASIC miners.&#x20;
4. For their ASICs to perform 4.3 billion nonce cycles on, in order to generate proof-of-work.&#x20;
5. All of the above.&#x20;

&#x20;

1. What happens once a successful proof-of-work is found?
2. It is immediately broadcasted to the network by the pool-miner in order to prevent the chance of competing blocks emerging.&#x20;
3. It is sent back to the node by the pool miner to be verified and then broadcasted to the network.  ✓
4. It is verified by the pool-miner before being sent to the node to be immediately distributed.&#x20;
5. It is retested multiple times to ensure that the block isn’t rejected and the hashing efforts lost.&#x20;

&#x20;

1. What happens if two competing valid blocks are simultaneously discovered?
2. Each node applies the first seen rule.&#x20;
3. The node that first sees both blocks simultaneously chooses which is valid.&#x20;
4. Nodes validate each block to see which has a lower difficulty and then continues the chain upon it.&#x20;
5. The block added to the longest proof-of-work chain is regarded as the true record of events.  ✓

&#x20;

1. 10\. What does the first seen rule state?
2. That the transaction or block seen first is automatically valid.&#x20;
3. That the first node to see any block or transaction is the node by which the record is determined.&#x20;
4. That the first valid block or transaction seen by a node is the one upon which it builds its record.  ✓
5. All of the above.&#x20;

&#x20;

1. 11\. Which best describes the first block?
2. The block which is first seen and is able to be validated by the node.  ✓
3. The first block is always valid.&#x20;
4. A block consisting of only new transactions.&#x20;
5. A block with never before seen valid transactions.  ✓

&#x20;

1. 12\. How does a node signal consensus?
2. By propagating a first seen block to the rest of the network.&#x20;
3. By sending a first seen block to a pool-miner in order to be hashed into the next block it is forming.&#x20;
4. By forming a block template using the new block’s hash for the prevHash field.  ✓
5. By retaining a first seen block’s block header for its record.&#x20;

&#x20;

1. 13\. How does an orphan block occur?
2. When a pool-miner continues proof-of-work on a surpassed block instead of updating to a newly validated one.&#x20;
3. When a node hasn’t updated its candidate’s block header to include a newly proposed valid block.&#x20;
4. When two valid blocks are propagated to the network simultaneously.  ✓
5. When proof-of-work is wasted on a block that includes the hash of a first seen block that was invalidated through Nakamoto consensus.&#x20;

&#x20;

1. 14\. The \_\_\_\_\_\_ that uses a particular input is accepted. Any transaction that \_\_\_\_\_\_\_ is invalid, making the block \_\_\_\_\_\_.
2. transaction seen first, comes later, an orphan.&#x20;
3. latest transaction, had the same input previously, invalid.&#x20;
4. newest transaction, double spends, an orphan block.&#x20;
5. first seen transaction, re-uses an input, also invalid.  ✓

&#x20;

1. 15\. What does the blockchain DAG consist of?
2. The Genesis block and each subsequent chain that has emerged from it.&#x20;
3. A single chain of valid blocks beginning with the Genesis block.  ✓
4. Each and every transaction that has occurred on all chains since the Genesis block.&#x20;
5. Every block ever produced including orphaned blocks.&#x20;

&#x20;

1. 16\. What happens when two valid blocks are found with the same previous block hash?
2. The First Seen Rule applies.  ✓
3. An Orphan Race.  ✓
4. The node who found them first choses by incorporating one of the block’s hash into their next block.&#x20;
5. Both blocks are orphaned.&#x20;

&#x20;

1. 17\. What is an orphan race?
2. A race to extend the chain where more than one valid block is available to be used in the longest chain of proof of work.  ✓
3. A race to get a proof-of-work from the pool-miner to the node for verification and then onto the network to prevent it from being orphaned.&#x20;
4. A race to update a node’s mining candidate’s block header in order to prevent any wasted proof-of-work on an already surpassed block.&#x20;
5. All of the above.&#x20;

&#x20;

1. 18\. How is an orphan race usually resolved?
2. When one group of nodes building on a particular block is larger than the other.&#x20;
3. By discarding both blocks and restarting the block building process.&#x20;
4. When a block is found in one of the chains before the other.  ✓
5. All of the above.&#x20;

&#x20;

1. 19\. Once an orphan race is resolved the network fully transitions to the \_\_\_\_\_ and the block that is no longer being built upon becomes  \_\_\_\_\_\_.
2. newly seen block, hashed into the next block.&#x20;
3. orphan block, invalid.&#x20;
4. majority chain, a separate chain.&#x20;
5. longest chain, an orphan block.  ✓

&#x20;

1. 20\. Which statements are true?
2. An orphan block has a valid chain of history leading back to the genesis block.  ✓
3. An orphan block is included in the longest chain’s DAG as a terminated block.&#x20;
4. An orphan block has a valid proof of work.  ✓
5. An orphan block has an invalid proof-of-work.&#x20;

&#x20;

1. 21\. What happens if a node’s proposed block fails a validation test?
2. The node checks to see if it needs to update the block header with a more recent block’s hash.&#x20;
3. The block becomes orphaned.&#x20;
4. The node resubmits the block with a new proof-of-work.&#x20;
5. The block is ignored and the search for a valid block continues.  ✓

&#x20;

1. 22\. What are some of the reasons a block may be considered invalid?
2. The block is oversized.  ✓
3. There are too many outputs from the coinbase transaction.&#x20;
4. There is a transaction within it containing previously spent inputs.  ✓
5. The block contains only newly seen transactions.&#x20;

&#x20;

1. 23\. What might happen if a node submits multiple invalid blocks?
2. They will be ignored.&#x20;
3. The node may cause a chain reorg.&#x20;
4. The node may end up being ignored.  ✓
5. The network may slow down.&#x20;

&#x20;

1. 24\. How are nodes disincentivized from submitting invalid blocks?
2. The wasted expense of proof-of-work and the missed opportunity to profit.  ✓
3. Disconnection from the network impacts their opportunity to earn revenue.  ✓
4. The loss of energy consumed by finding proof-of-work.  ✓
5. Even when a block is invalid it still needs to pay the pool-miners.&#x20;

&#x20;

1. 25\. Since nodes can freely accept and reject blocks, it is important that they are aware of what the \_\_\_\_\_\_ the network accepts as the valid chain in order to be sure they are always building on the \_\_\_\_\_\_ of blocks and not producing \_\_\_\_ blocks.
2. most recent block, valid chain, orphan.&#x20;
3. majority of nodes on, longest valid chain, invalid.  ✓
4. Different groups of nodes on, most recent, on orphaned.&#x20;
5. Most connected nodes on, most recent chain, on invalid.&#x20;
