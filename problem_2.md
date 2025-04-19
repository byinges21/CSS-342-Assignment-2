<img width="403" alt="image" src="https://user-images.githubusercontent.com/252020/163451813-37c307f1-f9c9-4f9e-853b-dce85c450c7b.png">


## (25pt) ArrayList

### Abstract Data Type (ADT)

In a programming language, we are often provided some data type such as integer, float, and even class such as in Java and C++. 

An Abstract Data Type (ADT) is a fancy term, but it really just means we can create our own data type. In C++ we can do this by using class.

For example, **List** is a very commonly used data type. Similar to array, a list has a few properties:

- A List contains a linear sequence of elements
- A List has a size and capacity, and capacity can be limited or unlimited
- Each element in the List has an index of 0, 1, 2, etc. 
- New element can be added to the front or back of the List
- Element can be removed from a List
- Lists can be merged into each other

And [here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/src/task_2/array_and_list.h#L8)'s an C++ interface that defines a List ADT.

One thing to note: **There's no mentioning of the type of the element, and how data is stored in a List. This is up to specific implementation of a List to decide.**

### The Task

The task here is to implement a List that stores data in an array. Call it "ArrayList". The name may sound familiar if you've written in Java before because there's an [ArrayList ADT in Java](https://docs.oracle.com/javase/8/docs/api/java/util/ArrayList.html). Similar concepts here.

All the functions to be completed are marked by **TODO** in [array_and_list.cpp](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/src/task_2/array_and_list.cpp).

The unit tests for this task are [here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_2.cpp). This test is written by using the c++ template to a high extent for the purpose of reducing code duplication, e.g. same code but for different types. It helps to read and understand the test code thoroughly before writing the code.

### Requirements

- In task 2, no sort function of any kind is allowed to be used.
