````markdown
# 🎮 Java Console Tic-Tac-Toe Game

A simple and interactive 3x3 **Tic-Tac-Toe** game built using **Java**. This game runs in the console and allows two players to take turns placing their marks (X or O) on a 3x3 board. The game continues until one player wins or the match ends in a draw.

---

## 📌 Table of Contents

- [Features](#-features)
- [How to Run](#-how-to-run)
- [Gameplay Instructions](#-gameplay-instructions)
- [Technologies Used](#-technologies-used)
- [Sample Output](#-sample-output)
- [License](#-license)
- [Author](#-author)

---

## 💡 Features

- 2-player gameplay on a 3x3 board
- Clear game board rendering after each move
- Input validation for slot range and duplicates
- Announces winner or draw
- Uses simple Java logic without external libraries

---

## ▶️ How to Run

Make sure you have Java installed. Then follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/PrathmeshJoshi01/MiniProjects-JAVA.git
   cd MiniProjects-JAVA
````

2. **Compile the Java file**

   ```bash
   javac TikTacToe.java
   ```

3. **Run the game**

   ```bash
   java TikTacToe
   ```

---

## 🎯 Gameplay Instructions

* The board consists of slots numbered 1 to 9:

  ```
  |---|---|---|
  | 1 | 2 | 3 |
  |-----------|
  | 4 | 5 | 6 |
  |-----------|
  | 7 | 8 | 9 |
  |---|---|---|
  ```

* Player `X` starts first.

* On each turn, the player enters the number corresponding to the slot they want to mark.

* The game checks for a win or draw after each move.

* The first player to align 3 symbols in a row, column, or diagonal wins.

* If all slots are filled without a winner, it's a draw.

---

## 🛠️ Technologies Used

* Java 8 or above
* `Scanner` class for input
* Arrays for board logic

---

## 📦 Sample Output

```
Welcome to 3x3 Tic Tac Toe.
|---|---|---|
| 1 | 2 | 3 |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
X will play first. Enter a slot number to place X in:
```

(Players take turns and the game updates accordingly...)

```
Congratulations! X's have won! Thanks for playing.
```

or

```
It's a draw! Thanks for playing.
```



## 🙋‍♂️ Author

**Prathmesh Joshi**
Passionate Java developer | Open to feedback and contributions
📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/prathmesh-joshi01)

---

*If you liked this project, feel free to ⭐️ the repository and share it!*

