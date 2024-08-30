### Assignment: Story-Based Game Project for Kids

**Module Title**: Project-Based Learning for Kids

**Assignment Title**: Design and Develop a Story-Based Game Project that Teaches Kids Basic Coding Concepts using Python or Scratch

---

#### **Problem Statement**

You are tasked with creating an engaging, story-based game project that introduces kids aged 8-15 to basic coding concepts. This project will use either Python or Scratch as the coding platform. The game should incorporate elements of storytelling and interactive gameplay to make learning fun and captivating. The goal is to help kids understand fundamental programming concepts such as sequences, loops, conditionals, and events through a narrative-driven approach.

---

#### **Starter Code**

**Python Starter Code:**

```python
# Starter code for a story-based game in Python

def start_game():
    print("Welcome to the Magic Forest Adventure!")
    print("You are about to embark on a journey to find the hidden treasure.")
    print("Make choices wisely to succeed in your quest.")
    
    # Step 1: Introduce the first decision point
    choice1 = input("You see two paths ahead. Do you choose the left path or the right path? (left/right): ")
    
    if choice1 == "left":
        left_path()
    elif choice1 == "right":
        right_path()
    else:
        print("Invalid choice. The game ends here.")
        
def left_path():
    print("You chose the left path and encounter a friendly dragon.")
    # Step 2: Add more interactions and choices here

def right_path():
    print("You chose the right path and find a mysterious cave.")
    # Step 2: Add more interactions and choices here

# Start the game
start_game()
```

**Scratch Starter Code:**

```scratch
when green flag clicked
say "Welcome to the Magic Forest Adventure!" for 2 seconds
say "You are about to embark on a journey to find the hidden treasure." for 2 seconds
say "Make choices wisely to succeed in your quest." for 2 seconds

# Step 1: Introduce the first decision point
ask "You see two paths ahead. Do you choose the left path or the right path? (left/right)" and wait

if <answer = "left"> then
    broadcast [left path v]
else
    if <answer = "right"> then
        broadcast [right path v]
    else
        say "Invalid choice. The game ends here." for 2 seconds
end

when I receive [left path v]
say "You chose the left path and encounter a friendly dragon." for 2 seconds
# Step 2: Add more interactions and choices here

when I receive [right path v]
say "You chose the right path and find a mysterious cave." for 2 seconds
# Step 2: Add more interactions and choices here
```

---

#### **Detailed Instructions**

**Step 1: Expand the Storyline**
- **Python**: Modify the `left_path` and `right_path` functions to include additional choices and interactions. For example, you can add a scenario where the player must solve a riddle to proceed.
- **Scratch**: Add more broadcasts and scripts to handle additional choices and interactions. For example, create new sprites or backdrops to represent different scenes in the story.

**Step 2: Introduce Coding Concepts**
- **Python**: Use loops and conditionals to create repetitive tasks or branching storylines. For instance, you can use a loop to give the player multiple attempts to solve a puzzle.
- **Scratch**: Utilize loops, conditionals, and events to manage game logic. For example, use a `repeat` block to create a countdown timer for a challenge.

**Step 3: Make it Interactive**
- **Python**: Add input prompts that require player responses. Ensure that each choice leads to different outcomes, enhancing the interactive experience.
- **Scratch**: Use `ask` blocks and broadcasts to create interactive dialogues and choices. Ensure that each response triggers different events or scenes.

**Step 4: Test and Refine**
- Test your game thoroughly to ensure all pathways and interactions work as intended.
- Refine the storyline and interactions based on feedback from test players.

---

#### **Criteria for Success and Evaluation**

**Success Criteria:**
- The game includes at least three decision points with multiple outcomes.
- Basic coding concepts such as sequences, loops, conditionals, and events are effectively integrated into the game.
- The storyline is engaging and appropriate for kids aged 8-15.
- The code is clean, well-documented, and follows best practices.
- The game is interactive, with clear feedback provided for each player choice.

**Evaluation Rubric:**

| Criteria                  | Excellent (5) | Good (4) | Satisfactory (3) | Needs Improvement (2) | Unsatisfactory (1) |
|---------------------------|---------------|----------|------------------|-----------------------|---------------------|
| **Engagement**            | Highly engaging storyline with multiple interactive elements. | Engaging storyline with some interactive elements. | Moderately engaging storyline with limited interactivity. | Storyline needs improvement; minimal interactivity. | Storyline is not engaging; lacks interactivity. |
| **Coding Concepts**       | Effectively integrates multiple coding concepts. | Integrates several coding concepts well. | Integrates basic coding concepts adequately. | Limited integration of coding concepts. | Does not effectively integrate coding concepts. |
| **Code Quality**          | Clean, well-documented code; follows best practices. | Mostly clean code with some documentation. | Adequate code quality; some documentation. | Code quality needs improvement; minimal documentation. | Poor code quality; lacks documentation. |
| **Interactivity**         | Highly interactive with clear feedback for each choice. | Interactive with some feedback for choices. | Moderately interactive with limited feedback. | Limited interactivity; minimal feedback. | Lacks interactivity; no feedback provided. |
| **Appropriateness**       | Content is highly appropriate for kids aged 8-15. | Content is mostly appropriate for kids aged 8-15. | Content is somewhat appropriate for kids aged 8-15. | Content needs improvement for age appropriateness. | Content is not appropriate for kids aged 8-15. |

---

By completing this assignment, you will apply the principles of Project-Based Learning (PBL) discussed in the lecture to create an engaging educational experience for kids. This hands-on project will help you build a portfolio of fun and educational coding projects, contributing to your career goal of teaching coding to kids in EdTech.

