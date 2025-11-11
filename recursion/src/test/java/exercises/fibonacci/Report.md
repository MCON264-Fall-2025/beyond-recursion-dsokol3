fibonacci
In this assignment, I implemented two versions of the Fibonacci algorithm: recursive and iterative. The recursive
version follows the mathematical definition directly but becomes very slow as n increases because it repeats work many
times. The iterative version uses a simple loop and two variables, which makes it much faster and efficient.

For the linked list part, I implemented the recursive version of inserting a node at the end of the list. It works
by checking if the list is empty or if we are at the last node, and then adding the new node there. The recursive calls
make it simple to write, but for very long lists it could cause a StackOverflowError.

Overall, recursion is pretty, but iteration is faster and safer when working with large inputs.

