
# Design and Analysis of Algorithims

## a thorough course in the art of programming

### (really a test of my consistency)

# Lab #1

#### 23-01-2020

Questions

* Square Root of a Number
  * Given an integer x, find square root of it. If x is not a perfect square, then return floor(√x).
  * solution : [sqrntnum.cpp](https://github.com/LearningMonkey61/DAA/blob/master/sqrtnum.cpp)
* Missing Number in Arithmetic Progression
  * Given an array that represents elements of arithmetic progression in order, one element is missing in the progression, which you need to find.
  * solution : [apcompletion.cpp](https://github.com/LearningMonkey61/DAA/blob/master/apcompletion.cpp)
* Number of days after which tank will become empty
  * Given a tank with capacity C litres which is completely filled in starting, every day the tank is filled with l litres of water and in the case of overflow extra water is thrown out. Now on i-th day, ‘i’ litres of water is taken out for drinking. We need to find out the day at which tank will become empty the first time.
* Longest Common Prefix
  * Given a set of strings, find the longest common prefix.
  * solution : [longestprefix.cpp](https://github.com/LearningMonkey61/DAA/blob/master/longestprefix.cpp)
* The Skyline Problem
  * Given n rectangular buildings in a 2-dimensional city, computes the skyline of these buildings, eliminating hidden lines. The main task is to view buildings from a side and remove all sections that are not visible.
  * All buildings share common bottom and every building is represented by triplet (left, ht, right)
  * ‘left’: is x coordinated of left side (or wall).
  * ‘right’: is x coordinate of right side
  * ‘ht’: is height of building.
  * A skyline is a collection of rectangular strips. A rectangular strip is represented as a pair (left, ht) where left is x coordinate of left side of strip and ht is height of strip.
  * solution : [skyline.cpp](https://github.com/LearningMonkey61/DAA/blob/master/skyline.cpp)

# Lab #2 & 3

#### 06-02-2020

Questions

* Number of rotations in circular array
  * Given a circularly sorted array, find the extent of rotation of the array Assume no duplicates and anti-clockwise rotation
  * Input – [8, 9, 10, 2, 5, 7]
  * Output – Rotation extent = 3
  * solution :  [rotation.cpp](https://github.com/LearningMonkey61/DAA/blob/master/rotation.cpp)
* Search in nearly sorted array in minimum time
  * Given a nearly sorted array (degree of misplaced element is no more than one position from correct place), efficiently search an element in it.
  * Input – [2, 1, 3, 4, 5, 6, 7, 8, 9]; 5
  * Output – Position of 5 = 4th (or index = 3)
  * solution :  [nearlysorted.cpp](https://github.com/LearningMonkey61/DAA/blob/master/nearlysorted.cpp)
* Efficient implementation of power function in recursive manner
  * Input – x = some number, n = some exponent
  * Output – x^n
* Perform ternary search
* Merge sort of linked list
  * solution :  [mergesort.cpp](https://github.com/LearningMonkey61/DAA/blob/master/mergesort.cpp)
* Quicksort
  * solution : [quicksort.cpp](https://github.com/LearningMonkey61/DAA/blob/master/quicksort.cpp)
* Towers of Hanoi
  * solution : [towerofhanoi.cpp](https://github.com/LearningMonkey61/DAA/blob/master/towerofhanoi.cpp)
* K-th largest element in unsorted array
* Search an element in a 2D array with efficiency
  * solution : [2darraysearch.cpp](https://github.com/LearningMonkey61/DAA/blob/master/2darraysearch.cpp)
* Beautiful Array
  * For some fixed N, an array A is beautiful if it is a permutation of the integers 1, 2, ..., N, such that: For every i < j, there is no k with i < k < j such that A[k]* 2 = A[i] + A[j].
  * Given N, return any beautiful array A.  (It is guaranteed that one exists.)
* Given a set of points, find the closest pair (having shortest distance between them)
* Implement Strassen’s algorithm
* Perform heapsort for the given data
  * solution : [heapsort.cpp](https://github.com/LearningMonkey61/DAA/blob/master/heapsort.cpp)
* Find greatest common divisor of two numbers using Divide and Conquer approach
  * trivial : use euclid's algorithim.

  * ```cpp
    int gcd(int a, int b){
      if (a == 0) return b;
      return gcd(b % a, a);
    }
      ```

# Lab #4

#### 13-02-2020

Questions

* Inversion Count of an Array
  * Inversion Count for an array indicates – how far (or close) the array is from being sorted. If array is already sorted then inversion count is 0. If array is sorted in reverse order that inversion count is the maximum.
  * Formally speaking, two elements a[i] and a[j] form an inversion if a[i] &gt; a[j] and i &lt; j
  * Example : The sequence 2, 4, 1, 3, 5 has three inversions (2, 1), (4, 1), (4, 3).
* Multiply two polynomials
* Find the maximum element in an array which is first increasing and then decreasing
* Binary Search on Singly Linked List
* Given three numbers x, y, and p, find the modular exponent (x^y)%p