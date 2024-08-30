### Module Title: Introduction to Coding and Educational Technology

### Exercise Requirements

#### Problem Statement:
Create a problem that requires the student to apply "Exercise 5: Implement a basic game loop" to a scenario directly related to the content covered in "Lecture 5: Storytelling in Coding: Making learning engaging through narratives."

**Exercise 5: Implement a Basic Game Loop**

**Scenario**: 
You are tasked with creating an interactive story game for kids using Python. The story involves a character named "Alex" who needs to navigate through different rooms in a castle to find a hidden treasure. Each room presents a challenge that Alex must solve using coding concepts. Your task is to implement a basic game loop that will drive this interactive story.

#### Learning Objectives:
By the end of this exercise, you will be able to:
- Implement a basic game loop in Python.
- Integrate storytelling elements into coding exercises.
- Create an engaging and interactive coding project for kids.

#### Instructions:
1. **Design the Game Loop**:
   - The game loop should continue running until the player either finds the treasure or decides to quit.
   - Each iteration of the loop should present a new room with a challenge.
   - Use storytelling elements such as characters, plot, setting, and conflict resolution to make the game engaging.

2. **Implement the Game Loop**:
   - Use Python to implement the game loop.
   - Include at least three different rooms with unique challenges.
   - Use conditional statements and loops to manage the game flow.

3. **Example Challenge**:
   - Room 1: Alex encounters a locked door. The player must solve a math puzzle to unlock it.
   - Room 2: Alex finds a sleeping dragon. The player must choose between sneaking past or finding another route.
   - Room 3: Alex reaches the treasure room but must answer a riddle to claim the treasure.

#### Fill-in-the-Blank Starter Code:
```python
# Starter code for implementing the basic game loop

def main():
    # Introduction to the story
    print("Welcome to the Castle Adventure!")
    print("Help Alex find the hidden treasure by navigating through different rooms.")
    
    # Initialize game variables
    found_treasure = False
    current_room = 1
    
    # Basic game loop
    while not found_treasure:
        print(f"\nYou are now in Room {current_room}.")
        
        if current_room == 1:
            print("You encounter a locked door. Solve this math puzzle to unlock it.")
            answer = int(input("What is 5 + 3? "))
            if answer == 8:
                print("Correct! The door unlocks.")
                current_room += 1
            else:
                print("Incorrect. Try again.")
        
        elif current_room == 2:
            print("You find a sleeping dragon. Do you want to sneak past or find another route?")
            choice = input("Type 'sneak' to sneak past or 'route' to find another route: ").lower()
            if choice == 'sneak':
                print("You successfully sneak past the dragon.")
                current_room += 1
            else:
                print("You find another route and avoid the dragon.")
                current_room += 1
        
        elif current_room == 3:
            print("You reach the treasure room but must answer a riddle to claim the treasure.")
            riddle_answer = input("What has keys but can't open locks? ").lower()
            if riddle_answer == "piano":
                print("Correct! You found the hidden treasure!")
                found_treasure = True
            else:
                print("Incorrect. Try again.")
    
    print("Congratulations! You completed the Castle Adventure.")

# Start the game
if __name__ == "__main__":
    main()
```

#### Hints:
1. **Hint for Room 1**: Remember basic arithmetic operations. What is the sum of 5 and 3?
2. **Hint for Room 2**: Think about stealth versus safety. What would be a cautious approach?
3. **Hint for Room 3**: Consider common objects with 'keys' that aren't used for locks.

#### Expected Outcome:
The student should be able to fill in the blanks correctly, demonstrating an understanding of how storytelling elements can be integrated into coding exercises. The final solution should adhere to best practices, include error handling, and be well-commented to explain the reasoning behind each step, as emphasized in the lecture.

#### Integration:
- Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform.
- Use markdown for formatting and include any necessary files or resources as links.

### Next Steps:
In our next lecture, we will delve into "Game-Based Learning: Using games to teach coding concepts." To prepare, consider reviewing some popular educational games that teach coding, such as CodeCombat or Lightbot. Reflect on how these games use storytelling elements to keep learners engaged. This will help you better understand the intersection of game-based learning and storytelling in coding education.