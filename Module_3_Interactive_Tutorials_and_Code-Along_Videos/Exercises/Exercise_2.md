### Module Title: Interactive Tutorials and Code-Along Videos

---

### Exercise Requirements

#### 1. Problem Statement:
Create a problem that requires the student to apply "Exercise 2: Write a script for a code-along video on creating a simple game" to a scenario directly related to the content covered in "Best Practices for Code-Along Videos: Keeping Viewers Engaged."

**Problem Statement:**

You are tasked with creating a code-along video script for a simple game where a character, "Hero," collects coins. The goal is to keep kids aged 8-15 engaged using storytelling and interactive elements. Use the best practices discussed in the lecture to create a compelling narrative and include frequent check-ins and real-time feedback.

---

#### 2. Fill-in-the-Blank Starter Code:

Provide starter code with strategically placed blanks that the student must fill in to complete the functionality. The code should include comments and guidance relevant to storytelling and be appropriate for someone with intermediate experience.

```python
# Introduction of the character
character = "Hero"
print(f"{character} is ready to collect coins!")

# Initialize the number of coins collected
coins_collected = 0

# Function to collect a coin
def collect_coin():
    global coins_collected
    # Increment the coins_collected by 1
    coins_collected += 1
    print(f"Coins collected: {coins_collected}")

# Function to simulate the game
def play_game():
    # Introduce the game and its objective
    print("Welcome to the coin collection game!")
    print("Help Hero collect as many coins as possible.")

    # Collect coins in a loop
    for _ in range(5):
        # Simulate collecting a coin
        collect_coin()

# Call the play_game function to start the game
play_game()
```

---

#### 3. Hints:

1. **Hint 1:** Remember to use storytelling techniques by introducing the character and setting up the game's objective at the beginning.
2. **Hint 2:** Use frequent check-ins by pausing after key steps and asking viewers what they think will happen next.
3. **Hint 3:** Provide real-time feedback by encouraging viewers to run their code and see the immediate results.
4. **Hint 4:** Keep your tone enthusiastic and vary your pitch to maintain interest. Avoid monotonous explanations.
5. **Hint 5:** Ensure clear visuals by highlighting important sections of the code and using annotations if necessary.

---

#### 4. Expected Outcome:

The student should be able to fill in the blanks correctly, demonstrating an understanding of how the concepts apply to real-world scenarios in EdTech. The final solution should adhere to best practices, include error handling, and be well-commented to explain the reasoning behind each step, as emphasized in the lecture.

**Expected Outcome Code:**

```python
# Introduction of the character
character = "Hero"
print(f"{character} is ready to collect coins!")

# Initialize the number of coins collected
coins_collected = 0

# Function to collect a coin
def collect_coin():
    global coins_collected
    # Increment the coins_collected by 1
    coins_collected += 1
    print(f"Coins collected: {coins_collected}")

# Function to simulate the game
def play_game():
    # Introduce the game and its objective
    print("Welcome to the coin collection game!")
    print("Help Hero collect as many coins as possible.")

    # Collect coins in a loop
    for _ in range(5):
        # Simulate collecting a coin
        collect_coin()

# Call the play_game function to start the game
play_game()
```

This script should incorporate storytelling elements by introducing the character and setting up a narrative. It should also include interactive elements like frequent check-ins and real-time feedback, ensuring that young learners remain engaged throughout the code-along video.

---

### Integration

Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

---

**Files/Resources:**
- [Starter Code File](link_to_starter_code_file.py)
- [Lecture Notes on Best Practices for Code-Along Videos](link_to_lecture_notes.pdf)

This exercise aligns with the outlined learning objectives and user profile, focusing on practical application in a context that resonates with your interests and career goals in EdTech.