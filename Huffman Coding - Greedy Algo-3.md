October 16, 2025

Two main parts in Huffman Coding: 
1. Build a Huffman Tree from input characters. 
2. Traverse the Huffman Tree and assign codes to characters. 

Example: 
``` output

character frequency
a             5
b             9
c             12
d             13
e             16
f             45
```

- Build a min heap that contains 6 nodes where each node represents root of a tree with single node.
- Extract two minimum frequency nodes from  min heap. Add new internal node with frequency e.g., 5 + 9 = 14. 

Now we have min heap on the left side and max  heap on the right side, or you could say the bigger value. 

![heap-image](https://media.geeksforgeeks.org/wp-content/uploads/20220906180150/1.png)

