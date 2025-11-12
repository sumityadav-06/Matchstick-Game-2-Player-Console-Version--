🔥 Matchstick Game (2 Player Console Version)
A simple C language mini-project based on the classic 21 Matchsticks Game.
This project features Human vs AI (Computer) gameplay in the console, demonstrating logical thinking and structured programming in C.

🧩 Overview
The game starts with 21 matchsticks.

Each player can pick 1 to 4 matchsticks per turn.
The player forced to pick the last matchstick loses.
The computer uses a smart strategy (computer_pick = 5 - user_pick) to ensure a guaranteed win.

⚙️ Algorithm
Start the program.
Initialize total matchsticks = 21.
Display game rules.
Player takes the first turn (1–4 matchsticks).
Computer responds by picking (5 – player’s pick).
Repeat until no matchsticks remain.
The player who picks the last matchstick loses.
Display “Game Over”.
💻 Code Structure
displayRules() → Shows game rules.
displayMatchsticks() → Displays remaining sticks visually using “|”.
getUserPick() → Takes and validates user input.
main() → Controls game flow and AI logic.
🧠 Concepts Used
Loops (while loop) for game repetition
Conditional statements (if–else) for decision-making
Functions for modular programming
Variables to store picks and counts
Mathematical logic for computer’s winning strategy
Boolean control for continuous input validation
🕹️ Example Output
--- Welcome to the Matchstick Game! --- Total matchsticks: 21 You can pick 1, 2, 3, or 4 matchsticks. The player who picks the last matchstick loses.

Your turn: 3 You picked 3 matchsticks. Computer picks 2 matchsticks. Remaining sticks: 16 ... You picked the last matchstick — You Lose! --- Game Over ---

🎯 Applications
Great mini-project for college students
Helps in learning loops, functions, and conditionals
Demonstrates AI-based game logic
Enhances logical thinking and programming skills
🧾 Conclusion
The Matchstick Game demonstrates how simple logic and strategy can make a computer unbeatable.
It’s a fun and educational way to learn C programming, modular design, and algorithmic thinking.

⚙️ How to Compile & Run
On Windows (using GCC)
gcc matchstick_game.c -o matchstick_game
matchstick_game
gcc matchstick_game.c -o matchstick_game
./matchstick_game


---

Would you like me to add a **“Project Members”** section (with names, CRN, etc.) like your report?
