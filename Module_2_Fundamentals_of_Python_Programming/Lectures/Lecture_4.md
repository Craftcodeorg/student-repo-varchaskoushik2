### Lecture: 4. Control Structures: If statements, loops, and functions

---

#### 1. **Learning Objectives**:

By the end of this lecture, you will:
- Understand the purpose and use of control structures in Python.
- Be able to write and use `if` statements to make decisions in your code.
- Know how to implement loops (`for` and `while`) to repeat actions.
- Be able to define and call functions to organize and reuse code.

---

#### 2. **Introduction**:

Control structures are the backbone of any programming language, allowing you to control the flow of your program. For those teaching coding to kids, mastering these concepts is essential as they form the foundation of problem-solving and logical thinking in programming. Understanding control structures will also enable you to create engaging, interactive stories and games, making learning more fun and effective for children.

---

#### 3. **Core Concepts**:

**a. If Statements:**
- **Definition**: `If` statements allow you to execute certain pieces of code based on conditions.
- **Syntax**:
    ```python
    if condition:
        # code to execute if condition is true
    ```
- **Example**:
    ```python
    age = 10
    if age < 13:
        print("You are a child.")
    ```

**b. Loops:**
- **For Loops**:
  - **Definition**: `For` loops are used to iterate over a sequence (like a list, tuple, or string).
  - **Syntax**:
    ```python
    for item in sequence:
        # code to execute for each item
    ```
  - **Example**:
    ```python
    for i in range(5):
        print(i)
    ```

- **While Loops**:
  - **Definition**: `While` loops continue to execute as long as a condition is true.
  - **Syntax**:
    ```python
    while condition:
        # code to execute while condition is true
    ```
  - **Example**:
    ```python
    count = 0
    while count < 5:
        print(count)
        count += 1
    ```

**c. Functions:**
- **Definition**: Functions are blocks of reusable code that perform a specific task.
- **Syntax**:
    ```python
    def function_name(parameters):
        # code to execute
        return result
    ```
- **Example**:
    ```python
    def greet(name):
        return f"Hello, {name}!"

    print(greet("Alice"))
    ```

---

#### 4. **Practical Application**:

To illustrate these concepts, let's consider a simple storytelling scenario where we create an interactive story for kids.

**Example Scenario**:
You are creating a story where the user can choose their path.

```python
def choose_adventure():
    print("You are in a dark forest. Do you want to go left or right?")
    choice = input("Type 'left' or 'right': ")

    if choice == 'left':
        print("You find a friendly dragon!")
    elif choice == 'right':
        print("You find a hidden treasure!")
    else:
        print("Invalid choice. Try again.")
        choose_adventure()

choose_adventure()
```

In this example, `if` statements are used to determine the path the story takes based on user input. This interactive approach makes learning programming fun and relatable for kids.

---

#### 5. **Summary**:

- Control structures like `if` statements, loops, and functions are crucial for directing the flow of a program.
- `If` statements help make decisions based on conditions.
- Loops (`for` and `while`) allow repeating actions multiple times.
- Functions enable code reusability and organization.
- These concepts are foundational for creating interactive stories and games, making coding engaging for kids.

---

#### 6. **Next Steps**:

In the next lecture, we will dive into **Data Structures: Lists, Tuples, and Dictionaries**, which will help you manage collections of data efficiently. Before moving on, review your notes on control structures and try creating a simple interactive story or game using `if` statements, loops, and functions. This hands-on practice will reinforce your understanding and prepare you for the upcoming topics.

---

Keep experimenting with these concepts in your projects, and you'll soon see how powerful control structures can be in making your programs dynamic and interactive!