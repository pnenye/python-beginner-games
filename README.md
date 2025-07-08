# 🎮 Python GUI Beginner Projects with Tkinter

Welcome to your beginner Python GUI project pack! These two hands-on mini-games are designed to help you practice fundamental programming concepts while learning how to build desktop applications using `tkinter`.

---

## 📦 Included Projects

### 1. 🟢 Tic Tac Toe (Two-Player)

#### 📋 Project Brief

Build a two-player **Tic Tac Toe** game using Python and the `tkinter` GUI library. The game should allow two players to take turns marking X and O on a 3x3 grid. It should detect when a player wins or when the match ends in a draw.

🔗 Learn how Tic Tac Toe is played: [Wikipedia - Tic Tac Toe](https://en.wikipedia.org/wiki/Tic-tac-toe)

#### ✅ Requirements

- GUI built using `tkinter`
- 3x3 grid interface using buttons
- Alternate turns between Player X and Player O
- Detect and display the winner or a draw using a popup
- Include a “Restart” button to reset the game board

#### 🔐 Bonus Challenges

- Add player name input fields
- Highlight the winning combination
- Display a running score counter for multiple rounds

---

### 2. 🔵 Hangman (With Word File)

#### 📋 Project Brief

Create a **Hangman** game using Python and the `tkinter` GUI library. The game should load words from a file named `words.txt`, select one at random, and let the player guess one letter at a time. The player loses if they run out of allowed guesses before completing the word.

🔗 Learn how Hangman is played: [Wikipedia - Hangman (game)](<https://en.wikipedia.org/wiki/Hangman_(game)>)

#### ✅ Requirements

- GUI built using `tkinter`
- Load a list of words from `words.txt` (one word per line)
- Randomly choose one word at the start of the game
- Display:
  - The hidden word using underscores
  - An input field to guess one letter
  - Incorrect guesses
  - Remaining attempts
- Show a popup when the game is won or lost
- Include a “Restart” button to play again with a new word

#### 🔐 Bonus Challenges

- Draw a stick figure using `Canvas` to represent incorrect guesses
- Show all guessed letters on the screen
- Disable input when the game ends
- Add a prompt to play again

---

## 📁 File Structure Suggestion

```plaintext
python-beginner-games/
├── tic_tac_toe/
│   └── main.py
├── hangman/
│   ├── main.py
│   └── words.txt
└── README.md
```

---

## 🛠 Tools You’ll Use

- Python 3.x
- Tkinter (comes pre-installed with Python)
- Basic file handling (`open()`, `readlines()`)
- Messageboxes, Labels, Buttons, Entry fields

---

Good luck and have fun building! 🎉
