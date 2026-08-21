🎯 Guess My Number

A browser-based number guessing game built with vanilla HTML, CSS, and JavaScript — no frameworks, no libraries, just core web fundamentals.

🔗 Live Demo: https://arijeet333.github.io/guess-my-number/

📋 About

The computer picks a secret number between 1 and 20. The player has to guess it, getting "too high" or "too low" hints after each try. Every wrong guess costs a point off the starting score of 20. Guess correctly before the score hits zero, and the game keeps track of your best (highest) score across rounds.

✨ Features
Random secret number generated on every load and every reset
Real-time feedback messages (too high / too low / correct / no input)
Live score tracking that decreases with each wrong guess
Persistent highscore tracking within a session
Visual feedback: background color and number box size change on a win
"Again!" button to reset and start a new round instantly
Fully responsive layout for mobile and desktop
🛠️ Built With
HTML5 – page structure
CSS3 – styling, layout, and responsive design
JavaScript (ES6) – game logic and DOM manipulation
🧠 How It Works
Math.random() generates a secret number between 1 and 20 on page load.
The player types a guess and clicks Check!.
JavaScript compares the guess to the secret number and updates the DOM:
Empty input → shows a warning message
Correct guess → reveals the number, updates the background, and updates the highscore if the current score beats it
Wrong guess → shows "too high" or "too low" and decreases the score by 1
Score reaching 0 without a correct guess ends the round with a loss message.
Clicking Again! resets the score, generates a new secret number, and restores the original UI state.
📂 Project Structure
guess-my-number/
├── index.html   # Page structure and DOM elements
├── style.css    # Styling and layout
└── script.js    # Game logic
🚀 Running It Locally
Clone the repo:
   git clone https://github.com/Arijeet333/guess-my-number.git
Open index.html in any browser. That's it — no build step, no dependencies.
📌 What This Project Demonstrates
DOM selection and manipulation (querySelector, textContent, style)
Event handling (addEventListener for clicks)
Conditional logic and state management in vanilla JS
Basic responsive CSS with media queries
Structuring and deploying a static site with GitHub Pages
👤 Author

Arijeet Kundu GitHub: @Arijeet333
