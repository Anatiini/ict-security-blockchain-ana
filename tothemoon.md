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

# Explorer
Block size: How much disk space the block takes. Received time: When the block was validated. Total Transactions: The total number of transactions within the block. Confirmations: The number of times a new block has been accepted to the chain.
Difficulty: the amount of hashes statistically needed to get the block's required hash. Rewards: The amount of bitcoin generated in the block. Block Hash: The hash or "fingerprint" of the block. Merkle root: The hash which contains all the transactions within the block.
![image](https://github.com/user-attachments/assets/8565061c-7491-45fa-a875-1c3a41c54dfd)

# Rogecoin
Arguments in the video, answered to one-by-one.
## Cryptos are far more volatile.
Cryptocurrencies are more volatile, but this is not necessarily a con. There are many people, especially really young people who have amassed their fortunes with cryptocurrencies, since they have the same volatility upwards. They are inherently high-risk high-reward investments.

## Cryptos destroy the environment.
Cryptocurrencies are very intensive on the electrical bill because of the proof-of-work mechanism, which requires one to expend computing power and due to that, electricity. If Bitcoin's energy expenditure would be considered as its own country, Bitcoin would be ranked 27th on the list of most electricity consuming countries, right after Malaysia. The environmental effect is not minimal, but there is also some good news. According to the article, 50% of the energy used in Bitcoin mining comes from renewable sources, so the environmental effect is not as bad as the numbers would seem.

## Cryptos can't be used to buy the vast majority of goods or services.
This one is also true, although there are more and more people and businesses who deal with cryptocurrencies, they are still extremely rare to be used within the confines of the law. Illegal activity and transactions are usually done via cryptocurrencies, since they lack the monitoring trusted third party.

## Cryptos value is false, since they have no practical use and aren't enforced by anything.
There might be some use cases for the technology in the future, but for now it has not had any significant breakthroughs on where it could be used so that it would improve the old system. However, I could see that they have their value, since value is also in many other things regardless of their usefulness. For example, any brand, fashion or otherwise, is usually valuable in the minds of the customer's even though the product's usefulness is not more optimized than its competitors for its use case. There are also things like art. Art pieces value can  vary drastically from person to person.

## Cryptos are unsafe, you can get scammed, hacked, the value plummets or you forget/lose the password and lose all your cryptos.
There are many risks when dealing with a system which is not governed by a trusted third party, this increases the responsibility. One has to know more how the system works, when there isn't any professionals handling the transactions. This makes it riskier than dealing with a trusted third party. On the flip side, you can get scammed or hacked with your regular bank information also. Forgetting your PIN code or bank credentials doesn't end with the money disappearing, but it is much trouble in getting it back, even with the regular systems.

## Cryptos were responsible for the price increase of GPUs.
They weren't solely responsible but they were a major player. The GPUs are pretty advanced and the materials they require are rare. The start of the price increase was partly due to the crypto-mining boom, but the prices have stayed high, since the companies have noticed that people pay the ludicrous prices for their GPUs.

# References
Bitcoin Difficulty. https://www.coinwarz.com/mining/bitcoin/difficulty-chart

Satoshi Nakamoto. Bitcoin: A Peer-to-Peer Electronic Cash System. https://bitcoin.org/bitcoin.pdf

https://terokarvinen.com/trust-to-blockchain/#homework

How Much Energy Does Bitcoin Consume? https://crypto.com/bitcoin/bitcoin-energy-consumption

