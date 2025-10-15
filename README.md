# Math-Puzzle
Of course! Here is a README.md file for the math puzzle program.

-----
# **Math Puzzle** 

**Math Puzzle** is a responsive, feature-rich, and self-contained web-based math game designed to challenge and entertain users of all skill levels. Built with vanilla HTML, CSS, and JavaScript, it offers a complete gaming experience with user authentication, multiple game modes, difficulty levels, and score tracking, all within a single file.

-----
## **✨ Features**

- **Complete User System**:
  - **User Authentication**: Secure-feeling login and registration system.
  - **Guest Mode**: Play anonymously without creating an account.
  - **Local Storage Backend**: All user data, history, and scores are saved in the browser's local storage for persistence.
- **Dynamic Gameplay**:
  - **Five Game Modes**: Choose from Addition (), Subtraction (), Multiplication (), Division (), or a Mixed mode.
  - **Four Difficulty Levels**: Ranging from **Easy** to **Extreme**, affecting number complexity and timer duration.
  - **Training Mode**: Practice any puzzle type and difficulty without the pressure of scores, lives, or a timer.
- **Engaging User Interface**:
  - **Responsive Design**: A clean, modern UI that adapts seamlessly to desktop, tablet, and mobile screens.
  - **Dual Themes**: Switch between a sleek **Light Mode** and a cool **Dark Mode**.
  - **Dynamic Animations**: Smooth screen transitions, button effects, and confetti for correct answers provide a polished user experience.
- **Score & Profile Management**:
  - **High Score Tracking**: The game saves your personal best score for each game mode and difficulty combination.
  - **User Profile Page**: View your account details and a history of your 10 most recent games.
-----
## **🚀 How to Run**

Since this is a self-contained vanilla JS project, no build steps or servers are required.

1. **Download the File**: Save the MATH PUZZLE.html file to your local machine.
1. **Open in Browser**: Right-click the file and open it with any modern web browser (like Chrome, Firefox, or Edge).
1. **Play!** 🎮
-----
## **💻 Technical Stack**

This project is built from the ground up using fundamental web technologies, with no external libraries or frameworks.

- **HTML5**: Provides the core structure and semantic layout for all game screens.
- **CSS3**:
  - Uses **Flexbox** and **Grid** for modern, responsive layouts.
  - Employs **CSS Custom Properties (Variables)** for easy theming (Light/Dark mode) and maintenance.
  - Includes **Keyframe Animations** for interactive UI effects.
- **JavaScript (ES6+)**:
  - Powers all game logic, including question generation, state management, and user interaction.
  - Handles the mock authentication system and interacts with the browser's localStorage API for data persistence.
-----
## **📂 Code Structure**

The entire application is contained within a single .html file, with clear separation of concerns.

1. **HTML Structure**: The <body> contains individual div elements that act as "screens" (e.g., #auth-login-screen, #game-screen). JavaScript controls which screen is visible at any time by toggling a .hidden class.
1. **CSS Styling**: An embedded <style> block in the <head> contains all the styling. It is organized into logical sections for clarity:
   1. CSS Variables (Theme Management)
   1. Base Styles & Animations
   1. Component-specific styles (Header, Buttons, Game Screen, etc.)
1. **JavaScript Logic**: An embedded <script> block at the end of the <body> handles all functionality. The script is organized into the following sections:
   1. **Authentication & Storage**: Manages the mock user database, login/registration logic, and guest sessions using localStorage.
   1. **Game State & Configuration**: Global objects that track the current game's settings (gameConfig) and state (gameState).
   1. **High Score & History Logic**: Functions for saving and retrieving user scores and game history.
   1. **Game Flow Functions**: Core logic for startGame(), generateQuestion(), checkAnswer(), and endGame().
   1. **Render & Display Functions**: UI-focused functions like showScreen() and updateDisplay() that manipulate the DOM.
   1. **Initialization & Event Listeners**: Sets up all the event handlers for buttons and user actions when the DOM is loaded.
-----
## **🧑‍💻 Authors**

This application was created as a final year project by:

- **Dinesh V**
- **Sanjaykumar K**
- **Vasanth M**
