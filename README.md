# MyPass — Password Manager 🔐

MyPass is a desktop password manager built with Python and Tkinter. It allows users to generate passwords, save website login details, and search for saved credentials through a simple graphical interface.

## Features

- Generate random passwords using letters, numbers, and symbols.
- Copy generated passwords to the clipboard.
- Save website names, email addresses or usernames, and passwords.
- Search for saved credentials by website name.
- Manage credentials through a desktop GUI.

## Built With

- Python
- Tkinter
- JSON for local data storage
- Pyperclip for clipboard functionality

## Getting Started

### Requirements

- Python 3
- `pyperclip`

Install the required package:

```bash
python3 -m pip install pyperclip
```

### Run the Application

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```bash
python3 main.py
```

## Project Structure

- `main.py` — contains the graphical interface, password generator, and credential management logic.
- `logo.png` — application logo.
- `.gitignore` — excludes local files such as saved password data and Python cache files.

## Security Note

This is a learning project. Saved credentials are currently stored in plain text in a local JSON file and are not encrypted. Do not use it to store real or sensitive passwords in its current form, and never commit your local credential file to GitHub.

## What I Learned

This project helped me practise Python functions, GUI development with Tkinter, JSON file handling, exception handling, random password generation, and clipboard integration.
