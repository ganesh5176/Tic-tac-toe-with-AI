# 🎮 Tic-Tac-Toe with AI Players 🤖

A Python implementation of Tic-Tac-Toe featuring multiple player types, including a smart AI using the minimax algorithm! 

## ✨ Features

- 👥 Multiple player types:
  - 🧑 Human player (you!)
  - 🎲 Random computer player
  - 🧠 Smart AI using minimax algorithm (unbeatable!)
- 📊 Score tracking and game state management
- 🔍 Input validation for correct moves
- ⚡ Optimised algorithm for quick AI decisions
## 🧩 How It Works

### 🔧 Player Classes
1. `Player` (base class)
2. `HumanPlayer` - Takes input from the user
3. `RandomComputerPlayer` - Makes random valid moves
4. `SmartComputerPlayer` - Uses minimax algorithm for optimal moves

### 🧠 Smart AI Implementation
The `SmartComputerPlayer` uses the **minimax algorithm**:
- 🤔 Recursively evaluates all possible moves
- 📈 Maximizes score when it's the AI's turn
- 📉 Minimizes score when it's the opponent's turn
- ⚡ Includes optimization for first move (random choice)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-ai.git
   cd tic-tac-toe-ai
Run the game:

bash
python tictactoe.py

💡 Customisation Options

Change the starting player by modifying initialisation
Adjust difficulty by choosing different player types

✏️ Modify the board display in the __str__ method

🤖 Understanding the AI
The minimax algorithm works by:
🌳 Building a game tree of all possible moves
🔄 Recursively evaluating each possible outcome
🏆 Assigning scores (+1 for win, -1 for loss, 0 for draw)
⬆️ Choosing the path with maximum gain/minimum loss


🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss.

📜 License
MIT - Feel free to use and modify!

Made with ❤️ by Ganesh | 🤖 AI-powered Tic-Tac-Toe | 🏆 Challenge the unbeatable minimax!

