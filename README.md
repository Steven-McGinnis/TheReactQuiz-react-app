# React Quiz App 📝

React Quiz App is a React application that allows users to take quizzes on various topics. It uses a local JSON server to fetch quiz questions and displays them in an interactive format. This app specifically uses both functional and class components to manage state and interactions, providing hands-on experience with different React paradigms.

## 📖 About This Project

React Quiz App is a feature-rich quiz application that interacts with a local JSON server to fetch quiz questions. It allows users to:

- Take quizzes on various topics
- View current question and options
- Track progress and score
- See the final score and highscore

This project helped reinforce foundational and intermediate React concepts through practical application.

## ✨ Features

- **Take Quizzes:** Fetch quiz questions from a local JSON server and display them interactively.
- **Current Question and Options:** View the current question and select an answer from the provided options.
- **Track Progress and Score:** Track the current question number, total questions, and current score.
- **Final Score and Highscore:** Display the final score and highscore at the end of the quiz.

## 🎓 Concepts Practiced

While developing React Quiz App, I gained hands-on experience with:

- Custom hooks for data fetching and API integration.
- Component hierarchy and reusability.
- State management with useState and useReducer.
- Conditional rendering and error handling.
- Enhancing UX with loading indicators and error messages.
- Using both functional and class components.
- Persisting state with localStorage.

## 🛠️ How to Run

To run the app locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-quiz-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-quiz-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The app will be accessible at [http://localhost:3000](http://localhost:3000).

## 🧩 Components

- **App.js:** Main application component managing state, interactions, and layout.
- **Question.js:** Displays the current question and options.
- **Options.js:** Displays the answer options for the current question.
- **Progress.js:** Tracks and displays the current progress and score.
- **Timer.js:** Manages and displays the countdown timer for each question.
- **FinishedScreen.js:** Displays the final score and highscore at the end of the quiz.
- **NextButton.js:** Button to proceed to the next question or finish the quiz.
- **Footer.js:** Footer component for additional controls and information.

## 🚀 Future Improvements

While the current version is fully functional, potential enhancements include:

- Adding persistent data storage with localStorage or an API backend.
- Implementing advanced quiz features like timed quizzes and difficulty levels.
- Upgrading styling with Tailwind CSS for a modern design.

## 🙏 Acknowledgments

A big thank you to Jonas Schmedtmann for designing an engaging and practical React course that bridges foundational learning with real-world applications.
