### Module Title: Introduction to Coding and Educational Technology ###

---

### Exercise 4: Create a Short Story Using Variables ###

#### Problem Statement:
In this exercise, you will create a short interactive story using variables in Python. This task will help you apply the concepts discussed in Lecture 4, particularly how coding integrates with storytelling to enhance educational engagement for kids aged 8-15. Your story should include characters, dialogues, and a simple interaction based on user input. Use variables to store character names, dialogues, and user choices.

#### Starter Code:
Below is the starter code for your interactive story. Fill in the blanks to complete the functionality.

```python
# Starter code for creating an interactive story using variables

# Define character names using variables
character1 = "______"
character2 = "______"

# Define dialogues using variables
dialogue1 = f"{character1}: Hello! What's your name?"
dialogue2 = f"{character2}: My name is ______. Nice to meet you!"
dialogue3 = f"{character1}: Nice to meet you too, ______! Do you want to go on an adventure?"

# Function to display the story
def display_story():
    print(dialogue1)
    user_name = input("Enter your name: ")
    print(dialogue2.replace("______", user_name))
    print(dialogue3.replace("______", user_name))
    
    # Simple interaction based on user input
    choice = input("Type 'yes' to go on an adventure or 'no' to stay home: ").lower()
    if choice == "yes":
        print(f"{character1}: Great! Let's start our adventure, {user_name}!")
    else:
        print(f"{character1}: Maybe next time, {user_name}. Have a great day!")

# Call the function to display the story
display_story()
```

#### Hints:
1. **Character Names**: Think of two fun and engaging names for your characters that kids aged 8-15 would find interesting.
2. **User Interaction**: Ensure the user input is captured correctly and integrated into the story. Use string replacement methods to personalize the dialogues.
3. **Conditional Logic**: Use an `if-else` statement to handle the user's choice for the adventure. Make sure to convert the user's input to lowercase to handle different cases (e.g., "Yes", "YES", "yes").

#### Expected Outcome:
The student should be able to complete the blanks, creating a short interactive story that:
- Engages the user by asking for their name.
- Personalizes the story based on the user's input.
- Provides a simple interaction where the user decides whether to go on an adventure or not.
- Demonstrates understanding of variables, string manipulation, and conditional logic.

The final solution should look something like this:

```python
# Starter code for creating an interactive story using variables

# Define character names using variables
character1 = "Alex"
character2 = "Jamie"

# Define dialogues using variables
dialogue1 = f"{character1}: Hello! What's your name?"
dialogue2 = f"{character2}: My name is ______. Nice to meet you!"
dialogue3 = f"{character1}: Nice to meet you too, ______! Do you want to go on an adventure?"

# Function to display the story
def display_story():
    print(dialogue1)
    user_name = input("Enter your name: ")
    print(dialogue2.replace("______", user_name))
    print(dialogue3.replace("______", user_name))
    
    # Simple interaction based on user input
    choice = input("Type 'yes' to go on an adventure or 'no' to stay home: ").lower()
    if choice == "yes":
        print(f"{character1}: Great! Let's start our adventure, {user_name}!")
    else:
        print(f"{character1}: Maybe next time, {user_name}. Have a great day!")

# Call the function to display the story
display_story()
```

This exercise will help students understand how coding can be used creatively to engage kids in educational activities, combining storytelling with interactive learning elements.