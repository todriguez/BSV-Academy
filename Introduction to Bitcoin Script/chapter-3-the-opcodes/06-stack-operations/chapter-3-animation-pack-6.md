# Chapter 3 animation pack 6

Animate the following functions:

<table><thead><tr><th width="134">Word</th><th width="177">Input</th><th width="175">Output</th><th>Description</th></tr></thead><tbody><tr><td>OP_SWAP</td><td>x1 x2</td><td>x2 x1</td><td>The top two items on the stack are swapped.</td></tr><tr><td>OP_2SWAP</td><td>x1 x2 x3 x4</td><td>x3 x4 x1 x2</td><td>Swaps the top two pairs of items.</td></tr><tr><td>OP_ROT</td><td>x1 x2 x3</td><td>x2 x3 x1</td><td>The top three items on the stack are rotated to the left.</td></tr><tr><td>OP_2ROT</td><td>x1 x2 x3 x4 x5 x6</td><td>x3 x4 x5 x6 x1 x2</td><td>The fifth and sixth items back are moved to the top of the stack.</td></tr><tr><td>OP_ROLL</td><td>xn ... x2 x1 x0 &#x3C;n></td><td>... x2 x1 x0 xn</td><td>The item <em>n</em> back in the stack is moved to the top.</td></tr></tbody></table>
