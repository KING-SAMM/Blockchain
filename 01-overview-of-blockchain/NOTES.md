BLOCKCHAIN
------------------------------------------

Blockchain is a decentralized ledger of all transactions (digital records) across a peer-to-peer network. It is a technology that enables Bitcoin and is also applied to many business processes. 

It not only performs transactions but also ensures anonymity and security of its users.

At its core, blockchain is simply a chain of blocks. When using using the words 'block' and 'chain', we are referring to digital information - the block, stored in a public database - the chain



HISTORY OF BLOCKCHAIN
------------------------------------------

1990 :-         The concept of distributed ledgers has been around since 1990. The application, Bitorrent, leverages this tech to share media files.
2009 :-         Satoshi Nakamoto created Bitcoin and introduced the concept of blockchain which used distributed ledger + advanced cryptography.
2011 - 2012 :-  Cryptocurrency deployment in applications like wallet and exchange platforms.
2012 - 2013 :-  This allwed cryptocurrencies to be used in currency transfers and digital payment systems.
2013 - 2014 :-  Financial markets and applications started using blockchain beyond cash transactions. The evolution of blockchain gave rise to:
2014 - 2015 :-  Evolution of smart contrcts, and:
2015 - 2016 :-  Permissioned Blockchain network solutions.
2016 - 2017 :-  Market development and exploration across industries.



ISSUES IN BANKING SYSTEM
------------------------------------------

1. Certain transactions take a long time (even days to complete)
2. High cost of transactions (due to intermediaries, e.g the bank)
3. Account Hacking
4. Net frauds
5. Financial Crisis (This can put your money at risk if it is held by a bank)
6. Every bank maintains its own ledger, thus the banks need to update them independently and reconcile periodically.


BLOCKCHAINN SOLUTION FOR THE ISSUES
------------------------------------------

1. Transactions are very fast, completeing almost immediately
2. In the banking system, every bank maintains its own ledger, thus the banks need to update them independently and reconcile periodically. The blockchain on the contrary, conprises of a single ledger shared among all participants, thus no separate messaging protocol is required.

Thus, blockchain takled the issues in traditional banking with some of its features mentioned below:

1. Decentralized system
2. Distributed ledger
3. Incentives of validation
4. Concensus Algorithm
5. Advanced Cryptography algorithm


BLOCKCHAIN TRANSACTION PROCESS
------------------------------------------

1. New transaction is requested.
2. The reqested transaction is broadcasted throughout the network and picked up by various miners who are part of the network
3. Each miner runs some computation in order to validate the transaction.
4. Once validated, the transaction becomes part of the new block created.
5. The new block is, in turn, added to the blockchain.

This is how a new transaction is completed.


STEPS OF BLOCKCHAIN TRANSACTION
------------------------------------------

Blockchain transaction works by implementing one of the following features in each step:
1. Cryptography Algorithm
2. Decentralized Network
3. Concensus Mechanism
4. Distributed Ledger


TRANSACTION INITIATION:
FEATURES OF BLOCKCHAIN: 1.CRYPTOGRAPHY ALGORITHM
------------------------------------------

It is an algorithm that is used to alter data from plain text (readable format) to ciphertext (protected format) and back to plain text

    Plaintext -> (Encryption) -> Ciphertext -> (Decryption) -> Plaintext

There are two kinds of cryptographies
    1. Asymmetric key cryptography, and
    2. Symmetric key cryptography


ASYMMETRIC KEY CRYPTOGAPHY
------------------------------------------

Asymmetric key cryptography uses two kinds of keys 
    - the public key (encrypt message using public key)
    - the private key (decrypt message using private key)



SYMMETRIC KEY CRYPTOGAPHY
------------------------------------------

Symmetric key cryptography uses only one key - the secret key - for both encryption and decryption

The Bitcoin Blockchain uses asymmetric key cryptography in order to leverage the public key and private key of users to create digital signatures for initiating a transaction which is eventually propagated through the network.




DIGITAL SIGNATURE
------------------------------------------

- A digital signature provides authentication and validation, like normal signatures
- It ensures the security and integrity of data recorded on the Blockchain
- It uses asymmetric cryptography in which information can be shared using a public key
- Primary keys are linked to users providing digital signatures a quality of nonrepudiation


DIGITAL SIGNATURE CREATION
------------------------------------------

1. The signer takes a information to be transmitted and runs a hash algorithm to generate a 32 or 64 bit hash value.
2. This hash value is encrypted using the signer's private key.
3. The result is a digitally signed document which is broadcasted into the network.
4. Once the verifier receives this document, he decrypts it using the signer's public key.
5. The hash value created after decryption is then compared with another hash value generarted locally by the verifier using the same hash algorithm as the one used by the signer.
6. If the hash valus are equal, then the signature is considered valid and the verifier can then use the document.


GENERATION OF A PUBLIC-PRIVATE KEY PAIR, AND A DIGITAL SIGNATURE
------------------------------------------

1. Visit: https://andersbrownworth.com/blockchain/public-private-keys/keys
2. Click on 'Random' to generate public and private keys
3. Click 'Signature' tab
4. Enter a message in the message field and click on the 'Sign' button
5. Visit the 'Verify' tab and click on 'Verify' button to verify the digital signature
6. Change the message in the 'Message' tab and click on 'Verify'



TRANSACTION BROADCAST:
FEATURES OF BLOCKCHAIN: 2. DECENTRALISED NETWORK
------------------------------------------

A decetraluzed network is a system wjere miners play an important role im the validation of transactions taking place


TYPES OF NETWORKS
------------------------------------------

1. Centralized network
2. Decentralized network

Blockchain is built on a decentralized network which can be identified by a peer-to-peer connections of miners who play an important role in the validation of every transaction.


Centralized network is characterized by a mandatory centralized point, which can be a client, a hub, or a piece of hardware through which all data on the  network must pass.



FEATURES OF CONCENSUS:
FEATURES OF BLOCKCHAIN: 3. CONCENSUS ALGORITHM
------------------------------------------

Concensus algorithm is a concept from Computer Science which is used to reach an agreement on a specific data value when the system is ditributed

Thus concensus algorithms provide reliiability in a network consisting of unreliable nodes.



CONCENSUS PROTOCOL
------------------------------------------

A Concensus Protocol is a fault-toleraant protocol that is used to acheive the necessary agreement on a single data value, on a single state of network.

It is a set of rules that decide on the contribution of the various participants of the blockchain.

It ensures that all transactions ocurring on the network are genuine and all participants agree on the concensus of the ledger.



FEATURES OF CONCENSUS PROTOCOL
------------------------------------------

1. Efficiency - Consensus makes exchanges quicker and simpler as no third party is required.
2. Security - this is ensured by NOT having a single poit of failure. Secentralization ensures that even if one device fails, the data continues to be secure elsewhere.
3. Real ime
4. Reliable - It isimpossible to tamper witth the contents of a block without it being noticed as along with the daystamp. This provides a non-repudable statement binding your work to a point in time.
5. Functional - Consensus is making the blockchain more functional due to its adoption in various industries for development of new applications.


MINERS and ROLE OF MINERS
------------------------------------------

Miners are an integral part of the bitcoin ecosystem who ensure fairness and keep the network stable, safe and secure by approving transactions.

Miners have to provide a solution to complex Mathematical problems which is called Proof of Work.


PROOF OF WORK
------------------------------------------

Proof of Work is a consensus algorithm in the blockchain network that is used to confirm the transactions, using a Mathematical puzzle or a challenge, and produces a new block within the existing blockchain.

Proof of Work comprises of three main characters: 
1. Nonce
2. Hash
3. Transaction



NONCE
------------------------------------------

Nonce: Number used Once

It is a random number whose value is set so that the hash of the block will contain a run of leading zeros. Thus, it is the number that blockchain miners are solving for.



HASH CODE
------------------------------------------

Hash code is a numeric value which assists in identifying an object at the time of equality testing. It also serves as an index for the object.

- The purpose of hash code is to assist in efficient lookup and insertions in data collections that are contingent on a hash table.
- Hash code is generated by taking an input and converting it to cryptographic output using Mathematical algorithms.
- hash of x is represented by H(x).
- Thus Hash code is an algorithm that converts a sequence of characters into a string of 64 letters or numbers.


HASH POINTER
------------------------------------------

A Hash pointer is a pointer to the location where information or hash of that information is stored.

- If we retrieve information that a pointer points at, we can get hash of the information and confirm it to be unchanged.
- It requires information of previous hash.

- Like a regular pointer, it lets us locate information. Unlike a regular pointer, it also lets us verify that the information has not been tampered.



GENERATION OF NONCE
------------------------------------------

Step 1: https://andersbrownworth.com/blockchain/block and observe the the nonce value
Step 2: Enter some data in the data field and click on 'mine'. Observe that a new nonce and hash are generated



GENERATION OF HASH VALUE
------------------------------------------

Step 1: Visit https://andersbrownworth.com/blockchain/hash 
Step 2: Enter some data in the data field and observe the change in the hash value.


PROOF OF STAKE
------------------------------------------

Proof of Stake is a low cost, low energy-consuming algorithm that states that a person can mine and validate transactions based on how many coins (cryptocurrency) s/he holds.

1. Anyone who holds the base cryptocurrency can become a validator, - although sometiimes a locked-up deposit is required.

2. A validator's chance of mining a block is based on how much stake or cryptocurrency they have. 

For example, if you owned 1% of the cryptocurrency, you would be able to mine 1% of all its transactions.


3. The Proof of Stake protocol will randomly assign the right to create a block between selected validators based upon the value created by their stakes. The chosen validator will be rewarded with a part of or the whole of the transaction fees.



PROOF OF ELAPSED TIME
------------------------------------------

Proof of Elapsed Time is a consensus algorithm that prevents high energy consumption and resourse utilization by following lottery system.

Each participant in the network is required to wait for a randomly chosen time period. The one who completes the designated waiting time wins the new block.



PRACTICAL BYZANTINE FAULT TOLERANCE (PBFT)
------------------------------------------

Practical Byzantine Faut Tolerance (PBFT) improves the robustness and performance of transactions by directing peer-to-peer messages with minimal latency.

- The blockchain operator configures and operates the blockchain network
- To this network, smart contracts are deployed and executed on peer nodes
- The applications are then used to invoke the smart contracts
- Though the exact network structure depends on the consensus mechanism, PBFT has a leader, validating and non-validating peers.
- Consensus messages flow between the appropriate peers to ensure that the blockchain's smart contract transactions are kept in order



BLOCKCHAIN BLOCK STRUCTURE
------------------------------------------

A block comprises of 3 parts:

1. Header - contains version information, nonce, previous block ID, and timestamp
2. Merkle - hash built from block's transaction identifiers
3. Transaction List - contains identification of hashes included in the block's merkle tree


BLOCKCHAIN IDENTIFIERS
------------------------------------------

1. Block Header
2. Block Heigth

Block Header is a primary identifier of a block. It is the digital fingerprint twice the size of the block. It serves as a unique identification for a block, and has 32 byte hash.

Block Height is the position of a block in a blockchain. The first block, called the Genesis Block, is of height 0. Each node dynamically identifies a block, thus height of a block is comsidered the number of blocks that the chain has between itself and the Genesis block. The height of a blockchain is generally taken to be the height of its highest block in a chain with the maximum total dificulty, which is the lenght of chain minus 1.


BLOCKCHAIN MERKLE TREE
------------------------------------------

Blockchain Merkle Tree is a data structure used for summarizing and verifying the integrity of large sets of data. It is also known as a binary hash tree.

Merkle Root



MERKLE ROOT
------------------------------------------




ADVANTAGES OF A MERKLE TREE
------------------------------------------

1. Merkle tree provides a way of proving integrity of the data.
2. Menmory or the disk space required is very low.
3. The proofs in a merkkle Tree is computed quickkly and easily.
4. Merkkle Trees also provide validation of the data.
5. Merkle Roots require very less information to be transmitted across the network.



FEATURES OF BLOCKCHAIN: 4. DISTRIBUTED LEDGER
------------------------------------------

A distributed ledger can be defined as a concensus of shared, replicated and synchronized data in digital format which is geographically spread across the globe. It has no central administartor or single data storage point.




