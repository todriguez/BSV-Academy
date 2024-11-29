# Pool 3

_Students must receive a score of 27/29 to successfully pass the course._&#x53;tudents must receive a score of 27/29 to successfully pass the course.

1. What must occur every time a node generates a new block template?

It must connect it to the longest chain of proof-of-work.&#x20;

It must create a new coinbase transaction.  ✓

It must propagate that block template to the rest of the nodes on the network.&#x20;

All of the above.&#x20;

1. In the early days of Bitcoin a problem emerged with nodes generating identical coinbase transactions creating multiple transactions with the same Transaction IDs. How was this problem solved?

Nodes now calculate the coinbase Transaction IDs using a UNIX epoch timestamp to ensure that each coinbase transaction is unique.&#x20;

Coinbase Transaction IDs are now predetermined by the protocol.&#x20;

Blocks with coinbase Transaction IDs that are identical to a previous Transaction ID are now rejected as invalid.&#x20;

A rule was created that requires that the first part of the scriptSig string must be a varInt containing the block height.  ✓

1. How do nodes often identify themselves to the rest of the network within a coinbase transaction?

Using the remainder of the input string.  ✓

By inputting a hash of their IP address into the transaction.&#x20;

Using OP CHECKSIG.&#x20;

All of the above.&#x20;

1. Since the coinbase transaction doesn’t need to be propagated to the network until a block is found, what does it need to adhere to?

It doesn’t need to adhere to any rules.&#x20;

Dust limits.&#x20;

Minimum transaction fees.&#x20;

Bitcoin’s immutable ruleset.  ✓

1. How does MinerID allow nodes to identify themselves in a Coinbase transaction?

Using a FALSE RETURN output with an inserted signature.  ✓

Using a scriptSig with a MinerID signature in it.&#x20;

Using the remainder of the input string to place a Miner ID scriptSig.&#x20;

Using a MinerID within a FALSE RETURN input string.&#x20;

1. When can outputs from the coinbase transaction be spent by nodes?

Immediately.&#x20;

After two blocks.&#x20;

After one hundred blocks.  ✓

After 1000 blocks.&#x20;

1. Most orphan races are won within?

One block.&#x20;

Five or six blocks.&#x20;

Ten or twelve blocks.&#x20;

Two or three blocks.  ✓

1. How does the delay on spending a coinbase transaction benefit the network?

It stabilizes the market price by transparently delaying the sale of newly distributed bitcoins.&#x20;

It acts as an incentive for miners to continue building blocks.  ✓

It ensures that the funds aren’t involved in an orphan race.  ✓

All of the above.&#x20;

1. What do the outputs of the coinbase transaction have to contain?

Equal or less satoshis then the combined transaction fees and block subsidy.  ✓

Less satoshis then the combined transaction fees but equal satoshis for the block subsidy.&#x20;

Only the satoshis of the Block Subsidy.&#x20;

A FALSE RETURN with a signature hash.&#x20;

**10. The transaction fee is the difference between the value of which?**

The transaction’s input and the network’s minimum transaction fee.&#x20;

The transaction’s input and output.  ✓

The average node's minimum fee policy and the networks fee rules.&#x20;

The transaction value and the amount of transactions that can fit in a block.&#x20;

**11. Which is BitcoinSV’s perspective on transaction fees?**

As demand for bitcoins grows, network limitations raise the cost of sending transactions creating a greater incentive for node participation.&#x20;

As transactions become cheaper nodes will need to find new ways of adding value to the network in order to increase the value of their block rewards.&#x20;

With growing adoption, large value transactions will increase the fees available to nodes creating a greater incentive for node participation.&#x20;

As the network accommodates more transactions the cumulative value of transaction fees becomes the dominant incentive for node participation.  ✓

**12. Which best describes the Block Subsidy?**

A predetermined distribution of bitcoins to block winning nodes.  ✓

An algorithmically defined distribution of Bitcoins to all nodes over time.&#x20;

The combined sum of the transaction fees and the block reward that is distributed to block winning nodes over time.&#x20;

A continual process by which the network rewards miners equally for producing successful blocks.&#x20;

**13. The Block Subsidy started at \_\_\_\_\_\_ Bitcoins in 2009 and reduces by \_\_\_\_\_\_ every\_\_\_\_\_ blocks, steadily decreasing until it reaches zero.**

75, 50%, 75,000&#x20;

50, 50%, 210,000  ✓

250, 50%, 120,000&#x20;

100, 25%,100,000&#x20;

**14. When will the subsidy complete?**

In approximately 2140.  ✓

Once transaction fees become the dominant value of the block reward.&#x20;

After 32 “halvings”.  ✓

After 200,000 blocks.&#x20;

**15. What does the subsidy give Bitcoin nodes in the early phases of the network?**

It covered the expense of running the node.&#x20;

It provided an opportunity for those running a node to become wealthy quickly.&#x20;

A chance at a reward when transaction fees were minimal.  ✓

It allowed for node operators to stockpile coins at an early price so that they could then sell for considerably more at a later date.&#x20;

**16. Which answer describes the long term block reward structure of Bitcoin most fully?**

Once the subsidy distribution is complete, the incentive will be entirely transaction based.&#x20;

As network usage increases the incentive will increasingly become more transaction based.&#x20;

The subsidy may be extended if network usage fails to provide enough reward to incentivize node participation.&#x20;

With the diminishing subsidy and increase of network usage, the incentive will increasingly become more transaction based.  ✓

**17. What happens if the outputs from a miner’s coinbase transaction are a lower value than the block reward?**

The remnants are redistributed into the next block reward.&#x20;

The remnants are removed from circulation.  ✓

The remnants are returned to the subsidy.&#x20;

The coinbase transaction is invalid.&#x20;

**18. What is a mining candidate?**

A block that will potentially be submitted to the network for validation.  ✓

A block that has been validated by the network.&#x20;

A block that is undergoing proof-of-work.  ✓

All of the above.&#x20;

**19. What does a mining candidate consist of?**

A template with the prevHash, block version, difficulty value, Merkle root and timestamp included in the header.  ✓

A set of transactions with a block header that includes the hashPrevBlock, the Nonce, and the Time.&#x20;

A set of transactions with the full Merkle tree, the hash of the previous block, the Nonce, and the block version.&#x20;

A full Merkle tree, the version number, a tracking code, the previous block hash, and the difficulty value.&#x20;

**20. What is a system that controls ASICs called?**

A pool-miner.  ✓

A hash-pooling system.  ✓

A node operator.&#x20;

A node.&#x20;

**21. Match the item with its description: An array containing a list of hex strings that represent the interior node values along the Merkle path for a given transaction.**

version.&#x20;

prevHash.&#x20;

nBits.&#x20;

Merkle proof.  ✓

&#x20;

**22. Match the item with its description: A 4 byte string representing the block.**

id.

version.  ✓

nBits.&#x20;

Merkle proof.&#x20;

&#x20;

23\. Match the item with its description: A 4 byte number representing the target difficulty.

version.&#x20;

prevHash.&#x20;

nBits.  ✓

Merkle proof.&#x20;

&#x20;

24\. Match the item with its description: An 8 byte number representing the value of the combined reward outputs in satoshis.

id.&#x20;

coinbaseValue.  ✓

prevHash.&#x20;

Height.&#x20;

&#x20;

25\. Match the item with its description: A varchar representing the candidate block’s location in the chain.

id.&#x20;

coinbaseValue.&#x20;

Time.&#x20;

Height.  ✓

&#x20;

26\. Match the item with its description: Used to advertise a block winning pool.

id.  ✓

version.&#x20;

coinbaseValue.&#x20;

nBits.&#x20;

&#x20;

27\. Match the item with its description: Unix epoch accurate to 1 second.

prevHash.&#x20;

Time.  ✓

nBits.&#x20;

Height.&#x20;

&#x20;

28\. Match the item with its description: A 32 byte string representing the previous block.

id.&#x20;

version.&#x20;

prevHash.  ✓

Merkle proof.&#x20;

&#x20;

29\. What else may be included in a mining candidate?

With the previous values a pool-miner has all of the information it needs.  ✓

A coinbase transaction.  ✓

Any data the node desires to include.&#x20;

All of the above.&#x20;
