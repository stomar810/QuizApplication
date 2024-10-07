# QuizApplication
The application presents a series of multiple-choice questions to the user, collects their answers, and provides a score at the end. All questions and answers are hard-coded into the application.

Key Features
Question Storage: Questions and their corresponding answers can be stored in arrays or lists.
User Interface: The application can run in the console, displaying questions and prompting the user for input.
Scoring System: After answering all questions, the application calculates the total score based on correct answers.
Feedback: At the end of the quiz, the application displays the user's score and possibly some feedback.

Components
Question Class: Represents a question with its text, possible answers, and the correct answer.
Quiz Class: Manages the quiz flow, including displaying questions, collecting user input, and calculating the score.
Main Class: The entry point of the application that initializes the quiz and starts the interaction.

How It Works
Initialization: The main method creates an array of Question objects with their text and answers.
Quiz Logic: The Quiz class handles the display of questions and collects user input. It compares user answers against the correct answer index and keeps track of the score.
Output: At the end, the total score is displayed to the user.
Potential Enhancements
Add more questions or categories.
Implement a timer for each question.
Include user-friendly error handling for input.
Allow for different types of questions (true/false, fill-in-the-blank).
This simple structure serves as a foundation, which can be expanded for more complexity and functionality.
