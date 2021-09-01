# reading-notes-401


## Reading 28 Hash Tables

*Hash* - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

*Buckets* - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

*Collisions* - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

Hash tables are a data structure that means every Node or Bucket has a key and a value paired. 
This allows us to have an easy lookup of a value by utilizing its' key. The lookup of the specific Id is O(1) Time complexity.

Collisions occur when more than one key hashes to the same index in an array. If a key ever does get put into the same bucket we should be able to handle that.

The collisions are solved by changing the initial state of the buckets.  Instead of starting them all as null we can initialize a linked list in each one. Now if two keys resolve to the same bucket then their pair gets stored in a linked list in the hashmap location.

[Table Of Contents](README.md)