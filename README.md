# Quiz Console App

A simple **Java-based Quiz Console Application** that allows users to answer multiple-choice questions and calculates their score. The project demonstrates core **Object-Oriented Programming (OOP)** concepts such as **classes**, **objects**, **encapsulation**, and **getters/setters**.

## Features

- Interactive quiz with multiple-choice questions.
- Instant feedback on user responses.
- Encapsulated question properties using private fields and public getters and setters.
- Displays the final score after completing the quiz.

## OOP Concepts Used

1. **Classes**: 
   - `Question`: Represents individual quiz questions, options, and the correct answer.
   - `QuestionService`: Handles the quiz logic, including displaying questions and calculating scores.
   - `Main`: Acts as the entry point for the application.

2. **Encapsulation**:  
   - The `Question` class encapsulates fields such as `id`, `question`, `options`, and `answer` using private access modifiers.
   - Getters and setters provide controlled access to these fields.

3. **Objects**:  
   - Instances of the `Question` class represent the quiz questions.
   - `QuestionService` manages the quiz functionality.

4. **toString Method**:
   - Provides a formatted representation of the `Question` object.

## Project Structure

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/quiz-console-app.git
   cd quiz-console-app 

