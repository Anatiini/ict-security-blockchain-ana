# h4 To the Moon!

# Summarize

## Introduction
  - Commerce on the internet relies on third-party trust. There are no non-reversible transactions possible, and the trust-based system invites fraud into the mix.
  - An electronic payment system, which is based on cryptographic proof instead of trust is introduced. This would allow peer-to-peer transactions without a middle man.
 
## Transactions
  - Electronic coin is defined as a chain of digital signatures. Each coin is verified by digitally signing the hash of the last transaction, and the public key of the new owner. This verifies ownership chain.
  - The problem is the need of trust to prevent double-spending.
  - This is solved by publicly announcing the transactions and by agreeing what transaction is the first for a coin to be used in that transaction.

## Timestamp Server
  - A solution to the need of trust: a hash which contains all the information from a block published with a timestamp to confirm the block's existence at that time period. Also adds the last block's hash to confirm the chain.

## Proof-of-Work
  - The proof-of-work works by searching for a value in which the hash starts with a predetermined number of zero bits. This involves trying nonces until it generates a hash with an x number of zeroes at the start. This requires a lot of computing power and is a proof that work has
    been done, hence the proof-of-work.
  - Solves the problem of majority representation in decision-making. Basically one CPU-one vote basis.
  - The proof-of-works difficulty (how many zeroes at the start of the hash) is variable, to keep the bitcoin stream steady.
## Network
  - This part summarizes how the network functions and constructs its currency.
  - Nodes always consider the longest chain to be the correct one, and the proof-of-work of the next block in the chain validates it to be the first new block in the chain if multiple blocks are created at the same time.
  - All nodes move on to the next validated block when the first proof-of-work concludes.
## Incentive
  - First block starts a new chain, and there is incentive for nodes to support the network and get some coins into circulation.
  - CPU power and electricity expended -> coins collected
  - Transaction fees are placed if the output value of a transaction is less than its input value.

# Wallet

Success! Wallet created.
![image](https://github.com/user-attachments/assets/d195cd3f-234c-49cc-ba36-2442d39546e5)

# Faucet
Yet another success! Money in the bank.
![image](https://github.com/user-attachments/assets/7e51f5c0-8353-40ae-aa6a-e7332e5a6166)

# Giveaway
Sent it to another wallet which I created. Somehow the amount is now less, than what I gained from the faucet, but the transaction had some kind of a fee where it couldn't complete it freely. This might be because the transaction amount was so small that it wasn't "worth" it.
![image](https://github.com/user-attachments/assets/312830ac-49b4-43b1-a2b2-721090dc5971)

# Recycle
And recycled back to the faucet!
![image](https://github.com/user-attachments/assets/d0c41a66-ba29-4b42-badf-4e70cdc21487)
