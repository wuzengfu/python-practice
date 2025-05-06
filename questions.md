# Python Practice Problems

## 1. Sum of Previous Two

> Output a sequence of numbers between 0 and 500 (inclusive) such that the i-th element is the sum of the previous two elements (e.g. (i-1)-th and (i-2)-th). The first two numbers of the sequence is 0 and 1.

**Output**

0 1 1 2 3 5 8 13 ...

**Explanation**

The first two numbers are `0` and `1` as they are starting numbers stated in the question. For the rest of numbers:

- 1 = 1 + 0
- 3 = 1 + 2
- 5 = 3 + 2
- 8 = 5 + 3
- 13 = 8 + 5

## 2. Beautiful Numbers

> A beautiful number is an integer such that it is divisible by 3 but not by 5. Output all beautiful numbers between 1 and 100 (inclusive).

**Output**

3 6 9 12 18 ...

**Explanation**

All these numbers are divisible by 3. Note that `15` is not a beautiful number as `15` is divisible by 5.

## 3. Time Converter

> Create a time converter that takes in an integer - `seconds` as input. Convert the `seconds` to `hours`, `minutes` and `seconds`.

**Input**

- `seconds`: 5103

**Output**

1 hour(s), 25 minute(s), 3 second(s)

**Explanation**

5103 seconds is equivalent to 1 hour, 25 minutes and 3 seconds.

## 4. Reversed Integer

> Take in an integer as input, output its reversed integer.

**Input**

291804

**Output**

408192

**Explanation**

Reversing the number `291804` gives `408192`.

## 5. Reverse an Array

> Take in an integer `n` - size of the array, `arr` - an array of size n. Output the reversed array.

**Input**

- `n` = 5
- `arr` = [4, 2, 10, 2, 6]

**Output**

6 2 10 2 4

**Explanation**

The output is the reversed array of `arr` by reading the value from right to left.

## 6. Merge Two Sorted Arrays of Same Size

> Take in an integer `n` - size of arrays, `arr1` and `arr2` - two sorted arrays of size n in ascending order as inputs. Output a merged array such that it is also sorted in ascending order.

**Input**

- `n` = 5
- `arr1` = [4, 7, 10, 15, 16]
- `arr2` = [2, 8, 9, 14, 21]

**Output**

2 4 7 8 9 10 14 15 16 21
