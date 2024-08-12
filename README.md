# Final Exam (Hands-on)

## Question 1

Write and test a linear-time method in Java or Python for computing the sum of the depths of all positions in a tree `T`. To achieve this, add the method to the `LinkedBinaryTree` class, and write the testing code within the `main` method.

## Question 2

The `put(k,v)` method is used to add an entry to a map, where it spends time locating an existing item with the given key. Write an efficient version of this method, `putOnlyIfAbsent(k,v)`, that adds the entry to the map only if there is no existing entry with the key `k`.

Provide a Java or Python implementation of the `putOnlyIfAbsent(k,v)` method for the `SortedTableMap` class. Include testing code in the `main` method.

**Hint:** Your solution should make a single call to the `findIndex` method, add the entry to the table if the key does not exist, and otherwise return the existing value.

## Question 3

This exercise involves sorting collections using different `Comparators`. Utilize an `Employee` class for this task.

Write a `main()` method for the `QuickSort` class, which creates a queue of `Employee` objects and sorts them in increasing order. Populate the queue with several `Employee` objects, and then call the `quicksort` method. The `Employee` class includes the following instance variables:

- `int employeeNumber`
- `String employeeName`
- `double employeeSalary`

**Hint:** Your solution should use `employeeSalary` to compare `Employee` objects.