### Assignment 2: Create a Math Tutoring Project Using Python

**Module Title:** Project-Based Learning for Kids

**Assignment Description:** Create a math tutoring project that uses Python to help kids practice arithmetic skills through interactive exercises.

---

### Problem Statement

In this assignment, you will create an interactive math tutoring project using Python. The project will help kids practice arithmetic skills (addition, subtraction, multiplication, and division) through a fun and engaging story-based game. The game will feature a character named "Mathy the Mathematician" who guides the learner through different levels of math challenges. Each correct answer will earn points, and learners will receive badges for completing levels.

### Starter Code

Below is the starter code for the project. You will build upon this code to create a fully functional math tutoring game.

```python
# Starter code for Math Tutoring Project

import random

def welcome_message():
    print("Welcome to Mathy's Math Tutoring Game!")
    name = input("Enter your name: ")
    print(f"Hello {name}, let's start our adventure with Mathy the Mathematician!")

def generate_question():
    operations = ['+', '-', '*', '/']
    num1 = random.randint(1, 10)
    num2 = random.randint(1, 10)
    operation = random.choice(operations)
    
    # Ensure no division by zero
    if operation == '/':
        while num2 == 0:
            num2 = random.randint(1, 10)
    
    question = f"What is {num1} {operation} {num2}?"
    return question, eval(f"{num1}{operation}{num2}")

def main_game():
    welcome_message()
    score = 0
    for _ in range(5):
        question, correct_answer = generate_question()
        print(question)
        user_answer = float(input("Your answer: "))
        
        if user_answer == correct_answer:
            print("Correct! You've earned a point.")
            score += 1
        else:
            print(f"Oops! The correct answer was {correct_answer}.")
    
    print(f"Game over! Your final score is {score} out of 5.")
    if score == 5:
        print("Congratulations! You've earned the 'Math Genius' badge.")
    elif score >= 3:
        print("Great job! You've earned the 'Math Enthusiast' badge.")
    else:
        print("Keep practicing! You've earned the 'Math Learner' badge.")

if __name__ == "__main__":
    main_game()
```

### Detailed Instructions

**Step 1: Enhance Storytelling**

- Modify the `welcome_message()` function to include a short story introduction where Mathy the Mathematician explains the importance of arithmetic skills and sets up the adventure.
- Example:
  ```python
  def welcome_message():
      print("Welcome to Mathy's Math Tutoring Game!")
      name = input("Enter your name: ")
      print(f"Hello {name}, I'm Mathy the Mathematician!")
      print("Today, we'll embark on an adventure to master arithmetic skills.")
      print("Solve the math problems to earn points and badges. Let's get started!")
  ```

**Step 2: Add Gamification Elements**

- Add levels to the game. Each level will have increasing difficulty.
- Track points and provide feedback after each question.
- Example:
  ```python
  def main_game():
      welcome_message()
      score = 0
      levels = {
          "Easy": (1, 10),
          "Medium": (10, 50),
          "Hard": (50, 100)
      }
      
      for level, (min_val, max_val) in levels.items():
          print(f"Starting {level} level...")
          for _ in range(5):
              question, correct_answer = generate_question(min_val, max_val)
              print(question)
              user_answer = float(input("Your answer: "))
              
              if user_answer == correct_answer:
                  print("Correct! You've earned a point.")
                  score += 1
              else:
                  print(f"Oops! The correct answer was {correct_answer}.")
          
          print(f"End of {level} level. Your current score is {score}.")
      
      print(f"Game over! Your final score is {score}.")
      if score >= 12:
          print("Congratulations! You've earned the 'Math Genius' badge.")
      elif score >= 8:
          print("Great job! You've earned the 'Math Enthusiast' badge.")
      else:
          print("Keep practicing! You've earned the 'Math Learner' badge.")
  ```

**Step 3: Educational Value**

- Clearly define learning objectives for each level.
- Include feedback and reflection opportunities.
- Example:
  ```python
  def main_game():
      welcome_message()
      score = 0
      levels = {
          "Easy": (1, 10),
          "Medium": (10, 50),
          "Hard": (50, 100)
      }
      
      for level, (min_val, max_val) in levels.items():
          print(f"Starting {level} level...")
          print(f"Learning Objective: Practice arithmetic with numbers between {min_val} and {max_val}.")
          
          for _ in range(5):
              question, correct_answer = generate_question(min_val, max_val)
              print(question)
              user_answer = float(input("Your answer: "))
              
              if user_answer == correct_answer:
                  print("Correct! You've earned a point.")
                  score += 1
              else:
                  print(f"Oops! The correct answer was {correct_answer}.")
          
          print(f"End of {level} level. Your current score is {score}.")
      
      print(f"Game over! Your final score is {score}.")
      if score >= 12:
          print("Congratulations! You've earned the 'Math Genius' badge.")
      elif score >= 8:
          print("Great job! You've earned the 'Math Enthusiast' badge.")
      else:
          print("Keep practicing! You've earned the 'Math Learner' badge.")
      
      # Reflection
      print("Reflect on your learning experience. What did you find challenging? What did you enjoy?")
  ```

### Criteria for Success and Evaluation

**Success Criteria:**
- The game should generate appropriate arithmetic questions based on the level.
- The game should provide immediate feedback on answers.
- The game should track points and award badges based on performance.
- The code should be clean, well-documented, and follow best practices.
- The output should be clear and user-friendly.

**Evaluation Rubric:**
- **Accuracy (40%)**: Correct implementation of arithmetic operations and scoring.
- **Engagement (30%)**: Effective use of storytelling and gamification elements.
- **Code Quality (20%)**: Cleanliness, readability, and documentation of code.
- **User Experience (10%)**: Clarity and usability of the game's interface.

---

By completing this assignment, you will apply key concepts from the lecture on designing kid-friendly projects. This practical coding task will help you build skills relevant to creating engaging and educational experiences for kids in EdTech.