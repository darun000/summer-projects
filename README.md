# Sem break Projects — Python Projects Portfolio

A collection of Python projects built to practice GUI development, game logic, and automation. The flagship project is a fully functional calculator app built with Kivy.

**Author:** Darun

---

##  Flagship Project: Calculator GUI

A functional calculator application built with Python and Kivy, featuring a clean graphical interface with real-time input and calculation support.

### Features
- **4x4 button grid** for digits (0–9), decimal point, and operators (`+`, `-`, `*`, `/`)
- **Live display label** that updates as buttons are pressed
- **Dynamic font resizing** so the display scales with the label's height
- **Expression evaluation** using Python's `eval()` for instant calculation
- **Error handling** for invalid expressions
- **Clear button** to reset and start fresh

### Tech Stack
- **Language:** Python
- **GUI Framework:** [Kivy](https://kivy.org/)

### How It Works
The app builds a vertical layout with an output label, a grid of buttons, and a clear button. Number/operator buttons append to the display text, the `=` button evaluates the expression using `eval()` wrapped in error handling, and the clear button resets the display. Font size adjusts dynamically based on label height.

### How to Run
```bash
pip install kivy
python calculator.py
```

 Folder: `Calculator_GUI`

---

## Other Projects in This Repo

### 🎡 Fidget Spinner Game
*(Folder: `Fidget_Spinner_game`)*
[1–2 line description — e.g. "An interactive fidget spinner simulation where users can click/drag to spin the wheel, built with Python."]

###  Rock Paper Scissors Game
*(Folder: `Rock_paper_scissors_game`)*
[1–2 line description — e.g. "A terminal-based Rock Paper Scissors game where the player competes against the computer, which selects randomly."]

###  Alarm Clock
*(Folder: `alarm-clock`)*
[1–2 line description — e.g. "A simple alarm clock application that takes a target time as input and plays a sound alert when reached."]

###  Story Generator
*(Folder: `story-generator`)*
[1–2 line description — e.g. "A Mad-Libs style story generator that creates randomized short stories based on user word input."]

---

## Tech Stack Summary
- **Language:** Python
- **Libraries used across projects:** Kivy, random, time (adjust based on what you actually used)

---

*Built as part of my Python learning journey — a mix of GUI, game logic, and automation projects.*
