# Page 3

_Students must receive a score of 34/38 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers._&#x53;tudents must receive a score of 34/38 to proceed. All questions are multiple choice questions and there could be one or more possible correct answers.

1. How many opcodes make up the scripting language?

48&#x20;

186  ✓

1600&#x20;

436&#x20;

1. What can happen if a minor change is made in how a node processes opcodes?&#x20;

Transactions that were committed to the ledger being rendered unspendable.  ✓

Irreparable damage to the Bitcoin network’s trust and usability.  ✓

Nodes would be forked off on separate chains.&#x20;

Absolutely nothing, nodes are free to process opcodes as desired.&#x20;

1. True or False: It is vital that every node processes each opcode in the script exactly the same way.

True  ✓

False&#x20;

1. A bug in the OP\_CHECKMULTISIG opcode requires nodes to do what, so as to not reject valid, or accept invalid, transactions and blocks?

Check to make sure the user has added an extra data item to their script.  ✓

To reject such transactions until such a time that the bug can be fixed.&#x20;

Add one extra data item to the transaction script.&#x20;

Retain it in case another node is able to build a block containing such transactions.&#x20;

1. Bitcoin Script retains all data items in a byte sequence. Their parameters are either interpreted as \_\_\_\_\_ or \_\_\_\_\_\_ values and the item must fulfil the specifications of those types.

valid, invalid&#x20;

numeric, boolean  ✓

functions, data&#x20;

data, monetary&#x20;

1. The byte sequence of length zero is called the?

null value.  ✓

boolean value.&#x20;

numeric value.&#x20;

zero value.&#x20;

1. If the data item is the null value, what is the boolean value?

0&#x20;

unknown&#x20;

True&#x20;

False  ✓

1. What data items can be interpreted as a boolean value?

Any.  ✓

Only those which the data item consists entirely of bytes with value zero.&#x20;

Big number (bignum) items.&#x20;

Only those specified.&#x20;

1. When script items are processed using opcodes that perform mathematical functions, what does a node treat any byte sequence of up to 7500 bytes length as?

A boolean value.&#x20;

A numeric value.  ✓

A “bignum”.&#x20;

A data item.&#x20;

**10. Who sets the Formal Grammar for Bitcoin Script?**

Satoshi Nakamoto.&#x20;

Users.&#x20;

Node operators.  ✓

Whoever has the most hashpower.&#x20;

**11.  Formal Grammar for Bitcoin Script includes:**

The spelling and function parameters of available opcodes.&#x20;

The complete list of opcodes.&#x20;

Only the opcodes that are functional.&#x20;

The list of opcodes and their exact spelling and function.  ✓

**12. The complete script consists of which sections?**

The unlocking script and the scriptPubKey.&#x20;

The locking script and the scriptSig.&#x20;

The unlocking script and the locking script.&#x20;

All of the above.  ✓

**13. Where does the locking script originate?**

The input which is spending the output&#x20;

The scriptSig.&#x20;

The transaction output that is being sent.  ✓

The unlocking script and the scriptPubKey.&#x20;

**14. Where is the unlocking script included?**

The scriptPubKey.&#x20;

The input which is spent to produce the output.  ✓

The list of opcodes included in the transaction.&#x20;

The transaction output that is being spent.&#x20;

**15. Why do current consensus rules state that an unlocking script can only contain the first 96 opcodes?**

These are the only opcodes currently operational.&#x20;

This allows for constants and data to be pushed onto the stack.  ✓

It is required as part of the Validity of Script Consensus Rule  ✓

All of the above.&#x20;

**16. A branching operator (OP\_IF or OP\_NOTIF) must have?**

A matching OP\_ENDIF.  ✓

An OP\_ELSE.&#x20;

A functional OP\_RETURN.&#x20;

All of the above.&#x20;

**17.  How many OP\_ELSE can be between a branching operator and an OP\_ENDIF?**

There has to be two.&#x20;

Zero.&#x20;

There cannot be more than one.  ✓

As many as the branching operator prefers.&#x20;

**18. Where may OP\_RETURN appear in a valid script?**

OP\_RETURN is not yet restored.&#x20;

At any place.  ✓

If OP\_RETURN is not in a branch block, it will not be evaluated.&#x20;

OP\_RETURN is, by its nature, invalid.&#x20;

**19. What happens to bytes after an OP\_RETURN that are not in a branch block?**

They are evaluated for grammar rules.&#x20;

They will produce a failure if executed.&#x20;

They won’t be evaluated.  ✓

They are invalid.&#x20;

**20. The locking and unlocking scripts for every input of a transaction being spent must be \_\_\_\_, as defined by the \_\_\_\_\_\_.**

PUSHDATA operations, grammar rules&#x20;

Grammatically valid, grammar rules  ✓

Included with OP\_VERNOTIF, unlocking scripts.&#x20;

Valid except for the output scripts, client software implementation policy.&#x20;

**21. The unlocking scripts used in transaction inputs may only contain \_\_\_\_\_ operations.**

OP\_ELSE&#x20;

OP\_VERNOTIF&#x20;

scriptSig&#x20;

PUSHDATA  ✓

**22. What must occur for a byte sequence to validly represent a numeric value?**

Its length must be less than or equal to 50,000 bytes&#x20;

Its length must be less than or equal to 750,000 bytes.  ✓

Its length must be greater than 50,000 bytes.&#x20;

Its length must be greater than 750,000 bytes.&#x20;

**23. What does the stack memory usage consensus rule limit?**

The memory usage allowed for the execution of the unlocking and locking script.  ✓

The amount of memory available to be used on the stacks.&#x20;

The limitations on the network to process transactions containing invalid opcodes.&#x20;

Allows for unlimited memory for the execution of the unlocking and locking script.&#x20;

**24.  How is the Stack Memory Usage Consensus Rule evaluated? (each correct answer is a point)**

Across all node software implementations.&#x20;

Against the sum of the memory used by the stack and the alt-stack.  ✓

By calculating the memory usage of the stack.&#x20;

Usage = sum of (for each element: 32 + size in bytes of element).  ✓

**25. What happens if the execution of the unlocking and locking script for an input uses more memory than defined in the Stack Memory Usage Consensus Rule?**

Then the unlocking scripts and locking script don’t represent a numeric value.&#x20;

They won’t be evaluated.&#x20;

The transaction is invalid.  ✓

The script is not grammatically valid.&#x20;

**26. What are some less important rules which are checked by nodes?**

Pay to Script Hash obsolescence.  ✓

OP\_RETURN limits and restrictions.&#x20;

P2SH utilization.&#x20;

Original OP\_RETURN functionality.  ✓

**27. As needed, node limits have been set so as to be bounded by the hardware/software implementation of the node client. What freedoms does this allow for node operators?**

Configuration settings allow each node operator to manage the in-use settings themselves.&#x20;

Node operators can operate generally how they like as long as it's in agreement with the majority of the network.&#x20;

Node operators are free to use their own configurations as long as they can make sure their blocks can be managed.&#x20;

All of the above.  ✓

**28. How are policies used to determine the validity of blocks or the transactions confirmed by a block?**

By controlling which transactions can be added to a block.&#x20;

They cannot.  ✓

By ensuring only valid transactions make it into a block.&#x20;

By allowing a node operator to configure the settings to meet the validity criteria.&#x20;

**29.  Policies are configured by \_\_\_\_\_\_. These settings are \_\_\_\_\_\_\_\_\_ software implementations. It is expected that as implementations of the software mature that these settings will be adjusted.**

Nakamoto consensus, necessary&#x20;

the network, regarded as outdated&#x20;

node operators, mostly required by  ✓

nodes, generally unnecessary&#x20;

**30. Which is the policy that configures the largest transactions that the software will propagate across the P2P network or include in a block?**

Transaction Size Limit.&#x20;

Maximum Transaction Size Limit.&#x20;

Maximum Acceptable Transaction Size.  ✓

Maximum Acceptable Transaction Propagation Size.&#x20;

**31.  The value of the Maximum Acceptable Transaction Size policy must be \_\_\_\_\_\_\_\_ to the value of the Maximum Transaction Size Consensus Rule, or it will have no effect.**

equal to&#x20;

greater than&#x20;

greater than or equal&#x20;

less than or equal  ✓

**32. What is the default value for the Maximum Acceptable Transaction Size policy?**

100MB&#x20;

1000MB&#x20;

1MB&#x20;

10MB  ✓

**33. The Transaction Evaluation Timeout is a standard policy that defines \_\_\_\_\_\_\_\_ that the software will allow for the evaluation of a transaction \_\_\_\_\_\_\_\_\_.**

the maximum acceptable transaction size policy, by the network&#x20;

the maximum amount of time, before rejecting that transaction  ✓

the maximum amount of time a node can configure its evaluation so, with complex data.&#x20;

the time limit, that is a payment channel.&#x20;

**34. If the evaluation of a transaction is terminated due to exceeding the timeout limit then the software has determined what?**

That the transaction is invalid.&#x20;

That the transaction is valid.&#x20;

The node has chosen not to determine validity.  ✓

The node cannot determine validity.&#x20;

**35. Which policy is set by each node that determines the minimum fee that a node will accept for mining a transaction into a block?**

Minimum Fee Policy.  ✓

Dust policy.&#x20;

Transaction Evaluation Timeout policy.&#x20;

Stack Memory Usage policy.&#x20;

**36.  How are fee rates currently determined?**

By the amount of time it takes for a node to evaluate a transaction priced in milliseconds.&#x20;

By a node determining the expense of processing a transaction and utilizing MinerID and MerchantAPI to form its own unique business model.&#x20;

By applying a cost per byte to the size of the transaction in satoshis to accept or relay that transaction.  ✓

All of the above.&#x20;

**37. Nodes which are mining transactions that are not cached by other nodes must be \_\_\_\_\_\_\_in order to minimize the time needed to transfer the block announcement and those transactions to other nodes.**

closely connected to the network  ✓

cost efficient&#x20;

well equipped with hashpower&#x20;

able to process high frequency low cost transactions&#x20;

**38.  The \_\_\_\_\_\_ is a setting that nodes use to discourage bitcoin users from creating outputs that contain fewer satoshis than it costs to on-spend them at the minimum fee rate. The goal of these policies is to prevent large numbers of low value outputs \_\_\_\_\_\_\_.**

Transaction Evaluation Time Out, with large amounts of data from slowing down the network&#x20;

Dust Rule, clogging up the network  ✓

Minimum Fee Policy, being used to attack the Bitcoin network&#x20;

Minimum Transaction Size Policy, from costing more to process than their fees are worth.&#x20;
