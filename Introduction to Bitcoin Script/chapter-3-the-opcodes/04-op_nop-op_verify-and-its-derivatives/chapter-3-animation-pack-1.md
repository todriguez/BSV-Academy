# Chapter 3 animation pack 1

Show scripts as follows:

`OP_NOP` show that nothing happens

`<input> OP_VERIFY` show that the script continues to process when input is non-zero and fails when it is zero

`<input_1> <input_2> OP_EQUALVERIFY` show that the script continues to process when inputs are exactly equal and fails when they are not equal. Use the following examples

0x01 and 0x01 EQUAL

0x01 and 0x02 NOT EQUAL

0x01 and 0x0001 NOT EQUAL

`<input> OP_NUMEQUALVERIFY` show that the script continues to process when inputs are numerically equal and fails when they are not numerically equal. Use the following examples

0x01 and 0x01 EQUAL

0x01 and 0x02 NOT EQUAL

0x01 and 0x0001 EQUAL

`<signature> <public key OP_CHECKSIGVERIFY` Show the sgnature being checked against the public key and the script either failing or continuing to process.



`OP_1 <signature_1> <signature_2> OP_2 <pubkey_1> <pubkey_2> <pubkey_3> OP_3 OP_CHECKMULTISIGVERIFY` Show all stack items being consumed by opcode. and the script either failing or continuing to process.
