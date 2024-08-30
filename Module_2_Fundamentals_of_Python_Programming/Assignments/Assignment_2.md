### Assignment: Creating a Python Program to Manage Favorite Books

#### Problem Statement:
In this assignment, you will create a Python program that asks the user for their favorite books, stores them in a list, and then prints the list. This task will help you apply the basic syntax and structure concepts covered in the lecture, particularly focusing on user input, lists, and basic output. This practical coding scenario is relevant to EdTech as it demonstrates how to collect and manage data interactively, which is a fundamental skill in educational software development.

#### Starter Code:
Below is the starter code for your assignment. You will need to expand upon this code to complete the task.

```python
# Starter code for managing favorite books

def main():
    # Step 1: Create an empty list to store favorite books
    favorite_books = []

    # Step 2: Ask the user how many books they want to enter
    num_books = int(input("How many favorite books would you like to enter? "))

    # Step 3: Use a loop to collect book titles from the user
    for _ in range(num_books):
        book = input("Enter the title of a favorite book: ")
        # Add the book to the list
        favorite_books.append(book)

    # Step 4: Print the list of favorite books
    print("\nYour favorite books are:")
    for book in favorite_books:
        print(book)

# Run the main function
if __name__ == "__main__":
    main()
```

#### Detailed Instructions:
Follow these steps to complete the assignment:

1. **Create an Empty List:**
   - Initialize an empty list called `favorite_books` to store the titles of the user's favorite books.

2. **Ask for Number of Books:**
   - Use the `input()` function to ask the user how many favorite books they would like to enter. Convert this input to an integer and store it in a variable called `num_books`.

3. **Collect Book Titles:**
   - Use a `for` loop to iterate `num_books` times.
   - Inside the loop, use `input()` to ask the user for the title of a favorite book.
   - Append each book title to the `favorite_books` list.

4. **Print the List of Favorite Books:**
   - After collecting all the book titles, print a message indicating that you will display the user's favorite books.
   - Use another `for` loop to iterate through the `favorite_books` list and print each book title.

#### Criteria for Success and Evaluation:
Your assignment will be evaluated based on the following criteria:

1. **Functionality (50%):**
   - The program correctly collects and stores the user's favorite books in a list.
   - The program accurately prints the list of favorite books.

2. **Code Quality (30%):**
   - The code is clean, well-documented, and follows Python best practices.
   - Proper use of comments to explain each part of the code.

3. **User Interaction (20%):**
   - The program interacts with the user in a clear and friendly manner.
   - The input prompts and output messages are informative and easy to understand.

By completing this assignment, you will reinforce your understanding of Python's basic syntax and structure, particularly focusing on user input, lists, and loops. This practical exercise is designed to help you create engaging and interactive educational content for kids, aligning with your career goals in EdTech.

Stay curious and keep coding!