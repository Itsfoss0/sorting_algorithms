![ALX](https://assets.imaginablefutures.com/media/images/ALX_Logo.max-200x150.png)
> sorting algorithms quizes

#### Question #0
What is the time complexity of accessing the nth element on an unsorted array?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #1
What is the time complexity of removing at index n in an unsorted array?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #2
Assuming you have a pointer to the node to insert, what is the time complexity of inserting after the nth element of a doubly linked list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #3
What is the time complexity of this function/algorithim?
```javascript
var factorial = function(n) {
    if(n == 0) {
        return 1
    } else {
        return n * factorial(n - 1);
    }
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #4
What is the time complexity of accessing the nth element of a singly linked list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #5
What is the time complexity of the “push” operation onto a stack?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #5
What is the time complexity of this function/algorithm
```c
void f(int n)
{
    int i;
    int j;

    for (i = 0; i < n; i++)
    {
        if (i % 2 == 0)
        {
            for (j = 1; j < n; j = j * 2)
            {
                printf("[%d] [%d]\n", i, j);
            }
        }
        else
        {
            for (j = 0; j < n; j = j + 2)
            {
                printf("[%d] [%d]\n", i, j);
            }
        }
    }
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [X] O(n^2)

#### Question #7
What is the time complexity of removing at index n from an unsorted Python 3 list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #8
What is the time complexity of inserting into an unsorted Python 3 list at index n?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] (nlog(n))
* [ ] O(n^2)

#### Question #9
What is the time complexity of setting a value at index n in an unsorted array?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #10
What is the time complexity of searching for an element in a queue of size n if you are given a pointer to both the head and the tail of the queue?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #11
What is the time complexity of searching for an element in an unsorted Python 3 list of size n?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #12
What is the best case time complexity searching for an element in a hash table with the implementation you used during the previous Hash Table C project (chaining)?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #13
What is the time complexity of best case deletion from a hash table with the implementation you used during the previous Hash Table C project (chaining)?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)


#### Question #14
What is the time complexity of following algorithm
```javascript
void f(unsigned int n)
{
    int i;
    int j;

    for (i = 0; i < n; i++)
    {
        for (j = 1; j < n; j = j * 2)
        {
            printf("[%d] [%d]\n", i, j);
        }
    }
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [X] O(nlog(n))
* [ ] O(n^2)

#### Question #15
What is the time complexity of accessing the nth element of a doubly linked list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #16
Assuming you have a pointer to the node to remove, what is the time complexity of removing the nth element of a doubly linked list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2

#### Question #17
What is the best case time complexity of insertion in a hash table with the implementation you used during the previous Hash Table C project (chaining)?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #18
What is the time complexity of this function/algorithm
```c
void f(int n)
{
    int i;

    for (i = 0; i < n; i++)
    {
        printf("[%d]\n", i);
    }
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #19
What is the time complexity of searching for an element in a doubly linked list of size n?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #20
What is the time complexity of the following algorithm/funciton
```c
void f(int n)
{
    int i;

    for (i = 0; i < n; i += 98)
    {
        printf("[%d]\n", i);
    }
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #21
What is the time complexity of inserting at index n on an unsorted array?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #22
What is the time complexity of setting the value of the nth element in a singly linked list? (Assuming you have a pointer to the node to set the value of)

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #23
What is the time complexity of the following function/algorithm
```c
void f(int n)
{
    printf("n = %d\n", n);
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] (1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #24
What is the time complexity of setting value at index n in an unsorted Python 3 list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #25
What is the time complexity of the following function/algorithm
```c
void f(int n)
{
     int i;
     int j;

     for (i = 0; i < n; i++)
     {
          for (j = i + 1; j < n; j++)
          {
               printf("[%d] [%d]\n", i, j);
          }
     }
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [X] O(n^2)

#### Question #26
What is the time complexity of worst case deletion from a hash table with the implementation you used during the previous Hash Table C project (chaining)?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #27
What is the time complexity of this algorithm
```python
def func(n):
    a=5
    b=6
    c=10
    for i in range(n):
        for j in range(n):
            x = i * i
            y = j * j
            z = i * j
    for k in range(n):
        w = a*k + 45
        v = b*b
    d = 33
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [X] O(n^2)

#### Question #28
What is the time complexity of searching for an element - worst case - in a hash table with the implementation you used during the previous Hash Table C project (chaining)?
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #29
What is the time complexity of “pushing” an element into a queue if you are given a pointer to both the head and the tail of the queue?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #30
What is the time complexity of this algorithm/function
```bash
foreach($numbers as $number)
{
    echo $number;
}
```
* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #31
What is the time complexity of the following algorithm
```c
int Fibonacci(int number)
{
    if (number <= 1) return number;

    return Fibonacci(number - 2) + Fibonacci(number - 1);
}
```
* [ ] O(n!)
* [X] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #32
What is the time complexity of removing the nth element of a singly linked list? (Assuming you have a pointer to the node to remove)

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #33
What is the time complexity of the “pop” operation onto a stack?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #34
What is the time complexity accessing the nth element in an unsorted Python 3 list?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #35
What is the time complexity of searching for an element in a stack of size n?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [X] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

#### Question #36
What is the time complexity of “popping” an element in a queue if you are given a pointer to both the head and the tail of the queue?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(nlog(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(log(n))

#### Question #36
What is the time complexity of searching for an element in an unsorted array of size n?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [ ] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)


#### Question #37
What is the worst case time complexity of insertion in a hash table with the implementation you used during the previous Hash Table C project (chaining)?

* [ ] O(n!)
* [ ] O(2^n)
* [ ] O(log(n))
* [ ] O(n)
* [X] O(1)
* [ ] O(nlog(n))
* [ ] O(n^2)

