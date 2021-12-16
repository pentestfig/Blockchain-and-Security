# Blockchain-and-Security

#Introduction to the Blockchain

##What is Blockchain

	+ A distributed record database, validated and maintained by a network of computers 
	instead of one centralized authority such as bank.
	+ No individual has control over them.
	+ A peer-to-peer (P2P) network. 
	+ A digital ledger of data that is replicated at each node.
	+ Nodes discuss and agree on a common consensus algorithm to add recent transactions to chain.
	+ "Timestamp" characterizes every transaction on the chain.
	+ Blockchain is immutable means that once a block is added to chain, it can never be modified or removed.
	+ New blocks are added to previous blocks.
	 

###Real life examples:

	+ Bank account statements
	+ A record keeping book etc.

###Centralized Vs. Decentralized Network

	+ Decentralized network is structured in a shared methodology.
	+ Control is primary difference.
	+ Processing power.
	+ All members of blockchain network is considered equal.

##Blockchain Vs. Cryptocurrency

	+ Blockchain is decentralized ledger of all transactions across P2P network whereas cryptocurrency 
	is a just a medium of exhange stored on the blockchain.	
	+ Cryptocurrencies have monetary value
	+ Blockchain can't be transferred. 
	+ Blockchain is multifaceted that it can be used for even voting process.
	+ Cryptocurrencies are just an application on the top of blockchain
	
##Benefits of Blockchain Technology

	+ Decentralization, P2P, security, open source, trust, ease-of-use, transparency, improved traceability, 
	permanent ledger, cost reduction

##Blocks, Nodes & Network

	+ Blocks: Files that permanently record data on blockchain. It is like a record book. Cannot be changed or deleted. 
	Bitcoin block stores "sender, receiver and the amount transferred". Block hash (a long alphanumeric cryptographic 
	value) is generated. Hash is useful to identify each block. 
	+ Node: Any device that is connected to blockchain network.
	+ Network: Peers are computer systems connected to one another and form P2P network. 

##Blockchain Transactions

	+ Each transaction must be authorized and authenticated before it's added to blockchain. 
	+ Keys authenticate users to access their wallets or accounts. 
	+ Every user has unique private key and public key is accesible by everyone
	+ Majority of nodes show consent that transaction is legitimate. Rewards are given to the people who verify transactions 
	to encourage them. this is called proof-of-work (PoW).



##Crytographic Hash Functions

	+ Hash function is function that compresses a string of random data to a fixed length of data. 


###Properties of Hash Functions

	+ Collision Free: No two input hashes should map to the same output hash
	+ One Way: It should be impossible to reverse the hashing (one-way function).

	

##Wallets and Keys

	+ A wallet is an application that holds both private and public key and it communicates with various blockchains 
	to let user send or receive digital currencies. 
	+ When users send you digital currencies, they basically sign off ownership at your wallet's address.
	+ Private key in your wallet must match the public address with which the currency is allocated to.


##Markle Tree

	+ It is a hash-based data structure wherein each leaf node is a hash of a data block. 
	+ It usually has a factor of branching 2, which means that each node has up to 2 children.
	+ It is use for effective data validation. 
	+ Completely secure because  hashes are used instead of complete files. Hashes are way to encrypt files that are 
	slightly smaller in size.


##Consensus Mechanisms

	+ Protocols to make sure all nodes are synchronized and agree on which transactions are legitimate and are to be 
	added to blockchain. 
	+ Without a proper consensus mechanisms, blockchains are vulnerable to various attacks. 
	+ They are simply a method to decide within a group. 


##Working Principle of Mining

	+ Mining is process of recording pending transactions by adding new blocks to the blockchain. 
	+ Miners are rewarded by new coins of that blockchain.

###Types of mining process

	+ Pool mining: A group of miners merging their resources to mine the Blockchain more quickly.
	+ Solo mining: Each miner set up their own equipment and registers themselves for mining. 


##Public & Private Blockchains

	+ Private and public blockchains have their own advantages & disadvantages in term of performance, privacy and security. 

###Public Blockchain

	+ Anyone can read and write without explicit permission.
	+ More complex rules and consensus algorithms.
	+ Computationally expensive to mine.
	+ Computational power is disturbed globally.

###Private Blockchain
	
	+ Only authorized nodes can read and write.
	+ Security is easier
	+ One authorized node can be arbitrator for any dispute.
	+ Less expensive to mine.
	+ Example: Hypeprledger, R3, corda, etc.


##Blockchain Fork
	
###What is Fork?

	+ Fork is a modification to the protocol on the blockchain. 
	+ Basically, a separation from previous blockchain. 
	+ Sometimes nodes in the blockchain cannot come to an agreement on the potential existence of blockchain which 
	splits it to two or more blockchains temporarily or permanently.  
	
###Reasons
	
	+ Adding new features
	+ Fixing security issues
	+ Transaction reversing

###Types of Forks

####Hard Forks

	+ When there is a modification in a software running on the blockchain, new blocks will be mined under the new 
	rules. And these blocks will not be deemed legitimate by old software version. 
	+ A radical modification that makes new blocks invalid in previous chain.
	+ This essentially creates fork.
	+ Usually, occurs when there is enough support from mining community, when majority votes for it.
	+ Example: Casper shifting from PoW to PoS. 

 
####Soft Forks

	+ New blocks mined under new rules are also legitimate by the older version of the software (reverse-compatibility).
	+ Example: SegWit introduced new kind of address, Bech32. This did not invalidate the existing P2SH addresses.

