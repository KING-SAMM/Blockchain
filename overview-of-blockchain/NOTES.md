BLOCKCHAIN
------------------------------------------
```
Blockchain is a decentralized ledger of all transactions (digital records) across a peer-to-peer network. It is a technology that enables Bitcoin and is also applied to many business processes. 

It not only performs transactions but also ensures anonymity and security of its users.

At its core, blockchain is simply a chain of blocks. When using using the words 'block' and 'chain', we are referring to digital information - the block, stored in a public database - the chain

```

HISTORY OF BLOCKCHAIN
------------------------------------------
```
1990 :-         The concept of distributed ledgers has been around since 1990. The application, Bitorrent, leverages this tech to share media files.
2009 :-         Satoshi Nakamoto created Bitcoin and introduced the concept of blockchain which used distributed ledger + advanced cryptography.
2011 - 2012 :-  Cryptocurrency deployment in applications like wallet and exchange platforms.
2012 - 2013 :-  This allwed cryptocurrencies to be used in currency transfers and digital payment systems.
2013 - 2014 :-  Financial markets and applications started using blockchain beyond cash transactions. The evolution of blockchain gave rise to:
2014 - 2015 :-  Evolution of smart contrcts, and:
2015 - 2016 :-  Permissioned Blockchain network solutions.
2016 - 2017 :-  Market development and exploration across industries.

```

ISSUES IN BANKING SYSTEM
------------------------------------------
```
1. Certain transactions take a long time (even days to complete)
2. High cost of transactions (due to intermediaries, e.g the bank)
3. Account Hacking
4. Net frauds
5. Financial Crisis (This can put your money at risk if it is held by a bank)
6. Every bank maintains its own ledger, thus the banks need to update them independently and reconcile periodically.
```

BLOCKCHAINN SOLUTION FOR THE ISSUES
------------------------------------------
```
1. Transactions are very fast, completeing almost immediately
2. In the banking system, every bank maintains its own ledger, thus the banks need to update them independently and reconcile periodically. The blockchain on the contrary, conprises of a single ledger shared among all participants, thus no separate messaging protocol is required.

Thus, blockchain takled the issues in traditional banking with some of its features mentioned below:

1. Decentralized system
2. Distributed ledger
3. Incentives of validation
4. Concensus Algorithm
5. Advanced Cryptography algorithm
```

BLOCKCHAIN TRANSACTION PROCESS
------------------------------------------
```
1. New transaction is requested.
2. The reqested transaction is broadcasted throughout the network and picked up by various miners who are part of the network
3. Each miner runs some computation in order to validate the transaction.
4. Once validated, the transaction becomes part of the new block created.
5. The new block is, in turn, added to the blockchain.

This is how a new transaction is completed.
```

STEPS OF BLOCKCHAIN TRANSACTION
------------------------------------------
```
Blockchain transaction works by implementing one of the following features in each step:
1. Cryptography Algorithm
2. Decentralized Network
3. Concensus Mechanism
4. Distributed Ledger
```

TRANSACTION INITIATION:
FEATURES OF BLOCKCHAIN: 1.CRYPTOGRAPHY ALGORITHM
------------------------------------------
```
It is an algorithm that is used to alter data from plain text (readable format) to ciphertext (protected format) and back to plain text

    Plaintext -> (Encryption) -> Ciphertext -> (Decryption) -> Plaintext

There are two kinds of cryptographies
    1. Asymmetric key cryptography, and
    2. Symmetric key cryptography
```

ASYMMETRIC KEY CRYPTOGAPHY
------------------------------------------
```
Asymmetric key cryptography uses two kinds of keys 
    - the public key (encrypt message using public key)
    - the private key (decrypt message using private key)

```

SYMMETRIC KEY CRYPTOGAPHY
------------------------------------------
```
Symmetric key cryptography uses only one key - the secret key - for both encryption and decryption

The Bitcoin Blockchain uses asymmetric key cryptography in order to leverage the public key and private key of users to create digital signatures for initiating a transaction which is eventually propagated through the network.

```


DIGITAL SIGNATURE
------------------------------------------
```
- A digital signature provides authentication and validation, like normal signatures
- It ensures the security and integrity of data recorded on the Blockchain
- It uses asymmetric cryptography in which information can be shared using a public key
- Primary keys are linked to users providing digital signatures a quality of nonrepudiation
```

DIGITAL SIGNATURE CREATION
------------------------------------------
```
1. The signer takes a information to be transmitted and runs a hash algorithm to generate a 32 or 64 bit hash value.
2. This hash value is encrypted using the signer's private key.
3. The result is a digitally signed document which is broadcasted into the network.
4. Once the verifier receives this document, he decrypts it using the signer's public key.
5. The hash value created after decryption is then compared with another hash value generarted locally by the verifier using the same hash algorithm as the one used by the signer.
6. If the hash valus are equal, then the signature is considered valid and the verifier can then use the document.
```

GENERATION OF A PUBLIC-PRIVATE KEY PAIR, AND A DIGITAL SIGNATURE
------------------------------------------
```
1. Visit: https://andersbrownworth.com/blockchain/public-private-keys/keys
2. Click on 'Random' to generate public and private keys
3. Click 'Signature' tab
4. Enter a message in the message field and click on the 'Sign' button
5. Visit the 'Verify' tab and click on 'Verify' button to verify the digital signature
6. Change the message in the 'Message' tab and click on 'Verify'
```


TRANSACTION BROADCAST:
FEATURES OF BLOCKCHAIN: 2. DECENTRALISED NETWORK
------------------------------------------
```
A decetraluzed network is a system wjere miners play an important role im the validation of transactions taking place
```

TYPES OF NETWORKS
------------------------------------------
```
1. Centralized network
2. Decentralized network

Blockchain is built on a decentralized network which can be identified by a peer-to-peer connections of miners who play an important role in the validation of every transaction.
```