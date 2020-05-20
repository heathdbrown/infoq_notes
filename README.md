# infoq_notes
notes on presentations from infoq

## Mastering Chaos A netflix Guide to Microservices

https://www.youtube.com/watch?v=CZ3wIuvmHeM

### CAP Theorem - https://en.wikipedia.org/wiki/CAP_theorem

"In theoretical computer science, the CAP theorem, also named Brewer's theorem after computer scientist Eric Brewer, states that it is impossible for a distributed data store to simultaneously provide more than two out of the following three guarantees:[1][2][3]

* Consistency: Every read receives the most recent write or an error
* Availability: Every request receives a (non-error) response, without the guarantee that it contains the most recent write
* Partition tolerance: The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes

When a network partition failure happens should we decide to

* Cancel the operation and thus decrease the availability but ensure consistency
* Proceed with the operation and thus provide availability but risk inconsistency"

Everything fails be prepared

### What is a stateless services?
* Not a cache or a database
* Frequently accessed metadata
* No instance affinity
* Loss of a node is a non-event
