# TicTacToe_Minimax_ALgorithm

The code you provided is an implementation of the Tic-Tac-Toe game using a minimax algorithm for the computer player. Here's a breakdown of how the code works:

1. The `initialize(board)` function is not used in the code. It initializes the player and pc variables but doesn't do anything with them.

2. The `print_board(board)` function is used to display the current state of the Tic-Tac-Toe board.

3. The `space_available(arr, i, j)` function is not used in the code.

4. The `checkspace(pos)` function checks whether a position on the board is available (i.e., not already occupied by 'X' or 'O').

5. The `check_X_win()` and `check_O_win()` functions check if either the player or the computer has won the game based on the current state of the board.

6. The `checkDraw()` function checks if the game has ended in a draw.

7. The `place_at_pos(var, pos)` function is used to place a player's move ('O') or a computer's move ('X') at the specified position on the board.

8. The `player_move()` function prompts the player to enter their move ('O') and calls `place_at_pos()` to place the move on the board.

9. The `pc_move()` function implements the minimax algorithm to determine the computer's move ('X'). It iterates over the available positions on the board, simulates each possible move, and assigns a score to each move based on the minimax algorithm. The computer then selects the move with the highest score and calls `place_at_pos()` to place the move on the board.

10. The `minimax(board, depth, isMaximizing)` function is the core of the minimax algorithm. It recursively evaluates the game state for each possible move, assigning a score to each leaf node (win, lose, or draw) and propagating the scores up the tree. The `isMaximizing` parameter indicates whether the current recursive call is for the maximizing player ('X') or the minimizing player ('O').

11. The `board` dictionary represents the current state of the Tic-Tac-Toe board, with keys 1 to 9 representing the positions on the board and values ' ', 'X', or 'O' indicating empty, occupied by the computer, or occupied by the player, respectively.

12. The code then executes a sequence of moves, alternating between the computer and the player, until the game is won, lost, or drawn.

Note that the code you provided is not properly indented, and the function calls at the end are not indented correctly either. To run the code, you should fix the indentation errors and make sure the functions are called in the correct order.
