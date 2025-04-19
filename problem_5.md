<img width="40%" alt="image" src="https://github.com/a-teaching-goose/CSS342A-2024-Summer/assets/252020/d58c71a0-e0f6-4c09-865a-7da14330232b">

## (10pt) Compound Interest
This task uses the formula in task 3 to implement a compound interest calculator. Make sure to finish task 3 completely before starting this task.

### Disclaimer
The content of this task is for illustration and CSS342 education purpose only. None of it is an investment advice by any means.

### The Background

"The eighth wonder of the world. He who understands it, earns it; he who doesn't, pays for it." - Albert Einstein

This is the famous quote about compound interest. 

And here's the definition from [Wikipedia](https://en.wikipedia.org/wiki/Compound_interest):
`
Compound interest is the addition of interest to the principal sum of a loan or deposit, or in other words, interest on interest. It is the result of reinvesting interest, rather than paying it out, so that interest in the next period is then earned on the principal sum plus previously accumulated interest.
`
Note: Compound interest is a general kind of effect that applies to more aspects than finance. We ain't just talking about money here.

In simple term, compound interest is about **a repeated small step produces acceleratingly large result over time**. But be aware that this can manifest as angel or evil, meaning it can be really good or really bad for you. There are many ways to benefit or suffer from the effect of compound interest, and a larger issue is that many people learn this too late.

So, let's learn this to stay on the positive side of it, and now.

### The Task (10pt)

- Complete a compound interest simulator. **Do not use any math library**. [Here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/src/task_5/million_dollar_idea.cpp#L23) is the code to write. There's details info in the TODOs, but the key requirement is the calculation is to be done using a [Formula](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/src/task_3/formula.hpp) object instead of writing the logic as code.
- Add a unit test [here](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_5.cpp#L139) with your own way of reaching 1M using compound interest.

### Features of the calculator

- The calculator we are writing is based on [this calculator](https://www.investor.gov/financial-tools-calculators/calculators/compound-interest-calculator). Use it to help understand how compound interest works. Lots of our test cases are generated using this calculator. See [this](problem_1_result_comparison.md) for a comparison between the web calculator and our use cases.

- All tests are given. This serves as validation, but more importantly, use it as a *manual* to figure out how the code should work. There's [one task](https://github.com/a-teaching-goose/2024-summer-342-hw-2/blob/main/test/unit_test_task_5.cpp#L139) to add in test.

- Computation is done in floating point number, so *round-off error* is an issue. See [this](https://en.wikipedia.org/wiki/Round-off_error) for an intro. 

