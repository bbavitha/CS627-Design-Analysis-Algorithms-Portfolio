# GitHub Portfolio: Assignments and Projects

Welcome to my GitHub portfolio! This repository showcases my work on various assignments and projects completed as part of my academic and professional journey. Below, you will find details about each project, including objectives, methodologies, and outcomes.

---

## Projects Overview

### 1. Array Reversal Algorithm
**Objective**:  
Develop an efficient in-place algorithm to reverse an array for a mobile application that plays audio files backward.

**Key Features**:
- Memory-efficient algorithm using in-place reversal (no additional memory allocation).
- Time Complexity: `O(n)`, where `n` is the size of the array.
- Space Complexity: `O(1)`.

**Highlights**:
- Measured runtime performance for various input sizes (500, 1500, and 2500 elements).
- Visualized performance trends using Python's Matplotlib library to understand scalability.

**References**:
- [Chrono Library Documentation](https://en.cppreference.com/w/cpp/chrono)
- [Matplotlib Visualization Guide](https://matplotlib.org/stable/contents.html)

---

### 2. Greedy Algorithm for File Organization
**Objective**:  
Implement a greedy algorithm to efficiently allocate files of varying sizes across multiple disks, minimizing wasted space.

**Key Features**:
- Greedy approach prioritizing larger files for minimal storage wastage.
- Time Complexity: `O(n log n + n ⋅ m)`, where `n` is the number of files and `m` is the number of disks.
- Limitations of the greedy algorithm discussed against a brute-force approach.

**Highlights**:
- Explored the trade-offs between greedy and brute-force methods for optimization.
- Analyzed time complexity for different scenarios to assess scalability.

**References**:
- [Introduction to Algorithms (Cormen et al.)](https://mitpress.mit.edu/books/introduction-algorithms)
- [Algorithm Design (Kleinberg & Tardos)](https://www.pearson.com/)

---

### 3. Ternary Search Algorithm for Playlist Lookup
**Objective**:  
Optimize search operations in a playlist using the ternary search algorithm.

**Key Features**:
- Comparison between ternary search (`O(log₃(n))`) and binary search (`O(log₂(n))`).
- Implementation of divide-and-conquer strategies for efficient search operations.

**Highlights**:
- Examined the advantages of ternary search in distributed or parallel systems.
- Discussed use cases where binary search might be preferred for faster results.

**References**:
- [GeeksforGeeks Guide on Ternary Search](https://www.geeksforgeeks.org/ternary-search/)
- [The Art of Computer Programming (Knuth)](https://www.addisonwesley.com/)

---

### 4. Dynamic Programming for Image Comparison
**Objective**:  
Compare two binary images row by row using a dynamic programming approach to measure similarity.

**Key Features**:
- Constructs a cost grid to calculate the minimum difference between corresponding rows.
- Time Complexity: `O(I ⋅ J ⋅ K)`, where `I` is the number of rows, and `J` and `K` are the row lengths.
- Space Complexity: `O(J ⋅ K)` for the cost grid.

**Highlights**:
- Optimal solution ensures minimal transformation cost for aligning two images.
- Evaluated performance against a defined threshold to classify images as "Similar" or "Different."

**References**:
- [Algorithm Design (Kleinberg & Tardos)](https://www.pearson.com/)
- [Engineering Optimization (Rao)](https://www.wiley.com/)

---

## How to Use This Repository
1. **Navigate Projects**: Each project has a dedicated folder with the associated code, documentation, and test cases.
2. **Run Code**: Refer to the setup instructions within each project folder to execute the programs.
3. **Explore Visualizations**: Where applicable, visualizations have been included to demonstrate algorithm performance.

---

## References
- Cormen, T. H., Leiserson, C. E., Rivest, R. L., & Stein, C. (2009). *Introduction to Algorithms* (3rd ed.). MIT Press.
- Knuth, D. E. (1997). *The Art of Computer Programming: Sorting and Searching* (Vol. 3). Addison-Wesley.
- Kleinberg, J., & Tardos, É. (2006). *Algorithm Design*. Pearson.
- Stroustrup, B. (2013). *The C++ Programming Language* (4th ed.). Addison-Wesley.
- Few, S. (2012). *Show Me the Numbers: Designing Tables and Graphs to Enlighten*. Analytics Press.
