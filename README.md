# base-data-indexer
Subgraph schemas, block monitors, and off-chain data processing scripts tailored for tracking high-speed Base transactions.

High-performance data query pipelines mapping block emissions, event data logs, and tracking systemic parameters across Base node operations.

```json
{
  "network": "base-mainnet",
  "dataSources": [
    {
      "kind": "ethereum/contract",
      "name": "EcosystemAggregator",
      "source": {
        "address": "0xaA95...Contract",
        "abi": "AggregatorABI",
        "startBlock": 5000015
      }
    }
  ]
}
```
