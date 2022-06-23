
## a quick look to interview questions 
```bash 
Collection taken from Blockchain interns (from codeeater)
** data structures concepts
** merkle tree idea
** solidity all a to z 
** btc,eth backgrounds 
** defi concepts,implementaions
** suppose u have 5 ether in your address,then write a smart contract which can
     transfer your certain eth to your next a/c after certain timestamp.
**  hashes 
** Cryptography  ..asym, symm.
**  DAO
** infura,hardahat,truffle,
** moralis, ipfs ====> basic concepts 
** Ipfs working 
** Decentralized vs distributed 
** secret sharing/spiltting 
** 
**
**
**
**
**   
 
```
## exploration of new interview questions 🔐🔐🔐🔐


## blockchain ?
```bash 
ledger that is distributed,immutable and decentralized where all transaction are protected by cryptographic algorithm.
```
## principle on which blockchain tech is based on ? 
```bash
based on distributed ledger technology which aims to provide a single source of truth being distributed across network.
```
## types of blockchain network 
```bash 
* public : bitcoin,ethereum
** private : Ripple (XRP), ,multichain,locks tax,
** consortium : Hyperledger
```
## is there any restriction in types of records in blockchain ?
```bash
no
```
## Blockchain vs traditional database 
```bash 
Blockchain : decentralized....can perform only insert operation....work on peer to peer network...no single point of failure...
traditional database : centralized....can perform CRUD operation....master-slave concept...single point failure exists....
```
## key features of blockchain 
```bash
* decentralized
* distributed 
* immutability 
* safety
* concept of mining
```
## encryption ? and its role in blockchain 
```bash 
keeping the data safe...by cryptographic algorithm, concept of public and private key....so to provide authenticity. 
```
## what is block ? 
```bash
blockcahin consists of a list of records/transaction...and that records are stored in blocks... 
```
## what are blocks identifiers ?
```bash 
* block header hash(which is generated from merkle tree) 
* block height (no of blocks in blockchain )
```
## possible to modify data in blockchain ?
```bash
impossible to modify data in that contract....
```
## how does a block is recognised in the blockchain approach ?
```bash 
>> hash
>> transaction data
>> timestamp
```
## is it possible to remove one or more blocks from network in blockchain ?
```bash
no, it can't be done....all are linked so if one block is removed then the chain will break
```
## security of blocks ??
```bash 
* entire blockchain is protected by cryptographic algorithm...
* each block has unique hash pointer, so any modification will change in others too(that will break the chain) so security is tight here.
* also consensus algorithm works here to validate record and to keep it in blocks....Consensus algos : pow,pos,poa, etc

```
## concept of merkle tree ...
```bash
https://www.youtube.com/watch?v=fB41w3JcR7U 

```
## ledger ? 
```bash 
where transaction are recorded . 
```
## centralized, distributed and decentralized systems
```bash
Centralized : that use client/server architecture where one or more client nodes are directly connected to a central server.
Distributed : it doesn’t have a single central owner...users have equal access to data, though user privileges can be enabled 
               when needed.The best example of a vast, distributed system is the internet itself.
Decentralized :  decentralized systems don’t have one central owner. Instead, they use multiple central owners,
                   each of which usually stores a copy of the resources users can access.
 
 💪 Fault tolerance:
Low: Centralized systems
Moderate: Decentralized systems
High: Distributed systems

🔧 Maintenance:
Low: Centralized systems
Moderate: Decentralized systems
High: Distributed systems

🚀 Scalability:
Low: Centralized systems
Moderate: Decentralized systems
High: Distributed systems

```
## mining ?? 
```bash 
process of transaction verification to keep that record in block..
```
## components of blockchain ecosystem 
```bash
* Shared ledger 
* virtual machine 
* node application
* consensus algorithm 

```
## pow vs pos 
```bash 
pow : where miners use high computational computer resources to validate..consume more energy...miners receive block rewards 
pos : stakeholders validate new blocks by utilizing the share of coin...consume less energy....validaters receive transaction fee as reward.

```
## is double spending possible in blockchain ? 
```bash
no....
The Double Spend Problem describes the difficulty of ensuring digital money is not easily duplicated.
the blockchain prevents double-spending by timestamping groups of transactions and then broadcasting them to all of the nodes in the bitcoin network
```
## examples of blockchain application developing platforms
```bash
====>>> ethereum, iota, cardano, hyperledger fabric
```
## 
```bash
* there is no concept of mining in private blockchains. coz nodes are pre-defined initially  
* blockchain saves time and cost too. coz if compare visa speed with solana blockchain ..then solana's speed is on moon.
```
## widely used cryptographic algorithm ?
```bash
* RSA
* AES
* Blowfish 
* Twofish
```
## concept of forking and its types 
```bash
** what happens when a blockchain diverges into two potential paths forward.
** a situation that occurs when two or more blocks have the same block height.
types : hard fork (where old rule is invalid now )
        soft fork (backward compatible )

fork results splitting ethereum into  Ethereum and Ethereum Classic...
          and bitcoin to bitcoin and bitcoin cash..
```
## blind signature
```bash

```
## secret spiltting/sharing
```bash
message/data will be splitted and transferred to trusted parties/nodes....and later on , if we need to retrieve data , we need to collect data from all nodes and it need to be integrated......splitted data is of no use until integration. 
```
## off-chain transaction
```bash

```
## anonymity and pseudonymity 
```bash
example od anonymity : Zcash (no trackdown of transaction,enhanced privacy for its users)
pseudonymity : for long term relation 
```
## how does peer discovery work in p2p network ? 
```bash

```
## what is 51% attack ? 
```bash

```
## durability and robustness ? 
```bash

```
## transparent and incorruptable ? 
```bash

```
## how does bitcoin use blockchain ? 
```bash

```
## how does NFTs use blockchain ?  
```bash

```
## business benefits of blockchain 
```bash

```
## 3 trilemma of blockchain ? 
```bash
>>>> decentralization, security and scalability  
```
## how do you stay upto date with the new and upcoming concept of blockchain ? 
```bash
==>> we can check new/trending coins in coinmarketcap & marketcal , and then we can do research what they are solving/doing in this blockchain field and so on...
==>> joining conference ...
==>> reading blogs/articles of coinmarketcap, tradingview,coingecko and marketcal. 
```
## nonce ? 
```bash

```
## process of blockchain mining ? 
```bash
* transaction....to mempool 
* solve mathematical problem 
* miners solved the problem first 
* miners verify the validity 
* block is added 
```
## Quick look questions a to z
```bash
 
How do we do multiplication in Bignumber's?
using `.mul()` ✅ 
using `*`
using `x`
Other:
 
What does ABI contain?
Its is an arbitrary array, it can contain anything
Contains rules and metadata about functions present in the contract ✅ 
Contains only rules about functions in the contract
Contains only metadata about functions present in the contract
 
What is a Signer?
Ethereum node connection which helps you to read data from state
Ethereum node connection which helps you to write data the state
Ethereum node connection which can write and read ✅ 
Its not an Ethereum node connection
 
If Alice wants a contract to take some ERC20 tokens from her what would she have to do?
Call `transferFrom` function
Call `approve` function
Call `pay` function
Call `approve`, and then some function on the contract which calls `transferFrom` internally ✅ 
 
 
What is a provider?
Ethereum node connection which helps you to read data from state ✅ 
Ethereum node connection which helps you to write data the state
Ethereum node connection which can write and read
Its not an Ethereum node connection
 
When does the code inside `useEffect` get called, if being used with dependent variables?
needs to be explicitly called
runs at a certain time interval
runs on every render of the page
runs every time a dependent state variable changes ✅ 


A transaction has "finality" on Ethereum when it's part of a block that can't change.
True ✅ 
False 
 
What is the technique used by miners to solve the mathematical problem to prove their work to the network?
Bruteforce ✅  
Penetration Attack
Sybil Attack
 
Since blockchains like Ethereum are essentially distributed databases, consensus on the current state need to be met.
True ✅  
False
 
Consensus protocols are impossible to hack/tamper with.
True
False ✅ 
 
 
What is the recommended time, on Ethereum, after which we can almost guarantee a block is not going to be deleted?
approx 15 seconds
approx 1 minute ✅  
approx 2 minutes
 
What is it called when one user tries to pretend to be many different users?
Sybil Attack ✅  
Denver Pretention
Charlie Attack 
 
What is it called when two different blocks are produced and included in parallel?
Finality
Fork ✅  
Proof of Work
 
Which of these is true about Proof of Work? Select all that apply.
Miners are responsible for ensuring no user tries to become a miner
Miners are responsible for producing new blocks ✅  
Miners are responsible for ensuring the network isn't tampered with ✅  
 
 
What are uncle blocks?
Blocks mined after the child block
Blocks that end up getting deleted ✅  
Blocks are that are included after a fork
 
What rule does Ethereum use to enforce that only one state of chain carries, even after a fork?
Sybil Chain
Longest Chain ✅  
Denver Chain
A transaction that costs 100 Gwei today can cost 200 Gwei tomorrow
True ✅
False
 
The value of gas price for a transaction was fixed before the London-upgrade
True
False ✅
 
 
You can change/choose the max gas fee you want to pay for a transaction using a wallet like Metamask
True ✅
False
 
What is the max block size limit possible on the Ethereum network today?
10M Gas
30M Gas ✅
15M Gas
 
Which of the fees is the minimum needed to send a transaction to the network, after the London fork?
Base fee ✅
Priority fee
Gas price
 
The concept of gas fees is bad for the network
True
False ✅
 
 
The cheapest transaction on the Ethereum network is the transfer of $ETH
True ✅
False
 
The London Fork took place in Ethereum's London servers
True
False ✅
  
Which version of the Ethereum network provided better gas estimations for the network?
Pre-London Fork
Post-London Fork ✅
 
If Alice wants to send Bob 1 ETH, assuming the gas price is 100 Gwei, how much ETH does Alice pay in transaction fees (assume pre-London ugprade)?
0.0021 ✅
2100000 ETH
0.021 ETH

Mining pools help individual miners to combine their computational effort to increase the chances of mining blocks
True ✅
False
 
It is very profitable to be a miner, for anybody
True
False ✅
 
 
What consensus mechanism does Ethereum use currently?
PoW ✅
PoS
PoR
 
Mempool is the list of transactions that have been mined
True
False ✅
 
 
Which is a more profitable method of mining?
Using CPUs
Using GPUs ✅
Using APUs
 
Which is the chip that was specifically designed to mine Ethereum?
APUs
ASICs ✅
GPUs
 
Miners exist in the network so as to ensure that users can be controlled
True
False ✅
 
The mining reward for Ethereum is roughly:
2ETH/block ✅
5ETH/block
1ETH/block
 
Miners are paid to mine the blocks
True ✅
False
 
Ethereum will shift to PoR after 2022 
True
False ✅

Which of the following are essential building blocks for the EVM : 
Stack ✅ 
Memory
Program Counter
Arrays
 
What is the data structure which is used to store the Ethereum state called?
Merkle Patricia Trie ✅ 
Graphs
Heaps
Arrays
 
A blockchain fundamentally works on the concepts of cryptography
True ✅ 
False
 
EVM has OPCODES, which represent hardware-level instructions for the virtual machine
True ✅ 
False
 
The EVM supports infinite recursion
True 
False ✅ 
  
Ethereum is a distributed state machine : 
True ✅ 
False
 
Ethereum Virtual Machine is a computer in London that can be accessed remotely
True
False ✅ 
  
There is only one Ethereum Client implementation available - in Solidity
True
False ✅ 
  
Smart contracts on Ethereum can only be written in Solidity
True
False ✅ 
 
The EVM runs on specialized hardware
True
False ✅ 
 
EVM defines the rules of computation for states from block to block.
True ✅ 
False

Who can modify the existing state of a blockchain?
Miners
Satoshi Nakamoto
Nobody ✓

Where are your cryptocurrency assets stored?
In your digital wallet
In 1000's of blockchain nodes ✓
In your bank account

What is a node in a blockchain network?
A programming language
A cryptocurrency token
A computer running the blockchain software ✓

Blockchains can be used for?
Storing and transferring assets
Participating in decentralized governance
Tracking food items across the supply chain
All of the above ✓

What is a genesis block?
The initial state of a blockchain ✓
The Book of Genesis on the blockchain
The first transaction on the blockchain

What is a miner?
A node responsible for verifying and auditing transactions
Someone mining for gold underground
A node responsible for proposing new blocks ✓

What is the term for when a blockchain splits?
Fork ✓
Spoon
Cut

Why do miners do hard work to secure the network?
For block rewards ✓
For goodwill
For fame

What does P2P mean?
Peer to Peer ✓
Product to Product
Password to Private key

Who created Bitcoin?
Satoshi Nakamoto ✓
Craig Wright
John McAfee

What is a blockchain?
A cryptocurrency
A distributed database running on a peer to peer network of nodes ✓
A database run by Satoshi Nakamoto

Who's "Block size" is bigger?
Bitcoin ✓
Ethereum

If you write a smart contract on the Ethereum mainnet... it will be replicated and processed on all the computers on the Ethereum main network.
True ✓
False

Who's "Block time" is shorter?
Bitcoin
Ethereum ✓

You can create your own ERC-20 token without the permission of Ethereum
True ✓
False

In the Serenity/ETH 2.0 patch... Ethereum will move to proof of stake
True ✓
False

What runs Smart contracts?
Ethereum's servers
The Ethereum Virtual Machine (EVM) ✓
Jeff Bezos

Ethereum currently runs on...
Proof of Work ✓
Proof of Stake

What is the native currency of Ethereum?
ETH/Ether ✓
AAVE
Bitcoin
Matic

Which statement best describes Proof of Work?
Miners compete to solve "computational puzzles". The winner of this competition gets to add a block to the blockchain. ✓
Miners with the most currency are allowed to mine and add blocks to the blockchain
Miners work to compute an EVM routing problem. The first miner to solve the problem gets to add blocks to the Blockchain

If uncles are referenced as uncles by a later block
The miner of the uncle gets ether ✓
The miner of the uncle doesn't get anything (like with bitcoin)

 
Which one of the following is an Ethereum address?
2
bc1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh
0x71C7656EC7ab88b098defB751B7401B5f6d8976F ✓
 
What should you do with your private key?
You should share your private key with everyone
You should share your private key with only your friends and family
You should never share your private key ✓

What is an example of seed phrase
1234
abcd
jealous expect hundred young unlock disagree major siren surge acoustic machine catalog ✓
 
What is a crypto wallet?
Crypto wallet manages your seed phrases
Crypto wallet manages the private keys associated with your addresses ✓
Crypto wallet manages your crypto balance
 
What is MetaMask?
An Ethereum crypto wallet ✓
 A Solana crypto wallet
A Bitcoin crypto wallet
 
What is an address?
An address represents a crypto currency
An address represents your account on the blockchain ✓
 an address represents your crypto balance

What are private keys?
Private key is like a password for your address that contains a bunch of letters and numbers ✓
 Private key is another name for an address
Private key refers to a crypto wallet
 
What is a seed phrase?
Seed phrase is like a master password for your crypto wallet ✓
Seed phrase is like a password for your address
Seed phrase is like a password for private key

 
Which of the following environments is NOT supported by Remix?
Javascript VM
Rinkeby Testnet
Ethereum Mainnet
Solana ✓
 
 
Remix allows you to interact with contracts you did not deploy
True ✓
False
 
Remix allows you to write :
Solidity contracts
Solidity tests
Javascript scripts
All of the above ✓
 
 
What does IDE stand for?
Integrated Development Environment ✓
Intelligent Discord Environment
Intentional Developer Experience
 
Which of the following features does Remix NOT support?
Interacting with deployed smart contracts
Importing code from Github repositories
Providing free testnet ether ✓
 
 
You can write code on Remix in languages other than Solidity?
True ✓
 False
 
Which one of the following is NOT a panel in Remix?
File Explorer
Solidity Compiler
Version control history ✓

 
Which is the correct function definition  for returning an unsigned integer array from a function ?

function getArr(uint[] memory _arr) public view returns (uint[] memory) ✓
 function getArr(uint[] memory _arr) public view returns (uint[])
function getArr(uint[] memory _arr) public view returns ([]uint)
 
What is the range of uint8?
2 ** 256 - 1
0 to 2 ** 16 - 1
0 to 2 ** 8 - 1 ✓
 
On which virtual machine does Solidity run?
JVM
EVM ✓
KVM
 
What is the default value of an address variable?
0x0936f87C98E8009f8C4fff9E3994b295761C30ad
0x0000000000000000000000000000000000000000 ✓
0xD9cd57AaECf5813FC41E26CFd55f67Fd72112b75

 
How to get the length of an array in Solidity?
len(arr)
arr.length() 
arr.length ✓

How to add an element to an array in Solidity?
arr.push(i); ✓
arr.add(i);
arr.back(i)
 
What is the significance of the view keyword in the function definition ?
It means that the function can change the state of contract
Function cant change the state of the contract ✓
It doesnt do anything
 
What is msg.sender?
address of the caller ✓
a function name
address of the smart contract
 
What is the significance of public keyword in the function definition ?
Function can only be called internally by the other smart contract functions
Function can only be called externally
It can be called from within the contract and also externally. ✓
 
What does uint stand for?
Signed integer
Unsigned integer ✓
Boolean
 
What are state variables in Solidity?
They are declared inside a function and are not stored on blockchain
They are declared outside a function and stored on the blockchain ✓
They provide information about the blockchain

 
What is the default value of an bool variable?
false ✓
true
```



