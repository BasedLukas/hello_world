# Hello World Tutorial

## Description

Welcome to VibeArena! This tutorial teaches you how to use the coding challenge system.

### How to Access Your Coding Environment

When you click "Start Challenge", VibeArena creates an isolated coding environment with the challenge code pre-loaded. You have several ways to access it:

**Option 1: Cursor IDE (Recommended)**
Click the "Open in Cursor" button. Cursor will automatically SSH into the environment and open the project folder.

**Option 2: VS Code**
Copy the VS Code command shown and run it in your terminal. This opens VS Code with a remote SSH connection to your environment.

**Option 3: Terminal/SSH**
Copy the SSH command and run it in your terminal to access the environment directly via command line.

### Important Notes

- The `tests/` directory contains test files that verify your solution. **Do not modify these files.**
- Your solution will also be evaluated against hidden tests, so make sure your code handles edge cases correctly.
- Run `pytest` in the terminal to test your solution at any time.

### Your Task

Fix the syntax error in `hello.py` so that it prints "Hello, World!" to the console.

### Expected Output

When you run `python hello.py`, it should output:
```
Hello, World!
```

### How to Test

**Option 1: Use the Test Button (Recommended)**
Click the "Run Tests" button in the VibeArena UI. This runs the test suite and shows you the results directly in the browser.

**Option 2: Run Tests Manually**
Run the following command in your terminal:
```bash
pytest tests/
```

If all tests pass, your solution is correct!
