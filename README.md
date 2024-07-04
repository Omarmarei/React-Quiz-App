# ReactQuiz App

The ReactQuiz app allows users to participate in a quiz, answering questions and receiving feedback on their performance.

## Technologies Used
- React
- JavaScript

## Hooks Used
- `useState`
- `useCallback`
- `useEffect`
- `useRef`

## Components

### App
The main component rendering the application with a header and the quiz.

### Quiz
Manages the quiz state, displays questions, handles user answers, and shows a summary upon completion.

### Question
Displays a single question, manages user answers, and handles timeouts for answering.

### Answers
Displays shuffled answer options for each question, handles user selection, and visualizes answer correctness.

### QuestionTimer
Counts down the time available for each question and triggers actions upon timeout.

### Header
Displays the logo and title of the quiz.

### Summary
Shows quiz completion statistics, including skipped, correct, and incorrect answers.

## Features
- Sequential display of questions with shuffled answer choices.
- Timer for each question, automatically submitting unanswered questions.
- Summary of quiz results with percentages of correct, incorrect, and skipped answers.

## Developer
- Developed by Omar Marei in 2024 as a practice project for Udemy. Please note that this project includes a starter package from Udemy [React: The Complete Guide (incl Hooks, React Router, Redux)](https://www.udemy.com/course/react-the-complete-guide-incl-redux).
