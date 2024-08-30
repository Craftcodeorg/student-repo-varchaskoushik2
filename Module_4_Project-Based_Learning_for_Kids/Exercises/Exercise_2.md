### Module Title: Project-Based Learning for Kids ###

### Exercise Requirements ###

#### Exercise 2: Implement Variables and Loops in Your Project ####

1. **Problem Statement**:
   Create a problem that requires the student to apply "Exercise 2: Implement variables and loops in your project" to a scenario directly related to the content covered in "### Lecture: 2. Designing Kid-Friendly Projects: Making projects fun and educational."

   **Scenario**:
   You are tasked with creating an interactive story-based coding project for kids aged 8-15. The project will involve a character named Codey the Coder who needs to collect pieces of code scattered across different levels. Each level requires the use of variables and loops to solve puzzles and advance to the next stage. Your goal is to implement these elements to make the project engaging and educational.

   **Task**:
   - Design a simple game where Codey the Coder collects items by solving coding challenges.
   - Use variables to keep track of collected items.
   - Implement loops to navigate through different levels and challenges.

2. **Fill-in-the-Blank Starter Code**:
   ```python
   # Starter code for implementing lecture concepts
   
   # Define the number of levels
   total_levels = 3

   # Initialize a variable to keep track of collected items
   collected_items = []

   # Function to display the current status
   def display_status(level, items):
       print(f"Level {level}: You have collected {len(items)} items: {items}")

   # Main game loop
   for level in range(1, total_levels + 1):
       print(f"\nWelcome to Level {level}!")
       item = input("Enter the item you found: ")
       collected_items.append(item)
       
       # Display the current status after each level
       display_status(level, collected_items)

       # Check if Codey has collected all items
       if len(collected_items) == total_levels:
           print("\nCongratulations! You have collected all the items and completed the quest!")
       else:
           print("Keep going! More items to collect!")

   ```

3. **Hints**:
   - **Hint 1**: Remember that variables can store data that you can use later in your code. In this exercise, use a list to keep track of the items Codey collects.
   - **Hint 2**: Loops can help you repeat actions multiple times. Use a `for` loop to iterate through each level.
   - **Hint 3**: Use the `input()` function to get user input for the items Codey collects at each level.
   - **Hint 4**: Think about how you can update the list of collected items and display the current status after each level.

4. **Expected Outcome**:
   The student should be able to fill in the blanks correctly, demonstrating an understanding of how variables and loops can be used in a story-based coding project. The final solution should include:
   - A list variable to keep track of collected items.
   - A `for` loop to iterate through levels.
   - User input to collect items.
   - A function to display the current status after each level.
   
   The output should look something like this:
   ```
   Welcome to Level 1!
   Enter the item you found: key
   Level 1: You have collected 1 items: ['key']
   Keep going! More items to collect!

   Welcome to Level 2!
   Enter the item you found: map
   Level 2: You have collected 2 items: ['key', 'map']
   Keep going! More items to collect!

   Welcome to Level 3!
   Enter the item you found: treasure
   Level 3: You have collected 3 items: ['key', 'map', 'treasure']

   Congratulations! You have collected all the items and completed the quest!
   ```

### Integration ###
- Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

---

By following these guidelines, you will create an engaging and educational coding project that uses variables and loops, aligned with your career goals in EdTech. This exercise will help kids aged 8-15 grasp coding concepts while having fun with storytelling and game-based learning.