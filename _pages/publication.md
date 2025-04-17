---
layout: archive
title: "First-author Publications:"
permalink: /publication/
author_profile: true
redirect_from:
  - /resume
---
- **[Mosaic: Client-driven Account Allocation Framework in Sharded Blockchains](https://arxiv.org/abs/2504.10846)** at the 45th IEEE International Conference on Distributed Computing Systems (ICDCS 2025, CORE ranking-A)

  - **Yuanzhe Zhang**, Shirui Pan, Jiangshan Yu.

  - Recent account allocation studies in sharded blockchains are typically miner-driven, requiring miners to
perform global optimizations for all accounts to enhance system-
wide performance. This forces each miner to maintain a complete
copy of the entire ledger, resulting in significant storage, communication, and computation overhead.
In this work, we explore an alternative research direction
by proposing Mosaic, the first client-driven framework for
distributed, lightweight local optimization. Rather than relying
on miners to allocate all accounts, Mosaic enables clients
to independently execute a local algorithm to determine their
residing shards. Mosaic naturally
addresses key limitations of miner-driven approaches, including
the lack of miner incentives and the significant overhead. While
clients are flexible to adopt any algorithm for shard allocation,
we design and implement a reference algorithm, Pilot, to guide
them. Clients execute Pilot to maximize their own benefits, such
as reduced transaction fees and confirmation latency.
We implement and evaluate
Pilot against state-of-the-art miner-driven global optimization
solutions. The results demonstrate that Mosaic significantly
enhances computational efficiency, achieving a four-order-of-
magnitude reduction in computation time, with the reduced input
data size from 1.44 GB to an average of 228.66 bytes per account.
Despite these efficiency gains, Pilot introduces only about a 5%
increase in the cross-shard ratio and maintains approximately
98% of the system throughput, demonstrating a minimal trade-
off in overall effectiveness.


- **[TxAllo: Dynamic Transaction Allocation in Sharded Blockchain Systems](https://ieeexplore.ieee.org/document/10184617/)** at the 39th IEEE International Conference on Data Engineering (ICDE 2023, CORE ranking-A*)

  - **Yuanzhe Zhang**, Shirui Pan, Jiangshan Yu.

  - This work investigated the transaction and account allocation problem in
sharded blockchains to reduce the expensive cross-shard transactions. We formulated and converted this problem and key concepts from the blockchain
domain to the graph domain and proposed a community detection algorithm, TxAllo, to
optimize the throughput on this graph. TxAllo simultaneously considered the number of cross-shard transactions and the workload balance among shards. The experiments illustrate that the ratio of cross-shard transactions can be significantly
reduced from about 98% to 12%. In the meantime, the workload
balance is also well maintained in different shards. For the
adaptive updating method A-TxAllo, the execution time is approximately
800 times faster.


- **[Correlation-aware Next Basket Recommendation using Graph Attention Networks](https://link.springer.com/chapter/10.1007/978-3-030-63820-7_85)** at the 27th International Conference on Neural Information Processing (ICONIP2020, CORE ranking-A)

  - **Yuanzhe Zhang**, Ling Luo, Jianjia Zhang et al.

  - This work investigated the next basket recommendation task and proposed the first end-to-end correlation-aware model to predict the next basket considering intra-basket correlations using graph attention networks. By estimating and aggregating the intra-basket correlations using the attention layer of the self-attention model, the recommendation can be conducted at the basket level, instead of at the item level.


- **[FCP Filter: A Dynamic Clustering-Prediction Framework for Customer Behavior](https://link.springer.com/chapter/10.1007/978-3-030-47426-3_45)** at the 24th Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD 2020, CORE ranking-A)

  - **Yuanzhe Zhang**, Ling Luo, Yang Wang, Zhiyong Wang.

  - Customer purchase behaviour prediction is often limited by the randomness of individual historic transaction data. In the meanwhile, Fragmentation and Coagulation Process (FCP), as a SOTA stochastic customer partition model, does not support forecasting purchase behaviour as such a data-driven method requires transaction observations to conduct clustering. To tackle this challenge, this work proposed FCP filter, a clustering-prediction framework based on FCP. FCP filter utilizes FCP to cluster customers into groups by their temporal interests to filter the individual random noise. A predictor is then built on grouped data and the predicted results are fed to FCP as the prior knowledge at the next time step. We demonstrated that FCP filter can discover a flexible number of latent groups and provide accurate predictions for dynamic purchase behaviour.

