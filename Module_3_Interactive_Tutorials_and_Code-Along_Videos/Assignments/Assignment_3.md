### Assignment 3: Design an Interactive Quiz to Assess Understanding of Functions in Python

#### Problem Statement:
Your task is to design an interactive quiz that assesses learners' understanding of functions in Python. This quiz should be engaging, fun, and educational, tailored for kids aged 8-15. The quiz will be story-driven, incorporating characters and plots to make the learning process more captivating. By completing this assignment, you will apply key concepts from the lecture on creating interactive content, such as storytelling, gamification, and hands-on practice.

#### Starter Code:
Below is the starter code framework for the interactive quiz. You will expand upon this code to create a fully functional quiz.

```python
# Starter code for the interactive quiz

# Define a function to ask a question
def ask_question(question, options, correct_answer):
    print(question)
    for i, option in enumerate(options):
        print(f"{i + 1}. {option}")
    
    answer = int(input("Choose the correct option (1/2/3/4): "))
    if options[answer - 1] == correct_answer:
        print("Correct!")
        return True
    else:
        print("Incorrect. The correct answer is:", correct_answer)
        return False

# Define a function to run the quiz
def run_quiz():
    score = 0
    
    # Question 1
    question1 = "What is the correct syntax to define a function in Python?"
    options1 = ["function myFunction():", "def myFunction():", "create myFunction():", "function: myFunction()"]
    correct_answer1 = "def myFunction():"
    if ask_question(question1, options1, correct_answer1):
        score += 1
    
    # Question 2
    question2 = "How do you call a function named 'myFunction'?"
    options2 = ["call myFunction()", "execute myFunction()", "myFunction()", "run myFunction()"]
    correct_answer2 = "myFunction()"
    if ask_question(question2, options2, correct_answer2):
        score += 1
    
    # Add more questions as needed
    
    print(f"Your final score is: {score}")

# Run the quiz
run_quiz()
```

#### Detailed Instructions:
1. **Story Integration**:
   - Create a narrative around the quiz. For example, a character named Alex needs to answer coding questions to unlock treasures or escape from a maze guarded by a dragon.
   - Modify the `ask_question` function to include story elements. For example, after each question, provide a brief narrative update based on whether the answer was correct or incorrect.

2. **Interactive Elements**:
   - Enhance the `ask_question` function to provide immediate feedback and explanations for both correct and incorrect answers.
   - Introduce gamification elements such as points, badges, and levels. For instance, award points for each correct answer and display a badge when certain milestones are reached.

3. **Visual and Audio Aids**:
   - Use ASCII art or simple text-based graphics to make the quiz visually appealing. For example, display a treasure chest or a dragon using ASCII art.
   - Optionally, integrate sound effects using Python libraries like `pygame` to make the quiz more engaging.

4. **Hands-On Practice**:
   - Encourage learners to modify the quiz by adding their own questions and story elements.
   - Provide instructions on how to customize the quiz, such as changing the characters or adding new levels.

#### Criteria for Success and Evaluation:
- **Engagement**: The quiz should be engaging and fun for kids aged 8-15.
- **Storytelling**: Effectively incorporate storytelling elements to make the quiz captivating.
- **Interactivity**: Include interactive elements such as immediate feedback and gamification.
- **Code Quality**: Ensure the code is clean, well-documented, and follows best practices.
- **User Experience**: The output should be formatted in a clear and user-friendly manner.

#### Example Steps:
1. **Step 1**: Modify the `ask_question` function to include narrative updates based on the answer.
   ```python
   def ask_question(question, options, correct_answer):
       print(question)
       for i, option in enumerate(options):
           print(f"{i + 1}. {option}")
       
       answer = int(input("Choose the correct option (1/2/3/4): "))
       if options[answer - 1] == correct_answer:
           print("Correct! Alex moves closer to the treasure.")
           return True
       else:
           print("Incorrect. The correct answer is:", correct_answer)
           print("Alex encounters a challenge but continues on.")
           return False
   ```

2. **Step 2**: Introduce gamification elements such as points and badges.
   ```python
   def run_quiz():
       score = 0
       badges = []
       
       # Question 1
       question1 = "What is the correct syntax to define a function in Python?"
       options1 = ["function myFunction():", "def myFunction():", "create myFunction():", "function: myFunction()"]
       correct_answer1 = "def myFunction():"
       if ask_question(question1, options1, correct_answer1):
           score += 10
       
       # Question 2
       question2 = "How do you call a function named 'myFunction'?"
       options2 = ["call myFunction()", "execute myFunction()", "myFunction()", "run myFunction()"]
       correct_answer2 = "myFunction()"
       if ask_question(question2, options2, correct_answer2):
           score += 10
       
       # Award badge for achieving certain score
       if score >= 20:
           badges.append("Python Novice")
       
       print(f"Your final score is: {score}")
       print(f"Badges earned: {', '.join(badges)}")
   ```

By completing this assignment, you will practice creating interactive and engaging educational content tailored for kids. This will help you build a portfolio of fun and educational coding projects that you can teach to kids aged 8-15.