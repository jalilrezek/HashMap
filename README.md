**Overview**

HashMaps are valuable data structures allowing for idealized O(1) operations. However, upon insertion, a "collision" may occur if another item is already present at the index that the new
entry was mapped to. In this case, it is important to use collision resolution strategies. Furthermore, when the hashmap's underlying array becomes full, one must "rehash" to a new
HashMap with a heightened capacity. Two strategies are used here: chaining, and open addressing. I implemented one hash map using chaining, and another using open addressing.

I also tested my two implementations with targeted unit tests and high-input stress tests. 

Lastly, I tested the performance of these two implementations using JMH Runtime Test benchmarking tool.

**Files**

The chaining hash map implementation is at main/java/hw7/hashing/ChainingHashMap.java

The open addressing implementation is at main/java/hw7/hashing/OpenAddressingHashMap.java

Tests for both implementations are at test/java/hw7/MapTest.java

Benchmarking results are at main/java/hw7/README.md
