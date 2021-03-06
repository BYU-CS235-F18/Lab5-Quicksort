# Lab5-Quicksort

## Briefing: 
You can get help on this lab. You can work with partners, get help from the TAs, etc. Just like a normal lab. (Last year it was a no-help lab and I did initially introduce it as a no-help lab, but in talking with the other CS 235 instructors we unanimously decided to get rid of the no-help requirement.)

## Destructor: 
This is the first time we will be using destructors in this class, you may get help from TAs and others to properly write your destructor. Your quicksort class will have a dynamic array where space is allocated in the createArray function and deleted in the destructor.

## Purpose
The purpose of this lab is to implement quicksort.

## Background
Quicksort is a sorting algorithm developed by Tony Hoare that, on average, makes O(n log n) comparisons to sort n items. It is also known as partition-exchange sort. In the worst case, it makes O(n^2) comparisons, though this behavior is rare. Quicksort is typically faster in practice than other O(n log n) algorithms. Additionally, quicksort's sequential and localized memory references work well with a cache. Quicksort can be implemented as an in-place partitioning algorithm,

## Requirements
You will need the files from this git repository to complete the lab.

### File 1 - Array Tests (10 points)
* This deals with testing operations such as creating and adding to an array. 

### File 2 - Median of Three (20 points)
* It will test your implementation of the median of three function.

### File 3 - Partition (20 points)
* It will test your implementation of the partition function.

### File 4 - Comprehensive Tests & Edge Cases (15 points)
* It will test whether or not your medianOfThree() and partition() functions work on cases that commonly cause problems.

### File 5 - Sort All (25 points)
* It will test whether or not you are able to create your own recursive function using the medianOfThree() and partition() functions you already coded for the previous tests.

### Valgrind (10 points)
* Your solution must be free of memory leaks and other Valgrind errors.

## Requirement Notes
* No predefined data structures may be used for this lab; you must use an array.
* You are required to write a separate '.h' and '.cpp' for every class you implement.
* Please note that because the Test Driver uses random tests, your code will need to be run multiple times to ensure it passes all cases. You must pass each time in order to get full credit for the lab.
