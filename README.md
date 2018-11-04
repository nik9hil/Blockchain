# Blockchain
WHAT IS BLOCKCHAIN?
In simple words, Blockchain can be defined as a chain of the block that contains information. The technique is intended to timestamp digital documents so that it's not possible to backdate them or temper them.
The blockchain is used for the secure transfer of items like money, property, contracts, etc. without requiring a third-party intermediary like bank or government. Once a data is recorded inside a blockchain, it is very difficult to change it.
The blockchain is a software protocol (like SMTP is for email). However, Blockchains could not be run without the Internet. It is also called meta-technology as it affects other technologies. It is comprised of several pieces: a database, software application, some connected computers, etc.

BLOCKCHAIN ARCHITECTURE
A Blockchain is a chain of blocks which contain information. The data which is stored inside a block depends on the type of blockchain.
For Example, A Bitcoin Block contains information about the Sender, Receiver, number of bitcoins to be transferred.
The first block in the chain is called the Genesis block. Each new block in the chain is linked to the previous block.

WHAT MAKES BC SO SPECIAL?
A block also has a hash. It can be understood as a fingerprint which is unique to each block. It identifies a block and all of its contents, and it's always unique, just like a fingerprint. So once a block is created, any change inside the block will cause the hash to change.
 
Therefore, the hash is very useful when you want to detect changes to intersections. If the fingerprint of a block changes, it does not remain the same block.
Each Block has
Data
Hash
Hash of the previous block
Consider following example, where we have a chain of 3 blocks. The 1st block has no predecessor. Hence, it does not contain the previous block. Block 2 contains a hash of block 1. While block 3 contains Hash of block 2.
 
Hence, all blocks are containing hashes of previous blocks. This is the technique that makes a blockchain so secure. Let's see how it works -
Assume an attacker is able to change the data present in the Block 2. Correspondingly, the Hash of the Block also changes. But, Block 3 still contains the old Hash of the Block 2. This makes Block 3, and all succeeding blocks invalid as they do not have correct hash the previous block.
 
Therefore, changing a single block can quickly make all following blocks invalid.
 
The blockchain is designed in a way such that the average time for a block to be generated remains fairly constant. In the bitcoin blockchain, the average time for a block to generate is 10 minutes. Other blockchains may have a different time, e.g. 30 seconds, 5 minutes, etc.
The controlled block generation time is achieved by adding a difficulty value inside the block. In bitcoin, the hash of the block must be strictly smaller than a given value to be accepted. The given value varies according to the total computation power of the network. The more powerful the network is, the more smaller the given value, and hence the more difficult it is to generate the block.


Contributors:
Nikhil Bhardwaj- @nik9hil
Darshan Chheda- @darshanc99
Rohit Gupta- @rohiiit
Raj Doshi- @Rajdoshi99
