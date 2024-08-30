### Module Title: Interactive Tutorials and Code-Along Videos

---

### Exercise Requirements

#### Problem Statement
Create an interactive quiz to assess understanding of loops in Python. This exercise should be designed for kids aged 8-15 and incorporate storytelling elements to make it engaging. The quiz will feature a scenario where a character named Alex needs to collect items to complete a quest. Each item requires solving a loop-related coding question.

#### Scenario
Alex is on a quest to collect magical items scattered across a fantasy land. To collect each item, Alex must solve a coding challenge that involves understanding loops in Python. Help Alex by designing an interactive quiz that tests the following concepts:
1. Basic for-loops
2. Nested loops
3. While-loops
4. Loop control statements (break, continue)

---

### Fill-in-the-Blank Starter Code

Below is the starter code for the interactive quiz. Fill in the blanks to complete the functionality.

```python
# Alex's Quest: Collecting Magical Items

# Function to collect magical items using a for-loop
def collect_items_for_loop(items):
    collected_items = []
    for item in items:
        collected_items.append(item)
        print(f"Collected: {item}")
    return collected_items

# Function to collect magical items using a while-loop
def collect_items_while_loop(items):
    collected_items = []
    index = 0
    while index < len(items):
        collected_items.append(items[index])
        print(f"Collected: {items[index]}")
        index += 1
    return collected_items

# Function to collect magical items using nested loops
def collect_nested_loops(matrix):
    collected_items = []
    for row in matrix:
        for item in row:
            collected_items.append(item)
            print(f"Collected: {item}")
    return collected_items

# Function demonstrating loop control statements
def collect_with_control_statements(items):
    collected_items = []
    for item in items:
        if item == "skip":
            continue  # Skip this item
        if item == "stop":
            break  # Stop collecting items
        collected_items.append(item)
        print(f"Collected: {item}")
    return collected_items

# Test the functions with example values
items = ["wand", "potion", "spellbook"]
matrix = [["wand", "potion"], ["spellbook", "crystal"]]

print("For Loop Collection:")
print(collect_items_for_loop(items))

print("While Loop Collection:")
print(collect_items_while_loop(items))

print("Nested Loops Collection:")
print(collect_nested_loops(matrix))

print("Control Statements Collection:")
print(collect_with_control_statements(["wand", "skip", "potion", "stop", "spellbook"]))
```

---

### Hints

1. **For-Loop**: Remember that a for-loop iterates over each element in a list.
   - Hint: Use `for item in items:` to iterate over the `items` list.
   
2. **While-Loop**: A while-loop continues as long as a condition is true.
   - Hint: Use `while index < len(items):` to loop through the list using an index.
   
3. **Nested Loops**: Nested loops are used for iterating over multi-dimensional data structures.
   - Hint: Use `for row in matrix:` and then `for item in row:` to access each element.
   
4. **Loop Control Statements**: `continue` skips the current iteration, and `break` exits the loop.
   - Hint: Use `if item == "skip": continue` and `if item == "stop": break` within the loop.

---

### Expected Outcome

The student should be able to fill in the blanks correctly, demonstrating an understanding of how loops work in Python. The final solution should adhere to best practices, include error handling, and be well-commented to explain the reasoning behind each step.

```python
# Alex's Quest: Collecting Magical Items

# Function to collect magical items using a for-loop
def collect_items_for_loop(items):
    collected_items = []
    for item in items:
        collected_items.append(item)
        print(f"Collected: {item}")
    return collected_items

# Function to collect magical items using a while-loop
def collect_items_while_loop(items):
    collected_items = []
    index = 0
    while index < len(items):
        collected_items.append(items[index])
        print(f"Collected: {items[index]}")
        index += 1
    return collected_items

# Function to collect magical items using nested loops
def collect_nested_loops(matrix):
    collected_items = []
    for row in matrix:
        for item in row:
            collected_items.append(item)
            print(f"Collected: {item}")
    return collected_items

# Function demonstrating loop control statements
def collect_with_control_statements(items):
    collected_items = []
    for item in items:
        if item == "skip":
            continue  # Skip this item
        if item == "stop":
            break  # Stop collecting items
        collected_items.append(item)
        print(f"Collected: {item}")
    return collected_items

# Test the functions with example values
items = ["wand", "potion", "spellbook"]
matrix = [["wand", "potion"], ["spellbook", "crystal"]]

print("For Loop Collection:")
print(collect_items_for_loop(items))

print("While Loop Collection:")
print(collect_items_while_loop(items))

print("Nested Loops Collection:")
print(collect_nested_loops(matrix))

print("Control Statements Collection:")
print(collect_with_control_statements(["wand", "skip", "potion", "stop", "spellbook"]))
```

### Integration

Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

---

By completing this exercise, students will gain hands-on experience with loops in Python, reinforcing their understanding through interactive and engaging content designed specifically for kids. This approach aligns with your goal of creating educational content that captivates young learners and makes coding fun.