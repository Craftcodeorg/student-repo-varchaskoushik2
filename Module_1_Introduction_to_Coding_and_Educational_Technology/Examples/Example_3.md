### Module Title: Introduction to Coding and Educational Technology

---

### Example 3: Defining and Calling a Function

---

#### 1. **Introduction**

In this example, we will delve into the concept of defining and calling a function, which is a fundamental aspect of programming. Functions allow us to encapsulate code into reusable blocks, making our programs more modular and easier to manage. This concept is particularly significant in EdTech as it helps create structured and maintainable code, which is essential when developing educational tools and applications. This example builds upon the key concepts of syntax and semantics discussed in Lecture 3.

---

#### 2. **Code Snippet**

```python
# Function to greet a user based on their name
def greet_user(name):
    """
    This function takes a user's name as input and prints a greeting message.
    :param name: str
    """
    try:
        # Ensure the name is a string
        if not isinstance(name, str):
            raise ValueError("Name must be a string")
        
        # Print the greeting message
        print(f"Hello, {name}! Welcome to our coding class.")
    
    except ValueError as e:
        print(e)

# Calling the function with a valid name
greet_user("Alice")

# Calling the function with an invalid input to demonstrate error handling
greet_user(123)
```

---

#### 3. **Explanation**

Let's break down the code step-by-step to understand how it implements the key concepts from the lecture:

1. **Defining the Function**:
   - The function `greet_user` is defined using the `def` keyword.
   - It takes one parameter `name`, which is expected to be a string.

2. **Docstring**:
   - A docstring is provided to describe what the function does and its parameter. This is a good practice for making code more understandable and maintainable.

3. **Type Checking**:
   - The function includes a type check to ensure that the `name` parameter is a string. If not, it raises a `ValueError`.

4. **Greeting Message**:
   - If the input is valid, the function prints a greeting message using an f-string for string interpolation.

5. **Error Handling**:
   - The `try-except` block handles any `ValueError` that might be raised if the input is not a string, providing a meaningful error message.

6. **Calling the Function**:
   - The function is called twice: once with a valid string input and once with an invalid integer input to demonstrate error handling.

This code demonstrates both correct syntax (function definition, string interpolation) and meaningful semantics (greeting the user, error handling).

---

#### 4. **Application**

**Real-World Application in EdTech:**

In the context of educational technology, defining and calling functions can significantly improve the efficiency and structure of coding projects. Here’s how:

- **Interactive Learning Modules**: Functions can be used to create modular and reusable components in interactive learning modules. For example, a function can handle user input validation across different exercises, ensuring consistency and reducing redundancy.
  
- **Personalized Learning Experiences**: Functions can help in personalizing learning experiences by encapsulating logic that adapts content based on user performance or preferences. For instance, a function could adjust the difficulty level of quiz questions based on the user's previous answers.

- **Code Maintainability**: By breaking down complex tasks into smaller functions, educators can maintain and update their code more easily. This modular approach also makes it easier for students to understand and learn from the code.

**Example Application:**

Imagine an educational platform where students can practice coding by solving problems. Functions can be used to create reusable templates for different types of problems (e.g., math problems, logic puzzles). This approach not only makes the codebase cleaner but also allows educators to quickly add new problems without rewriting common logic.

```python
def math_problem(question, correct_answer):
    """
    Function to present a math problem and check the user's answer.
    :param question: str
    :param correct_answer: int
    """
    try:
        user_answer = int(input(question))
        if user_answer == correct_answer:
            print("Correct!")
        else:
            print("Try again!")
    except ValueError:
        print("Please enter a valid number.")

# Example usage
math_problem("What is 5 + 3? ", 8)
```

In this example, the `math_problem` function encapsulates the logic for presenting a math problem and checking the user's answer, making it easy to reuse for different questions.

---

### Integration

This content is structured with clear headings and sections for easy parsing and integration into your learning platform. Use markdown formatting for clarity and organization.

By understanding how to define and call functions, you can create more engaging and interactive coding lessons for kids, helping them grasp fundamental programming concepts while having fun. Keep practicing, and soon you'll be able to build a portfolio of educational projects that captivate young learners!