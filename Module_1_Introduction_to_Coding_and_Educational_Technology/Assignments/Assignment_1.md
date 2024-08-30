### Assignment: Write a Short Story Using Variables and Conditional Statements

#### Problem Statement
In this assignment, you will write a short interactive story using variables and conditional statements. The story will involve choices that the reader can make, which will affect the outcome of the story. This task will help you apply the concepts of coding, specifically variables and conditional statements, in a practical and engaging way. The goal is to create a captivating story that can be used to teach coding to kids aged 8-15.

#### Starter Code
Below is the starter code for your interactive story. You will need to expand upon this code by adding more choices and outcomes.

```python
# Starter code for an interactive story

# Introduction
print("Welcome to the Adventure Story!")
print("You find yourself at the entrance of a dark cave.")

# Variables
has_torch = False
has_key = False

# First choice
choice1 = input("Do you want to enter the cave? (yes/no): ").strip().lower()

if choice1 == "yes":
    print("You enter the cave and find a torch on the ground.")
    has_torch = True
    # Second choice
    choice2 = input("Do you want to pick up the torch? (yes/no): ").strip().lower()
    if choice2 == "yes":
        print("You pick up the torch and light it. The cave is now illuminated.")
    else:
        print("You decide not to pick up the torch and proceed in the dark.")
else:
    print("You decide not to enter the cave and walk away. The adventure ends here.")

# Additional choices and outcomes
# Add more choices and outcomes here

print("Thank you for playing the Adventure Story!")
```

#### Detailed Instructions

1. **Step 1: Expand the Story with More Choices**
   - Add at least two more choices that the reader can make after entering the cave.
   - Use variables to track items or conditions (e.g., `has_key`, `has_map`).
   - Use conditional statements to create different outcomes based on the reader's choices.

2. **Step 2: Introduce Variables and Conditional Statements**
   - Introduce at least two new variables that will affect the story's outcome.
   - Use conditional statements (`if`, `elif`, `else`) to handle different scenarios based on these variables.

3. **Step 3: Create Multiple Endings**
   - Create at least three different endings for the story based on the reader's choices.
   - Ensure that each ending is unique and provides a satisfying conclusion to the story.

4. **Step 4: Add Comments and Documentation**
   - Add comments to your code to explain what each part does.
   - Ensure your code is well-documented and easy to understand.

5. **Step 5: Test Your Story**
   - Test your story by running the code multiple times and making different choices.
   - Ensure that all possible paths through the story work correctly and lead to a valid ending.

#### Criteria for Success and Evaluation

**Success Criteria:**
- The story includes at least three choices that affect the outcome.
- The code uses variables and conditional statements effectively.
- There are at least three unique endings based on the reader's choices.
- The code is clean, well-documented, and follows best practices.
- The story is engaging and suitable for kids aged 8-15.

**Evaluation Rubric:**

| Criteria                        | Excellent (5)                | Good (4)                    | Satisfactory (3)            | Needs Improvement (2)       | Unsatisfactory (1)          |
|---------------------------------|------------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
| **Story Choices**               | Includes 3+ choices, all affecting outcomes | Includes 2 choices, most affecting outcomes | Includes 1 choice affecting outcome | Includes choices but does not affect outcomes | No meaningful choices       |
| **Use of Variables**            | Uses 3+ variables effectively | Uses 2 variables effectively | Uses 1 variable effectively | Uses variables but not effectively | Does not use variables      |
| **Conditional Statements**      | Uses conditionals correctly in all scenarios | Uses conditionals correctly in most scenarios | Uses conditionals correctly in some scenarios | Uses conditionals but with errors | Does not use conditionals    |
| **Story Endings**               | 3+ unique endings            | 2 unique endings            | 1 unique ending             | Endings are not unique      | No clear endings            |
| **Code Quality**                | Clean, well-documented, follows best practices | Mostly clean, some documentation, follows best practices | Somewhat clean, limited documentation, follows some practices | Messy, poorly documented, follows few practices | Poor quality, no documentation |

By completing this assignment, you will gain hands-on experience with coding concepts such as variables and conditional statements while creating an engaging story for kids. This will contribute to your career goal of teaching coding in an educational and captivating way.