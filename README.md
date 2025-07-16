# 🤖♟️ Python Chess Game with AI (Pygame)

A single-player chess game built using **Python** and **Pygame**, where you play against a basic AI.  
The game features a fully interactive chessboard, move validation, visual move hints, and computer-controlled opponents.

---

## 🎮 Features

- 🎯 **Play against a basic AI**.
- ♟️ **Standard chess rules** with legal move enforcement.
- 🔁 **Turn-based**: Player (White) vs AI (Black).
- 🟦 Highlighted **valid moves** (blue for White, green for Black).
- ⚔️ **Captures** and **king capture win condition**.
- 👣 **Special pawn rules**: first double-step, diagonal capture, en passant.
- 🧠 **Modular structure**:
  - Separate `Chess`, `AI`, `Utils`, and `Piece` classes for clean, maintainable code.

---

## 📂 Project Structure

```

├── main.py              # Entry point for the game
├── game.py              # Game loop and board logic
├── chess.py             # Chess rule engine
├── piece.py             # Piece behavior and rules
├── utils.py             # Helper functions (coordinates, highlighting, etc.)
├── res/
│   ├── pieces.png       # Sprite sheet for chess pieces
│   ├── board.png        # Chess board image
│   └── chess\_icon.png   # Window/icon image

````

---

## 🕹️ How to Play

- 🖱️ Click to select and move pieces.
- 🟦 Valid moves are shown in **blue** (your turn) or **green** (AI thinking).
- 👑 **Game ends when a king is captured**.
- ♟️ Supports:
  - Pawn's first-move **double-step**
  - **Diagonal captures**
  - **En passant**

---

## 🧱 Packaging the Game into a Standalone `.exe` (Windows)

You can convert this game into a Windows `.exe` using **PyInstaller**, so others can play it without installing Python or Pygame.

### ✅ Steps to Build `.exe`:

1. **Install PyInstaller**:

   ```bash
   pip install pyinstaller
    ````

2. **Navigate to your project folder**:

   ```bash
   cd path/to/your/project
   ```

3. **Build the executable**:

   ```bash
   pyinstaller --noconfirm --onefile --windowed --icon=res/chess_icon.png main.py
   ```

   * `--onefile`: Bundles everything into a single `.exe`
   * `--windowed`: Prevents opening a terminal window
   * `--icon`: (Optional) Sets a custom icon for the window

4. **Find your `.exe` in the `/dist` folder**:

   ```
   dist/
   └── main.exe
   ```
---

## 👨‍💻 Author

**Behramm Umrigar**
GitHub: [@behramm10](https://github.com/behramm10)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 💡 Future Improvements

* ♜ Implement AI with Minimax or Alpha-Beta pruning
* 💾 Add save/load functionality
* 🌐 Web version using Pygbag (Pygame in the browser)
* 🔊 Add sound effects and animations

---
