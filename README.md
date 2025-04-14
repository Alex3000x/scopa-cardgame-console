# Scopa Card Game (Console Version)

A complete, console-based implementation of the traditional Italian card game **Scopa**. This version is built in **Java**, designed to run entirely in the terminal, and serves both as a fully playable game and a foundation for future graphical enhancements.

![Java](https://img.shields.io/badge/Java-17-blue?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Console-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/Status-Playable-brightgreen?style=flat-square)

---

## Table of Contents
* [Scopa Card Game](#scopa-card-game-console-version)
  * [About](#-about)
  * [Features](#-features)  
  * [Technologies Used](#-technologies-used)
  * [How To Run](#-how-to-run)
  * [Repository Structure](#-repository-structure)
  * [Future Plan & Contributions](#-future-plan--contributions)
  * [License](#-license)
  * [Credits](#-credits)

---

## 🌐 About
**Scopa** is a classic Italian card game played with a 40-card deck. The goal is to capture cards from the table by matching their total value with the card played from the hand, scoring points in the following ways:

- Capturing **the most cards**
- Capturing the **most Coins suit cards**
- Capturing the **Settebello** (7 of Coins)
- Having the best **Primiera** (highest-value card per suit)
- Performing a **Scopa** by clearing all cards from the table in one move

The game is played over multiple **rounds**, and it ends when the first player or team achieve a **target score** of 11 or more points. In case of tie, additional rounds are played until there's a winner.

---

## ✨ Features

- Full implementation of **Scopa** game rules and logic
- Play against an AI opponent with decision-making logic
- Turn-based gameplay with menu-based card and capture selection
- Multi-round match system with **customizable winning score**
- End-of-game statistics and round-based point tracking
- Menu-based structure for better navigation in the environment
- Input handling with quit options and confirmation prompts
- Support for rematch and game flow management

---

## ⚡ Technologies Used

- **Java JDK 17**
- **Object-Oriented Programming (OOP)**
- Gradle (optional for build)
- Custom logger and input manager for an enhanced CLI experience
- No external dependencies or framewok required

---

## 🛠 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/scopa-cardgame-console.git
cd scopa-cardgame-console
```

2. Compile and run (manually):
```bash
javac -d out src/main/java/com/alessio/scopa/*.java
java -cp out com.alessio.scopa.Main
```

Alternatively, you can use your favorite IDE (e.g. IntelliJ IDEA, Eclipse, VS Code), just import the folder as a **Java project** or **Gradle project**, then set the main class to `com.alessio.scopa.Main` and press Run to play!

### Requirements
- Java JDK 17 or above
- Command-line environment (Windows Terminal, macOS Terminal, Linux Bash)

---

## 📚 Repository Structure

```txt
com.alessio.scopa
├──enums
│  ├── EarnedBy.java
│  └── PointType.java
├── Card.java
├── Deck.java
├── NeapolitanDeck.java
├── GameController.java
├── GameState.java
├── GameLogger.java
├── GameStatistics.java
├── InputManager.java
└── Main.java
```

---

## 🔄 Future Plan & Contributions

Every **community contributions** are welcome!  
If you'd like to suggest improvements, fix bugs, or implement new features, feel free to open a **Pull Request**.

Here are some **example enhancements** planned for the future:

- **Graphical User Interface** (in another branch/repo)
- Save/load match status and progress
- View match history & statistics
- Multiplayer support (local or online)
- Enhanced AI difficulty levels
- Challenges or achievements system

---

## 📜 License
This project is open-source and free to use. All code is distributed under the [MIT License](./LICENSE).

---

## 🌟 Credits
Developed with passion by [@Alex3000x](https://github.com/Alex3000x) for educational and demonstrative purposes.

---

Enjoy the game and spread the joy of traditional Italian Scopa! 🃏🇮🇹
