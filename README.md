# Password-Generator
A simple and user-friendly Python desktop application built with **Tkinter** for generating secure passwords with adjustable complexity. This tool is designed for quick password creation and includes password strength evaluation and history tracking.

## Features

- **Password Generation**: Users can generate passwords with custom length (between 4 and 64 characters) and select options to include:
  - Uppercase letters
  - Numbers
  - Special symbols (punctuation)
  
- **Password Strength Indicator**: The app evaluates password strength and displays it in real-time (Weak, Medium, or Strong).
  
- **Password History**: The last 5 generated passwords are stored and displayed. Users can click on any password in the history to copy it to the clipboard.

- **Clipboard Copy**: Easily copy the generated password to the clipboard with one click.

## Requirements

- Python 3.x
- `tkinter` library (usually included by default in Python installations)

## Installation

1. Clone or download this repository.
2. Make sure you have Python 3.x installed.
3. No additional dependencies are required, as the project uses the built-in `tkinter` library.
4. Run the script `password_generator.py` to start the application.

```bash
python password_generator.py
