---
description: Stack operations
---

# Chapter 3 video 4

| Script                                                                                                                                                                   | Video                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- |
| Bitcoin script is a very simple programming language, but with a distinct quirk in its nature that makes it quite different to other more familiar languages out there.  | Todd                                                                                                            |
| Bitcoin script uses reverse polish notation and a pair of stacks to manage all data being processed in a script                                                          | Show animation of script processing and data items being added to main stack, sent to alt-stack and moved back. |
| The stacks are known as the Main stack and the Alt stack.                                                                                                                | Todd                                                                                                            |
| The main stack is where all opcodes in the programming language do their work.                                                                                           | Show opcodes changing main stack                                                                                |
| The ALT stack is simply a Last In First Out buffer that is accessible via the opcodes OP\_TOALTSTACK and OP\_FROMALTSTACK.                                               | Todd                                                                                                            |
| OP\_TOALTSTACK takes the topmost data item from the main stack and places it at the top of the alstack.                                                                  | Show OP\_TOALSTACK animation                                                                                    |
| OP\_FROMALTSTACK takes the topmost data item from the altstack and places it at the top of the main stack                                                                | Show OP\_FROMALTSTACK animation                                                                                 |
| The stack operations in Bitcoin script provide essential functionality for managing and manipulating data during script execution.                                       | Todd                                                                                                            |
| These operations ensure the proper flow of data between the Main stack and the Alt stack.                                                                                |                                                                                                                 |
| This feature empowers developers to process data effectively and adapt script behavior based on specific requirements.                                                   | Todd                                                                                                            |
|                                                                                                                                                                          |                                                                                                                 |
