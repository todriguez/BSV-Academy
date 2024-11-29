# Pool 2

_Students must receive a score of 48/54 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers._&#x53;tudents must receive a score of 48/54 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers.

1. What is the Proof of Work Target Adjustment Rule?

It is the rule that sets the limit on how many nodes are able to operate on the network by increasingly making it more difficult to find a proof-of-work.&#x20;

It's how the network adjusts the difficulty target for the proof-of-work needed to prevent any one entity from obtaining 51% of the network hashpower.&#x20;

It's how the network adjusts the difficulty target for the proof-of-work needed to maintain the average block discovery rate.  ✓

All of the above.&#x20;

1. What is the average block discovery rate?

Approximately every 10 minutes.  ✓

Approximately every 1 minute.&#x20;

Approximately every 5 minutes.&#x20;

Exactly 10 minutes.&#x20;

1. What does the Proof of Work Target Adjustment Rule define?

How the proof-of-work must be calculated.&#x20;

What kind of hardware can be used to generate proof-of-work on the network.&#x20;

How many blocks can be produced in a certain period of time by each individual node.&#x20;

How the network adjusts the target difficulty rate.  ✓

1. Why does the network need to adjust the target difficulty?

To compensate for the increase or decrease of resources applying proof-of-work.  ✓

To make bitcoin harder to mine and therefore more scarce, increasing both price and demand.&#x20;

To help increase the supply of GPUs available on the market and prevent older hardware from becoming unusable.&#x20;

To stop a chain death spiral if miners switch to a coin that's recently gone up in value.&#x20;

1. What kind of process is block discovery?

Random.&#x20;

Pseudorandom.  ✓

Calculated.&#x20;

Frequentist probability.&#x20;

1. How do nodes compete to find a block?

By finding a mathematical equation which results in a value that is equal to the block difficulty target.&#x20;

By connecting transactions in such a way that it forms a hash which is cycled through various nonces to find a difficulty value equal or less than the difficulty target.&#x20;

By finding the Merkle root of the block and using it to search through combinations of transaction hashes to form a valid Merkle tree.&#x20;

By hashing the candidate block header while changing the nonce field to find a value less than or equal to the difficulty target.  ✓

1. How does the system know to adjust the difficulty rate?

Based upon how large the blocks are.&#x20;

Based on the time it took to discover previous blocks.  ✓

Based upon how many nodes are connected to the network.&#x20;

All of the above.&#x20;

1. How often is the difficulty target adjusted in BitcoinSV?

Once every 2016 blocks.&#x20;

Every block.  ✓

Approximately every two weeks.&#x20;

Once per day.&#x20;

1. How often was the difficulty target adjusted in the original release of Bitcoin?

Once every 2016 blocks.  ✓

Every block.&#x20;

Once every 1015 blocks.&#x20;

Once per day.&#x20;

**10. What is necessary in order to revert the network back to the original difficulty adjustment cycle?**

Considerably more hashpower, a difficulty adjustment algorithm delivery and simultaneous delivery system.&#x20;

A network wide upgrade that allows nodes to revert to the original cycle.&#x20;

It is not something in consideration for BitcoinSV.&#x20;

All nodes will need to accept the modified consensus conditions.  ✓

**11. True or False: Only blocks that add to the block chain formed by building upon the Genesis block are valid?**

True  ✓

False&#x20;

**12. The Genesis Block Rule states that blocks must be added to an \_\_\_\_\_\_\_ chain of \_\_\_\_\_\_ leading back to the genesis block.**

existing, blocks&#x20;

unbroken, proof-of-work  ✓

original, block hashes&#x20;

unaltered, blocks&#x20;

**13. Why is the genesis block hash hard coded into the Bitcoin node client software?**

So nodes can automatically build on the valid chain of blocks.&#x20;

To prevent malicious imitations attempting to deceive the network.  ✓

To create a “memento mori” for chain recall following a node being disconnected from the network.&#x20;

All of the above.&#x20;

**14. True or False: A malicious party could replicate the block chain in order to deceive nodes in an attempt to divert hashpower or transactions from the network.**

True&#x20;

False  ✓

**15. What feature directly benefits from the genesis block hash being preserved?**

Proof-of-work.&#x20;

Double Spend Detection.&#x20;

Instant Transactions.&#x20;

Simplified Payment Verification.  ✓

**16. Which is the genesis block hash?**

0122239000906egjh6hs82l6jd47gdsh67ikrr5he4y6ked5697jrdrrr6336tgjk8kre&#x20;

000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f  ✓

rvsgtdsgbthtd57ht36yn6b3cfr3566he34tg6657bss443rf35gs44430000000000&#x20;

10000000000000000000000000000000000000000000000000000000000000&#x20;

**17.  Which are Transaction Consensus Rules?**

nLockTime and nSequence  ✓

Maximum Transaction Size Rule  ✓

Coinbase Maturity Rule  ✓

The sum of a transaction's inputs must be greater than, or equal to, that of it’s outputs.  ✓

**18. What do the transaction consensus rules define?**

How users are able to generate transactions.&#x20;

How transactions are interpreted by the nodes.  ✓

What a transaction is capable of being.&#x20;

All of the above.&#x20;

**19. The Maximum Transaction Size Rule is?**

A consensus imposed economic limit.  ✓

An individual node’s transaction size limit.&#x20;

A natural constraint imposed by limitations in the size of blocks.&#x20;

All of the above.&#x20;

**20. What does the Maximum Transaction Size Rule allow for?**

For nodes to raise the limit as the network's capabilities improve.  ✓

For nodes to keep the cost of transactions low in order to provide utility to all users.&#x20;

The network to form practical transaction size limits for users.&#x20;

All of the above.&#x20;

**21. What does the nSequence fields of each input and the nLockTime field of the transaction determine?**

Transaction format.&#x20;

Transaction fee value.&#x20;

Transaction finality.  ✓

Transaction size.&#x20;

**22. Which answers describe a transaction which is “non-final”?**

A transaction which cannot be valid.  ✓

A transaction which can become valid at a later time.  ✓

A transaction which can never be final.&#x20;

A transaction which cannot be entered into a block.  ✓

**23. If a transaction is “final” what is possible?**

The transaction is complete.&#x20;

The translation cannot be entered into a block.&#x20;

The transaction cannot be made.&#x20;

The transaction can be entered into a block.  ✓

**24. If the value of nSequence of a transaction input is not 0xFFFFFFFF then?**

That input is a “non-final input”.  ✓

That input is a “final input”.&#x20;

**25. If the value of nSequence of a transaction input is 0xFFFFFFFF then?**

That input is a “non-final input”.&#x20;

That input is a “final input”.  ✓

**26. If all of the inputs of a transaction are “final inputs” but the nLockTime hasn’t expired, what is the state of the transaction?**

It is non-final.&#x20;

It is final.  ✓

**27. If any of the inputs of a transaction are “non-final inputs” and the nLockTime field is 500,000,000 or less, what does the nLockTime field represent?**

The Block height.  ✓

A UNIX epoch timestamp.&#x20;

The transaction size&#x20;

The transaction fee.&#x20;

**28. If the node is working on a block which has a height greater or equal to the block height value of nLockTime field, then the transaction is?**

Non-final.&#x20;

Final.  ✓

**29. If the node is working on a block which has a height that is less then the block height value of the nLockTime field, then the transaction is?**

Non-final.  ✓

Final.&#x20;

**30.  If the value of the transactions nLockTime field is greater or equal to 500,000,000 then the field represents the?**

Block height.&#x20;

UNIX epoch timestamp.  ✓

Transaction size.&#x20;

Transaction fee.&#x20;

**31. If the median time passed of the last 11 blocks is greater or equal to the value of this field, then the transaction is?**

Final  ✓

Non-final&#x20;

**32. True or False: A non-final transaction may be confirmed in a block.**

True&#x20;

False  ✓

**33. What must occur in order for a new transaction to replace a non-final transaction?**

It is impossible to make a new transaction prior to the non-final transaction’s nLockTime expiring.&#x20;

It must have the same inputs in the same order.  ✓

Each sequence number for all inputs in the new transaction cannot be less than those of the prior transaction’s.  ✓

The sequence number of at least one input in the new transaction must be greater than that of the prior transaction’s corresponding input.  ✓

**34. If a new transaction is broadcasted to the network with conflicting inputs to that of a non-final transaction, yet the inputs are not identical to that of the “non-final” transaction, then the \_\_\_\_\_\_\_\_\_ transaction is the \_\_\_\_\_\_\_\_\_ transaction and takes priority over the \_\_\_\_\_\_\_transaction.**

new, valid, non-final&#x20;

first seen, new, final&#x20;

valid, final, non-final&#x20;

non-final, first seen, new  ✓

**35. How does nSequence and nLockTime rules benefit Bitcoin?**

They allow for users to lock bitcoins.&#x20;

They incentivize nodes to form closer network connections.&#x20;

They prevent malicious transactions.&#x20;

They allow for the creation of payment channels.  ✓

**36. What are UTXOs?**

Unspent Transaction Outputs.  ✓

Spendable coins on the network.  ✓

A way for nodes to trace transactions.&#x20;

Satoshi tokens locked inside a script.

&#x20;  ✓

**37. How are UTXO’s used?**

By using an unlocking script.  ✓

By using a private key.&#x20;

By using inputs.&#x20;

By retrieving them from the ledger.&#x20;

**38.  The ledger represents the \_\_\_\_\_\_\_ of those coins since being distributed as part of a block reward. Every node has a set of UTXOs it manages which it curates according to the \_\_\_\_\_\_\_.**

unspent transaction outputs, transaction format rules&#x20;

unspent transaction outputs, transaction consensus rules&#x20;

retrieval mechanism, network’s consensus rules&#x20;

complete transaction history, operator’s local policies  ✓

**39. When \_\_\_\_\_\_\_  is successfully evaluated in the script engine using  \_\_\_\_\_\_\_, the satoshi tokens are released to be spent.**

the UTXO, the unlocking script&#x20;

the locking script, the UTXO&#x20;

the unlocking script, the locking script&#x20;

the locking script, the unlocking script  ✓

**40. In order for the satoshi tokens to be released successfully, the full script must terminate with a \_\_\_\_\_\_\_ value remaining on the stack.**

zero&#x20;

single non-zero  ✓

non-zero&#x20;

single zero&#x20;

**41. The sum of the value of the \_\_\_\_\_ of a transaction must be \_\_\_\_\_ than or equal to the sum of the values of the \_\_\_\_\_.**

outputs, greater, inputs&#x20;

inputs, greater, outputs  ✓

Outputs, less, outputs&#x20;

UTXOs, greater, outputs&#x20;

**42. Once the UTXOs are unlocked the transaction re-allocates the satoshis to new outputs which then become what?**

UTXOs  ✓

Inputs&#x20;

Spent&#x20;

Locked&#x20;

**43. What happens to the newly formed UTXOs?**

They remain on the user's wallet until ready to spend, at that point they are propagated to the network alongside the unlocking script.&#x20;

They replace the previous ones within the network wide UTXO set.  ✓

They are distributed to all nodes.&#x20;

They are discarded from the ledger but remain with the user.&#x20;

**44.  If a transaction attempts to create outputs that cumulatively represent more value than the inputs it would be spending, what is it attempting to do?**

To spend already used inputs.&#x20;

To create new satoshi tokens.  ✓

To replace an existing transaction.&#x20;

To create an nLockTime value.&#x20;

**45.  How many blocks must pass before a node is able to spend the outputs of a Coinbase transaction?**

150 blocks&#x20;

10 blocks&#x20;

100 blocks  ✓

1000 blocks&#x20;

**46. What does the Coinbase Maturity Rule ensure?**

Node operators aren’t able to use outputs from blocks that might be involved in orphan races.  ✓

Protects the network from node operators attempting to generate bitcoins beyond what is allotted by the network.&#x20;

Reduces hashrate volatility.&#x20;

Keeps block discovery rates consistent.&#x20;

**47.  What does the Transaction Format Rule specify?**

That transactions must conform to the data formatting rules of the Bitcoin protocol.&#x20;

The sizes of certain fields and their encoding schemas.&#x20;

Bitcoin transaction serialization.&#x20;

All of the above.  ✓

**48. What is the Transaction version?**

A value indicating the version of the evaluation protocol (4 bytes)  ✓

A value defining the version of the protocol that should be used to evaluate the transaction (40 bytes)&#x20;

How many times a user has broadcast the same value transaction (4 bytes)&#x20;

It is the same as the nSequence field. (4 bytes)&#x20;

**49.  What comes after the transaction version?**

The number of inputs being spent.  ✓

The scriptSig needed to spend the inputs.&#x20;

The number of outputs being created.&#x20;

Each input.&#x20;

**50. The inputs include which of the following?**\
&#x20;

TXID of the UTXO  ✓

The VOUT index of the UTXO  ✓

A field indicating the length of the unlocking script.  ✓

The scriptPubKey.&#x20;

**51. What else is included with the inputs?**

The number of outputs being created.&#x20;

The scriptSig needed to spend the input.  ✓

The scriptSig's sequence number.  ✓

All of the above.&#x20;

**52. What are the outputs composed of?**

The number of outputs being spent.&#x20;

The value in satoshis to be locked into the output script  ✓

A field defining the length of the scriptPubkey.  ✓

The output scriptPubkey or locking script.  ✓

**53. If the transaction has an input with a non-final sequence number and an nLockTime in the future, what is it considered to be?**

An automated payment.&#x20;

Inside a payment channel.  ✓

An invalid transaction.&#x20;

A future transaction.&#x20;

**54. How much data can be theoretically expressed in each output?**

18 Kilobytes&#x20;

18 Gigabytes&#x20;

18 Megabytes&#x20;

18 Exabytes  ✓
