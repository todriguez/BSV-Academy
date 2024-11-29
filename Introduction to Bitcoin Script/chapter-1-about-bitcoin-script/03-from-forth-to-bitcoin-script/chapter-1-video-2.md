---
description: A video on the basics of Bitcoin transactions
---

# Chapter 1 video 2



| Script                                                                                                                                                                   | Video                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| Bitcoin transactions can be described as spending coins that were created in previous transactions as inputs, and using the satoshis they contain to create new coins.   | Evan's head                                                                                                                |
| Each coin consists of a value in satoshis and a lockScript.                                                                                                              | Visualisation of a transaction with 3 outputs, each containing a value and a lockScript                                    |
| When a user creates a new transaction, they reference the specific output from a previous transaction that they intend to spend                                          | Show a new transaction being created where it imports one of its inputs from one of the outputs of an earlier transaction. |
| and supply a valid solution to its lockScript. This solution is called the unlockScript (or scriptSig) and it typically includes the spending party's digital signature. | Show that the unlockScript is included in the input with a signature.                                                      |
| In the Bitcoin evaluator, the unlockScript is loaded onto the stack and then processed using the Bitcoin script contained in the lockScript.                             | Detatch unlockScript and lockScript, swap from right to left and join. Show evaluation bar.                                |
| For a transaction to be valid, all of its inputs must have valid unlockScripts.                                                                                          | Show all inputs to new transaction solving true                                                                            |
|                                                                                                                                                                          |                                                                                                                            |
