# Collections in Java

A collection in Java refers to group of objects or elements that are managed together. They provide a way to store, organize, and manipulate data efficiently. The Java Collections Framework provides a set of interfaces and classes to manipulate and store collections of objects.

## Interfaces provided by collections

### Collection<E>: 

This is the root interface in the Java Collections Framework. This interface provides basic operations for managing elements such as adding, removing, and querying for the presence of elements. The Collection interface in Java provides several subinterfaces that define more specific types of collections. 

The following are the main interfaces provided by the Collection interface:

* List: Represents an ordered collection of elements. Lists allow duplicate elements and maintain their insertion order. Common implementations include ArrayList, LinkedList, and Vector.

* Set: Represents a collection that does not allow duplicate elements. Sets do not guarantee the order of elements. Common implementations include HashSet, TreeSet, and LinkedHashSet.

* Queue: Represents a collection designed for holding elements prior to processing. Queues typically follow the FIFO (First-In-First-Out) order. Common implementations include PriorityQueue and LinkedList.


### Map<K, V>: 

The Map interface represents a collection of key-value pairs, where each key is associated with exactly one value. It provides operations for adding, removing, and retrieving key-value pairs, as well as methods for checking the presence of keys or values within the map. Common implementations include HashMap, TreeMap, LinkedHashMap.

## Benefits of Collections

- Provides reusable data structures.
- Encapsulates common data management operations.
- Improves code readability and maintainability.
- Supports polymorphism and generality in coding.

## Operations on Collections

- Adding elements
- Removing elements
- Finding elements
- Iterating over elements
- Sorting elements (for ordered collections)

## Example Program

Here's a simple Java program that demonstrates the usage of collections:
```java
import java.util.*;
public class CollectionExample {
    public static void main(String[] args) {
       List<String> names = new ArrayList<>();
        names.add("Ramu");
        names.add("Balu");
        names.add("Raju");
        System.out.println("Names: " + names);
        names.remove("Balu");
        System.out.println("Names after removal: " + names);
    }
} 
```

## References

- [GeeksforGeeks Java](https://www.geeksforgeeks.org/java/)
- [JavaPoint Java Tutorial](https://www.javatpoint.com/java-tutorial)

