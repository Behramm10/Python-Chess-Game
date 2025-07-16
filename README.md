🤖♟️ Python Chess Game with AI (Pygame)
A single-player chess game built in Python using Pygame, where you can play against a basic AI opponent. The game features an interactive chessboard, legal move validation, move highlighting, and automated moves by the computer.

This project is a modification of a full-featured PvP chess system, redesigned for human vs computer gameplay.

📸 Preview
(Insert screenshots if available)

🎮 Features
🎯 Play against a basic AI (random-move based or rule-based)

♟️ All standard chess pieces and moves implemented

🔁 Turn-based: Player (White) vs AI (Black)

🟩 Highlighted valid moves for selected pieces

⚔️ Captures and king win detection

🧠 Modular design with Chess, AI, Utils, and Piece classes

💡 How the AI Works
The AI currently uses one of the following (depending on your implementation):
Random-move AI – selects randomly from all legal moves
(or)
Greedy AI – prioritizes capturing high-value pieces
(optional)
MiniMax (WIP) – for smarter, depth-based decision making (to be added)


📂 Project Structure
.
├── chess.py          
├── piece.py          
├── utils.py 
├── game.py
├── main.py           
└── README.md
├── res/
│   └── pieces.png
│   └── board.png
│   └── chess_icon.png


🕹️ Gameplay Instructions
🖱️ Use mouse to select and move pieces
🔲 Legal moves are highlighted (blue for white, green for black)
👑 Game ends when a king is captured
♟️ Supports special pawn logic: first double move, diagonal capture, en passant

👨‍💻 Author
Behramm Umrigar
GitHub: @behramm

📜 License
This project is open source and available under the MIT License.

