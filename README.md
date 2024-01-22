# Othello_AI

## Overview
This Othello_AI project showcases an Artificial Intelligence designed for the classic board game Othello. It leverages the Mini-Max Algorithm to strategize moves against human players or other AIs. The project is implemented in Java and Processing, offering a solid backend coupled with an engaging front-end interface.

## About The Mini-Max Algorithm
![Minimax Algorithm](https://upload.wikimedia.org/wikipedia/commons/6/6f/Minimax.svg)<br></br>
I have implemented an AI for my Othello game which, while not explicitly using the Minimax algorithm in its current form, follows a similar conceptual framework. The Minimax algorithm is crucial in game theory, especially for turn-based games like Othello. It works by simulating all possible moves and their consequences, along with the opponent's potential responses. In my game, the AI, through methods like greedy_arty(), evaluates the game board to determine the move that maximizes my advantage, considering factors such as maximizing the number of flipped pieces and minimizing the opponent's possible moves. The Minimax algorithm typically has an exponential time complexity, generally O(b^d), where 'b' is the branching factor, and 'd' is the depth of the tree, and its space complexity is O(bm), where 'm' is the maximum depth. However, these complexities can vary based on specific implementations, like the inclusion of alpha-beta pruning, which can significantly reduce the number of nodes explored. In my code, while a full-fledged Minimax approach with recursive future move simulation and alpha-beta pruning isn't yet integrated, the foundation laid out by the current AI's decision-making process paves the way for such an enhancement, potentially leading to a more sophisticated and efficient AI for my Othello game.

## Features
- **Mini-Max Algorithm**: Employs this algorithm for calculating optimal moves by evaluating different game outcomes.
- **Interactive Gameplay**: Users can enjoy an intuitive gameplay experience.
- **Adaptive AI Opponent**: Engage with an AI that dynamically adjusts its strategy as the game evolves.
<br></br>
![](https://github.com/kickereb/Othello_AI/blob/master/src/Othello_AI_MinMax%20(1).gif)<br></br>
## How to Play
1. **Installation**: Clone this repository and ensure Java and Processing are installed.
2. **Starting the Game**: Execute the main application file to launch the game.
3. **Gameplay**: Choose to play against the AI or observe an AI vs. AI match.
4. **Making Moves**: Interact with the game board via the user interface to place discs.

## Technologies Used
- **Java**: For core game logic and AI algorithm implementation.
- **Processing**: To create the graphical user interface.

## Getting Started
For a local setup, follow these steps:
1. Clone the repository:
```git clone https://github.com/kickereb/Othello_AI.git```
2. Navigate to the project directory, compile the Java files.
3. Run the main file to start the game.

## Contributions
Open-source contributions are highly encouraged and appreciated. To contribute:
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact
Evam Kaushik - evamkaushik@gmail.com  
Project Link: [https://github.com/kickereb/Othello_AI](https://github.com/kickereb/Othello_AI)
