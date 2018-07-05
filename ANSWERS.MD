### Why does LinkedStack not require an explicit constructor?

Because LinkedStack does not require an explicit constructor since you have methods created in its class that you can call. Thus it eliminates the need for a constructor.

### What is the time and (extra) space complexity of each of the LinkedStack methods, as well as ReverseLines.main?

For LinkedStack methods the push, peek, and pop methods have a complexity of T(n) = O(1), and a space complexity of S(n) = 0(1); as they are in constant time. Whereas for the main class in ReverseLines the isEmpty and asList both have a time complexity of T(n) = O(1) and S(n) = O(1); they are in constant time.

### How else (not using Node) could we have implemented LinkedStack in such a way that it is still based on a linked list but the asList method uses constant time and space?

We could have achieve that by using an arrayList as the container so that we have O(n).

### Is it better for push and pop to return the item or the stack itself? Briefly discuss the pros and cons of each design.

Pros:
- Operating on constant time and space is also an advantage.
- Using push and pop methods will utilize less memory thus make them faster.

Cons:
- Returning whole stack at once means that each value is returned at once rather individually.
- Returning a large stack will take time.

