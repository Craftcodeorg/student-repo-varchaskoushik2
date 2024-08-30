### Assignment Creation: Analyzing and Finding the Largest Number in a List

#### Problem Statement:
In this assignment, you will apply the concepts of variables and data types to solve a practical problem relevant to EdTech. You will write a Python function that takes a list of numbers (representing scores from a math quiz) and returns the largest number in the list. This task will help you understand how to work with lists and basic data manipulation in Python, which are essential skills for creating educational tools and games.

#### Starter Code:
To get you started, here is a basic framework for your function. You will need to complete the function to achieve the desired functionality.

```python
# Starter code for finding the largest number in a list

def find_largest_number(numbers):
    # Step 1: Initialize a variable to store the largest number
    largest_number = None
    
    # Step 2: Iterate through the list of numbers
    for number in numbers:
        # Step 3: Compare each number with the current largest number
        if largest_number is None or number > largest_number:
            largest_number = number
    
    # Step 4: Return the largest number found
    return largest_number

# Test the function with sample data
quiz_scores = [85, 92, 78, 90, 88, 96, 79]
largest_score = find_largest_number(quiz_scores)
print(f"The largest score is: {largest_score}")
```

#### Detailed Instructions:
1. **Step 1: Initialize a Variable**
   - Start by initializing a variable `largest_number` to store the largest number found in the list. Initially, set it to `None`.

2. **Step 2: Iterate Through the List**
   - Use a `for` loop to iterate through each number in the list `numbers`.

3. **Step 3: Compare Each Number**
   - Inside the loop, compare each number with the current value of `largest_number`. If `largest_number` is `None` (which it will be at the start) or if the current `number` is greater than `largest_number`, update `largest_number` to be the current `number`.

4. **Step 4: Return the Largest Number**
   - After the loop completes, return the value stored in `largest_number`.

#### Criteria for Success and Evaluation:
- **Correctness**: The function correctly identifies and returns the largest number in the provided list.
- **Code Quality**: The code is clean, well-documented with comments explaining each step, and follows best practices.
- **Efficiency**: The function efficiently iterates through the list and performs comparisons.
- **Output**: The output should be formatted clearly, providing a user-friendly message indicating the largest number.

Example of a successful output:
```plaintext
The largest score is: 96
```

### Rubric:
| Criteria          | Excellent (10)                          | Good (8)                                  | Satisfactory (6)                          | Needs Improvement (4)                  |
|-------------------|-----------------------------------------|-------------------------------------------|-------------------------------------------|----------------------------------------|
| Correctness       | Function returns correct largest number | Function mostly correct but has minor issues | Function works but has some logical errors | Function does not return correct result |
| Code Quality      | Code is clean, well-documented, and follows best practices | Code is mostly clean but lacks some comments or has minor style issues | Code works but is poorly documented or styled | Code is messy and lacks documentation |
| Efficiency        | Efficiently iterates and performs comparisons | Mostly efficient but could be optimized | Function works but is not optimized | Function is inefficient |
| Output Formatting | Output is clear and user-friendly       | Output is mostly clear but could be improved | Output works but is not user-friendly     | Output is unclear or confusing         |

By completing this assignment, you will reinforce your understanding of variables and data types in Python, and gain practical experience in writing functions that manipulate lists. This skill is essential for developing educational content and games that are both engaging and informative for kids.