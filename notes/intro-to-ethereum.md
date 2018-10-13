Ethereum is a network of computers operating 24/7 in a decentralized environment where codes can be created and run by anyone. Codes are immuatble and trustworthy.

Vitalik Bulterin created Ethereum so that DApps should all be created on the Ethereum blochain.

Unlike Bitcoin, Ethereum is programable to create DApps. Ether has no limit, but annual cap of ethers can be created up to 18 millions. Ethereum new blocks are discovered for every 15 seconds and each block reward is 5 eth.

Ethereum us a network and ether is the fuel to power the network. Ether is needed to pay transaction fees, launch a contract, and call functions from a contract.

EVM (Ethereum Virtual Machine) is a program run on the Ethereum network that runs smart contracts.

Smart Contracts are codes that programed by delopers and deployed to the ethereum network when trsactions are verifed.

Anyone can interact with the smart contract. To call the method from the smart contract, a transaction is needed to be sent to that smart contract.

Gas us a unit in ether needed to invoke a smart contract method, paid by the sender. Gas is needed to deal with turing completion (looping).

Ethereum nodes parse and verify the blockchain, provide an interface to create transactions and mine blocks.

Ethereum account contains four fields
* The nonce, a counter used to make sure each transaction can only be processed once
* The account's current ether balance
* The account's contract code, if present
* The account's storage (empty by default)

There are two types of accounts: externally owned accounts, controlled by private keys, and contract accounts, controlled by their contract code.

Transactions contains:
* The recipient of the message
* A signature identifying the sender
* The amount of ether to transfer from the sender to the recipient
* An optional data field
* A STARTGAS value, representing the maximum number of computational steps the transaction execution is allowed to take
* A GASPRICE value, representing the fee the sender pays per computational step
