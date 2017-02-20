# Concurrency Patterns

***

| # | Name | Description |
|---| ------ | ------------------ |
| 1 | Active Object | Decouples method execution from method invocation that reside in their own thread of control. The goal is to introduce concurrency, by using asynchronous method invocation and a scheduler for handling requests. |
| 2 | Balking | Only execute an action on an object when the object is in a particular state. |
| 3 | Binding properties | Combining multiple observers to force properties in different objects to be synchronized or coordinated in some way. |
| 4 | Blockchain | Decentralized way to store data and agree on ways of processing it in a Merkle tree, optionally using Digital signature for any individual contributions. |
| 5 | Double-checked locking | Reduce the overhead of acquiring a lock by first testing the locking criterion (the 'lock hint') in an unsafe manner; only if that succeeds does the actual locking logic proceed. Can be unsafe when implemented in some language/hardware combinations. It can therefore sometimes be considered an anti-pattern. |
| 6 | Event-based asynchronous | Addresses problems with the asynchronous pattern that occur in multithreaded programs. |
| 7 | Guarded suspension | Manages operations that require both a lock to be acquired and a precondition to be satisfied before the operation can be executed. |
| 8 | Join | Join-pattern provides a way to write concurrent, parallel and distributed programs by message passing. Compared to the use of threads and locks, this is a high-level programming model. |
| 9 | Lock | One thread puts a "lock" on a resource, preventing other threads from accessing or modifying it. |
| 10 | Messaging design pattern (MDP) | Allows the interchange of information (i.e. messages) between components and applications. |
| 11 | Monitor object | An object whose methods are subject to mutual exclusion, thus preventing multiple objects from erroneously trying to use it at the same time. |
| 12 | Reactor | A reactor object provides an asynchronous interface to resources that must be handled synchronously. |
| 13 |  Read-write lock | Allows concurrent read access to an object, but requires exclusive access for write operations. |
| 14 | Scheduler | Explicitly control when threads may execute single-threaded code. |
| 15 | Thread pool | A number of threads are created to perform a number of tasks, which are usually organized in a queue. Typically, there are many more tasks than threads. Can be considered a special case of the object pool pattern. |
| 16 | Thread-specific storage | Static or "global" memory local to a thread. |
