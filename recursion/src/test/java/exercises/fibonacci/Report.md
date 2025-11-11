fibonacci
In this assignment, I implemented two versions of the Fibonacci algorithm: recursive and iterative. The recursive
version follows the mathematical definition directly but becomes very slow as n increases because it repeats work many
times. The iterative version uses a simple loop and two variables, which makes it much faster and efficient.

For the linked list part, I implemented insert-at-tail both recursively and iteratively. The recursive version uses one
stack frame per node, which makes it slower and can cause a StackOverflowError for very large lists. The iterative
version uses constant stack space and runs faster.

Overall, recursion is pretty, but iteration is faster and safer when working with large inputs.

