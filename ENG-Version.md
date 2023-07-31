# Correlation between Scalability, Performance, and Transaction Time of Blockchains

## Introduction:
Blockchains have gained increasing relevance and popularity, especially with the emergence of cryptocurrencies and decentralized applications (DApps). However, scalability, performance, and transaction time are three fundamental challenges that impact the mass adoption of these technologies. This research aims to investigate the correlation between the scalability, performance, and transaction time of blockchains, focusing on their ability to process transactions efficiently, quickly, and with appropriate confirmation times.

## Definitions:
- **Scalability:** Refers to the ability of a blockchain to handle an increase in the number of transactions or users without compromising its performance. In other words, it is the network's ability to grow and support a higher load of activity without becoming overloaded or facing significant delays. Scalability is a critical consideration, especially in public blockchains, where widespread adoption can lead to a rapid increase in transaction volume.

- **Performance:** Relates to the efficiency and speed with which the blockchain processes transactions. Generally measured in transactions per second (TPS), it indicates how many transactions the network can confirm and process within a given time interval. High performance is desirable, allowing for the processing of more transactions in less time, increasing the utility and viability of the blockchain in various applications.

- **Transaction Time:** It is the period required for a transaction to be confirmed and included in a block on the blockchain. This time can vary depending on the blockchain and factors such as the consensus algorithm used and the current network load. Some blockchains have fast transaction times, taking only a few seconds, while others, especially during periods of high activity, may take longer to confirm transactions.

## Method:
This research is based on data and information collected from reliable academic sources, technical reports, case studies, the Phemex blog, and the article "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" published on the website "news.bitcoin.com," which addresses the issue of blockchain scalability compared to traditional payment systems.

## Results:

### 1. Bitcoin (BTC):
Bitcoin, as the first cryptocurrency, played a fundamental role in popularizing blockchains. However, it faced significant challenges in scalability and performance. With its Proof of Work (PoW) architecture, Bitcoin has a limited capacity of approximately 7 TPS, and the average transaction confirmation time varies from 10 to 30 minutes. Source: [Bitcoin Scalability Problem - ResearchGate](https://www.researchgate.net/publication/313503768_Bitcoin_Scalability_Problem)

### 2. Ethereum (ETH):
Ethereum is known for supporting smart contracts but also faced scalability challenges. Originally based on Proof of Work (PoW), Ethereum encountered similar limitations to Bitcoin regarding scalability. However, efforts have been made to address this issue, including the transition to Ethereum 2.0 with the adoption of Proof of Stake (PoS) and the implementation of second-layer solutions like the Lightning Network. The average transaction confirmation time on Ethereum varies from 10 to 20 seconds. Source: [Ethereum 2.0: Challenges and Opportunities - Cornell University](https://arxiv.org/abs/2001.08966)

### 3. Binance Smart Chain (BSC):
Binance Smart Chain is a parallel blockchain to Binance Chain that offers smart contracts with higher scalability. Using the Delegated Proof of Stake (DPoS) consensus mechanism, BSC achieves a TPS rate of over 3,000 compared to Ethereum. The average transaction confirmation time on the Binance Smart Chain is about 3 seconds. Source: [An Introduction to Binance Smart Chain (BSC) - Binance Academy](https://academy.binance.com/pt-br/articles/an-introduction-to-binance-smart-chain-bsc)

### 4. Solana (SOL):
Solana is a high-performance blockchain known for its scalability. With the innovative Proof of History (PoH) consensus mechanism, Solana achieves an impressive TPS rate of over 65,000, making it one of the fastest and most efficient blockchains in terms of transaction processing. The average transaction confirmation time on Solana is approximately 1 second. Source: [Solana TPS - CoinCodex](https://coincodex.com/article/24666/solana-tps/)

### 5. Optimism (OPP):
Optimism is a scaling solution for Ethereum based on rollups technology. Its goal is to increase the scalability of the Ethereum network, enabling a higher number of transactions per second and reducing transaction fees. By aggregating multiple transactions into a single rollup, Optimism improves the efficiency and performance of the Ethereum network. The average transaction confirmation time on Optimism is about 15 minutes, due to the challenge and response period. Source: [Optimistic Rollups - Ethereum.org](https://ethereum.org/pt-br/developers/docs/scaling/optimistic-rollups/)

### 6. Ripple (XRP):
Ripple is a blockchain focused on international payments and remittances. With its consensus mechanism called the Ripple Protocol Consensus Algorithm (RPCA), the XRP Ledger achieves remarkable scalability, with a capacity of over 1,500 TPS. The average transaction confirmation time on Ripple is just 4 seconds, making it one of the fastest blockchains in terms of transaction time. Source: [The XRP Ledger and Consensus Algorithm - Ripple](https://ripple.com/xrp/)

## Phemex Blog. (2021). What is Transactions Per Second (TPS).
The Phemex blog explains the concept of "Transactions Per Second" (TPS) and its importance in evaluating the performance of blockchains. TPS represents the number of transactions a blockchain can process per second and is a crucial metric for evaluating scalability and performance. A higher TPS generally indicates greater transaction processing capacity and faster confirmation times, while lower TPS can lead to congestion and delays during periods of high demand. The blog also emphasizes that TPS is influenced by the consensus mechanism and the technical architecture of the blockchain. Source: [Phemex Blog - What is Transactions Per Second (TPS)](https://phemex.com/blogs/what-is-transactions-per-second-tps)

## Consensus Methods:
The way transactions are validated and included in the blockchain is determined by the consensus method used by the network. Below are some of the most common consensus methods:

### 1. Proof of Work (PoW):
- **Description:** Proof of Work is a consensus mechanism where network nodes (miners) compete to solve a complex cryptographic puzzle. The first node to solve the puzzle has the right to create the next block on the blockchain and receives a reward in cryptocurrencies. The process requires high computational power and is energy-intensive.

- **Advantages:** It is highly secure as it requires a significant amount of computational work to create new blocks, making it difficult to modify previous blocks. Additionally, it is decentralized, as any node can become a miner.

- **Disadvantages:** It is slow and has low scalability due to the competition among miners and the time required to solve the puzzle. Additionally, it consumes a large amount of energy, raising environmental concerns.

### 2. Proof of Stake (PoS):
- **Description:** Proof of Stake is a consensus mechanism in which validators are chosen to create blocks based on the amount of cryptocurrency they "stake" or lock as collateral on the network. The more cryptocurrency a validator has, the higher the

 probability of being chosen to validate transactions and create blocks.

- **Advantages:** It is more energy-efficient compared to PoW as it does not require intensive computational competition. Additionally, it incentivizes active participation of cryptocurrency holders to ensure the security of the network.

- **Disadvantages:** There can be a problem known as "Nothing at Stake," where validators may attempt to validate on multiple chains simultaneously without cost, compromising the network's security.

### 3. Delegated Proof of Stake (DPoS):
- **Description:** DPoS is a variant of PoS where cryptocurrency holders elect representatives called "witnesses" to validate transactions and create blocks on their behalf. Witnesses are periodically selected to act as validators.

- **Advantages:** Greater scalability compared to PoW and PoS, as witnesses are responsible for creating blocks, reducing competition among network nodes. It is also more energy-efficient.

- **Disadvantages:** There may be concerns about centralization, as a limited number of witnesses are responsible for the validation process.

### 4. Proof of History (PoH):
- **Description:** Proof of History is an asynchronous consensus mechanism used by Solana. It provides cryptographic proof that an event occurred at a specific time, allowing network nodes to agree on the order of transactions without the need for direct communication between them.

- **Advantages:** High scalability and efficiency, allowing nodes to agree on the order of transactions without the need for full consensus among all nodes.

- **Disadvantages:** It is not used in isolation as a consensus mechanism but in conjunction with other consensus algorithms like PoS.

### 5. Rollups:
- **Description:** Rollups are a second-layer solution designed to improve the scalability of blockchains by aggregating multiple transactions into a single "rollup" and recording the proof of these transactions on the main blockchain.

- **Advantages:** Increases the processing capacity of the main network, reducing transaction fees and improving efficiency.

- **Disadvantages:** There may be a small challenge and response period before transactions are confirmed on the main blockchain, which can lead to longer confirmation times compared to other direct consensus methods.

### 6. Lightning Network (LN):
- **Description:** The Lightning Network is a second-layer solution designed to improve the scalability and speed of Bitcoin transactions. It allows the creation of payment channels off the main blockchain, where transactions can be conducted instantly and with very low fees. Only when the channel is closed is the final transaction recorded on the main blockchain.

- **Advantages:** Significantly increases the scalability of Bitcoin, allowing a large number of transactions to be processed off-chain. Fast and low-cost transactions.

- **Disadvantages:** Requires users to lock funds in payment channels, which can be inconvenient and limit the total value of transactions that can be made.

### 7. Ripple Protocol Consensus Algorithm (RPCA):
- **Description:** RPCA is the consensus mechanism used by the XRP Ledger, Ripple's blockchain. In this method, a group of validators is periodically chosen to validate transactions and create new blocks. Validators are chosen based on a voting process in which they demonstrate their reliability and reputation.

- **Advantages:** Allows for high scalability and transaction speed. The XRP Ledger is capable of processing over 1,500 transactions per second with confirmation times of approximately 4 seconds.

- **Disadvantages:** Some critics point out that Ripple Labs, the company behind Ripple, has control over the majority of validators, which may raise concerns about the decentralization of the network.

## Relation to the Article "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain":
The article "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" from the website "news.bitcoin.com" highlights the issue of blockchain scalability and misleading comparisons with traditional payment systems like Visa. The article emphasizes the importance of analyzing real data and reliable sources when evaluating the capabilities of blockchains. This critical analysis is relevant to the research project as it reinforces the need to approach blockchain scalability and performance with caution. Additionally, the article underscores how misleading information can lead to unrealistic expectations and distrust in this technology.

## Impact of Misinformation:
It is essential to consider the impact of misinformation when analyzing the capabilities of blockchains regarding scalability and performance. The article "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" highlights how misleading information can lead to unrealistic expectations and distrust in this technology.

## Discussion and Analysis:
The information from the two repeated sections is related to the analysis of the correlation between scalability, performance, and transaction time in blockchains. Scalability is a critical element for enabling mass adoption and widespread use of blockchains. Different consensus methods have significant impacts on scalability, with Proof of Work presenting limitations regarding competition and high energy consumption, while Proof of Stake and Delegated Proof of Stake offer greater energy efficiency and scalability. Additionally, performance, measured in TPS (transactions per second), is crucial for the real-world viability of blockchains. The use of second-layer solutions such as Rollups and the Lightning Network can increase the processing capacity of the main network and reduce transaction fees, making blockchains more practical for day-to-day transactions. Transaction time is influenced by the consensus method and scalability capacity. Blockchains with faster transaction times, such as Ripple's XRP Ledger, may be more suitable for financial applications, where speed and quick confirmation are essential. The article "No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain" highlights the importance of analyzing real data and reliable sources when evaluating the capabilities of blockchains and alerts to the impact of misinformation, which can lead to unrealistic expectations and distrust in this technology.

## Conclusion:
The correlation between scalability, performance, and transaction time is essential for evaluating the viability of blockchains in various use cases. The continuous development of innovative solutions, such as more efficient consensus mechanisms and optimization of scalability layers, will continue to drive the evolution of blockchains, making them more efficient and versatile to meet the needs of the future. The ability to process transactions quickly, securely, and efficiently is fundamental for the mass adoption of blockchains and their application in various industries. It is crucial to approach blockchain scalability and performance with caution and consider the impact of misinformation on the correct understanding of the capabilities of this technology.

## Bibliography:
1. Nakamoto, S. (2008). Bitcoin: A Peer-to-Peer Electronic Cash System. [Available at: https://bitcoin.org/bitcoin.pdf]
2. Eyal, I., & Sirer, E. G. (2014). Majority is not enough: Bitcoin mining is vulnerable. In Financial Cryptography and Data Security (pp. 436-454). Springer, Berlin, Heidelberg. [Available at: https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf]
3. Ethereum Foundation. (2021). Ethereum 2.0: Challenges and Opportunities. [Available at: https://arxiv.org/abs/2001.08966]
4. Binance Academy. (2021). An Introduction to Binance Smart Chain (BSC). [Available at: https://academy.binance.com/pt-br/articles/an-introduction-to-binance-smart-chain-bsc]
5. CoinCodex. (2021). Solana TPS. [Available at: https://coincodex.com/article/24666/solana-tps/]
6. Ethereum.org. (2021). Optimistic

 Rollups. [Available at: https://ethereum.org/pt-br/developers/docs/scaling/optimistic-rollups/]
7. Ripple. (2021). The XRP Ledger and Consensus Algorithm. [Available at: https://ripple.com/xrp/]
8. Phemex Blog. (2021). What is Transactions Per Second (TPS). [Available at: https://phemex.com/blogs/what-is-transactions-per-second-tps]
9. Bitcoin.com. (2021). No, Visa Doesn't Handle 24,000 TPS and Neither Does Your Pet Blockchain. [Available at: https://news.bitcoin.com/no-visa-doesnt-handle-24000-tps-and-neither-does-your-pet-blockchain/]
