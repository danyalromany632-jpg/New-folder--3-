# NUMERA — Mental Math Game

A fast-paced mental math game built with **HTML, CSS, and JavaScript**.

NUMERA is designed to make simple arithmetic more challenging and engaging by combining quick calculations, a countdown timer, scoring, and combo rewards in a clean modern interface.

## Features

* Three difficulty levels:

  * Easy
  * Medium
  * Hard
* 10 questions per challenge
* Countdown timer for every question
* Dynamic scoring system
* Combo multiplier for consecutive correct answers
* Instant feedback after each answer
* Accuracy calculation
* Best score saved automatically using `localStorage`
* Responsive design for desktop and mobile
* Smooth animations and visual feedback
* No external JavaScript libraries required

## Operations

Depending on the selected difficulty, the game generates:

* Addition
* Subtraction
* Multiplication
* Division

Division questions are generated with whole-number answers to keep the gameplay focused on mental calculation.

## How to Play

1. Open the game.
2. Choose a difficulty level.
3. Click **Start Challenge**.
4. Solve each calculation before the timer reaches zero.
5. Enter your answer and press `Enter` or the submit button.
6. Try to build the highest possible combo.
7. Finish all 10 questions and check your final score.

## Scoring

Your score depends on:

* Correct answers
* Remaining time
* Current combo
* Difficulty level

Answering quickly and maintaining a combo will help you achieve a higher score.

## High Score

Your highest score is stored locally in your browser using:

```text
localStorage
```

This means your best score remains available when you return to the game on the same browser.

## Built With

* HTML5
* CSS3
* Vanilla JavaScript
* LocalStorage API

No frameworks or heavy dependencies are required.

## Project Structure

The entire game is contained in a single file:

```text
NUMERA/
└── index.html
```

The HTML, CSS, and JavaScript are all included inside `index.html`.

## Run Locally

No installation is required.

Simply download or clone the repository and open:

```text
index.html
```

in any modern web browser.

## GitHub Pages

The project can be hosted directly using GitHub Pages.

Make sure the main file is named:

```text
index.html
```

and is located in the root of the repository.

Then enable GitHub Pages from:

```text
Settings → Pages
```

Choose the `main` branch and `/ (root)` as the deployment folder.

## Browser Support

NUMERA works with modern browsers including:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## Future Improvements

Some ideas that could be added later:

* Sound effects
* More game modes
* Custom number ranges
* Daily challenges
* Global leaderboard
* Player statistics
* Keyboard shortcuts
* More advanced mathematical operations

## License

This project is available for personal and educational use.

---

**NUMERA**

*Think fast. Calculate faster.*
