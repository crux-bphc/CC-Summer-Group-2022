# Sorting Techniques

**Bubble sort** : Just like the movement of air bubbles in the water that rise up to the surface, each element of the array moves to the end in each iteration. Therefore, it is called a bubble sort. **Time complexity** $\mathcal{O}(n^2)$

[Bubble sort Tutorial](https://www.geeksforgeeks.org/bubble-sort/)

**Insertion Sort** : Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. **Time complexity** $\mathcal{O}(n^2)$

[Insertion Sort Tutorial](https://www.geeksforgeeks.org/insertion-sort/)

**Merge Sort** : Merge Sort is a Divide and Conquer algorithm. Here, a problem is divided into multiple sub-problems. Each sub-problem is solved individually. Finally, sub-problems are combined to form the final solution. **Time complexity** $\mathcal{O}(nlogn)$

[Merge Sort Tutorial](https://www.geeksforgeeks.org/merge-sort/)

**Quick Sort** : Quick Sort is also a Divide and Conquer algorithm. It picks an element as pivot and partitions the given array around the picked pivot. **Time complexity** : Worst case $\mathcal{O}(n^2)$, Best case $\mathcal{O}(nlogn)$, Average $\mathcal{O}(nlogn)$

[Quick Sort Tutorial](https://www.geeksforgeeks.org/quick-sort/)

**Heap Sort** : Heap sort is a comparison-based sorting technique based on [Binary Heap data structure](https://www.geeksforgeeks.org/binary-heap/) which we looked at last week. **Time complexity** $\mathcal{O}(nlogn)$

[Heap Sort Tutorial](https://www.geeksforgeeks.org/heap-sort/)

**Counting Sort** : Counting sort is a sorting algorithm that sorts the elements of an array by counting the number of occurrences of each unique element in the array (Frequency Table). **Time Complexity**: $\mathcal{O}(n+k)$, where k is the range of elements, it is more efficient than Mergesort for small k.

[Counting Sort Tutorial](https://www.geeksforgeeks.org/counting-sort/)

Most common sorting algorithms use the **Merge Sort** as the core of their logic, some others use a hybrid between multiple of the above listed algorithms.

An [optional read](https://theartofmachinery.com/2019/01/05/sorting_is_nlogn.html) on why the best asymptotic time complexity for sorting algorithms is $\mathcal{O}(nlogn)$.

<br>

# Fun Facts

-   Here’s a dance depicting how the different sorting algorithms work.

    [Sorting Strategies Dance](https://youtube.com/playlist?list=PLcX11VWS1PdA4dSPip8-1JfKxFa32X53y)

-   **Bogosort** : The worst sorting algorithm is Bogosort also known as permutation sort, stupid sort, slow sort, shotgun sort or monkey sort. Bogo sort is an algorithm used to sort the elements of an array by randomly generating different permutations of an array and then checking whether it is sorted or not. It’s based on the generate-and-test paradigm. **Time Complexity** : $\mathcal{O}(n*n!)$

---

Here are some links to practice sorting problems:

1. [CodeForces 339 A](https://codeforces.com/problemset/problem/339/A)
2. [CodeForces 456 A](https://codeforces.com/problemset/problem/456/A)
3. [CodeForces 1092 B](https://codeforces.com/problemset/problem/1092/B)
4. [LeetCode 242](https://leetcode.com/problems/valid-anagram/)
5. [CodeForces 977 C](https://codeforces.com/problemset/problem/977/C)
