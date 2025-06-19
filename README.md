# Jeopardy-Game

This project implements a timed, interactive quiz game inspired by "Kaun Banega Crorepati" (KBC), built entirely in C for the terminal. 
The game reads questions from a file and presents them with four answer options, each accompanied by a countdown timer to keep the gameplay engaging and challenging.
Players must answer within the allotted time or risk timing out. They can also use lifelines such as 50/50 (which removes two wrong answers) or Skip the Question to strategically navigate through the quiz. 
The game features colorful terminal output using ANSI escape codes to improve readability and user experience.
Under the hood, the program handles raw terminal input by disabling line buffering and echo, allowing immediate response to user keystrokes. 
Signal handling is used to manage timeouts, and dynamic memory allocation loads the questions from an external text file. 
The program carefully manages lifeline usage and validates answers, tracking the player's winnings as they progress through increasingly difficult questions.
This project highlights working with file I/O, terminal control, signal handling, user input management, and simple game logic — all designed to run smoothly in a console environment with a nostalgic TV quiz show feel.
