# Quiz Console App

A **Quiz Console App** built using Java, showcasing core Object-Oriented Programming (OOP) principles such as classes, objects, encapsulation, and the use of getters and setters. This app allows users to take a quiz with multiple questions, provides instant feedback, and displays the final score.

## Features

- **Encapsulation**: Ensures that quiz data is secure using private fields and provides controlled access using getters and setters.
- **Classes and Objects**: Designed with classes such as `Question`, `Quiz`, and `Main` to represent different components of the application.
- **Simple Console Interface**: Users interact with the app via a command-line interface.
- Supports multiple-choice questions.

## OOP Concepts Used

1. **Classes**:  
   - `Question`: Represents a single quiz question with options and the correct answer.
   - `Quiz`: Manages a list of questions and user interactions.
   - `Main`: Acts as the entry point to the application.

2. **Objects**:  
   - Instances of the `Question` class represent individual questions.
   - The `Quiz` class object handles the overall quiz logic.

3. **Encapsulation**:  
   - All fields in the `Question` class are private and accessed through public getters and setters.

4. **Getters and Setters**:  
   - Used to set and retrieve question details like the question text, options, and correct answer.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/quiz-console-app.git
   cd quiz-console-app
