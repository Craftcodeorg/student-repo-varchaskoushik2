### Module Title: Fundamentals of Python Programming ###

#### Example 3: If-else statement

---

### 1. Introduction

In our previous lecture, we discussed the fundamental concepts of variables and data types in Python. These are essential building blocks for any program and are particularly useful in creating engaging stories and interactive games for kids. In this lecture, we will build upon these concepts by introducing control structures, specifically the if-else statement. Control structures are crucial for adding logic and decision-making capabilities to your programs, making them more dynamic and interactive. This is particularly important in EdTech, where you want to create educational experiences that are both engaging and adaptive to the learner's input.

---

### 2. Code Snippet

Below is a well-commented code snippet that illustrates the concept of the if-else statement. The example is designed to be suitable for an intermediate-level programmer and includes error handling and best practices.

```python
# Example: Simple Quiz Game

# Defining variables
question = "What is 5 + 7?"
correct_answer = 12

try:
    # Asking the user for an answer
    user_answer = int(input("Your answer: "))
    
    # Using if-else statement to check the answer
    if user_answer == correct_answer:
        print("Correct! Well done.")
    else:
        print("Incorrect. The correct answer is 12.")
except ValueError:
    # Error handling for non-integer input
    print("Please enter a valid number.")
```

---

### 3. Explanation

#### Step-by-Step Explanation:

1. **Defining Variables:**
   - We start by defining the variables `question` and `correct_answer`. These variables store the quiz question and the correct answer, respectively.

2. **Input Handling:**
   - The `input()` function is used to capture the user's answer. We use `int()` to convert the input string to an integer, as we are expecting a numerical answer.

3. **If-else Statement:**
   - The if-else statement checks whether the user's answer matches the correct answer.
   - If `user_answer` is equal to `correct_answer`, the program prints "Correct! Well done."
   - Otherwise, it prints "Incorrect. The correct answer is 12."

4. **Error Handling:**
   - A `try-except` block is used to handle cases where the user inputs a non-integer value. If a `ValueError` occurs, the program prints "Please enter a valid number."

This example demonstrates how to use variables, data types, and control structures together to create an interactive quiz game. It also includes error handling to ensure the program runs smoothly even when unexpected input is provided.

---

### 4. Application

#### Real-World Application in EdTech:

**Adaptive Learning Systems:**

In EdTech, adaptive learning systems use control structures like if-else statements to personalize the learning experience based on student performance. For example, an adaptive math tutor can present different levels of questions based on whether the student answers correctly or incorrectly.

**Example:**

```python
# Adaptive Quiz Game
import random

# Function to generate a math question
def generate_question():
    num1 = random.randint(1, 10)
    num2 = random.randint(1, 10)
    return num1, num2, num1 + num2

# Function to ask a question
def ask_question():
    num1, num2, correct_answer = generate_question()
    question = f"What is {num1} + {num2}?"
    
    try:
        user_answer = int(input(question + " "))
        
        if user_answer == correct_answer:
            print("Correct! Well done.")
            return True
        else:
            print(f"Incorrect. The correct answer is {correct_answer}.")
            return False
    except ValueError:
        print("Please enter a valid number.")
        return False

# Main loop for adaptive learning
score = 0
for _ in range(5):  # Ask 5 questions
    if ask_question():
        score += 1

print(f"Your final score is {score}/5.")
```

In this example, the program generates random math questions and adapts based on the student's answers. This approach helps in identifying areas where students need more practice and provides immediate feedback, making learning more effective and engaging.

---

### Summary

In this lecture, we explored the if-else statement, a fundamental control structure in Python that allows us to add decision-making capabilities to our programs. We learned how to use it in a simple quiz game, incorporating error handling to manage unexpected input gracefully. Understanding and applying if-else statements are crucial for creating dynamic and interactive educational experiences in EdTech.

---

### Next Steps

In our next lecture, we will delve into loops and iterations, which will enable you to create more complex and repetitive tasks in your programs. This will further enhance your ability to design engaging and educational coding projects for kids.

Thank you for joining today’s lecture! Keep practicing, and see you next time!

---

By structuring your learning around these concepts and examples, you will be well-equipped to create captivating and educational coding projects that can make learning fun and interactive for kids aged 8-15.