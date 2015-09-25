#Hash Table Project

For this project, you will be creating a simple HashTable object. 

##API - Version 0
This version of HashTable will do a simple put using an object's hashcode. It does not use separate key and value objects. Create the appropriate private fields.

###HashTable()
Default constructor. Initializes to capacity 100.

###HashTable(int capacity)

###public void put(Object obj)
Puts the object in the hashtable. Deals with collisions by placing the object in the next open spot (OR ask John Lima for an even better way of finding an open spot!).

###public String toString()
String representation of the HashTable.

###private void rehash()
Doubles the size of the HashTable and rehashes each item contained within. Should be called anytime calling the put function makes the current fill of the HashTable exceed the load factor.




