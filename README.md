# Reflection – AI Number Program Lab

##  Student Name:
Christopher Davis

##  GitHub Repository Link:
https://github.com/dav-ach/cmsc115_unit8_lab2.git

## Iteration 1

What the AI code does:
- It inserted a comment, and did nothing.

Tests passed/failed:
- Failed: `testBasicArray`
- Failed: `testEmptyArray`
- Failed: `testSingleValue`
- Failed: `testNegativeNumbers`

What surprised you:
- I'm surprised that ChatGPT did nothing, but give me a stub.

Commit message:
- Iteration 1: AI-generated implementation

---

## Iteration 2

What changed:
- After using a prompt that contained implementation instructions, `duck.ai` generated a method for me.
- I had to update the parameter because I didn't provide the method prototype, but almost every test passed.
- It generated a proper loop, with almost everything working. 

What improved:
- The content, with a more sophisticated prompt.

What still failed and why:
- testEmptyArray, because the AI generated code to throw an `IllegalArgumentException` instead of returning a specific value.

Commit message:
- Iteration 2: largest value implementation

---

## Iteration 3

Final behavior:
- All tests pass.

What was fixed:
- Inside the input validation, the specific value was returned.

What you learned:
- A more sophisticated prompt in conjunction with tests make development with AIs pretty decent.
- Although I most likely still won't participate in TDD.

Commit message:
- Iteration 3: final version passing all tests

---

## Final Reflection

- How did AI responses change across prompts?
  - The output generated improved across executions.
- How did testing affect your changes?
  - Testing helped deal with specific input validation, and edge cases.
- What did version control help you understand?
  - Saving steps in between changes helped understand the issues being addressed.
