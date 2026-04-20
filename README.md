# ♟️ Unbeatable Tic-Tac-Toe

<div align="center">

![Tic-Tac-Toe Banner](https://img.shields.io/badge/Game-Tic--Tac--Toe-blueviolet?style=for-the-badge&logo=gamepad&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-68.1%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-19.8%25-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-12.1%25-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**A classic Tic-Tac-Toe game powered by the Minimax algorithm — challenge an unbeatable AI or play with a friend!**

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Play%20Now-brightgreen?style=for-the-badge)](https://yahskamrahs.github.io/Unbeatable-Tic-Tac-Toe/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/yahskamrahs/Unbeatable-Tic-Tac-Toe)

</div>

---

## 📸 Screenshots

> _Add your screenshots here by replacing the placeholders below._

| Home Screen | Gameplay | Game Over |
|:-----------:|:--------:|:---------:|
| ![Home](screenshots/home.png) | ![Gameplay](screenshots/gameplay.png) | ![Game Over](screenshots/gameover.png) |

---

## 🎮 About The Project

**Unbeatable Tic-Tac-Toe** is a browser-based implementation of the timeless Tic-Tac-Toe game. What sets it apart is the **AI bot powered by the Minimax algorithm** — an algorithm that explores every possible game state to make the optimal move every single time. No matter how hard you try, you **cannot beat the bot** — the best you can do is draw!

The project also includes a **2-player local mode**, so you can go head-to-head with a friend on the same device.

---

## ✨ Features

- 🤖 **Unbeatable AI Bot** — Powered by the Minimax algorithm; the bot plays perfectly every time
- 👥 **Two Game Modes** — Play vs Bot or Play vs Friend (local multiplayer)
- 🔄 **Play Again** — Instantly restart the game after it ends
- 🎨 **Clean UI** — Minimalistic and responsive design
- ⚡ **Zero Dependencies** — Pure HTML, CSS, and JavaScript; no frameworks needed
- 🌐 **Browser-Based** — No installation required; runs directly in the browser

---

## 🧠 How the AI Works

The bot uses the **Minimax Algorithm**, a classic decision-making algorithm used in two-player zero-sum games.

**Here's the core idea:**
- The algorithm recursively simulates **all possible future moves** for both the bot and the player.
- It assigns a score to each outcome: **+1 for a bot win**, **-1 for a player win**, and **0 for a draw**.
- The bot always picks the move with the **maximum score** (best outcome for itself), while assuming the player will pick the **minimum score** (worst outcome for the bot).
- This ensures the bot **never loses** — it always picks the mathematically optimal move.

```
Minimax(state, isMaximizing):
  if terminal state → return score
  if isMaximizing:
    return max over all moves of Minimax(next_state, false)
  else:
    return min over all moves of Minimax(next_state, true)
```

---

## 🚀 Getting Started

### Play Online
Click the badge below to play instantly — no setup required:

[![Play Now](https://img.shields.io/badge/▶%20Play%20Now-Live%20Demo-brightgreen?style=for-the-badge)](https://yahskamrahs.github.io/Unbeatable-Tic-Tac-Toe/)

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/yahskamrahs/Unbeatable-Tic-Tac-Toe.git

# 2. Navigate into the project folder
cd Unbeatable-Tic-Tac-Toe

# 3. Open in browser
open index.html
# or just double-click index.html in your file explorer
```

No build tools, no npm install — just open and play!

---

## 📁 Project Structure

```
Unbeatable-Tic-Tac-Toe/
├── index.html          # Main HTML structure
├── script/
│   └── script.js       # Game logic & Minimax AI
└── style/
    └── style.css       # Styling & layout
```

---

## 🕹️ How to Play

1. Open the game in your browser
2. Choose a mode:
   - **Play with Bot** — Face the unbeatable AI
   - **Play with Friend** — Challenge a friend on the same device
3. Players take turns clicking empty cells to place their mark (**X** or **O**)
4. The first to get **3 in a row** (horizontally, vertically, or diagonally) wins
5. If all cells are filled with no winner, it's a **Draw**
6. Click **Play Again** to start a new game

> ⚠️ **Challenge:** Try to beat the bot — spoiler: you can't! The best result is a draw.

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Game structure & layout |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling & responsive design |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Game logic, AI (Minimax), interactivity |

---

## 👨‍💻 Author

<div align="center">

**Akshay Kumar Sharma**

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-akshaykumarsharma.in-blue?style=for-the-badge)](https://akshaykumarsharma.in)
[![GitHub](https://img.shields.io/badge/GitHub-@yahskamrahs-black?style=for-the-badge&logo=github)](https://github.com/yahskamrahs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshaykumar-sharma-b803a6264/)

</div>

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ by [Akshay Kumar Sharma](https://akshaykumarsharma.in)

⭐ If you liked this project, consider giving it a **star** on GitHub!

</div>
