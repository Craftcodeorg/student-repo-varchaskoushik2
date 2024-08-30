### Assignment 1: Develop a Simple Calculator Program

#### Problem Statement:
In this assignment, you will create a simple calculator program that can perform basic arithmetic operations (addition, subtraction, multiplication, and division). This task will help you apply the key concepts of Python's simplicity and readability, which were discussed in the lecture. The calculator will be an interactive command-line tool where users can input two numbers and select an operation to perform.

#### Starter Code:
Below is the starter code for the calculator program. You will need to build upon this framework by adding functions for each arithmetic operation and logic to handle user inputs.

```python
# Simple Calculator Program

def add(x, y):
    # TODO: Implement addition
    pass

def subtract(x, y):
    # TODO: Implement subtraction
    pass

def multiply(x, y):
    # TODO: Implement multiplication
    pass

def divide(x, y):
    # TODO: Implement division
    pass

def main():
    print("Welcome to the Simple Calculator!")
    
    while True:
        print("\nSelect operation:")
        print("1. Add")
        print("2. Subtract")
        print("3. Multiply")
        print("4. Divide")
        print("5. Exit")

        choice = input("Enter choice (1/2/3/4/5): ")

        if choice == '5':
            print("Exiting the calculator. Goodbye!")
            break

        if choice in ['1', '2', '3', '4']:
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))

            if choice == '1':
                print(f"The result is: {add(num1, num2)}")
            elif choice == '2':
                print(f"The result is: {subtract(num1, num2)}")
            elif choice == '3':
                print(f"The result is: {multiply(num1, num2)}")
            elif choice == '4':
                print(f"The result is: {divide(num1, num2)}")
        else:
            print("Invalid Input")

if __name__ == "__main__":
    main()
```

#### Detailed Instructions:

**Step 1: Implement Addition Function**
- In the `add` function, write code to return the sum of `x` and `y`.

```python
def add(x, y):
    return x + y
```

**Step 2: Implement Subtraction Function**
- In the `subtract` function, write code to return the difference between `x` and `y`.

```python
def subtract(x, y):
    return x - y
```

**Step 3: Implement Multiplication Function**
- In the `multiply` function, write code to return the product of `x` and `y`.

```python
def multiply(x, y):
    return x * y
```

**Step 4: Implement Division Function**
- In the `divide` function, write code to return the quotient of `x` divided by `y`.
- Ensure you handle division by zero by checking if `y` is zero and returning an appropriate message.

```python
def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    return x / y
```

**Step 5: Enhance User Interaction**
- Modify the `main` function to provide a more interactive experience. For example, you can add error handling for invalid inputs and ensure the user can perform multiple calculations without restarting the program.

#### Criteria for Success and Evaluation:

**Success Criteria:**
- The program correctly performs addition, subtraction, multiplication, and division.
- The code is clean, well-documented, and follows best practices.
- The program handles edge cases, such as division by zero.
- The user interface is intuitive and provides clear instructions and feedback.

**Evaluation Rubric:**

| Criteria                  | Excellent (10) | Good (7-9) | Satisfactory (4-6) | Needs Improvement (1-3) |
|---------------------------|----------------|------------|--------------------|-------------------------|
| Functionality             | All operations work correctly and handle edge cases | Most operations work correctly | Some operations work correctly | Operations do not work correctly |
| Code Quality              | Clean, well-documented code with no errors | Mostly clean code with minor issues | Some documentation and minor errors | Poorly documented code with errors |
| User Interface            | Intuitive and user-friendly interface | Mostly user-friendly interface | Somewhat user-friendly interface | Confusing or difficult interface |
| Error Handling            | Handles all edge cases gracefully | Handles most edge cases | Handles some edge cases | Does not handle edge cases |

By completing this assignment, you will reinforce your understanding of Python's simplicity and readability while creating a practical tool that can be used as an educational resource for teaching coding to kids. This aligns with your goal of developing engaging and captivating projects for young learners in EdTech.