# Data Structure and Algorithm (DSA)

## What is Data Structures?

Data Structure - is a way of organizing data so that it can be used effectively.

## Why Data Structures?

* They are essential ingredients in crating fast and powerful algorithms.
* They help manage and organize data.
*  They make the code cleaner and easier to understand.



## Abstract Data Types vs Data Structures

### Abstract Data Types

- Abstract Data Types (ADT) is an abstraction of a data structure which provides only the interface to which a data structure must adhere to.

- The interface does not give any specific details about something should be implemented or in what programming language.

| ABSTRACTION **(ADT)** |                   **IMPLEMENTATION (DS)**                    |
| :-------------------: | :----------------------------------------------------------: |
|         List          |                Dynamic Array<br />Linked List                |
|         Queue         | Linked List Queue<br />Array based Queue<br />Stack based Queue |
|          Map          |             Tree Map<br />Hash Map / Hash Table              |
|        Vehicle        |            Golf Cart<br />Bicycle<br />Smart Car             |

****

## Complexity Analysis

* As Programmers, we often find ourselves asking the same to questions over and over again:
  * How much *<u>TIME</u>* does this algorithm need to finish?
  * How much *<u>SPACE</u>* does this algorithm need for its computation?

# BIG-O Notation

Big- O Notation gives an upper bound of the complexity in the ***worst*** case, helping to quantify performance as the input size become ***arbitrarily large***.

|                       BIG - O Notation                       |
| :----------------------------------------------------------: |
| ***n*** - The size of the input Complexities ordered in from smallest to largest. |

|   **Constant Time**   |      **O (1)**       |
| :-------------------: | :------------------: |
| **Logarithmic Time**  |   **O (log(*n*))**   |
|    **Linear Time**    |     **O (*n*)**      |
| **Linearithmic Time** | **O (*n* log(*n*))** |
|   **Quadric Time**    |    **O (*n*^2)**     |
|    **Cubic Time**     |    **O (*n*^3)**     |
| **Exponential Time**  | **O (b^*n*), b > 1** |
|  **Factorial Time**   |     **O (*n*!)**     |

# Big - O Properties

```bash
O (n + c) = O(n)
	O(cn) = O(n), c > 0
```

Let ***f*** be a function that describes the running time of a particular algorithm for an input of size ***n***:

```bash
f(n) = 7log(n)^3 + 15n^2 + 2n^3 + 9
	O(f(n)) = O(n^3)
```

# Big - O Examples

The following runs in ***Constant time*: O (1)**

``` c++
a = 1
b = 2
c = a + 5*b
```

```c++
i = 0
while i < 11 do
    i = i + 1 
```

The following runs in ***Linear time:*** **O (*n*)**

```c++
i = 0;
while i < n do
    i += 1

//formula
	f(n) = n
  O(f(n)) = O(n)
```

```c++
i = 0
while i < n do
    i += 3

//formula
	f(n) = n/3
  O(f(n)) = O(n)
```

Both of the following runs in a ***Quadratic time***. The first may be obvious since ***n*** work done ***n*** times is ***n*** * ***n*** = **O (*n* ^2)**, but what about the second one?

```c++
for(int i = 0; i < n; i++)
    for(int j = 0; j < n; j++)
        
//formula 
    f(n) = n*n = n^2, O(f(n)) = O(n^2)
```

```c++
for(int i = 0; i < n; i++)
    for(int j = i; j < n; j++)
//              ^ replaced 0 to i.
```

For a moment, just focus on the second loop. Since ***i*** goes from ***[0,n]*** the moment of looping done is directly determined by what ***i*** is. Remark that if ***i=0***, we do ***n*** work,  if ***i=1***, we do ***n-1*** work,  if ***i=2***, we do ***n-2*** work, etc...

So, the question then becomes what is:

***(n) + (n-1) + (n-2) + (n-3) + ... + 3 + 2 +1 ?***

Remarkably this turns out to be ***n(n+1)/2***, so O(***n***(***n***+1)/2) = O (***n***^2/2 + ***n***/2) = O(***n***^2).

```python
for(int i = 0; i < n; i++)
    for(int j = i; j < n; j++)
   
```

Another example for ***O (n^2)**

```c++
i = 0
    while i < n do
        j = 0
        while j 3*n do
            j++
        j = 0
        while j < 2*n do
            j++
        i++
     
 // Formula
      f(n) = n * (3n + 2n) = 5n^2
           O(f(n)) = O(n^2) 
```



Suppose we have a sorted array and we want to find the index of a particular value in the array, if it exists. What is the time complexity of the following algorithm?

```c++
low = 1
high = n-1;

while low <= high do
   mid = (low + high)/2
    
   if array[mid] == value:
       return mid
   else if array[mid] < value:
	   	low = mid + 1
   else if array[mid] < value:
	   	high = mid - 1
return -1 // Value not found
```

Answer:

```c++
O(log2(n)) = O(log(n))
    // also known as Binary Search
```





