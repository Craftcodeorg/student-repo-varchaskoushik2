### Module Title: Project-Based Learning for Kids ###

### Exercise 4: Create a Math Tutoring Project that Helps Kids Practice Arithmetic Skills ###

#### Problem Statement:
You are tasked with creating an engaging math tutoring game that helps kids aged 8-15 practice their arithmetic skills. Using the concepts discussed in Lecture 4, design a game that integrates storytelling and coding to teach basic arithmetic operations (addition, subtraction, multiplication, and division). The game should be built using Scratch and should incorporate elements that keep kids motivated and engaged.

#### Learning Objectives:
By the end of this exercise, you will:
- Apply game development techniques to create an educational math game.
- Integrate storytelling to make the learning experience immersive.
- Utilize Scratch to develop a project that teaches arithmetic skills.

#### Core Requirements:
1. **Game Concept**: Design a game where the player is a character on a quest to solve arithmetic problems to progress through different levels.
2. **Story Integration**: Incorporate a storyline where each level represents a new challenge or adventure that requires solving math problems.
3. **Educational Goals**: Ensure the game teaches basic arithmetic operations and provides immediate feedback on the player's answers.
4. **Engagement Elements**: Include rewards, such as points or virtual items, to motivate players.

#### Practical Application:
**Example Game: Math Quest Adventure in Scratch**

1. **Objective**: Teach basic arithmetic operations through a quest-based game.
2. **Storyline**: The player is a young adventurer who must solve math problems to unlock treasures and advance through different lands.

#### Fill-in-the-Blank Starter Code:
Here is some starter code for your Scratch project. Fill in the blanks to complete the functionality.

```scratch
# Create a new sprite for the player character
when green flag clicked
    # Initialize the game
    set [score v] to [0]
    say [Welcome to Math Quest Adventure!] for (2) seconds
    # Start the first level
    broadcast [start level 1 v]

# Define the first level
when I receive [start level 1 v]
    say [Solve this problem to find the hidden treasure!] for (2) seconds
    set [problem v] to [pick random (1) to (10)] + [pick random (1) to (10)]
    ask (join [What is ] (problem)) and wait
    if <(answer) = (problem)> then
        say [Correct! You found the treasure!] for (2) seconds
        change [score v] by (10)
        broadcast [start level 2 v]
    else
        say [Oops! Try again.] for (2) seconds
        broadcast [start level 1 v]

# Define the second level
when I receive [start level 2 v]
    say [Solve this problem to unlock the magic door!] for (2) seconds
    set [problem v] to [pick random (1) to (10)] * [pick random (1) to (10)]
    ask (join [What is ] (problem)) and wait
    if <(answer) = (problem)> then
        say [Great job! The door is open!] for (2) seconds
        change [score v] by (20)
        broadcast [start level 3 v]
    else
        say [Oops! Try again.] for (2) seconds
        broadcast [start level 2 v]
```

#### Hints:
1. **Story Integration**: Think about how you can make each level of your game part of an ongoing story. For example, each math problem could be a riddle that unlocks a new part of the adventure.
2. **Feedback Mechanism**: Ensure your game provides immediate feedback on whether the player's answer is correct or incorrect.
3. **Engagement**: Use rewards like points, badges, or virtual items to keep players motivated.

#### Expected Outcome:
By completing this exercise, you should have a fully functional math tutoring game in Scratch that teaches basic arithmetic skills through an engaging storyline. Your game should:
- Provide clear and immediate feedback on answers.
- Include multiple levels with increasing difficulty.
- Use storytelling elements to make the learning experience immersive and fun.

#### Integration:
Ensure your exercise content is well-structured with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

```markdown
### Math Quest Adventure in Scratch

#### Problem Statement:
Design an engaging math tutoring game using Scratch that helps kids practice arithmetic skills through storytelling and coding.

#### Learning Objectives:
- Apply game development techniques.
- Integrate storytelling into educational games.
- Utilize Scratch for creating interactive learning experiences.

#### Core Requirements:
1. **Game Concept**
2. **Story Integration**
3. **Educational Goals**
4. **Engagement Elements**

#### Practical Application:
**Example Game: Math Quest Adventure in Scratch**

#### Fill-in-the-Blank Starter Code:
```scratch
# Create a new sprite for the player character
when green flag clicked
    # Initialize the game
    set [score v] to [0]
    say [Welcome to Math Quest Adventure!] for (2) seconds
    # Start the first level
    broadcast [start level 1 v]

# Define the first level
when I receive [start level 1 v]
    say [Solve this problem to find the hidden treasure!] for (2) seconds
    set [problem v] to [pick random (1) to (10)] + [pick random (1) to (10)]
    ask (join [What is ] (problem)) and wait
    if <(answer) = (problem)> then
        say [Correct! You found the treasure!] for (2) seconds
        change [score v] by (10)
        broadcast [start level 2 v]
    else
        say [Oops! Try again.] for (2) seconds
        broadcast [start level 1 v]

# Define the second level
when I receive [start level 2 v]
    say [Solve this problem to unlock the magic door!] for (2) seconds
    set [problem v] to [pick random (1) to (10)] * [pick random (1) to (10)]
    ask (join [What is ] (problem)) and wait
    if <(answer) = (problem)> then
        say [Great job! The door is open!] for (2) seconds
        change [score v] by (20)
        broadcast [start level 3 v]
    else
        say [Oops! Try again.] for (2) seconds
        broadcast [start level 2 v]
```

#### Hints:
1. **Story Integration**
2. **Feedback Mechanism**
3. **Engagement**

#### Expected Outcome:
A fully functional math tutoring game in Scratch that teaches arithmetic skills through an engaging storyline.
```