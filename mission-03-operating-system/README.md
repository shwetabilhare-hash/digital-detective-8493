# Mission 3 - Understand the operating system

## 1. Task / objective

Explore the operating system, running processes, storage, paths and file permissions, and describe the responsibilities of an OS.

## 2. Work completed

I used Terminal to check system details, my account, storage and a snapshot of running activity. I looked at the process list, practised absolute and relative paths, and read the permissions of a file.

## 3. Commands / tools used

- sw_vers: shows the macOS name and version.
- uname -s: shows the kernel name.
- whoami: shows the active account.
- df -h: shows used and free storage in easy units.
- top -l 1 | head -n 10: shows a short snapshot of system activity.
- ps aux | head -n 5: shows the first few running processes.
- ls -l: shows permissions of a file.
- pwd and cd: show and change my current location.

## 4. My understanding

### Task 3.1 - System information

| Information explored | What it tells you | My observation (privacy-safe) |
|---|---|---|
| OS / system details | Which operating system and version the computer runs | macOS, version [write it from sw_vers] |
| Current account identity | Which user account is running the commands | [redacted] |
| Available and used storage | How much disk space is used and free | [write the Size, Used and Avail of the main disk from df -h] |
| System activity snapshot | How busy the CPU and memory are right now | [write one thing from top, e.g. number of processes or CPU usage] |

### Task 3.2 - Processes

- **What is a process?** A process is a program that is currently running.
- **What does the PID column represent?** PID is the process identifier, a unique number the OS gives each running process.
- **Two examples of processes on my computer:** [write two names from the ps output, e.g. a browser and a system process].

### Task 3.3 - Paths and permissions

- An **absolute path** starts from the top of the file system and gives the full location. Example: /Users/[redacted]/digital-detective-8493/mission-02-terminal
- A **relative path** starts from where I am now. Example: mission-02-terminal/terminal-practice
- When I moved between the project folder and a subfolder, pwd showed a longer or shorter path.
- Permissions of notes.txt: the owner part was rw-. So the owner can read and write the file but cannot execute it.

### Task 3.4 - OS responsibilities

| OS responsibility | My explanation | Example |
|---|---|---|
| Process management | Decides which programs run and when | Switching between a browser and a text editor |
| Memory management | Gives each program some RAM and takes it back after | A browser tab using more RAM when it loads a video |
| Device management | Lets programs use hardware through drivers | Printing a document or playing sound |
| File management | Stores, names and organises files and folders | Saving a document in a folder |
| User interface / shell | Lets me give instructions to the computer | The desktop, or the Terminal |
| Security and permissions | Controls who can read, change or run things | A file only the owner can edit |

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Not applicable.

## 7. Evidence / files

- mission-03-operating-system/README.md (observations with private details removed)

## 8. Commit details

Commit message: "Document operating system and file management". The work was pushed to GitHub.