**Quantum Tic-Tac-Toe**

## Description

This project involves playing a game of Quantum Tic-Tac-Toe and creating a quantum algorithm to identify optimal decisions with the highest probability. Quantum Tic-Tac-Toe is a variation of the classic game where players use qubits to represent their moves. For more information about Quantum Tic-Tac-Toe, refer to [Wikipedia](https://en.wikipedia.org/wiki/Quantum_tic-tac-toe).

## Scenario and Rules

- You are the X's (crosses) in the game.
- The matrix represents qubits, where the state of O's (noughts) is |0> and the state of X's (crosses) is |1> (empty cells have an unknown state).
- The game layout is represented by a 3x3 matrix, and certain cells may be entangled, indicated by "e" followed by a number.
- To win, you need to get three X's in a row, column, or diagonal.

## Requirements

This project requires the following Python modules:

- qiskit
- BasicAer (from qiskit)
- plot_histogram (from qiskit.visualization)
- job_monitor (from qiskit.tools.monitor)

## Installation

To set up the project, make sure you have Python and pip installed. Then install the required packages by running:

```bash
pip install qiskit
```

## Usage

To play Quantum Tic-Tac-Toe, run the provided code in your Python environment. The code sets up the game layout and initial conditions, and it shows the table state inputted by the user, where "0" corresponds to player 1 (O's), "1" corresponds to player 2 (X's), and "e1", "e2", etc., represent entangled tiles.

## Game Layout

The initial conditions for the game are defined using the following lists:

- `l_player_2`: List of qubit cell numbers initialized to 0 (player 1 tiles).
- `l_player_1`: List of qubit cell numbers initialized to 1 (player 2 tiles).
- `l_entangled`: List of pairs of cells that need to be entangled to |01>+|10>.

## Contributing

If you'd like to contribute to this project, feel free to submit pull requests or report any issues you encounter.

