# README

## Overview
This is the implementation for Carbyne: An Ultra-Lightweight DoS-Resilient Mempool for Bitcoin

The increasing adoption of cryptocurrencies has significantly amplified the resource requirements for operating full nodes, creating substantial barriers to entry. Unlike miners, who are financially incentivized through block rewards and transaction fees, full nodes lack direct economic compensation for their critical role in maintaining the network. A key resource burden is the transaction pool, which is particularly memory-intensive as it temporarily stores unconfirmed transactions awaiting verification and propagation across the network. We present Neonpool, a novel optimization for transaction pool leveraging bloom filter variants to drastically reduce memory consumption by up to 200 (e.g., 400 MB to 2 MB) while maintaining over 99.99% transaction processing accuracy. Implemented in C++ and evaluated on unique Bitcoin and Ethereum datasets, Neonpool enables efficient operation on lightweight clients, such as smartphones, IoT devices, and systems-on-a-chip, without requiring a hard fork. By lowering the cost of node participation, Neonpool enhances decentralization and strengthens the overall security and robustness of cryptocurrency networks.
 
## Preprint
https://arxiv.org/abs/2504.16089

## Carbyne
This package contains the source code for Carbyne: An Ultra-Lightweight DoS-Resilient Mempool for Bitcoin

## Dataset
1. **Mempool State**: https://www.kaggle.com/datasets/mempoolstate/mempool-state-bitcoin

## Included Libraries

The package comes with the following supporting libraries:
- **RapidJSON**: For efficient JSON parsing and manipulation.
- **libbf**: For bloom filter implementation.
- **cppdatetimelite**: For lightweight datetime operations.
- **Helpers Library**: Provides utility functions and transaction structure support for Bitcoin and Ethereum.

## Code Portability

The provided source code is portable and can be adapted to different environments. To run the code:
1. Update the paths to your data files and project directories to match your environment.
2. Ensure all dependencies are correctly configured.

## How to Use

1. Modify the project settings and paths as needed for your environment.
2. Compile and run the project.

For additional information or troubleshooting, refer to the code comments.

## Note

Please ensure that all dependencies are installed and configured before running the projects. If you encounter issues, verify the environment setup and paths are correctly aligned with your system.
