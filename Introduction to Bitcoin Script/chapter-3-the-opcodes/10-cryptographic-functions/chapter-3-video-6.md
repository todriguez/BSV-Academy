---
description: Cryptographic features
---

# Chapter 3 video 6

| Script                                                                                                                                                                                                          | Video                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Bitcoin's cryptographic functions exist as a set of tools within the protocol that allow peers who manage their identity off-chain to show their intent via the blockchain.                                     | Todd                                                                                              |
| The functions are broken into two groups: Hash functions, and signature checks using the Elliptic Curve Digital Signature Algorithm.                                                                            | Animate table 1 below script                                                                      |
| It is important to note that there are no encryption features in Bitcoin, and 100% of the Bitcoin protocol is in plain text.                                                                                    | <p>Todd<br><br>Show 'no encryption' in text</p>                                                   |
| Although the Bitcoin protocol itself does not include encryption features, it does allow for the insertion of data into transactions, including the possibility of incorporating encrypted data.                | <p>Todd<br><br></p>                                                                               |
| However, for the encrypted data inserted into Bitcoin transactions to be utilized, a second-layer system is required. This system enables the data owner to locate and decrypt the information at a later date. | Show encrypted data being pushed into a transaction script and then used by a second order system |

#### Table 1:

| Hash Functions                   | ECDSA Checks            |
| -------------------------------- | ----------------------- |
| OP\_RIPEMD160                    | OP\_CHECKSIG            |
| OP\_SHA1                         | OP\_CHECKSIGVERIFY      |
| OP\_SHA256                       | OP\_CHECKMULTISIG       |
| OP\_HASH256 (Double SHA256)      | OP\_CHECKMULTISIGVERIFY |
| OP\_HASH160 (SHA256 + RIPEMD160) |                         |
