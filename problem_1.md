<img width="526" alt="image" src="https://github.com/a-teaching-goose/CSS342A-2024-Summer/assets/252020/f0b4e035-8a77-4f99-8b82-c14885a4a29b">

## (25pt) Welcome to The Matrix

### The Background
A matrix is like a super-organized grid of numbers, arranged neatly in rows and columns. Think of it as a spreadsheet where each number has its own special spot. Matrices are incredibly useful in fields like math, physics, engineering, and especially in AI (artificial intelligence). In AI, matrix operations are the magic behind making smart decisions, recognizing faces in photos, and even training robots. They help process and transform huge amounts of data quickly and efficiently. So, whether you're solving equations or building the next cool AI app, matrices are your go-to tool for handling complex calculations with ease!

For example, in this matrix, there are 3 rows and 4 columns, with each number (element) neatly positioned in its own cell.

<img width="303" alt="image" src="https://github.com/a-teaching-goose/CSS342A-2024-Summer/assets/252020/dc100376-b29e-4421-bfdb-426b4a0bda1f">

Each number in a matrix is usually referred to by their horizontal and vertical indices together like *matrix(i, j)*. In the example above:
- value at (0, 0) is 1.
- value at (2, 3) is 12.
- value at (1, 2) is 7.

### The Task (25pt)

Given a [class](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/src/task_1/matrix.hpp) that "models" a matrix, the task is to finish the TODO functions.

The operator functions for (i, j) to be written is easier to understand from the TODO description.

The [matrix multiply](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/src/task_1/matrix.hpp#L114) needs a bit more explaining. Here's a quick explanation from GPT with prompt: *"explain how matrix multiply works with 2 examples of different dimensions no larger than 5. arrange these two examples side by side in a table. one on the left column and one on the right column."*

<img width="818" alt="image" src="https://github.com/a-teaching-goose/CSS342A-2024-Summer/assets/252020/ba5cc10a-ae13-4036-a451-0152a8a20c6c">

The unit tests for this task are [here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_1.cpp). Please spend some time reading both the src and test code to understand the code structure before coding.

### Note

- The code from this task is used in later tasks. Please finish this completely (all tests passing) before moving on to other tasks.
- MATLAB has a nice [online tool](https://matlab.mathworks.com/) for free. Use this to learn and try matrix operations.
