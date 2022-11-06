# Bitcoin Blockchian

## INTRODUCTION TO BITCOIN
------------------------------------------

> Bitcoin was the first digital currency to facilitate the instant transfer of value across <br> the world without a central authority like a bank.

Bitcoins cannot be printed. They are produced by computers all around the world using a free software and are held electronically.


## OPERATIONS IN A BITCOIN SYSTEM
------------------------------------------

1. Transaction Management
    - transfer of coins from one addrerss to another
2. Currency Generation
    - regulating of menetary value for bitcoin



## BITCOIN CONTROLLED SUPPLY
------------------------------------------

- Bitcoin supply is limited for the currency to have value.

- Each block produced contains new Bitcoins created from nothing.

- The total number of bitcoins have a cap at 21 million. Thus no more than 21 million bitcoins will ever be created.

- The rate of block creation is adjusted every 2016 blocks.

- At the desired rate of 1 block per 10 mins, 2016 blocks should take exactly 2 weeks to mine. Thus if the last 2016 block have taken more tha 2 weeks. The difficulty is reduced. Consequently, if they took less than 2 weeks, the difficulty is increased.

- The number of bitcoins generated per block decreases by 50% every 210,000 blocks.



## WAYS TO GET BITCOIN
------------------------------------------

Before getting bitcoin, a user must first install a virtual wallet on a computer or mobile device where bitcoins can be received.

1. Buying Online
    - First create an account in an online exchange
    - The online exchange can then be used to buy and sell bitcoin on your behalf
2. Buying with Cash
    - Choose a purchase method
    - Platforms like LocalBitcoins will help you find people near you willing to exchange Bitcoins for cash.
    - There are ATMs that send bitcoins to your wallet in exchange for cash.



## BUYING BITCOINS FROM AN EXCHANGE
------------------------------------------

1. Choose an exchange 
    - Choose an exchange by entering your country of residence and then selecting from a list of exchanges.
2. Set up an account
    - Set up an account on the exchange. Various forms of identification are required depending on the exchange.
3. Connect bank account
    - Connect one or more bank accounts to your exchange account for buying or selling of bitcoins.
4. Select amount
    - Select an amount of Bitcoins to purchase, enter your Bitcoins address and confirm purchase.


## BEST BITCOIN EXCHANGES
------------------------------------------

1. Coinbase
    - one of the world's largest bitcoin exchanges.
2. SpectroCoin
    - quick and easy exchange offering more than 20 payment options.
3. Indacoin
    - let's you buy Bitcoin and 700 other coins with Visa and MasterCard.
4. Kraken
    - best exchange for deposit and purchase of Bitcoins on the same day.
5. LocalBitcoins
    - an escrow service that helps match Bitcoin buyers and sellers



## WALLETS
------------------------------------------

> Bitcoin wallets are digital wallets where private keys are used to access the Bitcoin <br> address and signature for transactions.

Technically, Bitcoins are not stored anywhere.

There is a private key matched to every Bitcoin address which can be saved in the Bitcoin wallet of the person who owns the balance.

Thus Bitcoin wallets facilitate sending and receiving Bitcoins and gives ownership of the Bitcoin balance to the concerned user.


## TYPES OF BITCOIN WALLETS
------------------------------------------

1. Software wallets
2. Web wallet
3. Hardware wallets
4. Brain wallet
5. Mobile wallet


## BEST BITCOIN WALLETS (BY TYPES)
------------------------------------------

1. Software wallets
    - Armory, Bitcoin Core, MultiBit HD
2. Web wallets
    - Coinbase, Blockchain, Circle
3. Hardware wallets
    - Ledger, Trezor, Opendime
4. Mobile wallets
    - Breadwallet, Mycelium, Bitcoin Wallet



## GENERATE A JAXX WEB WALLET
------------------------------------------

Step 1: Visit https://jaxx.io to set up Jaxx web wallet
Step 2: Click on the chrome buttom to download Jaxx for Chrome.
Step 3: Click on 'Create New Wallet' from the Jaxx extension
Step 4: Click 'Continue' after accepting Terms and Conditions of the wallet'
Step 5: Your wallet will get generated for transactions



## GENERATE AN EXODUS SOFTWARE WALLET
------------------------------------------

Step 1: Visit https://exodus.io to download Exodus software wallet
Step 2: Click on the download button
Step 3: Select the download file that supports your operating system
Step 4: Click on the downloaded file to install the wallet software
Step 5: Click on the Exxodus icon to open the wallet



## EXAMPLES OF WHERE TO USE BITCOINS
------------------------------------------

1. Spending Bitcoins
    - Spending online:
        (a) common household items
        (b) gift cards
        (c) video games

    - Spending offline
        (a) food - there is a coffee shop in Prague that only accepts Bitcoins
        (b) travel - you can book for hotels, buy tickets of ships, cruises, flights using Bitcoins

2. Places to Spend Bitcoin
    - Overstock.com: 
        first big online retailer to accept Bitcoins
    - Shopify stores:
        e-commerce platform where you can pay in Bitcoin
    - CheapAir: 
        choose your flights and pay with Bitcoins
    - Expedia: 
        provides option to pay for their hotel bookings with Bitcoin
    - eGifter:
        popular gift card site accepting Bitcoins as payments
    - Reeds Jewelry Inc.
        American jewelers where you can purchase jewelry with Bitcoins
    - Newegg:
        an electronic retail giant that accepts Bitcoins
    - Dish:
        satellite TV nd internet provider that started accepting Bitcoin payments in 2014
    - Microsoft:
        you can use Bitcoin to deposit funds into your Microsoft account




## DOUBLE SPENDING PROBLEM
------------------------------------------

*Scenario: If Joey uses his 5 BTC in more than one transaction.*

> Spending the same Bitcoin in more than one transaction is called Double Spending Problem.



## ENCOUNTERNG DOUBLE SPENDING IN BLOCKCHAIN
------------------------------------------

The security measure which prevent double spending in Blockchain are as follows:

1. Transaction details are sent to all oe as many nnodes in the network.
2. Blockchain is constantly growing and each peer maintains their own copy of Blockchain (i.e distributed ledger)
3. Blockchain ensures that any modification in the block will lead to recomputing of the subsequent blocks until a consensus is reached
4. Anyone can validate the transactions and and this validation prevents double spendinng.


## PSEUDONYMITY IN BITCOIN
------------------------------------------

> Pseudonymity is the near anonymous state in which users have disguised identities and <br> do not disclose their true identities.

- Bitcoin is a permissionless blockchain where you don't need to set up an account.
- The public and private keys are generated by the wallet.
- The address acts as an identifier or pseudonym of a user's transaction.

Therefore Satoshi Nakamoto recommended that users use a new address for each transaction to avoid the transactions being linked to a common owner.


## BITCOIN ADDRESSES
------------------------------------------

> The Bitcoin address correspondsd to a public key based on ECDSA (Elliptic Curve <br> Digital Signature Algorithm) used in the Bitcoin.

A wallet can have many such addresses and can be used for transactions.


## BITCOIN TRANSACTIONS UTXOs
------------------------------------------

UTXO or Unspent Transaction Output is the fundamental building block of Bitcoin.

*Scenario: Ross wants to send 0.15 BTC to Joey.*

(Before): Ross has a total of 3.21BTC in his wallet distributed in three bytes: 3, 0.2, 0.01 BTCs.

Ross makes the transaction: He destroys the byte containing the 0.2 BTC in order to send 0.15 BTC to Joey.

(After): The remaining 0.05 BTC creates a new output, and is available in Ross' wallet as another byte, thereby reducing his balance to 3.06 BTC.



## BITCOIN TRANSACTION STRUCTURE
------------------------------------------

A Bitcoin transaction has three pieces of information
1. Input:
    - This is a record of which Bitcoin address was used to send the Bitcoin to the receiver in the first place. Also referred to as the unspent trasaction output.
2. Amount:
    - This is the amount of Bitcoins the sender sends to the receiver
3. Output:
    - This is sent to the sender's address as change. It is the new unspent transaction output for his wallet.



## BITCOIN SCRIPT: FEATURES
------------------------------------------

All Bitcoin transaction have scripts embedded into their inputs and outputs.

- Bitcoin Scripts is a stack-based programming language like Forth.
- A list of instructions are recorded with each transaction.
- Opreations in Bitcoin are composed of opcodes. Bitoin scripts have a total of 256 opcodes.
- Bitcoin Script describes how the person can access the Bitcoin if they want to spend them.
- Bitcoin Script is *turin incomplete*.

***NOTE***: Turin incomplete means one cannot have looping conditions in the code. Thus, output from the code is like a boolean: true or false.


## BITCOIN SCRIPT: EXAMPLE
------------------------------------------

*Scenario: Joey verifies the transaction is initiated by Ross.*

- Transaction from Ross is initiated (T<sub>Ross->Joey</sub>)
- Public key of Ross, K<sup>R</sup><sub>pub</sub>, is sent along with the signature, S<sub>R</sub>(T<sub>Ross->Joey</sub>) which Joey can verify.

- Bitcoin transfers scripts instead of signature and the public key.
- Joey can spend Bitcoin only if both the scripts return true after execution.


## BITCOIN SCRIPT: CONSTRUCTION
------------------------------------------

The script consists of a trnsaction input and a transaction output. The two kinds of scripts are called *unlocking script* and *locking script*.

Unlocking script is referred to as *scriptSig* while locking script is referred to as *scriptPubKey*.

Unlocking script is provided by the user to resolve the encumbrance.

The locking script is found in a transaction output, and is the encumbrance that must be fulfilled to spend the output.

The unlocking script consists of the receiver's private key and public key. The locking script is created as follows:

- the receier's public key is duplicated
- a hash is generated for the receiver's public key.
- this hash is compared with the public key hash of the received transaction. 
- the two are compared, and if they are equal, the receiver's private key is used to unlock the transaction. Thus making it available in his wallet.
![Bitcon Script Construction b](../../../../../mnt/d/programming/Blockchain-Solidity-SmartCntracts/blockchain-course/lesson3-Bitcoin-Blockchain/3.9-bitcoin-script-construction/bitcoin-script-construction2.png)