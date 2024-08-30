### Module Title: Fundamentals of Python Programming

---

### Exercise Requirements

#### 1. Problem Statement:
Create a problem that requires the student to apply "Exercise 3: Write an if-else statement to check if a number is positive or negative" to a scenario directly related to the content covered in the lecture "Variables and Data Types: Understanding Different Types of Data."

**Scenario:**
Imagine you are developing a simple text-based game for kids where a character named Alice collects items and gains or loses health points based on certain actions. You need to write a function that checks if Alice's health points are positive or negative after an action is performed.

**Task:**
Write a function `check_health_status` that takes an integer `health_points` as input and prints whether Alice's health points are positive, negative, or zero. Use an if-else statement to perform this check.

---

#### 2. Fill-in-the-Blank Starter Code:

```python
# Function to check if health points are positive, negative, or zero
def check_health_status(health_points):
    # Check if health points are positive
    if health_points > 0:
        print("Alice's health is positive.")
    # Check if health points are zero
    elif health_points == 0:
        print("Alice's health is neutral.")
    # If health points are negative
    else:
        print("Alice's health is negative.")

# Example usage:
# Define Alice's health points after an action
alice_health = _______

# Call the function to check Alice's health status
check_health_status(alice_health)
```

---

#### 3. Hints:

1. **Hint 1:** Recall from the lecture that an if-else statement allows you to make decisions in your code. You can use comparison operators (`>`, `<`, `==`) to compare the value of `health_points`.
   
2. **Hint 2:** Think about the different conditions you need to check for: positive, negative, and zero health points. Use the appropriate comparison operator for each condition.

3. **Hint 3:** Remember to assign a value to `alice_health` before calling the `check_health_status` function. This value should be an integer representing Alice's current health points.

---

#### 4. Expected Outcome:

The student should be able to fill in the blanks correctly, demonstrating an understanding of how the concepts apply to real-world scenarios in EdTech. The final solution should adhere to best practices, include error handling, and be well-commented to explain the reasoning behind each step, as emphasized in the lecture.

**Example Solution:**

```python
# Function to check if health points are positive, negative, or zero
def check_health_status(health_points):
    # Check if health points are positive
    if health_points > 0:
        print("Alice's health is positive.")
    # Check if health points are zero
    elif health_points == 0:
        print("Alice's health is neutral.")
    # If health points are negative
    else:
        print("Alice's health is negative.")

# Example usage:
# Define Alice's health points after an action
alice_health = 10

# Call the function to check Alice's health status
check_health_status(alice_health)
```

**Expected Output:**
```
Alice's health is positive.
```

By completing this exercise, students will practice using variables, data types, and control structures (if-else statements) in a practical and engaging context relevant to their interests in EdTech and game-based learning.

---

### Integration

Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

---

Thank you for participating in this exercise! Keep practicing, and see you next time!