# Code Smells Kata

### Smelly Tic Tac Toe

We created a very smelly implementation of TicTacToe. There are quite a few code smells in the implementation: 

* Primitive obsession
* Feature envy
* Data class
* Message chain
* Long method
* Comments
* Long parameter list
* Shotgun surgery
* Duplicated code
* Large class
* Divergent change
* Data clump
* Lazy class

Start by identifying the smells and then slowly refactor the code. Remember to keep the tests passing at all times during the refactor. It's ok to revert back to a previous working state at any moment.

### Game Setup

- One board – 3 x 3 cells
- Two players - O & X:
  - Player One - X
  - Player Two - O
- Players take turns

### Game Rules

- Player One starts
- A mark can only be placed on an empty cell
- Game ends if …
  - board full, or
  - only one symbol in column, row or diagonal - this
 is a winning condition: owner of the symbol wins