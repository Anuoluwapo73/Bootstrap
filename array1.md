Algorithm:

1. Start
2. Read two arrays A and B
3. Create an empty list distinct_elements
4. For each element x in A:
   * If x is not in B and x is not in distinct_elements, append x to distinct_elements
5. For each element y in B:
   * If y is not in A and y is not in distinct_elements, append y to distinct_elements
6. Initialize sum as 0
7. For each element in distinct_elements, add  it to sum
8. Output sum
9. End
