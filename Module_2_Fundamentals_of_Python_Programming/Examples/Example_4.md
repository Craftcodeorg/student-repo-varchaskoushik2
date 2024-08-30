### Module Title: Fundamentals of Python Programming

---

### Example 4: For Loop and While Loop

---

#### 1. **Introduction**

In this example, we will delve deeper into the concepts of `for` and `while` loops as covered in the lecture on Control Structures. Loops are fundamental tools in programming that allow us to execute a block of code multiple times, which is essential for tasks that require repetition. This example will illustrate how to use these loops effectively to create engaging and interactive educational content, particularly for teaching kids coding.

---

#### 2. **Code Snippet**

Below is a well-commented code snippet that demonstrates the use of `for` and `while` loops. This example is designed for an intermediate-level programmer and includes error handling and best practices.

```python
# This function prints numbers from 0 to a given limit using a for loop
def print_numbers_with_for(limit):
    try:
        # Ensure the limit is a positive integer
        if limit < 0:
            raise ValueError("Limit must be a non-negative integer.")
        
        # Using a for loop to iterate over a range of numbers
        for i in range(limit + 1):
            print(i)
    except ValueError as e:
        print(f"Error: {e}")

# This function prints numbers from 0 to a given limit using a while loop
def print_numbers_with_while(limit):
    try:
        # Ensure the limit is a positive integer
        if limit < 0:
            raise ValueError("Limit must be a non-negative integer.")
        
        count = 0
        # Using a while loop to iterate until the count reaches the limit
        while count <= limit:
            print(count)
            count += 1
    except ValueError as e:
        print(f"Error: {e}")

# Example usage
print("Using for loop:")
print_numbers_with_for(5)

print("\nUsing while loop:")
print_numbers_with_while(5)
```

---

#### 3. **Explanation**

Let's break down the code step-by-step to understand how it implements the key concepts from the lecture:

1. **Function Definition**:
   - Two functions are defined: `print_numbers_with_for` and `print_numbers_with_while`. Each function takes a single parameter `limit`, which determines the range of numbers to print.

2. **Error Handling**:
   - Both functions include error handling to ensure that the `limit` is a non-negative integer. If the `limit` is negative, a `ValueError` is raised with an appropriate message.

3. **For Loop**:
   - In `print_numbers_with_for`, a `for` loop is used to iterate over a range of numbers from 0 to `limit`. The `range` function generates this sequence, and each number is printed within the loop.

4. **While Loop**:
   - In `print_numbers_with_while`, a `while` loop is used to achieve the same result. The loop continues to execute as long as the `count` variable is less than or equal to `limit`. After printing each number, `count` is incremented by 1.

5. **Example Usage**:
   - The functions are called with a `limit` of 5, demonstrating how both loops can be used to print numbers from 0 to 5.

---

#### 4. **Application**

In the context of EdTech, understanding and implementing loops can significantly enhance the learning experience by enabling the creation of interactive and repetitive tasks. Here’s how these concepts can be applied:

- **Interactive Exercises**: Loops can be used to create exercises where students practice coding by repeatedly solving similar problems with different inputs.
- **Game-Based Learning**: In educational games, loops can manage game states, update scores, and handle user interactions in real-time.
- **Automated Feedback**: Loops can automate the process of checking multiple student submissions, providing instant feedback and improving learning efficiency.

For instance, consider an educational game where kids need to solve math problems to advance levels. Using loops, you can generate a series of problems, check answers, and provide immediate feedback, making learning both engaging and effective.

---

### Integration

The content above is structured with clear headings and sections for easy parsing and integration into your learning platform. Using markdown formatting ensures that each part of the content is easily readable and accessible.

By following this structured approach, you can create educational content that not only teaches coding concepts but also engages students through interactive and practical applications. Keep experimenting with these ideas in your projects, and you'll find innovative ways to make coding fun and educational for kids!