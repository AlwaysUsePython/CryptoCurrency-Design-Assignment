# Design Features:

1) If msg.gas is above a certain threshold, 10% of the coin minted goes to the msg.sender instead of block.coinbase

2) The amount of cryptocurrency minted is inversely proportional to the wealth of the person who would receive it

3) Cryptocurrency creation is dependent on block.timestamp
 - the later at night, the less minted
 - encourage transactions during reasonable hours
