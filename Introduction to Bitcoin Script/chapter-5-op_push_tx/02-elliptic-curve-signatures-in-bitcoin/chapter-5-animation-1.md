# Chapter 5 animation 1

Show an animation of the following elements being assembled into a signature message

<table><thead><tr><th width="85">Item</th><th width="146">Name</th><th>Description, Length and format</th></tr></thead><tbody><tr><td>1</td><td>nVersion</td><td>The version of the protocol being used to define this transaction - 4 Bytes little-endian integer</td></tr><tr><td>2</td><td>hashPrevouts</td><td>either a SHA256 hash of the transaction's concatenated input source / sources or a 32 byte null string if SIGHASH_ANYONECANPAY is used - 32 Byte hash string</td></tr><tr><td>3</td><td>hashSequence</td><td>the concatenation of the input nSequence value / values or a null string if SIGHASH_ANYONECANPAY is used - 32 Byte hash string</td></tr><tr><td>4</td><td>outpoint</td><td>Outpoint for input being signed - concatenation of input TXID + Vout - 32 Byte transaction hash + 4 Byte little-endian integer</td></tr><tr><td>5</td><td>scriptLen</td><td>Locking script length - a <a href="https://wiki.bitcoinsv.io/index.php/VarInt">VarInt</a> - 1, 3, 5 or 9 bytes depending on script length</td></tr><tr><td>6</td><td>scriptPubKey</td><td>Locking script for output being spent - scriptLen byte string</td></tr><tr><td>7</td><td>value</td><td>Value of input - An integer representing the input's satoshi value - 8 Byte little-endian integer - 4 byte little-endian integer</td></tr><tr><td>8</td><td>nSequence</td><td>Then nSequence value for input being signed - 4 byte little-endian integer</td></tr><tr><td>9</td><td>hashOutputs</td><td>If SIGHASH_ALL is used, this value is the SHA256 hash of the concatenation of all transaction outputs in <a href="https://wiki.bitcoinsv.io/index.php/Bitcoin_Transactions#Format_of_a_Transaction_Output">Transaction output format</a>. If SIGHASH_SINGLE is used, this value is the SHA256 hash of only the output corresponding to the input's Vin index. If SIGHASH_NONE is used, this is a null string - 32 Byte hash string</td></tr><tr><td>10</td><td>nLocktime</td><td>The nLocktime value for the transaction - 4 byte little-endian integer</td></tr><tr><td>11</td><td>sighash</td><td>The SIGHASH flags being applied to this signature - 4 bytes, XX000000 where XX is Sighash Flag</td></tr></tbody></table>