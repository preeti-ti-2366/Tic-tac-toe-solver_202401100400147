# Tic-tac-toe-solver_202401100400147
Problem Statement
This project implements an AI-powered Tic-Tac-Toe game where a human player competes against an unbeatable AI. The AI uses the Minimax Algorithm to make optimal moves, ensuring that it either wins or forces a draw.

🎯 Objective
Allow a human player (X) to play against an AI opponent (O).
The AI should always play optimally using the Minimax Algorithm.
Ensure that the game follows Tic-Tac-Toe rules and correctly detects wins/draws.
🛠 Approach
The AI determines the best possible move using the Minimax Algorithm, which works as follows:

Simulate all possible moves the AI can make.
For each move, predict the opponent’s best response.
Continue this process recursively until the game reaches a win, loss, or draw.
Assign a score to each outcome:
+1 if AI wins 🏆
-1 if AI loses ❌
0 if it's a draw 🤝
AI selects the move that maximizes its chances of winning while minimizing the opponent’s chances.
⚡ How to Run the Game
Clone this repository:
bash
Copy
Edit
git clone https://github.com/your-username/tic-tac-toe-minimax.git
cd tic-tac-toe-minimax
Run the Python script:
bash
Copy
Edit
python tic_tac_toe.py
Follow the on-screen instructions to play against the AI! 🎮
📸 Game Demo
markdown
Copy
Edit
 X | O | X  
-----------
 X | O |    
-----------
   |   |    
Player X's turn. Enter row and column (0-2): 
🧠 Why Minimax?
Guarantees the best move for the AI.
Evaluates all possible game states to make an informed decision.
Ensures the AI never loses, making it a perfect player.
🚀 Future Improvements
✅ Add Alpha-Beta Pruning to optimize the Minimax Algorithm.
✅ Implement a Graphical User Interface (GUI) using Tkinter or Pygame.
✅ Extend the game to support multiple difficulty levels.

