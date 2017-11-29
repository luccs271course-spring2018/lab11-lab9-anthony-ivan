# Questions

Try using a `TreeMap` and a `HashMap` instead of `MyHashMap`.

1. Are the resulting word frequencies any different?
- No the frequencies are not different.

2. Is the time performance any different?
- Yes, the three implementations rank as follow Hash, myHash,Tree

3. How are `%` and `Math.floorMod` different? Which works more reliably for computing a hash table index?
- Math.floorMod will not return a negative number. Whereas the modulus operator can. floorMod works more reliably for table indeces;
negative numbers would go out of bounds 

4. What is the time complexity of myHashmap.size()? How could you make it more efficient?
- O(n) is the time complexity of myHashmap.size()
- You can track the size as an integer value that is stored in the object

5. How does this implementation compare to one where you directly use your link node class? 
- Stylistically the code is cleaner as a linked list. 
- Correctness and reliability are the same for both implementations.
- hashMap does however have superior performance.
