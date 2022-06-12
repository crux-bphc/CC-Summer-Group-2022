# Frequency Tables

Frequency tables are used to keep track of how many times a certain element occurs within a list of elements.

[Frequency Table Tutorial](https://www.geeksforgeeks.org/counting-frequencies-of-array-elements/)

Note that sometimes, the array elements are too large and you can't always use a **vector** to maintain the count. In such cases, you can use a **map** or **unordered_map** to achieve the same result.

Note that sometimes, the array elements are too large so you can't always use a vector to maintain the count. In such cases, you can use a [map](https://www.geeksforgeeks.org/map-associative-containers-the-c-standard-template-library-stl/). However this would result in an $\mathcal{O}(log n)$ lookup time as compared to the $\mathcal{O}(1)$ with vectors.  
You can use [unordered_map](https://www.geeksforgeeks.org/unordered_map-in-cpp-stl/) for large array elements for O(1) lookup time but it will not retain the relative order of the elements.

---

Here are some links to practice Frequency Table problems:

1. [Codeforces 1183 D](https://codeforces.com/problemset/problem/1183/D)
2. [Codeforces 525 A](https://codeforces.com/problemset/problem/525/A)
3. [Codeforces 1520 D](https://codeforces.com/problemset/problem/1144/D)
4. [Codeforces 1269 B](https://codeforces.com/problemset/problem/1269/B)
