# Pool 1

_Students must receive a score of 15/17 to successfully pass the course._&#x53;tudents must receive a score of 15/17 to successfully pass the course.

1. What does the process of creating blocks require at scale?

Excessive energy consumption.&#x20;

Quantum computers.&#x20;

Purpose-built systems that operate in clusters.  ✓

All of the above.&#x20;

1. What are some of the aspects of managing the bitcoin network that touch many of the major infrastructure elements needed for digital commerce?

Banking infrastructure and custody services.&#x20;

Global telecommunication networks.  ✓

Computing systems.  ✓

Energy grids.  ✓

1. How are all of the bitcoins on the ledger held?

In UTXOs.  ✓

In a rapid access memory database.  ✓

Within the UTXO set.  ✓

Within the scriptPubKey.&#x20;

1. The record of all spendable bitcoin forms a database referred to as what?

The UTXO set.  ✓

The ledger.&#x20;

The blockchain.&#x20;

The rapid access memory database.&#x20;

1. What is held within the global UTXO set?

The outputs that meet both the global network rules and the local node policies.&#x20;

Every spendable output which has not yet been used as an input to a transaction.  ✓

The history of every transaction made on the network.&#x20;

The Merkle proofs and transaction output scripts of all bitcoins.&#x20;

1. How are Nodes currently making their work simpler?

By requiring spenders to provide the Merkle proofs and transaction output scripts.&#x20;

By removing UTXOs that are unlikely to be spent from the set.  ✓

By removing provably unspendable transaction outputs from the UTXO set.&#x20;

All of the above.&#x20;

1. When a node joins the network it is required to \_\_\_\_\_\_\_. This involves downloading and validating a complete set of all of the blocks in the longest valid chain of proof of work, and using the information contained within to reconstruct the current state of the \_\_\_\_\_\_.

validate the most recent block, block chain.&#x20;

perform proof-of-work, block being validated.&#x20;

conduct an initial block download, UTXO set.  ✓

download the UTXO set, network.&#x20;

1. How will newly connected or reconnected nodes likely update themselves in the future?

Using the chain of block headers.  ✓

They won’t need to as nodes will be automatically connected to the longest chain of proof-of-work.&#x20;

They will still need to download all of the blocks that form the longest chain except it will be considerably faster.&#x20;

By downloading the current UTXO set from a trusted party.  ✓

1. How will the ability of nodes to be able to choose subsets of the network they want to manage help the network scale?

By making it easier for nodes with inadequate resources to perform minor transaction processing tasks.&#x20;

By allowing more nodes to operate on the network.&#x20;

By enabling the system to form separate specialized services and nodes.  ✓

All of the above.&#x20;

**10. If a node uses a trusted party to download transactions with current UTXOs that are likely to be spent in the near future, what must it be sure to do in order to handle inputs from previously unseen transactions?**

Keep the UTXO set up to date.  ✓

Acquire UTXO sets from multiple sources.&#x20;

It won’t be able to until it does an initial chain sync.&#x20;

Check with other connected nodes which may have them in their UTXO set.&#x20;

**11. What should a node which uses a trusted party for acquiring its UTXO set do if it disconnects from the network.**

Rebuild the UTXO set by downloading and validating the blockchain.  ✓

Rebuild the UTXO set by downloading and validating any unconfirmed transactions.  ✓

Orchestrate a retrieval of a new UTXO set through a trusted party.&#x20;

It should conduct an initial block download.&#x20;

**12. How are nodes able to minimize storage requirements?**

By utilizing archival services.&#x20;

By pruning elements that are unlikely to be used.  ✓

By removing all transaction information from the ledger and just retaining the block headers.&#x20;

All of the above.&#x20;

**13. How can nodes build their own working blockchain?**

By only retaining the spendable transactions.&#x20;

Through a logical removal of redundant information.  ✓

With the help of trusted parties providing specific UTXO sets.&#x20;

All of the above.&#x20;

**14. What does the working blockchain consist of?**

All of the block headers in the chain.  ✓

Each block header and its connected pruned Merkle tree.  ✓

All of the pruned Merkle trees in the chain.&#x20;

Only the blockheaders that are connected to the desired Merkle trees.&#x20;

**15. A working blockchain allows for what?**

The optimization of data storage for cost management.&#x20;

Users can optimize the information they retain for their own needs.&#x20;

Allows users to use a timestamp to provide provenance.&#x20;

All of the above.  ✓

**16. Users can utilize their own working blockchain using only  \_\_\_\_\_, a service can receive transactions and their corresponding \_\_\_\_\_\_, using them to create \_\_\_\_\_ database of personalized information for the user.**

A UTXO set, blockheaders, a personalized.&#x20;

the block headers, Merkle proofs, an immutable.  ✓

the desired TXIDs, UTXO set, an optimized.&#x20;

the Merkle proofs, blockheaders, a secure.&#x20;

**17. Which section of the Bitcoin white paper defines the use of Merkle path data as a method of validating transactions?**

Section 8  ✓

Section 5&#x20;

Section 6&#x20;

Section 3&#x20;
