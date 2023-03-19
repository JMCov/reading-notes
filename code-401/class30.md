# Hash Tables

**Hashing** - a technique that is used to uniquely identify a specific object from a group of similar objects

**Hash** - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

**Buckets** - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

**Collisions** - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

**Two steps of implementation of hashing:**

  1. An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.

  2. The element is stored in the hash table where it can be quickly retrieved using hashed key.

**Hash function** - any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.

**Hash table** - a data structure that is used to store keys/value pairs. It uses a hash function to compute an index into an array in which an element will be inserted or searched.

**Separate chaining** - one of the most commonly used collision resolution techniques. It is usually implemented using linked lists. In separate chaining, each element of the hash table is a linked list. To store an element in the hash table you must insert it into a specific linked list. If there is any collision (i.e. two different elements have same hash value) then store both the elements in the same linked list.

**Linear probing** - when the interval between successive probes is fixed (usually to 1).

**Quadratic probing** - similar to linear probing and the only difference is the interval between successive probes or entry slots. Here, when the slot at a hashed index for an entry record is already occupied, you must start traversing until you find an unoccupied slot. The interval between slots is computed by adding the successive value of an arbitrary polynomial in the original hashed index.

**Double hashing** - similar to linear probing and the only difference is the interval between successive probes.

[Back to Home](../README.md)
