# Using the Command Line

The command line (also called terminal, shell, or command prompt) lets you control your computer by typing commands. Learning to use the command line is a key skill for anyone working with computers.

---

## What You Will Learn

- What a terminal is and why it’s useful
- Types of terminals: Bash, Command Prompt (CMD), PowerShell
- Basic commands for each terminal
- How to set and use the PATH variable

---

## Spend 3 Hours Exploring

Take up to three hours to explore and practice the following exercises. Try them on your own computer and write down what you learn.

---

### 1. Open the Terminal

- **Windows:**  
  - Open Command Prompt: Search for "cmd" in the Start menu.
  - Open PowerShell: Search for "PowerShell" in the Start menu.
- **Mac:**  
  - Open Terminal: Applications > Utilities > Terminal.
- **Linux:**  
  - Open Terminal: Usually found in Applications > System Tools, or press `Ctrl + Alt + T`.

---

### 2. Try Basic Commands

| Action                | Windows CMD / PowerShell | Mac/Linux (Bash) |
|-----------------------|--------------------------|------------------|
| Show current folder   | `cd` or `pwd`            | `pwd`            |
| List files/folders    | `dir`                    | `ls`             |
| Change folder         | `cd foldername`          | `cd foldername`  |
| Make new folder       | `mkdir test`             | `mkdir test`     |
| Remove file           | `del file.txt`           | `rm file.txt`    |
| Remove folder         | `rmdir test`             | `rm -r test`     |
| Clear screen          | `cls`                    | `clear`          |

**Exercise:**  
- Navigate to your Documents folder.
- Create a new folder called `practice`.
- Go into the `practice` folder.
- Create a new text file (try `echo Hello > hello.txt` or `touch hello.txt`).
- List the files in the folder.
- Delete the file and folder when done.

---

### 3. Script Exercise: Copy and Rename a File with Today’s Date

**Task:**  
Write a script that copies a file from `c:\source\data.json` to `c:\target\data_<yyyymmdd>.json`, where `<yyyymmdd>` is today’s date.

- **Windows (PowerShell):**
  ```powershell
  $date = Get-Date -Format "yyyyMMdd"
  Copy-Item "C:\source\data.json" "C:\target\data_$date.json"
  ```
- **Linux/Mac (Bash):**
  ```bash
  date=$(date +%Y%m%d)
  cp /source/data.json /target/data_$date.json
  ```

Try running the script and check if the file is copied and renamed correctly.

---

### 4. More Practice Exercises

- **Find all `.txt` files in a folder and list them.**
  - Windows: `dir *.txt`
  - Linux/Mac: `ls *.txt`
- **Display the contents of a file.**
  - Windows: `type filename.txt`
  - Linux/Mac: `cat filename.txt`
- **Search for a word in a file.**
  - Windows: `findstr word filename.txt`
  - Linux/Mac: `grep word filename.txt`
- **Check your current PATH variable.**
  - Windows: `echo %PATH%`
  - Linux/Mac: `echo $PATH`
- **Show running processes.**
  - Windows: `tasklist`
  - Linux/Mac: `ps` or `top`
- **Create a new empty file.**
  - Windows: `type nul > newfile.txt`
  - Linux/Mac: `touch newfile.txt`
- **Delete a file.**
  - Windows: `del newfile.txt`
  - Linux/Mac: `rm newfile.txt`

---

## Reflection

- What did you find easy or difficult about using the command line?
- Which commands did you find most useful?
- Write a short summary of what you