# Mission 4 - How programs run

## 1. Task / objective

Run a simple Python program and compare how compilers and interpreters work.

## 2. Work completed

I created hello.py with a one-line program, ran it with Python 3 in Terminal, and the message "Hello from Python" appeared. I also compared a compiler and an interpreter.

## 3. Commands / tools used

- echo with >: created hello.py with one line of code.
- python3: runs the Python program.
- print(): the Python function that shows a message on the screen.

## 4. My understanding

| Point | Compiler | Interpreter |
|---|---|---|
| When translation / execution happens | Translates the whole program before it runs | Reads and runs the program line by line while it runs |
| Typical output | A separate ready-to-run file (machine code) | No separate file; the result appears directly |
| One example | GCC for the C language | The Python interpreter |
| One advantage | The finished program usually runs faster | It is easy to test small changes quickly |

A compiler translates the full source code first and creates a program that can run later. An interpreter carries out the instructions at runtime, as it reads them. Python is mostly run with an interpreter, which is why python3 hello.py showed the result right away. Real languages can mix both ideas.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Not applicable.

## 7. Evidence / files

- mission-04-programs/hello.py
- mission-04-programs/README.md

## 8. Commit details

Commit message: "Compare compilers and interpreters". The work was pushed to GitHub.