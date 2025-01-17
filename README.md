# ETH2 Deposit Batching Smart Contract

The Staked ETH2 Deposit Batching smart contract is deployed and verified here: https://etherscan.io/address/0xfC3e2b3003859E28F6eFD8321615731F9b02c81F

With the launch of ETH2 Phase Zero, owners of ETH will be able to deposit ETH to the canonical [ETH2 Deposit contract](https://github.com/ethereum/eth2.0-specs/blob/dev/solidity_deposit_contract/deposit_contract.sol) and become validators on the ETH2 Beacon Chain. The ETH2 Deposit contract only allows once deposit per transaction, while one needs to make one deposit per validator they wish to have.

Staked has created a smart contract that enables depositers to stake N ETH to N / 32 validators within a single transaction, with an upper bound of the block gas-limit. It offers high convenience for large ETH stakers and also saves them transaction costs.

## Technical

**Language:** Solidity

**Compiler:** `0.5.11`
