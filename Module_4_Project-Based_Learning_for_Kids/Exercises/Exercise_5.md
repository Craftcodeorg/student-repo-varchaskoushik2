### Module Title: Project-Based Learning for Kids

---

### Exercise Requirements

#### 1. Problem Statement

**Exercise 5: Develop an Educational Game Using Scratch**

Welcome to Exercise 5! In this exercise, you will apply the concepts discussed in Lecture 5: Real-World Applications of PBL in Coding Education to create an educational game using Scratch. Your goal is to develop a game that teaches basic programming concepts to kids aged 8-15. This exercise will help you understand how to design engaging and educational projects that make learning fun and interactive.

**Scenario:**

Create a simple game where a character navigates through a maze to collect items. Each item collected will teach a new programming concept, such as loops, conditionals, or variables. The game should include:

1. A clear objective (e.g., collect all items to win).
2. Basic game mechanics (e.g., character movement, item collection).
3. Educational pop-ups or messages that explain the programming concepts when an item is collected.

---

#### 2. Fill-in-the-Blank Starter Code

Below is the starter code for your Scratch game. Fill in the blanks to complete the functionality. This code includes comments and guidance relevant to storytelling and game-based learning.

```python
# Starter code for implementing lecture concepts

# Initialize the game
when green flag clicked
    go to x:0 y:0
    set score to 0
    show

# Character movement
forever
    if <key "up arrow" pressed?>
        change y by 10
    if <key "down arrow" pressed?>
        change y by -10
    if <key "right arrow" pressed?>
        change x by 10
    if <key "left arrow" pressed?>
        change x by -10

# Item collection
when I start as a clone
    if <touching "character"?>
        hide
        change score by 1
        # Display educational message
        say "Great! You learned about _______!" for 2 seconds

# Create maze and items
when green flag clicked
    create clone of [item v]
    go to random position
    show

# Winning condition
forever
    if <score = _______>
        say "Congratulations! You collected all items and learned new programming concepts!" for 2 seconds
        stop all
```

---

#### 3. Hints

1. **Character Movement:** Ensure that the character can move in all four directions using the arrow keys.
2. **Item Collection:** Use the `touching` block to detect when the character collects an item and increase the score.
3. **Educational Messages:** Use the `say` block to display messages that explain the programming concepts when an item is collected.
4. **Winning Condition:** Set a winning condition by checking if the score equals the total number of items.

---

#### 4. Expected Outcome

By completing this exercise, you should be able to:

1. Create a simple educational game using Scratch that teaches basic programming concepts.
2. Apply project-based learning principles to design engaging and educational content.
3. Demonstrate an understanding of how storytelling and game-based learning can enhance coding education for kids.

The final solution should adhere to best practices, include error handling, and be well-commented to explain the reasoning behind each step, as emphasized in the lecture.

---

### Integration

Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

---

By completing this exercise, you will build a portfolio of fun and educational coding projects that you can teach to kids aged 8-15, helping them grasp coding concepts while having fun. This aligns with your career goals in EdTech and your interest in creating engaging learning experiences for kids.