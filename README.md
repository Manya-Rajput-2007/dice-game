# 🎲 Dice Game

A simple and interactive two-player dice game built using HTML, CSS, and JavaScript.

The game randomly rolls two dice representing Player 1 and Player 2. Based on the dice results, the application determines the winner or declares a draw.

---

## 📌 About the Project

Dice Game is a beginner-friendly web development project designed to practice JavaScript fundamentals and interactive frontend development.

Each time the page is refreshed, two dice are randomly generated for the players. The player with the higher dice value wins the round.

This project demonstrates how JavaScript can be used to manipulate HTML elements dynamically and create engaging browser-based applications.

---

## 🎯 Objectives

The main objectives of this project are:

* Practice JavaScript programming fundamentals.
* Understand random number generation.
* Learn DOM manipulation.
* Work with images dynamically.
* Build an interactive web application.
* Understand the connection between HTML, CSS, and JavaScript.

---

## ✨ Features

* Two-player dice game.
* Random dice roll generation.
* Dynamic dice image updates.
* Automatic winner determination.
* Draw detection when both players roll the same number.
* Simple and responsive user interface.

---

## 🎮 How to Play

1. Open the Dice Game in your browser.
2. Refresh the page to roll the dice.
3. Player 1 and Player 2 receive random dice values.
4. The player with the higher number wins.
5. If both dice show the same number, the result is a draw.

---

## 🛠️ Technologies Used

* **HTML5** — Structure of the web page.
* **CSS3** — Styling and layout.
* **JavaScript** — Random dice generation, DOM manipulation, and game logic.

---

## 📂 Project Structure

```text
dice-game/
│
├── dice1.png
├── dice2.png
├── dice3.png
├── dice4.png
├── dice5.png
├── dice6.png
│
├── dicee.html
│   └── Main HTML file
│
├── javadice.js
│   └── JavaScript game logic
│
├── styles.css
│   └── Styling and layout
│
└── README.md
```

---

## ⚙️ How It Works

### 1. Random Number Generation

JavaScript generates random numbers between 1 and 6, representing the possible outcomes of a standard dice.

```javascript
Math.floor(Math.random() * 6) + 1;
```

### 2. Dynamic Image Update

The corresponding dice image is selected based on the generated random number.

For example:

* Random number `1` → `dice1.png`
* Random number `6` → `dice6.png`

### 3. Winner Determination

The application compares both dice values:

* Player 1 wins if their dice value is higher.
* Player 2 wins if their dice value is higher.
* A draw occurs when both values are equal.

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Manya-Rajput-2007/dice-game.git
```

### Navigate to the Project Directory

```bash
cd dice-game
```

### Run the Application

Open the `dicee.html` file in any modern web browser.

No additional installation or dependencies are required.

---

## 📸 Demo

Add a screenshot or GIF of the game here to showcase the interface.

Example:

```markdown
![Dice Game Preview](dice1.png)
```

For a better portfolio presentation, consider deploying this project using GitHub Pages and adding the live demo link here.

---

## 🔮 Future Improvements

Possible enhancements for this project include:

* Add a Roll Dice button instead of requiring a page refresh.
* Add player score tracking.
* Create multiple rounds.
* Add animations when rolling dice.
* Add sound effects.
* Introduce a restart game button.
* Improve mobile responsiveness.
* Add a scoreboard and game history.

---

## 📚 Learning Outcomes

Through this project, I strengthened my understanding of:

* JavaScript random number generation.
* DOM manipulation.
* Conditional statements.
* Event handling.
* Dynamic image rendering.
* Frontend project organization.
* Basic Git and GitHub workflow.

---

## 👩‍💻 Author

**Manya Rajput**

B.Tech Computer Science Engineering Student | AIML & Software Development Enthusiast

Interested in Python, Artificial Intelligence, Machine Learning, Full-Stack Development, and Problem Solving.

### Connect With Me

* GitHub: [Manya Rajput](https://github.com/Manya-Rajput-2007)
* LinkedIn: [Manya Rajput](https://linkedin.com/in/manya-rajput-2a281b33)

---

## ⭐ Support the Project

If you found this project useful for learning web development, feel free to explore and star the repository!

Happy Coding! 🚀
