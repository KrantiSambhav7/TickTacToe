# Tic-Tac-Toe

This project implements a simple **Tic-Tac-Toe** game in Java. It is a two-player game played on a 3x3 grid, where players take turns to mark their positions. The objective is to align three marks either horizontally, vertically, or diagonally before the opponent does.

---

## Features

- Two-player gameplay: `Player X` and `Player O`.
- Dynamic board updates after each move.
- Win detection for rows, columns, and diagonals.
- Input validation to prevent overwriting occupied positions.
- Clear and interactive terminal-based interface.

---

## How to Run the Game

### Prerequisites

- Ensure you have [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) installed.

### Steps

1. Copy the provided Java code into a file named `Main.java`.
2. Open a terminal or command prompt.
3. Compile the program using:
   ```bash
   javac Main.java
   ```
4. Run the program:
   ```bash
   java Main
   ```

---

## Gameplay Instructions

1. The game starts with Player `X`.
2. Players are prompted to enter the row and column indices (0-based) where they want to place their mark.
3. If the chosen cell is empty, the mark is placed, and the turn switches to the other player.
4. If a player aligns three of their marks horizontally, vertically, or diagonally, they win the game, and the program declares the winner.
5. If a player tries to overwrite an occupied cell, they will be prompted to retry.

---

## Example Output

```plaintext
  |   |  
  |   |  
  |   |  
Player X enter: 1 1

  |   |  
  | X |  
  |   |  
Player O enter: 0 0

O |   |  
  | X |  
  |   |  
...
Player X has won!
```

---

## Code Structure

- **Main Class**: Contains the game logic and flow.
- **Key Methods**:
  - `printBoard`: Prints the current state of the board.
  - `haveWon`: Checks if the current player has won.

---

## Future Enhancements

- Add a draw condition to detect when the board is full and no player has won.
- Include AI for single-player mode.
- Add a graphical user interface (GUI) for better usability.
- Expand the board size for customizable gameplay.

---

## License

This project is open-source and free to use under the MIT License.

---

## Contributions

Contributions are welcome! If you have ideas for improvements, feel free to fork the repository and create a pull request.

Thanks.

