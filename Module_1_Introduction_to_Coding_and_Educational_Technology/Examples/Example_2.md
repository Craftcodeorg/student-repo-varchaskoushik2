### Module Title: Introduction to Coding and Educational Technology

---

### Example 2: Simple if statement

---

#### 1. Introduction:
In this section, we will explore the concept of a simple if statement, a fundamental building block in programming. This example builds upon the key concepts discussed in the lecture "Introduction to EdTech: How Technology is Transforming Education." Understanding if statements is crucial for creating interactive and responsive programs, which are essential in educational technology (EdTech) applications. By mastering if statements, you can develop more dynamic and engaging coding projects for kids.

---

#### 2. Code Snippet:
Below is a well-commented code snippet that illustrates the concept of a simple if statement using Python. This example is suitable for an intermediate-level programmer and includes error handling and best practices.

```python
# Example: Simple If Statement in Python

# Function to check if a student passed the test
def check_pass(score):
    """
    This function checks if the student's score is passing or failing.
    
    Args:
    score (int): The student's test score
    
    Returns:
    str: "Pass" if score >= 50, otherwise "Fail"
    """
    try:
        # Ensure the score is an integer
        score = int(score)
        
        # Check if the score is passing or failing
        if score >= 50:
            return "Pass"
        else:
            return "Fail"
    except ValueError:
        return "Invalid input! Please enter a numeric score."

# Example usage
student_score = input("Enter the student's test score: ")
result = check_pass(student_score)
print(f"Result: {result}")
```

---

#### 3. Explanation:
Let's break down the code step-by-step to understand how it implements the key concepts from the lecture:

1. **Function Definition**:
   - `def check_pass(score):` defines a function named `check_pass` that takes one argument, `score`.
   
2. **Docstring**:
   - The docstring provides a brief description of the function, including its arguments and return value.
   
3. **Error Handling**:
   - `try:` and `except ValueError:` ensure that the input is an integer. If the input is not numeric, the function returns an error message.

4. **If Statement**:
   - `if score >= 50:` checks if the student's score is greater than or equal to 50. If true, it returns "Pass"; otherwise, it returns "Fail".

5. **Example Usage**:
   - `student_score = input("Enter the student's test score: ")` prompts the user to enter a test score.
   - `result = check_pass(student_score)` calls the `check_pass` function with the user's input.
   - `print(f"Result: {result}")` prints the result of the function call.

This code snippet demonstrates how to use a simple if statement to make decisions based on user input, a fundamental concept in creating interactive EdTech applications.

---

#### 4. Application:
In EdTech, simple if statements can be used to create interactive quizzes and educational games that provide immediate feedback to students. For example, in a coding platform for kids, an if statement can be used to check whether a student's solution to a coding challenge is correct and provide appropriate feedback.

**Real-World Application Example**:
Imagine an interactive math quiz for kids where they solve problems and receive instant feedback. An if statement can be used to check their answers and display messages like "Correct!" or "Try again!" This immediate feedback helps reinforce learning and keeps students engaged.

```python
# Example: Interactive Math Quiz

def math_quiz():
    """
    This function conducts a simple math quiz and provides instant feedback.
    """
    question = "What is 5 + 3? "
    correct_answer = 8
    
    try:
        # Get user's answer
        user_answer = int(input(question))
        
        # Check if the answer is correct
        if user_answer == correct_answer:
            print("Correct!")
        else:
            print("Try again!")
    except ValueError:
        print("Invalid input! Please enter a numeric answer.")

# Run the quiz
math_quiz()
```

In this example, the if statement checks if the user's answer matches the correct answer and provides instant feedback, making learning more interactive and enjoyable.

---

By understanding and applying simple if statements, you can create engaging and interactive educational content that enhances learning experiences for kids. This foundational knowledge will enable you to build more complex and captivating coding projects that align with your career goals in EdTech.