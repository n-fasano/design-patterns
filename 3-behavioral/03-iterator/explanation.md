In object-oriented programming, the iterator pattern is a design pattern in which an iterator is used to traverse a container and access the container's elements. The iterator pattern decouples algorithms from containers; in some cases, algorithms are necessarily container-specific and thus cannot be decoupled.

#### What problems can the Iterator design pattern solve?

* The elements of an aggregate object should be accessed and traversed without exposing its representation (data structures).
* New traversal operations should be defined for an aggregate object without changing its interface.

Defining access and traversal operations in the aggregate interface is inflexible because it commits the aggregate to particular access and traversal operations and makes it impossible to add new operations later without having to change the aggregate interface.

#### What solution does the Iterator design pattern describe?

* Define a separate (iterator) object that encapsulates accessing and traversing an aggregate object.
* Clients use an iterator to access and traverse an aggregate without knowing its representation (data structures).