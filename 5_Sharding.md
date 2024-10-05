# Sharding
- https://aws.amazon.com/what-is/database-sharding/

## What I learned
- Database sharding is the process of storing a large database across multiple machines.
- Benefits
  - Improve response time
  - Avoid total service outage
  - Scale efficiently
- Database sharding operates on a shared-nothing architecture. Each physical shard operates independently and is unaware of other shards. 
- Good shard-key selection can evenly distribute data across multiple shards. When choosing a shard key, database designers should consider the following factors. 
  - Cardinality
  - Frequency
  - Monotonic change
- ***Comparison of database sharding and partitioning***
  - Partitioning stores all data groups in the same computer, but database sharding spreads them across different computers.

## English words I learned
- [ ] monotonic change
