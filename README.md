# hashtable

1. A hash table (also known as a hash map) is a data structure that uses an abstract data type called an associative array and may map keys to values.
In order to find the necessary value from an array of buckets or slots, a hash table uses a hash function to create an index, also known as a hash code.

2. An associative array is a collection of key-value pairs with the ability to obtain a value via a key. A hash table is an implementation of an associative array. A hash table internally uses a hash function to convert a key value into an index that identifies the location of the item in memory. Search, insertion, and deletion operations on hash tables are quick.

## Hashing:
In a hash table, a new index is processed using the keys. And, the element corresponding to that key is stored in the index. This process is called hashing.

## Using a Map Object

The Map object was created to implement this type of associative array without some of the downsides of using a basic Object:

1. A Map object has a size property to track its contents.

2.  A Map object can have keys that are any data type.

3. A Map has been optimized for repeated addition and insertion of key-value pairs.

## Uses of Hash Table:

it is used when :

1. constant time lookup and insertion is required
2. cryptographic applications
3. indexing data is required

## Good Hash Functions:
1. Division Method
2. Multiplication Method
3. Universal Hashing: In Universal hashing, the hash function is chosen at random independent of keys.




