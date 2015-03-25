# DistributedSystems

## Impossiblity results

* CAP theorem

## Sharding

* Horizontal sharding
* Vertical sharding
* Consistent hashing
* Nomralized and denormalized data structures

## Synchronization

Co-operation between processes to come up with an ordered set of operations

* Mutual exclusion based synchronization
* Wait free synchronization
  * Local writes and reconciliation during read
* Lock free synchronization
* Obstruction free synchronization
* Avoiding synchronization
  * Append only data structures (no overwrite. 1NF acutally supports this)
  * Conflict free replicated data types

## Ordering

* Vector clocks
* Lamport timestamps

## Fairness

* Swimlanes in queues
* Prioritzation and preemption
* Bulkhead pattern

## Back pressure

* Throttling
* Exponential retries
* Timeouts
* Circuit breaking

## Traffic shaping 

* Queuing
* Leaky bucket

## Distributed decision making

* Complete information
* Random decision
* Paxos (Best of random)
