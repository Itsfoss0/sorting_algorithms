![ALX](https://assets.imaginablefutures.com/media/images/ALX_Logo.max-200x150.png)
> sorting algorithms 

![meme](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/248/willy-wonka.png)

## About
Sorting algorithms are a fundamental part of computer science, and they play a crucial role in many areas of computer science and software engineering. These algorithms are used to arrange data in a particular order, such as ascending or descending, and are essential for tasks such as searching, merging and analyzing data. There are various sorting algorithms available, each with their own strengths and weaknesses, such as efficiency and stability, and choosing the right algorithm for a specific task can greatly improve the performance of a program. Some are more efficient for large data sets, while others are better suited for small data sets. Some are easy to implement, while others are more complex. Regardless of their differences, all sorting algorithms share the goal of arranging a set of elements in a specific order, whether it be ascending or descending. 

## Intro
In this project, we will explore sorting algorithims. This project should be done in [pair programming](https://en.wikipedia.org/wiki/Pair_programming)

## Resources
__Read or watch__:
1. [Sorting algorithms](https://en.wikipedia.org/wiki/Sorting_algorithm)
2. [Big O notation](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation)
3. [Sorting algorithms animation](https://www.toptal.com/developers/sorting-algorithms)
4. [15 Sorting algorithms in 6 minutes](https://www.youtube.com/watch?v=kPRA0W1kECg)
5. [CS50's Algorithm exaplanation by David Malan](https://www.youtube.com/watch?v=yb0PY3LX2x8&t=2s)
6. [All about sorting algorithms](https://www.geeksforgeeks.org/sorting-algorithms/)

## Learning objectives
By the end of this project, you should be able to [explain to anyone](https://fs.blog/feynman-learning-technique/) __Without the help of Google__ the following 

* [X] At least four different sorting algorithms
* [X] What is the Big O notation, and how to evaluate the time complexity of an algorithm
* [X] How to select the best sorting algorithm for a given input
* [X] What is a stable sorting algorithm

## More info
### Data Structures and functions
For this project, you are given the following ```print_array``` and ```print_list``` functions 
```c
#include <stdlib.h>
#include <stdio.h>

/**
 * print_array - Prints an array of integers
 *
 * @array: The array to be printed
 * @size: Number of elements in @array
 */
void print_array(const int *array, size_t size)
{
    size_t i;

    i = 0;
    while (array && i < size)
    {
        if (i > 0)
            printf(", ");
        printf("%d", array[i]);
        ++i;
    }
    printf("\n");
}
```
```c
#include <stdio.h>
#include "sort.h"

/**
 * print_list - Prints a list of integers
 *
 * @list: The list to be printed
 */
void print_list(const listint_t *list)
{
    int i;

    i = 0;
    while (list)
    {
        if (i > 0)
            printf(", ");
        printf("%d", list->n);
        ++i;
        list = list->next;
    }
    printf("\n");
}
```
- Our files ```print_array.c``` and ```print_list.c``` (containing the print_array and print_list functions) will be compiled with your functions during the correction.
- Please declare the prototype of the functions ```print_array``` and ```print_list``` in your ```sort.h``` header file
- Please use the following data structure for doubly linked list:

```c
/**
 * struct listint_s - Doubly linked list node
 *
 * @n: Integer stored in the node
 * @prev: Pointer to the previous element of the list
 * @next: Pointer to the next element of the list
 */
typedef struct listint_s
{
    const int n;
    struct listint_s *prev;
    struct listint_s *next;
} listint_t;
```
- Please, note this format is used for Quiz and Task questions.

    - O(1)
    - O(n)
    - O(n!)
    - n square -> O(n^2)
    - log(n) -> O(log(n))
    - n * log(n) -> O(nlog(n))
    - n + k -> O(n+k)
    …

- Please use the “short” notation (don’t use constants). Example: O(nk) or O(wn) should be written O(n). If an answer is required within a file, all your answers files must have a newline at the end.

## Test
Here is a quick tip to help you test your sorting algorithms with big sets of random integers: [Random.org](https://www.random.org/integer-sets/)