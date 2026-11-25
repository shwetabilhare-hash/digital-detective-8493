# Mission 2 - Become comfortable with the Terminal

## 1. Task / objective

Use the Terminal to inspect folders, create and manage practice files, understand flags and pipes, and explain what a package manager does.

## 2. Work completed

I practised basic Terminal commands, created a terminal-practice folder inside mission-02-terminal, created and copied files, added text to a file, made a backup, compared ls with ls -lah, used a pipe, and checked for Homebrew.

## 3. Commands / tools used

| Command | What it does | What I observed |
|---|---|---|
| pwd | Shows the full path of the folder I am in | It printed the path of my project folder |
| ls | Lists the files and folders here | It showed the mission folders and README.md |
| ls -l | Lists them in a detailed format | It showed permissions, size and date for each item |
| cd | Moves into another folder | My location changed to the folder I named |
| cd .. | Moves to the parent folder | My location moved one level up |
| mkdir | Creates a new folder | terminal-practice appeared in the listing |
| touch | Creates an empty file | notes.txt appeared and was empty |
| cp | Copies a file | A second file with the new name appeared |
| mv | Moves or renames a file | The copied file got a new name and the old name disappeared |
| cat | Shows what is inside a file | It printed both lines of text |
| echo with > and >> | Writes text into a file | > replaced the content and >> added a new line |
| head | Shows only the first few lines | It limited the output to 5 lines |
| brew | Package manager commands | See section 4 |

## 4. My understanding

**Replacing and adding text:** Using > replaces everything in a file, but >> adds text at the end and keeps the old lines.

**Copy and move:** Copying makes a second file and keeps the original. Moving changes the location or the name, so the original name is gone.

**Current directory:** pwd shows the exact folder I am working in, so I know where my commands will act.

**Directory listing:** ls helps me see what files and folders are in the current place before I change anything.

**Flags:** A flag changes how a command works. ls shows only names. ls -lah also shows details (l), hidden files (a) and sizes in easy units like KB and MB (h).

**Pipes:** The pipe symbol | takes the output of the command on its left and gives it to the command on its right. In ls -lah | head -n 5, the left side makes the list and the right side keeps only the first 5 lines.

**Package managers:** A package manager installs, updates and removes software from one place, so I don't have to download each program by hand. It also keeps track of what is installed.

Homebrew status: (keep ONE of these two lines and delete the other)
- Homebrew is installed on my Mac, and brew --version showed its version number.
- Homebrew is not installed on my Mac, so I did not install anything. I only explained what a package manager does.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Not applicable.

## 7. Evidence / files

- mission-02-terminal/terminal-practice/notes.txt
- mission-02-terminal/terminal-practice/notes-renamed.txt
- mission-02-terminal/terminal-practice/notes-backup-renamed.txt

## 8. Commit details

Commit message: "Complete Terminal and file management mission". The work was pushed to GitHub.