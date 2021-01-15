# Hash Tables

### Vocabulary:
  1. Hash: result of an algorithm taking in some information, and coverting it into something else, usually used for security purposes.
  2. Bucket: What is contained inside each space of a hash table.
  3. Collision: when more than one value is assigned to a bucket of a hash table.
  
### Structure:
  1. To store a value: Hash code turns value into an integer. Take the number and calculate the hash wiht an algorithm. Convert the hash to an array index. Store it by appending it to the end of a linked list.
  2. To read a value: Accept a key. Calculate the hash with an algorithm. Convert the hash to an array index. Use the index to access the linked list representing a bucket. Search through the bucket for the node that has the key/value pair you're looking for. 
  3. Hash maps can have any number of buckets, and each bucket can have any amount of data inside it. The fewer buckets, the more data will be inside each, more buckest equals less data inside each. 
### Methods for hash tables:
  1. Add(): adds a new value to the table.
  2. Find(): looks for a value in the table. 
  3. Contains(): will return true or false if the value is in the table.
  4. GetHash(): will look for and return a value if provided the index of where the key/vlaue is located.
  
