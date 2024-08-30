### Module Title: Fundamentals of Python Programming

### Exercise Requirements

1. **Problem Statement**: 
   Create a problem that requires the student to apply "Exercise 5: Define a function that takes two numbers and returns their sum" to a scenario directly related to the content covered in Lecture 5: Lists, Tuples, and Dictionaries: Working with Collections.

   **Scenario**: 
   You are designing an interactive storytelling game for kids where characters can collect items and gain points. Each character has a dictionary storing their attributes, including the points they have collected. You need to write a function that takes two dictionaries representing two different characters and returns the total points collected by both characters.

   **Task**:
   Define a function `total_points` that takes two dictionaries (`character1` and `character2`) as arguments. Each dictionary contains a key `points` with an integer value representing the points collected by the character. The function should return the sum of points from both dictionaries.

   **Example**:
   ```python
   character1 = {'name': 'Alice', 'points': 50}
   character2 = {'name': 'Bob', 'points': 30}
   
   print(total_points(character1, character2))  # Output: 80
   ```

2. **Fill-in-the-Blank Starter Code**:
   ```python
   # Function to calculate total points collected by two characters
   def total_points(character1, character2):
       # Extract points from both characters' dictionaries
       points1 = character1['points']
       points2 = character2['points']
       
       # Calculate the sum of points
       total = _______ + _______
       
       return total

   # Test the function with example values
   character1 = {'name': 'Alice', 'points': 50}
   character2 = {'name': 'Bob', 'points': 30}
   
   print(total_points(character1, character2))  # Expected Output: 80
   ```

3. **Hints**:
   - Remember how to access dictionary values using keys.
   - Recall the syntax for adding two numbers.
   - Ensure that the function returns the correct result by summing the points from both dictionaries.

4. **Expected Outcome**:
   The student should be able to fill in the blanks correctly, demonstrating an understanding of how to access dictionary values and perform basic arithmetic operations. The final solution should adhere to best practices, include error handling, and be well-commented to explain the reasoning behind each step, as emphasized in the lecture.

   **Completed Code**:
   ```python
   # Function to calculate total points collected by two characters
   def total_points(character1, character2):
       # Extract points from both characters' dictionaries
       points1 = character1['points']
       points2 = character2['points']
       
       # Calculate the sum of points
       total = points1 + points2
       
       return total

   # Test the function with example values
   character1 = {'name': 'Alice', 'points': 50}
   character2 = {'name': 'Bob', 'points': 30}
   
   print(total_points(character1, character2))  # Expected Output: 80
   ```

### Integration

- Ensure the exercise content is well-structured, with clear headings and sections for easy parsing and integration into the learning platform. Use markdown for formatting and include any necessary files or resources as links.

---

By completing this exercise, students will apply their knowledge of lists, tuples, and dictionaries in Python to a practical scenario relevant to EdTech. This will help them develop skills in organizing and managing data effectively, which is crucial for creating engaging educational content for kids.