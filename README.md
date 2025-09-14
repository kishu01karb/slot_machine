# 🎰 Slot Machine Game

This project is a simple **Slot Machine simulation** built in Python.  
It demonstrates the use of **Python programming fundamentals**, including loops, conditionals, random number generation, and user interaction through a terminal-based interface.

---

## 📂 Project Structure
```
SLOTMACHINE.ipynb   # Main Jupyter Notebook with the game logic
README.md            # Project documentation
```

---

## 🚀 Features
- Interactive terminal-based **Slot Machine game**.
- Allows players to:
  - Set a bet amount.
  - Spin the slot machine reels.
  - Win or lose based on random symbol matches.
- Tracks balance and game progress.
- Simple and beginner-friendly Python project.

---

## 🛠 Tech Stack
- **Programming Language:** Python 🐍
- **Libraries Used:**
  - `random` - For randomizing slot symbols
  - `numpy` *(optional)* - For additional numeric operations
  - `jupyter` - Notebook environment for running the game

---

## 🎮 Game Rules
1. Deposit an initial balance to start the game.
2. Choose the **number of lines** to bet on.
3. Set the **bet amount per line**.
4. Spin the slot machine:
   - If matching symbols appear on a line, you **win**.
   - Otherwise, you **lose** the bet amount.
5. Game continues until you quit or your balance runs out.

---

## 📊 Workflow
1. **Import Libraries** – Load required Python modules.
2. **Define Game Symbols** – List of possible slot machine symbols.
3. **Player Input** – Get deposit, bet, and number of lines from the user.
4. **Spin Logic** – Randomly shuffle symbols to simulate a spin.
5. **Win Check** – Determine if the spin resulted in a win or loss.
6. **Update Balance** – Adjust balance based on game results.
7. **Loop Until Exit** – Allow the user to continue playing or quit.

---

## 📥 Installation
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/slot-machine-game.git
cd slot-machine-game
```

### **2. Create Virtual Environment** (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### **3. Install Dependencies**
There are no special dependencies for this project, but to run it in Jupyter Notebook:
```bash
pip install jupyter
```

---

## 🧪 Usage
To run the game in a notebook:
```bash
jupyter notebook
```
Then open `SLOTMACHINE.ipynb` and run the cells step-by-step.

---

## 🎨 Example Gameplay
```
Welcome to the Slot Machine Game!
Enter deposit amount: 100
Enter number of lines to bet on (1-3): 2
Enter bet amount per line: 5

Spinning reels...
🎲 | 🎲 | 🍒
🍒 | 🍒 | 🍒
🍋 | 🍒 | 🎲

You WON 20 credits!
Current balance: 115
```

---

## 📜 License
This project is licensed under the MIT License.  
Feel free to use and modify for fun or educational purposes.

---

## 👤 Author
- **Krishna Karbhari**
- GitHub: [kishu01karb](https://github.com/kishu01karb)

---

## 🌟 Acknowledgements
- Inspiration from classic casino slot machines.
- Python randomization and beginner-friendly coding tutorials.
