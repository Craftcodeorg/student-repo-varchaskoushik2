### Personalized Curriculum: Introduction to Coding and Educational Technology

---

#### Module Title: Introduction to Coding and Educational Technology

---

### Assignment 2: Create a Simple Game that Uses a Loop and Basic Game Mechanics

#### Problem Statement:
In this assignment, you will create a simple game using the Scratch programming platform. The game will involve a character that moves continuously in a loop, collecting items while avoiding obstacles. This project will help you apply key concepts from the lecture on EdTech, such as game-based learning and storytelling, to create an engaging educational experience for kids.

---

### Starter Code:
Below is a basic framework for your Scratch project. You will build upon this by adding game mechanics, such as item collection and obstacle avoidance.

```plaintext
When green flag clicked
   forever
      move 10 steps
      if on edge, bounce
```

This code snippet sets up a character that moves continuously and bounces off the edges of the screen.

---

### Detailed Instructions:

1. **Setup Your Scratch Environment:**
   - Open the Scratch programming platform (https://scratch.mit.edu/).
   - Create a new project and name it "Simple Game with Loops."

2. **Character Movement:**
   - Use the starter code to make your character move continuously.
   - Modify the movement so that the character can be controlled using arrow keys.
   
   ```plaintext
   When green flag clicked
      forever
         if key "right arrow" pressed
            change x by 10
         if key "left arrow" pressed
            change x by -10
         if key "up arrow" pressed
            change y by 10
         if key "down arrow" pressed
            change y by -10
   ```

3. **Item Collection:**
   - Add items (e.g., stars) to the game that the character can collect.
   - Use a loop to continuously check if the character is touching an item.
   - If an item is collected, make it disappear and increase the score.
   
   ```plaintext
   When green flag clicked
      forever
         if touching "star"
            hide
            change score by 1
   ```

4. **Obstacle Avoidance:**
   - Add obstacles (e.g., rocks) to the game that the character must avoid.
   - Use a loop to check if the character is touching an obstacle.
   - If an obstacle is touched, end the game or decrease the score.
   
   ```plaintext
   When green flag clicked
      forever
         if touching "rock"
            stop all
   ```

5. **Game Over Condition:**
   - Implement a game over condition when the character touches an obstacle.
   - Display a "Game Over" message and stop all actions.
   
   ```plaintext
   When green flag clicked
      forever
         if touching "rock"
            broadcast "game over"
            stop all

   When I receive "game over"
      say "Game Over" for 2 seconds
   ```

6. **Enhancements:**
   - Add background music and sound effects for item collection and game over.
   - Create multiple levels with increasing difficulty.

---

### Criteria for Success and Evaluation:

**Success Criteria:**
- The game includes a character that moves continuously and can be controlled using arrow keys.
- The character can collect items and increase the score.
- The game includes obstacles that end the game when touched.
- The code is clean, well-documented, and follows best practices.
- The game includes sound effects and multiple levels for enhanced engagement.

**Evaluation Rubric:**

| Criteria                  | Excellent (5)       | Good (4)           | Satisfactory (3)    | Needs Improvement (2) | Poor (1)             |
|---------------------------|---------------------|--------------------|---------------------|-----------------------|----------------------|
| Character Movement        | Smooth and responsive | Mostly smooth     | Some lag or issues  | Frequent issues       | Barely functional    |
| Item Collection           | Fully functional    | Mostly functional  | Some issues         | Frequent issues       | Non-functional       |
| Obstacle Avoidance        | Fully functional    | Mostly functional  | Some issues         | Frequent issues       | Non-functional       |
| Game Over Condition       | Clear and effective | Mostly clear       | Somewhat clear      | Not very clear        | Unclear or missing   |
| Code Quality              | Clean and well-documented | Mostly clean    | Adequate            | Needs improvement     | Poor quality         |
| Engagement                | Highly engaging     | Engaging           | Moderately engaging | Slightly engaging     | Not engaging         |

---

### Practical Application:
By completing this assignment, you will gain hands-on experience in using loops and basic game mechanics to create an engaging educational game. This project will help you develop skills in storytelling and learning experience design, which are crucial for your career goal of teaching coding to kids in an EdTech environment.

---

### Next Steps:
In our next lecture, we will explore advanced coding platforms designed for kids and how you can leverage them to create more complex educational games. To prepare, continue experimenting with Scratch and try creating variations of your simple game. This practice will enhance your understanding of game mechanics and coding logic.

Thank you for your dedication to creating captivating learning experiences for kids. See you in the next lecture!