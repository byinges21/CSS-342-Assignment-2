<img width="60%" alt="image" src="https://github.com/a-teaching-goose/CSS342A-2024-Summer/assets/252020/9959e721-6937-460c-9d23-11557d096fec">

## (30pt) Formula As An Object

### Inspiration

This task is inspired by [this talk on "clean code"](https://youtu.be/4F72VULWFvc?si=m17Es-0PBKIUR8qm&t=461). It answers a lot of the "why" s about the way this code is designed. Based on this speaker, this is one of his favorite interview questions to ask candidates.

### Assumptions

This task extends our [quiz 3](https://github.com/a-teaching-goose/2024-summer-342-quiz-formula-database) to have the following assumptions:

- A formula can have any number of variables.
- No constant in the given formula, e.g. "3 + x2" is not allowed because 3 is a constant. Formula can only contain variables like x1, y2.
- Each variable needs to be provided values even if there's duplicates. An example [here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_5.hpp#L12), and a vector of 4 numbers needs to be used when calling the calculate function of this formula.
- No parentheses of any kind are allowed.
- Only + and * operations are allowed, and the evaluation of the formula follows the rule that * has higher priority than +.
- Variables in the formula can be of any type such as int, float, Matrix from task 1, etc.

### Tasks

Finish the TODOs to pass all the [unit tests](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_3.cpp).

There's also one extra credit (10pt) [here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_3.cpp#L130).

The unit tests in this task are very helpful for understanding how your code is supposed to work.

### Note

This task is the foundation for task 4 and 5, which will not work if this one is not completed. Please finish this one completely before moving on further.
