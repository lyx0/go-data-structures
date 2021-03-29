### Linked list vs Array

### Array:
- In an Array each box is indexed and is physically next to each other.

Example:
- Go to the 4th box and change 15 to 16

Adding at the beginning of an array all the elements have to be shifted


### Linked list:
- In a Linked list each box contains the value, and the address of the next element in the list.
- Linked lists don't have to be physically next to each other

Example:
- Go to the head, follow down the path to the 4th box, then change 15 to 16.

Going to the Kth element is slower O(n)
Adding or removing an element at the beginning is faster O(1)

### Doubly linked list
- Each element in a doubly linked list contains the address of the element before, and after its node