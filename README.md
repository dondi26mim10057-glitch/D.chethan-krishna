# 🎲 Snake and Ladder Game

## 📌 Project Description

This is a simple **Snake and Ladder Game** developed using **Python**.

The game is designed for **two players**. Each player takes turns rolling a dice and moving their position on the board. If a player lands on a ladder, they move upward. If they land on a snake, they move downward.

The first player to reach **100** wins the game.

---

## 🎯 Features

* 👥 Two-player game
* 🎲 Random dice rolling
* 🪜 Ladders increase the player's position
* 🐍 Snakes decrease the player's position
* 🔢 Exact number is required to reach 100
* 🔄 Option to play the game again
* 🏆 Displays the winner
* 📍 Displays the current position of both players

---

## 🛠️ Technologies Used

* **Python**
* `random` module

---

## 📚 Python Concepts Used

This project uses the following Python concepts:

* Variables
* Input and Output
* Dictionaries
* Functions
* Function parameters
* Return statements
* `if`, `elif`, and `else`
* `while` loops
* `break` statement
* `in` operator
* String methods
* Random number generation
* Game logic

---

## 🎮 How to Play

1. Run the Python program.
2. Enter the name of Player 1.
3. Enter the name of Player 2.
4. Press **Enter** to roll the dice.
5. Move according to the dice number.
6. If you land on a ladder, climb up.
7. If you land on a snake, move down.
8. Continue taking turns.
9. The first player to reach **100** wins.
10. Choose whether to play again.

---

## 🐍 Snakes

| Starting Position | Ending Position |
| ----------------: | --------------: |
|                99 |              54 |
|                87 |              36 |
|                64 |              25 |
|                48 |              10 |
|                32 |               8 |

---

## 🪜 Ladders

| Starting Position | Ending Position |
| ----------------: | --------------: |
|                 4 |              25 |
|                13 |              46 |
|                27 |              56 |
|                42 |              75 |
|                58 |              89 |

---

## 💻 Example

```text
================================
       SNAKE AND LADDER
================================

Enter Player 1 name: Rahul
Enter Player 2 name: Sidhu

Game starts!
First player to reach 100 wins.

Rahul 's turn
Press Enter to roll the dice...

You rolled: 4

You found a ladder!
You climbed to: 25

Rahul position: 25
```

---

## 🏆 Winning Condition

A player wins when their position becomes exactly **100**.

```python
if position1 == 100:
    print(name1, "WINS!")
```

If the dice number would take the player beyond 100, the player does not move.

---

## 🔄 Replay Option

After the game ends, the program asks:

```text
Do you want to play again?
Enter yes or no:
```

The player can start a new game by entering `yes`.

---

## 👨‍💻 Project Purpose

The purpose of this project is to practice Python programming concepts by creating an interactive game.

This project helped in understanding how **functions, loops, dictionaries, conditional statements, user input, and random numbers** can be combined to create a complete Python application.

---

## 🚀 Future Improvements

Some possible improvements are:

* Add a graphical user interface (GUI)
* Add a visual Snake and Ladder board
* Add sound effects
* Add more players
* Add player statistics
* Add a computer/AI opponent
* Add a scoreboard

---

## 📄 License

This project is created for **educational and learning purposes**.
