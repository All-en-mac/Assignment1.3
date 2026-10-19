Step 1: Terminal Commands Record
Option A: For macOS and Linux (Bash / Zsh)
Open your terminal and run the following commands sequentially:

Bash
# 1. Create the main project folder and navigate into it
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders inside it
mkdir week-1 week-2 week-3

# 3. Create an index.html file inside each week folder
touch week-1/index.html week-2/index.html week-3/index.html

# 4. Open the project folder in VS Code
code .
Option B: For Windows (PowerShell)
Open PowerShell and run the following commands sequentially:

PowerShell
# 1. Create the main project folder and navigate into it
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders inside it
mkdir week-1, week-2, week-3

# 3. Create an index.html file inside each week folder
New-Item week-1/index.html, week-2/index.html, week-3/index.html -ItemType File

# 4. Open the project folder in VS Code
code .
Step 2: Practice Commands Reference (Step 5)
To fulfill the requirement of practicing navigation, renaming, and deleting via the terminal, use these quick reference commands:

Navigate into a folder: cd folder-name

Go back to the parent folder: cd ..

Rename a folder:

Mac/Linux: mv old-folder-name new-folder-name

Windows: Rename-Item old-folder-name new-folder-name

Delete a folder/file:

Mac/Linux: rm -rf folder-name (or rm file-name)

Windows: Remove-Item folder-name -Recurse (or Remove-Item file-name)

Submission Checklist
Record of Terminal Commands: Copy and paste the list of commands you typed into your terminal.

Screenshot of Final Folder Structure: Take a screenshot of your VS Code Explorer sidebar showing the web-development-practice folder containing week-1, week-2, and week-3, with their respective index.html files.