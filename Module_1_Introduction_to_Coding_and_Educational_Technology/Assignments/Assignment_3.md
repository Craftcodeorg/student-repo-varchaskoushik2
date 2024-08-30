### Assignment 3: Develop an Interactive Tutorial Using Storytelling

---

#### **Problem Statement**:
You are tasked with creating an interactive tutorial that teaches a basic coding concept using storytelling. This assignment will help you apply the concepts of syntax and semantics discussed in Lecture 3. The interactive tutorial should be engaging for kids aged 8-15 and should make learning fun and intuitive.

---

#### **Assignment Components**:

---

**1. Problem Statement:**

Create an interactive story game where kids can choose their own adventure paths. The game should teach the basic concept of conditional statements (`if`, `elif`, `else`) in Python. The story should be captivating and educational, helping kids understand how different choices lead to different outcomes.

---

**2. Starter Code:**

Below is the starter code for the interactive story game. You will need to build upon this framework to complete the assignment.

```python
# Starter code for an interactive story game

def adventure_game():
    print("Welcome to the Adventure Game!")
    print("You are in a forest and you need to find your way out.")
    
    # Step 1: Get the first choice from the user
    choice1 = input("Do you want to go left or right? ")
    
    if choice1 == "left":
        print("You find a river.")
        # Step 2: Get the second choice from the user
        choice2 = input("Do you want to swim across or walk along the river? ")
        
        if choice2 == "swim":
            print("You swim across and find a treasure chest!")
        elif choice2 == "walk":
            print("You walk along the river and encounter a friendly dragon!")
        else:
            print("Invalid choice, try again.")
            
    elif choice1 == "right":
        print("You find a cave.")
        # Step 2: Get the second choice from the user
        choice2 = input("Do you want to enter the cave or walk past it? ")
        
        if choice2 == "enter":
            print("You enter the cave and discover hidden jewels!")
        elif choice2 == "walk":
            print("You walk past the cave and meet a wise old man who gives you a map!")
        else:
            print("Invalid choice, try again.")
            
    else:
        print("Invalid choice, try again.")

# Run the game
adventure_game()
```

---

**3. Detailed Instructions:**

**Step 1:** Modify the story to include at least three levels of choices. Each level should have at least two different outcomes based on the user's input.

**Step 2:** Add comments to your code explaining the syntax and semantics of each part, especially focusing on the conditional statements.

**Step 3:** Include error handling for invalid inputs at each level of choice to ensure the game continues smoothly.

**Step 4:** Enhance the storytelling aspect by adding more descriptive text and making the story more engaging for kids.

**Step 5:** Test your game with different choices to ensure all possible paths work correctly and provide meaningful outcomes.

---

**4. Criteria for Success and Evaluation:**

**Success Criteria:**
- The game includes at least three levels of choices with multiple outcomes.
- The code is well-commented, explaining the syntax and semantics clearly.
- Error handling is implemented for invalid inputs.
- The story is engaging and educational, suitable for kids aged 8-15.
- The game runs smoothly without any syntax or semantic errors.

**Evaluation Rubric:**
- **Functionality (40%)**: The game works as expected, with all paths leading to meaningful outcomes.
- **Code Quality (30%)**: The code is clean, well-organized, and follows best practices.
- **Educational Value (20%)**: The game effectively teaches the concept of conditional statements.
- **Engagement (10%)**: The story is captivating and keeps kids interested in playing and learning.

---

**Next Steps:**

After completing this assignment, review your work and identify areas for improvement. In our next lecture, we will dive into "Variables and Data Types: Building blocks of programming." To prepare, continue practicing writing simple programs focusing on correct syntax and meaningful semantics. This will set a solid foundation for understanding how variables and data types work in coding.

---

Thank you for your effort! Keep practicing, and see you next time!