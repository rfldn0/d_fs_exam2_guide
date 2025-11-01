October 31, 2025
## Chapter 7 – Trees

### 1. Structure and Terminology

- **Tree**: A hierarchical data structure with nodes.
    
- **Binary Tree**: Each node has at most two children.
    
- **Full Binary Tree**: Every node has 0 or 2 children.
    
- **Complete Binary Tree**: All levels are filled except possibly the last, which is filled from left to right.
    
- **Formulas**:
    
    - Number of nodes in a full binary tree: 2n+12n + 1
        
    - Height of a tree with nn nodes: ⌊log⁡2(n)⌋\lfloor \log_2(n) \rfloor
        

Tree Terminology and Basics – GeeksforGeeks

### 2. Full vs Complete Binary Trees

- **Full**: Every node has 0 or 2 children.
    
- **Complete**: All levels are filled except possibly the last, which is filled left to right.
    

Full vs Complete Trees – GeeksforGeeks

### 3. Tree Traversal Techniques

- **Inorder (LNR)**: Left → Node → Right
    
- **Preorder (NLR)**: Node → Left → Right
    
- **Postorder (LRN)**: Left → Right → Node
    
- **Level-order**: Breadth-first traversal using a queue.
    

Tree Traversals Explained – Programiz

### 4. Huffman Coding

- A greedy algorithm for lossless data compression.
    
- Steps:
    
    1. Count character frequencies.
        
    2. Build a priority queue.
        
    3. Merge nodes to form a binary tree.
        
    4. Assign binary codes to characters.
        

Huffman Coding – GeeksforGeeks

### 5. Recursive Function Evaluation

- Understand base and recursive cases.
    
- Use recursion trees or trace tables to follow execution.
    
- Common in tree traversals and divide-and-conquer algorithms.
    

Understanding Recursion – Khan Academy

### 6. Heap Insertion and Deletion

- **Insertion**: Add to the end, then "heapify up".
    
- **Deletion (usually root)**: Replace root with last element, then "heapify down".
    

Heap Operations – GeeksforGeeks

## Chapter 8 – Sorting

### 1. Sorting Algorithms and Characteristics

|Algorithm|Stable|In-Place|Notes|
|---|---|---|---|
|Bubble Sort|Yes|Yes|Simple, inefficient|
|Selection Sort|No|Yes|Always O(n²), few swaps|
|Insertion Sort|Yes|Yes|Good for small or sorted data|
|Merge Sort|Yes|No|Divide and conquer, fast|
|Quick Sort|No|Yes|Fast average, poor worst case|
|Heap Sort|No|Yes|Good worst-case, not stable|
|Counting Sort|Yes|No|Non-comparison, for integers|
|Radix Sort|Yes|No|Non-comparison, digit-based|

Sorting Algorithms Overview – Visualgo

### 2. Time Complexities

|Algorithm|Best|Average|Worst|
|---|---|---|---|
|Bubble Sort|O(n)|O(n²)|O(n²)|
|Selection Sort|O(n²)|O(n²)|O(n²)|
|Insertion Sort|O(n)|O(n²)|O(n²)|
|Merge Sort|O(n log n)|O(n log n)|O(n log n)|
|Quick Sort|O(n log n)|O(n log n)|O(n²)|
|Heap Sort|O(n log n)|O(n log n)|O(n log n)|
|Counting Sort|O(n + k)|O(n + k)|O(n + k)|
|Radix Sort|O(nk)|O(nk)|O(nk)|

Sorting Time Complexities – Big-O Cheat Sheet